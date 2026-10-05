# Programming - PCNC 1100 | Tormach Knowledge Base
In This Section, You'll Learn:
------------------------------

About the languages that are understood and interpreted by PathPilot.

### Before You Begin

*   Referring to This Section Use this section only for reference. To learn about the principles of the control language (so that you can write programs by hand from first principles, for example), we recommend that you consult an introductory textbook on G-code programming.
    
*   Creating and Editing G-Code Files We recommend using a text editor like Gedit or Notepad++. Don't use a word processor to create or edit G-code files — it'll leave unseen codes that could cause problems or prevent a G-code file from working.
    

Programming Overview
--------------------

Read the following sections for a G-code overview:

### About G-Code Programming Language

A G-code program is made up of one or more lines of code. Each line of code is called a block, and can include commands to the machine. Blocks are collected into a file, which makes a program.

A block is normally made up of an optional line number at the beginning, followed by one or more words, which groups the elements together into a single statement.

A word is a letter followed by a number (or, something that evaluates to a number). A word can either give a command or provide an argument to a command.

A program is one or more blocks, each separated by a line break. Blocks in a program are executed either:

*   Sequentially (from the top of the program to the bottom)
    
*   Until an end command (M02 or M30) is encountered
    

**Example:**  
G01 X3 is a valid line of code with two words:

*   G01 is a command: the machine should move in a straight line at the programmed feed rate.
    
*   X3 provides an argument value: the value of X should be 3 at the end of the move.
    

Most commands start with either G (general) or M (miscellaneous) — G-codes and M-codes.

There are two commands (M02 and M30) that end a program. A program can end before the end of a file. If there are lines in a file after the end of a program, they're not meant to be executed in the normal flow (they're generally parts of subroutines).

### G-Code Formatting Reference

A permissible block of input code is made up of the following programming elements, in order, with the restriction that there is a maximum of 256 characters allowed on a line:

1.  (Optional) Block delete character (/)
    
2.  (Optional) Line number
    
3.  Any number of words, parameter settings, and comments
    
4.  End of line marker (carriage return or line break)
    

Programs are limited to 999,999 lines of code.

Spaces and tabs are allowed anywhere on a line of code and do not change the meaning of the line, except inside comments. Blank lines are allowed in the input, but they're ignored. Input is not case sensitive (except in comments), so any letter outside a comment may be in uppercase or lowercase without changing the meaning of a line.

**Example**  
G00 x +0. 12 34y 7 is equal to G00 x+0.1234 y7

A line may have:

*   Any number of G words, but two G words from the same modal group may not appear on the same line.
    
*   Zero to four M words, but two M words from the same modal group may not appear on the same line.
    
*   For all other legal letters, a line may have only one word beginning with that letter.
    

Any input not explicitly allowed is illegal, and causes the interpreter to either signal an error or ignore the line.

PathPilot omits blocks of code that are prefixed with a block delete character (/).

PathPilot sometimes ignores things it doesn't understand. If a command doesn't work as expected, or does nothing, make sure that it's correctly typed. PathPilot doesn't check for excessively high machining feeds or speeds, and it doesn't detect situations where a legal command will do something unfortunate (like machining a fixture).

**Line Numbers**

A line number is indicated by the following, in the order listed:

1.  The letter N
    
2.  An integer (with no sign) between 0 and 99,999,999 (which must be written without commas)
    

Line numbers may be repeated, or used out of order, but that's rare in normal practice. A line number isn't required, and is often omitted.

**Words**

A word is indicated by the following, in the order listed:

1.  A letter other than N or O
    
2.  A real value
    

**Letters**

Words may begin with any of the following letters, except N or O:

**NOTE: Several letters (I, J, K, L, P and R) may have different meanings in different contexts.**



*          Letter        :          A        
  *          Description        :          A-axis        
*          Letter        :          B        
  *          Description        :          B-axis        
*          Letter        :          C        
  *          Description        :          C-axis        
*          Letter        :          D        
  *          Description        :          Tool radius compensation number        
*          Letter        :          F        
  *          Description        :          Feed rate        
*          Letter        :          G        
  *          Description        :          General function        
*          Letter        :          H        
  *          Description        :          Tool length offset index        
*          Letter        :          I        
  *          Description        :          X-axis offset for arcs        
*          Letter        :          J        
  *          Description        :          Y-axis offset for arcs        
*          Letter        :          K        
  *          Description        :          Z-axis offset for arcs        
*          Letter        :          L        
  *          Description        :          Number of repetitions in canned cycles and subroutines, or key used with G10        
*          Letter        :          M        
  *          Description        :          Miscellaneous function        
*          Letter        :          N        
  *          Description        :          Line number        
*          Letter        :          O        
  *          Description        :          Subroutine label number        
*          Letter        :          P        
  *          Description        :          Dwell time in canned cycles, dwell time with G04, key used with G10, or tapping depth in M871 through M874        
*          Letter        :          Q        
  *          Description        :          Feed increment in a G83 canned cycle, or repetitions of subroutine call        
*          Letter        :          R        
  *          Description        :          Arc radius, or canned cycle retract level        
*          Letter        :          S        
  *          Description        :          Spindle speed        
*          Letter        :          T        
  *          Description        :          Tool selection        
*          Letter        :          U        
  *          Description        :          Synonymous with A        
*          Letter        :          V        
  *          Description        :          Synonymous with B        
*          Letter        :          W        
  *          Description        :          Synonymous with C        
*          Letter        :          X        
  *          Description        :          X-axis        
*          Letter        :          Y        
  *          Description        :          Y-axis        
*          Letter        :          Z        
  *          Description        :          Z-axis        


**Values**

A real value is one of the following:

*   An explicit number (like 341, or -0.8807)
    
*   An expression (like \[2+2.4\])
    
