# Supported CNC M-Codes Reference for PathPilot | Tormach
The store will not work correctly when cookies are disabled.

Toggle Nav [![Tormach](https://tormach.com/media/logo/websites/2/Logo_Tormach_Solid-Icon_horizontal_White_100_Percent_Employee_Owned.png "Tormach")](https://tormach.com/ "Tormach")



*   **M00**: Program stop
*   **M01**: Optional program stop
*   **M02**: Program end
*   **M03/M04**: Rotate spindle clockwise/counterclockwise
*   **M05**: Stop spindle rotation
*   **M06**: Tool change
*   **M07/M08**: Coolant on
*   **M09**: All coolant off
*   **M10/M11**: Unclamp/clamp automatic collet closer (8L,15L) / Dust shoe/open-close collet (24R)
*   **M19**: Orient spindle
*   **M27/M28**: Dust Shoe (24R)
*   **M29**: Axis unwind
*   **M30**: Program end and rewind
*   **M44/M45**: Probe on-off
*   **M46/M47**: ETS on-off
*   **M48**: Enable speed and feed override
*   **M49**: Disable speed and feed override
*   **M50**: Feed override control
*   **M51**: Spindle override control
*   **M52**: Adaptive feed control
*   **M53**: Feed stop control
*   **M59**: Smoothing
*   **M60**: Pallet change pause
*   **M61**: Set tool number
*   **M64**: Activate output relays
*   **M65**: Deactivate output relays
*   **M66**: Wait on an input
*   **M67/M68**: Analog output control

> **NOTE**: **M64** through **M66** is only useful with a USB M-Code I/O Interface Kit (PN 32616).

*   **M70**: Save Modal State
*   **M71**: Invalidate stored modal state
*   **M72**: Restore modal state
*   **M73**: Save autostore modal state
*   **M83**: Clear remap start line
*   **M98**: Call subroutine
*   **M99**: Return from subroutine/repeat
*   **M101-M109**: User Defined M-Codes
*   **M101-M199**: User Defined M-Codes
*   **M207**: TSC on
*   **M208**: Washdown pump on(1500MX) / Cut height(1300PL)
*   **M209**: All aux coolant off
*   **M210**: TSC off(1500MX) / THC volts(1300PL)
*   **M231/M233**: Chip conveyor on/off
*   **M301/M302**: Video recording start/stop
*   **M303**: Take picture
*   **M400/M401**: G-Code flag clear/set
*   **M740**: Program stop callback
*   **M998**: Alias for G30