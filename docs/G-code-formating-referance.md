# G-Code Syntax & Formatting Reference | Tormach
A permissible block of input code is made up of the following programming elements, in order, with the restriction that there is a maximum of 256 characters allowed on a line:

*   _(Optional)_ Block delete character (/)
*   _(Optional)_ Line number
*   Any number of words, parameter settings, and comments
*   End of line marker (carriage return or line break)

Programs are limited to 999,999 lines of code.

Spaces and tabs are allowed anywhere on a line of code and do not change the meaning of the line, except inside comments. Blank lines are allowed in the input, but they’re ignored. Input is not case sensitive (except in comments), so any letter outside a comment may be in uppercase or lowercase without changing the meaning of a line.

> **EXAMPLE** G00 x +0. 12 34y 7 is equal to G00 x+0.1234 y7

A line may have:

*   Any number of G words, but two G words from the same modal group may not appear on the same line.
*   Zero to four M words, but two M words from the same modal group may not appear on the same line.
*   For all other legal letters, a line may have only one word beginning with that letter.

Any input not explicitly allowed is illegal, and causes the interpreter to either signal an error or ignore the line.

PathPilot omits blocks of code that are prefixed with a block delete character (/).

PathPilot sometimes ignores things it doesn’t understand. If a command doesn’t work as expected, or does nothing, make sure that it’s correctly typed. PathPilot doesn’t check for excessively high machining feeds or speeds, and it doesn’t detect situations where a legal command will do something unfortunate (like machining a fixture).

LINE NUMBERS
------------

A line number is indicated by the following, in the order listed:

1.  The letter N
2.  An integer (with no sign) between 0 and 99,999,999 (which must be written without commas)

Line numbers may be repeated, or used out of order, but that’s rare in normal practice. A line number isn’t required, and is often omitted.

WORDS
-----

A word is indicated by the following, in the order listed:

1.  A letter other than N or O
2.  A real value

LETTERS
-------

Words may begin with any of the following letters, except N or O:

> **NOTE:** Several letters (I, J, K, L, P and R) may have different meanings in different contexts.

*   A: A-axis of mill
*   B: B-axis of mill
*   C: C-axis of mill
*   D: Tool radius compensation number
*   F: Feed rate
*   G: General function
*   H: Tool length offset index
*   I: X-axis offset for arcs, or X offset in a **G87** canned cycle
*   J: Y-axis offset for arcs, or Y offset in a **G87** canned cycle
*   K: Z-axis offset for arcs, or Z offset in a **G87** canned cycle
*   L: Number of repetitions in canned cycles and subroutines, or key used with **G10**
*   M: Miscellaneous function
*   N: Line number
*   O: Subroutine label number
*   P: Dwell time in canned cycles, dwell time with **G04**, key used with **G10**, or tapping depth in **M871** through **M874**
*   Q: Feed increment in a **G83** canned cycle, or repetitions of subroutine call
*   R: Arc radius, or canned cycle retract level
*   S: Spindle speed
*   T: Tool selection
*   U: Synonymous with A
*   V: Synonymous with B
*   W: Synonymous with C
*   X: X-axis of mill
*   Y: Y-axis of mill
*   Z: Z-axis of mill

VALUES
------

A real value is one of the following:

