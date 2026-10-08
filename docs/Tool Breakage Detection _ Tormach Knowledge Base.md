**Title:** Tool Breakage Detection | Tormach Knowledge Base

**Source:** [https://knowledgebase.tormach.com/pcnc-1100/tool-breakage-detection](https://knowledgebase.tormach.com/pcnc-1100/tool-breakage-detection)

---

# Page Structure Map
```text
Tool Breakage Detection | Tormach Knowledge Base
├── Background
└── Move and Measure Tool Length
```

---

## Background

Utilizing an ETS with the G37 H~ P~ command allows you to check for broken tools mid program with Tormach’s PathPilot!

## Move and Measure Tool Length

To move and measure the tool length, program: G37 H~ P~

- H~ saves the measured tool length to the H tool table entry instead of the current tool number's entry.  
	You could use this to track tool wear between the two tool table entries, for example.  
	**NOTE: The newly measured tool length isn't applied, but it's stored in the tool table entry for tool number H.**
- P~ is positive or negative tolerance. It measures the tool length, but, instead of storing it in the tool table, compares it to the length in the tool table. If the difference exceeds the P tolerance, the G-code program stops.  
	**You could use this to detect broken or improperly inserted tools that are not fully seated in the spindle, for example.**

**NOTE: MX BT30 tool holders are designed to seat in the spindle taper, and should never touch the nose of the spindle.**

G37 with no optional words moves to the G37 ETS position (through G37.1), probes the ETS, stores the new tool length in the tool table entry of the current tool, and applies the tool length offset.

G37 fails if the spindle nose hasn't been referenced to the ETS after a Z-axis reference. This sets a G53 coordinate at the ETS trigger point such that the measured tool length is the distance of the spindle nose to ETS reference. For more information, see the **ETS G37 Spindle Nose Reference** group on the **ETS Setup** tab.

**NOTE: On MX mills, use the tip of the BT30 drive dog, not the spindle nose, to reference.**

So that tool length measurements have consistent results, G37 uses the fine probe feed rate of 2.5 in./min for the final ETS touch. G37 uses the rough probe feed rate for the first ETS touch.