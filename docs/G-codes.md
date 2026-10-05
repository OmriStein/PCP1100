# Supported CNC G-Codes Reference for PathPilot | Tormach
The store will not work correctly when cookies are disabled.

Toggle Nav [![Tormach](https://tormach.com/media/logo/websites/2/Logo_Tormach_Solid-Icon_horizontal_White_100_Percent_Employee_Owned.png "Tormach")](https://tormach.com/ "Tormach")

*   **G00**: Rapid positioning
*   **G01**: Linear interpolation
*   **G02**: Clockwise circular interpolation
*   **G03**: Counter-clockwise circular interpolation
*   **G04**: Dwell
*   **G07**, **G08**: Diameter / radius mode

> **NOTE**: The Tormach 15L and Rapid Turn both use **G7** (X positions displayed in diameter values). **G8** is not used or supported in PathPilot.

*   **G10 L1**: Set tool table entry
*   **G10 L10**: Set tool table – calculated – workpiece
*   **G10 L11:** Set tool table – calculated – fixture
*   **G10 L2**: Set work offset origin
*   **G10 L20**: Set work offset origin – calculated
*   **G17, G18, G19**: Plane selection
*   **G20/G21**: Inch / millimeter unit
*   **G28**: Return home
*   **G28.1**: Reference axes
*   **G30**: Return home
*   **G33**: Spindle sync. motion (like threading)
*   **G33.1**: Rigid tapping
*   **G40**: Cancel cutter radius compensation
*   **G41/G42**: Start cutter radius compensation left / right
*   **G41.1**, **G42.1**: Dynamic Cutter Compensation
*   **G43**: Apply tool length offset
*   **G49**: Cancel tool length offset
*   **G53**: Move in absolute machine coordinate system
*   **G54**: Use fixture offset 1
*   **G55**: Use fixture offset 2
*   **G56-G58**: Use fixture offset 3, 4, 5
*   **G59**: Use fixture offset 6 / use general fixture number
*   **G61/G61.1**: Path control mode
*   **G64**: Path control with optional tolerance
*   **G73**: Canned cycle – peck drilling
*   **G76**: Multi-pass threading cycle
*   **G80**: Cancel motion mode (including canned cycles)
*   **G81**: Canned cycle – drilling
*   **G82**: Canned cycle – drilling with dwell
*   **G83**: Canned cycle – peck drilling
*   **G85**: Canned cycle – boring, no dwell, feed out
*   **G86**: Canned cycle – boring, spindle stop, rapid out
*   **G88**: Canned cycle – boring, spindle stop, manual out
*   **G89**: Canned cycle – boring, dwell, feed out
*   **G90**, **G90.1**: Absolute distance mode
*   **G91**,**G91.1**: Incremental distance mode
*   **G92**: Offset coordinates and set parameters
*   **G92.x**: Cancel **G92**, etc.
*   **G93**, **G94**, **G95**: Feed modes
*   **G96**, **G97**: **CSS**, RPM modes
*   **G98**: Initial level return / R-point level after canned cycles
# CNC G-Code Programming Overview and Reference | Tormach
![Loading...](https://tormach.com/static/version1790064994/frontend/Tormach/US/en_US/images/loader-1.gif)

Read the following sections as a G-code reference:

*   [Rapid Linear Motion (**G00**)](rapid-linear-motion-g00)
*   [Linear Motion at Feed Rate (**G01**)](linear-motion-at-feed-rate-g01)
*   [Arc at Feed Rate (**G02** and **G03**)](arc-at-feed-rate-g02-and-g03)
*   [Dwell (**G04**)](dwell-g04)
*   [Set Offsets (**G10**)](set-offsets-g10)
*   [Plane Selection (**G17**, **G18**, **G19**)](plane-selection-g17-g18-g19)
*   [Length Units (**G20** and **G21**)](length-units-g20-and-g21)
*   [Return to Predefined Position (**G28** and **G28.1**)](return-to-predefined-position-g28-and-g28-1)
*   [Return to Predefined Position (**G30** and **G30.1**)](return-to-predefined-position-g30-and-g30-1)
*   [Straight Probe (**G38.x**)](straight-probe-g38-x)
*   [Cutter Compensation (**G40**, **G41**, **G42**)](cutter-compensation-g40-g41-g42)
*   [Dynamic Cutter Compensation (**G41.1** and **G42.1**)](dynamic-cutter-compensation-g41-1-and-g42-1)
*   [Apply Tool Length Offset (**G43**)](apply-tool-length-offset-g43)
*   [Engrave Sequential Serial Number (**G47**)](engrave-sequential-serial-number-g47)
*   [Cancel Tool Length Compensation (**G49**)](cancel-tool-length-compensation-g49)
*   [Absolute Coordinates (**G53**)](absolute-coordinates-g53)
*   [Select Work Offset Coordinate System (**G54** to **G59.3**)](select-work-offset-coordinate-system-g54-to-g59-3)
*   [Set Exact Path Control Mode (**G61**)](set-exact-path-control-mode-g61)
*   [Set Blended Path Control Mode (**G64**)](set-blended-path-control-mode-g64)
*   [Distance Mode (**G90** and **G91**)](distance-mode-g90-and-g91)
*   [Arc Distance Mode (**G90.1** and **G91.1**)](arc-distance-mode-g90-1-and-g91-1)
*   [Temporary Work Offsets (**G92**, **G92.1**, **G92.2**, and **G92.3**)](temporary-work-offsets-g92-g92-1-g92-2-and-g92-3)
*   [Feed Rate Mode (**G93**, **G94**, and **G95**)](feed-rate-mode-g93-g94-and-g95)
*   [Spindle Control Mode (**G96** and **G97**)](spindle-control-mode-g96-and-g97)

ABOUT THE EXAMPLES USED
-----------------------

Many commands require axis words (X~, Y~ ,Z~, or A~) as an argument. Unless explicitly stated otherwise, you can make the following assumptions:

*   Axis words specify a destination point
*   Axis words relate to the currently active coordinate system, unless explicitly described as being in the absolute coordinate system
*   Where axis words are optional, any omitted axes retain their current value

Any items in the command examples not explicitly described as optional are required.

