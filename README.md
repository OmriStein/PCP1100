# CAMWorks post processor for Tormach PCNC 1100 Series 3 (PathPilot)

A CAMWorks post processor that outputs G-code for the Tormach PCNC 1100 Series 3 running PathPilot. 3-axis milling and drilling, metric or imperial.

## Files

| File | Purpose |
|---|---|
| `Tormach PCNC1100 Series 3.SRC` | Main post file: options, operation setup, program start/end. |
| `Tormach PCNC1100 Series 3.LIB` | Machine-specific macros. |
| `MILL.LIB` | Milling and drilling operation macros. |
| `Tormach PCNC1100 Series 3.kin` | Machine kinematics. |

Keep all four post files in the same folder.

## Included and tested

Each item was posted from a test part and checked against the G-code.

- **Milling:** facing, pocket roughing and finishing, contour (absolute and incremental), lace, profiling, countersink, thread milling.
- **Cutter compensation:** G41/G42 with D = tool number.
- **Arcs:** XY arcs (G2/G3) and helical arcs.
- **Drilling:** G81, G82, G83, G73, G84, G85, G89, back boring warning, fine boring, counterbore, hole patterns, G98.
- **Work offsets:** G54-G59 and G59.1-G59.3.
- **Coolant:** all coolant types.
- **Program control:** program stop (M0) and optional stop (M1), with or without a tool change after, with the operation comment on the stop line. M30 program end.
- **Safety block** at program start: one line that cancels anything left over from the previous program and sets a known state: `G17 G40 G49 G50 G54 G64 G80 G90 G91.1 G94` (XY plane, cutter comp off, tool length offset off, scaling off, work offset, path blending, canned cycles off, absolute mode, arc centers incremental, feed per minute). The work offset in it follows the one chosen in the operation (G54-G59, G59.1-G59.3).
- **Units** are set automatically on the line after the safety block: G21 if the part is metric, G20 if it is imperial. 
- **Optional ETS tool-length probe (G37):** setting "Measure Tool Length" on the Machine Posting tab, No/Yes, default No. When Yes, the post adds `G37` right after each tool change (`M6 T.. G43 H..`) so PathPilot measures the new tool with the ETS and sets its length offset before cutting. It also writes a tool list to a separate .set file (M6/G43/G37 per tool) for a measuring-only run.

## Included but not tested

- **3D operations:** slice cut, rough cut, curve cut, topo cut, freeform cut, pencil cut. The CAMWorks version used for testing has no full 3D toolpaths.
- **Arcs in XZ and YZ planes:** the post outputs only I and J, with no G18/G19, so these would post wrong. Matters only for 3D toolpaths.
- **Incremental mode on milling:** only contour was tested. Profiling and pocket were not.
- **Feed type:** G95 (feed per revolution) and inverse time.
- **Misc milling:** CAMWorks' catch-all operation type for milling that doesn't fit the other types (face, pocket, contour and so on). The post handles it like a pocket.

## Not supported

- **UV cut** and other multiaxis operations: PathPilot 3-axis can't run them.
- **Reverse tapping:** PathPilot doesn't support it.

## Use

These are source files. They must be compiled before CAMWorks can use them.

1. Compile `Tormach PCNC1100 Series 3.SRC` with Universal Post Generator 2 (UPG-2).
2. Compiling produces three files: `.ctl`, `.kin` and `.lng`. Put all three where CAMWorks looks for posts and select **Tormach PCNC1100 Series 3**.
3. you can add a Tormach PCNC1100 Series 3.PINF file to set the default posting extension, just put these lines in:  
`PostName = Tormach PCNC1100 Series 3
PostExtension = nc
`

A compiled post (`.ctl`, `.kin`, `.lng`) is available in the `post` folder.