*   A parameter value (like #88)
    
*   A unary operation value (like acos\[0\])
    

**NOTE: In the command examples that we use, the tilde symbol (~) stands for a real value. If L~ is written in an example, the ~ is often referred to as the L number. Similarly the ~ in H~ may be called the H number, and so on for any other letter.**

A number is a subset of a real value. Processing a real value to come up with a number is called evaluating. An explicit number evaluates to itself.

Explicit numbers have the following rules (in this case, a digit is a single character, 0 through 9):

*   A number must consist of the following, in the order listed:
    
    *   An optional plus or minus sign
        
    *   Zero to many digits
        
    *   (Optional) One decimal point
        
    *   Zero to many digits
        
*   There must be at least one digit somewhere in the number.
    
*   It must be either an integer (no decimal point) or a decimals (decimal point).
    
*   It may have any number of digits (subject to line length limitations).
    

**NOTE:  PathPilot only keeps 17 significant figures, which is enough for all known applications.**

*   A non-zero number with no sign as the first character is assumed to be positive.
    

Initial zeros (a zero before the decimal point and the first non-zero digit) and trailing zeros (a zero after the decimal point and the last non-zero digit) are allowed, but not required. A number written with initial or trailing zeros has the same value when it is read as if the extra zeros were not there.

Numbers used for specific purposes by PathPilot are often restricted to some finite set of values, or to some range of values. In many uses, decimal numbers must be close enough to an integer to be accepted as a valid input. A decimal number which is supposed to be close to an integer is considered close enough if it is within 0.0001 of an integer.

**Order of Execution**

If a parameter setting of the same parameter is repeated on a line (like #3=15 #3=6), only the last setting takes effect. It's illogical, but not illegal, to set the same parameter twice on the same line.

The order of items on a line doesn't determine the order of execution on the commands.

Three types of items' order may vary on a line (as given earlier in this section):

*   **Word** May be reordered in any way without changing the meaning of the line.
    
*   **Parameter Setting** If it's reordered, there is no change in the meaning of the line unless the same parameter is set more than once. In this case, only the last setting of the parameter takes effect.
    

**Example**  
When the line #3=15 #3=6 is interpreted, the value of parameter 3 is 6. If the order is reversed to #3=6 #3=15 and the line is interpreted, the value of parameter 3 is 15.

*   **Comment** If it contains more than one comment and is reordered, only the last comment is used. If each group is kept in order or reordered without changing the meaning of the line, then the three groups may be interleaved in any way without changing the meaning of the line.
    

**Example**  
G40 G01 #3=15 (foo) #4=-7.0 has five items and means exactly the same thing in any of the 120 possible orders, like #4=-7.0 G01 #3=15 G40 (foo), for the five items.

The order of execution of items on a line is critical to safe and effective machine operation. If items occur on the same line, they are executed in a particular order. To impose a different order (like to turn coolant off before the spindle is stopped), code the commands on separate blocks.

The order of execution is as follows:

1.  Comment (including message)
    
2.  Set feed rate mode (G93, G94, G95)
    
3.  Set feed rate (F)
    
4.  Set spindle speed (S)
    
5.  Special I/O (M62 to M68)
    

**NOTE: This is not supported.**

6.  Change tool (T)
    
7.  Spindle on/off (M03, M04, M05)
    
8.  Save State (M70, M73, restore state (M72), invalidate state (M71)
    
9.  Coolant on/off (M07, M08, M09)
    
10.  Enable/disable overrides (M48, M49, M50, M51, M52, M53)
     
11.  Operator defined commands (M101 to M199)
     
12.  Dwell (G04)
     
13.  Set active plane (G17, G18, G19)
     
14.  Set length units (G20, G21)
     
15.  Cutter radius compensation on/off (G40, G41, G42)
     
16.  Tool table offset on/off (G43, G49)
     
17.  Fixture table select (G54 through G58 and G59 P~)
     
18.  Set path control mode (G61, G61.1, G64)
     
19.  Set distance mode (G90, G91)
     
20.  Set canned cycle return level mode (G98, G99)
     
21.  Home, change coordinate system data (G10) or set offsets (G92, G94)
     
22.  Perform motion (G00 to G03, G12, G13, G80 to G89 as modified by G53)
     
23.  Stop (M00, M01, M02, M30, M60)
     

**Modal Groups**

G- and M-codes are, generally speaking, modal — they cause the machining system to change from one mode to another. The mode stays active until another command changes it implicitly or explicitly.

**Example**  
If coolant is turned on (M07 or M08), it stays on until it is explicitly turned off in the program (M09).

A few G-codes and M-codes are non-modal (like Dwell (G04)). These codes have effect only on the lines on which they occur.

Modal commands are arranged in sets, called modal groups. Only one member of a modal group may be in force at any given time. In general, a modal group contains commands for which it is logically impossible for two members to be in effect at the same time (like inch units (G20) vs. millimeter units (G21)).

A machining system may be in many modes at the same time, with one mode from each modal group being in effect.

For all G-code modal groups, when a machining system is ready to accept commands, one member of the modal group must be in effect. There are default settings for these modal groups. When the machining system is turned on or re-initialized, default values are automatically in effect.

Modal groups for G-codes are detailed in the following table.



*          Group        :          Group 1        
  *          Commands        :          {G00, G01, G02, G03, G33, G37, G37.1, G38.x, G73, G76, G80, G81, G82, G84, G85, G86, G88, G89}        
  *          Group Description        :          Motion (one always in effect)        
*          Group        :          Group 2        
  *          Commands        :          {G17, G18, G19, G17.1, G17.2, G17.3}        
  *          Group Description        :          Plane selection        
*          Group        :          Group 3        
  *          Commands        :          {G90, G91}        
  *          Group Description        :          Distance mode        
*          Group        :          Group 4        
  *          Commands        :          {G90.1, G91.1}        
  *          Group Description        :          Arc distance mode        
*          Group        :          Group 5        
  *          Commands        :          {G93, G94}        
  *          Group Description        :          Feed rate mode        
*          Group        :          Group 6        
  *          Commands        :          {G20, G21}        
  *          Group Description        :          Length units        
*          Group        :          Group 7        
  *          Commands        :          {G40, G41, G42, G41.1, G42.1}        
  *          Group Description        :          Cutter compensation        
*          Group        :          Group 8        
  *          Commands        :          {G43, G43.1, G49}        
  *          Group Description        :          Tool length offset        
*          Group        :          Group 10        
  *          Commands        :          {G98, G99}        
  *          Group Description        :          Return mode in canned cycles        
*          Group        :          Group 12        
  *          Commands        :          {G54, G55, G56, G57, G58, G59, G59.1, G59.2, G59.3}        
  *          Group Description        :          Select work offset coordinate system        
*          Group        :          Group 13        
  *          Commands        :          {G61, G61.1, G64}        
  *          Group Description        :          Path control mode        
*          Group        :          Group 14        
  *          Commands        :          {G96, G97}        
  *          Group Description        :          Spindle control mode        
*          Group        :          Group 15        
  *          Commands        :          {G07, G08}        
  *          Group Description        :          Lathe diameter mode        


Modal groups for M-codes are detailed in the following table.



*          Group        :          Group 4        
  *          Commands        :          {M00, M01, M02, M30, M60}        
  *          Group Description        :          Program stop and program end        
*          Group        :          Group 7        
  *          Commands        :          {M03, M04, M05}        
  *          Group Description        :          Spindle control        
*          Group        :          Group 8        
  *          Commands        :          {M07, M08, M09}        
  *          Group Description        :          Coolant control (special case: M07 and M08 may be active at the same time)        
*          Group        :          Group 9        
  *          Commands        :          {M48, M49}        
  *          Group Description        :          Override control        


Non-modal G-codes are:

*   **Group 0** {G04, G10, G28, G30, G53, G92, G92.1, G92.2, G92.3}
    

**Comments**

You can add comments to lines of G-code to help clarify the intention of the programmer. To embed a comment in a line, use parentheses. To add a comment to the end of a line, use a semicolon.

**NOTE: The semicolon is not treated as the start of a comment when it's enclosed in parentheses.**

Comments can appear between words, but they can't be between words and their corresponding parameter.

**Example**:  
S100(set speed)F200(feed) is okay, but S(speed)100F(feed) is not.

### Supported G-Codes Reference



*          G-Code        :          G00        
  *          Description        :          Rapid linear motion        
*          G-Code        :          G01        
  *          Description        :          Linear motion at feed rate        
*          G-Code        :          G02        
  *          Description        :          Clockwise arc at feed rate        
*          G-Code        :          G03        
  *          Description        :          Counterclockwise arc at feed rate        
*          G-Code        :          G04        
  *          Description        :          Dwell        
*          G-Code        :          G07, G08        
  *          Description        :          Diameter / radius mode         NOTE: The 15L Slant-PRO lathe and the RapidTurn both use G07 (X positions displayed in diameter values). G08 is not used or supported in PathPilot.        
*          G-Code        :          G10 L1        
  *          Description        :          Set tool table        
*          G-Code        :          G10 L2        
  *          Description        :          Set coordinate system        
*          G-Code        :          G10 L10        
  *          Description        :          Set tool table – calculated – workpiece        
*          G-Code        :          G10 L11        
  *          Description        :          Set tool table – calculated – fixture        
*          G-Code        :          G10 L20        
  *          Description        :          Set coordinate system        
*          G-Code        :          G17, G18, G19        
  *          Description        :          Plane selection        
*          G-Code        :          G20/G21        
  *          Description        :          Length units        
*          G-Code        :          G28        
  *          Description        :          Return to predefined position        
*          G-Code        :          G28.1        
  *          Description        :          Return to predefined position        
*          G-Code        :          G30        
  *          Description        :          Return to predefined position        
*          G-Code        :          G33        
  *          Description        :          Spindle synchronized motion (like threading)        
*          G-Code        :          G33.1        
  *          Description        :          Rigid tapping        
*          G-Code        :          G37        
  *          Description        :          Automatically Measure Tool Lengths with an ETS        
*          G-Code        :          G37.1        
  *          Description        :          Automatically Measure Tool Lengths with an ETS        
*          G-Code        :          G38.x        
  *          Description        :          Straight Probe        
*          G-Code        :          G40        
  *          Description        :          Cancel cutter compensation        
*          G-Code        :          G41/G42        
  *          Description        :          Cutter compensation (left/right)        
*          G-Code        :          G41.1, G42.1        
  *          Description        :          Dynamic cutter compensation        
*          G-Code        :          G43        
  *          Description        :          Apply tool length offset        
*          G-Code        :          G47        
  *          Description        :          Engrave Sequential Serial Number        
*          G-Code        :          G49        
  *          Description        :          Cancel tool length compensation        
*          G-Code        :          G53        
  *          Description        :          Absolute coordinates        
*          G-Code        :          G54-G59.3        
  *          Description        :          Select work offset coordinate system        
*          G-Code        :          G61/G61.1        
  *          Description        :          Set exact path control mode        
*          G-Code        :          G64        
  *          Description        :          Set blended path control mode        
*          G-Code        :          G73        
  *          Description        :          High-speed peck drill        
*          G-Code        :          G76        
  *          Description        :          Multi-pass threading cycle        
*          G-Code        :          G80        
  *          Description        :          Cancel canned cycles        
*          G-Code        :          G81        
  *          Description        :          Drilling cycle        
*          G-Code        :          G82        
  *          Description        :          Simple drilling cycle        
*          G-Code        :          G83        
  *          Description        :          Peck drilling cycle        
*          G-Code        :          G85        
  *          Description        :          Boring cycle        
*          G-Code        :          G86        
  *          Description        :          Boring cycle        
*          G-Code        :          G88        
  *          Description        :          Boring cycle        
*          G-Code        :          G89        
  *          Description        :          Boring cycle        
*          G-Code        :          G90, G90.1        
  *          Description        :          Arc distance mode        
*          G-Code        :          G91, G91.1        
  *          Description        :          Incremental distance mode        
*          G-Code        :          G92        
  *          Description        :          Offset coordinates and set parameters        
*          G-Code        :          G92.x        
  *          Description        :          Cancel G92, etc.        
*          G-Code        :          G93, G94, G95        
  *          Description        :          Feed rate mode        
*          G-Code        :          G96, G97        
  *          Description        :          Spindle control mode        
*          G-Code        :          G98        
  *          Description        :          Initial level return / R-point level after canned cycles        


Programming G-Code
------------------

Read the following sections as a G-code reference:

### About the Examples Used

Many commands require axis words (X~, Y~ ,Z~, or A~) as an argument. Unless explicitly stated otherwise, you can make the following assumptions:

*   Axis words specify a destination point
    
*   Axis words relate to the currently active coordinate system, unless explicitly described as being in the absolute coordinate system
    
*   Where axis words are optional, any omitted axes retain their current value
    

Any items in the command examples not explicitly described as optional are required.

### Rapid Linear Motion (G00)

For rapid linear motion, program: G00 X~ Y~ Z~ A~

*   X~ is the X-axis coordinate
    
*   Y~ is the Y-axis coordinate
    
*   Z~ is the Z-axis coordinate
    
*   A~ is the A-axis coordinate
    

This produces coordinated linear motion to the destination point at the current traverse rate (or slower, if the machine won't go that fast). It's expected that cutting won’t take place when a G00 command is executing. The G00 is optional if the current motion mode is G00.

Depending on where the tool is located, follow these two basic rules:

1.  If the Z value represents a cutting move in the positive direction (like out of a hole), the X-axis should be moved last.
    
2.  If the Z value represents a move in the negative direction, the X-axis should be moved first.
    

**Conditions**

The motion differs if:

*   Cutter radius compensation is active
    
*   G53 is programmed on the same line
    

**Troubleshooting**

It's an error if:

*   All axis words are omitted  
    The axis words are optional, except that at least one must be used.
    
*   G10, G28, G30 or G92 appear in the same block
    

### Linear Motion at Feed Rate (G01)

For linear motion at feed rate (for cutting or not), program: G01 X~ Y~ Z~ A~ F~

*   X~ is the X-axis coordinate
    
*   Y~ is the Y-axis coordinate
    
*   Z~ is the Z-axis coordinate
    
*   A~ is the A-axis coordinate
    
*   F~ is the feed rate
    

This produces coordinated linear motion to the destination point at the current feed rate (or slower, if the machine won’t go that fast). The G01 is optional if the current motion mode is G01.

**Conditions**

The motion differs if:

*   Cutter radius compensation is active
    
*   G53 is programmed on the same line
    

**Troubleshooting**

It's an error if:

*   All axis words are omitted  
    The axis words are optional, except that at least one must be used.
    
*   G10, G28, G30, or G92 appear in the same block
    
*   No F word is specified
    

### Arc at Feed Rate (G02 and G03)

A circular or helical arc is specified using either G02 (clockwise arc) or G03 (counterclockwise arc). The axis of the circle or helix must be parallel to the X-, Y- or Z-axis of the machine coordinate system. The axis (or equivalently, the plane perpendicular to the axis) is selected with G17 (Z-axis, XY-plane), G18 (Y-axis, XZ-plane) or G19 (X-axis, YZ-plane). If the arc is circular, it lies in a plane parallel to the selected plane.

If a line of code makes an arc and includes rotational axis motion, the rotational axes turn at a constant rate so that the rotational motion starts and finishes when the XYZ motion starts and finishes. This is rare.

The motion differs if cutter radius compensation is active.

Two formats are allowed for specifying an arc: the center format and the radius format. In both formats, the G02 or G03 is optional if it's the current motion mode.

**Radius Format Arc**

For a clockwise arc in radius format, program: G02 X~ Y~ Z~ A~ R~

For a counterclockwise arc in radius format, program: G03 X~ Y~ Z~ A~ R~

*   X~ is the X-axis coordinate
    
*   Y~ is the Y-axis coordinate
    
*   Z~ is the Z-axis coordinate
    
*   A~ is the A-axis coordinate
    
*   R~ is the radius of the arc
    

In radius format, the coordinates of the end point of the arc in the selected plane are specified along with the radius of the arc. A positive radius indicates that the arc turns through 180 degrees or less, while a negative radius indicates a turn of 180 degrees to 359.999 degrees.

If the arc is helical, the value of the end point of the arc on the coordinate axis parallel to the axis of the helix is also specified.

We don't recommend programming radius format arcs that are:

*   Nearly full circles
    
*   Semicircles
    
*   Nearly semicircles
    

A small change in the location of the end point produces a much larger change in the location of the center of the circle (and the middle of the arc). The magnification effect is large enough that rounding error in a number can produce out-of-tolerance cuts.

You can program arcs that are:

*   Up to 165 degrees
    
*   Between 195 degrees to 345 degrees
    

**Example**  
G17 G02 X 1.0 Y 1.5 R 2.0 Z 0.5 is a radius format command to mill an arc, which makes a clockwise (as viewed from the positive Z-axis) circular or helical arc whose axis is parallel to the Z-axis, ending where X = 1.0, Y = 1.5, and Z = 0.5, with a radius of 2.0. If the starting value of Z is 0.5, this is an arc of a circle parallel to the XY-plane; otherwise, it's a helical arc.

**Troubleshooting**

It's an error if:

*   Both of the axis words for the axes of the selected plane are omitted  
    The axis words are all optional except that at least one of the two words for the axes in the selected plane must be used.
    
*   No R word is given
    
*   The end point of the arc is the same as the current point
    
*   G10, G28, G30, or G92 appear in the same block
    

**Center Format Arc**

For a clockwise arc in center format, program: G02 X~ Y~ Z~ I~ J~

For a counterclockwise arc in center format, program: G03 X~ Y~ Z~ I~ J~

*   X~ is the X-axis coordinate
    
*   Y~ is the Y-axis coordinate
    
*   Z~ is the Z-axis coordinate
    
*   A~ is the A-axis coordinate
    
*   I~ is the center of arc (X coordinate)
    
*   J~ is the center of arc (Y coordinate)
    
*   K~ is the center of arc (Z coordinate)
    

In the center format, the coordinates of the end point of the arc in the selected plane are specified along with the offsets of the center of the arc from the current location. In this format, it's okay if the end point of the arc is the same as the current point.

The center is specified using the I, J, K words associated with the active plane. These specify the center relative to the current point at the start of the arc, defined in incremental coordinates from the start point.

It's an error if:

*   When the arc is projected on the selected plane, the distance from the current point to the center differs from the distance from the end point to the center by more than 0.0002 inches (if you're programming in inches) or 0.002 millimeters (if you're programming in millimeters)
    
*   G10, G28, G30, or G92 appear in the same block
    

**Arc in XY Plane**

When the XY-plane is selected, program: G02 X~ Y~ Z~ A~ I~ J~ (or, use G03 instead of G02)

I and J are the offsets from the current location or coordinates – depending on arc distance mode (G90.1/G91.1) of the center of the circle (X and Y directions, respectively).

It's an error if:

*   X and Y are both omitted  
    The axis words are all optional except that at least one of X and Y must be used.
    
*   I and J are both omitted  
    I and J are optional except that at least one of the two must be used.
    

**Arc in XZ Plane**

When the XZ-plane is selected, program: G02 X~ Y~ Z~ A~ I~ K~ (or, use G03 instead of G02)

I and K are the offsets from the current location or coordinates – depending on arc distance mode (G90.1/G91.1) of the center of the circle (X and Z directions, respectively).

It's an error if:

*   X and Z are both omitted  
    The axis words are all optional except that at least one of X and Z must be used.
    
*   I and K are both omitted  
    I and K are optional except that at least one of the two must be used.
    

**Arc in YZ Plane**

When the YZ-plane is selected, program: G02 X~ Y~ Z~ A~ J~ K~ (or, use G03 instead of G02)

J and K are the offsets from the current location or coordinates – depending on depending on arc distance mode (G90.1/G91.1) of the center of the circle (Y and Z directions, respectively).

It's an error if:

*   Y and Z are both omitted  
    The axis words are all optional except that at least one of Y and Z must be used.
    
*   J and K are both omitted  
    J and K are optional except that at least one of the two must be used.
    

**Example**  
G17 G02 X1.0 Y1.6 I0.3 J0.4 Z0.9 is a center format command to mill an arc in incremental arc distance mode (G91.1) that makes a clockwise (as viewed from the positive Z-axis), circular, or helical arc whose axis is parallel to the Z-axis, ending where X = 1.0, Y = 1.6, and Z = 0.9, with its center offset in the X direction by 0.3 units from the current X location and offset in the Y direction by 0.4 units from the current Y location. If the current location has X = 0.7, Y = 0.7 at the outset, the center is at X = 1.0, Y = 1.1. If the starting value of Z is 0.9, this is a circular arc; otherwise, it's a helical arc. The radius of this arc would be 0.5.

In the center format, the radius of the arc is not specified, but it may be found easily as the distance from the center of the circle to either the current point or the end point of the arc.

**(Sample Program G02EX3:)**  
(Workpiece Size: X4, Y3, Z1)  
(Tool: Tool #2, 1/4” Slot Drill)  
(Tool Start Position: X0, Y0, Z1)  
N2 G90 G80 G40 G54 G20 G17 G94 G64 (SAFETY BLOCK)  
N5 G90 G20  
N10 M06 T2 G43 H2  
N15 M03 S1200  
N20 G00 X1 Y1  
N25 Z0.1  
N30 G01 Z-0.1 F5  
N35 G02 X2 Y2 I1 J0 F20 (ARC FEED CW, RADIUS I1,J0 AT 20 IPM)  
N40 G01 X3.5  
N45 G02 X3 Y0.5 R2 (ARC FEED CW, RADIUS 2)  
N50 X1 Y1 R2 (ARC FEED CW, RADIUS 2)  
N55 G00 Z0.1  
N60 X2 Y1.5  
N65 G01 Z-0.25  
N70 G02 X2 Y1.5 I0.25 J-0.25 (FULL CIRCLE ARC FEED MOVE CW)  
N75 G00 Z1  
N80 X0 Y0  
N85 M05  
N90 M30

### Dwell (G04)

For a dwell, program: G04 P~

*   P~ is the dwell time (measured in seconds)
    

Dwell keeps the axes unmoving for the period of time in seconds specified by the P number.

**Example**  
G04 P4.2 (to wait 4.2 seconds)

**Troubleshooting**

It's an error if:

*   The P number is negative
    

### Set Offsets (G10)

Use the controls on the Offsets tab to set offsets. You can program offsets with the G10 G-code command.

Read the following sections for reference:

**Set Tool Table (G10 L1)**

To define an entry in the tool table, program: G10 L1 P~ R~

*   P~ is the tool number
    
*   R~ is the radius of tool
    

G10 L1 sets the tool table for the P tool number to the values of the words. A valid G10 L1 rewrites and reloads the tool table.

**Troubleshooting**

It's an error if:

*   Cutter Compensation is on
    
*   The P number is unspecified
    
*   The P number is not a valid tool number from the tool table
    
*   The P number is 0
    

**Set Coordinate System (G10 L2)**

To define the origin of a work offset coordinate system, program: G10 L2 P~ <axes R~>

*   P~ is the number of coordinate system to use (G54 = 1, G59.3 = 9)
    
*   R~ is the rotation about the the Z-axis
    

The G10 L2 P~ command doesn’t change from the current coordinate system to the one specified by P. Use G54 through G59.3 to select a coordinate system.

The coordinate system whose origin is set by a G10 command may be active or inactive at the time the G10 is executed. If it’s currently active, the new coordinates take effect immediately. For example, if a G92 origin offset was in effect before G10 L2, it continues to be in effect after.

Optionally program R to indicate the rotation of the XY axis around the Z-axis. The direction of rotation is counterclockwise (viewed from the positive end of the Z-axis). When a rotation is in effect, jogging an axis only moves that axis in a positive or a negative direction – not along the rotated axis. To cancel a rotation for the active coordinate, program G10 L2 P0 R0.

**Troubleshooting**

It’s an error if:

*   The P number does not evaluate to an integer in the range 0-500
    
*   An axis other than X or Z is programmed
    

**Set Tool Table (G10 L10)**

To change the tool table entry for tool P so that if the tool offset is reloaded with the machine in its current position and with the current G5x and G92 offsets active, program: G10 L10 P~ R~

*   P~ is the tool number
    
*   R~ is the radius of tool
    

The current coordinates for the given axes become the given values. The axes that are not specified in the G10 L10 command are not changed. This could be useful with a probe move (G38).

**Troubleshooting**

It's an error if:

*   Cutter Compensation is on
    
*   The P number is unspecified
    
*   The P number is not a valid tool number from the tool table
    
*   The P number is 0
    

**Set Tool Table (G10 L11)**

G10 L11 is just like G10 L10, except that instead of setting the entry according to the current offsets, it's set so that the current coordinates would become the given value if the new tool offset is reloaded and the machine is placed in the G59.3 coordinate system without any G92 offset active. This allows you to set the G59.3 coordinate system according to a fixed point on the machine, and then use that fixture to measure tools without regard to other currently active offsets.

Program: G10 L11 P~ X~ Y~ Z~ R~

*   P~ is the tool number
    
*   R~ is the radius of tool
    

**Troubleshooting**

It's an error if:

*   Cutter Compensation is on
    
*   The P number is unspecified
    
*   The P number is not a valid tool number from the tool table
    
*   The P number is 0
    

**Set Coordinate System (G10 L20)**

G10 L20 is similar to G10 L2, except that instead of setting the offset/entry to the given value, it is set to a calculated value that makes the current coordinates become the given value.

**Program**: G10 L20 P~ X~ Y~ Z~ A~

*   P~ is the number of coordinate system to use (G54 = 1, G59.3 = 9)
    
*   X~ is the X-axis coordinate
    
*   Y~ is the Y-axis coordinate
    
*   Z~ is the Z-axis coordinate
    
*   A~ is the A-axis coordinate
    

**Troubleshooting**

It's an error if:

*   The P number does not evaluate to an integer in the range 0 to 9
    
*   An axis other than X, Y, Z, or A is programmed
    

### Plane Selection (G17, G18, G19)

To select the XY-plane as active, program: G17

To select the XZ-plane as active, program: G18

To select the YZ-plane as active, program: G19

The active plane determines how the tool path of an arc (G02 or G03) or canned cycle (G73, G81 through G89) is interpreted.

### Length Units (G20 and G21)

To set length units to inches, program: G20

To set length units to millimeters, program: G21

**Tip! Program either G20 or G21 near the beginning of a program, before any motion occurs. Avoid using either one anywhere else in the program. It's your responsibility to make sure that all numbers are appropriate for use with the current length units.**

### Return to Predefined Position (G28 and G28.1)

To make a rapid linear move from the current position to the absolute position of the values in parameters 5161-5166: G28

To make a rapid linear move to the G28.1 position by first going to the intermediate position specified by the X~, Y~, and Z~ words, program: G28 X~ Y~ Z~

**NOTE: Any axis not specified won't move.**

To store the current location of the tool in the G28.1 setting, program: G28.1

G28 uses the values stored in parameters 5161, 5162, and 5163 as the X, Y, and Z final points to move to. The parameter values are absolute machine coordinates in the native machine units of inches.

To store the current absolute position into parameters 5161-5163, program: G28.1

If no positions are stored with G28.1 then all axes will go to the machine origin.

**Troubleshooting**

It's an error if:

*   Cutter Compensation is turned on
    

### Return to Predefined Position (G30 and G30.1)

G30 uses the values stored in parameters 5181 and 5183 as the X and Z final point to move to. The parameter values are absolute machine coordinates in the native machine units of inches.

To make a rapid traverse move from the current position to the absolute position of the values in parameters, program: G30

To make a rapid traverse move to the position specified by axes including any offsets, then make a rapid traverse move to the absolute position of the values in parameters 5181 and/or 5183, program: G30 X~ Z~

**NOTE: Any axis not specified won't move.**

To store the current absolute position into parameters 5181-5183, program: G30.1

**Troubleshooting**

It's an error if:

*   Cutter Compensation is turned on
    

### Automatically Measure Tool Lengths with an ETS (G37 and G37.1)

Use G37 and G37.1 with an Electronic Tool Setter (ETS) to enable automatic length measurement. For automated use, add a G37 command after an M6 tool change commands.

If you're using the ETS with a mill, the input port varies depending on your machine:

*   **M Series Mills** Plug the ETS into the Accessory Input 2 port. You can still use the Accessory Input 1 port for other probes and accessories.
    
*   **Older PCNC Mills** Plug the ETS into the (single) accessory input port.
    

**Move to G37 Position Over ETS (G37.1)**

To move to the G37 position (over the ETS), program: G37.1

**To set the G37 position:**

1.  Jog the machine over the center of the ETS.
    
2.  From the **Probe** tab, on the **ETS Setup** tab, select **Set G37 ETS Position**.  
    _The read-only DROs in the ETS G37 Position Setup group display the new position._
    

The G37 position is in G53 machine coordinate space. It defaults to (0, 0, 0), or the top left rear of machine travel (the same as the X-, Y-, and Z-axis reference position).

G37.1 supports X and Y tool offsets. If there are X or Y tool offsets present in the tool table (manually applied through a G10 L1 command), they offset the spindle position. This enables G37 for tools mounted in an auxiliary spindle installed on the spindle column.

**NOTE: If G10 L1 is used to change the X or Y offset of the currently loaded tool, you must then apply the new offsets with a G43 command.**

G37.1 performs as follows:

1.  A rapid upward move to the Z clear position (which is always G53 Z = 0.0).
    
2.  A rapid move in X and Y to the X and Y ETS coordinates.
    
3.  A rapid downward move in Z to the Z ETS coordinate.
    

**NOTE: The Z word saves time by rapidly moving closer to the ETS before the slower probing begins. You must use caution if you set this lower than G53 Z = 0.0. If you don't, there's a risk that a long tool could collide with the ETS and damage it and the tool.**

**Move and Measure Tool Length (G37)**

To move and measure the tool length, program: G37 H~ P~

*   H~ saves the measured tool length to the H tool table entry instead of the current tool number's entry.  
    You could use this to track tool wear between the two tool table entries, for example.
    

**NOTE: The newly measured tool length isn't applied, but it's stored in the tool table entry for tool number H.**

*   P~ is positive or negative tolerance. It measures the tool length, but, instead of storing it in the tool table, compares it to the length in the tool table. If the difference exceeds the P tolerance, the G-code program stops.  
    You could use this to detect broken or improperly inserted tools that are not fully seated in the spindle, for example.
    

G37 with no optional words moves to the G37 ETS position (through G37.1), probes the ETS, stores the new tool length in the tool table entry of the current tool, and applies the tool length offset.

G37 fails if the spindle nose hasn't been referenced to the ETS after a Z-axis reference. This sets a G53 coordinate at the ETS trigger point such that the measured tool length is the distance of the spindle nose to ETS reference. For more information, see the **ETS G37 Spindle Nose Reference** group on the **ETS Setup** tab.

So that tool length measurements have consistent results, G37 uses the fine probe feed rate of 2.5 in./min for the final ETS touch. G37 uses the rough probe feed rate for the first ETS touch.

**G37 performs as follows:**

1.  Issues a G37.1 move to the ETS location.
    
2.  A downward rough probe feed rate move until the tool triggers the ETS.
    
3.  An upward retract move of 0.100 in. to back off the triggered ETS.
    
4.  A downward slow ETS probe feed rate move until the tool triggers the ETS.
    
5.  An upward retract move of 0.100 in. to back off the triggered ETS.
    
6.  An upward rapid move to the G37 ETS Z position.
    

### Straight Probe (G38.x)

G38.2 probes toward the workpiece, stops on contact, and signals error if failure

G38.3 probes toward the workpiece and stops on contact

G38.4 probes away from the workpiece, stops on loss of contact, and signals error if failure

G38.5 probes away from the workpiece and stops on loss of contact

G38.6 moves away from the workpiece and ignores probe input

To perform a straight probe operation program: G31 X~ Y~ Z~ A~

Conventionally, the probe is tool #99. The rotational axis words are allowed, but it's better to omit them. If rotational axis words are used, the numbers must be the same as the current position numbers so that the rotational axes do not move. The tool in the spindle must be a probe.

In response to this command, the machine moves the controlled point (which should be at the end of the probe tip) in a straight line at the current feed rate toward the programmed point; if the probe trips, then the probe decelerates.

After successful probing, parameters 5061 to 5064 will be set to the coordinates of the location of the controlled point at the time the probe tripped (not where it stopped), or if it does not trip to the coordinates at the end of the move and a triplet giving X, Y, and Z at the trip is written to the triplet file.

**Troubleshooting**

It's an error if:

*   The current point is less than 0.01 in. (0.254 mm) from the programmed point
    
*   G38 is used in inverse time feed rate mode
    
*   Any rotational axis is commanded to move
    
*   No X-, Y- or Z-axis word is used
    

The linear axis words are optional, except that at least one of them must be used.

*   Feed rate is zero
    
*   The probe is already tripped
    

**Use the Straight Probe Command**

When you use the straight probe command, if the probe shank is kept nominally parallel to the Z-axis (i.e., any rotational axes are at zero) and the tool length offset for the probe is used, so that the controlled point is at the end of the tip of the probe, you may be able to find:

*   Without additional knowledge about the probe, the parallelism of a face of a part to the XY-plane
    
*   If the probe tip radius is known approximately, the parallelism of a face of a part to the YZ or XZ-plane
    
*   If the shank of the probe is known to be well-aligned with the Z-axis and the probe tip radius is known approximately, the center of a circular hole
    

If the shank of the probe is known to be well-aligned with the Z-axis and the probe tip radius is known precisely, you can use the straight probe command for things like finding the diameter of a circular hole.

**Example code:**  
o<probe\_pocket> sub  
(probe to find center of circular or rectangular pocket)  
#<x\_start> = #5420 (Current X Location)  
#<y\_start> = #5421 (Current Y Location)  
#<x\_max> = 1  
#<x\_min> = -1  
#<y\_max> = 1  
#<y\_min> = -1  
#<feed\_rate> = 30 (30 IPM)  
F #<feed\_rate>  
G38.3 X #<x\_max> (rough probe +X side of hole)  
F \[#<feed\_rate>/30\]  
G38.5 X #<x\_start> (finish probe)  
#<x\_plus>=#5061 (save results)  
G00 X #<x\_start> (return to start)  
F #<feed\_rate>  
G38.3 X #<x\_min> (probe -X side of hole)  
F \[#<feed\_rate>/30\]  
G38.5 X #<x\_start>  
#<x\_minus>=#5061 (save results)  
G00 X #<x\_start>  
#<x\_center> = \[\[#<x\_plus>+#<x\_minus>\]/2\]  
G00 X #<x\_center> (go to middle)  
F #<feed\_rate>  
G38.3 Y #<y\_max> (probe +Y side of hole)  
F \[#<feed\_rate>/30\]  
G38.5 Y #<y\_start>  
#<y\_plus>=#5062 (save results)  
G00 Y #<y\_start> (return to start)  
F #<feed\_rate>  
G38.3 Y #<y\_min> (probe -Y side of hole)  
F \[#<feed\_rate>/30\]  
G38.5 Y #<y\_start>  
#<y\_minus>=#5062 (save results)  
G00 Y #<y\_start>  
#<y\_center> = \[\[#<y\_plus>+#<y\_minus>\]/2\]  
G00 Y #<y\_center> (go to middle)  
G10 L20 P1 X 0 Y 0 (set current location to zero)  
F #<feed\_rate> (restore original feed rate)  
o<probe\_pocket> endsub  
M02

### Cutter Compensation (G40, G41, G42)

To turn Cutter Compensation off, program: G40

It's okay to turn compensation off when it is already off.

It's an error if:

*   A G02/G03 arc move is programmed next after a G40
    
*   The linear move after turning compensation off is less than twice the tool tip radius
    

To program Cutter Compensation to the left of the programmed tool path (as viewed looking down on the machine), program: G41 D~

To program Cutter Compensation to the right of the programmed tool path (as viewed looking down on the machine), program: G42 D~

*   D~ is the tool number associated with the diameter offset to be applied
    

The D word is optional — if there is no D word, the radius of the currently loaded tool is used. If no tool is loaded and no D word is given, a radius of 0 is used. If supplied, the D word is the tool number to use.

The lead in move must be at least as long as the tool radius. The lead in move can be a rapid move.

It's an error if:

*   The D number is not a valid tool number, or it's 0
    
*   Cutter Compensation is commanded to turn on when it is already on
    

### Dynamic Cutter Compensation (G41.1 and G42.1)

To program dynamic Cutter Compensation to the left of the programmed tool path, program: G41.1 D~

To program dynamic Cutter Compensation to the right of the programmed tool path, program: G42.1 D~

D~ is the tip radius multiplied by two

G41.1 and G42.1 function the same as G41 and G42, with the added scope of being able to ignore the tool table and to program the tool diameter.

**Troubleshooting**

It's an error if:

*   Cutter Compensation is commanded to turn on when it is already on
    

### Apply Tool Length Offset (G43)

To apply a tool length offset from a stored value in the tool table, program: G43 H~

*   H~ is the tool number associated with the length offset to be applied.
    

**NOTE: Generally speaking, the value of the H~ word should match the active tool number (T~ word).**

It's okay to program using the same offset already in use, or to program without a tool length offset (if none is currently being used).

**Troubleshooting**

It's an error if:

*   The H number is not an integer
    
*   The H number is negative
    
*   The H number is not a valid tool number
    

### Engrave Sequential Serial Number (G47)

To engrave a serial number, either alone or added to the end of any text, program: Z~ R~ X~ Y~ P~ Q~ D~

*   Z~ is the depth of cut of the engraving
    
*   R~ is the retract height between character segments in the numbers
    
*   X~ is, if present, the starting X position, or the left side of the serial number  
    If omitted, the current X position is assumed.
    
*   Y~ is, if present, the starting Y position, or the bottom side of the serial number  
    If omitted, the current Y position is assumed.
    
*   P~ is, if present, the X extent (width) in current units (inches or millimeters) of the engraved number
    
*   Q~ is, if present, the Y extent (height) in current units (inches or millimeters) of the engraved number
    
*   D~ is, if present, the requested number of decimals of the engraved number  
    If the requested D value exceeds the number of decimals in the serial number, the serial number will show leading zeros. If the requested D value is less than the number of decimals in the serial number, only the digits of the serial number will show.
    

**Example**  
A serial number of 10, where D = 4, engraves as 0010. A serial number of 9056, where D = 3, engraves as 9056.

**Troubleshooting**

It's an error if:

*   Cutter Compensation is on
    
*   The Z number is unspecified
    
*   The R number is unspecified
    
*   The Z number is greater than the R number
    
*   The P number is too small (determined by the font used)
    
*   The Q number is too small (determined by the font used)
    

### Cancel Tool Length Compensation (G49)

To cancel tool length compensation, program: G49

### Absolute Coordinates (G53)

For rapid linear motion to a point expressed in absolute coordinates, program: G01 G53 X~ Y~ Z~ (or use with G00 instead of G01)

All the axis words are optional, except that at least one must be used. The G00 or G01 is optional if it is in the current motion mode. G53 isn't modal, and must be programmed on each line on which it is intended to be active. This produces coordinated linear motion to the programmed point. If G01 is active, the speed of motion is the current feed rate (or slower if the machine won’t go that fast). If G00 is active, the speed of motion is the current traverse rate (or slower if the machine won’t go that fast).

**Troubleshooting**

It's an error if:

*   G53 is used without G00 or G01 being active
    
*   G53 is used while cutter radius compensation is on
    

### Select Work Offset Coordinate System (G54 to G54.1 P500)

You can save up to 500 work offsets in PathPilot. The naming structure varies based on the offset number.

*   To select work offset 1, program: G54 or G54.1 P1
    
*   To select work offset 2, program: G55 or G54.1 P2
    
*   To select work offset 3, program: G56 or G54.1 P3
    
*   To select work offset 4, program: G57 or G54.1 P4
    
*   To select work offset 5, program: G58 or G54.1 P5
    
*   To select work offset 6, program: G59 or G54.1 P6
    
*   To select work offset 7, program: G59.1 or G54.1 P7
    
*   To select work offset 8, program: G59.2 or G54.1 P8
    
*   To select work offset 9, program: G59.3 or G54.1 P9
    
*   To select a work offset beyond the standard 9 (listed above), program: G54.1 P###, where P### is a parameter indicating the index of the work offset you want to use (work offset 10 through work offset 500).
    

**Example**  
To select the 124th work offset, program G54.1 P124.

For information, see “[Set Work Offsets](https://knowledgebase.tormach.com/pcnc-1100/setting-up-work-and-tool-offsets-on-tormach-mills)”.

**Troubleshooting**

It's an error if:

*   One of these G-codes is used while cutter radius compensation is on
    
*   The X- and Z-axis work offset values are stored in parameters corresponding to the system in use (i.e., System 1 X=5221, Z=5223; System 2 X=5141, Z=5143; up to System 9 X= 5381, Z = 5383).
    

### Set Exact Path Control Mode (G61)

To put the machining system into exact path mode, program: G61

### Set Blended Path Control Mode (G64)

To attempt to maintain the defined feed velocity, program: G64 P~ Q~

*   P~ is, if present, the maximum acceptable tool path deviation to round corners to maintain speed.  
    If P is omitted then the speed is maintained however far from the programmed path the tool cuts.
    
*   Q~ is, if present, the maximum deviation from collinearity that will collapse a series of linear G01 moves at the same feed rate into a single linear move.
    

It's okay to program for the mode that is already active.

### Distance Mode (G90 and G91)

Interpretation of the operating system code can be in one of two distance modes: absolute or incremental.

To go into absolute distance mode, program: G90.

In absolute distance mode, axis numbers (X, Y, Z, A) usually represent positions in terms of the currently active coordinate system. Any exceptions to that rule are described explicitly in this section.

To go into incremental distance mode, program: G91.

In incremental distance mode, axis numbers (X, Y, Z, A) usually represent increments from the current values of the numbers. I and J numbers always represent increments, regardless of the distance mode setting. K numbers represent increments.

### Arc Distance Mode (G90.1 and G91.1)

G90.1 – Absolute distance mode for I and K offsets. When G90.1 is in effect, I and K both must be specified with G02/G03 for the XZ plane or it is an error.

G91.1 – Incremental distance mode for I and K offsets. G91.1 returns I and K to their default behavior.

### Temporary Work Offsets (G92, G92.1, G92.2, and G92.3)

**IMPORTANT! This is a legacy feature. Most modern programming methods don't use temporary work offsets.**

To apply a temporary work offset, program: G92 X~ Y~ Z~ A~

*   X~ is the X-axis coordinate
    
*   Y~ is the Y-axis coordinate
    
*   Z~ is the Z-axis coordinate
    
*   A~ is the A-axis coordinate
    

G92 reassigns the current controlled point to the coordinates specified by the axis words (X~, Y~, Z~, and/or A~). No motion takes place.

The axis words are optional, except that at least one must be used. If an axis word is not used for a given axis, the coordinate on that axis of the current point is not changed. Incremental distance mode (G91) has no effect on the action of G92.

When G92 is executed, it is applied to the origins of all coordinate systems (G54 through G59.3).

**Example**  
If the current controlled point is at X = 4, and there is currently no G92 offset active, and then G92 X7 is programmed, this reassigns the current controlled point to X = 7 — effectively moving the origin of the active coordinate system -3 units in X. The origins of all inactive coordinate systems also move -3 units in X. This -3 is saved in parameter 5211.

G92 offsets may be already be in effect when the G92 is called. If this is the case, the offset is replaced with a new offset that makes the current point become the specified value.

It's an error if:

*   All axis words are omitted
    

PathPilot stores the G92 offsets and reuses them on the next run of a program. To prevent this, you can program a G92.1 (to erase them), or program a G92.2 (to stop them being applied – they are still stored).

To reset axis offsets to zero and sets parameters 5211 - 5219 to zero, program: G92.1

To reset axis offsets to zero, program: G92.2

To set the axis offset to the values saved in parameters 5211 to 5219, program: G92.3

### Feed Rate Mode (G93, G94, and G95)

To set the active feed rate mode to inverse time, program: G93

Inverse time is used to program simultaneous coordinated linear and coordinated rotary motion. In inverse time feed rate mode, an F word means the move should be completed in **\[1/F number\]** minutes.

**Example**  
If the F number is 2.0, the move should be completed in half a minute.

When the inverse time feed rate mode is active, an F word must appear on every line which has a G01, G02, or G03 motion, and an F word on a line that does not have G01, G02, or G03 is ignored. Being in inverse time feed rate mode does not affect G00 (rapid traverse) motions.

To set the active feed rate mode to units per minute mode, program: G94

In units per minute feed rate mode, an F word is interpreted to mean the controlled point should move at a certain number of inches per minute, or millimeters per minute, depending upon what length units are being used.

To set the active feed rate mode to units per revolution mode, program: G95

In units per revolution mode, an F word is interpreted to mean the controlled point should move a certain number of inches per revolution of the spindle, depending on what length units are being used. G95 is not suitable for threading, for threading use G33 or G76.

**Troubleshooting**

It's an error if:

*   Inverse time feed rate mode is active and a line with G01, G02, or G03 (explicitly or implicitly) does not have an F word
    
*   A new feed rate is not specified after switching to G94 or G95 canned cycle return level – G98 and G99
    

### Spindle Control Mode (G96 and G97)

To set constant surface speed mode, program: G96 D~ S~

*   D~ is the maximum spindle RPM.  
    This word is optional.
    
*   S~ is the surface speed.
    

**NOTE: If G20 is the active mode, the value is interpreted as feet per minute. If G21 is the active mode, the value is interpreted as meters per minute**

**Example**  
G96 D2500 S250 (set constant surface speed with a maximum RPM of 2500, and a surface speed of 250).

When using G96 (the most common mode of machine operation), X0 in the current coordinate system (including offsets and tool lengths) must be the spindle axis.

To set RPM mode, program: G97

**Troubleshooting**

It's an error if:

*   S is not specified with G96
    
*   A feed move is specified in G96 mode while the spindle is not turning
    

Programming Canned Cycles
-------------------------

Read the following sections for reference:

### Canned Cycles Reference

Supported Canned Cycles


|         Canned Cycle        |         Description                               |
|-----------------------------|---------------------------------------------------|
|         G80                 |         Cancel active canned cycle                |
|         G81                 |         Simple drilling cycle                     |
|         G82                 |         Simple drilling with dwell cycle          |
|         G83                 |         Peck drilling cycle                       |
|         G73                 |         High speed peck drilling cycle            |
|         G84                 |         Tapping cycle                             |
|         G85                 |         Boring cycle – feedrate out               |
|         G86                 |         Boring cycle – stop, rapid out            |
|         G88                 |         Boring cycle – stop, manual out           |
|         G89                 |         Boring cycle – dwell, feedrate out        |


All canned cycles are performed with respect to the active plane. The descriptions we use assume the XY-plane has been selected. The behavior is always analogous if the YZ- or XZ-plane is selected.

*   X~ is the X-axis coordinate
    
*   Y~ is the Y-axis coordinate
    
*   Z~ is the Z-axis coordinate
    
*   A~ is the A-axis coordinate
    
*   R~ is the retract position along the axis perpendicular to the currently selected plane (Z-axis for XY-plane, X-axis for YZ-plane, Y-axis for XZ-plane)
    
*   L~ is the L number is optional and represents the number of repeats
    

All canned cycles use X, Y, Z, and R words. The R word sets the retract position; this is along the axis perpendicular to the currently selected plane (Z-axis for XY-plane, X-axis for YZ-plane, Y-axis for XZ-plane). Some canned cycles use additional arguments.

Rotational axis (A-axis) words are allowed in canned cycles, but it's better to omit them. If rotational axis words are used, the numbers must be the same as the current position numbers so that the rotational axes do not move.

The R number is always sticky — it keeps its value on subsequent blocks if they're not explicitly programmed to be different.

In absolute distance mode (G90), the X, Y, R, and Z numbers are absolute positions in the current coordinate system.

In incremental distance mode (G91), when the XY-plane is selected, X, Y, and R numbers are treated as increments to the current position and Z as an increment from the Z-axis position before the move involving Z takes place; when the YZ- or XZ-plane is selected, treatment of the axis words is analogous.

Many canned cycles use the L word. The L word is optional and represents the number of repeats. L0 is not allowed. The L word is not sticky. The interpretation of the L word depends on the active distance mode:

*   In incremental distance mode (G91), L > 1 in incremental mode means (with the XY-plane selected), that the X and Y positions are determined by adding the given X and Y numbers either to the current X and Y positions (on the first iteration) or to the X and Y positions at the end of the previous go-around (on the subsequent repetitions). The R and Z positions do not change during the repeats
    
*   In absolute distance mode (G90), L > 1 means do the same cycle in the same place several times. Omitting the L word is equivalent to specifying L=1
    

The height of the retract move at the end of each repeat — called clear Z — is determined by the setting of the retract mode: either to the original Z position (if that is above the R position and the retract mode is G98) or otherwise to the R position.

**Troubleshooting**

It's an error if:

*   X, Y, and Z words are all missing during a canned cycle
    
*   A P number is required and a negative P number is used
    
*   An L number is used that does not evaluate to a positive integer
    
*   Rotational axis motion is used during a canned cycle
    
*   Inverse time feed rate is active during a canned cycle
    
*   Cutter radius compensation is active during a canned cycle
    

When the XY plane is active, the Z number is sticky and it's an error if:

*   The Z number is missing and the same canned cycle was not already active
    
*   The R number is less than the Z number
    

When the XZ plane is active, the Y number is sticky and it's an error if:

*   The Y number is missing and the same canned cycle was not already active
    
*   The R number is less than the Y number
    

When the YZ plane is active, the X number is sticky and it's an error if:

*   The X number is missing and the same canned cycle was not already active
    
*   The R number is less than the X number
    

At the very beginning of the execution of any of the canned cycles (with the XY-plane selected), if the current Z position is below the R position, the Z-axis will move in rapid motion to the R position. This happens only once, regardless of the value of L. In addition, at the beginning of the first cycle and each repeat, the following one or two moves are made:

*   A straight traverse parallel to the XY-plane to the given XY-position
    
*   A straight traverse of the Z-axis only to the R position, if it is not already at the R position
    

If the XZ- or YZ-plane is active, the preliminary and in-between motions are analogous.

### High Speed Peck Drill (G73)

The G73 cycle is intended for deep drilling with chip breaking. The retracts in this cycle break the chip but do not totally retract the drill from the hole. It's suitable for tools with long flutes which clear the broken chips from the hole.

Program: G73 X~ Z~ R~ L~ Q~

*   Q~ is the delta increment along the Z-axis
    

**The G73 cycle is as follows:**

*   **Step 1**: Preliminary canned cycle motion
    
*   **Step 2**: Move the Z-axis only at the current feed rate downward by delta or to the Z position (whichever is less deep)
    
*   **Step 3**: Rapid back incrementally in Z 0.010 in.
    
*   **Step 4**: Repeat Step 1 through 3 until the Z position is reached at Step 1.
    
*   **Step 5**: Rapid back down to the current hole bottom, backed off a bit.
    
*   **Step 6**: Retract the Z-axis at traverse rate to clear Z.
    

**Troubleshooting**

It's an error if:

*   The Q number is negative or zero
    
*   The R number is not specified
    

### Cancel Canned Cycles (G80)

To cancels all canned cycles, program: G80

It's okay to program G80 if no canned cycles are in effect. After a G80, the motion mode must be set with G00 (or any other motion mode G word). If motion mode is not set after G80, this error message appears: "**Cannot use axis values without a g code that uses them**."

### Drilling Cycle (G81)

The G81 cycle is intended for drilling.

Program: G81 X~ Y~ Z~ A~ R~ L~

The G81 Cycle is as follows:

*   **Step 1**: Preliminary canned cycle motion.
    
*   **Step 2**: Move the Z-axis only at the current feed rate to the Z position.
    
*   **Step 3**: Retract the Z-axis at the traverse rate to clear Z
    

**Examples**  
These examples demonstrate how the G81 canned cycle works in detail. Other canned cycles work in a similar manner.

**Example**  
The current position is (1, 2, 3), the XY-plane has been selected, and the following line of code is interpreted: G90 G81 G98 X4 Y5 Z1.5 R2.8  
This means that it's in absolute distance mode (G90), old Z retract mode (G98) and the G81 drilling cycle is performed once. The X number and X position are 4. The Y number and Y position are 5. The Z number and Z position are 1.5. The R number and clear Z are 2.8. The following moves take place:

1.  G00 motion parallel to the XY-plane to (4,5,3)
    
2.  G00 motion parallel to the Z-axis to (4,5,2.8)
    
3.  G01 motion parallel to the Z-axis to (4,5,1.5)
    
4.  G00 motion parallel to the Z-axis to (4,5,3)
    

**Example**  
The current position is (1, 2, 3), the XY-plane has been selected, the following line of code is interpreted: G91 G81 G98 X4 Y5 Z-0.6 R1.8 L3  
This means that it's in incremental distance mode (G91), old Z retract mode, and the G81 drilling cycle is repeated three times. The X number is 4, the Y number is 5, the Z number is -0.6 and the R number is 1.8. The initial X position is 5 (=1+4), the initial Y position is 7 (=2+5), the clear Z position is 4.8 (=1.8+3) and the Z position is 4.2 (=4.8-0.6). Old Z is 3.0.  
The first move is a traverse along the Z-axis to (1,2,4.8), since old Z < clear Z.  
The first repeat consists of three moves:

1.  G00 motion parallel to the XY-plane to (5,7,4.8)
    
2.  G01 motion parallel to the Z-axis to (5,7, 4.2)
    
3.  G00 motion parallel to the Z-axis to (5,7,4.8)
    

The second repeat consists of three moves. The X position is reset to 9 (=5+4) and the Y position to 12 (=7+5):

1.  G00 motion parallel to the XY-plane to (9,12,4.8)
    
2.  G01 motion parallel to the Z-axis to (9,12, 4.2)
    
3.  G00 motion parallel to the Z-axis to (9,12,4.8)
    

The third repeat consists of three moves. The X position is reset to 13 (=9+4) and the Y position to 17 (=12+5):

1.  G00 motion parallel to the XY-plane to (13,17,4.8)
    
2.  G01 motion parallel to the Z-axis to (13,17, 4.2)
    
3.  G00 motion parallel to the Z-axis to (13,17,4.8)
    

**Example code using G81 cycle:**  
(Sample Program G81EX18:)  
(Workpiece Size: X4, Y3, Z1)  
(Tool: Tool #6, 3/4” HSS DRILL)  
(Tool Start Position: X0, Y0, Z1)  
N2 G90 G80 G40 G54 G20 G17 G94 G64 (Safety Block)  
N5 G90 G80 G20  
N10 M06 T6 G43 H6  
N15 M03 S1300  
N20 G00 X1 Y1  
N25 Z0.5  
N30 G81 Z-0.25 R0.125 F5 (Drill Cycle Invoked)  
N35 X2  
N40 X3  
N45 Y2  
N50 X2  
N55 X1  
N60 G80 G00 Z1 (Cancel Canned Cycles)  
N65 X0 Y0  
N70 M05  
N75 M30

### Simple Drilling Cycle (G82)

The G82 cycle is intended for drilling.

Program: G82 X~ Y~ Z~ A~ R~ L~ P~

The G82 cycle is as follows:

*   **Step 1**: Preliminary canned cycle motion
    
*   **Step 2**: Move the Z-axis only at the current feed rate to the Z position.
    
*   **Step 3**: Dwell for the P number of seconds.
    
*   **Step 4**: Dwell for the P number seconds.
    

### Peck Drilling Cycle (G83)

The G83 cycle (often called peck drilling) is intended for deep drilling or milling with chip breaking. The retracts in this cycle clear the hole of chips and cut off any long stringers (which are common when drilling in aluminum).

Program: G83 X~ Y~ Z~ A~ R~ L~ Q~

*   Q~ is a delta increment along the Z-axis
    

The G83 cycle is as follows:

*   **Step 1**: Preliminary canned cycle motion.
    
*   **Step 2**: Move the Z-axis only at the current feed rate downward by delta or to the Z position, whichever is less deep.
    
*   **Step 3**: Rapid back out to the clear Z.
    
*   **Step 4**: Repeat Steps 1 through 3 until the Z position is reached at Step 1.
    
*   **Step 5**: Rapid back down to the current hole bottom, backed off a bit.
    
*   **Step 6**: Retract the Z-axis at traverse rate to clear Z.
    

**Troubleshooting**

It's an error if:

*   The Q number is negative or zero
    

### Tapping Cycle (G84)

The G84 cycle is intended for tapping. This cycle rotates the spindle clockwise to tap a pre-drilled hole; when the bottom of the hole is reached, the spindle rotates in the reverse direction and exits the hole.

Program: G84 X~ Y~ Z~ R~ P~ F~

*   X~ is the position of the hole on the X-axis
    
*   Y~ is the position of the hole on the Y-axis
    
*   Z~ is the depth, tapping from the R-plane to the Z-depth
    
*   R~ is the position of the retract plane (R-plane)
    
*   P~ is the number of seconds to dwell
    
*   F~ is the feed rate
    

The G84 cycle is as follows:

*   **Step 1**: Preliminary canned cycle motion.
    
*   **Step 2**: Start the spindle forward.
    
*   **Step 3**: Move the Z-axis at the programmed feed rate (F~) to the Z-depth.
    
*   **Step 4**: Reverse the spindle.
    
*   **Step 5**: Dwell for the P number of seconds.
    
*   **Step 6**: Retract the Z-axis at the programmed feed rate (F~) to the R-plane.
    

This cycle uses a P word, where P specifies the number of seconds to dwell. The P word is optional – if it is not included, PathPilot calculates a dwell for you (half of a second per 1000 RPM).

Spindle speed must be commanded before calling a G84 cycle. Feed rate override is ignored during a tapping cycle. Feedhold is ignored until the return operation is executed. After the tapping operation is completed, either a G98 or G99 command controls the return height — G99 returns the tool to the R-plane; G98 returns the tool to the initial height.

**Example**  
N40 T51 G43 H51 M6  
N45 S400 M3  
N50 G54  
N55 M8  
N65 G0 X0.5 Y-0.75  
N70 G43 Z0.6 H51  
N80 G0 Z0.2  
N85 S400  
N90 G98 G84 X0.5 Y-0.75 Z-0.605 R0.2 F20.  
N95 X1.0 Y -1.25  
N100 G80  
N105 G0 Z0.6

### Boring Cycle (G85)

The G85 cycle is intended for boring or reaming, but could be used for drilling or milling.

Program: G85 X~ Y~ Z~ A~ R~ L~

The G85 cycle is as follows:

**Step 1**: Preliminary canned cycle motion.  
**Step 2**: Move the Z-axis only at the current feed rate to the Z position.  
**Step 3**: Retract the Z-axis at the current feed rate to clear Z.

### Boring Cycle (G86)

The G86 cycle is intended for boring. This cycle uses a P number for the number of seconds to dwell.

Program: G86 X~ Y~ Z~ A~ R~ L~ P~

The G86 cycle is as follows:

*   **Step 1**: Preliminary canned cycle motion.
    
*   **Step 2**: Move the Z-axis only at the current feed rate to the Z position.
    
*   **Step 3**: Dwell for the P number of seconds.
    
*   **Step 4**: Stop the spindle turning.
    
*   **Step 5**: Retract the Z-axis at traverse rate to clear Z.
    
*   **Step 6**: Restart the spindle in the direction it was going.
    
*   **Step 7**: Move the Z-axis only at the current feed rate to the Z position.
    

**Troubleshooting**

It's an error if:

*   The spindle is not turning before this cycle is executed
    

### Boring Cycle (G88)

The G88 cycle is intended for boring and uses a P word, where P specifies the number of seconds to dwell.

Program: G88 X~ Y~ Z~ A~ R~ L~ P~

The G88 cycle is as follows:

*   **Step 1**: Preliminary canned cycle motion.
    
*   **Step 2**: Move the Z-axis only at the current feed rate to the Z position.
    
*   **Step 3**: Dwell for the P number of seconds.
    
*   **Step 4**: Stop the spindle turning.
    
*   **Step 5**: Stop the program so the operator can retract the spindle manually.
    
*   **Step 6**: Restart the spindle in the direction it was going.
    

### Boring Cycle (G89)

The G89 cycle is intended for boring. This cycle uses a P number, where P specifies the number of seconds to dwell.

Program: G89 X~ Y~ Z~ A~ R~ L~ P~

The G89 cycle is as follows:

*   **Step 1**: Preliminary canned cycle motion.
    
*   **Step 2**: Move the Z-axis only at the current feed rate to the Z position.
    
*   **Step 3**: Dwell for the P number of seconds.
    
*   **Step 4**: Retract the Z-axis at the current feed rate to clear Z.
    

Programming M-Code
------------------

Read the following sections for reference:

### Supported M-Codes Reference



*          M-Code        :          M00        
  *          Description        :          Program stop        
*          M-Code        :          M01        
  *          Description        :          Optional program stop        
*          M-Code        :          M02        
  *          Description        :          Program end        
*          M-Code        :          M03, M04        
  *          Description        :          Rotate spindle clockwise/counterclockwise        
*          M-Code        :          M05        
  *          Description        :          Stop spindle rotation        
*          M-Code        :          M07, M08        
  *          Description        :          Coolant on        
*          M-Code        :          M09        
  *          Description        :          All coolant off        
*          M-Code        :          M30        
  *          Description        :          Program end and rewind        
*          M-Code        :          M48        
  *          Description        :          Enable speed and feed override        
*          M-Code        :          M49        
  *          Description        :          Disable speed and feed override        
*          M-Code        :          M64        
  *          Description        :          Activate output relays        
*          M-Code        :          M65        
  *          Description        :          Deactivate output relays        
*          M-Code        :          M66        
  *          Description        :          Wait on an input         NOTE:  M64 through M66 is only useful with a USB M-Code I/O Interface Kit (PN 32616).        
*          M-Code        :          M98        
  *          Description        :          Call subroutine        
*          M-Code        :          M99        
  *          Description        :          Return from subroutine/repeat        
*          M-Code        :          M301, M302, M303        
  *          Description        :          USB camera control        


### Program Stop and Program End (M00, M01, M02, and M30)

To stop a running program temporarily, regardless of the optional stop switch setting, program: M00

To stop a running program temporarily, but only if the optional stop switch is on, program: M01

It's okay to program M00 and M01 in MDI mode, but the effect probably won’t be noticeable because normal behavior in MDI mode is to stop after each line of input.

If a program is stopped by an M00, M01, selecting Cycle Start restarts the program at the following line of the G-code program.

To end a program, program: M02 or M30.

M02 leaves the next line to be executed as the M02 line. M30 rewinds the G-code file. These commands can have the following effects:

*   Axis offsets are set to zero (like G92.2) and origin offsets are set to the default (like G54)
    
*   Selected plane is set to XY (like G17)
    
*   Distance mode is set to absolute (like G90)
    
*   Feed rate mode is set to units per minute mode (like G94)
    
*   Feed and speed overrides are set to on (like M48)
    
*   Cutter Compensation is turned off (like G40)
    
*   The spindle is stopped (like M05)
    
*   The current motion mode is set to G01 (like G01)
    
*   Coolant is turned off (like M09)
    

No more lines of code in the file are executed after the M02 or M30 command is executed. Selecting Cycle Start starts the program back at the beginning of the file.

**Display Information and Capture Images During an M00 or M01 Break**

**Display Information with Images**

If the comment occurs on a line with M00 or M01, and contains a file name with a .jpg or .png extension, PathPilot displays the image in the Tool Path display when the program reaches the M00 or M01 break.

To display an image during an M00 or M01 break:

1.  Move an image file with a .jpg or .png extension to the PathPilot controller in one of the following locations:
    
    1.  In the same folder as the G-code program
        
    2.  In an images folder within the G-code program's folder
        
    3.  In an images folder within the home directory
        
2.  Program an M00 or M01 break, and, using parentheses, type the full file name of the image (including its extension).
    

**Example**  
M01 (Op1\_Setup.jpg) displays the image file on the Tool Path display.

3.  The image file displays on the Tool Path display.
    

**Display Information with Text**

To display a message on the Tool Path display:

1.  Program an M00 or M01 break, and, using parentheses, type a message that you'd like to display on the screen.
    

**Example**  
M01 (Check coolant nozzles are pointed correctly) displays Check coolant nozzles are pointed correctly across the bottom of the Tool Path display.

2.  The message displays on the Tool Path display.
    

**Capture Images with a USB Camera**

In addition to displaying information like pictures or messages during an M01 break, you can also use a USB camera (if installed) to take a picture.

To use M01 to take pictures:

1.  Add M01 (op1\_setup.jpg) into your G-code program.
    
2.  Run the G-code program.
    
3.  When PathPilot executes the M01 it looks to see if the comment contains a file name.
    
    1.  If there isn't a file name: The comment is shown as instructional text across the tool path.
        
    2.  If there is a file name, but the file doesn’t exist yet and the extension is .jpg, .png, or .jpeg: The USB cameras are initialized and shown in the tool path display.
        
4.  Select the **Shutter** button to take the picture and create the **op1\_setup.jpg** file.  
    In future runs of the G-code program, op1\_setup.jpg will display to the operator for instructional purposes on the workpiece.
    

For more information, see “[Use a USB Camera](https://knowledgebase.tormach.com/pcnc-1100/pathpilot-interface-pcnc-1100#Use-a-USB-Camera)”.

### Spindle Control (M03, M04, and M05)

To start the spindle turning clockwise at the currently programmed speed, program: M03

To start the spindle turning counterclockwise at the currently programmed speed, program: M04

The speed is programmed by the S word.

To stop the spindle from turning, program: M05

It's okay to use M03 or M04 if the spindle speed is set to 0; if this is done, the spindle won’t start turning. If later the spindle speed is set above 0, the spindle starts turning. It is permitted to use M03 or M04 when the spindle is already turning, or to use M05 when the spindle is already stopped.

### Tool Change (M06)

To execute a tool change sequence, program: M06

M06 behaves differently depending on whether or not the machine is equipped with an Automatic Tool Changer (ATC):

*   If you have an ATC:
    
    *   If the requested tool (T number) is assigned to the carousel, M06 initiates an automatic tool change.
        
    *   If the tool is not assigned to the carousel, you're prompted to manually change the tool and select Cycle Start to confirm the tool change. This resumes the program.
        
*   If you don't have an ATC:
    
    *   M06 commands the machine, stops the spindle, pauses program execution, and prompts operator to change tools by flashing Tool Change LED.
        
    *   The program resumes after you select Cycle Start to confirm that the tool has been changed.
        

We recommend putting the T~, the M06, and the G43 H~ on one line (block) of code.

**Example**  
N191 M06 T3 G43 H3

### Coolant Control (M07, M08, and M09)

To turn coolant on, program: M07

To turn flood coolant on, program: M08

To turn all coolant off, program: M09

It's always okay to use any of these commands, regardless of what coolant is on or off.

### Override Control (M48 and M49)

To enable the speed and feed override, program: M48

To disable both overrides, program: M49

It's okay to enable or disable the switches when they are already enabled or disabled.

### Feed Override Control (M50)

To enable the feed rate override control, program: M50 P1

The P1 is optional.

To disable the feed rate control, program: M50 P0

When feed rate override control is disabled, the feed rate override slider has no influence, and all motion is executed at programmed feed rate (unless there is an adaptive feed rate override active).

### Spindle Speed Override Control (M51)

To enable the spindle speed override control, program: M51 P1

The P1 is optional.

To disable the spindle speed override control, program: M51 P0

When spindle speed override control is disabled, the spindle speed override slider has no influence, and the spindle speed is equal to the value of the S word.

### Set Current Tool Number (M61)

To change the current tool number while in MDI or manual mode, program: M61 Q~

*   Q~ is the tool number
    

**Troubleshooting**

It's an error if:

*   Q~ is not 0 or greater
    

### Set Output State (M64 and M65)

**NOTE: These commands are only useful when the machine is equipped with the USB M-Code I/O Interface Kit.**

There are four output relays available on the USB I/O module.

To activate output relays (contact close), program: M64

To deactivate output relays (contact open), program: M65

There are four contacts, numbered from 0 to 3. The contact is specified by the P word.

**Example**

*   Activating the first relay: M64 P0
    
*   Activating the second relay: M64 P1
    

The outputs are deactivated using M65 with the P word specifying the relay.

**Example**

*   Deactivating the second relay: M65 P1
    
*   Deactivating the fourth relay: M65 P3
    

There is only one P word and one relay per line. Each relay command must be done on an individual line.

The following is legal:

M64 P0  
M64 P2  
M64 P3

The following is not legal:

M64 P023  
M64 P0 P2 P3

### Wait on Input (M66)

**NOTE: This command is only useful when the machine is equipped with the USB M-Code I/O Interface Kit.**

There are four digital inputs available on the USB I/O module.

M66 P- | E- <L->

*   P- is the digital input number from 0 to 3.
    
*   L- is the wait mode type:
    
    *   Mode 0: IMMEDIATE – no waiting, returns immediately. The value of the input at that time is stored in parameter #5399.
        
    *   Mode 1: RISE – waits for the selected input to perform a rise event.
        
    *   Mode 2: FALL – waits for the selected input to perform a fall event.
        
    *   Mode 3: HIGH – waits for the selected input to go to the HIGH state.
        
    *   Mode 4: LOW – waits for the selected input to go to the LOW state.
        
*   Q- is the timeout in seconds for waiting
    

The Q value is ignored if the L word is zero (IMMEDIATE). A Q value of zero is an error if the L word is non-zero.

### USB Camera Control (M301, M302, M303)

PathPilot supports three new M-codes to control cameras within G-code programs: M301, M302, and M303. Example use cases:

*   Record only across M01 stop where the operator needs to flip a workpiece or change a tool.
    
*   Create short videos that focus on unique aspects of the program to reduce later video editing.
    
*   Record USB IO integration operations with robots or other devices (pneumatic vises, etc.).
    
*   Monitor process on a workpiece by including M303 through the program.
    

To begin a video recording by an attached camera, program: M301

To stop a video recording by an attached camera, program: M302

To take a picture with an attached camera, program: M303  
For more information, see “[Use a USB Camera](https://knowledgebase.tormach.com/pcnc-1100/pathpilot-interface-pcnc-1100#Use-a-USB-Camera)”.

Programming Input Codes
-----------------------

Read the following sections for reference:

### Feed Rate (F)

To set the feed rate, program: F~

Depending on the setting of the feed mode toggle, the rate may be in units-per-minute or units-per-rev of the spindle. The units are those defined by the G20/G21 mode. The feed rate may sometimes be overridden.

### Spindle Speed (S)

To set the speed in revolutions per minute (rpm) of the spindle, program: S~

The spindle turns at the commanded speed when it has been programmed to start turning. It's okay to program an S word whether the spindle is turning or not. If the speed override switch is enabled and not set at 100 percent, the speed is different from what is programmed. It's okay to program S0, but the spindle does turn if that is done.

**Troubleshooting**

It's an error if:

*   The S number is negative
    

### Change Tool Number (T)

It's your responsibility to make sure that the machine is in a safe place for changing tools (for example, by using G30). This allows optimization of motion which can save time. You can provide a pause for manual intervention with M00 or M01 before the tool change.

**Troubleshooting**

It's an error if:

*   A negative T number is used
    
*   A T number larger than 1000 is used
    

Advanced Programming
--------------------

Parameter and expression programming language features are not used in common G-code application (hand coding), G-code created by PathPilot conversational programming, or the majority of third-party CAM-programming systems.

There are significant differences between controls in the way parameters work. Do not assume that code from another control works in the same way with the operating system. We don't recommend writing parametric G-code — it's difficult to debug, and difficult for another operator to understand. Modern CAM virtually eliminates the need for it.

Read the following sections for reference:

### Parameters

Read the following sections for reference:

**Parameters Reference**

The RS274/NGC language supports parameters. Parameters are analogous to variables in other programming languages. PathPilot maintains an array of 10,320 numerical parameters. Many of them have specific uses. The parameters that are associated with fixtures are persistent over time. Other parameters are undefined when the operating system is loaded. The parameters are preserved when the interpreter is reset. Parameters 1 to 1000 can be used by the code of part-programs.

There are several types of parameters of different purpose and appearance. The only value type supported by parameters is floating-point; there are no string, Boolean or integer types in G-code like in other programming languages. However, logic expressions can be formulated with Boolean operators (AND, OR, XOR, and the comparison operators EQ, NE, GT, GE ,LT, LE), and the MOD, ROUND, FUP and FIX operators support integer arithmetic.

**Parameter Syntax**

There are three types of parameters, numbered, named local, and named global. The type of the parameter is defined by its syntax:

*   Numbered - #4711
    
*   Named local - #<localvalue>
    
*   Named global - #<\_globalvalue>
    

**Parameter Scope**

The scope of a parameter is either global or local within a subroutine. The scope of each parameter is inferred from its syntax. Subroutine parameters and named local parameters have local scope. Named global parameters and all numbered parameters starting from #31 are global in scope. RS274/NGC uses lexical scoping. In a subroutine, only the local parameters defined therein and any global parameters are visible. The local parameters of a calling procedure are not visible in a called procedure.

**Behavior of Uninitialized Parameters**

Uninitialized global parameters and unused subroutine parameters return the value zero when used in an expression. Uninitialized named parameters signal an error when used in an expression.

**Parameter Mode**

The mode of a parameter can either be read/write or read-only. Read/write parameters may be assigned values within an assignment statement. Read-only parameters cannot be assigned values. They may appear in expressions, but not on the left-hand side of an assignment statement.

**Persistence and Volatility**

Parameters can either be persistent or volatile. When the operating system is powered off, volatile parameters lose their values and are reset to zero. The values of persistent parameters are saved in a disc file and restored to their previous values when the operating system is powered on again. All parameters except numbered parameters in the current persistent range (5163 to 5390) are volatile.

**Intended Use**

Numbered parameters in the range #31-#5000, named global, and local parameters are available for general-purpose storage of floating-point values, like intermediate results, flags, etc., throughout program execution. They are read/write (can be assigned a value). Subroutine parameters, numbered parameters #1-#30, and system parameters are read-only and not available for general use. Subroutine parameters are used to hold the actual parameters passed to a subroutine. Numbered parameters in the range of #1-#30 are used to access offsets of coordinate systems. System parameters are used to determine the current running version and are read-only.

**Numbered Parameters Reference**

A numbered parameter is recognized by the pound symbol (#) followed by an integer between 1 and 5399. The parameter is referred to by this integer, and its value is whatever number is stored in the parameter. A value is stored in a parameter with the (=) operator.

**Example**: #3 = 15 (set parameter 3 to 15)

A parameter setting does not take effect until after all parameter values on the same line have been found. For example, if parameter 3 has been previously set to 15 and the line: #3=6 G01 X#3 is interpreted, a straight move to a point where X = 15 occurs before the value of parameter 3 is set to 6.

The # symbol takes precedence over other operations. For example, #1+2 means the number found by adding 2 to the value of parameter 1, not the value found in parameter 3. Of course, #\[1+2\] does mean the value found in parameter 3.

The # character may be repeated; for example ##2 means the value of parameter whose index is the (integer) value of parameter 2. PathPilot maintains a number of read-only parameters. Only parameters for the relevant axes are maintained: (X Y Z A) for mill and (X Z) for lathe. The remaining parameters for unused axes are undefined.

**Read-Only Parameters**

*   1-30: Subroutine local parameters of call arguments. These parameters are local to the subroutine. For further information, see Programming with Subroutines later in this chapter
    
*   31-5000: G-code operator parameters. These parameters are global in G-code file
    
*   5061-5070: Result of G38.2 probe (X Y Z A B C U V W)
    
*   5161-5169: G28 home for (X Y Z A B C U V W)
    
*   5181-5189: G30 home for (X Y Z A B C U V W)
    
*   5210: 1 if G92 offsets are active, 0 if not
    
*   5211-5219: G92 offset (X Y Z A B C U V W)
    
*   5220: Current coordinate system number 1-9 for G54 - G59.3
    
*   5221-5230: Coordinate System 1, G54 (X Y Z A B C U V W R) – R denotes XY rotation angle around Z-axis
    
*   5241-5250: Coordinate System 2, G55 (X Y Z A B C U V W R)
    
*   5261-5270: Coordinate System 3, G56 (X Y Z A B C U V W R)
    
*   5281-5290: Coordinate System 4, G57 (X Y Z A B C U V W R)
    
*   5301-5310: Coordinate System 5, G58 (X Y Z A B C U V W R)
    
*   5321-5330: Coordinate System 6, G59 (X Y Z A B C U V W R)
    
*   5341-5350: Coordinate System 7, G59.1 (X Y Z A B C U V W R)
    
*   5361-5370: Coordinate System 8, G59.2 (X Y Z A B C U V W R)
    
*   5381-5390: Coordinate System 9, G59.3 (X Y Z A B C U V W R)
    
*   5399: Result of M66 – check or wait for input
    
*   5400: Current tool number
    
*   5401-5409: Tool offset (X Y Z A B C U V W)
    
*   5410: Current tool diameter
    
*   5411: Current tool front angle
    
*   5412: Current tool back angle
    
*   5420-5428: Current position including offsets in current program units (X Y Z A B C U V W)
    

**Subroutine Parameters Reference**

Subroutine parameters are specifically reserved for call arguments. By definition, these are parameters #1-#30 and are local to the subroutine.

**Named Parameters Reference**

Named parameters work like numbered parameters, but are easier to read and remember. All parameter names are converted to lowercase and have spaces and tabs removed. Named parameters must be enclosed with < > marks.

#<named parameter here> is a local named parameter. By default, a named parameter is local to the scope in which it is assigned.

You can’t access a local parameter outside of its subroutine. This is so two subroutines can use the same parameter names without fear of one subroutine overwriting the values in another.

#<\_global named parameter here> (i.e., name starting with an underscore) is a global named parameter. They are accessible from within called subroutines and may set values within subroutines that are accessible to the caller. As far as scope is concerned, they act just like regular numeric parameters. They are not made persistent by storage in a file.

The global parameters \_a, \_b, \_c, . . . \_z are reserved for special use. Do not use these parameters.

**Examples**

*   #<\_endmill\_dia> = 0.049 is a declaration of named global variable.
    
*   #<\_endmill\_rad> = \[#<\_endmill\_dia>/2.0\] is a reference to previously declared global variable.
    
*   o100 call \[0.0\] \[0.0\] \[#<\_inside\_cutout>-#<\_endmill\_dia>\] \[#<\_Zcut>\] \[#<\_feedrate>\] is mixed literal and named parameters.
    

### Expressions

An expression is a set of characters starting with a left bracket (\[) and ending with a right bracket (\]). Located between the brackets are numbers, parameter values, binary operators, functions, and other expressions. An expression is evaluated to produce a number. An example of an expression is:

\[1 + acos\[0\] - \[#3 \*\* \[4.0/2\]\]\]

All expressions on a line are evaluated when the line is read and before anything on the line is executed.

Read the following sections for reference:

**Binary Operators Reference**

Binary operators only appear inside expressions. There are three types of binary operators: mathematical, logical, and relational.

There are four basic mathematical operations: addition (+), subtraction (-), multiplication (\*), and division (/). In addition, the modulus operation (MOD) finds the remainder after division of one number by another number. The power operation (\*\*) of raising the number on the left of the operation to the power on the right. There are three logical operations: non-exclusive or (OR), exclusive or (XOR), and logical and (AND).

The relational operators are equality (EQ), inequality (NE), strictly greater than (GT), greater than or equal to (GE), strictly less than (LT), and less than or equal to (LE).

Binary operators are divided into several groups according to their precedence as follows, from highest to lowest:

1.  \*\*
    
2.  \* / MOD
    
3.  \+ -
    
4.  EQ NE GT GE LT LE
    
5.  AND OR XOR
    

If operations in different precedence groups are strung together, operations with a higher precedence are performed before operations with a lower precedence. If an expression contains more than one operation with the same precedence, the operation on the left is performed first.

**Example**

\[2.0 / 3 \* 1.5 - 5.5 / 11.0\] is equivalent to \[\[\[2.0 / 3\] \* 1.5\] - \[5.5 / 11.0\]\]  
which is equivalent to \[1.0 - 0.5\]  
which is  
0.5

The logical operations and modulus are to be performed on any real numbers, not just on integers. The number zero is equivalent to logical false, and any non-zero number is equivalent to logical true.

**Functions Reference**

The available functions are:

*   ATAN\[Y\]/\[X\]: Four quadrant inverse tangent
    
*   ABS\[arg\]: Absolute value
    
*   ACOS\[arg\]: Inverse cosine
    
*   ASIN\[arg\]: Inverse sine
    
*   COS\[arg\]: Cosine
    
*   EXP\[arg\]: e raised to the given power (ex)
    
*   FIX\[arg\]: Round down to integer
    
*   FUP\[arg\]: Round up to integer
    
*   ROUND\[arg\]: Round to nearest integer
    
*   LN\[arg\]: Base-e logarithm
    
*   SIN\[arg\]: Sine
    
*   SQRT\[arg\]: Square root
    
*   TAN\[arg\]: Tangent
    
*   EXISTS\[arg\]: Check named parameter
    

### Subroutines

Subroutines are subprograms that are called from inside another program.

Read the following sections for reference:

**Subroutines Reference**

Subroutines are identified in a program by a unique subroutine label. The subroutine label is the letter o followed by an integer (with no sign) between 0 and 99999 written with no more than five digits (000009 is not permitted, for example) or a string of characters surrounded by <> symbols.

Examples of valid subroutine labels:

*   o123
    
*   o99999
    
*   o<my test code>
    

Subroutine labels may be used in any order, but they must be unique in a program. Each subroutine label must be followed by a subroutine keyword. The subroutine keyword defines the action associated with the subroutine label.

Valid subroutine keywords and their meanings are:

*   Sub: Begin subroutine definition
    
*   Endsub: End of subroutine definition
    
*   Call: Call the subroutine
    
*   Do/while/endwhile: Execute the subroutine while a condition is true
    
*   Repeat/endrepeat: Execute the subroutine while a condition is true
    
*   If/elseif/else/endif: Conditionally execute the subroutine
    
*   Break: Break out of a while or if/elseif statement
    
*   Continue: Skip remaining code and restart at top of while or repeat loop
    
*   Return: Return a value
    

The sub and endsub keywords are used to define the beginning and end a subroutine. All lines of code between the sub and endsub keywords are considered to be part of the subroutine.

**Example of sub, endsub, call:**

o100 sub  
G53 G00 X0 Y0 Z0 (rapid move to machine home)  
o100 endsub  
...  
o100 call (call the subroutine here)  
M02

Subroutines can either be defined in the program file or in a separate file. If the subroutine is defined in the same file as the main program that calls the subroutine, it must be defined before the call statement.

For example, this is valid:

o100 sub  
G53 G00 X0 Y0 Z0 (rapid move to machine home)  
o100 endsub  
...  
o100 call (call the subroutine here)  
M02

But this is not:

o100 call (call the subroutine here)  
M02  
o100 sub  
G53 G00 X0 Y0 Z0 (rapid move to machine home)  
o100 endsub  
...

A subroutine can be a separate file as long as:

*   The file is named the same as your call.
    
*   The file includes a sub and endsub in the file.
    
*   The file is in the directory **/subroutines**.
    
*   The file name only includes lowercase letters, numbers, dashes, and underscores.
    
*   The file only contains a single subroutine definition.
    
*   The file ends with the extension .nc.
    

**NOTE: File names are lowercase letters only. o<MyFile> is converted to o<myfile> by the interpreter.**

To execute a subroutine in a program, it must be called. To call a subroutine, program o~ call where ~ is the subroutine name. The subroutine name may be either a named file, a numbered file, or an expression that evaluates to a valid subroutine label.

*   Expression example: o\[#101+2\] call
    
*   Named file example: o<myfile> call
    
*   Numbered file example: o123 call
    

o~ call takes up to 30 optional arguments, which are passed to the subroutine as #1, #2 , . . . , #N. Unused parameters from #N+1 to #30 have the same value as in the calling context.

Parameters #1-#30 are local to the subroutine. On return from the subroutine, the values of parameters #1 through #30 (regardless of the number of arguments) are restored to the values they had before the call.

The following calls a subroutine with three arguments: o200 call \[1\] \[2\] \[3\]

Because 1 2 3 is parsed as the number 123, the parameters must be enclosed in square brackets.

Subroutine bodies may be nested.

*   Nested subroutines may only be called after they are defined.
    
*   They may be called from other functions, and may call themselves recursively if it makes sense to do so.
    
*   The maximum subroutine nesting level is 10.
    

Subroutines do not have return values, but they may change the value of parameters above #30 and those changes are visible to the calling G-code. Subroutines may also change the value of global named parameters.

**Conditional Subroutines Reference**

Subroutines can be conditionally executed using the if/endif or the if/else/elseif/endif keyword constructs.

**if/endif**

The if/endif conditional will execute a block of code following theif keyword only when the if argument evaluates to true.

**If/endif example:**

o100 sub  
(notice that the if-endif block uses a different number)  
o110 if \[#2 GT 5\]  
(some code here)  
o110 endif  
(some more code here)  
o100 endsub

**if/elseif/else/endif**

The if/elseif/else/endif conditional will execute the block of code following the if keyword when its argument evaluates to true. If the argument evaluates to false, then the code following each elseif is executed as long as the associated elseif argument evaluates to true. If no elseif keywords are present, or if all elseif arguments evaluate to false, than the code following the else keyword is executed.

**If/elseif/endif example:**

o102 if \[#2 GT 5\] (if parameter #2 is greater than 5 set F100)  
F100  
o102 elseif \[#2 LT 2\] (else if parameter #2 is less than 2 set F200)  
F200  
o102 else (else if parameter #2 is 2 through 5 set F150)  
F150  
o102 endif

**Repeating Subroutines Reference**

Subroutines can be repeated a finite number of times using the repeat/endrepeat keyword.

**Repeat example:**

(Mill 5 diagonal shapes)  
G91 (Incremental mode)  
o103 repeat \[5\]  
... (insert milling code here)  
G00 X1 Y1 (diagonal move to next position)  
o103 endrepeat  
G90 (Absolute mode)

**Looping Subroutines Reference**

Subroutines can be looped using the do/while or while/endwhile keyword constructs.

**do/while**

The do/while loop executes a block of code once and continues to execute the code block until the while argument evaluates to true.

**Do/while loop example:**

#1 = 0 (assign parameter #1 the value of 0)  
o100 do  
(debug, parameter 1 = #1)  
o110 if \[#1 EQ 2\]  
#1 = 3 (assign the value of 3 to parameter #1)  
(msg, #1 has been assigned the value of 3)  
o100 continue (skip to start of loop)  
o110 endif  
(some code here)  
#1 = \[#1 + 1\] (increment the test counter)  
o100 while \[#1 LT 3\]  
M02

**while/endwhile**

The while/endwhile repeats a set of statements an indefinite number of times, as long as the while argument evaluates to true.

**While/endwhile example:**

(draw a sawtooth shape)  
G00 X1 Y0 (move to start position)  
#1 = 1 (assign parameter #1 the value of 0)  
F25 (set a feed rate)  
o101 while \[#1 LT 10\]  
G01 X0  
G01 Y\[#1/10\] X1  
#1 = \[#1+1\] (increment the test counter)  
o101 endwhile  
M02 (end program)

The following statements cause an error message and abort the interpreter:

*   A return or endsub not within a sub definition
    
*   A label on repeat which is defined elsewhere
    
*   A label on while which is defined elsewhere and not referring to a do
    
*   A label on if defined elsewhere
    
*   A undefined label on else or elseif
    
*   A label on else, elseif or endif not pointing to a matching if
    
*   A label on break or continue which does not point to a matching while or do
    
*   A label on endrepeat or endwhile no referring to a corresponding while or repeat
    

_Looking for more information?_

_This is a section of the PCNC 1100 operator's manual. To view the whole manual, go to_ [_Tormach document UM10349_](https://tormach.com/docs/download/assetlink/asset_id/39)_._

_If you have additional questions, we can help. Create a support ticket with Tormach Technical Support at_ [http://tormach.com/how-to-submit-a-support-ticket](http://tormach.com/how-to-submit-a-support-ticket) _for guidance on how to proceed._