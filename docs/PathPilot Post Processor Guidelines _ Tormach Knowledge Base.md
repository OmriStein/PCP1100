**Title:** PathPilot Post Processor Guidelines | Tormach Knowledge Base

**Source:** [https://knowledgebase.tormach.com/pcnc-1100/pathpilot-post-processor-guidelines](https://knowledgebase.tormach.com/pcnc-1100/pathpilot-post-processor-guidelines)

---

# Page Structure Map
```text
PathPilot Post Processor Guidelines | Tormach Knowledge Base
├── Background
├── Deviations from Fanuc G-code
│   ├── Mill/Router
│   ├── Lathe
│   └── Miscellaneous
└── Sample Programs
```

---

## Background

PathPilot is a dedicated machine controller designed specifically for Tormach machine tools. It shares common code with the open source LinuxCNC project, with Tormach specific additions. If your CAM system already supports a LinuxCNC post, this would be a good starting point for a PathPilot post.

PathPilot control implements 98 percent of the Fanuc standard. The entire list of supported codes is located below.

## Deviations from Fanuc G-code

### Mill/Router

- G07, G09 not supported
- G12, G13 pocketing canned cycles are not supported
- G52 local coordinate system offset is not supported. See G92 below
- PathPilot supports G54 – G59, G59.1, G59.2, and G59.3 as well as G54.1 P1 - P500 (G54.1 P2 = G55) for work offset systems
- G74 tapping cycle for left-hand threads is not supported
- G87, G88 boring cycles are not supported
- The number of tool offsets for mills is 1000
- Tool changes are expressed as either “Txx M06” or “M06 Txx” on one line or by “Txx” and “M06” on separate lines
- It is recommended to set the machine to path blending mode for most situations with G64. “G64” is equivalent to “G64 P0.005” and is recommend to be set on a separate line at the beginning of a program.
	- For roughing toolpaths P can be increased and Q can be specified. There are greatly diminishing returns setting Q larger than 0.002

### Lathe

- Diameter mode only – PathPilot does not allow programming in radius values
- G07, G09 are not supported
- PathPilot uses G33.1 in place of G32 for spindle-synched moves
- G50 max RPM in CSS is not supported. See G96 below for max CSS rpm
- G75 peck groove is not supported. Instead program G73 for chip break
- G70-73 roughing cycles not supported
- The number of tool offsets for lathes is 99
- Tool changes are expressed as “Txx” or “Txxnn”
	- “Txx” of the tool call will both call the tool number and apply the geometry offset
		- “nn” of the tool call will call the wear offset
		- If a turret is installed calling tools 1-8 will automatically command the turret to rotate to pocket 1-8
		- If additional tools are installed in a given pocket, you must first call that pocket (eg, “T07”) and then call the desired tool offset (eg, “T1717”)
		- If a quick change tool post (QCTP) is installed an M0 or other break for the tool change is not needed, PathPilot will automatically pause at the tool call for a manual tool change

### Miscellaneous

- It is highly recommended to include a G30 command before a tool change.
- Cancelling a canned cycle with G80 also cancels the motion mode. This means that you must explicitly call a G00 or G01 after cancelling a canned cycle before using axis values on a line.
- G28/G30 moves cannot be made in G91 – machine must be in G90 before a G28 or G30 is executed
- G41/G42 cutter compensation entry move must be a straight G01 move and must be greater than the tool radius
- Characters such as “$” or “%” at the beginning/end of a program should not be used
- End of block characters, “;”, should not be used

## Sample Programs

Sample mill/router program

Conversational mill example program.nc

Sample lathe program

Conversational lathe example program.nc

Sample plasma program

Plasma example program.nc