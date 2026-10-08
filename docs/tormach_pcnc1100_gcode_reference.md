# Tormach PCNC 1100 Series 3 - PathPilot G-Code Reference

This document contains the comprehensive list of G-codes supported by the Tormach PathPilot Controller for the PCNC 1100 Series 3 mill, integrated with critical deviations from the standard Fanuc formatting.

---
## Complete Supported G-Code List

### Motion and Positioning
* ~~**G00**: Rapid linear positioning.~~
* ~~G01**: Linear interpolation at programmed feed rate.~~
* ~~**G02**: Clockwise circular or helical interpolation.~~
* ~~**G03**: Counter-clockwise circular or helical interpolation.~~
* ~~**G04**: Dwell (pauses the machine for a specified time duration).~~
* **G28 / G28.1**: Return to machine home predefined position / Reference specific machine axes.
* ~~**G30 / G30.1**: Return to secondary predefined position (often used for tool changes).~~
* **G33**: Spindle-synchronized motion.
* **G33.1**: Rigid tapping.
* **G53**: Move in absolute machine coordinates (ignores work coordinate offsets).

### Work Offsets & Coordinate Systems
* **G10 L1**: Set tool table entry values.
* **G10 L2**: Set work offset origin coordinate values.
* **G10 L10**: Set tool table via calculated workpiece positioning.
* **G10 L11**: Set tool table via calculated fixture positioning.
* **G10 L20**: Set work offset origin via calculated system measurements.
~~* **G54 to G59**: Primary work offset coordinate systems (1 through 6).~~
* **G59.1, G59.2, G59.3**: Additional work offset systems (7 through 9). 
* **G92**: Temporary work coordinate system offsets.
* **G92.1**: Reset temporary G92 work offsets to zero.
* **G92.2**: Pause G92 offsets without clearing the parameters.
* **G92.3**: Resume paused G92 offsets.

### Setups, Planes, & Units
* ~~**G17**: Select XY plane for circular interpolation and cutter compensation.~~
* ~~**G18**: Select XZ plane.~~
* ~~**G19**: Select YZ plane.~~
* ~~**G20**: Set units to inches.~~
* ~~**G21**: Set units to millimeters.~~
* ~~**G37 / G37.1**: Automatically measure tool lengths using an Electronic Tool Setter (ETS).~~
* **G50**: Cancel coordinate system rotation (Note: PathPilot uses this exclusively for rotation cancellation, not scaling).

### Probing & Specialty Cycles
* **G38.2**: Straight probe toward workpiece (stops on contact, signals error if it misses).
* **G38.3**: Straight probe toward workpiece (stops on contact without signaling an error if it misses).
* **G38.4**: Straight probe away from workpiece (stops when contact is broken, errors if no contact broken).
* **G38.5**: Straight probe away from workpiece (stops when contact is broken without error codes).
* **G47**: Engrave sequential serial numbers or text strings.

### Tool Offsets & Cutter Compensation
* ~~**G40**: Cancel cutter radius compensation.~~
* ~~**G41 / G42**: Enable cutter radius compensation (Left / Right side of programmed path).~~
* ~~**G41.1 / G42.1**: Dynamic cutter radius compensation.~~
* ~~**G43**: Apply tool length offset (positive direction compensation).~~
* ~~**G49**: Cancel tool length offset compensation.~~
### Path Control & Modes
* **G61**: Set exact path control mode (stops precisely at the end of each motion vector).
* ~~**G64**: Set blended path control mode (maintains continuous velocity rounding corners based on tolerance parameters).~~
* ~~**G90**: Absolute distance mode positioning.~~
* ~~**G91**: Incremental distance mode positioning.~~
* **G90.1**: Absolute distance mode for arc centers (I, J, K coordinates).
* **G91.1**: Incremental distance mode for arc centers (I, J, K coordinates).

### Speeds and Feeds
* ~~**G93**: Inverse time feed rate mode.~~
* ~~**G94**: Units per minute feed rate mode (Inches or Millimeters per minute).~~
* **G95**: Units per revolution feed rate mode.
* **G96**: Constant surface speed (CSS) control.
* **G97**: Constant spindle speed control (RPM mode).

### Canned Cycles (Drilling & Boring)
* ~~**G73**: High-speed peck drilling cycle (breaks chips without fully retracting out of the hole).~~
* ~~**G80**: Cancel active canned cycle motion.~~
* ~~**G81**: Standard drilling cycle.~~
* ~~**G82**: Drilling cycle with a programmed dwell at the bottom of the hole.~~
* ~~**G83**: Deep hole peck drilling cycle (fully retracts to clear chips).~~
* ~~**G84**: Standard right-hand tapping cycle.~~
* ~~**G85**: Boring cycle (feeds down, feeds back up out of the hole).~~
* ~~**G86**: Boring cycle (feeds down, stops spindle, rapid retracts out).~~
* ~~**G88**: Boring cycle (feeds down, dwells, manual retract option).~~
* ~~**G89**: Boring cycle (feeds down, dwells, feeds back up out).~~
* ~~**G98**: Initial level return after completing a canned cycle step.~~
* ~~**G99**: R-plane (retract clearance plane) return after completing a canned cycle step.~~
