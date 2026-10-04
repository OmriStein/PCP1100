# Post processor test list

Post one small part per item and compare the G-code with the OG post.

## Verified

Facing, pocket roughing and finishing, contour (absolute and incremental), lace, profiling, countersink, thread milling, G37 Yes/No, G54/G55, all drilling operations (G81, G82, G83, G73, G84, G85, G89, back boring warning, fine boring, counterbore, hole patterns, G98).

## Still to test

### Milling operations

| # | Operation | What it is |
|---|---|---|
| 1 | Profiling with machine compensation | Contour with G41/G42 and a D offset. Controller compensation, high risk. |
| 2 | Slice cut | 3D toolpath cut in horizontal slices. |
| 3 | Rough cut | 3D roughing. |
| 4 | Curve cut | Tool follows a curve in 3D. |
| 5 | Topo cut | 3D finishing over a surface. |
| 6 | Freeform cut | 3D finishing over freeform surfaces. |
| 7 | Pencil cut | Cleans up corners and fillets left by earlier cuts. |
| 8 | UV cut | Multiaxis, which a 3-axis PathPilot can't run. Decide whether to delete it. |

### Global features

| # | Feature | What it is |
|---|---|---|
| 9 | Work offsets G56-G59, G59.1-G59.3 | Check each code posts, plus one program with two setups on different offsets. |
| 10 | Coolant types | Mist, through-tool and off, not just flood. |
| 11 | G37 on later tool changes | Tool length probe after the second and later M6, Yes and No. |
| 12 | Post Program Stop | Tape output option, on and off. |
| 13 | M1 and M2/M30 | Optional stop and program end. |
| 14 | Safety block | Program with no coolant and no tool offset. |
| 15 | Arcs | G2/G3 on XZ and YZ planes, helical arcs, full 360 circles. |
| 16 | Feed type | G95 feed per revolution or inverse time. Only if you plan to use them. |
| 17 | Incremental on milling | Profiling, pocket and 3D operations. Contour already passed. |

## Not tested, and why

- **Misc milling:** no CAMWorks operation posted as `MILL_MISC`, and the post treats it like a pocket.
- **Display tool offset (profiling):** display setting in CAMWorks only, no effect on G-code.
- **Reverse tapping:** removed, PathPilot doesn't support it.
- **Incremental on drilling:** option hidden, drilling is always absolute.
