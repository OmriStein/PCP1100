# G/M Code Lists: Post vs. Tormach Docs

## List 1: In the post, not in the Tormach docs

These codes are defined or printed by `Tormach PCNC1100 Series 3.SRC` but are not listed in the Tormach PathPilot docs, so they are probably unsupported.

- **G:** G50, G54.1 P..
- **M:** (none)

(M13, M14, M20, M21, the duplicate M50 `M_COOL_THRU`, and G110–G129 (`G_WORK_7..26`) removed from the `.SRC` 2026-09-29; re-post matched ground truth. M_COOL_THRU is still M51.)

(G74 REVERSE_TAP and G87 BACK_BORE removed from `CALC_INIT_GCODES` 2026-09-29 —
not selected by any ground-truth job and not worth registering. G84 kept:
confirmed supported by PathPilot docs as the Tapping Cycle.)

## List 2: In the Tormach docs, not in the post

These codes are supported by PathPilot and relevant to the PCNC1100, but the post never uses them.

- **G:** G10 L1, G10 L2, G10 L10, G10 L11, G10 L20, G28.1, G30.1, G38.x, G41.1, G42.1, G43.1, G47, G59.1–G59.3, G61, G61.1, G90.1, G92.1–G92.3
- **M:** M44–M49, M52, M53, M59, M61, M70–M73, M83, M100–M199, M301–M303, M400, M401, M740, M998
