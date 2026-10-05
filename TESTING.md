# Post processor test list

Post one small part per item and compare the G-code with the OG post.

## Verified

Facing, pocket roughing and finishing, contour (absolute and incremental), lace, profiling, profiling with machine compensation (G41/G42 with D = tool number), countersink, thread milling, G37 Yes/No, G54-G59 and G59.1-G59.3 work offsets, coolant types, program stop and optional stop (with and without a tool change after, operation comment on the stop line), M30 program end, safety block, XY arcs (G2/G3) and helical arcs, all drilling operations (G81, G82, G83, G73, G84, G85, G89, back boring warning, fine boring, counterbore, hole patterns, G98).

## Still to test

### Milling operations

| # | Operation | What it is |
|---|---|---|
| 1 | Slice cut | 3D toolpath cut in horizontal slices. |
| 2 | Rough cut | 3D roughing. |
| 3 | Curve cut | Tool follows a curve in 3D. |
| 4 | Topo cut | 3D finishing over a surface. |
| 5 | Freeform cut | 3D finishing over freeform surfaces. |
| 6 | Pencil cut | Cleans up corners and fillets left by earlier cuts. |

### Global features

| # | Feature | What it is |
|---|---|---|
| 7 | Arcs in XZ and YZ planes | Post only outputs I and J with no G18/G19, so these would post wrong. Needs a decision, only matters for 3D operations. |
| 8 | Feed type | G95 feed per revolution or inverse time. Only if you plan to use them. |
| 9 | Incremental on milling | Profiling, pocket and 3D operations. Contour already passed. |

## Not tested, and why

- **Misc milling:** no CAMWorks operation posted as `MILL_MISC`, and the post treats it like a pocket.
- **Display tool offset (profiling):** option removed, it had no effect on the G-code.
- **UV cut:** multiaxis, removed from the post, PathPilot 3-axis can't run it.
- **Reverse tapping:** removed, PathPilot doesn't support it.
- **Incremental on drilling:** option hidden, drilling is always absolute.