*   An explicit number (like 341, or -0.8807)
*   An expression (like \[2+2.4\])
*   A parameter value (like #88)
*   A unary operation value (like acos\[0\])

> **NOTE**: In the command examples that we use, the tilde symbol (~) stands for a real value. If L~ is written in an example, the ~ is often referred to as the L number. Similarly the ~ in H~ may be called the H number, and so on for any other letter.

A number is a subset of a real value. Processing a real value to come up with a number is called evaluating. An explicit number evaluates to itself.

Explicit numbers have the following rules (in this case, a digit is a single character, 0 through 9):

*   A number must consist of the following, in the order listed:

1.  An optional plus or minus sign
2.  Zero to many digits
3.  (Optional) One decimal point
4.  Zero to many digits

*   There must be at least one digit somewhere in the number.
*   It must be either an integer (no decimal point) or a decimals (decimal point).
*   It may have any number of digits (subject to line length limitations).

> **NOTE:** PathPilot only keeps 17 significant figures, which is enough for all known applications.

*   A non-zero number with no sign as the first character is assumed to be positive.

Initial zeros (a zero before the decimal point and the first non-zero digit) and trailing zeros (a zero after the decimal point and the last non-zero digit) are allowed, but not required. A number written with initial or trailing zeros has the same value when it is read as if the extra zeros were not there.

Numbers used for specific purposes by PathPilot are often restricted to some finite set of values, or to some range of values. In many uses, decimal numbers must be close enough to an integer to be accepted as a valid input. A decimal number which is supposed to be close to an integer is considered close enough if it is within 0.0001 of an integer.

ORDER OF EXECUTION
------------------

If a parameter setting of the same parameter is repeated on a line (like #3=15 #3=6), only the last setting takes effect. It’s illogical, but not illegal, to set the same parameter twice on the same line.

The order of items on a line doesn’t determine the order of execution on the commands.

Three types of items’ order may vary on a line (as given earlier in this section):

*   Word May be reordered in any way without changing the meaning of the line.
*   Parameter Setting If it’s reordered, there is no change in the meaning of the line unless the same parameter is set more than once. In this case, only the last setting of the parameter takes effect.

> **EXAMPLE** When the line #3=15 #3=6 is interpreted, the value of parameter 3 is 6. If the order is reversed to #3=6 #3=15 and the line is interpreted, the value of parameter 3 is 15.

*   Comment If it contains more than one comment and is reordered, only the last comment is used. If each group is kept in order or reordered without changing the meaning of the line, then the three groups may be interleaved in any way without changing the meaning of the line.

> **EXAMPLE**  
> **G40** **G01** #3=15 (foo) #4=-7.0 has five items and means exactly the same thing in any of the 120 possible orders, like #4=-7.0 **G01** #3=15 **G40** (foo), for the five items.

The order of execution of items on a line is critical to safe and effective mill operation. If items occur on the same line, they are executed in a particular order. To impose a different order (like to turn coolant off before the spindle is stopped), code the commands on separate blocks.

The order of execution is as follows:

1.  Comment (including message)
2.  Set feed rate mode (**G93**, **G94**, **G95**)
3.  Set feed rate (**F**)
4.  Set spindle speed (**S**)
5.  Special I/O (**M62** to **M68**)

> **NOTE**: This is not supported.

1.  Change tool (**T**)
2.  Spindle on/off (**M03**, **M04**, **M05**)
3.  Save State (**M70**, **M73**, restore state (**M72**), invalidate state (**M71**)
4.  Coolant on/off (**M07**, **M08**, **M09**)
5.  Enable/disable overrides (**M48**, **M49**, **M50**, **M51**, **M52**, **M53**)
6.  Operator defined commands (**M100** to **M199**)
7.  Dwell (**G04**)
8.  Set active plane (**G17**, **G18**, **G19**)
9.  Set length units (**G20**, **G21**)
10.  Cutter radius compensation on/off (**G40**, **G41**, **G42**)
11.  Tool table offset on/off (**G43,** **G49**)
12.  Fixture table select (**G54** through **G58** and **G59** P~)
13.  Set path control mode (**G61**, **G61.1**, **G64**)
14.  Set distance mode (**G90**, **G91**)
15.  Set canned cycle return level mode (**G98**, **G99**)
16.  Home, change coordinate system data (**G10**) or set offsets (**G92**, **G94**)
17.  Perform motion (**G00** to **G03**, **G12**, **G13**, **G80** to **G89** as modified by **G53**)
18.  Stop (**M00**, **M01**, **M02**, **M30**, **M60**)

**MODAL GROUPS**
----------------

G- and M-codes are, generally speaking, modal — they cause the machining system to change from one mode to another. The mode stays active until another command changes it implicitly or explicitly.

> **EXAMPLE** If coolant is turned on (**M07** or **M08**), it stays on until it is explicitly turned off in the program (**M09**).

A few G-codes and M-codes are non-modal. These codes have effect only on the lines on which they occur.

> **EXAMPLE** Dwell (**G04**) is non-modal.

Modal commands are arranged in sets, called modal groups. Only one member of a modal group may be in force at any given time. In general, a modal group contains commands for which it is logically impossible for two members to be in effect at the same time.

> **EXAMPLE** Inch units (**G20**) vs. millimeter units (**G21**).

A machining system may be in many modes at the same time, with one mode from each modal group being in effect.

For all G-code modal groups, when a machining system is ready to accept commands, one member of the modal group must be in effect. There are default settings for these modal groups. When the machining system is turned on or re-initialized, default values are automatically in effect.

Modal groups for G-codes are as follows:

*   Group 1 {**G00**, **G01**, **G02**, **G03**, **G33**, **G38.x**, **G73**, **G76**, **G80**, **G81**, **G82**, **G84**, **G85**, **G86**, **G87**, **G88**, **G89**} motion – This is a group of G-codes for motion called current motion mode — one is always in effect.
*   Group 2 {**G17**, **G18**, **G19**, **G17.1**, **G17.2**, **G17.3**} plane selection
*   Group 3 {**G90**, **G91**} distance mode
*   Group 4 {**G90.1**, **G91.1**} arc IJK distance mode
*   Group 5 {**G93**, **G94**} feed rate mode
*   Group 6 {**G20**, **G21**} units
*   Group 7 {**G40**, **G41**, **G42**, **G41.1**, **G42.1**} cutter radius compensation
*   Group 8 {**G43**, **G43.1**, **G49**} tool length offset
*   Group 10 {**G98**, **G99**} return mode in canned cycles
*   Group 12 {**G54**, **G55**, **G56**, **G57**, **G58**, **G59**, **G59.1**, **G59.2**, **G59.3**} coordinate system selection
*   Group 13 {**G61**, **G61.1**, **G64**} path control mode
*   Group 14 {**G96**, **G97**} spindle speed mode
*   Group 15 {**G07**, **G08**} lathe diameter mode

Modal groups for M-codes are as follows:

*   Group 4 {**M00**, **M01**, **M02**, **M30**, **M60**} stopping
*   Group 7 {**M03**, **M04**, **M05**} spindle turning
*   Group 8 {**M07**, **M08**, **M09**} coolant (special case: **M07** and **M08** may be active at the same time)
*   Group 9 {**M48**, **M49**} enable/disable feed and speed override controls
*   Group 10 {operator defined **M100** to **M199**}

Non-modal G-codes are as follows:

*   Group 0 {**G04**, **G10**, **G28**, **G30**, **G53**, **G92**, **G92.1**, **G92.2**, **G92.3**}