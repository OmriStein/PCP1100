# <a name="chmtopic3"></a>**What's New in Posting/UPG for CAMWorks 2021**
Listed below are the new additions. Click on the links below to view the descriptions of these new additions. 
### ***CAMWorks 2021 BETA***
**New          Support for Probing Cycles in Mill-Turn Posts**

From *CAMWorks 2021* version onwards, the support for Probing Cycles has been extended to Mill-Turn post processors in addition to the existing Mill post processors.

For details of the necessary coding to be added in existing Mill-Turn Post Processors, refer the topic: [Supporting Probing Cycles in Mill-Turn Posts](#chmtopic2). 


# <a name="chmtopic5"></a>**Post Processor Writer's Reference**


This online Help system is a reference guide that provides detailed information on changing the source of a post processor.

Use the Contents, Index and Search tabs on the left to quickly find the information you need.

![image\tabs_help.gif](data:image/gif;base64,R0lGODlhkgAYAIcAAAAAAAAAKAAAKgAoKCgAACkAACoAACkAKCoAKgAATwAAUAAAVQAodwApdwApeAApeQAqfygATykATykAUSoAVSkpUCgodykpdykpeCkpeSkpeikpeyoqf1AAAFEAAFIAAFQAAFEAKFIAKVIpAHkoAHopAHspAH4qAHopKH4qKlEAT1QAVXtSAH5UAABQngBRngBRnwBUqSl6oCh5xSl7ySp+1Hmhd3qjeH6of1So1FCh7VGh7VGj8FKj8VOl9lSo/nnJxXnJ7XrK7nrK73rL8HvM8XvN837S/qFQAKFRAKNRAKNSAKhUAMl5KMp5KNJ+KqLKd6jSf+aLLOuXLuSXPO6fMfm4OPm5OPu+Od2hU/KhT/OiUPSjUP/HPP/IPMnJd8rKd8rKeMvLeMzMedLSf/HJd/LKd/PKd/PKePTLePXMefbNefbNevjPe/zSf5GbnJGntKGzu6m5v6HynqP1obbEzaHyxaHx7aHy7aLz7qT286j8/t3CjdL8qeHGjvHxnvLynvPzn/T0oPb2ovz8qcjRzdDW0Mryxcv0yMnx7cry7crz7srz78v08Mz18c328s3288/49tL8/uDd1OTi2eTi2uXi2+bj3Obj3efk3ejl3ujl3+zp2PHv3/LyxfT0yPX1yfz81OPp6+Pp7OTp7Onm4Orn4Ono4ero4evo4evo4uvq4+vr5ezr5Ozr5ezr5u3q5u3s5e7t5u7t5+/u6O/v6e3x8/Dv6fDu6vDw6vDw6/Hw6vHw6/Dw7PHx7PHx7fPx7vLy7fLy7vPz7vPz7/T07/T08PX18fX08vX18vb08vb28vb28/b29Pf39fj49vj49/r6+Pr6+fr6+vv7+vz8+/z8/P39/Pz8/v7+/f7+/v///wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAAAAP8ALAAAAACSABgAAAj/ADv5mSKloMGDCBMqXMhQIRU+nThJnEixosWLGDNq3MhRo58qV7yIHEmypMmTKFOexFLFT8eXMGPK7JjFSpebOHPq3Mmzp0+fVrLIgUO0qNGjSJMmjVOok1NDQ5VKnTqVqdOInN5g28q1q9evYMOKHYvtDaltaNOqXcu2bVtbdQx1MlTnrNu7ePHClYtVK9m/gAN7faOtsOHDiBMrXpxNlJxOckYtnky5srbGj/uGfQKg8w/BoP++uWatmunTqFOrXq2amjI4neBcI826tm3brmFr/voEgiRshEB8HuuGw2+yxY+TfSOtufPn0KNLlx4NGS7YcKZN3869e/XrTiX6//Wa4gjo5H/Ri37G/lmbDZHay2f/Pv78+/KdAYOFHdr8NgV05gN+BN5XX3776SYeWMZ55YYBACywR3EtdJbDCQD49iAAAhxBoYUY+sYZADWE9UYzzKTIhgaQpOjiiyu2+OKMNCbDiyrYNYNiioOIYAQzbEygB41EEhnjizbiGF5WDCqHTSgnfPZEDA9+VhwZxoVSHjZXGmAlB1hKQsgKE1KwB1hvMLPMmmtk8MiacMbZ5ptx1mnnMbukgl2KcM5p55+A9ulmnHjqueR4XTXIFXpXNtioJBt2JgAOjoKZJYYlmpjMMZyqkcEYGbDQWQ/HqBEgAA84YioAARSxRKqmkv/KKafG3GIKdstsyikoJtAwa6kBtnrMEp0B0IMaFYygAB0fjOqpqMYeU+uth4K15aKVhsmlpZCaie1vj3LFhIRoSmuMMWlgIEYBPKCLASIltMuFA4igQIS7jSghQ7zn9msMMbSUgh2t/X5SAqtEfGIvvv2mK8YBCfMrSAg3sIsvwAJXy5tvwIFwoZRUZnuplRREITKkCByhpXlfvfEvMcSggUEYGDAS88w13xzGqawOEYgHMMAsNMzCzLIJducOLfQWDuxcbABDoHFq0zXLbDPMVt/MSNFHa8xbsVZCqGGlfYAgYXAceki22XuMmGnLxQwj9xkXgHHBIsPQbTfeekv/kIfccxfQAN6Ayx2MLJpgV0zchcsdiApQ+A14ICEIkXfdd9NN+OV833144l6HJrrobwwTzOlmWACGBYoEk/ohJOwQjBMMwC67GRHYEXsSM5zuezC+xJIJdoaf7sQLp2tRe+yuRzCHCngEo/zqinjCPCAh2MC666wHP3zoo4cP2BvC/GJ+GRZ8YUEiv6CfSBkEADDA+n90wCoQJLjwS/0zmO9/L67ABHaEUT7/IaEzCbjD/uwXgCD8ognFYoD62Fe/zujAfe1bHwAFCD7xedBEwPOFCEdIwhKa8IQl1EUrLoGd06HwhTCEoQpZ2MEP2pArb/CFLnbIwx768IdA/GEthVZhCeyIMIhITGISh1jEGt7Qhm/IhRSnSMUqWvGKV6QFKiiBHV1g8YtgDKMWuejEJ3rwDaxghStewcY2uvGNcIxjG1lxikpMAjuvSOMa5cjHPuYxjYCs4x3LaMbwveGQiEykIhfJyEY68pGQjGQkC0nJSlrSjIi6pCY3yUk0dfKToNxkQAAAOw==)
## **Context Sensitive Help**
When you are working with a source file in the editor, you can highlight a command or variable, then click the right mouse button and select Help on the shortcut menu. The Online Help will open and display the applicable topic.


## **Printing Topics**
To print a topic, either right click on the topic and select Print Topic on the shortcut menu or click File on the topic menu bar, then select Print Topic.
# <a name="chmtopic71"></a>**What's New in Posting/UPG for CAMWorks 2020**
Listed below are the new additions. Click on the links below to view the descriptions of these new additions. 
### ***CAMWorks 2020 SP3***
**New          System Constant**

`      `[CAM_REV2020_SP3](#chmbookmark1)



**Additions to System Command '[**TRANSFORM**](#chmtopic7)'**

- [New Parameters from Kinematics File](#chmbookmark2)
- [New Parameters supported by TRANSFORM](#chmbookmark3)
- [New KIN File Parameters](#chmbookmark4)  


### ***CAMWorks 2020 SP2***
**New   Post Variables**

[WRAPPED_AXIS](#chmtopic8)

**New**   

[Configuring UPG Batch Compiler](#chmtopic9)

**New**   

[Adding Wrapped Cylindrical to Mill Posts](#chmtopic10)

-----
### ***CAMWorks 2020 SP1***
**New  Variables**

[MACH_IS_4TH_AXIS_REV_DIR](#chmtopic11)

[MACH_IS_5TH_AXIS_REV_DIR](#chmtopic12)

-----
### ***CAMWorks 2020 SP0***
**New  System Commands**

[GET_SW_CUSTOM_PROP_BY_NAME](#chmtopic13)

[GET_SW_SUMMARY_INFO_BY_ID](#chmtopic14)



**New  System Header Commands**

[:ALLOW_PROBING](#chmtopic15)



**New  System Variables for Probing**

[PROBE_A_1ST_ANGLE](#chmtopic16)

[PROBE_B_2ND_ANGLE_OR_TOL](#chmtopic17)

[PROBE_C_3RD_ANGLE](#chmtopic18)

[PROBE_D_NOMINAL_SIZE](#chmtopic19)

[PROBE_E_EXPERIENCE_VALUE](#chmtopic20)

[PROBE_F_PERCENT_FEEDBACK](#chmtopic21)

[PROBE_H_TOL_VALUE](#chmtopic22)

[PROBE_I_CYCLE_SPEC_DIST_X](#chmtopic23)

[PROBE_J_CYCLE_SPEC_DIST_Y](#chmtopic24)

[PROBE_K_CYCLE_SPEC_DIST_Z](#chmtopic25)

[PROBE_M_POS_TOL](#chmtopic26)

[PROBE_Q_OVERTRAVEL_DIST](#chmtopic27)

[PROBE_R_CLERANCE](#chmtopic28)

[PROBE_T_TOOL_OFFSET_NUMBER](#chmtopic29)

[PROBE_U_UPPER_TOL_LIMIT](#chmtopic30)

[PROBE_V_NULL_BAND](#chmtopic31)

[PROBE_W_PRINT_DATA](#chmtopic32)

[PROBE_X_POS_OR_SIZE_X](#chmtopic33)

[PROBE_Y_POS_OR_SIZE_Y](#chmtopic34)

[PROBE_Z_POS_OR_SIZE_Z](#chmtopic35)

[PROBE_CYCLE_FEEDRATE](#chmtopic36)

[PROBE_WORK_SUB_OFFSET_NUM](#chmtopic37)

[PROBE_WORK_OFFSET_NUM](#chmtopic38)

[PROBE_UPDATE_WCS_OFFSET](#chmtopic39)

[PROBE_FIXTURE_OFFSET_NUM](#chmtopic40)

[PROBE_CYCLE_TYPE](#chmtopic41)

[PROBE_UPDATE_OFFSET_TYPE](#chmtopic42)

[HAVE_PROBE_CYCLE](#chmtopic43)



**New  Calc Sections** 

[CALC_LINE_MOVE_PROBE_MILL](#chmbookmark5)

[CALC_RAPID_MOVE_PROBE_MILL](#chmbookmark5)

[CALC_RAPID_Z_UP_PROBE_MILL](#chmbookmark5)

[CALC_RAPID_Z_DOWN_PROBE_MILL](#chmbookmark5)

[CALC_FEED_Z_PROBE_MILL](#chmbookmark5)

[CALC_OUTPUT_PROBE_CYCLE_MILL](#chmbookmark5)

[CALC_OUTPUT_CL_COMMENT](#chmbookmark6)

[CALC_OUTPUT_CL_COMMAND](#chmbookmark6)

[CALC_GET_SW_CUSTOM_FIELDS](#chmtopic44)

[CALC_GET_SW_PROPERTIES](#chmtopic45)

[CALC_GET_SW_SUMMARY_FIELDS](#chmtopic46)

[CALC_OUTPUT_SW_PROPERTY](#chmtopic47)



**New  Variables**

[CL_COMMENT](#chmtopic48)

[CL_COMMAND](#chmtopic49)

[OPR_IS_PRIMARY](#chmtopic50)

[IS_SUB_SPINDLE_REVERSE_Z](#chmtopic51)

[MACH_NUMBER_AXIS](#chmtopic52)

[MACH_ROTARY_4AXIS_TYPE](#chmtopic53)

[MACH_ROTARY_VEC_4X](#chmtopic54)

[MACH_ROTARY_VEC_4Y](#chmtopic55)

[MACH_ROTARY_VEC_4Z](#chmtopic56)

[MACH_ROTARY_VEC_5X](#chmtopic57)

[MACH_ROTARY_VEC_5Y](#chmtopic58)

[MACH_ROTARY_VEC_5Z](#chmtopic59)



**New  Query Commands**

[QUERY_TOOL_ID_COMMENT](#chmtopic60)

[QUERY_TOOL_VENDOR_COMMENT](#chmtopic61)

[QUERY_TOOL_DESCRIPTION_COMMENT](#chmtopic62)

[QUERY_HOLDER_NUM_COMMENT](#chmtopic63)

[QUERY_HOLDER_VENDOR_COMMENT](#chmtopic64)

[QUERY_HOLDER_DESCRIPTION_COMMENT](#chmtopic65)

[QUERY_STATION_DESCRIPTION_COMMENT](#chmtopic66)



**New   System Constants for SOLIDWORKS**

Refer: [System Constants for SOLIDWORKS](#chmtopic67).



**New   System Constants**

[SURFACE_X_TOOLPATH](#chmbookmark7)

[SURFACE_Y_TOOLPATH](#chmbookmark8)

[SURFACE_Z_TOOLPATH](#chmbookmark9)

[WEB_X_TOOLPATH](#chmbookmark10)

[WEB_Y_TOOLPATH](#chmbookmark11)

[POCKET_X_TOOLPATH](#chmbookmark12)

[POCKET_Y_TOOLPATH](#chmbookmark13)

[POCKET_WITH_ISLAND_X_TOOLPATH](#chmbookmark14)

[POCKET_WITH_ISLAND_Y_TOOLPATH](#chmbookmark15)

[BOSS_TOOLPATH](#chmbookmark16)

[BORE_TOOLPATH](#chmbookmark17)

[BORE_WITH_ISLAND_TOOLPATH](#chmbookmark18)

[THREE_POINT_BOSS_TOOLPATH](#chmbookmark19)

[THREE_POINT_BORE_TOOLPATH](#chmbookmark20)

[THREE_POINT_BORE_WITH_ISLAND_TOOLPATH](#chmbookmark21)

[FIXTURE](#chmbookmark22)

[UPDATE_WORK_OFFSET_CYCLE](#chmbookmark23)

[WORK_COORDINATE](#chmbookmark24)

[WORK_AND_SUB_COORDINATE](#chmbookmark25)

[MILL_PROBING](#chmbookmark26)

[ROTATE_ABOUT_X](#chmbookmark27)

[ROTATE_ABOUT_Y](#chmbookmark28)

[ROTATE_ABOUT_Z](#chmbookmark29)

[ROTATE_ABOUT_MULTIPLE](#chmbookmark30)



**New   Additional System Constants**

[CAM_REV2020](#chmbookmark31)



**New   Attribute Commands**

[QUERY_SW_FIELD_NAME](#chmtopic68)

[QUERY_SW_FIELD_TYPE](#chmtopic69)

[QUERY_SW_FIELD_VAL](#chmtopic70)
# <a name="chmtopic127"></a>**What's New in Posting / Universal Post Generator (UPG) for CAMWorks 2019**
### ***CAMWorks 2019 SP2***
***New*  System Header Commands**

[:FORCE_UPPERCASE_OUTPUT](#chmtopic73)



***New*  Attribute Commands**

[:MUST_BE_LOWERCASE ](#chmtopic74)

[:MUST_BE_UPPERCASE ](#chmtopic75)

-----
### ***CAMWorks 2019 SP1***
[Posting Feature Notes for Simultaneous B Axis Output for Turning](#chmtopic76)



***New*  System Header Commands**

[:ALLOW_B_AXIS_SIMULTANEOUS_CUTTING](#chmtopic77)



***New*  Variables**

[OPR_START_APPROACH_TYPE](#chmtopic78)

[OPR_X_APPROACH_POS](#chmtopic79)

[OPR_Z_APPROACH_POS](#chmtopic80)

[MAX_B_AXIS_INCREMENT](#chmtopic81)

[NEXT_OPR_BAXIS_TURNING](#chmtopic82)

[NUM_OPERATIONS_FRONT1](#chmtopic83)

[NUM_OPERATIONS_FRONT2](#chmtopic84)

[NUM_OPERATIONS_REAR1](#chmtopic85)

[NUM_OPERATIONS_REAR2](#chmtopic86)

[NUM_SYNC_CODES_REAR1](#chmtopic87)

[NUM_SYNC_CODES_REAR2](#chmtopic88)

[NUM_SYNC_CODES_FRONT1](#chmtopic89)

[NUM_SYNC_CODES_FRONT2](#chmtopic90)

[OPR_BAXIS_TURNING](#chmtopic91)

[OPR_TOOL_TIP_CENTER](#chmtopic92)

[P_TLP_B_AXIS_OFFSET](#chmtopic93)

[TLP_B_AXIS_OFFSET](#chmtopic93)



***New*  Query Commands**

[QUERY_INT_CENTER_TOUCHOFF_REG](#chmtopic94)



***New* System Constants** 

[FROM_PREVIOUS_POS](#chmbookmark32)

[FROM_APPROACH_POS](#chmbookmark33)

[CAM_REV2019_SP2](#chmbookmark34)

-----
** 
### ***CAMWorks 2019 SP0***
[Posting Feature Notes for Pinch Turning](#chmbookmark35)

[List of changes to be made to support Pinch Turning Functionality](#chmtopic95)

[Posting Feature Notes for Multi Turret Support](#chmtopic96)

[List of changes to be made to support Multi Turret (2-4 turrets) Functionality](#chmtopic97)



***New*  System Header Commands**

[:ALLOW_MIN_PECK_ON_VARIABLE_CANNED_CYCLE](#chmtopic98)

[:ALLOW_FIRST_FEED_SYNC_ON_CANNED_CYCLE](#chmtopic99)
**\


***New*  Variables**

[HAVE_FIRST_FEED_SYNC_CODES](#chmtopic100)

[MACHINE_MAX_FEEDRATE](#chmtopic101)

[NEXT_USER_TURRET_NUM](#chmtopic102)

[OPR_IS_ARC_FEEDRATE_OVERRIDE_ENABLED](#chmtopic103)

[OPR_IS_CORNER_SLOWDOWN_ENABLED](#chmtopic104)

[OPR_IS_SYS_CALCULATED_FEEDRATES_ENABLED](#chmtopic105)

[OPR_MACH_DEVIATION](#chmtopic106)

[OPR_STEPOVER](#chmtopic107)

[SYNCED_WITH_FRONT1](#chmtopic108)

[SYNCED_WITH_FRONT2](#chmtopic109)

[SYNCED_WITH_REAR1](#chmtopic110)

[SYNCED_WITH_REAR2](#chmtopic111)

[TOOL SHANK DIAMETER](#chmtopic112)

[TURN PART LENGTH](#chmtopic113)

[TURN PART DIAMETER](#chmtopic114)

[TURRET_NUM](#chmtopic115)

[N_TURRET_NUM](#chmtopic115)

[P_TURRET_NUM](#chmtopic115)

[OPR_FACET_DEVIATION](#chmtopic116)

[OPR_SPLINE_DEVIATION](#chmtopic117)

[OPR_PINCH_TURNING](#chmtopic118)



***New*  Miscellaneous Commands**

[FLUSH_ALL_SYNC_CODES()](#chmtopic119)



***New*  System Commands**

[OUTPUT_FIRST_FEED_SYNC_CODES](#chmtopic120)



***New*  Query Commands**

[QUERY_MACHINE_NAME](#chmtopic121)

[QUERY_NC_FILE_EXTENSION](#chmtopic122)

[QUERY_INT_MILL_FEATURE_SUB_TYPE](#chmtopic123)

[QUERY_INT_MILL_PROCESS_TOOLPATH_BY](#chmtopic124)
**\


***New*  Post System Section Command**

[CALC_SET_TURRET_CHANNEL](#chmtopic125)



***New*  Constants**

[FRONT1](#chmbookmark36)

[FRONT2](#chmbookmark37)

[REAR1](#chmbookmark38)

[REAR2](#chmbookmark39)

[MILL_FEATURE_SUB_TYPE_BLIND](#chmtopic126)

[MILL_FEATURE_SUB_TYPE_THROUGH](#chmtopic126)

[MILL_FEATURE_SUB_TYPE_DOUBLE_BLIND](#chmtopic126)

[MILL_FEATURE_SUB_TYPE_UNKNOWN](#chmtopic126)

[MILL_FEATURE_SUB_TYPE_DRILLED](#chmtopic126)

[MILL_PROCESS_TOOLPATH_BY_NONE](#chmtopic126)

[MILL_PROCESS_TOOLPATH_BY_TOOL](#chmtopic126)

[MILL_PROCESS_TOOLPATH_BY_FEATURE](#chmtopic126)

[MILL_PROCESS_TOOLPATH_BY_PART](#chmtopic126)
# <a name="chmtopic138"></a>**What's New in Posting/Universal Post Generator (UPG) for CAMWorks 2018**
### **CAMWorks 2018 SP4**
**New Variables**

[BAR_STOCK_BACK_FACE_OFFSET](#chmtopic129)

-----
** 
### **CAMWorks 2018 SP2**
**New Compiler Command**

[:".\" or "..\"](#chmtopic130)

-----

### **CAMWorks 2018 SP0**
**New  Query Commands**

[QUERY_FEATURE_ENTRY_TYPE](#chmtopic131)

[QUERY_TOOL_COOLANT_TYPE](#chmtopic132)

[QUERY_TOOL_DIAMETER_REG](#chmtopic133)

[QUERY_TOOL_LENGTH_REG](#chmtopic134)
**\


**New  Variables**

[TOOL_INEFFECTIVE_LENGTH](#chmtopic135)

[N_TOOL_INEFFECTIVE_LENGTH](#chmtopic135)  

[NC_TOOL_INEFFECTIVE_LENGTH](#chmtopic135)

[TOOL_TIP_OFFSET](#chmtopic136)

[N_TOOL_TIP_OFFSET](#chmtopic136)

[NC_TOOL_TIP_OFFSET](#chmtopic136)

[OPR_SUPPORTS_TOOL_TIP_OFFSET](#chmtopic137)

-----

# <a name="chmtopic179"></a>**What's New in Posting/Universal Post Generator for CAMWorks 2017**
### **CAMWorks 2017 SP3**
**New  Variables**

[USE MULTIAXIS_MAX_MOVE_DISTANCE](#chmtopic140)

-----

### **CAMWorks 2017 SP2**
**New  Variables**

[MULTIAXIS_MAX_MOVE_DISTANCE](#chmtopic141)

[FACET_DEVIATION](#chmtopic142)

[SPLINE_DEVIATION](#chmtopic143)

-----

### **CAMWorks 2017 SP1**
**New  System Header Commands**

[MILL_3AXIS_ONLY](#chmtopic144)

[USE_STATION_ID_AS_NAME](#chmtopic145)



**New  Variables**

[CAP_PART_MAX_RPM_MAIN](#chmtopic146)

[CAP_PART_MAX_RPM_SUB](#chmtopic147)

[NUM_OPS_BET_SYNCS_OTHER_TURRET](#chmtopic148)

[NUM_OPS_BET_SYNCS_THIS_TURRET](#chmtopic149)

[OPR_SUB_TYPE](#chmtopic150)

[OPR_THREAD_LAST_CUT](#chmtopic151)

[TOOL_CORNER_RADIUS_BOT](#chmtopic152)

[TOOL_CORNER_RADIUS_TOP](#chmtopic153)

-----

### **CAMWorks 2017 SP0**
**New  System Header Commands**

[ALLOW_PART_MAX_RPM](#chmtopic154)

[ALLOW_PART_MAX_RPM_BY_OPER](#chmtopic155)

[FACE_MILL=FIXED_OR_X+_ONLY](#chmtopic156)

[FACE_MILL=CONVERT_X+_ONLY_TO_FIXED_OR_X+_ONLY](#chmtopic157)



**New  System Commands**

[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)



**New  Variables**

[BAR_STOCK_ID_DIAM](#chmtopic160)

[BAR_STOCK_FACE_OFFSET](#chmtopic161)

[CAP_OPR_MAX_RPM](#chmtopic162)

[OPR_FSPAGE_X_FEED](#chmtopic163)

[OPR_FSPAGE_Z_FEED](#chmtopic164)

[OPR_MAX_RPM](#chmtopic165)

[OPR_XPLUS_ONLY](#chmtopic166)

[PART_MAX_RPM_MAIN](#chmtopic167)

[PART_MAX_RPM_SUB](#chmtopic168)

PART\_STOCK\_ID\_DIAM

PART\_STOCK\_FACE\_OFFSET

[PLANE_4AX_ANGLE](#chmtopic169)

[PLANE_5AX_ANGLE](#chmtopic170)

[QUERY_STATS_X_MAX](#chmtopic171)

[QUERY_STATS_X_MIN](#chmtopic172)

[QUERY_STATS_Y_MAX](#chmtopic173)

[QUERY_STATS_Y_MIN](#chmtopic174)

[QUERY_STATS_Z_MAX](#chmtopic175)

[QUERY_STATS_Z_MIN](#chmtopic176)

[MULTI_AXIS_MOVE_TYPE](#chmtopic177)

[VOLUMILL_HIGH_FEEDRATE](#chmtopic178)
### ** 
**New**  **System Constants**

[Additional System Constants](#chmbookmark40)
# <a name="chmtopic213"></a>**What's New in Posting/Universal Post Generator (UPG) for CAMWorks 2016**
### **CAMWorks 2016 SP2**
**New  Variables**

[TOOL_SPINDLE_USAGE](#chmtopic181)

[HAVE_COORDINATE_SYS](#chmtopic182)

[USE_NON_ROTATED_WCS_FOR_VM](#chmtopic183)
### ** 
**New**  **System Constants**

[Additional System Constants](#chmtopic184)

-----

### **CAMWorks 2016 SP1**
**New  Variables**

[OPR_APPROACH_AUTO_CORRECT](#chmtopic185)

[OPR_RETRACT_AUTO_CORRECT](#chmtopic186)

-----
### ** 
### **CAMWorks 2016 SP0**
**New  System command**

[QUERY NUM THREAD PASSES](#chmtopic187)



**New  Variables**

[POST_RESETS_CAXIS_ON_TOOL_CHANGE](#chmtopic188)

[NEXT_USER_TURRET](#chmtopic189)

[IS_CANNED_DRILL_CYCLE](#chmtopic190)

[GUN_DRILL_PILOT_FEEDIN_DIST](#chmtopic191)

[GUN_DRILL_PILOT_FEEDRATE](#chmtopic192)

[GUN_DRILL_ENTRY_RETRACT_SPEED](#chmtopic193)

[GUN_DRILL_DWELL_BEFORE_DRILL](#chmtopic194)

[GUN_DRILL_FEEDBACK_AMOUNT](#chmtopic195)

[GUN_DRILL_RETRACT_FEEDRATE](#chmtopic196)

[GUN_DRILL_IS_RAPID_RETRACT](#chmtopic197)

[GUN_DRILL_CHANGE_RPM_AT](#chmtopic198)

[OPR_B_AXIS_OFFSET](#chmtopic199)

[CL_COOLANT_TYPE](#chmtopic200)

[OPR_APPROACH_STRATEGY](#chmtopic201)

[OPR_RETRACT_STRATEGY](#chmtopic202)

[POST_ADV_ENTRY_RETRACT](#chmtopic203)

[OPR_END_RETRACT_TYPE](#chmtopic204)

[QUERY_CHAR_VAL](#chmtopic205)

[TOOL_FLUTE_LENGTH](#chmtopic206)

[OPR_FIRST_MOVE_COMP_DIR](#chmtopic207)



**New  System Header Commands**

[MILL_ADVANCED_ENTRY_RETRACT](#chmtopic208)

[ALLOW_GUN_DRILLING](#chmtopic209)

[ALLOW_LONG_CODE_DRILLING_CYCLES](#chmtopic210)

[ALLOW_GUN_DRILLING_CANNED_CYCLE](#chmtopic211)

[ALLOW_B_AXIS_OFFSET_REAR](#chmtopic212)



**New**  **System Constants**

[Additional System Constants](#chmtopic184)


# <a name="chmtopic252"></a>**What's New in Posting/UPG for CAMWorks 2015**
### **CAMWorks 2015 SP2**
**New  Variables**

[3AXIS_RAPID_PLANE_TYPE](#chmtopic215)

[WORK_PLANE_X_VEC_X](#chmtopic216)

[WORK_PLANE_X_VEC_Y](#chmtopic217)

[WORK_PLANE_X_VEC_Z](#chmtopic218)

[WORK_PLANE_Y_VEC_X](#chmtopic219)

[WORK_PLANE_Y_VEC_Y](#chmtopic220)

[WORK_PLANE_Y_VEC_Z](#chmtopic221)

[WORK_PLANE_Z_VEC_X](#chmtopic222)

[WORK_PLANE_Z_VEC_Y](#chmtopic223)

[WORK_PLANE_Z_VEC_Z](#chmtopic224)

[DRILL_DWELL](#chmtopic225)

[DRILL_SHIFT](#chmtopic226)

[NEXT_USER_TOOL](#chmtopic227)

[PART_PULL_DISTANCE](#chmtopic228)

[TOOL_INCLUDED_ANGLE](#chmtopic229)

[ABS_ARC_MID_X](#chmtopic230)

[ABS_ARC_MID_Y](#chmtopic231)

[ABS_ARC_MID_Z](#chmtopic232)

-----

### **CAMWorks 2015 SP1**
**New  Post Queries**

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)



**New  Variables**

[IS_PATTERN_FEATURE](#chmtopic235)

[IS_TLP_COMPENSATED](#chmtopic236)

[OPR_THREAD_NUM_STARTS](#chmtopic237)



**New  System Commands**

[GETMCS (1, calc_section)](#chmtopic238)

[GETMCS (3, calc_section)](#chmtopic238)

-----

### **CAMWorks 2015 SP0**
**New  Variables**

[STOCK_MAX_X](#chmtopic239)

[STOCK_MAX_Y](#chmtopic240)

[STOCK_MAX_Z](#chmtopic241)

[STOCK_MIN_X](#chmtopic242)

[STOCK_MIN_Y](#chmtopic243)

[STOCK_MIN_Z](#chmtopic244)

[USE_FEATURE_OD_ID](#chmtopic245)
**\


**New  Miscellaneous Commands**

[MILL_OPER_SETUP](#chmtopic246)

[LATHE_OPER_SETUP](#chmtopic247)



**New**  **System Variables**

[OPR_REVERSE_ARC_DIR](#chmtopic248)

[OPR_Z_DEPTH](#chmtopic249)

[O_CYCLE_START_X](#chmtopic250)

[O_CYCLE_START_Z](#chmtopic251)
# <a name="chmtopic311"></a>**What's New in Posting/Universal Post Generator (UPG) for CAMWorks 2014**
### **CAMWorks 2014 SP2**
**New  Post Queries**

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_MILL_TLP_Z_EXTENTS](#chmtopic255)
**\


**New  System Variables**

[DIST_BETWEEN_CHUCKS](#chmtopic256)

[OPR_REVERSE_ARC_DIR=TRUE or FALSE](#chmtopic257)



**New  Variables**

[TLP_2AX_FEAT_DEPTH](#chmtopic258)

[QUERY_TLP_Z_MIN](#chmtopic259)

[QUERY_TLP_Z_MAX](#chmtopic260)

[SETUP_MACH_X](#chmtopic261)

[SETUP_MACH_Y](#chmtopic262)

[SETUP_MACH_Z](#chmtopic263)

[SETUP_MACH_I](#chmtopic264)

[SETUP_MACH_J](#chmtopic265)

[SETUP_MACH_K](#chmtopic266)

[SOLIDWORKS_FILENAME](#chmtopic267)

-----

### **CAMWorks 2014 SP1**
### **New  Miscellaneous Commands**
[CALC_OUTPUT_FEED_SPINDLE_TO_HOME](#chmtopic268)

[CALC_OUTPUT_RAPID_SPINDLE_TO_HOME](#chmtopic269)

-----

### **CAMWorks 2014 SP0.1**

### **New System Header Commands**
[USE_TOOL_COMMENT_AS_NAME](#chmtopic270)


### **New Variables**
[MCS_U_NAME](#chmtopic271)

[MCS_V_NAME](#chmtopic272)

[MCS_W_NAME](#chmtopic273)

[MCS_U_OFFSET](#chmtopic274)

[MCS_V_OFFSET](#chmtopic275)

[MCS_W_OFFSET](#chmtopic276)

-----

### **CAMWorks 2014 SP0.0**

### **New System Header Commands**
[GENERIC_POST](#chmtopic277)


### **New  Post System Calc Sections**
[CALC_PRE_POST_INITIALIZE](#chmtopic278)


### **New  Miscellaneous Commands**
[FLUSH_SYNC_CODES](#chmtopic279)


### **New Variables**
[CONVENTIONAL_AXIS_LABELS](#chmtopic280)  

[NUM_TURRETS_FRONT](#chmtopic281)

[NUM_TURRETS_REAR](#chmtopic282)

[REAR_TURRET_1_TYPE](#chmtopic283)

[FRONT_TURRET_1_TYPE](#chmtopic284)

[REAR_TURRET_TYPE](#chmtopic285)

[REAR_TURRET_2_TYPE](#chmtopic286)

[REAR_TURRET_3_TYPE](#chmtopic287)

[REAR_TURRET_4_TYPE](#chmtopic288)

[FRONT_TURRET_TYPE](#chmtopic289)

[FRONT_TURRET_2_TYPE](#chmtopic290)

[FRONT_TURRET_3_TYPE](#chmtopic291)

[FRONT_TURRET_4_TYPE](#chmtopic292)

[CHUCK_WIDTH](#chmtopic293)

[SUB_CHUCK_WIDTH](#chmtopic294)

[MACH_SIM_CHANGER](#chmtopic295)

[MACH_SIM_CHANGER_1A](#chmtopic296)

[MACH_SIM_CHANGER_2A](#chmtopic297)

[MACH_SIM_CHANGER_1B](#chmtopic298)

[MACH_SIM_CHANGER_2B](#chmtopic299)

[MACH_SIM_CRIB_OFF](#chmtopic300)

[MACH_SIM_CRIB_OFF_1A](#chmtopic296)

[MACH_SIM_CRIB_OFF_2A](#chmtopic301)

[MACH_SIM_CRIB_OFF_1B](#chmtopic302)

[MACH_SIM_CRIB_OFF_2B](#chmtopic303)

[MACH_SIM_TOOL_SPINDLE](#chmtopic304)

[MACH_SIM_TOOL_SPINDLE_1A](#chmtopic305)

[MACH_SIM_TOOL_SPINDLE_2A](#chmtopic306)

[MACH_SIM_TOOL_SPINDLE_1B](#chmtopic307)

[MACH_SIM_TOOL_SPINDLE_2B](#chmtopic308)

[MACH_SIM_MAIN_SPINDLE](#chmtopic309)

[MACH_SIM_SUB_SPINDLE](#chmtopic310)
# <a name="chmtopic368"></a>**What's New in Posting/Universal Post Generator (UPG) for CAMWorks 2013**
### **CAMWorks 2013 SP0.0**
### **New Additional Variables**
[SETUP_REVERSE_Z_DIR](#chmtopic313)

[IS_COMMENT](#chmtopic314)

[SPINDLE_STATE](#chmtopic315)

[SPINDLE_SYNC_TYPE](#chmtopic316)

[SPINDLE_ORIENTATION](#chmtopic317)

[ABS_SPINDLE_Z_END](#chmtopic318)

[TLP_FEATURE_ID](#chmtopic319)

[OPR_MOVE_ID](#chmtopic320)

[OPR_RPM](#chmtopic321)

[NEXT_OPR_SUB_STATION](#chmtopic322)

[SUB_STATION](#chmtopic323)

[NC_SUB_STATION](#chmtopic324)

[N_SUB_STATION](#chmtopic325)

[HAVE_SUB_STATIONS](#chmtopic326)

[HAVE_START_OPER_SYNC_CODES](#chmtopic327)

[HAVE_FIRST_MOVE_SYNC_CODES](#chmtopic328)

[HAVE_END_OPER_SYNC_CODES](#chmtopic329)

[POST_LIBRARY_VERSION](#chmtopic330)

[POST_LIBRARY_SUBVERSION](#chmtopic331)

[MCS_TYPE](#chmtopic332)

[SETUP_WORLD_X_OFFSET](#chmtopic333)

[SETUP_WORLD_Y_OFFSET](#chmtopic334)

[SETUP_WORLD_Z_OFFSET](#chmtopic335)  

[SUB_STATION_ID](#chmtopic336)

[NC_SUB_STATION_ID](#chmtopic337)

[TOOL_X_GAGE_OFFSET](#chmtopic338)

[NC_TOOL_X_GAGE_OFFSET](#chmtopic339)

[SPINDLE_I](#chmtopic340)

[SPINDLE_J](#chmtopic341)

[SPINDLE K](#chmtopic342)


### **New System Commands**
[OUTPUT_START_SYNC_CODES()](#chmtopic343)

[OUTPUT_FIRST_MOVE_SYNC_CODES()](#chmtopic344)

[OUTPUT_END_SYNC_CODES()](#chmtopic345)


### **New System Header Commands**
[SORT_BY_TURRET](#chmtopic346)

[SINGLE_Y_AXIS_DIRECTION](#chmtopic347)


### **New  Post System Calc Sections**
New sections have been introduced for Sync Manager and Sub spindle operations. Following are list of Calc Sections introduced in CAMWorks 2013.

[CALC_CHANGE_MILL_SPEED](#chmtopic348)

[CALC_OUTPUT_ARBOR_OPEN](#chmtopic349)

[CALC_OUTPUT_ARBOR_CLOSE](#chmtopic350)

[CALC_OUTPUT_CANCEL_POLAR_SPINDLE_ORIENTATION](#chmtopic351)

[CALC_OUTPUT_CHUCK_OPEN](#chmtopic352)

[CALC_OUTPUT_CHUCK_CLOSE](#chmtopic353)

[CALC_OUTPUT_COLLET_OPEN](#chmtopic354)

[CALC_OUTPUT_COLLET_CLOSE](#chmtopic355)

[CALC_OUTPUT_FEEDRATE](#chmtopic356)

[CALC_OUTPUT_POLAR_SPINDLE_ORIENTATION](#chmtopic357)

[CALC_OUTPUT_REFERENCE_POINT](#chmtopic358)

[CALC_OUTPUT_SPEED](#chmtopic359)

[CALC_OUTPUT_SPINDLE_COMMAND](#chmtopic360)

[CALC_OUTPUT_SPINDLE_COMMENT](#chmtopic361)

[CALC_OUTPUT_SPINDLE_ORIENTATION](#chmtopic362)

[CALC_OUTPUT_SPINDLE_STATE](#chmtopic363)

[CALC_OUTPUT_SPINDLE_SYNC](#chmtopic364)

[CALC_OUTPUT_RAPID_SPINDLE_TO_POSITION](#chmtopic365)

[CALC_OUTPUT_FEED_SPINDLE_TO_POSITION](#chmtopic366)

[CALC_QUERY_POST](#chmtopic367)


# <a name="chmtopic381"></a>**What's New in Posting/Universal Post Generator (UPG) for CAMWorks 2011**
### **CAMWorks 2011 SP1.0**
### **New Additional Variables**
[WORLD_FCS_TO_SETUP_X](#chmtopic370)

[WORLD_FCS_TO_SETUP_Y](#chmtopic371)

[WORLD_FCS_TO_SETUP_Z](#chmtopic372)

[WORLD_VECTOR_X](#chmtopic373)

[WORLD_VECTOR_Y](#chmtopic374)

[WORLD_VECTOR_Z](#chmtopic375)

[SETUP_MCS_X_OFFSET](#chmtopic376)

[SETUP_MCS_Y_OFFSET](#chmtopic377)

[SETUP_MCS_Z_OFFSET](#chmtopic378)

[OPR_LEADIN_FEEDRATE](#chmtopic379)

[OPR_THREAD_DEPTH](#chmtopic380)


### **New System Constants**
CAM\_REV2011\_SP1 = 111


# <a name="chmtopic402"></a>**What's New in Posting/Universal Post Generator (UPG) for CAMWorks 2010**
### **CAMWorks 2010 SP2.0**
### **New Variables**
[**OPR_XY_ALLOWANCE**](#chmtopic383)

-----
### ** 
### **CAMWorks 2010 SP1.0**
### **New Variables**
[**TOOL_ANGLE**](#chmtopic384)

[**TOOL_PROTRUSION**](#chmtopic385)

[**STOCK_LENGTH**](#chmtopic386)

[**STOCK_WIDTH**](#chmtopic387)

[**STOCK_HEIGHT**](#chmtopic388)

-----

### **CAMWorks 2010 SP0.0**
Post customization is required in order to use new commands and variables. These commands and variables are not supported in previous versions of CAMWorks or in any ProCAM product.
### **New Variables**
[PRE_POSITION_ROTARY_TYPE](#chmtopic389)

[TLP_FEAT_SETUP_DESC](#chmtopic390)

[TLP_FEAT_SETUP_NAME](#chmtopic391)

[SYNC_CODE_COMMENT](#chmtopic392)

[REAR_SYNC_CODE](#chmtopic393)

[REAR_SYNC_CODE_TYPE](#chmtopic394)

[FRONT_SYNC_CODE](#chmtopic395)

[FRONT_SYNC_CODE_TYPE](#chmtopic396)

[ARC_NORM_X](#chmtopic397)

[ARC_NORM_Y](#chmtopic398)

[ARC_NORM_Z](#chmtopic399)

[CTL_PATH](#chmtopic400)


### **New  Post System Calc Sections**
CALC\_ADD\_ REAR\_SYNC\_CODE

The section called CALC\_ADD\_REAR\_SYNC\_CODE gets called when a command to output rear sync code is encountered and the post variables SYNC\_CODE\_COMMENT, REAR\_SYNC\_CODE and REAR\_SYNC\_CODE\_TYPE are set.



CALC\_ADD\_ FRONT\_SYNC\_CODE

The section called CALC\_ADD\_FRONT\_SYNC\_CODE gets called when a command to output front sync code is encountered and the post variables SYNC\_CODE\_COMMENT, FRONT\_SYNC\_CODE and FRONT\_SYNC\_CODE\_TYPE are set.


### **New System Command**
[ATOF](#chmtopic401)
# <a name="chmtopic432"></a>**What's New in Posting/Universal Post Generator (UPG) for CAMWorks 2009**
### **CAMWorks 2009 SP0.0**
Post customization is required in order to use new commands and variables. These commands and variables are not supported in previous versions of CAMWorks or in any ProCAM product.
### **New Post Processor Output for Node Names**
**Purpose**

Provide post processor variables that report the various node names associated to each toolpath.

**Implementation**

Internal post processors can be customized to output the following node names during post processing: Part name-Part configuration, Setup name, Setup description, Feature name, Feature description, Operation name.

In the APT CL output, keywords and associated values are output for each of the node names.

[TLP_PART_NAME](#chmtopic404)

[TLP_PART_DESC](#chmtopic405)

[TLP_SETUP_NAME](#chmtopic406)

[TLP_SETUP_DESC](#chmtopic407)

[TLP_FEAT_NAME](#chmtopic408)

[TLP_FEAT_DESC](#chmtopic409)

[TLP_OPER_NAME](#chmtopic410)

[TLP_OPER_DESC](#chmtopic411)
\*\


**New Additional Variables**

[SETUP_ID](#chmtopic412)

[TOOLPATH_ID](#chmtopic413)

[NEXT_SETUP_4AX_ANGLE](#chmtopic414)

[NEXT_SETUP_5AX_ANGLE](#chmtopic415)

[PART_STOCK_DIAM](#chmtopic416)

[PART_STOCK_LENGTH](#chmtopic417)

[NEXT_OPR_TYPE](#chmtopic418)

[NEXT_OPR_SUB_TYPE](#chmtopic419)

[NEXT_IS_LATHE](#chmtopic420)

[QUERY_ITEM_ID](#chmtopic421)

[QUERY_RESULT](#chmtopic422)

[QUERY_ERROR](#chmtopic423)

[QUERY_INT_VALUE](#chmtopic424)

[QUERY_DEC_VALUE](#chmtopic425)

[IS_MILL_OD = TRUE or FALSE](#chmtopic426)

[IS_MILL_FACE = TRUE or FALSE](#chmtopic427)

[IS_WRAPPED = TRUE or FALSE](#chmtopic428)            

[IS_5AXIS = TRUE or FALSE](#chmtopic429)  



**New System Commands**

[QUERY_SYSTEM()](#chmtopic430)

This command will query any object ID you pass to it. It can get information from an object that is in a Setup or operation dialog box. Available in Mill, Turn and Mill-Turn.

[KILLSYSFILE()](#chmtopic431)

This command will delete any file that has a path in the new variable called SYSFILENAME.
# <a name="chmtopic450"></a>**What's New in Posting/Universal Post Generator (UPG) for CAMWorks 2008**
### **CAMWorks 2008 SP3.0**
### **New TOOL\_EDGE**  

|Purpose|Provide additional post support for CAMWorks.|
| :- | :- |
|Implementation|CAMWorks 2008 SP3.0 and later: the [TOOL_EDGE](#chmtopic434) variable has been added. Post customization is required in order to use this.|

-----

### **CAMWorks 2008**
### **New Commands and Variables**

|Purpose|Provide additional post support for CAMWorks.|
| :- | :- |
|Implementation|<p>CAMWorks 2008 and later: the following commands and variables have been added. Post customization is required in order to use these.</p><p>[LENGTH_DIAM_OFFSET_FROM_TOOL](#chmtopic435)</p><p>[TOOL_COOLANT](#chmtopic436)</p><p>[TOOL_DIAM_OFFSET](#chmtopic437)</p><p>[TOOL_LENGTH_OFFSET](#chmtopic438)</p><p>[TOOL_LENGTH_DIAM_OFFSET_METHOD](#chmtopic439)</p><p>[CW_DWELL](#chmtopic440)</p>|
### **New Multiaxis Commands and Variables**

|Purpose|Provide additional post support for CAMWorks Multiaxis machining.|
| :- | :- |
|Implementation|<p>CAMWorks 2008 and later: the following commands and variables have been added. Post customization is required in order to use these.</p><p>[5AXIS_CNC_COMP](#chmtopic441)</p><p>[HAVE_SURFACE_CP](#chmtopic442)</p><p>[MACH_CX](#chmtopic443)</p><p>[MACH_CY](#chmtopic444)</p><p>[MACH_CZ](#chmtopic445)</p><p>MACH\_CI</p><p>[MACH_CJ](#chmtopic446)</p><p>[MACH_CK](#chmtopic445)</p><p>[ABS_X_PART_END](#chmtopic447)</p><p>[ABS_Y_PART_END](#chmtopic448)</p><p>[ABS_Z_PART_END](#chmtopic449)</p>|

\
\

# <a name="chmtopic468"></a>**What's New in Posting/Universal Post Generator (UPG) for CAMWorks 2007**
### **CAMWorks 2007 SP2 and later**
### **New Editing Utilities**

|Purpose|Provide access from the UPG to utilities for customizing the MPS file for Machine Simulation, creating CAMWorks EDM posts and editing CAMWorks mill, turn and mill/turn posts.|
| :- | :- |
|Implementation|<p>New commands have been added to the File menu:</p><p>- Multiaxis MPS File Editor: Allows you to customize the MPS file that sets up the CAMWorks Machine Simulation  posting environment. This file should match the CAMWorks \*.kin file.</p><p>- Multiaxis Simulator Help: Opens a PDF file containing directions for editing the Machine Simulator in CAMWorks and the XML file.</p><p>- EDM Post Setup: Allows you to create new CAMWorks EDM posts. This utility adds the information to the registry so that the new post is listed in CAMWorks. Posts created using this utility can be edited using the EDM Post Editor.</p><p>- EC Post Editor: Allows you to fully customize CAMWorks mill, turn and mill/turn posts.  </p>|
### **New System Commands**

|Purpose|Provide additional post support for CAMWorks.|
| :- | :- |
|Implementation|<p>CAMWorks 2007 SP2 and later: The following commands have been added. Post customization is required in order to use these.</p><p>[RUN_PROCESS](#chmtopic452)</p><p>[TRANSFORM](#chmtopic7)</p>|
### **New Optional Mill and Lathe Post Sections**

|Purpose|Provide additional mill and lathe post sections for CAMWorks.|
| :- | :- |
|Implementation|CAMWorks 2007 SP2 and later.|

-----
### **CAMWorks 2007 and later**
### **New Command and Variables for CAMWorks Turn**

|Purpose|Provide additional post support for CAMWorks Turn.|
| :- | :- |
|Implementation|<p>CAMWorks 2007 and later: the following support has been added for CAMWorks Turn. Post customization is required in order to use these.</p><p>[FLAGGED(variable, bit value)](#chmtopic453)</p><p>[OPR_LATHE_APPROACH_STRATEGY](#chmtopic454)</p><p>[OPR_LATHE_RETRACT_STRATEGY](#chmtopic455)</p><p>[CAM_MOVE_FLAG](#chmtopic456)</p><p>[TOOL_ORIENT](#chmtopic457)</p><p>[OPR_SHIFT_TYPE](#chmtopic458)</p><p>[P_DRIVE_POINT_TYPE](#chmtopic459)</p><p>[DRIVE_POINT_TYPE](#chmtopic459)</p><p>[N_DRIVE_POINT_TYPE](#chmtopic459)</p><p>[P_TOUCHOFF_POINT_TYPE](#chmtopic460)</p><p>[TOUCHOFF_POINT_TYPE](#chmtopic460)</p><p>[N_TOUCHOFF_POINT_TYPE](#chmtopic460)</p><p>[P_LATHE_X_TOOL_OFFSET](#chmtopic461)</p><p>[LATHE_X_TOOL_OFFSET](#chmtopic461)</p><p>[N_LATHE_X_TOOL_OFFSET](#chmtopic461)</p><p>[P_LATHE_Z_TOOL_OFFSET](#chmtopic462)</p><p>[LATHE_Z_TOOL_OFFSET](#chmtopic462)</p><p>[N_LATHE_Z_TOOL_OFFSET](#chmtopic462)</p><p>[CALC_SLOWDOWN_SPEED](#chmtopic463)</p><p>[CALC_SHIFT_TOOL_LATHE](#chmtopic463)</p><p>[CALC_CUTTER_COMP_LATHE](#chmtopic463)</p>|


### **New Command and Variables for CAMWorks 2007**

|Purpose|Provide additional post support for CAMWorks 2007.|
| :- | :- |
|Implementation|<p>The following support has been added for new functions in CAMWorks 2007. Post customization is required in order to use these.</p><p>[CAMWORKS_VER](#chmtopic464)</p><p>[RAPID_DURING_DRILL_CYCLE](#chmtopic465)</p><p>[OPR_THREAD_CHAMFER_ANG](#chmtopic466)</p><p>[CAMWORKS_MATERIAL](#chmtopic467)</p><p>[CALC_ALLOW_RAPID_DURING_DRILL](#chmtopic463)</p><p>[CALC_SET_PRE_POSITION_ROTARY_TYPE](#chmtopic463)</p><p> </p>|

# <a name="chmtopic9"></a><a name="chmbookmark41"></a>**Configuring UPG Batch Compiler**
## **Illustrative Example for Configuring Compiler**
1. Create a batch file "xxxxx.bat" in any directory.
1. Edit this "xxxxx.bat" using a text editor.
1. In first line, enter **@ECHO OFF**.
1. In second line, enter **CD "C:\CAMWorksData\UPG-2"**. This is the default directory for **compile.exe**. Alternatively, this directory could be wherever you have installed the UPG-2 application.
1. In third line, enter the compiler name “**compile.exe** ”. Make sure you input the space character after the compiler name.
1. On the third line after the compile.exe, you will need to enter the parameters that need to be passed on to the compiler program. These parameters will  need to have double quotes around them with a space in between each parameter. You can pass up to maximum 8 parameters. These parameters are listed below: 
- Parameter #1 = Post SRC name with path **“C:\Post\fanuc.src”**. 
- Parameter #2 = Post SRC name **“fanuc.src”**.
- Parameter #3 = Master ATR file name and path **“C:\Post\master.atr”**.
- Parameter #4 = Compiled CTL directory **“C:\post\ctl”**.
- Parameter #5 = Compiler Type – S for standard and X for CAMWorks express posts = **“S”**.
- Parameter #6 = Compile.exe working directory **“C:\CAMWorksData\UPG-2”**.
- Parameter #7 = Post License or license numbers “xxxxx”. If not using, then just enter “”.
- Parameter #8 = Post license expiration date “xxxxx”. If not using, then just enter “”.


# <a name="chmtopic96"></a>**Posting Feature Notes for Multi Turret Functionality**

|<h4>**ASSOCIATED SYSTEM HEADER COMMAND**</h4>|
| :- |
|[:SYSTEM=LATHE4AX](#chmtopic471)|
|<h4>**ADDED LIBRARY FILES**</h4>|
|LATHE\_MULTI\_TURRET.LIB|
|MILLTURN\_MULTI\_TURRET.LIB|
|<h4>**New SYSTEM VARIABLES**</h4>|
|[N_TURRET_NUM](#chmtopic115)|
|[NEXT_USER_TURRET_NUM](#chmtopic102)|
|[NUM_TURRETS FRONT](#chmtopic281)|
|[NUM_TURRETS_REAR](#chmtopic282)|
|[P_TURRET_NUM](#chmtopic115)|
|[TURRET_NUM](#chmtopic115)|
|[SYNCED_WITH_FRONT1](#chmtopic108)|
|[SYNCED_WITH_FRONT2](#chmtopic109)|
|[SYNCED_WITH_REAR1](#chmtopic110)|
|[SYNCED_WITH_REAR2](#chmtopic111)|
|<h4>**ASSOCIATED CONSTANTS**</h4>|
|[FRONT1](#chmbookmark36)|
|[FRONT2](#chmbookmark37)|
|[REAR1](#chmbookmark38)|
|[REAR2](#chmbookmark39)|
|<h4>**ASSOCIATED SYSTEM CALC SECTIONS**</h4>|
|[:SECTION=CALC_SET_TURRET_CHANNEL](#chmtopic125)|
|<h4>**ASSOCIATED POST ATTRIBUTE NAMES**</h4>|
|rear2 x preset|
|rear2 z preset|
|front2 u preset|
|front2 w preset|
|rear2 sub x preset|
|rear2 sub z preset|
|front2 sub u preset|
|front2 sub w preset|
|<h4>**New SYSTEM COMMANDS**</h4>|
|[FLUSH_ALL_SYNC_CODES()](#chmtopic119)|



Further topic for reference: [List of changes to be made to support Multi Turret (2-4 turrets) Functionality](#chmtopic97).
# <a name="chmtopic97"></a><a name="chmbookmark42"></a>**List of changes to be made to support Multi Turret Functionality in CAMWorks 2019 SP0 and Later Versions**
Click on the below hyperlinks to jump to the corresponding section:

1. [Set system command in a Turn SRC file](#chmbookmark43)
1. [Set system command in a MillTurn SRC file](#chmbookmark44)
1. [Add Header command in SRC file](#chmbookmark45)
1. [Add Library file to Lathe SRC file as the first library in list](#chmbookmark46)
1. [Add library file to Millturn SRC file as the first library in list](#chmbookmark47)
1. [Add new post attributes to LIB file and SRC files](#chmbookmark48)
1. [Add new Post variables](#chmbookmark49)
1. [Add new calc sections](#chmbookmark50)
1. [Changed :SECTION=CALC_QUERY_POST section](#chmbookmark51)
1. [Changed SECTION=CALC_INITIALIZE](#chmbookmark52)
1. [Add Addition template sections](#chmbookmark53)
1. [Changed SECTION=CALC_INIT_CODES section](#chmbookmark54)
1. [New general lib file for multi turret support for turn post](#chmbookmark55)
1. [New general lib file for multi turret support for millturn post](#chmbookmark56)
1. [New post command “FLUSH_ALL_SYNC_CODES()](#chmbookmark57)
-----
## <a name="chmbookmark43"></a>**1. Set system command in a Turn SRC file**
**SYSTEM=LATHE4AX**

For illustrative example, refer the T4axis-tutorial.src file.

[Top of Page](#chmbookmark42)

-----

## <a name="chmbookmark44"></a>**2. Set system command in a MillTurn SRC file**
**SYSTEM=LATHE4AX/MILL**

For illustrative example, refer the MT4axis-tutorial.src file.

[Top of Page](#chmbookmark42)

-----

## <a name="chmbookmark45"></a>**3. Add Header command in SRC file**
**SORT\_BY\_TURRET=TRUE or FALSE**

For illustrative examples, refer the T4axis-tutorial.src and/or MT4axis-tutorial.src files.

[Top of Page](#chmbookmark42)

-----

## <a name="chmbookmark46"></a>**4. Add Library file to Lathe SRC file as the first library in list**
**LATHE\_MULTI\_TURRET.LIB**

For illustrative example, refer the T4axis-tutorial.src file.

[Top of Page](#chmbookmark42)

-----

## <a name="chmbookmark47"></a>**5. Add library file to Millturn SRC file as the first library in list**
**MILLTURN\_MULTI\_TURRET\_LIB**

For illustrative example, refer the T4axis-tutorial.src file.

[Top of Page](#chmbookmark42)

-----

## <a name="chmbookmark48"></a>**6. Add new post attributes to LIB file and SRC files**
rear2 x preset

rear2 z preset

front2 u preset

front2 w preset

rear2 sub x preset

rear2 sub z preset

front2 sub u preset

front2 sub w preset

For illustrative examples, refer the LATHE.LIB, MILLTURN.LIB, T4axis-tutorial.src and MT4axis-tutorial.src files.



[Top of Page](#chmbookmark42)

-----

## <a name="chmbookmark49"></a>**7. Add new Post variables**
NOT\_USING\_MULTIPLE\_FILES

SEQ\_NUMBERS\_PER\_TURRET

TOTAL\_NUMBER\_OF\_TURRETS

For illustrative examples, refer the LATHE.LIB and MILLTURN.LIB files.



[Top of Page](#chmbookmark42)

-----

## <a name="chmbookmark50"></a>**8. Add new calc sections**
CALC\_END\_BONDARY\_RETRACT\_MULTI\_TURRET

CALC\_RETRACT\_X\_MULTI\_TURRET

CALC\_RETRACT\_Z\_MULTI\_TURRET

CALC\_RETRACT\_Z\_THEN\_X\_MULTI\_TURRET

CALC\_RETRACT\_X\_THEN\_Z\_MULTI\_TURRET

For illustrative examples, refer the LATHE.LIB and MILLTURN.LIB files.



CALC\_SET\_TURRET\_CHANNEL

CALC\_RESET\_TURRETS

CALC\_DELETE\_MULTIPLE\_FILES

For illustrative examples, refer the LATHE\_MULTI\_TURRET.LIB and MILLTURN\_MULTI\_TURRET.LIB files.



[Top of Page](#chmbookmark42)

-----

## <a name="chmbookmark51"></a>**9. Change :SECTION=CALC\_QUERY\_POST section**
:C: IF CAMWORKS\_VER<CAM\_REV2019 THEN

:C:    IF QUERY\_ITEM\_ID = QUERY\_INT\_NUM\_TURRETS\_ABOVE THEN QUERY\_INT\_VAL=1 RETURN ENDIF

:C:    IF QUERY\_ITEM\_ID = QUERY\_INT\_NUM\_TURRETS\_BELOW THEN QUERY\_INT\_VAL=1 RETURN ENDIF

:C: ELSE

:C:    IF QUERY\_ITEM\_ID = QUERY\_INT\_NUM\_TURRETS\_ABOVE THEN QUERY\_INT\_VAL=NUM\_TURRETS\_REAR RETURN ENDIF

:C:    IF QUERY\_ITEM\_ID = QUERY\_INT\_NUM\_TURRETS\_BELOW THEN QUERY\_INT\_VAL=NUM\_TURRETS\_FRONT RETURN ENDIF

:C: ENDIF



:C: IF OPR\_TOOL\_TIP\_CENTER=1 THEN

:C:    IF HAVE\_SUB\_STATIONS=FALSE THEN

:C:       IF QUERY\_ITEM\_ID = QUERY\_INT\_CENTER\_TOUCHOFF\_REG THEN

:C:          IF SECTIONEXIST(QUERY\_TOUCHOFF\_CENTER) THEN

:C:          CALL(QUERY\_TOUCHOFF\_CENTER)

:C:          ELSE

:C:          QUERY\_INT\_VAL=(TOOL+1)

:C:          ENDIF

:C:       ENDIF

:C:    ELSE

:C:       IF QUERY\_ITEM\_ID = QUERY\_INT\_CENTER\_TOUCHOFF\_REG THEN

:C:          IF SECTIONEXIST(QUERY\_TOUCHOFF\_CENTER\_SUB\_STATIONS) THEN

:C:          CALL(QUERY\_TOUCHOFF\_CENTER\_SUB\_STATIONS)

:C:          ELSE

:C:          QUERY\_INT\_VAL=((SUB\_STATION\*10)+2)

:C:          ENDIF

:C:       ENDIF

:C:    ENDIF

:C: ENDIF



:C: IF QUERY\_ITEM\_ID = QUERY\_GCODE\_FILE\_NAME\_T2A THEN

:C:   IF SECTIONEXIST(QUERY\_FILE\_NAME\_T2A) THEN CALL(QUERY\_FILE\_NAME\_T2A) ENDIF

:C: ENDIF

:C: IF QUERY\_ITEM\_ID = QUERY\_GCODE\_FILE\_NAME\_T2B THEN

:C:   IF SECTIONEXIST(QUERY\_FILE\_NAME\_T2B) THEN CALL(QUERY\_FILE\_NAME\_T2B) ENDIF

:C: ENDIF



For illustrative examples, refer the LATHE.LIB and MILLTURN.LIB files.



[Top of Page](#chmbookmark42)

-----

## <a name="chmbookmark52"></a>**10. Change SECTION=CALC\_INITIALIZE**
Add the following line:

:C: CALL(CALC\_CONFIGURE\_TURRETS)

For illustrative examples, refer the LATHE.LIB and MILLTURN.LIB files.



[Top of Page](#chmbookmark42)

-----

## <a name="chmbookmark53"></a>**11. Add Additional template sections**
**Additional Template sections for Turn and MillTurn source files**

SECTION=BLANK\_LINE

SECTION=START\_OF\_TAPE\_REAR1

SECTION=START\_OF\_TAPE\_REAR2

SECTION=START\_OF\_TAPE\_FRONT1

SECTION=START\_OF\_TAPE\_FRONT2

SECTION=START\_MULTIPLE\_PROGRAMS

SECTION=ERROR

SECTION=ADD\_REAR\_SYNC\_CODE\_MULTI

SECTION=ADD\_FRONT\_SYNC\_CODE\_MULTI

SECTION=INIT\_TOOL\_CHANGE\_LATHE\_REAR1

SECTION=INIT\_TOOL\_CHANGE\_LATHE\_REAR2

SECTION=INIT\_TOOL\_CHANGE\_LATHE\_FRONT1

SECTION=INIT\_TOOL\_CHANGE\_LATHE\_FRONT2

SECTION=SUB\_TOOL\_CHANGE\_LATHE\_REAR1

SECTION=SUB\_TOOL\_CHANGE\_LATHE\_REAR2

SECTION=SUB\_TOOL\_CHANGE\_LATHE\_FRONT1

SECTION=SUB\_TOOL\_CHANGE\_LATHE\_FRONT2

SECTION=END\_OF\_TAPE\_REAR1

SECTION=END\_OF\_TAPE\_REAR2

SECTION=END\_OF\_TAPE\_FRONT1

SECTION=END\_OF\_TAPE\_FRONT2

SECTION=END\_MULTIPLE\_PROGRAMS

SECTION=CALC\_CONFIGURE\_TURRETS

SECTION=QUERY\_FILE\_NAME\_T2A

SECTION=QUERY\_FILE\_NAME\_T2B



**Additional Template sections exclusively for MillTurn source files**

SECTION=INIT\_TOOL\_CHANGE\_MILL\_REAR1

SECTION=INIT\_TOOL\_CHANGE\_MILL\_REAR2

SECTION=INIT\_TOOL\_CHANGE\_MILL\_FRONT1

SECTION=INIT\_TOOL\_CHANGE\_MILL\_FRONT2

SECTION=SUB\_TOOL\_CHANGE\_MILL\_REAR1

SECTION=SUB\_TOOL\_CHANGE\_MILL\_REAR2

SECTION=SUB\_TOOL\_CHANGE\_MILL\_FRONT1

SECTION=SUB\_TOOL\_CHANGE\_MILL\_FRONT2

For illustrative examples, refer the T4axis-tutorial.src and MT4axis-tutorial.src files.



[Top of Page](#chmbookmark42)

-----

## <a name="chmbookmark54"></a>**12. Change the SECTION=CALC\_INIT\_CODES section**
Add the following:

:C: NOT\_USING\_MULTIPLE\_FILES=NO or YES

:C: SEQ\_NUMBERS\_PER\_TURRET =NO or YES

[Top of Page](#chmbookmark42)

-----

## <a name="chmbookmark55"></a>**13. New general lib file for multi turret support for turn post**
New general lib file for multi turret support for turn post - LATHE\_MULTI\_TURRET.LIB

This file has new or modified CALC sections and additional post variables for handling multi turret support to be used in CAMWorks 2019 or later versions of CAMWorks.

This file must be listed as the first LIBRARY command in a Turn src file that needs multi turret support. Below are modified sections in this library.



CALC\_START\_OF\_TAPE

CALC\_START\_OPERATION

CALC\_INIT\_TOOL\_CHANGE\_LATHE

CALC\_SUB\_TOOL\_CHANGE\_LATHE

CALC\_END\_OPERATION

CALC\_ADD\_REAR\_SYNC\_CODE

CALC\_ADD\_FRONT\_SYNC\_CODE

CALC\_END\_OF\_TAPE

CALC\_SETUP\_SHEET

[Top of Page](#chmbookmark42)

-----

## <a name="chmbookmark56"></a>**14. New general lib file for multi turret support for millturn post**
New general lib file for multi turret support for millturn post - MILLTURN\_MULTI\_TURRET.LIB

This file has new or modified CALC sections and additional post variables for handling multi turret support to be used in CAMWorks 2019 or later versions of CAMWorks.

This file must be listed as the first LIBRARY command in a turn src file that needs multi turret support. Below are modified sections in this library.



CALC\_START\_OF\_TAPE

CALC\_START\_OPERATION

CALC\_INIT\_TOOL\_CHANGE\_LATHE

CALC\_SUB\_TOOL\_CHANGE\_LATHE

CALC\_INIT\_TOOL\_CHANGE\_MILL

CALC\_SUB\_TOOL\_CHANGE\_MILL

CALC\_END\_OPERATION

CALC\_ADD\_REAR\_SYNC\_CODE

CALC\_ADD\_FRONT\_SYNC\_CODE

CALC\_END\_OF\_TAPE

CALC\_SETUP\_SHEET

[Top of Page](#chmbookmark42)

-----

## <a name="chmbookmark57"></a>**15. New Post Command “FLUSH\_ALL\_SYNC\_CODES()"**
This new command needs to be in CALC\_END\_OF\_TAPE

:C: IF (NUM\_TURRETS\_REAR+NUM\_TURRETS\_FRONT)>1 THEN

:C: FLUSH\_ALL\_SYNC\_CODES()

:C: ENDIF

For illustrative examples, refer the LATHE\_MULTI\_TURRET.LIB and MILLTURN\_MULTI\_TURRET.LIB files.
## [Top of Page](#chmbookmark42)
-----

# <a name="chmtopic474"></a>**Posting Feature Notes for Pinch Turning Functionality**
### <a name="chmbookmark35"></a>**Posting Feature Notes for Pinch Turning**

|<h4>**ASSOCIATED SYSTEM HEADER COMMAND**</h4>|
| :- |
|[:ALLOW_FIRST_FEED_SYNC_ON_CANNED_CYCLE](#chmtopic99)|
|<h4>**ASSOCIATED VARIABLES**</h4>|
|[OPR_PINCH_TURNING](#chmtopic118)|
|[HAVE_FIRST_FEED_SYNC_CODES](#chmtopic100)|



Further topic for reference: [List of changes to be made to support Pinch Turning Functionality](#chmtopic95).

-----

# <a name="chmtopic95"></a>**List of changes to be made to support Pinch Turning Functionality in CAMWorks 2019 SP0 and later versions**
1. **Add Header command in SRC file.**

:ALLOW\_FIRST\_FEED\_SYNC\_ON\_CANNED\_CYCLE=TRUE



For reference, see T4axis-tutorial.src and MT4axis-tutorial.src.

**NOTE:  This is required for Canned cycle output only.**

2. **Add the below line, 2 places each in CALC\_START\_BOUNDARY\_LATHE**

:C:    CALL(CALC\_OUTPUT\_BEFORE\_FEED\_SYNC\_BEFORE\_CANNED\_CYCLE)



For reference, see LATHE.LIB and MILLTURN.LIB files.

**NOTE:  This is required for Canned cycle output only.**

3. **Added below calc section**

:SECTION=CALC\_OUTPUT\_BEFORE\_FEED\_SYNC\_BEFORE\_CANNED\_CYCLE

:C: IF CAMWORKS\_VER<CAM\_REV2019 THEN RETURN ENDIF

:C: IF HAVE\_FIRST\_FEED\_SYNC\_CODES=TRUE THEN

:C: OUTPUT\_FIRST\_FEED\_SYNC\_CODES()

:C: ENDIF



For reference, see LATHE.LIB and MILLTURN.LIB files

**NOTE:  This is required for Canned cycle output only.**
# <a name="chmtopic76"></a><a name="chmbookmark58"></a>**Posting Feature Notes for Simultaneous B Axis Output for Turning**

|<h4>**ASSOCIATED SYSTEM HEADER COMMAND**</h4>|
| :- |
|[:ALLOW_B_AXIS_SIMULTANEOUS_CUTTING=TRUE](#chmtopic77)|
|<h4>**ASSOCIATED VARIABLES**</h4>|
|[TLP_B_AXIS_OFFSET](#chmtopic93)|
|[P_TLP_B_AXIS_OFFSET](#chmtopic93)|
|[OPR_TOOL_TIP_CENTER](#chmtopic92)|
|[MAX_B_AXIS_INCREMENT](#chmtopic81)|
|[OPR_BAXIS_TURNING](#chmtopic91)|
|[NEXT_OPR_BAXIS_TURNING](#chmtopic82)|
|<h4>**New QUERY COMMAND**</h4>|
|[QUERY_INT_CENTER_TOUCHOFF_REG](#chmtopic94)|
|<h4>**New SYSTEM CANNED CYCLE COMMAND**</h4>|
|[SYS_CANNED(7,?????)](#chmtopic477)|



Further topic for reference: [List of changes to be made to support Simultaneous B Axis Functionality](#chmtopic478).
# <a name="chmtopic478"></a>**List of changes to be made to support Simultaneous B Axis Functionality in CAMWorks 2019 SP1 and later versions**
1. **Add New Header command in SRC file**

ALLOW\_B\_AXIS\_SIMULTANEOUS\_CUTTING=TRUE or FALSE

For reference, see T2axis-tutorial.src or MT2axis-tutorial.src files.

2. **Add New Post Variable**

CREATE\_SMALLER\_LATHE\_ARCS

For reference, see LATHE.LIB or MILLTURN.LIB files

3. **Change the section named SECTION=CALC\_ENDPOINT**

:C:    IF CAMWORKS\_VER<CAM\_REV2019\_SP1 THEN

:C:       IF CAMWORKS\_VER>CAM\_REV2015\_SP2 THEN

:C:          IF REG=2 THEN

:C:          DVAL=(DVAL+OPR\_B\_AXIS\_OFFSET)

:C:          ENDIF

:C:       ENDIF

:C:    ELSE

:C:       IF REG=2 THEN

:C:       DVAL=(DVAL+OPR\_B\_AXIS\_OFFSET+TLP\_B\_AXIS\_OFFSET)

:C:       ENDIF

:C:    ENDIF

For reference see LATHE.LIB or MILLTURN.LIB files

4. **Changed section SECTION=CALC\_INIT\_CODES**

Added :C: CREATE\_SMALLER\_LATHE\_ARCS=NO

For reference, see T2axis-tutorial.src or MT2axis-tutorial.src files

5. **Changed section SECTION=CALC\_LINE\_MOVE\_LATHE**

   Added and changed logic to call CALC\_LINE\_LEADIN\_LATHE and CALC\_LINE\_LEADOUT\_LATHE. Changed logic in this section and the Leadin and Leadout section to handle calling different template sections depending on whether there was a B axis move or not.

   For reference, see LATHE.LIB or MILLTURN.LIB files

6. **Changed section SECTION=CALC\_ARC\_MOVE\_LATHE**

   Added logic to handle arc to arc breakup if needed in a B axis simultaneous move.

   Added logic to call a different template section depending on whether there was a B axis move or not.

   For reference, see LATHE.LIB or MILLTURN.LIB files



7. **Add new CALC sections**

   CALC\_BREAK\_ARC\_TO\_ARC\_LATHE

   CALC\_BREAK\_RADIAL\_ARC\_TO\_ARC\_LATHE

   For reference, see LATHE.LIB or MILLTURN.LIB files


## <a name="chmtopic481"></a>**ABS**
#### **Purpose**
Returns the absolute value of an argument or number.
#### **Syntax**
**ABS(arg)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|arg|can be any expression or number|


#### **Example**
Check if two points are the same:

:C: IF ABS(X\_START X\_END)<.00005 THEN CALL(SAME) ENDIF

Assign the absolute value of a number to another variable:

:C: DISTANCE=(ABS(INC\_X\_END))
## <a name="chmtopic483"></a>**ACOS**
#### **Purpose**
Returns the arc cosine of a value from 1 to 1.
#### **Syntax**
**ACOS(r)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|r|must be a value between 1 and 1|



ACOS returns a value in radians between 0 and 3.141593.
#### **Example**
:C: Y=(ACOS(X))
## <a name="chmtopic485"></a>**ADD\_MACRO\_END**
#### **Purpose**
To define the end of a macro. This command cancels an ADD\_MACRO\_START command and redirects all code back to the main program tape.
#### **Syntax**
**ADD\_MACRO\_END**
#### **Comments**
#### **Example**
:C: ADD\_MACRO\_END
## <a name="chmtopic487"></a>**ADD\_MACRO\_START**
#### **Purpose**
To define the start of a macro. This command redirects all code to a secondary file, which is used to store all subprograms prior to the system inserting the subprogram file before or after the main tape.
#### **Syntax**
**ADD\_MACRO\_START**
#### **Comments**
None.
#### **Example**
:C: ADD\_MACRO\_START
## <a name="chmtopic489"></a>**APPEND**
#### **Purpose**
To append another file into current part that is being posted.
#### **Syntax**
**:C: APPEND(STRG)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|strg|The strg must be defined in the attribute section as a string variable. The strg should hold the path and filename you want to append.|



The APPEND command will put whatever information is in the file you append into the file you are posting. This command could be used for a special cycle that is hardcoded and happens all the time.
#### **Example**
:SECTION=CALC\_APPEND\_FILE

:C: STRG={C:\PROCAM\DRILL.TXT}

**:C: APPEND(STRG)**
## <a name="chmtopic491"></a>**ASIN**
#### **Purpose**
Returns the arc sine of a value from 1 to 1.
#### **Syntax**
**ASIN(r)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|r|must be a value between 1 and 1|



ASIN returns a value in radians between 0 and 3.141593.
#### **Example**
:C: Y=(ASIN(X))
## <a name="chmtopic493"></a>**ATAN**
#### **Purpose**
Returns the arc tangent of x.
#### **Syntax**
**ATAN(x)**
#### **Comments**
ATAN returns a value between (3.141593/2) and ( 3.141593/2).
#### **Example**
:C: V=(ATAN(X))
## <a name="chmtopic495"></a>**ATAN2**
#### **Purpose**
Returns the arc tangent of dx and dy (i.e., the slope of a line).
#### **Syntax**
**ATAN2(dx,dy)**
#### **Comments**
ATAN2 returns a value between 3.141593 and 3.141593.
#### **Example**
:C: V=(ATAN2(DX,DY))
## <a name="chmtopic401"></a>**ATOF**
#### **Purpose**
To turn a string input into a number.
#### **Syntax**
**ATOF()**
#### **Comments**
This will work in connection with opening an external file. By reading in an external file line by line, you will be able to transform the string into a number, if required.
#### **Examples**
The example code below shows you how you could use this command. The post variable TESTSTR could also be a string that was being read in line by line from an external file. MyVal could be either an integer or decimal post variable.

:C: TESTSTR={6.1957}

:C: MyVal=ATOF(TESTSTR)

:C: CALL(SEE\_MY\_VAL)

The result:

N1 X6.1957


## <a name="chmtopic498"></a>**CALL**
#### **Purpose**
To call another section of the post.
#### **Syntax**
## **A**
**CALL(section)**
## **B**
**CALL(section(arga,argb,...))**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|section|must be an existing section in the post. The CALL function can only call a SECTION.|
|arga|argument that is passed to the section (Syntax B)|
|argb|argument that is passed to the section (Syntax B)|



When passing arguments, the section must be defined to be capable of accepting arguments. See SECTION= below.
#### **Example**
## **A**
:C: CALL(LINE\_MOVE\_MILL)

:SECTION=LINE\_MOVE\_MILL

:T:<N><G:01><X><Y><Z><F><attributes><EOL>
## **B**
**:C: CALL(CALC\_ESTIMATE\_TIME(DISTANCE,OPR\_X\_FEED,TIME))**

:SECTION=CALC\_ESTIMATE\_TIME(DIS,FEED,TIME)

:C: IF FEED=0 THEN RETURN ENDIF

:C: TIME=(TIME+(DIS/FEED))
## <a name="chmtopic500"></a>**CLOSETXT**
#### **Purpose**
Allows the post to close external files and write to them while posting.
#### **Syntax**
**CLOSETXT(FileNumber)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|FileNumber|Alternate text file ID number - range (0 to 20) – 0 reserved for Post Text file and cannot be used in OPENTXT or CLOSETXT.|

## <a name="chmtopic502"></a>**COS**
#### **Purpose**
Returns the cosine of an angle in radians.
#### **Syntax**
**COS(ang)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|Ang|an angle in radians|



To convert degrees to radians, multiply by (PI/180).
#### **Example**
:C: X\_POS=(ABS\_I\_CENTER+(ARC\_RADIUS\*COS(ARC\_END\_ANGLE\*(PI/180))))
## <a name="chmtopic504"></a>**FASTLINE**
#### **Purpose**
To output lines of code at a faster rate then normal. This is only available in the 3 axis milling operations.
#### **Syntax**
**FASTLINE(template\_section)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|template\_section|The template section that will output the lines of code. You will need to define the ATTRNAMES listed below.|
**\


\*----------------------------------------------------------

:ATTRNAME=FX

:ATTRTYPE=POST

:ATTRVTYPE=DECIMAL

:ATTREMARK=X End

:CODETYPE=FORMAT

:WORD\_ADDRESS\_BEF=|X

:VAR=ABS\_X\_END

:MODAL=YES

:ATTREND

\*-----------------------------------

:ATTRNAME=FY

:ATTRTYPE=POST

:ATTRVTYPE=DECIMAL

:ATTREMARK=Y End

:CODETYPE=FORMAT

:WORD\_ADDRESS\_BEF=|Y

:VAR=ABS\_Y\_END

:MODAL=YES

:ATTREND

\*-----------------------------------

:ATTRNAME=FZ

:ATTRTYPE=POST

:ATTRVTYPE=DECIMAL

:ATTREMARK=Z End

:CODETYPE=FORMAT

:WORD\_ADDRESS\_BEF=|Z

:VAR=ABS\_Z\_END

:MODAL=YES

:ATTREND



Normally you will need to start this command in the CALC\_START\_OPERATION section as shown below.

:C: IF SECTIONEXIST(FASTLINE) THEN

:C: IF OPR\_TYPE=MILL\_UV\_CUT

:C: OR OPR\_TYPE=MILL\_SLICE\_CUT

:C: OR OPR\_TYPE=MILL\_ROUGH\_CUT

:C: OR OPR\_TYPE=MILL\_CURVE\_CUT

:C: OR OPR\_TYPE=MILL\_TOPO\_CUT

:C: OR OPR\_TYPE=MILL\_FREEFORM\_CUT THEN

:C: FASTLINE(FASTLINE)

:C: ENDIF

:C: ENDIF



The template section should look like this.

**:SECTION=FASTLINE**

**:T:<N><G:01><FX><FY><FZ><EOL>**
## <a name="chmtopic506"></a>**GET\_OPER\_COMMENTS**
#### **Purpose**
To get the comments from the current operation. This command outputs the comments entered in the Comments dialog box. Used in Mill and Lathe only.
#### **Syntax**
**GET\_OPER\_COMMENTS(section)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|section|<p>section that will be called each time a comment is loaded.</p><p>The word SYSTEM instructs the system to output the comments directly to the tape.</p>|


#### **Example**
:SECTION=CALC\_SUB\_TOOL\_CHANGE\_MILL

**:C: GET\_OPER\_COMMENTS(CALC\_OUTPUT\_OPER\_COMMENT)**



:SECTION=CALC\_OUTPUT\_OPER\_COMMENT

:C: CALL(OUTPUT\_OPER\_COMMENT)



:SECTION=OUTPUT\_OPER\_COMMENT

:T:<N><OPR\_COMMENT><EOL>
## <a name="chmtopic508"></a>**GET\_SELECT STRING**
#### **Purpose**
To gather a string list from a life that will update the list selection from the Setup Info. It lets the user put more materials in the file and not have to recompile the post. The file that will store the string lists corresponds to the name of the compiled post. If the compiled post is FANUC6M.CTL, then the file used will be FANUC6M.CNF.
#### **Syntax**
These commands are associated with this command, which will be in the \*.CNF file.

|*Command*|*Description*|
| :- | :- |
|CONFIG\_SELECT\_NAME|The name of the lowercase attribute that will show the list in the Setup Info.|
|CONFIG\_SELECT\_OPTION|The string that you want to select from. You can have as many of these in a row as needed. It basically creates the list.|
|CONFIG\_SELECT\_DEFAULT|Sets the default selection from the list. If you wanted the 3rd string in the list as the default, then this would equal 3.|
|CONFIG\_SELECT\_END|Lets the post know you are done with the list.|



This is what would be in the \*.CNF file.

:CONFIG\_SELECT\_NAME=material type

:CONFIG\_SELECT\_OPTION=STEEL

:CONFIG\_SELECT\_OPTION=STAINLESS** STEEL

:CONFIG\_SELECT\_OPTION=ALUMINUM

:CONFIG\_SELECT\_OPTION=COPPER

:CONFIG\_SELECT\_DEFAULT=3

:CONFIG\_SELECT\_END
#### **Comments**
Below is an example of using this for gathering a list of materials.

\*------------------------------

:ATTRNAME=material type

:ATTRTYPE=SELECT

:ATTREMARK=Material type

:ATTRSEL=N

:ATTRTITLE=Material Type

:ATTRSELSTR=Rolled Steel

:ATTRSELSTR=Aluminum

:ATTRSELSTR=Stainless Steel

:ATTRDEFAULT=1

:ATTRUSED=1

:ATTREND

\*-----------------------------------

:ATTRNAME=S MATERIAL TYPE

:ATTRTYPE=POST

:ATTRVTYPE=CHARACTER

:ATTREMARK=

:CODETYPE=FORMAT

:WORD\_ADDRESS\_BEF=|(

:WORD\_ADDRESS\_AFT=)

:LEFT\_PLACES=0

:RIGHT\_PLACES=0

:UNITFLAG=NON\_CONVERT

:ATTRSPACES=YES

:MODAL=YES

:ATTRUSED=1

:ATTREND
**\


\*-----------------------------------

:SECTION=CALC\_INIT\_TOOL\_CHANGE\_MILL

:C: IF SECTIONEXIST(DEBUG) THEN

:C: DEBUG=4 CALL(DEBUG)

:C: ENDIF

\*
**\


:C: GET\_SELECT\_STRING(material\_type,S\_MATERIAL\_TYPE)

:C: CALL(OUPTUT\_MATERIAL)
**\


\*-----------------------------------

:SECTION=OUTPUT\_MATERIAL

:T:<S\_MATERIAL\_TYPE>



**GET\_SELECT\_STRING(material\_type,S\_MATERIAL\_TYPE)**

Material\_type is an attribute that is defined and is lower case, plus it needs to be defined in the master.atr file. You can insert a few :ATTRSELSTR= in this definition as shown above.

The next attribute defined is the output post attribute S\_MATERIAL\_CODE, which can be any name you give it.

The section called :SECTION=CALC\_INIT\_TOOL\_CHANGE\_MILL is where I will start the command. GET\_SELECT\_STRING(material\_type,S\_MATERIAL\_TYPE), then call a template section to test out the selection :C: CALL(OUTPUT\_MATERIAL). Make sure you have a template section created for the call. You do not need to do this step if you do not need to output the selected string.
## <a name="chmtopic13"></a>**GET\_SW\_CUSTOM\_PROP\_BY\_NAME**
#### **Purpose**
Gets SOLIDWORKS Custom properties. If the field is found, the system will call one of the CALC sections listed below: 

- CALC\_GET\_SW\_PROPERTIES
- CALC\_GET\_SW\_SUMMARY\_FIELDS
- CALC\_GET\_SW\_CUSTOM\_FIELDS
- CALC\_OUTPUT\_SW\_PROPERTY

These Calc sections are called with the attribute parameters [QUERY_SW_FIELD_NAME](#chmtopic68) and [QUERY_SW_FIELD_VAL](#chmtopic70).

To be used in CAMWorks 2020 SP0 or higher versions. 


#### **Syntax**
**GET\_SW\_CUSTOM\_PROP\_BY\_NAME({field name}, CALC\_?????)**





**Logic to be used in CALC\_START\_OF\_TAPE**

\*Outputs SOLIDWORKS Custom and Summary property fields

:C: IF SECTIONEXIST(OUTPUT\_SW\_PROPERTY) THEN

:C: CALL([CALC_GET_SW_PROPERTIES](#chmtopic45))

:C: ENDIF

\*\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_





**Logic to be used in \*SRC File** 

**:SECTION=OUTPUT\_SW\_PROPERTY**

:T:<N> (<[QUERY_SW_FIELD_NAME](#chmtopic68)><[QUERY_SW_FIELD_VAL](#chmtopic70)> )<EOL>

\*\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_


#### **Comments**
For information on the Calc Sections used with GET\_SW\_CUSTOM\_PROP\_BY\_NAME, click on the below hyperlinks: 

- [CALC_GET_SW_PROPERTIES ](#chmtopic45)
- [CALC_GET_SW_SUMMARY_FIELDS](#chmtopic46)
- [CALC_GET_SW_CUSTOM_FIELDS ](#chmtopic44)
- [CALC_OUTPUT_SW_PROPERTY ](#chmtopic47)

For post examples pertaining to the attribute parameters used with OUTPUT\_SW\_PROPERTY, click on the below hyperlinks:  

- [QUERY_SW_FIELD_NAME](#chmtopic68)
- [QUERY_SW_FIELD_VAL](#chmtopic70)


## <a name="chmtopic14"></a>**GET\_SW\_SUMMARY\_INFO\_BY\_ID**
#### **Purpose**
Gets SOLIDWORKS Custom properties summary information. If the field is found, the system will call one the CALC sections listed below: 

- CALC\_GET\_SW\_PROPERTIES
- CALC\_GET\_SW\_SUMMARY\_FIELDS
- CALC\_GET\_SW\_CUSTOM\_FIELDS
- CALC\_OUTPUT\_SW\_PROPERTY

To be used in CAMWorks 2020 SP0 or higher versions. 




#### **Syntax**
**GET\_SW\_SUMMARY\_INFO\_BY\_ID(SW\_FIELD\_ID, CALC\_?????)**


#### **Constants**
Constants for SW\_FIELD\_ID:

- SW\_INFO\_TITLE
- SW\_INFO\_SUBJECT
- SW\_INFO\_AUTHOR
- SW\_INFO\_KEYWORDS
- SW\_INFO\_COMMENTS
- SW\_INFO\_SAVED\_BY
- SW\_INFO\_CREATION\_DATE
- SW\_INFO\_SAVED\_DATE
#### **Comments**
The system will also query the result and store a field type in an integer parameter – QUERY\_SW\_FIELD\_TYPE. 

For more details, refer: [QUERY_SW_FIELD_TYPE](#chmtopic69).  




## <a name="chmtopic512"></a>**GETID**
#### **Purpose**
To allow a string, which is the attribute name that defines the record list in the OPENDB or LOOKUPDB commands.
#### **Syntax**
**GETID(cutdata\_fields)**
#### **Comments**
Basically to use a POST string attribute that will store the Record list and Lookup list attributes. The "cutdata\_fields" is the attrname that defines the RECORD\_LIST. Since you can have up to 20 different databases open at anytime, you would need to have 20 different OPENDB and LOOKUPDB calc sections. With this function you can put a string in place of the "cutdata\_fields" attrname. As an example, you would use GETID(cutdata\_fields) in a calc section and then call the calc section that does the OPENDB or LOOKUPDB command and all you need is one calc section to do the OPENDB or LOOKUPDB commands for as many databases that are open.

(RECORD\_LIST is an integer variable)



RECORD\_LIST=**GETID(cutdata\_fields)**



OPENDB(1,LASER\_DBPATH,{FABDB},RECORD\_LIST,DATABASE\_STATUS)
## <a name="chmtopic238"></a>**GETMCS**
#### **Purpose**
To get all the different MCS offsets inserted in the current part file using ProCAM II or CAMWorks.
#### **Syntax**
**GETMCS(1,calc\_section)**

**GETMCS(2,calc\_section)**

**GETMCS(3,calc\_section)**
#### **Comments**
·        Using GETMCS (1, calc\_section) will call all Setups, including duplicate Setups. To be used in CAMWorks 2015 SP1 or newer version.

·        Using GETMCS (2, calc\_section) will do a search through the whole part file and gather all the different MCS offsets along with the Tool, Tool Comment, Rotation angles, Work Coordinate Offset values and TLP\_SETUP\_NAME. The calc\_section is any calc section you want to use for getting that information. The GETMCS will call that calc section every time it finds a different MCS offset. This can be used for machines that need to call out all the MCS offsets at the start of the program like Fanuc’s G10 command. Variables that will have information stored during this command are MCS\_X\_OFFSET, MCS\_Y\_OFFSET, MCS\_Z\_OFFSET, TOOL, TOOL\_COMMENT, ROT\_TILT\_A, ROT\_TILT\_B, work\_coord, sub\_work\_coord and fixture\_offset.

·        Using GETMCS (3, calc\_section) will call all unique Setups with different angles, thus excluding duplicate Setups. To be used in CAMWorks 2015 SP1 or newer version.


## <a name="chmtopic515"></a>**GETTOOLS**
#### **Purpose**
To retrieve from the system all tools used within the part being posted.
#### **Syntax**
**GETTOOLS(type,section)**
#### **Comments**

|*Parameter*|*Description*||
| :- | :- | :- |
|type|type of sorting method||
| |1|Sorted by turret location|
| |2|Sorted by order used in part|
|section|<p>section that will be called each time a tool is loaded.</p><p>The word SYSTEM will instruct the system to output a tool setup sheet.</p>||

#### **Example**
:C: GETTOOLS(2,CALC\_PRELOAD\_TOOL)



:C: GETTOOLS(1,SYSTEM)
## <a name="chmtopic517"></a>**GETTXT**
#### **Purpose**
To set the current FileNumber to read line by line.
#### **Syntax**
**GETTXT(FileNumber,StringVar,Status)**
#### **Comments**
This command will work only if the current file has been opened by OPENRWTXT only. This will not work with OPENTXT.

|*Parameter*|*Description*|
| :- | :- |
|FileNumber|Alternate text file ID number - range (0 to 20) – 0 reserved for Post Text file and cannot be used in OPENTXT or CLOSETXT. The FileNumber must be opened before you can read it.|
|StringVar|Stores the read string variable.|
|Status|Integer variable to return status of the command – 1 = Success, 0 = Fail or at end of line.|

## <a name="chmtopic519"></a>**GOTO**
#### **Purpose**
Branches to a specific line number in the current section.
#### **Syntax**
**GOTOnumber**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|number|any number from 0 to 9999|


#### **Type**
Calculation section only
#### **Example**
To make a looping portion of code that loops until a condition is satisfied:

:C: LOOP=1

:C1: CALL(OUTPUT\_TOOL)

:C: LOOP=(LOOP+1)

:C: IF LOOP>TOTAL\_NUMBER\_OF\_TOOLS THEN RETURN ENDIF

**:C: GOTO1**
## <a name="chmtopic521"></a>**INCOFF**
#### **Purpose**
To cancel incremental movements.
#### **Syntax**
**:C: INCOFF**
#### **Comments**
At the time INCOFF is executed, the variables XAXIS, YAXIS and ZAXIS are set to absolute distances. This command is the system default.

This command is not used often, because it does not handle incremental roundoff.
#### **Example**
:SECTION=CALC\_LINE\_MOVE\_MILL

**:C: INCOFF**

:C: X\_POS=XAXIS

:C: Y\_POS=YAXIS

:C: CALL(LINE\_MOVE\_MILL)



:SECTION=LINE\_MOVE\_MILL

:T:<N><G:01> X<#:X\_POS> Y<#:Y\_POS><F><EOL>
## <a name="chmtopic523"></a>**INCON**
#### **Purpose**
To output incremental movements.
#### **Syntax**
**:C: INCON**
#### **Comments**
At the time INCON is executed, the variables XAXIS, YAXIS and ZAXIS are set to incremental distances.

This command is not used often, because it does not handle incremental roundoff.
#### **Example**
:SECTION=CALC\_LINE\_MOVE\_MILL

**:C: INCON**

:C: X\_POS=XAXIS

:C: Y\_POS=YAXIS

:C: CALL(LINE\_MOVE\_MILL)



:SECTION=LINE\_MOVE\_MILL

:T:<N><G:01> X<#:X\_POS> Y<#:Y\_POS><F><EOL>
## <a name="chmtopic431"></a>**KILLSYSFILE()**
#### **Purpose**
To delete any file that has a path in the new variable called SYSFILENAME.
#### **Syntax**
**:C: SYSFILENAME="drive:\folder\filename"**

**:C: KILLSYSFILE()**
#### **Example**
:C: SYSFILENAME="C:\TEST\TEST.TXT"

:C: KILLSYSFILE()
## <a name="chmtopic526"></a>**LEFTSTRG**
#### **Purpose**
Allows the post to capture a string starting from the left of the string to the right by a character count (length).
#### **Syntax**
**LEFTSTRG(target\_string,string\_var,length)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|target\_string|The receiving string variable. This can only be a defined POST character variable.|
|string\_var|The string variable or hard coded. Hard coded means using the {} braces and putting characters between them.|



:C: STRG={TEST}

:C: LEFTSTRG(STRGA , STRG, 2)

The STRGA would equal "TE" 



:C: LENGTH=2

:C: STRG={TEST}

:C: LEFTSTRG(STRGA , STRG, LENGTH)

The STRGA would equal "TE"
## <a name="chmtopic528"></a>**LOOKUP**
#### **Purpose**
To find a value within an array.
#### **Syntax**
**LOOKUP(ARRAY,VALUE,INDEX)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|ARRAY|name of the array to search|
|VALUE|value to search for|
|INDEX|<p>position in the array where the value was found</p><p>(if INDEX= 1 the system failed to find the value in the array)</p>|


#### **Example**
The example below seeds an array then searches the array:

:C: ARRAY(1)=10 ARRAY(2)=11 ARRAY(3)=12

:C: VALUE=11

**:C: LOOKUP(ARRAY,VALUE,INDEX)**

:C: IF INDEX<> 1 THEN CALL(FOUND\_IN\_ARRAY) ENDIF



(The system will return a 2 in the variable INDEX)



:C: ARRAY(1)=10 ARRAY(2)=11 ARRAY(3)=12

:C: VALUE=20

**:C: LOOKUP(ARRAY,VALUE,INDEX)**

:C: IF INDEX= 1 THEN CALL(NOT\_FOUND\_IN\_ARRAY) ENDIF



(The system will return a 1 in the variable INDEX)
## <a name="chmtopic530"></a>**LOWERTXT**
#### **Purpose**
To set the output from the post's template lines as all lower case letters in the current FileNumber.
#### **Syntax**
**LOWERTXT(FileNumber)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|FileNumber|Alternate text file ID number - range (0 to 20) – 0 reserved for Post Text file and cannot be used in OPENTXT or CLOSETXT. The FileNumber must be opened before you can write to it. You can do a SETTXT(?) command and then do the LOWERTXT(?) command before you output any post template lines.|

## <a name="chmtopic532"></a>**MIDSTRG**
#### **Purpose**
Allows the post to capture a string starting from a given character count from the left of the string to the right by a character count (length).
#### **Syntax**
**MIDSTRG(target\_string,string\_var,start,length)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|target\_string|The receiving string variable. This can only be a defined POST character variable.|
|string\_var|The string variable or hard coded. Hard coded means using the {} braces and putting characters between them.|
|start|An integer or integer variable that defines the starting character to capture.|
|length|An integer or integer variable that stores the given character count from the left of the string starting character to the right.|



:C: STRG={JOHN DOE}

:C: MIDSTRG(STRGA , STRG, 6, 3)

The STRGA would equal "DOE" 



:C: START=6

:C: LENGTH=3

:C: STRG={TEST}

:C: MIDSTRG(STRGA , STRG, START, LENGTH)

The STRGA would equal "DOE"
## <a name="chmtopic534"></a>**OFFSET\_INC**
#### **Purpose**
To incrementally add an offset to all horizontal and vertical axis information.
#### **Syntax**
**OFFSET\_INC(hoff,voff)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|hoff|decimal variable containing amount of offset to add to all horizontal axis information|
|voff|decimal variable containing amount of offset to add to all vertical axis information|


#### **Example**
Add 10" offset to X and 5" offset to Y, then cancel the offset:

:C: X\_OFFSET=10 Y\_OFFSET=5

**:C: OFFSET\_INC(X\_OFFSET,Y\_OFFSET)**

:C: CALL(LINE\_MOVE)

:C: X\_OFFSET= 10 Y\_OFFSET= 5

**:C: OFFSET\_INC(X\_OFFSET,Y\_OFFSET)**
## <a name="chmtopic536"></a>**OFFSET\_XYZ**
#### **Purpose**
To incrementally add an offset to all X,Y,Z axis information. This command is used only in Mill.
#### **Syntax**
**OFFSET\_XYZ(x,y,z)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|x|decimal variable containing amount of offset to add to all X axis information|
|y|decimal variable containing amount of offset to add to all Y axis information|
|z|decimal variable containing amount of offset to add to all Z axis information|


#### **Example**
Add 10" offset to X and 5" offset to Y and 3" offset to Z, then cancel the offsets:

:C: X\_OFFSET=10 Y\_OFFSET=5 Z\_OFFSET=3

**:C: OFFSET\_XYZ(X\_OFFSET,Y\_OFFSET,Z\_OFFSET)**

:C: CALL(LINE\_MOVE)

**:C: OFFSET\_XYZ( X\_OFFSET, Y\_OFFSET, Z\_OFFSET)**
## <a name="chmtopic538"></a>**OPEN\_NEXT**
#### **Purpose**
To break a ".TXT" file and start a new tape output file. Typically, this command is used only for some older controllers that have a limit on the number of lines per file.
#### **Syntax**
**OPEN\_NEXT(char\_str(arg),str\_len(arg),int\_number(arg))**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|char\_str(agr)|file name as in A0000001.TXT. A0000001 is the File name. It will assign the ".TXT" to it.|
|str\_len(agr)|the " = Length of file name "A0000001 is (8) Characters long|
|int\_number(agr)|used for incrementing the last digits of the program name|


#### **Example**
:SECTION=CALC\_BREAK\_PROGRAM

This example will break a program at a certain line count. It will string cat until it has built a line.

The example file name = A1000001.TXT

program\_letter = A

PROGRAM\_PREFIX = program\_name = 1000

SUB\_COUNT = 1

:C: IF (LINE\_COUNT+2)>line\_number THEN GOTO2 ENDIF

:C: IF line\_number<>(LINE\_COUNT+2) THEN RETURN ENDIF

:C2: SUB\_COUNT=(SUB\_COUNT+1)



PROGRAM\_PREFIX = Character Var. String length = 5

SUB\_ID = Character Var.

ZEROS = Character Var.

program\_letter = Character setup Var. String length = 1

SUB\_COUNT = Integer Var. Max. length = 3

:C: PROGRAM\_PREFIX=program\_letter

:C: SUB\_ID=program\_number

:C: STRCAT(PROGRAM\_PREFIX,SUB\_ID)

:C: IF SUB\_COUNT>99 THEN

:C: SUB\_ID=SUB\_COUNT

:C: STRCAT(PROGRAM\_PREFIX,SUB\_ID)

:C: GOTO1 ENDIF

:C: IF SUB\_COUNT>9 THEN

:C: ZEROS={0}

:C: SUB\_ID=SUB\_COUNT

:C: STRCAT(ZEROS,SUB\_ID)

:C: STRCAT(PROGRAM\_PREFIX,ZEROS)

:C: GOTO1

:C: ENDIF

:C: ZEROS={00}

:C: SUB\_ID=SUB\_COUNT

:C: STRCAT(ZEROS,SUB\_ID)

:C: STRCAT(PROGRAM\_PREFIX,ZEROS)

:C1: S\_SUB\_COUNT\_START=SUB\_COUNT

This will call end of tape.

:C: CALL(SUB\_OUTPUT\_END)

:C: IF SUB\_COUNT=1 THEN

:C: CALL(END\_OF\_TAPE\_PUNCH)

:C: ELSE

This will call end of sub.

:C: CALL(SUB\_END)

:C: ENDIF

:C: TOTAL\_BYTE\_COUNT=(TOTAL\_BYTE\_COUNT+BYTE\_COUNT)

This will open new file.

**:C: OPEN\_NEXT(PROGRAM\_PREFIX,8,SUB\_COUNT)**

This will call start of sub.

:C: IF CANT\_OUTPUT\_PROGRAM=YES THEN RETURN ENDIF

:C: CALL(SUB\_OUTPUT\_START)
## <a name="chmtopic540"></a>**OPENRWTXT**
#### **Purpose**
Allows the post to open external files to read and write line by line while posting.
#### **Syntax**
**OPENRWTXT(FileNumber,FileName,Status)**
#### **Comments**
When reading line by line, you will use GETTXT(FileNumber, StringVar, Status) until Status = 0 then you are at the end of the file. If you want to append to an existing file, you can use the GETTXT command to get to the end of the file, then use SETTXT command to append. To open a new file, you use either OPENTXT or OPENRWTXT command. You can use this command with these commands: CLOSETXT , SETTXT, UPPERTXT, LOWERTXT and ORIGINALTXT.

|*Parameter*|*Description*|
| :- | :- |
|FileNumber|Alternate text file ID number - range (0 to 20) – 0 reserved for Post Text file and cannot be used in OPENTXT or CLOSETXT.|
|FileName|Alternate text filename – character string or character variable with full path.|
|Status|Integer variable to return status of the command – 1 = Success, 0 = Fail.|

## <a name="chmtopic542"></a>**OPENTXT**
#### **Purpose**
Allows the post to open external files and write to them while posting.
#### **Syntax**
**OPENTXT(FileNumber,FileName,Status)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|FileNumber|<p>Alternate text file ID number - range (0 to 20) – 0 reserved for Post</p><p>Text file and cannot be used in OPENTXT or CLOSETXT</p>|
|FileName|Alternate text filename – character string or character variable with full path.|
|Status|Integer variable to return status of the command – 1 = Success, 0 = Fail.|

## <a name="chmtopic544"></a>**ORIGINALTXT**
#### **Purpose**
To set the output from the post's template lines as either upper or lower case letters in the current FileNumber.
#### **Syntax**
**ORIGINALTXT(FileNumber)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|FileNumber|Alternate text file ID number - range (0 to 20) – 0 reserved for Post Text file and cannot be used in OPENTXT or CLOSETXT. The FileNumber must be opened before you can write to it. You can do a SETTXT(?) command and then do the ORIGINALTXT(?). This is the standard format if not specified to be upper or lower case.|

## <a name="chmtopic345"></a>**OUTPUT\_END\_SYNC\_CODES**
#### **Purpose**
To Find any Auto End Sync Codes from Sync Manager.
#### **Syntax**
**This logic should be in [**CALC_END_OPERATION**](#chmtopic463)**

**:C:    IF HAVE\_END\_OPER\_SYNC\_CODES=TRUE THEN**

**:C:    OUTPUT\_END\_SYNC\_CODES()**

**:C:   ENDIF**


#### **Example**
If rear start sync codes are found then it gets passed to this system section

**:SECTION=CALC\_ADD\_REAR\_SYNC\_CODE**

If front start sync codes are found then it gets passed to this system section

**:SECTION=CALC\_ADD\_FRONT\_SYNC\_CODE**  
## <a name="chmtopic120"></a>**OUTPUT\_FIRST\_FEED\_SYNC\_CODES()**


|**Purpose**|<p>To find any Auto first feed Sync Codes from *CAMWorks Sync Manager*.</p><p>To be used in CAMWorks 2019 SP0 or higher versions.  </p>|
| :- | :- |
|**Syntax**|<p>The following logic should be in CALC\_EVERY\_MOVE\_LATHE and CALC\_EVERY\_MOVE\_MILL</p><p>:C:    IF HAVE\_FIRST\_FEED\_SYNC\_CODES=TRUE THEN</p><p>:C:    OUTPUT\_FIRST\_FEED\_SYNC\_CODES()</p><p>:C:   ENDIF</p>|
|**Example**|<p>If rear start sync codes are found, then it gets passed to below system section:</p><p>:SECTION=CALC\_ADD\_REAR\_SYNC\_CODE</p><p>If front start sync codes are found, then it gets passed to the below system section:</p><p>:SECTION=CALC\_ADD\_FRONT\_SYNC\_CODE</p>|


## <a name="chmtopic344"></a>**OUTPUT\_FIRST\_MOVE\_SYNC\_CODES**
#### **Purpose**
To Find any Auto after first move Sync Codes from Sync Manager.  
#### **Syntax**
**This logic should be in [**CALC_EVERY_MOVE_MILL**](#chmtopic463) and [**CALC_EVERY_MOVE_LATHE**](#chmtopic463)**

**:C:  IF HAVE\_FIRST\_MOVE\_SYNC\_CODES=TRUE THEN**

**:C:  OUTPUT\_FIRST\_MOVE\_SYNC\_CODES()**

**:C:  ENDIF**


#### **Example**
If rear start sync codes are found then it gets passed to this system section

**:SECTION=CALC\_ADD\_REAR\_SYNC\_CODE**   

If front start sync codes are found then it gets passed to this system section  

**:SECTION=CALC\_ADD\_FRONT\_SYNC\_CODE**   
## <a name="chmtopic343"></a>**OUTPUT\_START\_SYNC\_CODES**
#### **Purpose**
To Find any Auto Start Sync Codes from Sync Manager.  
#### **Syntax**
**This logic should be in CALC\_START\_OPERATION**

**:C:    IF HAVE\_START\_OPER\_SYNC\_CODES=TRUE THEN**

**:C:    OUTPUT\_START\_SYNC\_CODES()**

**:C:   ENDIF**


#### **Example**
If rear start sync codes are found then it gets passed to this system section

**:SECTION=CALC\_ADD\_REAR\_SYNC\_CODE**

If front start sync codes are found then it gets passed to this system section

**:SECTION=CALC\_ADD\_FRONT\_SYNC\_CODE**  
## <a name="chmtopic550"></a>**REPLACE**
#### **Purpose**
To replace all occurrences of string A with string B throughout the entire tape.
#### **Syntax**
**REPLACE(stringa,stringb)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|stringa|name of a character variable|
|stringb|name of a character variable|


#### **Example**
This example will replace the comment "Total hits=xxx", which was output at the beginning of the tape, with the correct number of hits known at the end of the tape. A temporary string must be used to transfer the number of hits stored in an integer to a string.

:SECTION=CALC\_END\_OF\_TAPE

:C: STRA={Total hits=xxx}

:C: STRB={Total hits=}

:C: STRC=TOTAL\_HITS

:C: STRCAT(STRB,STRC)

**:C: REPLACE(STRA,STRB)**
## <a name="chmtopic552"></a>**RESETEOL**
#### **Purpose**
To remove (delete) the <EOL> (end of line) character from the last line of code output, so more code can be added.
#### **Syntax**
**RESETEOL**
#### **Comments**
#### **Example**
**:C: RESETEOL CALL(ADD\_END\_OF\_TAPE)**



:SECTION=ADD\_END\_OF\_TAPE

:T:<M02><EOL>
## <a name="chmtopic554"></a>**RETURN**
#### **Purpose**
To end the current section and return processing control to the system.
#### **Syntax**
**RETURN**
#### **Comments**
None
#### **Example**
**:C: IF TOOL=LAST\_TOOL THEN RETURN ENDIF**

:C: CALL(CALC\_TOOL\_CHANGE\_TIME)

:C: CALL(SUB\_TOOL\_CHANGE)
## <a name="chmtopic556"></a>**RIGHTSTRG**
#### **Purpose**
Allows the post to capture a string starting from the right of the string to the left by a character count (length).
#### **Syntax**
**RIGHTSTRG(target\_string,string\_var,length)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|target\_string|The receiving string variable. This can only be a defined POST character variable.|
|string\_var|The string variable or hard coded. Hard coded means using the {} braces and putting characters between them.|



:C: STRG={TEST}

:C: RIGHTSTRG(STRGA , STRG, 2)

The STRGA would equal "ST"



:C: LENGTH=2

:C: STRG={TEST}

:C: RIGHTSTRG(STRGA , STRG, LENGTH)

The STRGA would equal "ST"
## <a name="chmtopic558"></a>**ROUNDOFF**
#### **Purpose**
To roundoff a number. This command is no longer used since all posts round-off automatically for inch or metric.
#### **Syntax**
**ROUNDOFF(number,bucket,result,places,type)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|number|decimal number or argument containing the value to be rounded off|
|bucket|decimal variable that will receive the difference between the original number and the rounded off number (bucket is also added to the original number before any rounding occurs)|
|result|decimal variable that will receive the rounded off result|
|places|number of places to the right of the decimal|
|type|type of mode: 1 English , 2 Metric|


#### **Example**
:C: BUCKET=0

**:C: ROUNDOFF(ABS\_X\_END,BUCKET,X\_POS,G\_RIGHT\_PLACES,METRIC\_OUT)**
## <a name="chmtopic452"></a>**RUN\_PROCESS**
#### **Purpose**
To call any \*.exe file and execute it. It will also allow you to either continue posting while executing or stop posting until process is done.
#### **Syntax**
**RUN\_PROCESS**
#### **Comments**
Supported in CAMWorks 2007 SP2 and higher. Not supported in any ProCAM product.
#### **Example**
In the example below:

**PROCESS\_COMMAND** determines the file and path to execute.

**WAIT\_FOR\_PROCESS=TRUE or FALSE** sets whether posting continues as the program is executed or waits until executed program is done.

This example will execute NOTEPAD.EXE and wait until you close NOTEPAD. This process can be executed in any CALC section.



:C: PROCESS\_COMMAND={C:\WINDOWS\NOTEPAD.EXE}

:C: WAIT\_FOR\_PROCESS=TRUE

:C: RUN\_PROCESS
## <a name="chmtopic561"></a>**SETOFF**
#### **Purpose**
To set a parameter to not output code.
#### **Syntax**
**SETOFF(<name>)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|name|name of the parameter to be set off|



Parameters must be defined as MODAL parameters in order for this command to have any effect.
#### **Example**
:C: SETOFF(<F>)



The system will execute all sections responsible for outputting the parameter, however the result will not be sent to the tape.
## <a name="chmtopic563"></a>**SETON**
#### **Purpose**
To set a parameter to output code.
#### **Syntax**
**SETON(<name>)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|name|name of the parameter to be set on|



Parameters must be defined as MODAL parameters in order for this command to have any effect.
#### **Example**
:SECTION=CALC\_LINE\_MOVE\_MILL

:C: SETON(<X>)

:C: CALL(LINE\_MOVE\_MILL)

:SECTION=LINE\_MOVE\_MILL

:T: <N><G:01><X><Y><EOL>
## <a name="chmtopic565"></a>**SETTXT**
#### **Purpose**
To set the current FileNumber as the file to receive output from the posts template lines.
#### **Syntax**
**SETTXT(FileNumber)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|FileNumber|Alternate text file ID number - range (0 to 20) – 0 reserved for Post Text file and cannot be used in OPENTXT or CLOSETXT. The FileNumber must be opened before you can write to it.|

## <a name="chmtopic567"></a>**SIN**
#### **Purpose**
Returns the sine of an angle in radians.
#### **Syntax**
**SIN(ang)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|Ang|an angle in radians|



To convert degrees to radians, multiply by (180/PI).
#### **Example**
:C: Y\_POS=(ABS\_J\_CENTER+(ARC\_RADIUS\*SIN(ARC\_END\_ANGLE\*(PI/180))))
## <a name="chmtopic569"></a>**SPACES**
#### **Purpose**
To allow spaces to be output or not to be output to the tape. This command is used to override the global post definition of :SPACES=FALSE in the header in <CONTROLLER.SRC).
#### **Syntax**
**SPACES(YES)**

**SPACES(NO)**
#### **Comments**
This command can be executed prior to calling a template section; however, it is recommended you use ATTRSPACE instead.
#### **Example**
**:C: SPACES(YES)**

:C: CALL(SETUP\_SHEET)
## <a name="chmtopic571"></a>**SQRT**
#### **Purpose**
Return the square root of x.
#### **Syntax**
**SQRT(x)**
#### **Comments**
None.
#### **Example**
:C: V=(SQRT(DX\*DX+DY\*DY))
## <a name="chmtopic573"></a>**STRCAT**
#### **Purpose**
To append one string to another (i.e., concatenate strings).
#### **Syntax**
**STRCAT(string1,string2)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|string1|character variable that will get the string attached to it|
|string2|character variable that is the string to attach|


#### **Example**
:C: STRING1={ProCAD} STRING2={/CAM}

**:C: STRCAT(STRING1,STRING2)**

:C: CALL(OUTPUT\_STRING1)



:SECTION=OUTPUT\_STRING1

:T:<N><STRING1><EOL>



Result: N10 ProCAD/CAM
## <a name="chmtopic575"></a>**STRGLEN**
#### **Purpose**
Allows the post to get the string length of any string.
#### **Syntax**
**STRGLEN(string\_var)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|string\_var|Is the string variable or hard coded. Hard coded means using the {} braces and putting characters between them.|



:C: STRG={TEST}

:C: STRG\_LENGTH=STRGLEN(STRG)

The STRG\_LENGTH would equal 4 
## <a name="chmtopic577"></a>**STRGLOWER**
#### **Purpose**
Allows the post to change the given string to have all lower case characters.
#### **Syntax**
**STRGLOWER(target\_string,string\_var)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|target\_string|The receiving string variable. This can only be a defined POST character variable.|
|string\_var|The string variable or hard coded. Hard coded means using the {} braces and putting characters between them.|



:C: STRG={TEST}

:C: STRGLOWER(STRGA , STRG)

The STRGA would equal "test"
## <a name="chmtopic579"></a>**STRGUPPER**
#### **Purpose**
Allows the post to change the given string to have all upper case characters.
#### **Syntax**
**STRGUPPER(target\_string,string\_var)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|target\_string|The receiving string variable. This can only be a defined POST character variable.|
|string\_var|The string variable or hard coded. Hard coded means using the {} braces and putting characters between them.|



:C: STRG={test}

:C: STRGUPPER(STRGA , STRG)

The STRGA would equal "TEST" 
## <a name="chmtopic477"></a>**SYS\_CANNED**
#### **Purpose**
To break an entity not supported by the post into a series of entities that are supported by the post. Typically, this command is used the explode line, grid, arc and bolt hole patterns into single points.
#### **Syntax**
**SYS\_CANNED(type,section)**
#### **Comments**

|*Parameter*|*Description*||
| :- | :- | :- |
|type|Indicates the type of breakup and is a constant||
| |<p>[1](#chmbookmark59)</p><p>[2](#chmbookmark60)</p><p> </p><p>3</p><p> </p><p>[4](#chmbookmark61)</p><p> </p><p> </p><p> </p><p>[5](#chmbookmark62)</p><p> </p><p> </p><p> </p><p>[6](#chmbookmark63)</p><p> </p><p>[7](#chmbookmark64)</p>|<p>Single points</p><p>Lines, arcs and bolt holes</p><p>(use only on grids and big hole patterns)</p><p>Breaks a thread cycle into diameters</p><p>(use only on threading cycles)</p><p>Breaks a Live C post Mill OD or Mill Face line move into increments defined by post variable MILL\_FACE\_INC as a chord length(use only in ProCAM 2D with post set to :SYSTEM=LATHE/MILL and on Mill line moves only. It will also break the angle rotation of the C axis in the line move).</p><p>Breaks an arc that is not on the top plane by ARC\_DEVIATION set in the arc calc section (use only in 4 and 5 axis posts that have arcs that are not on the top plane. This command can only be used in ProCAM II 2004 and CAMWorks 2005 or newer versions).</p><p>Breaks a canned peck drilling cycle into operation defined increments (use only in CAMWorks 2005 or later versions for mill pecking canned cycles).</p><p>Breaks all Turn line and arc moves for simultaneous X,Z and B axis moves. (Use only in CAMWorks 2019 or later versions.)</p>|
|section|<p>section that will handle the exploded entity</p><p>The word SYSTEM instructs the system to call the appropriate sections.</p>||
-----
#### **Examples**
<a name="chmbookmark59"></a>**SYS\_CANNED(1,?????)**

:SECTION=CALC\_ARC\_PATTERN\_PUNCH

:C: SYS\_CANNED(1,CALC\_SINGLE\_HIT\_PUNCH)

:SECTION=CALC\_GRID\_PATTERN\_PUNCH

:C: SYS\_CANNED(2,SYSTEM)

:SECTION=CALC\_MACHINE\_THREAD\_LATHE

:C: SYS\_CANNED(3,CALC\_MULTIPLE\_THREAD\_LATHE)

Warning: A SYS\_CANNED command cannot be executed while inside of another SYS\_CANNED cycle. In the example below, grids are broken into line patterns, but since the post does not support line patterns, another SYS\_CANNED command is executed. This is an error.

-----
<a name="chmbookmark60"></a>**SYS\_CANNED(2,?????)**

:SECTION=CALC\_GRID\_PATTERN\_PUNCH

:C: SYS\_CANNED(2,SYSTEM)

:SECTION=CALC\_LINE\_PATTERN\_PUNCH



:C: SYS\_CANNED(1,CALC\_SINGLE\_HIT\_PUNCH)



The post should have been written as follows:

:SECTION=CALC\_GRID\_PATTERN\_PUNCH

:C: SYS\_CANNED(1,CALC\_SINGLE\_HIT\_PUNCH)

-----
<a name="chmbookmark61"></a>**SYS\_CANNED(4,?????)**

:SECTION=CALC\_LINE\_MOVE\_OD\_FREE

:C: MILL\_FACE\_INC=chord\_length

:C: SYS\_CANNED(4,CALC\_BREAK\_LINE\_OD)

-----
<a name="chmbookmark62"></a>**SYS\_CANNED(5,?????)**

:SECTION=CALC\_ARC\_MOVE\_MILL\_YZ

:C: ARC\_DEVIATION=max\_arc\_dev

:C: SYS\_CANNED(5,CALC\_BREAK\_ARC)

-----
<a name="chmbookmark63"></a>**SYS\_CANNED(6,?????)**

:SECTION=CALC\_HIGH\_SPEED\_PECKING\_CYCLE

:C: SYS\_CANNED(6,CALC\_HIGH\_SPEED\_PECKING)

-----
<a name="chmbookmark64"></a>**SYS\_CANNED(7,?????)**

:SECTION=CALC\_ARC\_MOVE\_LATHE

:C: MAX\_B\_AXIS\_INCREMENT=Post Variable

:C: SYS\_CANNED(7,CALC\_BREAK\_ARC\_TO\_ARC\_LATHE)

\*:C: SYS\_CANNED(7, CALC\_BREAK\_RADIAL\_ARC\_TO\_ARC\_LATHE)

:C: RETURN



:SECTION=CALC\_BREAK\_ARC\_TO\_ARC\_LATHE

:C: X\_POS=ABS\_X\_END

:C: Z\_POS=ABS\_Z\_END

:C: CALL(ARC\_MOVE\_LATHE)

\*-----------------------------------

:SECTION=CALC\_BREAK\_RADIAL\_ARC\_TO\_ARC\_LATHE

:C: X\_POS=ABS\_X\_END

:C: Z\_POS=ABS\_Z\_END

:C: CALL(RADIUS\_MOVE\_LATHE)



**Lines can also be broken as follows:**

**:**SECTION=CALC\_LINE\_MOVE\_LATHE

:C: MAX\_B\_AXIS\_INCREMENT=1.

:C: SYS\_CANNED(7,CALC\_BREAK\_LINE\_LATHE)

:C: RETURN



:SECTION= CALC\_BREAK\_LINE\_LATHE

:C: X\_POS=ABS\_X\_END

:C: Z\_POS=ABS\_Z\_END

:C: CALL(LINE\_MOVE\_LATHE)


## <a name="chmtopic582"></a>**TAN**
#### **Purpose**
Returns the tangent of an angle in radians.
#### **Syntax**
**TAN(ang)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|ang|an angle in radians|



To convert degrees to radians, multiply by (PI/180).
#### **Example**
:C: HEIGHT=(RADIUS/TAN((TOOL\_ANGLE\*(PI/180))/2))
## <a name="chmtopic7"></a>**TRANSFORM**
### **Purpose**
To allow the post to output world coordinates when it is outputting in machine coordinates.

There are specific machines that when implementing rotary axis preposition moves that the first move needs to be in world coordinates then switch back to machine coordinates for all other moves until a new rotary position is called.

This command is supported in CAMWorks 2007 SP2 and higher. It is not supported in any ProCAM product. Some of the parameters associated with the TRANSFORM command are supported only from CAMWorks 2020 SP3 version onwards. Such parameters are listed separately at the bottom of this webpage.
### **Syntax**
Associated commands and variables:

These variables need to be set to the current** machine values as shown.

**:C: TRANS\_START\_X=ABS\_X\_END**

**:C: TRANS\_START\_Y=ABS\_Y\_END**

**:C: TRANS\_START\_Z=ABS\_Z\_END**



These variables need to be assigned a vector number depending on the direction of the rotary motion. Below shows us that the 4th axis rotates about X and the 5th** axis about Y. The vector numbers can have a range from -1 to +1. If you are using this in conjunction with 5axis multiaxis operations and are using a \*.KIN file, then you can use the second example below which will use the \*.KIN file to get the vector numbers.

:C: TRANS\_ROTAXISDIR\_4X=1.0

:C: TRANS\_ROTAXISDIR\_4Y=0.0

:C: TRANS\_ROTAXISDIR\_4Z=0.0

:C: TRANS\_ROTAXISDIR\_5X=0.0

:C: TRANS\_ROTAXISDIR\_5Y=1.0

:C: TRANS\_ROTAXISDIR\_5Z=0.0


#### **2nd Example:**
:C: IF KIN\_HAVE\_KINEMATICS=TRUE THEN

:C: TRANS\_ROTAXISDIR\_4X=KIN\_ROTAXISDIR\_4X

:C: TRANS\_ROTAXISDIR\_4Y=KIN\_ROTAXISDIR\_4Y

:C: TRANS\_ROTAXISDIR\_4Z=KIN\_ROTAXISDIR\_4Z

:C: TRANS\_ROTAXISDIR\_5X=KIN\_ROTAXISDIR\_5X

:C: TRANS\_ROTAXISDIR\_5Y=KIN\_ROTAXISDIR\_5Y

:C: TRANS\_ROTAXISDIR\_5Z=KIN\_ROTAXISDIR\_5Z

:C: ENDIF



These variables are setting the current rotated angle.

:C: TRANS\_ROTANGLE\_A=ROT\_TILT\_A

:C: TRANS\_ROTANGLE\_B=ROT\_TILT\_B



This command will perform** the transform** calculations.

:C: TRANSFORM



The lines below show how you can set post variables equal to the transformed numbers once the transform** is done.

:C: X\_POS=TRANS\_END\_X

:C: Y\_POS=TRANS\_END\_Y

:C: Z\_POS=TRANS\_END\_Z


#### **Examples**
This is an example of the order and how you could implement this command.

:C: TRANS\_START\_X=ABS\_X\_END

:C: TRANS\_START\_Y=ABS\_Y\_END

:C: TRANS\_START\_Z=ABS\_Z\_END

:C: TRANS\_ROTAXISDIR\_4X=1.0

:C: TRANS\_ROTAXISDIR\_4Y=0.0

:C: TRANS\_ROTAXISDIR\_4Z=0.0

:C: TRANS\_ROTAXISDIR\_5X=0.0

:C: TRANS\_ROTAXISDIR\_5Y=1.0

:C: TRANS\_ROTAXISDIR\_5Z=0.0

:C: TRANS\_ROTANGLE\_A=ROT\_TILT\_A

:C: TRANS\_ROTANGLE\_B=ROT\_TILT\_B

:C:** TRANSFORM

:C: X\_POS=TRANS\_END\_X

:C: Y\_POS=TRANS\_END\_Y

:C: Z\_POS=TRANS\_END\_Z

:C: CALL(TRANSLATED\_OUTPUT)



This is another example of the order and how you could implement this command.

:C: TRANS\_START\_X=ABS\_X\_END

:C: TRANS\_START\_Y=ABS\_Y\_END

:C: TRANS\_START\_Z=ABS\_Z\_END

:C: IF KIN\_HAVE\_KINEMATICS=TRUE THEN

:C: TRANS\_ROTAXISDIR\_4X=KIN\_ROTAXISDIR\_4X

:C: TRANS\_ROTAXISDIR\_4Y=KIN\_ROTAXISDIR\_4Y

:C: TRANS\_ROTAXISDIR\_4Z=KIN\_ROTAXISDIR\_4Z

:C: TRANS\_ROTAXISDIR\_5X=KIN\_ROTAXISDIR\_5X

:C: TRANS\_ROTAXISDIR\_5Y=KIN\_ROTAXISDIR\_5Y

:C: TRANS\_ROTAXISDIR\_5Z=KIN\_ROTAXISDIR\_5Z

:C: ENDIF

:C: TRANS\_ROTANGLE\_A=ROT\_TILT\_A

:C: TRANS\_ROTANGLE\_B=ROT\_TILT\_B

:C: TRANSFORM

:C: X\_POS=TRANS\_END\_X

:C: Y\_POS=TRANS\_END\_Y

:C: Z\_POS=TRANS\_END\_Z

:C: CALL(TRANSLATED\_OUTPUT)
**\

### <a name="chmbookmark2"></a>**New Parameters from Kinematics File (Available from CAMWorks2020 SP3 Version Onwards)**
**KIN\_ROTAXISBASE\_4X**

**KIN\_ROTAXISBASE\_4Y**

**KIN\_ROTAXISBASE\_4Z**
**\


**KIN\_ROTAXISBASE\_5X**

**KIN\_ROTAXISBASE\_5Y**

**KIN\_ROTAXISBASE\_5Z**
**\

### <a name="chmbookmark3"></a>**New Parameters supported by TRANSFORM (Available from CAMWorks2020 SP3 Version Onwards)**
**TRANS\_ROTAXISBASE\_PNT\_4X**

**TRANS\_ROTAXISBASE\_PNT\_4Y**

**TRANS\_ROTAXISBASE\_PNT\_4Z**
**\


**TRANS\_ROTAXISBASE\_PNT\_5X**

**TRANS\_ROTAXISBASE\_PNT\_5Y**

**TRANS\_ROTAXISBASE\_PNT\_5Z**
**\

#### **Example:**
:C: TRANS\_START\_X=0

:C: TRANS\_START\_Y=0

:C: TRANS\_START\_Z=0

:C: IF KIN\_HAVE\_KINEMATICS=TRUE THEN

:C:  TRANS\_ROTAXISDIR\_4X=KIN\_ROTAXISDIR\_4X

:C:  TRANS\_ROTAXISDIR\_4Y=KIN\_ROTAXISDIR\_4Y

:C:  TRANS\_ROTAXISDIR\_4Z=KIN\_ROTAXISDIR\_4Z

:C:  TRANS\_ROTAXISDIR\_5X=KIN\_ROTAXISDIR\_5X

:C:  TRANS\_ROTAXISDIR\_5Y=KIN\_ROTAXISDIR\_5Y

:C:  TRANS\_ROTAXISDIR\_5Z=KIN\_ROTAXISDIR\_5Z

\*

**:C:  TRANS\_ROTAXISBASE\_PNT\_4X=KIN\_ROTAXISBASE\_4X**

**:C:  TRANS\_ROTAXISBASE\_PNT\_4Y=KIN\_ROTAXISBASE\_4Y**

**:C:  TRANS\_ROTAXISBASE\_PNT\_4Z=KIN\_ROTAXISBASE\_4Z**

**:C:  TRANS\_ROTAXISBASE\_PNT\_5X=KIN\_ROTAXISBASE\_5X**

**:C:  TRANS\_ROTAXISBASE\_PNT\_5Y=KIN\_ROTAXISBASE\_5Y**

**:C:  TRANS\_ROTAXISBASE\_PNT\_5Z=KIN\_ROTAXISBASE\_5Z**

:C: TRANS\_ROTANGLE\_A=ROT\_TILT\_A

:C: TRANS\_ROTANGLE\_B=ROT\_TILT\_B

:C: TRANSFORM

:C: ENDIF


### <a name="chmbookmark4"></a>**New KIN File Parameters (Available from CAMWorks2020 SP3 Version Onwards)**
**0 \* 5 Axis Type 0-TABLE\_TABLE,1-HEAD\_HEAD,2-HEAD\_TABLE, 3-TABLE\_TABLE\_TOOLCOMP, 4-HEAD\_HEAD\_NOTOOLCOMP, 5-HEAD\_TABLE\_NOTOOLCOMP**

**1 \* XYZ Coordinate Type 0-Part , 1-Machine**

**0.000000 \* Spindle Direction X**

**0.000000 \* Spindle Direction Y**

**1.000000 \* Spindle Direction Z**

**0.000000 \* 1st Rotary Axis Direction X**

**0.000000 \* 1st Rotary Axis Direction Y**

**-1.000000 \* 1st Rotary Axis Direction Z**

**0.000000 \* 2nd Rotary Axis Direction X**

**-1.000000 \* 2nd Rotary Axis Direction Y**

**0.000000 \* 2nd Rotary Axis Direction Z**

**-60.000000 \* Rotation 5th Axis Base Point X  (Millimeters Only)**

**0.000000 \* Rotation 5th Axis Base Point Y  (Millimeters Only)**

**-154.2491\* Rotation 5th Axis Base Point Z  (Millimeters Only)**

**-100000.000000 \* 1st Rotation Axis Limit Min**

**100000.000000 \* 1st Rotation Axis Limit Max**

**-180.000000 \* 2nd Rotation Axis Limit Min**

**180.000000 \* 2nd Rotation Axis Limit Max**

**Mill\_Tutorial \* Default Machine Simulation**

**0.000000 \* Rotation 4th Axis Base Point X  (Millimeters Only)**

**0.000000 \* Rotation 4th Axis Base Point Y  (Millimeters Only)**

**0.000000 \* Rotation 4th Axis Base Point Z  (Millimeters Only)**
## <a name="chmtopic585"></a>**UPPERTXT**
#### **Purpose**
To set the output from the post's template lines as all upper case letters in the current FileNumber.
#### **Syntax**
**UPPERTXT(FileNumber)**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|FileNumber|Alternate text file ID number - range (0 to 20) – 0 reserved for Post Text file and cannot be used in OPENTXT or CLOSETXT. The FileNumber must be opened before you can write to it. You can do a SETTXT(?) command and then do the UPPERTXT(?) command before you output any post template lines.|

## <a name="chmtopic158"></a>**QUERY\_CONFIGURATION\_NAME**
#### **Purpose**
If the return value of QUERY\_RESULT is TRUE, the system will pass a string value to post system variable called QUERY\_CHAR\_VAL.

To be used in CAMWorks 2017 SP0 or higher versions.


#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_CONFIGURATION\_NAME**


#### **Comments**
`     `**Associated commands and variables:**

`     `The example code below shows the other variables used with this command.



:C: QUERY\_ITEM\_ID=QUERY\_CONFIGURATION\_NAME

:C: QUERY\_SYSTEM()

:C: IF QUERY\_RESULT=1 THEN

:C:     Char post variable=QUERY\_CHAR\_VAL

:C: ENDIF


#### **Other Associated commands and variables:**
[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic587"></a>**QUERY\_DEC\_MIN\_PROTRUSION**
#### **Purpose**
This command will query the Minimum tool protrusion in 3axis operation.     

Available in Mill, Turn and Mill-Turn.

Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.
#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_DEC\_MIN\_PROTRUSION**
#### **Comments**
**Associated commands and variables:**

The example code below shows the other variables used with this command. If the Query result was "1" then the value will be in  **QUERY\_DEC\_VAL**.  



*:C: QUERY\_ITEM\_ID=QUERY\_DEC\_MIN\_PROTRUSION*

*:C: QUERY\_SYSTEM()*

*:C: IF QUERY\_RESULT=1 THEN*

*\*   Post Variable = QUERY\_DEC\_VAL*

*:C: ENDIF*


#### **Other Associated commands and variables:**
[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic588"></a>**QUERY\_DEC\_OPER\_TIME**
#### **Purpose**
This command will query the estimated machine time per operation.    

Available in Mill, Turn and Mill-Turn.

Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.
#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_DEC\_OPER\_TIME**
#### **Comments**
**Associated commands and variables:**

The example code below shows the other variables used with this command. If the Query result was "1" then the value will be in  **QUERY\_DEC\_VAL**.



*:C: QUERY\_ITEM\_ID=QUERY\_DEC\_OPER\_TIME*

*:C: QUERY\_SYSTEM()*

*:C: IF QUERY\_RESULT=1 THEN*

*\*   Post Variable = QUERY\_DEC\_VAL*

*:C: ENDIF*


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic589"></a>**QUERY\_EXPORT\_ERROR**
#### **Purpose**
This command will query an error for finding sync codes if post is not setup to handle that. The error will be sent to the CAMWorks error message box.        

Available in Mill, Turn and Mill-Turn.

Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.
#### **Syntax**
**QUERY\_ITEM\_ID= QUERY\_EXPORT\_ERROR**  
#### **Comments**
**Associated commands and variables:**

The example code below shows the other variables used with this command. This logic should be in:

**:SECTION=CALC\_ADD\_REAR\_SYNC\_CODE           and :SECTION=CALC\_ADD\_FRONT\_SYNC\_CODE**   
**\


*:C: QUERY\_ITEM\_ID= QUERY\_EXPORT\_ERROR*

*:C: QUERY\_ERROR= HAVE\_SYNC\_CODE\_ERROR*

*:C: QUERY\_SYSTEM()*


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic131"></a>**QUERY\_FEATURE\_ENTRY\_TYPE**
#### **Purpose**
If the return value of QUERY\_RESULT is TRUE, then the system will pass the *feature entry type* info in a Rough Mill or Contour Mill operation in QUERY\_INT\_VAL. (returns FALSE if the operation is not a Rough Mill or Contour Mill operation). To be used in CAMWorks 2018 SP0 or higher versions.


#### **Syntax**
QUERY\_ITEM\_ID=QUERY\_FEATURE\_ENTRY\_TYPE****              
#### **Comments**
Associated constants:

·        ENTRY\_TYPE\_NONE

·        ENTRY\_TYPE\_PLUNGE

·        ENTRY\_TYPE\_DRILL

·        ENTRY\_TYPE\_RAMP

·        ENTRY\_TYPE\_HOLE

·        ENTRY\_TYPE\_SPIRAL

·        ENTRY\_TYPE\_RAMP\_ON\_LEADIN

The sample code below illustrates how other variables are used with this command. 



*:C: IF QUERY\_ITEM\_ID = QUERY\_FEATURE\_ENTRY\_TYPE*

*:C: QUERY\_SYSTEM()*

*:C: IF SECTION EXIST (START\_OPERATION) THEN CALL (START\_OPERATION)ENDIF*

*\**

*:SECTION=START\_OPERATION*

*:T: Entry type=<%:QUERY\_INT\_VAL><EOL>*




#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_TOOL_COOLANT_TYPE](#chmtopic132)

[QUERY_TOOL_DIAMETER_REG](#chmtopic133)

[QUERY_TOOL_LENGTH_REG](#chmtopic134)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic233"></a>**QUERY\_FEATURE\_STRATEGY**
#### **Purpose**
If the return value of QUERY\_RESULT is TRUE, the system will pass the feature strategy in the post variable called QUERY\_CHAR\_VAL. To be used in CAMWorks 2015 SP1 or newer version.
#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_FEATURE\_STRATEGY**
#### **Comments**
Associated commands and variables:

The example code below shows the other variables used with this command.



*:C: QUERY\_ITEM\_ID=QUERY\_FEATURE\_STRATEGY*

*:C: QUERY\_SYSTEM()*

*:C: IF QUERY\_RESULT=TRUE THEN*

*\*\*  If you need to output this in the code then you will need to create a post attribute as a character and use QUERY\_CHAR\_VAL as the :VAR=*

*:C: CALL (section name)*

*\*\*  You can also save this to a post variable and use it for checking for a different feature strategy*

*:C: ENDIF*
#### ** 
#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
#### ** 
## <a name="chmtopic590"></a>**QUERY\_GCODE\_AXIS\_NAMES\_MILL**
#### **Purpose**
This command will define which axis is controlled by work offsets for milling in the posted output. This is used in conjunction with CAMWorks Virtual Machine.         

Available in Mill, Turn and Mill-Turn.

Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.
#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_GCODE\_AXIS\_NAMES\_MILL**            
#### **Comments**
Note: QUERY\_GCODE\_AXIS\_NAMES\_T1A can be used as a default in milling also.

**Associated commands and variables:**  

The example code below shows the other variables used with this command. This logic should be in:  **SECTION=CALC\_QUERY\_POST**.  



*:C: IF QUERY\_ITEM\_ID = QUERY\_GCODE\_AXIS\_NAMES\_MILL THEN*

*:C: CALL(QUERY\_AXIS\_NAMES\_MILL)- This section is in the General library files.*

*:C: RETURN*

*:C: ENDIF*

*\**

*:SECTION=QUERY\_AXIS\_NAMES\_MILL*

*:T:X,Y,Z<EOL>*    


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic591"></a>**QUERY\_GCODE\_AXIS\_NAMES\_T1A**
#### **Purpose**
This command will define which axis is controlled by work offsets for the 1st turret above centerline in the posted output. This is used in conjunction with CAMWorks Virtual Machine.         

Available in Mill, Turn and Mill-Turn.

Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.
#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_GCODE\_AXIS\_NAMES\_T1A**        
#### **Comments**
**Associated commands and variables:**

The example code below shows the other variables used with this command. This logic should be in:  **SECTION=CALC\_QUERY\_POST**.



*:C: IF QUERY\_ITEM\_ID = QUERY\_GCODE\_AXIS\_NAMES\_T1A THEN*

*:C: CALL(QUERY\_AXIS\_NAMES\_T1A)- This section is in the General library files.*

*:C: RETURN*

*:C: ENDIF*

*\**

*:SECTION=QUERY\_AXIS\_NAMES\_T1A*

*:T:X,Y,Z<EOL>*  


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic593"></a>**QUERY\_GCODE\_AXIS\_NAMES\_T1B**
#### **Purpose**
This command will define which axis is controlled by work offsets for the 1st turret below centerline in the posted output. This is used in conjunction with CAMWorks Virtual Machine.         

Available in Mill, Turn and Mill-Turn.

Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.
#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_GCODE\_AXIS\_NAMES\_T1B**          
#### **Comments**
**Associated commands and variables:**

The example code below shows the other variables used with this command. This logic should be in:  **SECTION=CALC\_QUERY\_POST**.  



*:C: IF QUERY\_ITEM\_ID = QUERY\_GCODE\_AXIS\_NAMES\_T1B THEN*

*:C: CALL(QUERY\_AXIS\_NAMES\_T1B)- This section is in the General library files.*

*:C: RETURN*

*:C: ENDIF*

*\**

*:SECTION=QUERY\_AXIS\_NAMES\_T1B*

*:T:X,Y,Z<EOL>*   


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic592"></a>**QUERY\_GCODE\_AXIS\_NAMES\_T2A**
#### **Purpose**
This command will define which axis is controlled by work offsets for the 2nd turret above centerline in the posted output. This is used in conjunction with CAMWorks Virtual Machine.         

Available in Mill, Turn and Mill-Turn.

Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.
#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_GCODE\_AXIS\_NAMES\_T2A**         
#### **Comments**
**Associated commands and variables:**

The example code below shows the other variables used with this command. This logic should be in:  **SECTION=CALC\_QUERY\_POST**.  



*:C: IF QUERY\_ITEM\_ID = QUERY\_GCODE\_AXIS\_NAMES\_T2A THEN*

*:C: CALL(QUERY\_AXIS\_NAMES\_T2A)- This section is in the General library files.*

*:C: RETURN*

*:C: ENDIF*

*\**

*:SECTION=QUERY\_AXIS\_NAMES\_T2A*

*:T:X,Y,Z<EOL>*  


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic594"></a>**QUERY\_GCODE\_AXIS\_NAMES\_T2B**
#### **Purpose**
This command will define which axis is controlled by work offsets for the 2nd turret below centerline in the posted output. This is used in conjunction with CAMWorks Virtual Machine.         

Available in Mill, Turn and Mill-Turn.

Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.
#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_GCODE\_AXIS\_NAMES\_T2B**           
#### **Comments**
**Associated commands and variables:**

The example code below shows the other variables used with this command. This logic should be in:  **SECTION=CALC\_QUERY\_POST**.



*:C: IF QUERY\_ITEM\_ID = QUERY\_GCODE\_AXIS\_NAMES\_T2B THEN*

*:C: CALL(QUERY\_AXIS\_NAMES\_T2B)- This section is in the General library files.*

*:C: RETURN*

*:C: ENDIF*

*\**

*:SECTION=QUERY\_AXIS\_NAMES\_T2B*

*:T:X,Y,Z<EOL>*   


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic595"></a>**QUERY\_GCODE\_DEFAULT\_WCS**
#### **Purpose**
This command will query the number of default work coordinates in the posted output. This is used in conjunction with CAMWorks Virtual Machine.         

Available in Mill, Turn and Mill-Turn.

Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.
#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_GCODE\_DEFAULT\_WCS**    
#### **Comments**
**Associated commands and variables:**

The example code below shows the other variables used with this command. This logic should be in:  **SECTION=CALC\_QUERY\_POST**.  



*:C: IF QUERY\_ITEM\_ID = QUERY\_GCODE\_DEFAULT\_WCS THEN*

*:C:    IF SECTIONEXIST(QUERY\_WCS) THEN*

*:C:    CALL(QUERY\_WCS)  -  Have this section in your post if you need to do something special.*

*:C:    RETURN*

*:C:    ELSE*

*:C:    CALL(AUTO\_QUERY\_WCS) - This section will be in the General library files.*

*:C:    RETURN*

*:C:    ENDIF*

*:C: ENDIF*

*\**

*:SECTION=AUTO\_QUERY\_WCS*

*:T: IF MCS\_TYPE=2 OR COORD\_TYPE=0 THEN <G!:work\_coord><EOL>ENDIF*

*:T: IF MCS\_TYPE=3 AND work\_coord=54 THEN <G!:work\_coord><POINT\_ONE><EOL>ENDIF*

*:T: IF MCS\_TYPE=3 AND work\_coord>54 THEN <G!:work\_coord><EOL>ENDIF*   


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic596"></a>**QUERY\_GCODE\_FILE\_NAME\_T1A**
#### **Purpose**
This command will define what is the file name for 1st turret above centerline. This is used in conjunction with CAMWorks Virtual Machine.         

This command is not needed if using the file path and name as in the posting dialog box.

Available in Mill, Turn and Mill-Turn.

Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.
#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_GCODE\_FILE\_NAME\_T1A**              
#### **Comments**
**Associated commands and variables:**  

The example code below shows the other variables used with this command. This logic should be in:  **SECTION=CALC\_QUERY\_POST**.  



*:C: IF QUERY\_ITEM\_ID = QUERY\_GCODE\_FILE\_NAME\_T1A THEN*

*:C: CALL(QUERY\_FILE\_NAME\_T1A )*

*:C: RETURN*

*:C: ENDIF*

*\**

*:SECTION=QUERY\_FILE\_NAME\_T1A*

*:T: file name<EOL>*     


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic598"></a>**QUERY\_GCODE\_FILE\_NAME\_T1B**
#### **Purpose**
This command will define what is the file name for 1st turret below centerline. This is used in conjunction with CAMWorks Virtual Machine.         

This command is not needed if using the file path and name as in the posting dialog box.

Available in Mill, Turn and Mill-Turn.

Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.
#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_GCODE\_FILE\_NAME\_T1B**              
#### **Comments**
**Associated commands and variables:**  

The example code below shows the other variables used with this command. This logic should be in:  **SECTION=CALC\_QUERY\_POST**.  



*:C: IF QUERY\_ITEM\_ID = QUERY\_GCODE\_FILE\_NAME\_T1B THEN*

*:C: CALL(QUERY\_FILE\_NAME\_T1B )*

*:C: RETURN*

*:C: ENDIF*

*\**

*:SECTION=QUERY\_FILE\_NAME\_T1B*

*:T: file name<EOL>*     


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic597"></a>**QUERY\_GCODE\_FILE\_NAME\_T2A**
#### **Purpose**
This command will define what is the file name for 2nd turret above centerline. This is used in conjunction with CAMWorks Virtual Machine.         

This command is not needed if using the file path and name as in the posting dialog box.

Available in Mill, Turn and Mill-Turn.

Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.
#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_GCODE\_FILE\_NAME\_T2A**              
#### **Comments**
**Associated commands and variables:**  

The example code below shows the other variables used with this command. This logic should be in:  **SECTION=CALC\_QUERY\_POST**.



*:C: IF QUERY\_ITEM\_ID = QUERY\_GCODE\_FILE\_NAME\_T2A THEN*

*:C: CALL(QUERY\_FILE\_NAME\_T2A )*

*:C: RETURN*

*:C: ENDIF*

*\**

*:SECTION=QUERY\_FILE\_NAME\_T2A*

*:T: file name<EOL>*     


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic625"></a>**QUERY\_GCODE\_FILE\_NAME\_T2B**
#### **Purpose**
This command will define what is the file name for 2nd turret below centerline. This is used in conjunction with CAMWorks Virtual Machine.         

This command is not needed if using the file path and name as in the posting dialog box.

Available in Mill, Turn and Mill-Turn.

Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.
#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_GCODE\_FILE\_NAME\_T2B**              
#### **Comments**
**Associated commands and variables:**  

The example code below shows the other variables used with this command. This logic should be in:  **SECTION=CALC\_QUERY\_POST**.  



*:C: IF QUERY\_ITEM\_ID = QUERY\_GCODE\_FILE\_NAME\_T2B THEN*

*:C: CALL(QUERY\_FILE\_NAME\_T2B )*

*:C: RETURN*

*:C: ENDIF*

*\**

*:SECTION=QUERY\_FILE\_NAME\_T2B*

*:T: file name<EOL>*  


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic599"></a>**QUERY\_GCODE\_POSTED\_FILE\_NAME**
#### **Purpose**
This command will define what is the file name for the milling posted output. This is used in conjunction with CAMWorks Virtual Machine.         

This command is not needed if using the file path and name as in the posting dialog box.

Available in Mill, Turn and Mill-Turn.

Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.
#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_GCODE\_POSTED\_FILE\_NAME**             
#### **Comments**
Note: QUERY\_GCODE\_FILE\_NAME\_T1A can be used as a default in milling also.

**Associated commands and variables:**  

The example code below shows the other variables used with this command. This logic should be in:  **SECTION=CALC\_QUERY\_POST**.  



*:C: IF QUERY\_ITEM\_ID = QUERY\_GCODE\_POSTED\_FILE\_NAME THEN*

*:C: CALL(QUERY\_POSTED\_FILE\_NAME )*

*:C: RETURN*

*:C: ENDIF*

*\**

*:SECTION=QUERY\_POSTED\_FILE\_NAME*

*:T:file name<EOL>*  


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)    

[QUERY_INT_OFFSET_REG](#chmtopic606)  

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic600"></a>**QUERY\_GCODE\_WCS**
#### **Purpose**
This command will query the number of  work coordinates in the posted output. This is used in conjunction with CAMWorks Virtual Machine.         

Available in Mill, Turn and Mill-Turn.

Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.
#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_GCODE\_WCS**     
#### **Comments**
**Associated commands and variables:**

The example code below shows the other variables used with this command. This logic should be in:  **SECTION=CALC\_QUERY\_POST**.



*:C: IF QUERY\_ITEM\_ID = QUERY\_GCODE\_WCS THEN*

*:C:    IF SECTIONEXIST(QUERY\_WCS) THEN*

*:C:    CALL(QUERY\_WCS)  -  Have this section in your post if you need to do something special.*

*:C:    RETURN*

*:C:    ELSE*

*:C:    CALL(AUTO\_QUERY\_WCS) - This section will be in the General library files.*

*:C:    RETURN*

*:C:    ENDIF*

*:C: ENDIF*

*\**

*:SECTION=AUTO\_QUERY\_WCS*

*:T: IF MCS\_TYPE=2 OR COORD\_TYPE=0 THEN <G!:work\_coord><EOL>ENDIF*

*:T: IF MCS\_TYPE=3 AND work\_coord=54 THEN <G!:work\_coord><POINT\_ONE><EOL>ENDIF*

*:T: IF MCS\_TYPE=3 AND work\_coord>54 THEN <G!:work\_coord><EOL>ENDIF*


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic65"></a>**QUERY\_HOLDER\_DESCRIPTION\_COMMENT**
#### **Purpose**
If the return value of QUERY\_RESULT is TRUE, then the system will pass a string value to post system variable named QUERY\_CHAR\_VAL.

To be used in *CAMWorks 2020 SP0* or higher versions.


#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_HOLDER\_DESCRIPTION\_COMMENT**
#### **Comments**
**Associated commands and variables:**

`             `The example code below shows the other variables used with this command. 



*:C: QUERY\_ITEM\_ID =QUERY\_HOLDER\_DESCRIPTION\_COMMENT*

*:C: QUERY\_SYSTEM()*

*:C: IF QUERY\_RESULT=1 THEN*

*:C:    Char post variable=QUERY\_CHAR\_VAL*

*:C: ENDIF*
## <a name="chmtopic63"></a>**QUERY\_HOLDER\_NUM\_COMMENT**
#### **Purpose**
If the return value of QUERY\_RESULT is TRUE, the system will pass a string value to post system variable named QUERY\_CHAR\_VAL.

To be used in *CAMWorks 2020 SP0* or higher versions.


#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_HOLDER\_NUM\_COMMENT**
#### **Comments**
**Associated commands and variables:**

`             `The example code below shows the other variables used with this command. 



*:C: QUERY\_ITEM\_ID =QUERY\_HOLDER\_NUM\_COMMENT*

*:C: QUERY\_SYSTEM()*

*:C: IF QUERY\_RESULT=1 THEN*

*:C:    Char post variable=QUERY\_CHAR\_VAL*

*:C: ENDIF*
## <a name="chmtopic64"></a>**QUERY\_HOLDER\_VENDOR\_COMMENT**
#### **Purpose**
If the return value of QUERY\_RESULT is TRUE, then the system will pass a string value to post system variable named QUERY\_CHAR\_VAL.

To be used in *CAMWorks 2020 SP0* or higher versions.


#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_HOLDER\_VENDOR\_COMMENT**
#### **Comments**
**Associated commands and variables:**

`             `The example code below shows the other variables used with this command. 



*:C: QUERY\_ITEM\_ID =QUERY\_HOLDER\_VENDOR\_COMMENT*

*:C: QUERY\_SYSTEM()*

*:C: IF QUERY\_RESULT=1 THEN*

*:C:    Char post variable=QUERY\_CHAR\_VAL*

*:C: ENDIF*
## <a name="chmtopic94"></a>**QUERY\_INT\_CENTER\_TOUCHOFF\_REG**
#### **Purpose**
This command will query whether the user has selected tool nose center or tool nose tip in a turn operation .   This is used in conjunction with IMS Simulator.  Available in Turn and Mill-Turn. 

Supported in CAMWorks 2019 SP1 and later versions. Not supported in any ProCAM product.


#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_INT\_CENTER\_TOUCHOFF\_REG**


#### **Comments**
`     `**Associated commands and variables:**

The example code below shows the other variables used with this command. This logic should be in :SECTION=[CALC_QUERY_POST](#chmtopic367)



:C: IF OPR\_TOOL\_TIP\_CENTER=1 THEN

:C:    IF HAVE\_SUB\_STATIONS=FALSE THEN

:C:       IF QUERY\_ITEM\_ID = QUERY\_INT\_CENTER\_TOUCHOFF\_REG THEN

:C:          IF SECTIONEXIST(QUERY\_TOUCHOFF\_CENTER) THEN

:C:          CALL(QUERY\_TOUCHOFF\_CENTER)

:C:          ELSE

:C:          QUERY\_INT\_VAL=(TOOL+1)

:C:          ENDIF

:C:       ENDIF

:C:    ELSE

:C:       IF QUERY\_ITEM\_ID = QUERY\_INT\_CENTER\_TOUCHOFF\_REG THEN

:C:          IF SECTIONEXIST(QUERY\_TOUCHOFF\_CENTER\_SUB\_STATIONS) THEN

:C:          CALL(QUERY\_TOUCHOFF\_CENTER\_SUB\_STATIONS)

:C:          ELSE

:C:          QUERY\_INT\_VAL=((SUB\_STATION\*10)+2)

:C:          ENDIF

:C:       ENDIF

:C:    ENDIF

:C: ENDIF


## <a name="chmtopic601"></a>**QUERY\_INT\_HAND\_OF\_TOOL**
#### **Purpose**
This command will query the hand of the tool. 

Available in Turn only.

Supported in CAMWorks 2013 and higher versions. Not supported in any ProCAM product.
#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_INT\_HAND\_OF\_TOOL**
#### **Comments**
**Associated commands and variables:**

The example code below shows the other variables used with this command. If the Query result was "1" then the value will be in  **QUERY\_INT\_VAL**.



*:C: QUERY\_ITEM\_ID=QUERY\_INT\_HAND\_OF\_TOOL*

*:C: QUERY\_SYSTEM()*

*:C: IF QUERY\_RESULT=1 THEN*

*:C:    IF QUERY\_INT\_VAL=1 THEN*

*\*      Hand of tool = "LEFT"*

*:C:    ENDIF*

*:C:    IF QUERY\_INT\_VAL=2 THEN*

*\*      Hand of tool = "RIGHT"*

*:C:    ENDIF*

*:C: ENDIF*


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic254"></a>**QUERY\_INT\_KIN\_SETUP\_POS**
#### **Purpose**
If the return value of QUERY\_INT\_VAL is TRUE, the system will look for the Kin file and the result will be passed back to the post as X, Y, Z, I, J, K from the Kinematic Setup Transform in below post variables. To be used in CAMWorks 2014 SP3 or later versions.


#### **Syntax**
`     `**QUERY\_ITEM\_ID=QUERY\_INT\_KIN\_SETUP\_POS**


#### **Comments**
Associated commands and variables:

The example code below shows the other variables used with this command.



`     `*:C: QUERY\_ITEM\_ID=QUERY\_INT\_KIN\_SETUP\_POS*

`   `*\*    If you need length comp then add below line.*

`   `*\*    QUERY\_INT\_VAL=ALLOW\_TOOL\_HEAD\_LENGTH\_COMP*

`   `*:C: QUERY\_SYSTEM()*

`   `*:C: IF QUERY\_RESULT=TRUE THEN*

`   `*\*    Post Variable = SETUP\_MACH\_X*

`   `*\*    Post Variable = SETUP\_MACH\_Y*

`   `*\*    Post Variable = SETUP\_MACH\_Z*

`   `*\*    Post Variable = SETUP\_MACH\_I*

`   `*\*    Post Variable = SETUP\_MACH\_J*

`   `*\*    Post Variable = SETUP\_MACH\_K*

`   `*:C: ENDIF*


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic602"></a>**QUERY\_INT\_LENGTH\_REG**
#### **Purpose**
This command will query the Tool Length offsets in the posted output. This is used in conjunction with CAMWorks Virtual Machine.         

Available in Mill, Turn and Mill-Turn.

Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.
#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_INT\_LENGTH\_REG**      
#### **Comments**
**Associated commands and variables:**

The example code below shows the other variables used with this command. This logic should be in:  **SECTION=CALC\_QUERY\_POST**.  



:C: IF QUERY\_ITEM\_ID = QUERY\_INT\_LENGTH\_REG THEN

:C: QUERY\_INT\_VAL=TOOL

:C: RETURN

:C: ENDIF


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic123"></a>**QUERY\_INT\_MILL\_FEATURE\_SUB\_TYPE**
#### **Purpose**
This If the return value of QUERY\_RESULT is TRUE, the system will pass the Feature Hole type in QUERY\_INT\_VAL. To be used in CAMWorks 2019 SP0 or higher versions.
#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_INT\_MILL\_FEATURE\_SUB\_TYPE**      
#### **Comments**
Associated commands and variables:

The example code below shows the other variables used with this command.



:C: IF QUERY\_ITEM\_ID = QUERY\_INT\_MILL\_FEATURE\_SUB\_TYPE

:C: QUERY\_SYSTEM()

:C: IF QUERY\_RESULT = 1 THEN

:C: CALL(OUTPUT\_FEATURE\_SUB\_TYPE)

:C: ENDIF



:SECTION=OUTPUT\_FEATURE\_SUB\_TYPE

:T:<BLANK><EOL>

:T:(MILL\_FEATURE\_SUB\_TYPE=<%LT":QUERY\_INT\_VAL>)<EOL>


#### **Available constants:**
MILL\_FEATURE\_SUB\_TYPE\_BLIND

MILL\_FEATURE\_SUB\_TYPE\_THROUGH

MILL\_FEATURE\_SUB\_TYPE\_DOUBLE\_BLIND

MILL\_FEATURE\_SUB\_TYPE\_UNKNOWN

MILL\_FEATURE\_SUB\_TYPE\_DRILLED
## <a name="chmtopic124"></a>**QUERY\_INT\_MILL\_PROCESS\_TOOLPATH\_BY**

#### **Purpose**
This If the return value of QUERY\_RESULT is TRUE, the system will pass the Mill Process Toolpath type in QUERY\_INT\_VAL. To be used in CAMWorks 2019 SP0 or higher versions.
#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_INT\_MILL\_PROCESS\_TOOLPATH\_BY**      
#### **Comments**
Associated commands and variables:

The example code below shows the other variables used with this command.



:C: IF QUERY\_ITEM\_ID = QUERY\_INT\_MILL\_PROCESS\_TOOLPATH\_BY

:C: QUERY\_SYSTEM()

:C: IF QUERY\_RESULT = 1 THEN

:C: CALL(OUTPUT\_PROCESS\_TOOLPATH\_BY)

:C: ENDIF



:SECTION=OUTPUT\_PROCESS\_TOOLPATH\_BY

:T:<BLANK><EOL>

:T:(MILL\_PROCESS\_TOOLPATH\_BY=<%LT":QUERY\_INT\_VAL>)<EOL>


#### **Available constants:**
MILL\_PROCESS\_TOOLPATH\_BY\_NONE

MILL\_PROCESS\_TOOLPATH\_BY\_TOOL

MILL\_PROCESS\_TOOLPATH\_BY\_FEATURE

MILL\_PROCESS\_TOOLPATH\_BY\_PART


## <a name="chmtopic603"></a>**QUERY\_INT\_MILL\_ROUGH\_TYPE**
#### **Purpose**
This command will query the Rough Mill Type.         

Available in Mill and Mill-Turn.

Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.
#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_INT\_MILL\_ROUGH\_TYPE**      
#### **Comments**
**Associated commands and variables:**

The example code below shows the other variables used with this command. If the Query result was "1", then the value will be in the **QUERY\_INT\_VAL**  



*:C: QUERY\_ITEM\_ID=QUERY\_INT\_MILL\_ROUGH\_TYPE*

:C: QUERY\_SYSTEM()

:C: IF QUERY\_RESULT=1 THEN

:C:    IF QUERY\_INT\_VAL=0 THEN

\*         2 axis “Pocket In” = **MILL\_ROUGH\_TYPE\_SPIRALIN**

:C:    ENDIF

:C:    IF QUERY\_INT\_VAL=1 THEN

\*         2 axis “Pocket Out” = **MILL\_ROUGH\_TYPE\_SPIRALOUT**

\*         3 axis “Pocket Out” = **MILL\_ROUGH\_TYPE\_SPIRALOUT**

:C:    ENDIF

:C:    IF QUERY\_INT\_VAL=2 THEN

\*         2 axis “Zig” = **MILL\_ROUGH\_TYPE\_ZIG**

:C:    ENDIF

:C:    IF QUERY\_INT\_VAL=3 THEN

\*         2 axis “Zigzag” = **MILL\_ROUGH\_TYPE\_ZIGZAG**

\*         3 axis “Lace” = **MILL\_ROUGH\_TYPE\_ZIGZAG**

:C:    ENDIF

:C:    IF QUERY\_INT\_VAL=4 THEN

\*         2 axis “Spiral In” = **MILL\_ROUGH\_TYPE\_TRUESPIRALIN**

:C:    ENDIF

:C:    IF QUERY\_INT\_VAL=5 THEN

\*         2 axis “Spiral Out” = **MILL\_ROUGH\_TYPE\_TRUESPIRALOUT**

:C:    ENDIF

:C:    IF QUERY\_INT\_VAL=6 THEN

\*         2 axis “Plunge Rough” = **MILL\_ROUGH\_TYPE\_PLUNGEROUGH**

:C:    ENDIF

:C:    IF QUERY\_INT\_VAL=7 THEN

\*         2 axis “Offset Roughing” = **MILL\_ROUGH\_TYPE\_POCKETIN\_CORE**

\*         3 axis “Pocket In Core” = **MILL\_ROUGH\_TYPE\_POCKETIN\_CORE**

:C:    ENDIF

:C:    IF QUERY\_INT\_VAL=8 THEN

\*         2 axis “Volumill” = **MILL\_ROUGH\_TYPE\_VOLUMILL**

\*         3 axis “Volumill” = **MILL\_ROUGH\_TYPE\_VOLUMILL**

:C:    ENDIF

:C:    IF QUERY\_INT\_VAL=19 THEN

\*         3 axis “Adaptive” = **MILL\_ROUGH\_TYPE\_ADAPTIVE**

:C:    ENDIF*    

*:*C: ENDIF


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic604"></a>**QUERY\_INT\_NUM\_TURRETS\_ABOVE**
#### **Purpose**
This command will query the number of turrets above Spindle centerline. This is used in conjunction with CAMWorks Virtual Machine.        

Available in Mill, Turn and Mill-Turn.

Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.
#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_INT\_NUM\_TURRETS\_ABOVE**  
#### **Comments**
**Associated commands and variables:**

The example code below shows the other variables used with this command. This logic should be in:  **SECTION=CALC\_QUERY\_POST**.  



*:C: IF QUERY\_ITEM\_ID = QUERY\_INT\_NUM\_TURRETS\_ABOVE  THEN*

*:C: QUERY\_INT\_VAL=1*

*:C: RETURN*

*:C: ENDIF*  


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic605"></a>**QUERY\_INT\_NUM\_TURRETS\_BELOW**
#### **Purpose**
This command will query the number of turrets below Spindle centerline. This is used in conjunction with CAMWorks Virtual Machine.         

Available in Mill, Turn and Mill-Turn.

Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.
#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_INT\_NUM\_TURRETS\_BELOW**   
#### **Comments**
**Associated commands and variables:**

The example code below shows the other variables used with this command. This logic should be in:  **SECTION=CALC\_QUERY\_POST**.  



*:C: IF QUERY\_ITEM\_ID = QUERY\_INT\_NUM\_TURRETS\_BELOW  THEN*

*:C: QUERY\_INT\_VAL=1*

*:C: RETURN*

*:C: ENDIF*  


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic606"></a>**QUERY\_INT\_OFFSET\_REG**
#### **Purpose**
This command will query the Tool Diameter offsets in the posted output. This is used in conjunction with CAMWorks Virtual Machine.         

Available in Mill, Turn and Mill-Turn.

Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.
#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_INT\_OFFSET\_REG**       
#### **Comments**
**Associated commands and variables:**

The example code below shows the other variables used with this command. This logic should be in:  **SECTION=CALC\_QUERY\_POST**.  



*:C: IF QUERY\_ITEM\_ID = QUERY\_INT\_OFFSET\_REG THEN*

*:C: CALL(CALC\_QUERY\_DIAM\_OFFSET\_REG) - This section is in the    General library files.*

*:C: RETURN*

*:C: ENDIF*

*\**

*:SECTION=CALC\_QUERY\_DIAM\_OFFSET\_REG*

*:C: QUERY\_INT\_VAL=(TOOL+COMP\_OFFSET)*

*:C: IF TOOL\_LENGTH\_DIAM\_OFFSET\_METHOD=METHOD\_FROM\_TOOL THEN*

*:C: QUERY\_INT\_VAL=TOOL\_DIAM\_OFFSET*

*:C: ENDIF*  


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic607"></a>**QUERY\_INT\_PRIMARY\_TOUCHOFF\_REG**

#### **Purpose**
This command will query the Primary Tool Length offsets in the posted output.  

This is used in conjunction with CAMWorks Virtual Machine, Turn and Mill-Turn.

Supported in CAMWorks 2013 SP1 and later.

Not supported in any ProCAM product.


#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_INT\_PRIMARY\_TOUCHOFF\_REG**
#### **Comments**
**Associated commands and variables:**

The example code below shows the other variables used with this command. This logic should be in:    **SECTION=CALC\_QUERY\_POST**  



*:C: IF QUERY\_ITEM\_ID =QUERY\_INT\_PRIMARY\_TOUCHOFF\_REG THEN*

*:C: QUERY\_INT\_VAL=TOOL*

*:C: RETURN*

*:C: ENDIF*




#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic608"></a>**QUERY\_INT\_SECONDARY\_TOUCHOFF\_REG**
#### **Purpose**
This command will query the Secondary Tool Length offsets in the posted output. 

This is used in conjunction with CAMWorks Virtual Machine, Turn and Mill-Turn.

Supported in CAMWorks 2013 SP1 and later.

Not supported in any ProCAM product.


#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_INT\_SECONDARY\_TOUCHOFF\_REG**
#### **Comments**
**Associated commands and variables:**

The example code below shows the other variables used with this command. This logic should be in:    **SECTION=CALC\_QUERY\_POST**  



*:C: IF QUERY\_ITEM\_ID =QUERY\_INT\_SECONDARY\_TOUCHOFF\_REG THEN*

*:C: QUERY\_INT\_VAL=TOOL*

*:C: RETURN*

*:C: ENDIF*




#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic609"></a>**QUERY\_INT\_ZERO\_OFFSET\_RADIUS**
#### **Purpose**
If the return value of QUERY\_INT\_VAL is TRUE, the system will zero out the Radius in the Eureka Offset radius correctors for this Tool.

If the return value of QUERY\_INT\_VAL is FALSE, the system will Not zero out the Radius in the Eureka Offset radius correctors for this Tool.

If the Post doesn’t know whether to zero out the Radius offset, then don’t set it since the system has already pre-set the QUERY\_INT\_VAL based on whether CNC comp with part geometry or CNC comp for Tool wear only was used.
#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_INT\_ZERO\_OFFSET\_RADIUS**  
#### **Comments**
**Associated commands and variables:**

The example code below shows the other variables used with this command. This logic should be in  **:SECTION=CALC\_QUERY\_POST**.  


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic121"></a>**QUERY\_MACHINE\_NAME**
#### **Purpose**
If the return value of QUERY\_RESULT is TRUE, the system will pass the string associated with the machine name from the TechDB and pass the value in post system variable called QUERY\_CHAR\_VAL. To be used in CAMWorks 2019 SP0 or higher versions.


#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_MACHINE\_NAME**
**\

#### **Comments**
Associated commands and variables:

The example code below indicates the other variables used with this command.



**:C:    QUERY\_ITEM\_ID=QUERY\_MACHINE\_NAME**

**:C:    QUERY\_SYSTEM()**

**:C:    IF QUERY\_RESULT=1 THEN**

**:C:    Defined Post Variable=QUERY\_CHAR\_VAL**

**:C:    ENDIF**


**\

## <a name="chmtopic255"></a>**QUERY\_MILL\_TLP\_Z\_EXTENTS**
#### **Purpose**
If the return value of QUERY\_RESULT is TRUE, the system will pass the Z extents in post variables called QUERY\_TLP\_Z\_MIN and QUERY\_TLP\_Z\_MAX. To be used in CAMWorks 2014 SP3 or later versions.


#### **Syntax**
`     `**QUERY\_ITEM\_ID=QUERY\_MILL\_TLP\_Z\_EXTENTS**




#### **Comments**
Associated commands and variables:

The example code below shows the other variables used with this command.



`     `*:C: QUERY\_ITEM\_ID=QUERY\_MILL\_TLP\_Z\_EXTENTS*

`   `*:C: QUERY\_SYSTEM()*

`   `*:C: IF QUERY\_RESULT=TRUE THEN*

`   `*\*    Post Variable = QUERY\_TLP\_Z\_MIN*

`   `*\*    Post Variable = QUERY\_TLP\_Z\_MAX*

`   `*:C: ENDIF*


#### **Other Associated commands and variables:**
[QUERY_SYSTEM](#chmtopic430)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic122"></a>**QUERY\_NC\_FILE\_EXTENSION**
#### **Purpose**
If the return value of QUERY\_RESULT is TRUE, the system will pass the string associated with the posted output file's extension and pass the value in post system variable called QUERY\_CHAR\_VAL. To be used in CAMWorks 2019 SP0 or higher versions.


#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_NC\_FILE\_EXTENSION**
**\

#### **Comments**
Associated commands and variables:

The example code below indicates the other variables used with this command.



**:C:    QUERY\_ITEM\_ID=QUERY\_NC\_FILE\_EXTENSION**

**:C:    QUERY\_SYSTEM()**

**:C:    IF QUERY\_RESULT=1 THEN**

**:C:    Defined Post Variable=QUERY\_CHAR\_VAL**

**:C:    ENDIF**
## <a name="chmtopic187"></a>**QUERY\_NUM\_THREAD\_PASSES**
#### **Purpose**
If the return value of [QUERY_RESULT](#chmtopic422) is TRUE, the system will pass the number of thread passes to the post system variable called [QUERY_INT_VAL](#chmtopic424) in a Turn threading operation. To be used in CAMWorks 2016 SP0 or higher versions.


#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_NUM\_THREAD\_PASSES**
**\

#### **Comments**
Associated commands and variables:

The example code below indicates how other variables are to be used with this command.



**:C:    IF OPR\_TYPE=LATHE\_THREADING THEN**

**:C:    QUERY\_ITEM\_ID=QUERY\_NUM\_THREAD\_PASSES**

**:C:    QUERY\_SYSTEM()**

**:C:    IF QUERY\_RESULT=1 THEN**

**:C:    Defined Post Variable=QUERY\_INT\_VAL**

**:C:    ENDIF**
## <a name="chmtopic66"></a>**QUERY\_STATION\_DESCRIPTION\_COMMENT**
#### **Purpose**
If the return value of QUERY\_RESULT is TRUE, then the system will pass a string value to post system variable named QUERY\_CHAR\_VAL.

To be used in *CAMWorks 2020 SP0* or higher versions.


#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_STATION\_DESCRIPTION\_COMMENT**
#### **Comments**
**Associated commands and variables:**

`             `The example code below shows the other variables used with this command. 



*:C: QUERY\_ITEM\_ID =QUERY\_STATION\_DESCRIPTION\_COMMENT*

*:C: QUERY\_SYSTEM()*

*:C: IF QUERY\_RESULT=1 THEN*

*:C:    Char post variable=QUERY\_CHAR\_VAL*

*:C: ENDIF*
## <a name="chmtopic159"></a>**QUERY\_STATS\_PAGE\_XYZ\_EXTENTS**
#### **Purpose**
If the return value of QUERY\_RESULT is TRUE, the system will pass the decimal values in Statistics page to Post system variables.

To be used in CAMWorks 2017 SP0 or higher versions.


#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_STATS\_PAGE\_XYZ\_EXTENTS**  


#### **Comments**
`     `**Associated commands and variables:**

`     `The example code below shows the other variables used with this command.



:C: QUERY\_ITEM\_ID=QUERY\_STATS\_PAGE\_XYZ\_EXTENTS

:C: QUERY\_SYSTEM()

:C: IF QUERY\_RESULT=1 THEN

Post var =QUERY\_STATS\_X\_MIN

Post var =QUERY\_STATS\_Y\_MIN

Post var =QUERY\_STATS\_Z\_MIN

Post var =QUERY\_STATS\_X\_MAX

Post var =QUERY\_STATS\_Y\_MAX

Post var =QUERY\_STATS\_Z\_MAX

:C: ENDIF


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic430"></a>**QUERY\_SYSTEM()**
#### **Purpose**
This command will query any object ID you pass to it. It can get information from an object that is in a Setup or operation dialog box.

Available in Mill, Turn and Mill-Turn.

Supported in CAMWorks 2009 and later. Not supported in any ProCAM product.
#### **Syntax**
**QUERY\_SYSTEM()**
#### **Comments**
Associated commands and variables:

The example code below shows the other variables used with this command and that QUERY\_SYSTEM() will first determine what has been selected for X Axis machining direction on the Axis tab in the Setup dialog box. If the value is “1” then “Angle” was selected and we can now do another QUERY\_SYSTEM() to find the angle value that will be passed to QUERY\_DEC\_VALUE.

**Note:**

Currently QUERY\_INT\_X\_SETUP\_DIR and QUERY\_DEC\_X\_SETUP\_ANGLE are the only object ID’s set. In the future you can send in an enhancement request to query other objects and we will add them when R&D resources are available.

*:C: QUERY\_ITEM\_ID=QUERY\_INT\_X\_SETUP\_DIR*

*:C: QUERY\_SYSTEM()*

*:C: IF QUERY\_RESULT=1 THEN*

*:C:    IF QUERY\_INT\_VAL=1 THEN*

*:C:    QUERY\_ITEM\_ID=QUERY\_DEC\_X\_SETUP\_ANGLE*

*:C:    QUERY\_SYSTEM()*

*:C:       IF QUERY\_RESULT=1 THEN*

*:C:       MY\_OPER\_SETUP\_ANGLE=QUERY\_DEC\_VAL*

*:C:       CALL(TEST\_QUERY)*

*:C:       ENDIF*

*:C:    ENDIF*

*:C: ENDIF*
#### ** 
#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic132"></a>**QUERY\_TOOL\_COOLANT\_TYPE**
#### **Purpose**
If the return value of QUERY\_RESULT is TRUE, then the system will pass the *Tool coolant type* info when *From tool* is selected for an operation. To be used in CAMWorks 2018 SP0 and higher versions.


#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_TOOL\_COOLANT\_TYPE**              
#### ** 
#### **Comments**
The sample code below illustrates how other variables are used with this command. 



*:C: IF QUERY\_ITEM\_ID = QUERY\_TOOL\_COOLANT\_TYPE*

*:C: QUERY\_SYSTEM()*

*:C: IF QUERY\_RESULT=TRUE THEN*

*:C: IF SECTION EXIST (OUTPUT\_TOOL\_COOLANT\_TYPE) THEN CALL (OUTPUT\_TOOL\_COOLANT\_TYPE)ENDIF*

*:C: ENDIF*

*\**

*:SECTION=OUTPUT\_TOOL\_COOLANT\_TYPE*

*:T: (Tool Coolant type=<%:QUERY\_INT\_VAL>)<EOL>*


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_ENTRY_TYPE](#chmtopic131)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_TOOL_DIAMETER_REG](#chmtopic133)

[QUERY_TOOL_LENGTH_REG](#chmtopic134)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic62"></a>**QUERY\_TOOL\_DESCRIPTION\_COMMENT**
#### **Purpose**
If the return value of QUERY\_RESULT is TRUE, the system will pass a string value to post system variable named QUERY\_CHAR\_VAL.

To be used in *CAMWorks 2020 SP0* or higher versions.


#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_TOOL\_DESCRIPTION\_COMMENT**
#### **Comments**
**Associated commands and variables:**

`             `The example code below shows the other variables used with this command. 



*:C: QUERY\_ITEM\_ID =QUERY\_TOOL\_DESCRIPTION\_COMMENT*

*:C: QUERY\_SYSTEM()*

*:C: IF QUERY\_RESULT=1 THEN*

*:C:    Char post variable=QUERY\_CHAR\_VAL*

*:C: ENDIF*
## <a name="chmtopic133"></a>**QUERY\_TOOL\_DIAMETER\_REG**
#### **Purpose**
If the return value of QUERY\_RESULT is TRUE, then the system will pass the *tool diameter register number* info when *From tool* is selected for an operation. To be used in CAMWorks 2018 SP0 or higher versions.


#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_TOOL\_DIAMETER\_REG**              
#### ** 
#### **Comments**
The sample code below illustrates how other variables are used with this command. 



*:C: IF QUERY\_ITEM\_ID = QUERY\_TOOL\_DIAMETER\_REG*

*:C: QUERY\_SYSTEM()*

*:C: IF QUERY\_RESULT=TRUE THEN*

*:C: IF SECTION EXIST (OUTPUT\_TOOL\_DIAMETER\_REG) THEN CALL (OUTPUT\_TOOL\_DIAMETER\_REG)ENDIF*

*:C: ENDIF*

*\**

*:SECTION=OUTPUT\_TOOL\_DIAMETER\_REG*

*:T: (Tool Diameter Reg=<%:QUERY\_INT\_VAL>)<EOL>*


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_ENTRY_TYPE](#chmtopic131)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_TOOL_COOLANT_TYPE](#chmtopic132)

[QUERY_TOOL_LENGTH_REG](#chmtopic134)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic60"></a>**QUERY\_TOOL\_ID\_COMMENT**
#### **Purpose**
If the return value of QUERY\_RESULT is TRUE, then the system will pass a string value to post system variable named QUERY\_CHAR\_VAL.

To be used in *CAMWorks 2020 SP0* or higher versions.


#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_TOOL\_ID\_COMMENT**
#### **Comments**
**Associated commands and variables:**

`             `The example code below shows the other variables used with this command. 



*:C: QUERY\_ITEM\_ID =QUERY\_TOOL\_ID\_COMMENT*

*:C: QUERY\_SYSTEM()*

*:C: IF QUERY\_RESULT=1 THEN*

*:C:    Char post variable=QUERY\_CHAR\_VAL*

*:C: ENDIF*
## <a name="chmtopic134"></a>**QUERY\_TOOL\_LENGTH\_REG**
#### **Purpose**
If the return value of QUERY\_RESULT is TRUE, then the system will pass the *tool length register number* info when *From tool* is selected for an operation. To be used in CAMWorks 2018 SP0 or higher versions.


#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_TOOL\_LENGTH\_REG**              
#### ** 
#### **Comments**
The sample code below illustrates how other variables are used with this command. 



*:C: IF QUERY\_ITEM\_ID = QUERY\_TOOL\_LENGTH\_REG*

*:C: QUERY\_SYSTEM()*

*:C: IF QUERY\_RESULT=TRUE THEN*

*:C: IF SECTION EXIST (OUTPUT\_TOOL\_LENGTH\_REG) THEN CALL (OUTPUT\_TOOL\_LENGTH\_REG)ENDIF*

*:C: ENDIF*

*\**

*:SECTION=OUTPUT\_TOOL\_LENGTH\_REG*

*:T: (Tool length Reg=<%:QUERY\_INT\_VAL>)<EOL>*


#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_ENTRY_TYPE](#chmtopic131)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)

[QUERY_TOOL_COOLANT_TYPE](#chmtopic132)

[QUERY_TOOL_DIAMETER_REG](#chmtopic133)

[QUERY_USE_SUB_PROGRAMS](#chmtopic234)
## <a name="chmtopic61"></a>**QUERY\_TOOL\_VENDOR\_COMMENT**
#### **Purpose**
If the return value of QUERY\_RESULT is TRUE, then the system will pass a string value to post system variable named QUERY\_CHAR\_VAL.

To be used in *CAMWorks 2020 SP0* or higher versions.


#### **Syntax**
**QUERY\_ITEM\_ID=QUERY\_TOOL\_VENDOR\_COMMENT**
#### **Comments**
**Associated commands and variables:**

`             `The example code below shows the other variables used with this command. 



*:C: QUERY\_ITEM\_ID =QUERY\_TOOL\_VENDOR\_COMMENT*

*:C: QUERY\_SYSTEM()*

*:C: IF QUERY\_RESULT=1 THEN*

*:C:    Char post variable=QUERY\_CHAR\_VAL*

*:C: ENDIF*
## <a name="chmtopic234"></a>**QUERY\_USE\_SUB\_PROGRAMS**
#### **Purpose**
If the return value of QUERY\_RESULT is TRUE, then the system will pass 1 or 0 if in assembly mode irrespective of whether the Subprogram checkbox is checked or not. The value will be stored in the post system variable called QUERY\_INT\_VAL. To be used in CAMWorks 2015 SP1 or newer version.


#### **Syntax**
`     `**QUERY\_ITEM\_ID=QUERY\_USE\_SUB\_PROGRAMS**


#### **Comments**
`     `**Associated commands and variables:**

`     `The example code below shows the other variables used with this command.



:C: QUERY\_ITEM\_ID=QUERY\_USE\_SUB\_PROGRAMS

:C: QUERY\_SYSTEM()

:C: IF QUERY\_RESULT=1 THEN Defined Post Variable=QUERY\_INT\_VAL

ENDIF




#### **Other Associated commands and variables:**
[QUERY_CONFIGURATION_NAME](#chmtopic158)

[QUERY_DEC_MIN_PROTRUSION](#chmtopic587)

[QUERY_DEC_OPER_TIME](#chmtopic588)

[QUERY_EXPORT_ERROR](#chmtopic589)

[QUERY_FEATURE_STRATEGY](#chmtopic233)

[QUERY_GCODE_AXIS_NAMES_MILL](#chmtopic590)

[QUERY_GCODE_AXIS_NAMES_T1A](#chmtopic591)

[QUERY_GCODE_AXIS_NAMES_T2A](#chmtopic592)

[QUERY_GCODE_AXIS_NAMES_T1B](#chmtopic593)

[QUERY_GCODE_AXIS_NAMES_T2B](#chmtopic594)

[QUERY_GCODE_DEFAULT_WCS](#chmtopic595)

[QUERY_GCODE_FILE_NAME_T1A](#chmtopic596)

[QUERY_GCODE_FILE_NAME_T2A](#chmtopic597)

[QUERY_GCODE_FILE_NAME_T1B](#chmtopic598)

[QUERY_GCODE_FILE_NAME_T2B](#chmtopic594)

[QUERY_GCODE_POSTED_FILE_NAME](#chmtopic599)

[QUERY_GCODE_WCS](#chmtopic600)

[QUERY_INT_HAND_OF_TOOL](#chmtopic601)

[QUERY_INT_KIN_SETUP_POS](#chmtopic254)

[QUERY_INT_LENGTH_REG](#chmtopic602)

[QUERY_INT_MILL_ROUGH_TYPE](#chmtopic603)

[QUERY_INT_NUM_TURRETS_ABOVE](#chmtopic604)

[QUERY_INT_NUM_TURRETS_BELOW](#chmtopic605)

[QUERY_INT_OFFSET_REG](#chmtopic606)

[QUERY_INT_PRIMARY_TOUCHOFF_REG](#chmtopic607)

[QUERY_INT_SECONDARY_TOUCHOFF_REG](#chmtopic608)

[QUERY_INT_ZERO_OFFSET_RADIUS](#chmtopic609)

[QUERY_MILL_TLP_EXTENTS](#chmtopic255)

[QUERY_STATS_PAGE_XYZ_EXTENTS](#chmtopic159)

[QUERY_SYSTEM](#chmtopic430)
## <a name="chmtopic659"></a>**L**
#### **Purpose**
Tells the system to output leading zeros.
#### **Syntax**
**L**
#### **Comments**
The example is output if the number is 1 inch

N10 G01 X001
#### **Example**
:SECTION=LINE\_MOVE\_MILL

:T:<N><G:01> X<"#34L":ABS\_X\_END><EOL>
## <a name="chmtopic661"></a>**l**
#### **Purpose**
A lowercase "l" tells the system to output leading spaces.
#### **Syntax**
**l**
#### **Comments**
The example is output if the number is 1 inch

N10 G01 X\_\_1
#### **Example**
:SECTION=LINE\_MOVE\_MILL

:T:<N><G:01> X<"#34l":ABS\_X\_END><EOL>
## <a name="chmtopic663"></a>**N**
#### **Purpose**
An uppercase "N" tells the system not to convert output if decimal.
#### **Syntax**
**N**
#### **Comments**
The example is output if the number is 180 degrees

N10 G01 A180
#### **Example**
:SECTION=LINE\_MOVE\_MILL

:T:<N><G:01> A<"#33N":ARC\_START\_ANGLE><EOL>
## <a name="chmtopic665"></a>**T**
#### **Purpose**
An uppercase "T" tells the system to output trailing zeros.
#### **Syntax**
**T**
#### **Comments**
The example is output if the number is 1 inch

N10 G01 X10000
#### **Example**
:SECTION=LINE\_MOVE\_MILL

:T:<N><G:01> X<"#34T":ABS\_X\_END><EOL>
## <a name="chmtopic667"></a>**t**
#### **Purpose**
A lowercase "t" tells the system to output trailing spaces.
#### **Syntax**
**t**
#### **Comments**
The example is output if the number is 1 inch

N10 G01 X1\_\_\_\_
#### **Example**
:SECTION=LINE\_MOVE\_MILL

:T:<N><G:01> X<"#34t":ABS\_X\_END><EOL>
## <a name="chmtopic669"></a>**@**
#### **Purpose**
An @ tells the system to output a space in place of a plus or minus sign if a sign is not output.
#### **Syntax**
**@**
#### **Comments**
The below example is output if the number is 1 inch

N10 G01 X\_1
#### **Example**
:SECTION=LINE\_MOVE\_MILL

:T:<N><G:01> X<"#-34@":ARC\_START\_ANGLE><EOL>
## <a name="chmtopic671"></a>**-**
#### **Purpose**
Tells the system to output a minus sign if number is negative.
#### **Syntax**
**-**
#### **Comments**
The below example is output if the number is negative 1 inch.

N10 G01 X-1
#### **Example**
:SECTION=LINE\_MOVE\_MILL

:T:<N><G:01> X<"#-34":ARC\_START\_ANGLE><EOL>
## <a name="chmtopic673"></a>**+**
#### **Purpose**
Forces the system to output a plus or minus sign.
#### **Syntax**
**+**
#### **Comments**
The below example is output if the number is negative 1 inch.

N10 G01 X+1
#### **Example**
:SECTION=LINE\_MOVE\_MILL

:T:<N><G:01> X<"#+34":ARC\_START\_ANGLE><EOL>
## <a name="chmtopic675"></a>**"**
#### **Purpose**
Double quotation marks are used to group output format.
#### **Syntax**
**" "**
#### **Comments**
None.
#### **Example**
## **#1: Not using HEADER default decimal output**
:SECTION=LINE\_MOVE\_MILL

:T:<N><G:01> X<"#-34":ARC\_START\_ANGLE><EOL>


## **#2: Using HEADER defaults**
:SECTION=LINE\_MOVE\_MILL

:T:<N><G:01> X<#:ARC\_START\_ANGLE><EOL>
## <a name="chmtopic677"></a>**#**
#### **Purpose**
Tells the system the output is decimal.
#### **Syntax**
**#**
#### **Comments**
None.
#### **Example**
## **#1: Not using HEADER default decimal output**
:SECTION=LINE\_MOVE\_MILL

:T:<N><G:01> X<"#-34":ARC\_START\_ANGLE><EOL>


## **#2: Using HEADER defaults**
:SECTION=LINE\_MOVE\_MILL

:T:<N><G:01> X<#:ARC\_START\_ANGLE><EOL>
## <a name="chmtopic679"></a>**.**
#### **Purpose**
A decimal point (.) forces the system to output a decimal to tape.
#### **Syntax**
**.**
#### **Comments**
None.
#### **Example**
## **#1: Not using a decimal point**
:SECTION=LINE\_MOVE\_MILL

:T:<N><G:01> X<"#-34":ARC\_START\_ANGLE><EOL>



N100 G01 X?
## **#2: Using a decimal point**
:SECTION=LINE\_MOVE\_MILL

:T:<N><G:01> X<"#-3.4":ARC\_START\_ANGLE><EOL>



N10 G01 X?.
## <a name="chmtopic681"></a>**%**
#### **Purpose**
Tells the system the output is integer.
#### **Syntax**
**%**
#### **Comments**
None.
#### **Example**
## **#1: Using HEADER default integer output**
:SECTION=START\_OF\_TAPE\_MILL

:T:O<"%4LT":program\_number><EOL>

Returns: O0001
## **#2: Using HEADER defaults**
:SECTION=START\_OF\_TAPE\_MILL

:T:O<%:program\_number><EOL>
## <a name="chmtopic683"></a>**ADD\_CAD()**
#### **Purpose**
To add a CAD entity.
#### **Syntax**
**:C: ADD\_CAD(position)**
#### **Comments**
You must set all the system variables first before you add the entity in CAD. You add CAD by PREVIOUS position, CURRENT position or NEXT position.
#### **Examples**
**#1: Example of a current line entity**

:SECTION=CALC\_MAIN

:C: ABS\_X\_START=5.

:C: ABS\_Y\_START=5.

:C: ABS\_X\_END=10.

:C: ABS\_Y\_END=10.

:C: MOVE\_TYPE=MLINE

**:C: ADD\_CAD(CURRENT)**

**#2: Example of an current clockwise arc entity**

:SECTION=CALC\_MAIN

:C: ABS\_X\_START=5.

:C: ABS\_Y\_START=5.

:C: ABS\_X\_END=10.

:C: ABS\_Y\_END=10.

:C: ABS\_I\_CENTER=10.

:C: ABS\_J\_CENTER=5.

:C: MOVE\_TYPE=MCW\_ARC

**:C: ADD\_CAD(CURRENT)**

**#3: Example of a previous line entity**

:SECTION=CALC\_MAIN

:C: P\_ABS\_X\_START=5.

:C: P\_ABS\_Y\_START=5.

:C: P\_ABS\_X\_END=10.

:C: P\_ABS\_Y\_END=10.

:C: P\_MOVE\_TYPE=MLINE

**:C: ADD\_CAD(PREVIOUS)**

**#4: Example of a previous clockwise arc entity**

:SECTION=CALC\_MAIN

:C: P\_ABS\_X\_START=5.

:C: P\_ABS\_Y\_START=5.

:C: P\_ABS\_X\_END=10.

:C: P\_ABS\_Y\_END=10.

:C: P\_ABS\_I\_CENTER=10.

:C: P\_ABS\_J\_CENTER=5.

:C: P\_MOVE\_TYPE=MCW\_ARC
## <a name="chmtopic685"></a>**ADD\_PUNCH\_PATH()**
#### **Purpose**
To add a punch path - nibble line or arc.
#### **Syntax**
**:C: ADD\_PUNCH\_PATH(path)**
#### **Comments**
You must set all the system variables first before you add the path in CAM.
#### **Example**
**#1: Example of a line path**

:SECTION=CALC\_MAIN

:C: SELECT\_TOOL(1)

:C: ABS\_X\_START=5.

:C: ABS\_Y\_START=5.

:C: ABS\_X\_END=10.

:C: ABS\_Y\_END=10.

:C: PITCH=.125

:C: MOVE\_TYPE=LINE

**:C: ADD\_PUNCH\_PATH(MLINE)**

**#2: Example of an clockwise arc path**

:SECTION=CALC\_MAIN

:C: SELECT\_TOOL(1)

:C: ABS\_X\_START=5.

:C: ABS\_Y\_START=5.

:C: ABS\_X\_END=10.

:C: ABS\_Y\_END=10.

:C: ABS\_I\_CENTER=10.

:C: ABS\_J\_CENTER=5.

:C: PITCH=.125

:C: MOVE\_TYPE=CW\_ARC

**:C: ADD\_PUNCH\_PATH(MARC)**
## <a name="chmtopic687"></a>**ADD\_PUNCH\_PATTERN()**
#### **Purpose**
To add a punch pattern.
#### **Syntax**
**:C: ADD\_PUNCH\_PATTERN(pattern)**
#### **Comments**
You must set all the system variables first before you add the pattern in CAM.
#### **Examples**
**#1: Example of a grid pattern**

:SECTION=CALC\_MAIN

:C: SELECT\_TOOL(1)

:C: ABS\_X\_START=5.

:C: ABS\_Y\_START=5.

:C: ABS\_X\_END=10.

:C: ABS\_Y\_END=10.

:C: ANGLE=0

:C: NUM\_HITS\_X=5

:C: NUM\_HITS\_Y=5

:C: DIST\_BET\_HOLES\_X=1.

:C: DIST\_BET\_HOLES\_Y=1.

:C: HORIZ\_OR\_VERT=HORIZONTAL

**:C: ADD\_PUNCH\_PATTERN(MGRID)**

**#2: Example of a clockwise arc pattern**

:SECTION=CALC\_MAIN

:C: SELECT\_TOOL(1)

:C: ABS\_X\_START=5.

:C: ABS\_Y\_START=5.

:C: ABS\_X\_END=10.

:C: ABS\_Y\_END=10.

:C: ABS\_I\_CENTER=10.

:C: ABS\_J\_CENTER=5.

:C: NUM\_HITS=5

:C: MOVE\_TYPE=CW\_ARC

**:C: ADD\_PUNCH\_PATTERN(MARC)**



**#3: Example of a counterclockwise bolt circle pattern**

:SECTION=CALC\_MAIN

:C: SELECT\_TOOL(1)

:C: ABS\_X\_START=20.

:C: ABS\_Y\_START=15.

:C: ABS\_X\_END=20.

:C: ABS\_Y\_END=15.

:C: ABS\_I\_CENTER=15.

:C: ABS\_J\_CENTER=15.

:C: NUM\_HITS=8

:C: ARC\_START\_ANGLE=22.5

:C: INC\_ANGLE=45

:C: MOVE\_TYPE=CCW\_ARC

**:C: ADD\_PUNCH\_PATTERN(MCIRCLE)**

**#4: Example of a line at angle pattern**

:SECTION=CALC\_MAIN

:C: SELECT\_TOOL(1)

:C: ABS\_X\_START=5.

:C: ABS\_Y\_START=5.

:C: ABS\_X\_END=10.

:C: ABS\_Y\_END=10.

:C: NUM\_HITS=5

:C: MOVE\_TYPE=LINE

**:C: ADD\_PUNCH\_PATTERN(MLINE)**
## <a name="chmtopic689"></a>**ADD\_PUNCH\_TOOL()**
#### **Purpose**
To add a punch tool in CAM.
#### **Syntax**
**:C: ADD\_PUNCH\_TOOL(tool)**
#### **Comments**
You must set all the system tool variables first before you add the tool in CAM.

TOOL\_TYPE:

|<p>ROUND</p><p>RECTANGLE</p><p>TRIANGLE</p><p>CROSS</p><p>OBROUND</p><p>SQUARE</p><p>RECRAD</p><p>DOUBLED</p><p>SINGLED</p><p>SPETOOL</p>|<p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p>|<p>1</p><p>2</p><p>3</p><p>4</p><p>5</p><p>6</p><p>7</p><p>8</p><p>9</p><p>10</p>|
| :- | :- | :- |
#### **Examples**
**#1**

:SECTION=CALC\_MAIN

:C: TOOL\_TYPE=1

:C: TOOL\_DIAMETER=.5

:C: TOOL\_LOAD\_ANGLE=0

:C: TOOL\_COMMENT={.5 ROUND PUNCH}

:C: TOOL\_DISCRIPTION={ROUND PUNCH}

**:C: ADD\_PUNCH\_TOOL(TOOL)**

**#2**

:SECTION=CALC\_MAIN

:C: TOOL\_TYPE=2

:C: TOOL\_LENGTH=.5

:C: TOOL\_WIDTH=.25

:C: TOOL\_LOAD\_ANGLE=0

:C: TOOL\_COMMENT={.5 x .25 RECTANGLE PUNCH}

:C: TOOL\_DISCRIPTION={RECTANGLE PUNCH}

**:C: ADD\_PUNCH\_TOOL(TOOL)**

**#3**

:SECTION=CALC\_MAIN 

:C: TOOL\_TYPE=7 

:C: TOOL\_LENGTH=.5 

:C: TOOL\_WIDTH=.25 

:C: TOOL\_CORNER\_RADIUS=.01 

:C: TOOL\_LOAD\_ANGLE=0 

:C: TOOL\_COMMENT={.5 x .25 RECTANGLE RADIUS PUNCH} 

:C: TOOL\_DISCRIPTION={RECTANGLE RADIUS PUNCH} 

**:C: ADD\_PUNCH\_TOOL(TOOL)**
## <a name="chmtopic691"></a>**ADD\_REPOSITION()**
#### **Purpose**
To add a reposition in CAM.
#### **Syntax**
**:C: ADD\_REPOSITION()**
#### **Comments**
You must set all the system variables first before you add the reposition in CAM.
#### **Example**
The example below will rapid to "X" and "Y" to ten inches and then reposition the sheet in "X" 20 inches incrementally.

:SECTION=CALC\_MAIN

:C: SELECT\_TOOL(1)

:C: ABS\_X\_END=10.

:C: ABS\_Y\_END=10.

:C: INC\_X\_END=20

**:C: ADD\_REPOSITION()**
## <a name="chmtopic693"></a>**END\_COMPLEX()**
#### **Purpose**
To end a CAM boundary.
#### **Syntax**
**:C: END\_COMPLEX()**
#### **Comments**
This command will end a CAM boundary. Make sure this command is after your last entity in CAD.
#### **Example**
:SECTION=CALC\_MAIN

:C: START\_COMPLEX()

:C: ABS\_X\_START=5.

:C: ABS\_Y\_START=5.

:C: ABS\_X\_END=10.

:C: ABS\_Y\_END=10.

:C: MOVE\_TYPE=MLINE

:C: ADD\_CAD(CURRENT)

**:C: END\_COMPLEX()**
## <a name="chmtopic695"></a>**END\_GROUP()**
#### **Purpose**
To end a group of entities.
#### **Syntax**
**:C: END\_GROUP()**
#### **Comments**
This command will end a group. Make sure this command is after your last entity in CAD.
#### **Example**
:SECTION=CALC\_MAIN

:C: START\_GROUP()

:C: ABS\_X\_START=5.

:C: ABS\_Y\_START=5.

:C: ABS\_X\_END=10.

:C: ABS\_Y\_END=10.

:C: MOVE\_TYPE=MLINE

:C: ADD\_CAD(CURRENT)

**:C: END\_GROUP()**
## <a name="chmtopic697"></a>**GET\_DATA()**
#### **Purpose**
To build popup for attribute list.
#### **Syntax**
**:C: GET\_DATA(listname)**
#### **Comments**
This command will invoke an attribute list for the user to answer in CAD.
#### **Example**
:ATTRNAME=elipse

:ATTRTYPE=LIST

:ATTRSEL=N

:ATTRTITLE=Elipse

:ATTRLIST=major

:ATTRLISTDEF=10

:ATTRLIST=minor

:ATTRLISTDEF=5

:ATTRLIST=nsegments

:ATTRLISTDEF=120

:ATTRUSED=1

:ATTRDEFAULT=1

:ATTREND



:SECTION=CALC\_MAIN

**:C: GET\_DATA(elipse)**
## <a name="chmtopic699"></a>**GET\_POINT()**
#### **Purpose**
To call pick point and return result.
#### **Syntax**
**:C: GET\_POINT()**
#### **Comments**
This command invokes user to snap a point, which will return the result in the system variables ABS\_X\_END and ABS\_Y\_END.
#### **Example**
:SECTION=CALC\_MAIN

**:C: GET\_POINT()**

:C: OFF\_IN\_X=ABS\_X\_END

:C: OFF\_IN\_Y=ABS\_Y\_END
## <a name="chmtopic701"></a>**MAKE\_FILLET()**
#### **Purpose**
To make a fillet between two CAD entities.
#### **Syntax**
**:C: MAKE\_FILLET(radius)**
#### **Comments**
You must set all the system variables first before you make the fillet in CAD.
#### **Example**
:SECTION=CALC\_MAIN

:C: ARC\_RAD(.1)

:C: P\_ABS\_X\_START=5.

:C: P\_ABS\_Y\_START=5.

:C: P\_ABS\_X\_END=10.

:C: P\_ABS\_Y\_END=5.

:C: P\_MOVE\_TYPE=MLINE

:C: N\_ABS\_X\_START=10.

:C: N\_ABS\_Y\_START=5.

:C: N\_ABS\_X\_END=10.

:C: N\_ABS\_Y\_END=10.

:C: N\_MOVE\_TYPE=MLINE

**:C: MAKE\_FILLET(ARC\_RAD)**

:C: ADD\_CAD(PREVIOUS)

:C: ADD\_CAD(CURRENT)

:C: P\_ABS\_X\_START=N\_ABS\_X\_START

:C: P\_ABS\_Y\_START=N\_ABS\_Y\_START

:C: P\_ABS\_X\_END=N\_ABS\_X\_END

:C: P\_ABS\_Y\_END=N\_ABS\_Y\_END

:C: P\_MOVE\_TYPE=N\_MOVE\_TYPE

:C: ADD\_CAD(NEXT)
## <a name="chmtopic703"></a>**SELECT\_TOOL()**
#### **Purpose**
To select a punch tool in CAM.
#### **Syntax**
**:C: SELECT\_TOOL(tool)**
#### **Comments**
If the tool already exists in the part tool list then you can use this command. If the tool does not exist in the current part tool list, you must use the ADD\_PUNCH\_TOOL() command.
#### **Example**
:SECTION=CALC\_MAIN

:C: TOOL=1

**:C: SELECT\_TOOL(TOOL)**
## <a name="chmtopic705"></a>**SET\_COLOR()**
#### **Purpose**
To set current system color in CAD.
#### **Syntax**
**:C: SET\_COLOR(color)**
#### **Comments**
This command sets the system color from 0-15:

|<p>BLACK</p><p>BLUE</p><p>GREEN</p><p>CYAN</p><p>RED</p><p>MAGENTA</p><p>BROWN</p><p>WHITE</p><p>GREY</p><p>LIGHT\_BLUE</p><p>LIGHT\_GREEN</p><p>LIGHT\_CYAN</p><p>LIGHT\_RED</p><p>LIGHT\_MAGENTA</p><p>LIGHT\_YELLOW</p><p>BRIGHT\_WHITE</p>|<p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p>|<p>0</p><p>1</p><p>2</p><p>3</p><p>4</p><p>5</p><p>6</p><p>7</p><p>8</p><p>9</p><p>10</p><p>11</p><p>12</p><p>13</p><p>14</p><p>15</p>|
| :- | :- | :- |
#### **Example**
This example sets the system color to BLUE.

:SECTION=CALC\_MAIN

**:C: SET\_COLOR(1)**
## <a name="chmtopic707"></a>**SET\_LAYER()**
#### **Purpose**
To set current system layer in CAD.
#### **Syntax**
**:C: SET\_LAYER(layer)**
#### **Comments**
This command sets the system layer from 0-256.
#### **Example**
This example sets the system layer to "1".

:SECTION=CALC\_MAIN

**:C: SET\_LAYER(1)**
## <a name="chmtopic709"></a>**SET\_TEXT\_COLOR()**
#### **Purpose**
To set current system text color in CAD.
#### **Syntax**
**:C: SET\_TEXT\_COLOR(color)**
#### **Comments**
This command sets the system text color from 0-15:

|<p>BLACK</p><p>BLUE</p><p>GREEN</p><p>CYAN</p><p>RED</p><p>MAGENTA</p><p>BROWN</p><p>WHITE</p><p>GREY</p><p>LIGHT\_BLUE</p><p>LIGHT\_GREEN</p><p>LIGHT\_CYAN</p><p>LIGHT\_RED</p><p>LIGHT\_MAGENTA</p><p>LIGHT\_YELLOW</p><p>BRIGHT\_WHITE</p>|<p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p><p>=</p>|<p>0</p><p>1</p><p>2</p><p>3</p><p>4</p><p>5</p><p>6</p><p>7</p><p>8</p><p>9</p><p>10</p><p>11</p><p>12</p><p>13</p><p>14</p><p>15</p>|
| :- | :- | :- |
#### **Example**
This example sets the system text color to BLUE.

:SECTION=CALC\_MAIN

**:C: SET\_TEXT\_COLOR(1)**
## <a name="chmtopic711"></a>**START\_COMPLEX()**
#### **Purpose**
To start a CAM boundary.
#### **Syntax**
**:C: START\_COMPLEX()**
#### **Comments**
This command will initiate a CAM boundary. Make sure you use this command before you add your first entity in CAD.
#### **Example**
:SECTION=CALC\_MAIN

**:C: START\_COMPLEX()**

:C: ABS\_X\_START=5.

:C: ABS\_Y\_START=5.

:C: ABS\_X\_END=10.

:C: ABS\_Y\_END=10.

:C: MOVE\_TYPE=MLINE

:C: ADD\_CAD(CURRENT)
## <a name="chmtopic713"></a>**START\_GROUP()**
#### **Purpose**
To start a group of entities.
#### **Syntax**
**:C: START\_GROUP()**
#### **Comments**
This command will initiate a group of entities. Make sure you use this command before you add your first entity in CAD.
#### **Example**
:SECTION=CALC\_MAIN

**:C: START\_GROUP()**

:C: ABS\_X\_START=5.

:C: ABS\_Y\_START=5.

:C: ABS\_X\_END=10.

:C: ABS\_Y\_END=10.

:C: MOVE\_TYPE=MLINE

:C: ADD\_CAD(CURRENT)
## <a name="chmtopic715"></a>**ATTRCFUNC**
#### **Purpose**
Define function to process the attribute.
#### **Syntax**
**:ATTRCFUNC=function**
#### **Comments**
This command allows you to call a section you specify. When this attribute is used, it will first goto the specified function (:SECTION=), then return back to the attribute and output the contents.
#### **Example**
:ATTRNAME=R

:ATTRTYPE=POST

:ATTRVTYPE=DECIMAL

:ATTREMARK=R Radius

:CODETYPE=FORMAT

:ATTRCFUNC=CALC\_RADIUS(R,MACH,REG\_R)

:WORD\_ADDRESS\_BEF=|R

:MODAL=YES

:ATTREND



:SECTION=CALC\_RADIUS(RVAL,MACH,REGISTER)

\*

\* Arc Radius

\*

:C: IF ATTROVERRIDE=YES THEN

:C: RVAL=ATTRDVALUE ELSE RVAL=ARC\_RADIUS ENDIF

:C: SETON ()

:C: MACH(REGISTER)=RVAL

:C: IF ARC\_INC\_ANGLE>HALF\_CIRCLE OR

:C: ARC\_INC\_ANGLE=HALF\_CIRCLE

:C: THEN RVAL=(-MACH(REGISTER)) ENDIF
## <a name="chmtopic717"></a>**ATTRDEFAULT**
#### **Purpose**
Define default for attribute.
#### **Syntax**
**:ATTRDEFAULT=value**
#### **Comments**
This command sets the default value for input. This command overrides ATTRLISTDEF.
#### **Example**
:ATTRNAME=x sheet width

:ATTRTYPE=VALUE

:ATTRVTYPE=DECIMAL

:ATTREMARK=X Sheet Width

:ATTRSEL=N

:ATTRINLEN=10

:ATTRSHORT=X Sheet Width

:ATTRLONG=Enter X Sheet Width

:ATTRHIGH=9999

:ATTRLOW=9999

**:ATTRDEFAULT=0**

:ATTRUSED=1

:ATTREND
## <a name="chmtopic719"></a>**ATTREMARK**
#### **Purpose**
Information for programmer only.
#### **Syntax**
**:ATTREMARK=text**
#### **Comments**
This command allows the programmer to document the attribute for future reference.
#### **Example**
:ATTRNAME=x sheet width

:ATTRTYPE=VALUE

:ATTRVTYPE=DECIMAL

:ATTREMARK=X Sheet Width

:ATTRSEL=N

:ATTRINLEN=10

:ATTRSHORT=X Sheet Width

:ATTRLONG=Enter X Sheet Width

:ATTRHIGH=9999

:ATTRLOW=9999

:ATTRDEFAULT=0

:ATTRUSED=1

:ATTREND
## <a name="chmtopic721"></a>**ATTREND**
#### **Purpose**
Ends an attribute definition.
#### **Syntax**
**:ATTREND**
#### **Comments**
This command ends an attribute definition.
#### **Example**
:ATTRNAME=MACHINE NAME

:ATTRTYPE=DESCRIPTOR

:ATTRVTYPE=CHARACTER

:ATTRID=501

**:ATTREND**
## <a name="chmtopic723"></a>**ATTRFUNC**
#### **Purpose**
Define the function to process the attribute.
#### **Syntax**
**:ATTRFUNC=function**
#### **Comments**
This command allows you to call a section you specify. When this attribute is attached to an entity, it will then goto the specified function (:SECTION=) to output the code.
#### **Example**
In this example, the output is M01.

:ATTRNAME=optional stop

:ATTRTYPE=DISPLAY

:ATTREMARK=Optional Stop M01

:ATTRSEL=Y

:ATTRTEXT=

:ATTRFUNC=optional\_stop

:CODETYPE=HARDCODE

:CODE=|M01

:ATTRUSED=1

:ATTREND



:SECTION=optional\_stop

:T:<optional\_stop>
## <a name="chmtopic725"></a>**ATTRHIGH**
#### **Purpose**
Answer high.
#### **Syntax**
**:ATTRHIGH=value**
#### **Comments**
This command defines the maximum value that can be entered for the attribute. This command is used with value type attributes.
#### **Example**
:ATTRNAME=x sheet width

:ATTRTYPE=VALUE

:ATTRVTYPE=DECIMAL

:ATTREMARK=X Sheet Width

:ATTRSEL=N

:ATTRINLEN=10

:ATTRSHORT=X Sheet Width

:ATTRLONG=ENTER X Sheet Width

**:ATTRHIGH=9999**

:ATTRLOW=9999

:ATTRDEFAULT=0

:ATTRUSED=1

:ATTREND
## <a name="chmtopic727"></a>**ATTRID**
#### **Purpose**
Attribute ID number.
#### **Syntax**
**:ATTRID=501**
#### **Comments**
This command determines the ID number for any attribute that is defined in the MASTER.ATR file.
#### **Example**
:ATTRNAME=MACHINE NAME

:ATTRTYPE=DESCRIPTOR

:ATTRVTYPE=CHARACTER

**:ATTRID=501**

:ATTREND
## <a name="chmtopic729"></a>**ATTRINLEN**
#### **Purpose**
Define input length for attribute.
#### **Syntax**
**:ATTRINLEN=value**
#### **Comments**
This command sets the input length.

For decimal input (3.4), set this value to 10, which includes the decimal point, the + sign and the - sign.

For integers, the length is normally 4.
#### **Example**
:ATTRNAME=x sheet width

:ATTRTYPE=VALUE

:ATTRVTYPE=DECIMAL

:ATTREMARK=X Sheet Width

:ATTRSEL=N

**:ATTRINLEN=10**

:ATTRSHORT=X Sheet Width

:ATTRLONG=Enter X Sheet Width

:ATTRHIGH=9999

:ATTRLOW=9999

:ATTRDEFAULT=0

:ATTRUSED=1

:ATTREND
## <a name="chmtopic731"></a>**ATTRLIST**
#### **Purpose**
List string for list type attribute.
#### **Syntax**
**:ATTRLIST=attribute name**
#### **Comments**
This command allows you to insert a previously defined attribute into a list.
#### **Example**
:ATTRNAME=setup

:ATTRTYPE=LIST

:ATTRSEL=N

:ATTRTITLE=Setup

**:ATTRLIST=program number**

:ATTRLISTDEF=1

**:ATTRLIST=x sheet width**

:ATTRLISTDEF=0

**:ATTRLIST=y sheet width**

:ATTLISTDEF=0

:ATTRUSED=1

:ATTRDEFAULT=1

:ATTREND
## <a name="chmtopic733"></a>**ATTRLISTDEF**
#### **Purpose**
List string default.
#### **Syntax**
**:ATTRLISTDEF=n**
#### **Comments**
This command allows you to set the list default value for a Setup select type attribute.
#### **Example**
:ATTRNAME=setup

**:ATTRTYPE=LIST**

:ATTRSEL=N

:ATTRTITLE=Setup

:ATTRLIST=program number

:ATTRLISTDEF=1

:ATTRLIST=x sheet width

:ATTRLISTDEF=0

:ATTRLIST=y sheet width

:ATTLISTDEF=0

:ATTRUSED=1

:ATTRDEFAULT=1

:ATTREND
## <a name="chmtopic735"></a>**ATTRLNG**
#### **Purpose**
Add attribute to language file.
#### **Syntax**
**ATTRLNG=YES or NO**
#### **Comments**
This command defines whether the attribute will be added to the language file (.LNG) when the post is compiled. The compiler automatically knows which attributes to add to the language file and this command is rarely used.
#### **Example**
:ATTRNAME=R

:ATTRTYPE=POST

:ATTRVTYPE=DECIMAL

:ATTREMARK=R Radius

:CODETYPE=FORMAT

:ATTRCFUNC=CALC\_RADIUS(R,MACH,REG\_R)

:WORD\_ADDRESS\_BEF=|R

**:ATTRLNG=YES**

:MODAL=YES

:ATTREND
## <a name="chmtopic737"></a>**ATTRLONG**
#### **Purpose**
Defines the text that displays on the prompt line for value type attributes.
#### **Syntax**
**:ATTRLONG=text**
#### **Comments**
This command defines the text that displays on the prompt line for value type attributes. When the post is compiled, this text is output to the .LNG file and can be translated if necessary.
#### **Example**
:ATTRNAME=x sheet width

:ATTRTYPE=VALUE

:ATTRVTYPE=DECIMAL

:ATTREMARK=X Sheet Width

:ATTRSEL=N

:ATTRINLEN=10

:ATTRSHORT=X Sheet Width

**:ATTRLONG=ENTER X Sheet Width**

:ATTRHIGH=9999

:ATTRLOW=9999

:ATTRDEFAULT=0

:ATTRUSED=1

:ATTREND
## <a name="chmtopic739"></a>**ATTRLOW**
#### **Purpose**
Answer low.
#### **Syntax**
**:ATTRLOW=value**
#### **Comments**
This command defines the lowest value that can be entered for the attribute. This command is used with value type attributes. If the value type is an integer, you cannot define a negative value. If the value type is decimal, you can define a negative value.
#### **Example**
:ATTRNAME=x sheet width

:ATTRTYPE=VALUE

:ATTRVTYPE=DECIMAL

:ATTREMARK=X Sheet Width

:ATTRSEL=N

:ATTRINLEN=10

:ATTRSHORT=X Sheet Width

:ATTRLONG=ENTER X Sheet Width

:ATTRHIGH=9999

**:ATTRLOW=9999**

:ATTRDEFAULT=0

:ATTRUSED=1

:ATTREND
## <a name="chmtopic741"></a>**ATTRNAME**
#### **Purpose**
Start attribute definition.
#### **Syntax**
**:ATTRNAME=name**
#### **Comments**
This command starts an attribute definition. name identifies the attribute.
#### **Example**
**:ATTRNAME=MACHINE NAME**

:ATTRTYPE=DESCRIPTOR

:ATTRVTYPE=CHARACTER

:ATTRID=501

:ATTREND
## <a name="chmtopic743"></a>**ATTRSEL**
#### **Purpose**
Selectable switch.
#### **Syntax**
**:ATTRSEL=Y or N**
#### **Comments**
This command determines whether an attribute displays in the Select Attribute dialog box or in the Setup Information dialog box. If set to Y (yes), the attribute displays in the Select Attribute dialog box and cannot be listed in the Setup Information dialog box. If set to N (no), the attribute displays in the Setup Information dialog box.
#### **Example**
:ATTRNAME=init machine comp

:ATTRTYPE=SELECT

:ATTREMARK=Comp lft, rgt, cancel

**:ATTRSEL=N**

:ATTRTITLE=Laser Compensation

:ATTRLIST=program number

:ATTRSELSTR=Left

:ATTRSELSTR=Right

:ATTRSELSTR=Cancel

:ATTRDEFAULT=1

:ATTRUSED=1

:ATTREND
## <a name="chmtopic745"></a>**ATTRSELSTR**
#### **Purpose**
Select string for select type.
#### **Syntax**
**:ATTRSELSRT=string**
#### **Comments**
This command is used in select type attributes to specify the choices.
#### **Example**
:ATTRNAME=init machine comp

:ATTRTYPE=SELECT

:ATTREMARK=Comp lft, rgt, cancel

:ATTRSEL=N

:ATTRTITLE=Laser Compensation

:ATTRLIST=program number

**:ATTRSELSTR=Left**

**:ATTRSELSTR=Right**

**:ATTRSELSTR=Cancel**

:ATTRDEFAULT=1

:ATTRUSED=1

:ATTREND
## <a name="chmtopic747"></a>**ATTRSHORT**
#### **Purpose**
Defines the text that displays in the dialog boxes for value type attributes.
#### **Syntax**
**:ATTRSHORT=text**
#### **Comments**
This command defines the text that displays in the dialog box for value type attributes. When the post is compiled, this text is output to the .LNG file and can be translated if necessary.
#### **Example**
:ATTRNAME=x sheet width

:ATTRTYPE=VALUE

:ATTRVTYPE=DECIMAL

:ATTREMARK=X Sheet Width

:ATTRSEL=N

:ATTRINLEN=10

**:ATTRSHORT=X Sheet Width**

:ATTRLONG=ENTER X Sheet Width

:ATTRHIGH=9999

:ATTRLOW=9999

:ATTRDEFAULT=0

:ATTRUSED=1

:ATTREND
## <a name="chmtopic749"></a>**ATTRSPACES**
#### **Purpose**
Code space flag.
#### **Syntax**
**:ATTRSPACES=YES or NO**
#### **Comments**
This command allows spaces in the code output even when the global :SPACE=FALSE is set in the ? file.
#### **Example**
:ATTRNAME=TOOL COMMENT

:ATTRTYPE=POST

:ATTREMARK=

:CODETYPE=FORMAT

:WORD\_ADDRESS\_BEF=|(

:LEFT\_PLACES=0

:RIGHT\_PLACES=0

:UNITFLAG=NON\_CONVERT

**:ATTRSPACES=YES**

:MODAL=YES

:ATTRUSED=1

:ATTREND
## <a name="chmtopic751"></a>**ATTRTEXT**
#### **Purpose**
Text for display type attributes.
#### **Syntax**
**:ATTRTEXT=text**
#### **Comments**
This command defines the text for display type attributes. This command is not used.
#### ** 
## <a name="chmtopic753"></a>**ATTRTITLE**
#### **Purpose**
Text for select type attributes in the Select Attribute dialog box.
#### **Syntax**
**:ATTRTITLE=text**
#### **Comments**
This command defines the text that identifies the attribute in the Select Attribute dialog box.
#### **Example**
:ATTRNAME=init machine comp

:ATTRTYPE=SELECT

:ATTREMARK=Comp Lft, Rgt, Cancel

:ATTRSEL=N

**:ATTRTITLE=Laser Compensation**

:ATTRSELSTR=Left

:ATTRSELSTR=Right

:ATTRSELSTR=Cancel

:ATTRDEFAULT=1

:ATTRUSED=1

:ATTREND
## <a name="chmtopic755"></a>**ATTRTYPE**
#### **Purpose**
Defines attribute type.
#### **Syntax**
**:ATTRTYPE=POST**

**:ATTRTYPE=DESCRIPTOR**

**:ATTRTYPE=VALUE**

**:ATTRTYPE=DISPLAY**

**:ATTRTYPE=SELECT**

**:ATTRTYPE=LIST**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|POST|Defined only in the post and can only be used while posting.|
|DESCRIPTOR|Machine descriptors. These attributes have to be defined in MASTER.ATR and defined in the post.|
|VALUE|Used for Setup and Attachable attributes that require entering a value. These attributes have to be defined in MASTER.ATR and defined in the post.|
|DISPLAY|Used in HARDCODE attributes that are displayed only (they do not require a choice or value). These attributes have to be defined in MASTER.ATR and defined in the post.|
|SELECT|Used for attributes that require selection from a list of choices. These attributes have to be defined in MASTER.ATR if they are to be used for Setup or Attachable type attributes. If used for posting only, then they need to be defined only in the post.|
|LIST|Used for Setup attributes. This has to be the last attribute defined. These attributes have to be defined in MASTER.ATR and defined in the post.|
#### **Example**
:ATTRNAME=x sheet width

**:ATTRTYPE=VALUE**

:ATTRVTYPE=DECIMAL

:ATTREMARK=X Sheet Width

:ATTRSEL=N

:ATTRINLEN=10

:ATTRSHORT=X Sheet Width

:ATTRLONG=Enter X Sheet Width

:ATTRHIGH=9999

:ATTRLOW=9999

:ATTRDEFAULT=0

:ATTRUSED=1

:ATTREND



:ATTRNAME=optional stop

**:ATTRTYPE=DISPLAY**

:ATTREMARK=optional stop M01

:ATTRSEL=Y

:ATTRTEXT=

:ATTRFUNC=optional\_stop

:CODETYPE=HARDCODE

:CODE=|M01

:ATTRUSED=1

:ATTREND



:ATTRNAME=work chute

**:ATTRTYPE=SELECT**

:ATTRVTYPE=INTEGER

:ATTRSEL=Y

:ATTRSHORT=Work Chute

:ATTRTITLE=Work Chute (open/close)

:ATTRSELSTR=M80

:ATTRDEFAULT=1

:ATTRUSED=1

:ATTREND



:ATTRNAME=setup

**:ATTRTYPE=LIST**

:ATTRSEL=N

:ATTRTITLE=Setup

:ATTRLIST=program number

:ATTRLISTDEF=1

:ATTRLIST=x sheet width

:ATTRLISTDEF=0

:ATTRLIST=y sheet width

:ATTLISTDEF=0

:ATTRUSED=1

:ATTRDEFAULT=1

:ATTREND
## <a name="chmtopic757"></a>**ATTRUSED**
#### **Purpose**
Flag for attribute used or not.
#### **Syntax**
**:ATTRUSED=1 or 0**
#### **Comments**
This command tells the compiler if an attribute is used or not. If set to 1, the attribute is included in the compile. If set to 0, the attribute is not compiled.
#### **Example**
:ATTRNAME=init machine comp

:ATTRTYPE=SELECT

:ATTREMARK=Compt lft, rgt, cancel

:ATTRSEL=N

:ATTRTITLE=Laser Compensation

:ATTRLIST=program number

:ATTRSELSTR=Left

:ATTRSELSTR=Right

:ATTRSELSTR=Cancel

:ATTRDEFAULT=1

**:ATTRUSED=1**

:ATTREND
## <a name="chmtopic759"></a>**ATTRVCNT**
#### **Purpose**
Defines attribute as an array.
#### **Syntax**
**:ATTRVCNT=value**
#### **Comments**
This command defines the attribute as an array and the value indicates the size of the array.
#### **Example**
:ATTRNAME=GC

:ATTRTYPE=POST

:ATTRVTYPE=INTEGER

:ATTREMARK=G Codes

:ATTREND
## <a name="chmtopic761"></a>**ATTRVTYPE**
#### **Purpose**
Variable type.
#### **Syntax**
**:ATTRVTYPE=INTEGER**

**:ATTRVTYPE=DECIMAL**

**:ATTRVTYPE=CHARACTER**

**:ATTRVTYPE=FEET**
**\

#### **Comments**
If no ATTRVTYPE is put in the attribute definition, then it assumes it is a character variable type. However if you, you define the attribute with a **:VAR=?** and the **?= another** attribute that has been defined before this one had  ATTRVTYPE defined, then this attribute will be of the same variable type as in the **:VAR=** command.
#### **Example**
:ATTRNAME=x sheet width

:ATTRTYPE=VALUE

**:ATTRVTYPE=DECIMAL**

:ATTREMARK=X Sheet Width

:ATTRSEL=N

:ATTRINLEN=10

:ATTRSHORT=X Sheet Width

:ATTRLONG=Enter X Sheet Width

:ATTRHIGH=9999

:ATTRLOW=9999

:ATTRDEFAULT=0

:ATTRUSED=1

:ATTREND
## <a name="chmtopic763"></a>**CANNOT\_BE\_DECIMAL**
#### **Purpose**
Forces integer output.
#### **Syntax**
**:CANNOT\_BE\_DECIMAL**
#### **Comments**
This command allows you to override the global DECIMAL=TRUE command for this attribute only.
#### **Example**
:ATTRNAME=N

:ATTRTYPE=POST

:ATTRVTYPE=INTEGER

:ATTREMARK=Sequence Number

:CODETYPE=FORMAT

:ATTRCFUNC=CALC\_REG\_N(SEQ,MAX\_SEQUENCE)

:WORD\_ADDRESS\_BEF=N

:VAR=SEQ

:LEFT\_PLACES=4

:RIGHT\_PLACES=0

**:CANNOT\_BE\_DECIMAL**

:UNITFLAG=NON\_CONVERT

:ATTREND
## <a name="chmtopic765"></a>**CANNOT\_BE\_LEADING**
#### **Purpose**
Global leading format flag.
#### **Syntax**
**:CANNOT\_BE\_LEADING**
#### **Comments**
This command allows you to override the global :LEADING=TRUE command for this attribute only. No leading zeros will be output.
#### **Example**
:ATTRNAME=TIME HOURS

:ATTRTYPE=POST

:ATTRVTYPE=INTEGER

:ATTREMARK=Time in Hours

:CODETYPE=FORMAT

:ATTRCFUNC=CALC\_REG\_N(SEQ,MAX\_SEQUENCE)

:WORD\_ADDRESS\_BEF=|ESTIMATED|MACHINE|TIME=

:WORD\_ADDRESS\_AFT=|HRS.||

:LEFT\_PLACES=3

:RIGHT\_PLACES=04

**:CANNOT\_BE\_LEADING**

:UNITFLAG=NON\_CONVERT

:ATTREND
## <a name="chmtopic767"></a>**CANNOT\_BE\_SIGNED**
#### **Purpose**
Signed format definition.
#### **Syntax**
**:CANNOT\_BE\_SIGNED**
#### **Comments**
This command prevents the attribute from outputting a + or - sign to the output field. Only a positive number will be output.
#### **Example**
:ATTRNAME=TIME HOURS

:ATTRTYPE=POST

:ATTRVTYPE=INTEGER

:ATTREMARK=Time in Hours

:CODETYPE=FORMAT

:ATTRCFUNC=CALC\_REG\_N(SEQ,MAX\_SEQUENCE)

:WORD\_ADDRESS\_BEF=|ESTIMATED|MACHINE|TIME=

:WORD\_ADDRESS\_AFT=|HRS.||

:LEFT\_PLACES=3

:RIGHT\_PLACES=04

**:CANNOT\_BE\_SIGNED**

:UNITFLAG=NON\_CONVERT

:ATTREND
## <a name="chmtopic769"></a>**CANNOT\_BE\_TRAILING**
#### **Purpose**
Global trailing format flag.
#### **Syntax**
**:CANNOT\_BE\_TRAILING**
#### **Comments**
This command allows you to override the global :TRAILING=TRUE command for this attribute only. No trailing zeros will be output.
#### **Example**
:ATTRNAME=TIME HOURS

:ATTRTYPE=POST

:ATTRVTYPE=INTEGER

:ATTREMARK=Time in Hours

:CODETYPE=FORMAT

:ATTRCFUNC=CALC\_REG\_N(SEQ,MAX\_SEQUENCE)

:WORD\_ADDRESS\_BEF=|ESTIMATED|MACHINE|TIME=

:WORD\_ADDRESS\_AFT=|HRS.||

:LEFT\_PLACES=3

:RIGHT\_PLACES=04

**:CANNOT\_BE\_TRAILING**

:UNITFLAG=NON\_CONVERT

:ATTREND
## <a name="chmtopic771"></a>**CODE**
#### **Purpose**
Define code for code block.
#### **Syntax**
**:CODE=hardcode**
#### **Comments**
This command allows you to define a constant, not a variable.
#### **Example**
:ATTRNAME=BLOCK DELETE

:ATTRTYPE=POST

:ATTREMARK=

:CODETYPE=HARDCODE

**:CODE=/**

:ATTREND
## <a name="chmtopic773"></a>**CODETYPE**
#### **Purpose**
Define codeblock type.
#### **Syntax**
**:CODETYPE=FORMAT**

**:CODETYPE=SELECT**

**:CODETYPE=SELECT\_FORMAT**

**:CODETYPE=HARDCODE**
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|FORMAT|Defines how you want your output to be|
|SELECT|Defines a selectable output.|
|SELECT\_FORMAT|Defines two variables. The first is a select and the second is a format type.|
|HARDCODE|Defines hardcoded output.|


#### **Example**
:ATTRNAME=F

:ATTRTYPE=POST

:ATTRVTYPE=DECIMAL

:ATTREMARK=Feedrate IPM/MPM

**:CODETYPE=FORMAT**

:ATTRCFUNC=CALC\_REG\_F\_(MACH,REG\_E,F)

:WORD\_ADDRESS\_BEF=|F

:LEFT\_PLACES=3

:RIGHT\_PLACES=4

:CANNOT\_BE\_SIGNED

:MODAL=YES

:ATTREND



:ATTRNAME=DEBUG

:ATTRTYPE=POST

:ATTRVTYPE=INTEGER

:ATTREMARK=Debug

**:CODETYPE=SELECT**

:SELECT=1

:CODE=|||||Line|Move

:SELECT=2

:CPDE=|||||Arc|Move

:ATTRUSED=1

:ATTREND



:ATTRNAME=F

:ATTRTYPE=POST

:ATTRVTYPE=DECIMAL

:ATTREMARK=Feedrate IPM/MPM

**:CODETYPE=SELECT\_FORMAT**

:ATTRCFUNC=CALC\_REG\_F\_(MACH,REG\_E,F)

:VAR=OPR\_FEED\_TYPE

:SELECT=1

:WORD\_ADDRESS\_BEF=|F|

:VARB=F

:LEFT\_PLACES=2

:RIGHT\_PLACES=4

:CANNOT\_BE\_SIGNED

:MODAL=YES

:SELECT=2

:WORD\_ADDRESS\_BEF=|F|

:VARB=F

:LEFT\_PLACES=3

:RIGHT\_PLACES=2

:CANNOT\_BE\_SIGNED

:MODAL=YES

:ATTREND



:ATTRNAME=BLOCK DELETE

:ATTRTYPE=POST

:ATTREMARK=

**:CODETYPE=HARDCODE**

:CODE=/

:ATTREND
## <a name="chmtopic775"></a>**COLUMN**
#### **Purpose**
Position of code output.
#### **Syntax**
**:COLUMN=value**
#### **Comments**
This command determines the position of the code output. :COLUMN=9 positions the output in the 10th place from the left. This command is used for some older controllers that require fielded output where every space means something.
#### **Example**
:ATTRNAME=S

:ATTRTYPE=POST

:ATTRVTYPE=INTEGER

:ATTREMARK=Spindle RPM

:CODETYPE=FORMAT

:ATTRCFUNC=CALC\_INT\_REGISTER(S,MACH,OPR\_SPEED,REG\_S)

:WORD\_ADDRESS\_BEF=SP=

:WORD\_ADDRESS\_AFT=|RPM

:LEFT\_PLACES=4

:RIGHT\_PLACES=0

:COLUMN=9

:RIGHT\_JUST=4

:ATTREND



N001 S1000
## <a name="chmtopic777"></a>**LEFT\_JUST**
#### **Purpose**
Left justification of the code output.
#### **Syntax**
**:LEFT\_JUST=value**
#### **Comments**
This command determines the position of the code output from where you were last, starting from the left.
#### **Example**
:ATTRNAME=S

:ATTRTYPE=POST

:ATTRVTYPE=INTEGER

:ATTREMARK=Spindle RPM

:CODETYPE=FORMAT

:ATTRCFUNC=CALC\_INT\_REGISTER(S,MACH,OPR\_SPEED,REG\_S)

:WORD\_ADDRESS\_BEF=SP=

:WORD\_ADDRESS\_AFT=|RPM

:LEFT\_PLACES=4

:RIGHT\_PLACES=0

**:LEFT\_JUST=7**

:ATTREND





N001S1000 M03
## <a name="chmtopic779"></a>**LEFT\_PLACES**
#### **Purpose**
Number of places to the left of the implied decimal.
#### **Syntax**
**:LEFT\_PLACES=value**
#### **Comments**
This command allows you to override the global G\_LEFT\_PLACES command for this attribute only.
#### **Example**
:ATTRNAME=F

:ATTRTYPE=POST

:ATTRVTYPE=DECIMAL

:ATTREMARK=Feedrate IPM/MPM

:CODETYPE=FORMAT

:ATTRCFUNC=CALC\_REG\_F\_(MACH,REG\_E,F)

:WORD\_ADDRESS\_BEF=|F

**:LEFT\_PLACES=3**

:RIGHT\_PLACES=4

:CANNOT\_BE\_SIGNED

:MODAL=YES

:ATTREND
## <a name="chmtopic781"></a>**METRIC\_UNITS**
#### **Purpose**
Metric unit definition.
#### **Syntax**
**:METRIC\_UNITS=MM**

**:METRIC\_UNITS=CM**

**:METRIC\_UNITS=M**
#### **Comments**
This command converts the output to always be whatever METRIC-UNITS is set to: MM (millimeters), CM (centimeters) or M (meters). The default is MM (millimeters). Some controllers may require a different metric unit.
#### **Example**
:ATTRNAME=REDUCED FEED

:ATTRTYPE=POST

:ATTRVTYPE=DECIMAL

:ATTREMARK=Reduced feed rate

:CODETYPE=FORMAT

:WORD\_ADDRESS\_BEF=|F

:VAR=REDUCED FEED

:LEFT\_PLACES=4

:RIGHT\_PLACES=0

:MODAL=YES

:CANNOT\_BE\_SIGNED

:CANNOT\_BE\_DECIMAL

:MUST\_BE\_TRAILING

**:METRIC\_UNITS=M**

:ATTREND
## <a name="chmtopic783"></a>**MODAL**
#### **Purpose**
Modality for code block.
#### **Syntax**
**:MODAL=YES or NO**
#### **Comments**
If MODAL=YES, then the attribute does not get output to the output file again until the attribute's value changes.

MODAL=NO forces the attribute to be output to the output file. If this command is not used, the default is NO.
#### **Example**
:ATTRNAME=F

:ATTRTYPE=POST

:ATTRVTYPE=DECIMAL

:ATTREMARK=Feedrate IPM/MPM

:CODETYPE=FORMAT

:ATTRCFUNC=CALC\_REG\_F\_(MACH,REG\_E,F)

:WORD\_ADDRESS\_BEF=|F

:LEFT\_PLACES=3

:RIGHT\_PLACES=4

:MUST\_BE\_SIGNED

**:MODAL=YES**

:ATTREND
## <a name="chmtopic785"></a>**MUST\_BE\_DECIMAL**
#### **Purpose**
Global decimal format flag.
#### **Syntax**
**:MUST\_BE\_DECIMAL**
#### **Comments**
This command sets the output to always have a decimal even if the output equals zero.
#### **Example**
:ATTRNAME=F

:ATTRTYPE=POST

:ATTRVTYPE=DECIMAL

:ATTREMARK=Feedrate IPM/MPM

:CODETYPE=FORMAT

:ATTRCFUNC=CALC\_REG\_F\_(MACH,REG\_E,F)

:WORD\_ADDRESS\_BEF=|F

:LEFT\_PLACES=3

:RIGHT\_PLACES=4

**:MUST\_BE\_DECIMAL**

:MODAL=YES

:ATTREND
## <a name="chmtopic787"></a>**MUST\_BE\_LEADING**
#### **Purpose**
Global leading format flag.
#### **Syntax**
**:MUST\_BE\_LEADING**
#### **Comments**
This command overrides the global :LEADING=FALSE command and always outputs leading zeros.
#### **Example**
:ATTRNAME=F

:ATTRTYPE=POST

:ATTRVTYPE=DECIMAL

:ATTREMARK=Feedrate IPM/MPM

:CODETYPE=FORMAT

:ATTRCFUNC=CALC\_REG\_F\_(MACH,REG\_E,F)

:WORD\_ADDRESS\_BEF=|F

:LEFT\_PLACES=3

:RIGHT\_PLACES=4

**:MUST\_BE\_LEADING**

:MODAL=YES

:ATTREND
## <a name="chmtopic74"></a>**:MUST\_BE\_LOWERCASE**

#### **Example:**
:ATTRNAME=OPR COMMENT

:ATTRTYPE=POST

:ATTREMARK=

:CODETYPE=FORMAT

:WORD\_ADDRESS\_BEF=|(

:VAR=OPR COMMENT

:WORD\_ADDRESS\_AFT=)

:LEFT\_PLACES=0

:RIGHT\_PLACES=0

:UNITFLAG=NON\_CONVERT

:ATTRSPACES=YES

:MODAL=NO

**:MUST\_BE\_LOWERCASE**

:ATTRUSED=1

:ATTREND
## <a name="chmtopic790"></a>**MUST\_BE\_SIGNED**
#### **Purpose**
Signed format definition.
#### **Syntax**
**:MUST\_BE\_SIGNED**
#### **Comments**
This command forces the attribute to output a + or - sign to the output file.
#### **Example**
:ATTRNAME=F

:ATTRTYPE=POST

:ATTRVTYPE=DECIMAL

:ATTREMARK=Feedrate IPM/MPM

:CODETYPE=FORMAT

:ATTRCFUNC=CALC\_REG\_F\_(MACH,REG\_E,F)

:WORD\_ADDRESS\_BEF=|F

:LEFT\_PLACES=3

:RIGHT\_PLACES=4

**:MUST\_BE\_SIGNED**

:MODAL=YES

:ATTREND
## <a name="chmtopic792"></a>**MUST\_BE\_TRAILING**
#### **Purpose**
Global trailing format flag.
#### **Syntax**
**:MUST\_BE\_TRAILING**
#### **Comments**
This command overrides the global :TRAILING=FALSE command and always outputs trailing zeros.
#### **Example**
:ATTRNAME=F

:ATTRTYPE=POST

:ATTRVTYPE=DECIMAL

:ATTREMARK=Feedrate IPM/MPM

:CODETYPE=FORMAT

:ATTRCFUNC=CALC\_REG\_F\_(MACH,REG\_E,F)

:WORD\_ADDRESS\_BEF=|F

:LEFT\_PLACES=3

:RIGHT\_PLACES=4

**:MUST\_BE\_TRAILING**

:MODAL=YES

:ATTREND
## <a name="chmtopic794"></a>**MUST\_BE\_LEADING\_SPACES**
#### **Purpose**
Global leading spaces format flag.
#### **Syntax**
**:MUST\_BE\_LEADING\_SPACES**
#### **Comments**
This command forces leading spaces in the output file.

If G\_LEFT\_SPACES=3 and the number you output is -1., then you get a minus sign, one space, then 1. (- 1.). If the number output is 1., you will get two spaces, then 1. ( 1.).

This command can be used for controllers where each space means something.
## <a name="chmtopic75"></a>**:MUST\_BE\_UPPERCASE**

#### **Example**
:ATTRNAME=OPR COMMENT

:ATTRTYPE=POST

:ATTREMARK=

:CODETYPE=FORMAT

:WORD\_ADDRESS\_BEF=|(

:VAR=OPR COMMENT

:WORD\_ADDRESS\_AFT=)

:LEFT\_PLACES=0

:RIGHT\_PLACES=0

:UNITFLAG=NON\_CONVERT

:ATTRSPACES=YES

:MODAL=NO

**:MUST\_BE\_UPPERCASE**

:ATTRUSED=1

:ATTREND


## <a name="chmtopic797"></a>**MUST\_BE\_TRAILING\_SPACES**
#### **Purpose**
Global trailing spaces format flag.
#### **Syntax**
**:MUST\_BE\_TRAILING\_SPACES**
#### **Comments**
This command forces trailing spaces in the output file.

If G\_RIGHT\_SPACES=4 and the number you output is -1., then you get a minus sign, 1., then four spaces (-.1 ). If the number output is 1.1, you will get the number and three spaces, then 1. (1.1 ).
## <a name="chmtopic68"></a>**QUERY\_SW\_FIELD\_NAME**
#### **Purpose**
Indicates the name of the field within SOLIDWORKS Custom Properties. 


#### **Example**
:ATTRNAME=QUERY SW FIELD NAME

:ATTRTYPE=POST

:ATTREMARK=

:CODETYPE=FORMAT

:WORD\_ADDRESS\_BEF=|

:VAR=QUERY\_SW\_FIELD\_NAME

:WORD\_ADDRESS\_AFT=|:

:LEFT\_PLACES=0

:RIGHT\_PLACES=0

:UNITFLAG=NON\_CONVERT

:ATTRSPACES=YES

:MODAL=NO

:ATTRUSED=1

:ATTREND
## <a name="chmtopic69"></a>**QUERY\_SW\_FIELD\_TYPE**
#### **Purpose**
If a SW Field ID is found on executing the [GET_SW_SUMMARY_INFO_BY_ID](#chmtopic14)(SW\_FIELD\_ID, CALC\_?????) command, the system will query the result and store the filed type in an integer parameter named QUERY\_SW\_FIELD\_TYPE. This attribute parameter indicates the type of field found. 

- If the field type is a SW\_NUMBER, the system will store the field integer value in QUERY\_INT\_VAL. 
- If the field type is a SW\_DECIMAL, the system will store the field double value in QUERY\_DEC\_VAL. 


#### **Constants**
Constants for the QUERY\_SW\_FIELD\_TYPE:

- SW\_UNKNOWN
- SW\_NUMBER
- SW\_DOUBLE
- SW\_YES\_NO
- SW\_TEXT
- SW\_DATE
## <a name="chmtopic70"></a>**QUERY\_SW\_FIELD\_VAL**
#### **Purpose**
Indicates the character string value in the field within SOLIDWORKS Custom Properties. 


#### **Example**
:ATTRNAME=QUERY SW FIELD VAL

:ATTRTYPE=POST

:ATTREMARK=

:CODETYPE=FORMAT

:WORD\_ADDRESS\_BEF=|

:VAR=QUERY\_SW\_FIELD\_VAL

:WORD\_ADDRESS\_AFT=

:LEFT\_PLACES=0

:RIGHT\_PLACES=0

:UNITFLAG=NON\_CONVERT

:ATTRSPACES=YES

:MODAL=NO

:ATTRUSED=1

:ATTREND 


## <a name="chmtopic802"></a>**RIGHT\_JUST**
#### **Purpose**
Right justification of the code output.
#### **Syntax**
**:RIGHT\_JUST=value**
#### **Comments**
This command determines the position of the code output from where you were last, starting from the right.
#### **Example**
:ATTRNAME=S

:ATTRTYPE=POST

:ATTRVTYPE=INTEGER

:ATTREMARK=Spindle RPM

:CODETYPE=FORMAT

:ATTRCFUNC=CALC\_INT\_REGISTER(S,MACH,OPR\_SPEED,REG\_S)

:WORD\_ADDRESS\_BEF=SP=

:WORD\_ADDRESS\_AFT=|RPM

:LEFT\_PLACES=4

:RIGHT\_PLACES=0

**:RIGHT\_JUST=7**

:ATTREND





N001 S1000M03
## <a name="chmtopic804"></a>**RIGHT\_PLACES**
#### **Purpose**
Number of places to the right of the implied decimal.
#### **Syntax**
**:RIGHT\_PLACES=value**
#### **Comments**
This command allows you to override the global G\_RIGHT\_PLACES command for this attribute only.
#### **Example**
:ATTRNAME=F

:ATTRTYPE=POST

:ATTRVTYPE=DECIMAL

:ATTREMARK=Feedrate IPM/MPM

:CODETYPE=FORMAT

:ATTRCFUNC=CALC\_REG\_F(MACH,REG\_E,F)

:WORD\_ADDRESS\_BEF=|F

:LEFT\_PLACES=3

**:RIGHT\_PLACES=4**

:CANNOT\_BE\_SIGNED

:MODAL=YES

:ATTREND
## <a name="chmtopic806"></a>**SELECT**
#### **Purpose**
First value for codeblock.
#### **Syntax**
**:SELECT=text**
#### **Comments**
This command allows you have hardcoded selectable output.
#### **Example**
:ATTRNAME=G CODE

:ATTRTYPE=POST

:ATTREMARK=G code parameters

:CODETYPE=SELECT

:VAR=MOVE TYPE

**:SELECT=LINE**

:CODE=|G01

:MODAL=YES

**:SELECT=CW ARC**

:CODE=|G02

:MODAL=YES

**:SELECT=CCW ARC**

:CODE=|G03

:MODAL=YES

**:SELECT=RAPID**

:CODE=|G00

:MODAL=YES

:ATTREND
## <a name="chmtopic808"></a>**UNITFLAG**
#### **Purpose**
Global English/Metric definition.
#### **Syntax**
**:UNITFLAG=CONVERT or NON\_CONVERT**
#### **Comments**
The default for this command is CONVERT. If the part is saved as metric, then the output will be converted to metric. If set to NON\_CONVERT, then the output will always be in inches.
#### **Example**
:ATTRNAME=TIME HOURS

:ATTRTYPE=POST

:ATTRVTYPE=INTEGER

:ATTREMARK=Time in Hours

:CODETYPE=FORMAT

:ATTRCFUNC=CALC\_REG\_N(SEQ,MAX\_SEQUENCE)

:WORD\_ADDRESS\_BEF=|ESTIMATED|MACHINE|TIME=

:WORD\_ADDRESS\_AFT=|HRS.||

:LEFT\_PLACES=3

:RIGHT\_PLACES=04

:CANNOT\_BE\_SIGNED

**:UNITFLAG=NON\_CONVERT**

:ATTREND
## <a name="chmtopic810"></a>**VAR**
#### **Purpose**
First variable for code block.
#### **Syntax**
**:VAR=variable**
#### **Comments**
This command defines the first variable in a :CODETYPE=SELECT\_FORMAT type attribute.
#### **Example**
:ATTRNAME=X

:ATTRTYPE=POST

:ATTRVTYPE=DECIMAL

:ATTREMARK=X End

:CODETYPE=SELECT\_FORMAT

:ATTRCFUNC=CALC\_ENDPOINT(X,Y\_POS,GC,GG,G\_GROUP,MACH,PREV,REG\_X,\
RAD\_OR\_DIAM,SX)

**:VAR=CURRENT\_MODE**

:SELECT=1

:WORD\_ADDRESS\_BEF=|X

:VERB=X

:MODAL=YES

:SELECT=2

:WORD\_ADDRESS\_BEF=|U

:VERB=X

:CODE=|G03

:MODAL=YES

:ATTREND
## <a name="chmtopic812"></a>**VARB**
#### **Purpose**
Second variable for code block.
#### **Syntax**
**:VARB=variable**
#### **Comments**
This command defines the second variable in a :CODETYPE=SELECT\_FORMAT type attribute.
#### **Example**
:ATTRNAME=X

:ATTRTYPE=POST

:ATTRVTYPE=DECIMAL

:ATTREMARK=X End

:CODETYPE=SELECT\_FORMAT

:ATTRCFUNC=CALC\_ENDPOINT(X,Y\_POS,GC,GG,G\_GROUP,MACH,PREV,REG\_X,\
RAD\_OR\_DIAM,SX)

:VAR=CURRENT\_MODE

:SELECT=1

:WORD\_ADDRESS\_BEF=|X

**:VERB=X**

:MODAL=YES

:SELECT=2

:WORD\_ADDRESS\_BEF=|U

**:VERB=X**

:CODE=|G03

:MODAL=YES

:ATTREND
## <a name="chmtopic814"></a>**WORD\_ADDRESS\_AFT**
#### **Purpose**
Word address after variable.
#### **Syntax**
**:WORD\_ADDRESS\_BEF=output**
#### **Comments**
This command allows you to define what to output in a FORMAT type attribute after the number has been output. Use the pipe (|) to put a space in the output.
#### **Example**
:ATTRNAME=PART NAME

:ATTRTYPE=POST

:ATTREMARK=

:CODETYPE=FORMAT

:WORD\_ADDRESS\_BEF=|(|PART|NAME=

:CAR=PART NAME

**:WORD\_ADDRESS\_AFT=|)**

:LEFT\_PLACES=0

:RIGHT\_PLACES=0

:UNITFLAG=NON\_CONVERT

:ATTRUSED=1

:ATTREND
## <a name="chmtopic816"></a>**WORD\_ADDRESS\_BEF**
#### **Purpose**
Word address before variable.
#### **Syntax**
**:WORD\_ADDRESS\_BEF=output**
#### **Comments**
This command allows you to define what to output in a FORMAT type attribute before the number has been output. Use the pipe (|) to put a space in the output.
#### **Example**
:ATTRNAME=PART NAME

:ATTRTYPE=POST

:ATTREMARK=

:CODETYPE=FORMAT

**:WORD\_ADDRESS\_BEF=|(|PART|NAME=**

:CAR=PART NAME

:WORD\_ADDRESS\_AFT=|)

:LEFT\_PLACES=0

:RIGHT\_PLACES=0

:UNITFLAG=NON\_CONVERT

:ATTRUSED=1

:ATTREND
## <a name="chmtopic818"></a>**ATTRID**
#### **Purpose**
Attribute ID number.
#### **Syntax**
**:ATTRID=501**
#### **Comments**
This command determines the ID number for any attribute that is defined in the MASTER.ATR file.
#### **Example**
:ATTRNAME=MACHINE NAME

:ATTRTYPE=DESCRIPTOR

:ATTRVTYPE=CHARACTER

**:ATTRID=501**

:ATTREND
## <a name="chmtopic820"></a>**ATTRMACHINE**
#### **Purpose**
Set of machine-dependent attributes.
#### **Syntax**
**:ATTRMACHINE=PUNCH**
#### **Comments**
After this command is put in the post, any attachable attribute that is defined after it will be assumed to be the system you entered in this command.
#### **Example**
None.
## <a name="chmtopic822"></a>**CALC\_ALLOW\_RAPID\_DURING\_DRILL**
#### **Purpose**
This system section will be called in a mill drilling cycle and handles posted output of toolpath editing in drilling cycles. This section is for allowing rapids in drilling cycles.
#### **Syntax**
**:SECTION=CALC\_ALLOW\_RAPID\_DURING\_DRILL**
#### **Comments**
This section will looks for a post variable called RAPID\_DURING\_DRILL\_CYCLE. The post will set this to a TRUE or FALSE value. If the post does not have this section or variable, then the posting system assumes a FALSE value. When the value is set to TRUE, then the system assumes that the post can support rapids in a drilling cycle that are added in the Edit toolpath area of CAMWorks.

The drilling cycles were designed in a specific way and when you add rapids to the toolpath, you may get unwanted results. You can adjust the drilling cycles in new posts if needed and set RAPID\_DURING=1. The default is handled by not having or setting RAPID\_DURING=0. Older posts do not have RAPID\_DURING compiled in the source, so in that case the default will be zero.

Supported in CAMWorks 2007 and later. Not supported in any ProCAM product.
#### **Example**
:SECTION=CALC\_ALLOW\_RAPID\_DURING\_DRILL

:C: IF CAMWORKS\_VER>CAM\_REV2006EX THEN

:C: IF RAPID\_DURING=1 THEN

:C: RAPID\_DURING\_DRILL\_CYCLE=TRUE

:C: ENDIF

:C: ENDIF


## <a name="chmtopic824"></a>**CALC\_CUTTER\_COMP\_LATHE**
#### **Purpose**
This system section will be called in a lathe finish grooving cycle if a shift from one side of the groove tool to the opposite side is detected. This will support machine cutter comp values.
#### **Syntax**
**:SECTION=CALC\_CUTTER\_COMP\_LATHE**
#### **Comments**
Supported in CAMWorks 2007 and later. Not supported in any ProCAM product.

These sections need to be added to the \*.src file: LINE\_LEADIN\_MOVE\_LATHE and LINE\_LEADOUT\_MOVE\_LATHE.



:SECTION=CALC\_CUTTER\_COMP\_LATHE

:SECTION: LINE\_LEADIN\_MOVE\_LATHE

:SECTION: LINE\_LEADOUT\_MOVE\_LATHE
## <a name="chmtopic826"></a>**DEFINE**
#### **Purpose**
Hardcoded definitions.
#### **Syntax**
**:DEFINE RAPID\_Z\_UP=8**
#### **Comments**
This command sets a define variable equal to a value. In the example below RAPID\_Z\_UP=8 sets the value to eight. This command needs to be set at the beginning of the attribute list in the library.
#### **Example**
:DEFINE RAPID\_Z\_UP=8
## <a name="chmtopic453"></a>**FLAGGED(variable, bit value)**
#### **Purpose**
This command is used in the CAMWorks Turn system only for the first approach and last retract moves of an operation. It stores multiple bits of information about those moves and depending on the flag it is looking for it will pass a True or False value.
#### **Syntax**
**FLAGGED(CAM\_MOVE\_FLAG, CAM\_APPROACH)**
#### **Comments**
CAM\_MOVE\_FLAG is a multiple bit variable and CAM\_APPROACH is the value it will look for. The bit value of CAM\_APPROACH is 2. What the command FLAGGED is going to return is a True or False value. In the CAM\_MOVE\_FLAG variable is CAM\_APPROACH’s bit value equal to True or False.
#### **Example**
:C: IF **FLAGGED(**CAM\_MOVE\_FLAG,CAM\_APPROACH**)**=TRUE THEN

:C: IF **FLAGGED(**CAM\_MOVE\_FLAG, CAM\_MOVE\_X**)**=TRUE AND

:C: **FLAGGED(**CAM\_MOVE\_FLAG, CAM\_MOVE\_Z**)**=TRUE THEN

:C: CALL(RAPID\_MOVE\_LATHE)

:C: RETURN

:C: ELSE

:C: IF **FLAGGED(**CAM\_MOVE\_FLAG,CAM\_MOVE\_X**)**=TRUE THEN

:C: CALL(RAPID\_MOVE\_LATHE\_X)

:C: RETURN

:C: ELSE

:C: IF **FLAGGED(**CAM\_MOVE\_FLAG,CAM\_MOVE\_Z**)**=TRUE THEN

:C: CALL(RAPID\_MOVE\_LATHE\_Z)

:C: RETURN

:C: ENDIF

:C: ENDIF

:C: ENDIF
## <a name="chmtopic119"></a>**FLUSH\_ALL\_SYNC\_CODES()**

#### **Purpose**
To find any sync codes that have not been output in all multiple turrets.
#### **Syntax**
This logic would normally be used in CALC\_END\_OF\_TAPE just before calling end of tape output in all turret files.



:C: FLUSH\_ALL\_SYNC\_CODES()
#### **Example**
:SECTION=CALC\_END\_OF\_TAPE

:C: FLUSH\_ALL\_SYNC\_CODES()
## <a name="chmtopic279"></a>**FLUSH\_SYNC\_CODES**
#### **Purpose**
Can be used with any post that users sync codes.
#### **Syntax**
**FLUSH\_SYNC\_CODES(REAR)**

**FLUSH\_SYNC\_CODES(FRONT)**
#### **Comments**
You would use this command in CALC\_END\_OF\_TAPE. to be used in CAMWorks 2014 or newer version.
## <a name="chmtopic831"></a>**IDHIGH**
#### **Purpose**
Highest attribute ID in MASTER.ATR file.
#### **Syntax**
**:IDHIGH=17501**
#### **Comments**
This command determines the highest ID number used in the MASTER.ATR file. This command should be put at the beginning of the MASTER.ATR file.
#### **Example**
None.
## <a name="chmtopic833"></a>**INCLUDE**
#### **Purpose**
Include definition.
#### **Syntax**
**:INCLUDE=\MILL\TOOLS\GENERAL.T32**
#### **Comments**
This command defines the name and location of another file to be used when compiling.
#### **Example**
:INCLUDE=\MILL\TOOLS\GENERAL.T32
## <a name="chmtopic247"></a>**LATHE\_OPER\_SETUP**

#### **Usage**
Creates post questions per setup. To be used in CAMWorks 2015 SP0 or newer versions.
#### ** 
#### **Example**
:OPERID=LATHE\_OPER\_SETUP

:OPERLIST=abs inc

:OPEREND
## <a name="chmtopic836"></a>**LIBRARY**
#### **Purpose**
Library definition.
#### **Syntax**
**:LIBRARY=\MILL\LIBRARY\GENERAL.LIB**
#### **Comments**
This command defines the name and location of the post library. The example below shows that the GENERAL.LIB file is located in the \MILL\LIBRARY directory.
#### **Example**
:LIBRARY=\MILL\LIBRARY\GENERAL.LIB
## <a name="chmtopic246"></a>**MILL\_OPER\_SETUP**
#### ** 
#### **Usage**
Creates post questions per setup. To be used in CAMWorks 2015 SP0 or newer versions.
#### ** 
#### **Example**
:OPERID=MILL\_OPER\_SETUP

:OPERLIST=abs inc

:OPEREND
## <a name="chmtopic130"></a> **: “.\” or “..\”**
#### **Purpose**
This compiler command makes defining the path for either the LIBRARY or INCLUDE easier as it is taken from where the SRC is located so you do not have to specify the drive letter.
#### **Notes**
When UPG saves source files it will automatically save the post LIB file in the same directory as the source file (SRC). The LIBRARY command will then insert “.\” in front of the post lib name “:LIBRARY=.\?????.lib”. This will work for any version of CAMWorks as long as the  “loadfdll.dll” file  used is dated 1<sup>st</sup> November, 2017 or later.


#### **Comments and Examples**
These examples are showing where the MILL.LIB might be from where the SRC file is located.
#### **Example 1:**
**I**n this example, the ".\" File location is the same location as the SRC.

|Location of SRC File|C:\CAMworksData\UPG|
| :- | :- |
|Actual Location|:LIBRARY=C:\CAMworksData\UPG\Mill.LIB|
|Using this Command|:LIBRARY=.\Mill.LIB|


#### ` `**Example 2:**
In this example, "..\" File location is one directory level above the SRC.

|Location of SRC File|C:\CAMworksData\UPG\MillSourceTemplates|
| :- | :- |
|Actual Location|:LIBRARY=C:\CAMworksData\UPG\Mill.LIB |
|Using this Command|:LIBRARY=..\Mill.LIB|
#### **Example 3:**
In this example, the location is the one directory level above the SRC but inside a sub folder.

|Location of SRC File|C:\CAMworksData\UPG\MillSourceTemplates |
| :- | :- |
|Actual Location|<p>:LIBRARY=C:\CAMworksData\UPG\MasterLibraryFiles\</p><p>Mill.LIB</p><p> </p>|
|Using this Command|:LIBRARY=..\MasterLibraryFiles\Mill.LIB |
#### **Example 4:**
In this example, the location is two directory level above the SRC but inside a sub folder.

|Location of SRC File|<p> </p><p>C:\CAMworksData\UPG\Template\MillSourceTemplates</p><p> </p>|
| :- | :- |
|Actual Location|<p>:LIBRARY=C:\CAMworksData\UPG\MasterLibraryFiles\</p><p>Mill.LIB</p><p> </p>|
|Using this Command|:LIBRARY=..\..\MasterLibraryFiles\Mill.LIB|
#### **Example 5:**
If saving source from the Universal Post Generator (UPG) which is not under the default UPG installed file structure,

then the file saving path that UPG will follow is illustrated in the below example using  the MILL.LIB file.



|Location of SRC File|C:\test\test2|
| :- | :- |
|Actual Location|<p>:LIBRARY=C:\CAMworksData\UPG\MasterLibraryFiles\</p><p>Mill.LIB</p>|
|Using this Command|<p>:LIBRARY=..\..\CAMWorksData\UPG\MasterLibraryFiles\Mill.LIB  </p><p> </p>|


## <a name="chmtopic840"></a>**OPEREND**
#### **Purpose**
Mill and Lathe operation definition end.
#### **Syntax**
**:OPEREND**
#### **Comments**
This command determines the end of an operation questions.
#### **Example**
:OPERID=MILL\_PROFILING

:OPERLIST=machine compensation

:OPERLIST=abs inc

:OPERLIST=work coord

:OPERLIST=coolant

**:OPEREND**
## <a name="chmtopic842"></a>**OPERID**
#### **Purpose**
Mill and Lathe operation ID name.
#### **Syntax**
**:OPERID=MILL\_PROFILING**
#### **Comments**
This command determines the name of an operation ID. Any OPERLIST question asked after this command will be added to the operation questions in CAD.

Operation List:

|<p>DRILLING</p><p>SPOT\_DRILLING</p><p>PECKING</p><p>TAPPING</p><p>BORING</p><p>HIGH\_SPEED\_PECKING</p><p>VARIABLE\_PECKING</p><p>REVERSE\_TAPPING</p><p>REAMING</p><p>REAMING\_DWELL</p><p>BORE\_DWELL</p><p>BACK\_BORING</p><p>FINE\_BORING</p>|<p>MILL\_DRILLING</p><p>MILL\_PROFILING</p><p>MILL\_LACE</p><p>MILL\_POCKET</p><p>MILL\_MISC</p><p>MILL\_SPECIAL</p><p>MILL\_MACRO</p><p>MILL\_UV\_CUT</p><p>MILL\_SLICE\_CUT</p><p>MILL\_ROUGH\_CUT</p><p>MILL\_CURVE\_CUT</p><p>MILL\_TOPO\_CUT</p><p>MILL\_FREEFORM\_CUT</p><p>MILL\_PENCIL\_CUT</p><p>MILL\_OPER\_SETUP</p>|<p>LATHE\_DRILLING</p><p>LATHE\_PROFILING</p><p>LATHE\_ROUGHING</p><p>LATHE\_GROOVING</p><p>LATHE\_THREADING</p><p>LATHE\_MISC</p><p>LATHE\_SPECIAL</p><p>LATHE\_CUTOFF</p><p>LATHE\_OPER\_SETUP</p>|<p>EDM\_PROFILE</p><p>EDM\_SKIM</p><p>EDM\_CORE</p><p>EDM\_MACROS</p><p> </p>|
| :- | :- | :- | :- |
#### **Example**
**:OPERID=MILL\_PROFILING**

:OPERLIST=machine compensation

:OPERLIST=abs inc

:OPERLIST=work coord

:OPERLIST=coolant

:OPEREND
## <a name="chmtopic844"></a>**:OPERID**
#### **Purpose**
EDM operations ID names.
#### **Syntax**

|***Syntax***|***Purpose***|
| :- | :- |
|<p>**:OPERID=EDM\_PROFILE**</p><p> </p>|EDM operation ID for creating an EDM Profile operation.|
|**:OPERID=EDM\_SKIM**|EDM operation ID for creating an EDM Skimcut operation. This operid was added when operations were added to the ProCAM 2d EDM system.|
|**:OPERID=EDM\_CORE**|EDM operation ID for creating an EDM core removal operation. This operid was added when operations were added to the ProCAM 2d EDM system.|
|**:OPERID=EDM\_MACRO**|EDM operation ID for creating an EDM macro call operation. This operid was added when operations were added to the ProCAM 2d EDM system.|
|** | |

## <a name="chmtopic846"></a>**OPERLIST**
#### **Purpose**
Mill and Lathe operation question.
#### **Syntax**
**:OPERLIST=abs inc**
#### **Comments**
This command determines the name of an attribute question that is to be asked in CAD.
#### **Example**
:OPERID=MILL\_PROFILING

**:OPERLIST=machine compensation**

**:OPERLIST=abs inc**

**:OPERLIST=work coord**

**:OPERLIST=coolant**

:OPEREND
## <a name="chmtopic848"></a>**OPERSUB**
#### **Purpose**
Mill drilling operation ID name.
#### **Syntax**
**:OPERSUB=DRILLING**
#### **Comments**
This command determines the name of a drilling operation ID. Any OPERLIST questions asked after this command will be added to the operation questions in CAD. This command is used in a drilling operation only. It should be placed after the :OPERID=MILL\_DRILLING.
#### **Example**
:OPERID=MILL\_DRILLING

**:OPERSUB=DRILLING**

:OPERLIST=abs inc

:OPERLIST=work coord

:OPERLIST=coolant

:OPEREND
## <a name="chmtopic850"></a>**SECTION**
#### **Purpose**
Start function definitions.
#### **Syntax**
**:SECTION=CALC\_REMOVE\_OFFSET**
#### **Comments**
This command determines the name of a section and what type of section it is. If the :SECTION=CALC\_? section equals starts with a [CALC](#chmtopic463), then it is a calculation section; otherwise, it is a template section.
#### **Example**
**:SECTION=CALC\_REMOVE\_OFFSET**

:C: IF DEFINING\_MACRO=YES AND JUST\_STARTED\_MACRO=1

:C: THEN SAV\_MODE=CURRENT\_MODE JUST\_STARTED\_MACRO=2

:C: ENDIF

:C: IF OFFSET\_RESIDENT=NO THEN RETURN ENDIF

:C: X\_OFFSET=(LAST\_X-SYS\_X\_OFFSET)

:C: Y\_OFFSET=(LAST\_Y-SYS\_Y\_OFFSET)

:C: CALL(OFFSET\_PART\_PUNCH)

:C: OFFSET\_RESIDENT=NO



**:SECTION=OFFSET\_PART\_PUNCH**

:T:<SEQ><ABS\_PRESET><X\_OFFSET><Y\_OFFSET><EOL>
## <a name="chmtopic463"></a>**CALC Sections**


The [:SECTION command](#chmtopic850) determines the name of a section and what type of section it is. If the **:SECTION=CALC\_?** section equals starts with a **CALC**, then it is a calculation section; otherwise, it is a template section.
**\


**Calc sections:**

|<a name="chmbookmark6"></a>**Mill**|
| :-: |
|<p>CALC\_LINE\_MOVE\_MILL</p><p>CALC\_ARC\_MOVE\_MILL</p><p>CALC\_RAPID\_MOVE\_MILL</p><p>CALC\_SINGLE\_DRILL\_MILL</p><p>CALC\_INIT\_TOOL\_CHANGE\_MILL</p><p>CALC\_SUB\_TOOL\_CHANGE\_MILL</p><p>CALC\_EVERY\_MOVE\_MILL</p><p>CALC\_GRID\_PATTERN\_DRILL</p><p>CALC\_DRILL\_INCREMENT\_DRILL</p><p>CALC\_BOLT\_HOLE\_CIR\_DRILL</p><p>CALC\_ARC\_PATTERN\_DRILL</p><p>CALC\_RAPID\_Z\_UP\_MILL</p><p>CALC\_RAPID\_Z\_DOWN\_MILL</p><p>CALC\_FEED\_Z\_MILL</p><p>CALC\_ROTATE\_X</p><p>CALC\_ROTATE\_Y</p><p>CALC\_ROTATE\_Z</p><p>[CALC_ARC_MOVE_MILL_ZX](#chmtopic852)</p><p>[CALC_ARC_MOVE_MILL_YZ](#chmtopic853)</p><p>[CALC_ARC_MOVE_MILL_ANYPLANE](#chmtopic854)</p><p>[CALC_POST_INITIALIZE](#chmtopic855)</p><p>[CALC_TOOL_INITIALIZE](#chmtopic856)</p><p>[CALC_ALLOW_RAPID_DURING_DRILL](#chmtopic822)</p><p>[CALC_SET_PRE_POSITION_ROTARY_TYPE](#chmtopic857)</p><p>CALC\_OUTPUT\_CL\_COMMENT</p><p>CALC\_OUTPUT\_CL\_COMMAND </p>|







|**Lathe**|
| :-: |
|<p>CALC\_LINE\_MOVE\_LATHE</p><p>CALC\_ARC\_MOVE\_LATHE</p><p>CALC\_RAPID\_MOVE\_LATHE</p><p>CALC\_SYSTEM\_THREAD\_LATHE</p><p>CALC\_INIT\_TOOL\_CHANGE\_LATHE</p><p>CALC\_SUB\_TOOL\_CHANGE\_LATHE</p><p>CALC\_EVERY\_MOVE\_LATHE</p><p>CALC\_MACHINE\_THREAD\_LATHE</p><p>CALC\_SYSTEM\_DRILL\_LATHE</p><p>CALC\_MACHINE\_DRILL\_LATHE</p><p>CALC\_START\_BOUNDARY\_LATHE</p><p>CALC\_END\_BOUNDARY\_LATHE</p><p>[CALC_SLOWDOWN_SPEED](#chmtopic858)</p><p>[CALC_SHIFT_TOOL_LATHE](#chmtopic859)</p><p>[CALC_CUTTER_COMP_LATHE](#chmtopic824)</p>|





|<a name="chmbookmark65"></a>**Mill-Turn**|
| :-: |
|<p>[CALC_CHANGE_MILL_SPEED](#chmtopic348)</p><p>[**C**ALC_OUTPUT_POLAR_SPINDLE_ORIENTATION](#chmtopic357)</p><p>[CALC_OUTPUT_CANCEL_POLAR_SPINDLE_ORIENTATION](#chmtopic351)</p><p>[CALC_OUTPUT_SPINDLE_STATE](#chmtopic363)</p><p>[CALC_OUTPUT_SPINDLE_ORIENTATION](#chmtopic362)</p><p>[CALC_OUTPUT_SPINDLE_COMMENT](#chmtopic361)</p><p>[CALC_OUTPUT_SPINDLE_COMMAND](#chmtopic360)</p><p>[CALC_OUTPUT_CHUCK_OPEN](#chmtopic352)</p><p>[CALC_OUTPUT_CHUCK_CLOSE](#chmtopic353)</p><p>[CALC_OUTPUT_ARBOR_OPEN](#chmtopic349)</p><p>[CALC_OUTPUT_ARBOR_CLOSE](#chmtopic350)</p><p>[CALC_OUTPUT_COLLET_OPEN](#chmtopic354)</p><p>[CALC_OUTPUT_COLLET_CLOSE](#chmtopic355)</p><p>[CALC_OUTPUT_FEEDRATE](#chmtopic356)</p><p>[CALC_OUTPUT_SPEED](#chmtopic359)</p><p>[CALC_OUTPUT_REFERENCE_POINT](#chmtopic358)</p><p>[CALC_OUTPUT_RAPID_SPINDLE_TO_POSITION](#chmtopic365)</p><p>[CALC_OUTPUT_FEED_SPINDLE_TO_POSITION](#chmtopic366)</p><p>[CALC_OUTPUT_RAPID_SPINDLE_TO_HOME](#chmtopic269)</p><p>[CALC_OUTPUT_FEED_SPINDLE_TO_HOME](#chmtopic268)</p><p>[CALC_OUTPUT_SPINDLE_SYNC](#chmtopic364)</p><p>[CALC_QUERY_POST](#chmtopic367)</p><p> </p>|



|<a name="chmbookmark5"></a>**Probe Cycles**|
| :-: |
|<p>CALC\_LINE\_MOVE\_PROBE\_MILL</p><p>CALC\_RAPID\_MOVE\_PROBE\_MILL</p><p>CALC\_RAPID\_Z\_UP\_PROBE\_MILL</p><p>CALC\_RAPID\_Z\_DOWN\_PROBE\_MILL</p><p>CALC\_FEED\_Z\_PROBE\_MILL</p><p>CALC\_OUTPUT\_PROBE\_CYCLE\_MILL</p>|





|**Punch**|
| :-: |
|<p>CALC\_LINE\_MOVE\_PUNCH</p><p>CALC\_ARC\_MOVE\_PUNCH</p><p>CALC\_RAPID\_MOVE\_PUNCH</p><p>CALC\_SINGLE\_HIT\_PUNCH</p><p>CALC\_INIT\_TOOL\_CHANGE\_PUNCH</p><p>CALC\_SUB\_TOOL\_CHANGE\_PUNCH</p><p>CALC\_EVERY\_MOVE\_PUNCH</p><p>CALC\_START\_OF\_TAPE\_PUNCH</p><p>CALC\_END\_OF\_TAPE\_PUNCH</p><p>CALC\_GRID\_PATTERN\_PUNCH</p><p>CALC\_PUNCH\_INCREMENT\_PUNCH</p><p>CALC\_BOLT\_HOLE\_CIR\_PUNCH</p><p>CALC\_ARC\_PATTERN\_PUNCH</p><p>CALC\_WINDOW\_PUNCH</p><p>CALC\_WINDOW\_FRAME\_PUNCH</p><p>CALC\_REPOSITION\_PUNCH</p><p>CALC\_OFFSET\_PART\_PUNCH</p><p>CALC\_BEG\_MACRO\_PUNCH</p><p>CALC\_END\_MACRO\_PUNCH</p><p>CALC\_MULTIPLE\_MACRO\_CALL\_PUNCH</p><p>CALC\_MIRROR\_MACRO\_CALL\_PUNCH</p><p>CALC\_MACRO\_CALL\_PUNCH</p><p>CALC\_MULTIPLE\_MACRO\_DEFINE\_PUNCH</p><p>CALC\_SETUP\_SHEET\_PUNCH</p>|







|**Plasma**|
| :-: |
|<p>CALC\_LINE\_MOVE\_PLASMA</p><p>CALC\_ARC\_MOVE\_PLASMA</p><p>CALC\_RAPID\_MOVE\_PLASMA</p><p>CALC\_INIT\_TOOL\_CHANGE\_PLASMA</p><p>CALC\_SUB\_TOOL\_CHANGE\_PLASMA</p><p>CALC\_EVERY\_MOVE\_PLASMA</p><p>CALC\_GRID\_PATTERN\_PLASMA</p><p>CALC\_PLASMA\_INCREMENT\_PLASMA</p><p>CALC\_BOLT\_HOLE\_CIR\_PLASMA</p><p>CALC\_ARC\_PATTERN\_PLASMA</p><p>CALC\_REPOSITION\_PLASMA</p><p>[CALC_RAPID_TO_TRAPDOOR_PLASMA](#chmtopic860)</p><p>[CALC_PROFILE_DRILL_PLASMA](#chmtopic861)</p>|







|**Laser**|
| :-: |
|<p>CALC\_LINE\_MOVE\_LASER</p><p>CALC\_ARC\_MOVE\_LASER</p><p>CALC\_RAPID\_MOVE\_LASER</p><p>CALC\_PROFILE\_DRILL\_LASER</p><p>CALC\_INIT\_TOOL\_CHANGE\_LASER</p><p>CALC\_SUB\_TOOL\_CHANGE\_LASER</p><p>CALC\_EVERY\_MOVE\_LASER</p><p>CALC\_GRID\_PATTERN\_LASER</p><p>CALC\_LASER\_INCREMENT\_LASER</p><p>CALC\_BOLT\_HOLE\_CIR\_LASER</p><p>CALC\_ARC\_PATTERN\_LASER</p><p>CALC\_REPOSITION\_LASER</p><p>[CALC_RAPID_TO_TRAPDOOR_LASER](#chmtopic862)</p><p>[CALC_PROFILE_DRILL_LASER](#chmtopic863)</p>|







|**Shear**|
| :-: |
|<p>[CALC_RAPID_MOVE_SHEAR](#chmtopic864)</p><p>[CALC_INIT_TOOL_CHANGE_SHEAR](#chmtopic865)</p><p>[CALC_SUB_TOOL_CHANGE_SHEAR](#chmtopic866)</p><p>[CALC_EVERY_MOVE_SHEAR](#chmtopic867)</p><p>[CALC_FULL_SHEAR](#chmtopic868)</p><p>[CALC_HALF_SHEAR_X](#chmtopic869)</p><p>[CALC_HALF_SHEAR_Y](#chmtopic870)</p><p>[CALC_FULL_SHEAR_DIAGONAL](#chmtopic871)</p><p>[CALC_HALF_SHEAR_DIAGONAL](#chmtopic872)</p><p>[CALC_REPOSITION_SHEAR](#chmtopic873)</p>|







|**EDM**|
| :-: |
|<p>CALC\_LINE\_MOVE\_EDM</p><p>CALC\_ARC\_MOVE\_EDM</p><p>CALC\_POINT\_MOVE\_EDM</p><p>CALC\_RAPID\_MOVE\_EDM</p><p>CALC\_INIT\_TOOL\_CHANGE\_EDM</p><p>CALC\_SUB\_TOOL\_CHANGE\_EDM</p><p>CALC\_EVERY\_MOVE\_EDM</p><p>CALC\_START\_HOLE\_EDM</p><p>CALC\_END\_HOLE\_EDM</p><p>[CALC_GET_TAPER_EDM](#chmtopic874)</p>|



|**Misc**|
| :-: |
|<p>CALC\_BEFORE\_ATTRIBUTES</p><p>CALC\_DURING\_ATTRIBUTES</p><p>CALC\_AFTER\_ATTRIBUTES</p><p>CALC\_SWITCH\_TO\_PLASMA</p><p>CALC\_SWITCH\_TO\_PUNCH</p><p>CALC\_START\_OF\_TAPE</p><p>CALC\_END\_OF\_TAPE</p><p>CALC\_OFFSET\_PART</p><p>CALC\_BEG\_MACRO</p><p>CALC\_END\_MACRO</p><p>CALC\_MULTIPLE\_MACRO\_CALL</p><p>CALC\_MIRROR\_MACRO\_CALL</p><p>CALC\_MACRO\_CALL</p><p>CALC\_MULTIPLE\_MACRO\_DEFINE</p><p>CALC\_SETUP\_SHEET</p><p>CALC\_START\_OPERATION</p><p>CALC\_END\_OPERATION</p><p>[CALC_ADD_FRONT_SYNC_CODE](#chmtopic875)</p><p>[CALC_ADD_REAR_SYNC_CODE](#chmtopic876)</p><p>[CALC_PRE_POST_INITIALIZE](#chmtopic278)</p>|

## <a name="chmtopic875"></a>**CALC\_ADD\_FRONT\_SYNC\_CODE**
#### **Purpose**
CALC\_ADD\_FRONT\_SYNC\_CODE gets called when a command to output rear sync code is encountered and the post variables SYNC\_CODE\_COMMENT, FRONT\_SYNC\_CODE and FRONT\_SYNC\_CODE\_TYPE are set.
## <a name="chmtopic876"></a>**CALC\_ADD\_REAR\_SYNC\_CODE**
#### **Purpose**
CALC\_ADD\_REAR\_SYNC\_CODE gets called when a command to output rear sync code is encountered and the post variables SYNC\_CODE\_COMMENT, REAR\_SYNC\_CODE and REAR\_SYNC\_CODE\_TYPE are set.
## <a name="chmtopic854"></a>**CALC\_ARC\_MOVE\_ANYPLANE**
#### **Purpose**
Mill calc section for arc moves on none standard planes using CAMWorks 2005 or ProCAM II 2004 or newer versions.
#### **Syntax**
**:SECTION=CALC\_ARC\_MOVE\_ANYPLANE**
#### **Comments**
The post will only get to this section when you are doing an arc movement that is on none standard planes. If section does not exist then post outputs line moves.

If you have an old post that does not have this section compiled in the source, then the post will break the arcs into line moves by a default deviation. If you are creating a new post and your machine does not support arcs on different planes, then you need to add the question "max\_arc\_dev" to either the Setup Info or the operation questions to set the deviation amount. This value will then set the post variable ARC\_DEVIATION to this value.

:C: ARC\_DEVIATION=max\_arc\_dev

:C: SYS\_CANNED(5,CALC\_BREAK\_ARC)
## <a name="chmtopic853"></a>**CALC\_ARC\_MOVE\_YZ**
#### **Purpose**
Mill calc section for arc moves on YZ plane using CAMWorks 2005 or ProCAM II 2004 or newer versions.
#### **Syntax**
**:SECTION=CALC\_ARC\_MOVE\_YZ**
#### **Comments**
The post will only get to this section when you are doing an arc movement that is on the YZ plane. If section does not exist then post outputs line moves.

If you have an old post that does not have this section compiled in the source, then the post will break the arcs into line moves by a default deviation. If you are creating a new post and your machine does not support arcs on different planes, then you need to add the question "max\_arc\_dev" to either the Setup Info or the operation questions to set the deviation amount. This value will then set the post variable ARC\_DEVIATION to this value.

:C: ARC\_DEVIATION=max\_arc\_dev

:C: SYS\_CANNED(5,CALC\_BREAK\_ARC)


## <a name="chmtopic852"></a>**CALC\_ARC\_MOVE\_ZX**
#### **Purpose**
Mill calc section for arc moves on ZX plane using CAMWorks 2005 or ProCAM II 2004 or newer versions.
#### **Syntax**
**:SECTION=CALC\_ARC\_MOVE\_ZX**
#### **Comments**
The post will only get to this section when you are doing an arc movement that is on the ZX plane. If section does not exist then post outputs line moves.Type topic text here.

If you have an old post that does not have this section compiled in the source, then the post will break the arcs into line moves by a default deviation. If you are creating a new post and your machine does not support arcs on different planes, then you need to add the question "max\_arc\_dev" to either the Setup Info or the operation questions to set the deviation amount. This value will then set the post variable ARC\_DEVIATION to this value.

:C: ARC\_DEVIATION=max\_arc\_dev

:C: SYS\_CANNED(5,CALC\_BREAK\_ARC)
## <a name="chmtopic348"></a>**CALC\_CHANGE\_MILL\_SPEED**
#### **Purpose**
This section will be called by CAMWorks automatically when you are in Volumill.
#### **Comments**
Supported in CAMWorks 2011 and later. Not supported in any ProCAM product.

Available in Mill, and Mill-Turn.
#### **Example**
:SECTION=CALC\_CHANGE\_MILL\_SPEED

:C: IF SECTIONEXIST(CHANGE\_MILL\_SPEED) THEN CALL(CHANGE\_MILL\_SPEED) ENDIF


## <a name="chmtopic867"></a>**CALC\_EVERY\_MOVE\_SHEAR**
#### **Purpose**
Shear system every move calc section.
#### **Syntax**
**:SECTION=CALC\_EVERY\_MOVE\_SHEAR**
#### **Comments**
This section will be called for every move type that occurs while you are shearing.
## <a name="chmtopic868"></a>**CALC\_FULL\_SHEAR**
#### **Purpose**
Shear system full shear calc section.
#### **Syntax**
**:SECTION=CALC\_FULL\_SHEAR**
#### **Comments**
This section will be called for every stroke that uses a full shear while you are shearing.
## <a name="chmtopic871"></a>**CALC\_FULL\_SHEAR\_DIAGONAL**
#### **Purpose**
Shear system full shear diagonally calc section.
#### **Syntax**
**:SECTION=CALC\_FULL\_SHEAR\_DIAGONAL**
#### **Comments**
This section will be called for every stroke that uses the full shear tool in a diagonal direction while you are shearing.
## <a name="chmtopic44"></a>**CALC\_GET\_SW\_CUSTOM\_FIELDS**
#### **Purpose**
Used when you need to get the SOLIDWORKS Custom fields.
#### **Syntax**
**:SECTION=CALC\_GET\_SW\_CUSTOM\_FIELDS**
#### **Comments**
This section will be called only when it is inserted into the post source. 
**\


**Logic to be used in CALC\_GET\_SW\_CUSTOM\_FIELDS**

:SECTION=CALC\_GET\_SW\_CUSTOM\_FIELDS

:C: IF CAMWORKS\_VER<CAM\_REV2020 THEN RETURN ENDIF

:C: [GET_SW_CUSTOM_PROP_BY_NAME](#chmtopic13)({CAMWorks Machine},CALC\_OUTPUT\_SW\_PROPERTY)

\*\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_


## <a name="chmtopic45"></a>**CALC\_GET\_SW\_PROPERTIES**
#### **Purpose**
Used when you need to get SOLIDWORKS Properties.
#### **Syntax**
**:SECTION=CALC\_GET\_SW\_PROPERTIES**
#### **Comments**
This section will be called only when it is inserted into the post source. 
**\


**Logic to be used in CALC\_GET\_SW\_PROPERTIES**

:SECTION=CALC\_GET\_SW\_PROPERTIES

:C: IF CAMWORKS\_VER<CAM\_REV2020 THEN RETURN ENDIF

\*

:C: CALL(CALC\_OUTPUT\_SW\_HEADER)

:C: CALL([CALC_GET_SW_SUMMARY_FIELDS](#chmtopic46))

\*

:C: CALL(CALC\_OUTPUT\_SW\_HEADER)

:C: CALL([CALC_GET_SW_CUSTOM_FIELDS](#chmtopic44))

\*

:C: CALL(CALC\_OUTPUT\_SW\_HEADER)

\*\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
## <a name="chmtopic46"></a>**CALC\_GET\_SW\_SUMMARY\_FIELDS**
#### **Purpose**
Used when you need to get the various SOLIDWORKS Summary fields.
#### **Syntax**
**:SECTION=CALC\_GET\_SW\_SUMMARY\_FIELDS**
#### **Comments**
This section will be called only when it is inserted into the post source. 
**\


**Logic to be used in CALC\_GET\_SW\_SUMMARY\_FIELDS**

:SECTION=CALC\_GET\_SW\_SUMMARY\_FIELDS

:C: IF CAMWORKS\_VER<CAM\_REV2020 THEN RETURN ENDIF

:C: [GET_SW_SUMMARY_INFO_BY_ID](#chmtopic14)(SW\_INFO\_AUTHOR,[CALC_OUTPUT_SW_PROPERTY](#chmtopic47))

:C: [GET_SW_SUMMARY_INFO_BY_ID](#chmtopic14)(SW\_INFO\_KEYWORDS,[CALC_OUTPUT_SW_PROPERTY](#chmtopic47))

:C: [GET_SW_SUMMARY_INFO_BY_ID](#chmtopic14)(SW\_INFO\_COMMENTS,[CALC_OUTPUT_SW_PROPERTY](#chmtopic47))

:C: [GET_SW_SUMMARY_INFO_BY_ID](#chmtopic14)(SW\_INFO\_TITLE,[CALC_OUTPUT_SW_PROPERTY](#chmtopic47))

:C: [GET_SW_SUMMARY_INFO_BY_ID](#chmtopic14)D(SW\_INFO\_SUBJECT,[CALC_OUTPUT_SW_PROPERTY](#chmtopic47))

:C: [GET_SW_SUMMARY_INFO_BY_ID](#chmtopic14)(SW\_INFO\_CREATION\_DATE,[CALC_OUTPUT_SW_PROPERTY](#chmtopic47))

:C: [GET_SW_SUMMARY_INFO_BY_ID](#chmtopic14)(SW\_INFO\_SAVED\_DATE,[CALC_OUTPUT_SW_PROPERTY](#chmtopic47))

:C: [GET_SW_SUMMARY_INFO_BY_ID](#chmtopic14)(SW\_INFO\_SAVED\_BY,[CALC_OUTPUT_SW_PROPERTY](#chmtopic47))

\*\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_


## <a name="chmtopic874"></a>**CALC\_GET\_TAPER\_EDM**
#### **Purpose**
Used when you need to get all the different taper angles used in the current part and output them at the start of the program.
#### **Syntax**
**:SECTION=CALC\_GET\_TAPER\_EDM**
#### **Comments**
This section will be called only when it is inserted into the post source. When you start to post out, the current EDM part file the system will go through the complete tool paths of the part file to gather all the different taper changes, then it will start calling this section for each different taper angle and you can store this information in post arrays. Now it will start the normal post output.
## <a name="chmtopic872"></a>**CALC\_HALF\_SHEAR\_DIAGONAL**
#### **Purpose**
Shear system half shear diagonally calc section.
#### **Syntax**
**:SECTION=CALC\_HALF\_SHEAR\_DIAGONAL**
#### **Comments**
This section will be called for every stroke that uses half of the shear tool in a diagonal direction while you are shearing.
## <a name="chmtopic869"></a>**CALC\_HALF\_SHEAR\_X**
#### **Purpose**
Shear system half shear in X calc section.
#### **Syntax**
**:SECTION=CALC\_HALF\_SHEAR\_X**
#### **Comments**
This section will be called for every stroke that only uses half the shear tool in the X direction while you are shearing.
## <a name="chmtopic870"></a>**CALC\_HALF\_SHEAR\_Y**
#### **Purpose**
Shear system half shear in Y calc section.
#### **Syntax**
**:SECTION=CALC\_HALF\_SHEAR\_Y**
#### **Comments**
This section will be called for every stroke that only uses half the shear tool in the Y direction while you are shearing.
## <a name="chmtopic865"></a>**CALC\_INIT\_TOOL\_CHANGE\_SHEAR**
#### **Purpose**
Shear system initial tool change calc section.
#### **Syntax**
**:SECTION=CALC\_INIT\_TOOL\_CHANGE\_SHEAR**
#### **Comments**
This section will be called for the first tool change that occurs while you are shearing.
## <a name="chmtopic350"></a>**CALC\_OUTPUT\_ARBOR\_CLOSE**
#### **Purpose**
Reserved for future use in Sub Spindle operation.
#### **Syntax**
Post variable DSPINDLE will be available with values of either, 1 = MAIN\_SPINDLE, 2 = SUB\_SPINDLE.
#### **Example**
:SECTION=CALC\_OUTPUT\_ARBOR\_CLOSE

:C: IF SECTIONEXIST(OUTPUT\_ARBOR\_CLOSE) THEN

:C: CALL(OUTPUT\_ARBOR\_CLOSE)

:C: ENDIF


## <a name="chmtopic349"></a>**CALC\_OUTPUT\_ARBOR\_OPEN**
#### **Purpose**
Reserved for future use in Sub Spindle operation.
#### **Syntax**
Post variable DSPINDLE will be available with values of either, 1 = MAIN\_SPINDLE, 2 = SUB\_SPINDLE.
#### **Example**
:SECTION=CALC\_OUTPUT\_ARBOR\_OPEN

:C: IF SECTIONEXIST(OUTPUT\_ARBOR\_OPEN) THEN

:C: CALL(OUTPUT\_ARBOR\_OPEN)

:C: ENDIF


## <a name="chmtopic351"></a>**CALC\_OUTPUT\_CANCEL\_POLAR\_SPINDLE\_ORIENTATION**
#### **Purpose**
This section will be called by CAMWorks automatically. Available in Mill-Turn.
#### **Syntax**
To activate this option set post header as

:MILL\_FACE\_POLAR = X+\_ONLY
#### **Comments**
This will work for Face Polar and Fixed only.

Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.
#### **Example**
:SECTION=CALC\_OUTPUT\_CANCEL\_POLAR\_SPINDLE\_ORIENTATION

:C: IF SECTIONEXIST(OUTPUT\_CANCEL\_POLAR\_SPINDLE\_ORIENTATION) THEN

:C: CALL(OUTPUT\_CANCEL\_POLAR\_SPINDLE\_ORIENTATION)

:C: ENDIF


## <a name="chmtopic353"></a>**CALC\_OUTPUT\_CHUCK\_CLOSE**
#### **Purpose**
This section will be called by CAMWorks automatically when using a sub spindle operation and you insert a Spindle Clamp step.
#### **Syntax**
Post variable DSPINDLE will be available with values of either, 1=MAIN\_SPINDLE, 2=SUB\_SPINDLE.
#### **Comments**
Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.

Available in Mill-Turn and Turn.
#### **Example**
:SECTION=CALC\_OUTPUT\_CHUCK\_CLOSE

:C: IF SECTIONEXIST(OUTPUT\_CHUCK\_CLOSE) THEN

:C: CALL(OUTPUT\_CHUCK\_CLOSE)

:C: ENDIF


## <a name="chmtopic352"></a>**CALC\_OUTPUT\_CHUCK\_OPEN**
#### **Purpose**
This section will be called by CAMWorks automatically when using a sub spindle operation and you insert a Spindle Unclamp step.
#### **Syntax**
Post variable DSPINDLE will be available with values of either, 1 = MAIN\_SPINDLE, 2 = SUB\_SPINDLE.
#### **Comments**
Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.

Available in Mill-Turn and Turn.
#### **Example**
:SECTION=CALC\_OUTPUT\_CHUCK\_OPEN

:C: IF SECTIONEXIST(OUTPUT\_CHUCK\_OPEN) THEN

:C: CALL(OUTPUT\_CHUCK\_OPEN)

:C: ENDIF


## <a name="chmtopic355"></a>**CALC\_OUTPUT\_COLLECT\_CLOSE**
#### **Purpose**
Reserved for future use in Sub Spindle operation.
#### **Syntax**
Post variable DSPINDLE will be available with values of either, 1 = MAIN\_SPINDLE, 2 = SUB\_SPINDLE.
#### **Example**
:SECTION=CALC\_OUTPUT\_COLLET\_CLOSE

:C: IF SECTIONEXIST(OUTPUT\_COLLET\_CLOSE) THEN

:C: CALL(OUTPUT\_COLLET\_CLOSE)

:C: ENDIF


## <a name="chmtopic354"></a>**CALC\_OUTPUT\_COLLECT\_OPEN**
#### **Purpose**
Reserved for future use in Sub Spindle operation.
#### **Syntax**
Post variable DSPINDLE will be available with values of either, 1 = MAIN\_SPINDLE, 2 = SUB\_SPINDLE.
#### **Example**
:SECTION=CALC\_OUTPUT\_COLLET\_OPEN

:C: IF SECTIONEXIST(OUTPUT\_COLLET\_OPEN) THEN

:C: CALL(OUTPUT\_COLLET\_OPEN)

:C: ENDIF


## <a name="chmtopic268"></a>**CALC\_OUTPUT\_FEED\_SPINDLE\_TO\_HOME**
#### **Purpose**
Can be used with any turn or mill/turn posts that support sub spindle operations
#### **Syntax**
:SECTION=CALC\_OUTPUT\_FEED\_SPINDLE\_TO\_HOME
#### **Comments**
This section will get called when you insert a sub spindle operation and you select “Sub Spindle Home” in a feed step. To be used in CAMWorks 2014 or newer version.
# <a name="chmtopic366"></a>**Calc\_Output\_Feed\_Spindle\_To\_Position**
#### **Purpose**
This section will be called by CAMWorks automatically when using a sub spindle operation and you insert a Spindle Feed step.
#### **Syntax**
Post variable DSPINDLE will be available with values of either, 1 = MAIN\_SPINDLE, 2 = SUB\_SPINDLE.

Post variable OPR\_SPEED\_FPM will be available with feedrate value.

Post variable ABS\_SPINDLE\_Z\_END will be available with Decimal value.
#### **Comments**
Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.

Available in Mill-Turn and Turn.
#### **Example**
:SECTION=CALC\_OUTPUT\_FEED\_SPINDLE\_TO\_POSITION

:C: IF SECTIONEXIST(OUTPUT\_FEED\_SPINDLE\_TO\_POSITION) THEN

:C: OPR\_FEED\_TYPE=2

:C: FEED\_TYPE=GC(G\_FPM)

:C: CALL(OUTPUT\_FEED\_SPINDLE\_TO\_POSITION)

:C: ENDIF


## <a name="chmtopic356"></a>**CALC\_OUTPUT\_FEEDRATE**
#### **Purpose**
Reserved for future use in Sub Spindle operation.
#### **Syntax**
Post variable OPR\_FEED\_FPM will be available with feedrate values.
#### **Example**
:SECTION=CALC\_OUTPUT\_FEEDRATE

:C: IF SECTIONEXIST(OUTPUT\_FEEDRATE) THEN

:C: CALL(OUTPUT\_FEEDRATE)

:C: ENDIF


## <a name="chmtopic357"></a>**CALC\_OUTPUT\_POLAR\_SPINDLE\_ORIENTATION**
#### **Purpose**
This section will be called by CAMWorks automatically. 
#### **Syntax**
To activate this option set post header as

:MILL\_FACE\_POLAR = X+\_ONLY

This will work for face Polar and Fixed only.

SPINDLE\_ORIENTATION post variable will have the value of rotation to get the feature to C zero.
#### **Comments**
Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.

Available in Mill-Turn.
#### **Example**
:SECTION=CALC\_OUTPUT\_POLAR\_SPINDLE\_ORIENTATION

:C: IF SECTIONEXIST(OUTPUT\_POLAR\_SPINDLE\_ORIENTATION) THEN

:C: CALL(OUTPUT\_POLAR\_SPINDLE\_ORIENTATION)

:C: ENDIF


## <a name="chmtopic269"></a>**CALC\_OUTPUT\_RAPID\_SPINDLE\_TO\_HOME**
#### **Purpose**
Can be used with any turn or mill/turn posts that support sub spindle operations
#### **Syntax**
:SECTION=CALC\_OUTPUT\_RAPID\_SPINDLE\_TO\_HOME
#### **Comments**
This section will get called when you insert a sub spindle operation and you select “Sub Spindle Home” in a rapid step. To be used in CAMWorks 2014 or newer version.


## <a name="chmtopic365"></a>**CALC\_OUTPUT\_RAPID\_SPINDLE\_TO\_POSITION**
#### **Purpose**
This section will be called by CAMWorks automatically when using a sub spindle operation and you insert a Spindle Rapid step.
#### **Syntax**
Post variable DSPINDLE will be available with values of either, 1 = MAIN\_SPINDLE, 2 = SUB\_SPINDLE.

Post variable ABS\_SPINDLE\_Z\_END will be avaliable with Decimal value.
#### **Comments**
Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.

Available in Mill-Turn and Turn.
#### **Example**
:SECTION=CALC\_OUTPUT\_RAPID\_SPINDLE\_TO\_POSITION

:C: IF SECTIONEXIST(OUTPUT\_RAPID\_SPINDLE\_TO\_POSITION) THEN

:C: CALL(OUTPUT\_RAPID\_SPINDLE\_TO\_POSITION)

:C: ENDIF
## <a name="chmtopic358"></a>**CALC\_OUTPUT\_REFERENCE\_POINT**
#### **Purpose**
Reserved for future use in Sub Spindle operation.
#### **Comments**
Available in Mill-Turn and Turn.
#### **Example**
:SECTION=CALC\_OUTPUT\_REFERENCE\_POINT

:C: IF SECTIONEXIST(OUTPUT\_REFERENCE\_POINT) THEN

:C: CALL(OUTPUT\_REFERENCE\_POINT)

:C: ENDIF


## <a name="chmtopic359"></a>**CALC\_OUTPUT\_SPEED**
#### **Purpose**
This section will be called by CAMWorks automatically when using a sub spindle operation and you insert a Spindle Speed step.
#### **Syntax**
Post variable DSPINDLE will be available with values of either, 1 = MAIN\_SPINDLE, 2 = SUB\_SPINDLE.

Post variable OPR\_SPEED\_DIR will be available with values of either, 1 = CW, 2 = CCW.

Post variable OPR\_SPEED\_RPM will be available with RPM value.
#### **Comments**
Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.

Available in Mill-Turn and Turn.
#### **Example**
:SECTION=OUTPUT\_SPEED

:T: IF DSPINDLE=MAIN\_SPINDLE AND OPR\_SPEED\_DIR=1 THEN <N><G!:SPEED\_TYPE><S!:OPR\_SPEED\_RPM><M!:MC(M\_SPIN\_CW)><EOL>ENDIF

:T: IF DSPINDLE=MAIN\_SPINDLE AND OPR\_SPEED\_DIR<>1 THEN <N><G!:SPEED\_TYPE><S!:OPR\_SPEED\_RPM><M!:MC(M\_SPIN\_CCW)><EOL>ENDIF

:T: IF DSPINDLE=SUB\_SPINDLE AND OPR\_SPEED\_DIR=1 THEN <N><G!:SPEED\_TYPE><S!:OPR\_SPEED\_RPM><M!:MC(M\_SUB\_CW)><EOL>ENDIF

:T: IF DSPINDLE=SUB\_SPINDLE AND OPR\_SPEED\_DIR<>1 THEN <N><G!:SPEED\_TYPE><S!:OPR\_SPEED\_RPM><M!:MC(M\_SUB\_CCW)><EOL>ENDIF


## <a name="chmtopic360"></a>**CALC\_OUTPUT\_SPINDLE\_COMMAND**
#### **Purpose**
This section will be called by CAMWorks automatically when using a sub spindle operation and you insert a Text/with No Comment selected step.
#### **Syntax**
Post variable SPINDLE\_COMMENT will be available with an comment string.

This will output raw text (hardcoded) output "N1 M05".
#### **Comments**
Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.

Available in Mill-Turn and Turn.
#### **Example**
:SECTION=CALC\_OUTPUT\_SPINDLE\_COMMAND

:C: IF SECTIONEXIST(OUTPUT\_SPINDLE\_COMMAND) THEN

:C: CALL(OUTPUT\_SPINDLE\_COMMAND)

:C: ENDIF


## <a name="chmtopic361"></a>**CALC\_OUTPUT\_SPINDLE\_COMMENT**
#### **Purpose**
This section will be called by CAMWorks automatically when using a sub spindle operation and you insert a Text/with Comment selected step.
#### **Syntax**
Post variable SPINDLE\_COMMENT will be available with an comment string.

This will output text as a comment "N1 (M05)".
#### **Comments**
Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.

Available in Mill-Turn and Turn.
#### **Example**
:SECTION=CALC\_OUTPUT\_SPINDLE\_COMMENT

:C: IF SECTIONEXIST(OUTPUT\_SPINDLE\_COMMENT) THEN

:C: CALL(OUTPUT\_SPINDLE\_COMMENT)

:C: ENDIF
## <a name="chmtopic362"></a>**CALC\_OUTPUT\_SPINDLE\_ORIENTATION**
#### **Purpose**
This section will be called by CAMWorks automatically when using a sub spindle operation and you insert a Spindle Orient step.
#### **Syntax**
Post variable SPINDLE\_ORIENTATION will be available with an Orientation angle.
#### **Comments**
Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.

Available in Mill-Turn and Turn.
#### **Example**
:SECTION=CALC\_OUTPUT\_SPINDLE\_ORIENTATION

:C: IF SECTIONEXIST(OUTPUT\_SPINDLE\_ORIENTATION) THEN

:C: CALL(OUTPUT\_SPINDLE\_ORIENTATION)

:C: ENDIF


## <a name="chmtopic363"></a>**CALC\_OUTPUT\_SPINDLE\_STATE**
#### **Purpose**
This section will be called by CAMWorks automatically when using a sub spindle operation and you insert a Spindle On/Off/Lock step.
#### **Syntax**
Post variable DSPINDLE will be available with values of either, 1 = MAIN\_SPINDLE, 2 = SUB\_SPINDLE.

Post variable SPINDLE\_STATE will be available with values of either:

0 = OFF, 1 = ON, 2 = LOCK
#### **Comments**
Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.

Available in Mill-Turn and Turn.
#### **Example**
:SECTION=CALC\_OUTPUT\_SPINDLE\_STATE

:C: IF SECTIONEXIST(OUTPUT\_SPINDLE\_STATE) THEN

:C: CALL(OUTPUT\_SPINDLE\_STATE)

:C: ENDIF
## <a name="chmtopic364"></a>**CALC\_OUTPUT\_SPINDLE\_SYNC**
#### **Purpose**
This section will be called by CAMWorks automatically when using a sub spindle operation and you insert a Spindle Feed step.
#### **Syntax**
Post variable DSPINDLE will be available with values of either, 1 = MAIN\_SPINDLE, 2 = SUB\_SPINDLE.

Post variable SPINDLE\_SYNC\_TYPE will be available with values of either, 0 = SPEED, 1 = PHASE
#### **Comments**
Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.

Available in Mill-Turn and Turn.
#### **Example**
:C: SECTION=CALC\_OUTPUT\_SPINDLE\_SYNC

:C: IF SECTIONEXIST(OUTPUT\_SPINDLE\_SYNC) THEN

:C: CALL(OUTPUT\_SPINDLE\_SYNC)

:C: ENDIF
## <a name="chmtopic47"></a>**CALC\_OUTPUT\_SW\_PROPERTY**
#### **Purpose**
Used when you need to output the SOLIDWORKS Custom and Summary Property fields.
#### **Syntax**
**:SECTION=CALC\_OUTPUT\_SW\_PROPERTY**
#### **Comments**
This section will be called only when it is inserted into the post source. 
**\


**Logic to be used in CALC\_OUTPUT\_SW\_PROPERTY**

:SECTION=CALC\_OUTPUT\_SW\_PROPERTY

:C: IF CAMWORKS\_VER<CAM\_REV2020 THEN RETURN ENDIF

:C: IF [QUERY_SW_FIELD_VAL](#chmtopic70)={} THEN RETURN ENDIF

:C: IF SECTIONEXIST(OUTPUT\_SW\_PROPERTY) THEN

:C: CALL(OUTPUT\_SW\_PROPERTY)

:C: ENDIF

\*\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
## <a name="chmtopic855"></a>**CALC\_POST\_INITIALIZE**
#### **Purpose**
Mill calc section for setting 4 and 5 axis parameters used in ProCAM II only.
#### **Syntax**
**:SECTION=CALC\_POST\_INITIALIZE**

:C: IF SECTIONEXIST(FIVE\_AXIS\_LINE\_MOVE\_MILL) THEN

:C: CALL(CALC\_RESET\_REGISTERS)

:C: CALL(CALC\_RESET\_FIVE\_AXIS\_REGISTERS)

:C: ENDIF
#### **Comments**
The post will only get to this section when you have either :4AXIS\_X\_MILLING=TRUE, :4AXIS\_Y\_MILLING=TRUE or :5AXIS\_MILLING=TRUE, It will get to this section before it gets to CALC\_START\_OPERATION for the first time.
## <a name="chmtopic278"></a>**CALC\_PRE\_POST\_INITIALIZE**
#### **Purpose**
Can be used with all posts. This section will get called when posting before any other section gets called. Can be used to set system or post variables before other main sections get called for initializing code. To be used in CAMWorks 2014 or newer version.
#### **Syntax**
**:SECTION=CALC\_PRE\_POST\_INITIALIZE**
#### **Comments**
This section will get called when posting before any other section gets called. Can be used to set system or post variables before other main sections get called for initializing code. To be used in CAMWorks 2014 or newer version.






## <a name="chmtopic863"></a>**CALC\_PROFILE\_DRILL\_LASER**
#### **Purpose**
Used when you have a PUNCH/LASER combination machine that uses a pre-punched hole for starting a laser profile.
#### **Syntax**
**:SECTION=CALC\_PROFILE\_DRILL\_LASER**
#### **Comments**
This section will be called when you do pre-punch hole for the laser profile. Normally, you would do a punch single hit and this, then give the laser a place to start the cut if not on the edge of the sheet.
## <a name="chmtopic861"></a>**CALC\_PROFILE\_DRILL\_PLASMA**
#### **Purpose**
Used when you have a PUNCH/PLASMA combination machine that uses a pre-punched hole for starting a plasma profile.
#### **Syntax**
**:SECTION=CALC\_PROFILE\_DRILL\_PLASMA**
#### **Comments**
This section will be called when you do pre-punch hole for the plasma profile. Normally, you would do a punch single hit and this, then give the plasma a place to start the cut if not on the edge of the sheet.
## <a name="chmtopic367"></a>**CALC\_QUERY\_POST**
#### **Purpose**
This is used in conjunction with CAMWorks Virtual Machine.  
#### **Comment**
Supported in CAMWorks 2013 and later. Not supported in any ProCAM product.

Available in Mill, Turn and Mill-Turn.
#### **Example**
:SECTION=CALC\_QUERY\_POST

:C:  IF QUERY\_ITEM\_ID = QUERY\_INT\_NUM\_TURRETS\_ABOVE THEN QUERY\_INT\_VAL=1 RETURN ENDIF

:C:  IF QUERY\_ITEM\_ID = QUERY\_INT\_NUM\_TURRETS\_BELOW THEN QUERY\_INT\_VAL=1 RETURN ENDIF

:C:  IF QUERY\_ITEM\_ID = QUERY\_GCODE\_DEFAULT\_WCS THEN

:C:  IF SECTIONEXIST(QUERY\_WCS) THEN

:C:  CALL(QUERY\_WCS)

:C:  RETURN

:C:  ELSE

:C:  CALL(AUTO\_QUERY\_WCS)

:C:  RETURN

:C:  ENDIF

:C:  ENDIF

:C:  IF QUERY\_ITEM\_ID = QUERY\_GCODE\_WCS THEN

:C:  IF SECTIONEXIST(QUERY\_WCS) THEN

:C:  CALL(QUERY\_WCS)

:C:  RETURN

:C:  ELSE

:C:  CALL(AUTO\_QUERY\_WCS)

:C:  RETURN

:C:  ENDIF

:C:  ENDIF

:C:  IF QUERY\_ITEM\_ID = QUERY\_INT\_LENGTH\_REG THEN QUERY\_INT\_VAL=TOOL RETURN ENDIF

:C:  IF QUERY\_ITEM\_ID = QUERY\_INT\_OFFSET\_REG THEN CALL(CALC\_QUERY\_DIAM\_OFFSET\_REG) RETURN ENDIF

:C:  IF QUERY\_ITEM\_ID = QUERY\_GCODE\_AXIS\_NAMES\_T1A THEN CALL(QUERY\_AXIS\_NAMES\_T1A) RETURN ENDIF

:C:  IF QUERY\_ITEM\_ID = QUERY\_GCODE\_AXIS\_NAMES\_T2A THEN CALL(QUERY\_AXIS\_NAMES\_T2A) RETURN ENDIF

:C:  IF QUERY\_ITEM\_ID = QUERY\_GCODE\_AXIS\_NAMES\_T1B THEN CALL(QUERY\_AXIS\_NAMES\_T1B) RETURN ENDIF

:C:  IF QUERY\_ITEM\_ID = QUERY\_GCODE\_AXIS\_NAMES\_T2B THEN CALL(QUERY\_AXIS\_NAMES\_T2B) RETURN ENDIF


## <a name="chmtopic864"></a>**CALC\_RAPID\_MOVE\_SHEAR**
#### **Purpose**
Shear system rapid move calc section.
#### **Syntax**
**:SECTION=CALC\_RAPID\_MOVE\_SHEAR**
#### **Comments**
This section will be called for every rapid move that occurs while you are shearing.
## <a name="chmtopic862"></a>**CALC\_RAPID\_TO\_TRAPDOOR\_LASER**
#### **Purpose**
Laser system rapid move to trap door calc section.
#### **Syntax**
**:SECTION=CALC\_RAPID\_TO\_TRAPDOOR\_LASER**
#### **Comments**
This section will be called when a trap door is attached to any entity. The header command :TRAPDOOR must equal either DROP or TILT. If this header command is not in the post or is set to FALSE, then you will not get to this calc section.
## <a name="chmtopic860"></a>**CALC\_RAPID\_TO\_TRAPDOOR\_PLASMA**
#### **Purpose**
Plasma system rapid move to trap door calc section.
#### **Syntax**
**:SECTION=CALC\_RAPID\_TO\_TRAPDOOR\_PLASMA**
#### **Comments**
This section will be called when a trap door is attached to any entity. The header command :TRAPDOOR must equal either DROP or TILT. If this header command is not in the post or is set to FALSE, then you will not get to this calc section.
## <a name="chmtopic873"></a>**CALC\_REPOSITION\_SHEAR**
#### **Purpose**
Shear system reposition calc section.
#### **Syntax**
**:SECTION=CALC\_REPOSITION\_SHEAR**
#### **Comments**
This section will be called for every reposition created while you are shearing.
## <a name="chmtopic857"></a>**CALC\_SET\_PRE\_POSITION\_ROTARY\_TYPE**
#### **Purpose**
This system section handles the 5th axis preposition and simultaneous output. It will be called automatically in a Mill 4th or 5th axis Preposition operation to set the preferred 4th axis preposition axis output values, either in ROT\_TILT\_A or ROT\_TILT\_B.
#### **Syntax**
Integer variable: PRE\_POSITION\_ROTARY\_TYPE

System Constants

ROTARY\_TYPE\_A = 4

ROTARY\_TYPE\_B = 5
#### **Comments**
Currently, posting will assume ROT\_TILT\_B for a 4th axis preposition move. A wrapped feature will always be ROT\_TILT\_A.

PRE\_POSITION\_ROTARY\_TYPE can be set by two constants ROTARY\_TYPE\_A and ROTARY\_TYPE\_B. Setting this to ROTARY\_TYPE\_B supports old preposition posts.

Supported in CAMWorks 2007 and later. Not supported in any ProCAM product.
#### **Example**
:SECTION=CALC\_SET\_PRE\_POSITION\_ROTARY\_TYPE

:C: FOURTH\_AXIS\_SELECTION=ROTARY\_TYPE\_B

:C: IF FOURTH\_AXIS\_SELECTION>3 AND FOURTH\_AXIS\_SELECTION<6 THEN

:C: IF CAMWORKS\_VER>CAM\_REV2006EX THEN

:C: PRE\_POSITION\_ROTARY\_TYPE=FOURTH\_AXIS\_SELECTION

:C: ENDIF

:C: ENDIF
## <a name="chmtopic125"></a>**CALC\_SET\_TURRET\_CHANNEL**
#### **Purpose**
CALC\_SET\_TURRET\_CHANNEL gets called when a change in turret is encountered so that the post can switch to the correct turret output file.
**\

#### **Comments**
Associated post variables available are:  

- [TURRET_NUM](#chmtopic115)
- [P_TURRET_NUM](#chmtopic115)
- [N_TURRET_NUM](#chmtopic115)
- [NEXT_USER_TURRET_NUM](#chmtopic102)
- [SYNCED_WITH_REAR1](#chmtopic110)
- [SYNCED_WITH_FRONT1](#chmtopic108)
- [SYNCED_WITH_REAR2](#chmtopic111)
- [SYNCED_WITH_FRONT2](#chmtopic109)
- [NUM_TURRETS_REAR](#chmtopic282)
- [NUM_TURRETS_FRONT](#chmtopic281)

Associated constants are:

- [REAR1](#chmbookmark38)
- [FRONT1](#chmbookmark36)
- [REAR2](#chmbookmark39)  
- [FRONT2](#chmbookmark37)
## <a name="chmtopic859"></a>**CALC\_SHIFT\_TOOL\_LATHE**
#### **Purpose**
This section of system will be called in a lathe finish grooving cycle if a shift from one side of the groove tool to the opposite side is detected.
#### **Syntax**
**:SECTION=CALC\_SHIFT\_TOOL\_LATHE**
#### **Comments**
Supported in CAMWorks 2007 and later. Not supported in any ProCAM product.

These sections need to be added to the \*src file: SHIFT\_OFFSET\_PRIMARY and SHIFT\_OFFSET\_SECONDARY.



:SECTION=CALC\_SHIFT\_TOOL\_LATHE

:SECTION: SHIFT\_OFFSET\_PRIMARY

:SECTION: SHIFT\_OFFSET\_SECONDARY
## <a name="chmtopic858"></a>**CALC\_SLOWDOWN\_SPEED**
#### **Purpose**
Called in a lathe cutoff cycle if a slowdown is selected in the cutoff operation.
#### **Syntax**
**:SECTION=CALC\_SLOWDOWN\_SPEED**
#### **Comments**
Supported in CAMWorks 2007 and later. Not supported in any ProCAM product.

The section needs to be in the \*.src file: CHANGE\_SPEED.

:SECTION=CALC\_SLOWDOWN\_SPEED

:SECTION:=CHANGE\_SPEED
## <a name="chmtopic866"></a>**CALC\_SUB\_TOOL\_CHANGE\_SHEAR**
#### **Purpose**
Shear system sub tool change calc section.
#### **Syntax**
**:SECTION=CALC\_SUB\_TOOL\_CHANGE\_SHEAR**
#### **Comments**
This section will be called for every tool change that occurs after the first tool change while you are shearing.
## <a name="chmtopic856"></a>**CALC\_TOOL\_INITIALIZE**
#### **Purpose**
Mill calc section for setting 4 and 5 axis HEAD\_LEN tool parameters. When you have a machine that has the Head that rotates or tilts and you need to add the tool length on to the posted output. Used in ProCAM II 2004 or CAMWorks 2005 or newer versions only.
#### **Syntax**
**:SECTION=CALC\_TOOL\_INITIALIZE**

:C: HEAD\_LEN=(INIT\_TOOL\_LENGTH+head\_length)
#### **Comments**
The post will only get to this section when you have either :4AXIS\_X\_MILLING=TRUE, :4AXIS\_Y\_MILLING=TRUE or :5AXIS\_MILLING=TRUE, It will get to this section before it gets to CALC\_START\_OPERATION for the first time.

INIT\_TOOL\_LENGTH is a system post variable.

INIT\_TOOL\_LENGTH  holds the tool length from tool definition.

Head\_length = is a post question and it can be added or subtracted.
## <a name="chmtopic931"></a>**AUTOINDEX**
#### **Purpose**
Tool station number.
#### **Syntax**
**:AUTOINDEX=YES or NO**
#### **Comments**
This command defines whether this is auto indexable or not. This should be set to NO if not a punch. This should be set to YES if punch station is auto indexable.
#### **Example**
STATION\_NUM=01

**AUTOINDEX=NO**

KEYSIZE=4

KEYED=YES

LARGEDIAM=3.000000

XWDEAD=8.000000

YHDEAD=4.000000

XLORANGE=-1.000000

YLORANGE=-1.000000

XHIRANGE=50.000000

YHIRANGE=30.000000
## <a name="chmtopic933"></a>**KEYED**
#### **Purpose**
Tool station keyed.
#### **Syntax**
**:KEYED=YES or NO**
#### **Comments**
This command defines if the tool is keyed. Normally, you would set this to YES.
#### **Example**
STATION\_NUM=01

AUTOINDEX=NO

KEYSIZE=4

**KEYED=YES**

LARGEDIAM=3.000000

XWDEAD=8.000000

YHDEAD=4.000000

XLORANGE=-1.000000

YLORANGE=-1.000000

XHIRANGE=50.000000

YHIRANGE=30.000000
## <a name="chmtopic935"></a>**KEYSIZE**
#### **Purpose**
Tool station key size.
#### **Syntax**
**:KEYSIZE=4**
#### **Comments**
This command defines what size the key is:

|1|=|.5|
| :- | :- | :- |
|2|=|1\.25|
|3|=|2\.0|
|4|=|3\.5|
|5|=|4\.5|
|6|=|greater than 4.5|



If not a punch tool, then set KEYSIZE=5
#### **Example**
STATION\_NUM=01

AUTOINDEX=NO

**KEYSIZE=4**

KEYED=YES

LARGEDIAM=3.000000

XWDEAD=8.000000

YHDEAD=4.000000

XLORANGE=-1.000000

YLORANGE=-1.000000

XHIRANGE=50.000000

YHIRANGE=30.000000
## <a name="chmtopic937"></a>**LARGEDIAM**
#### **Purpose**
Tool station largest diameter used.
#### **Syntax**
**:LARGEDIAM=3.000000**
#### **Comments**
This command defines how big a diameter tool you can use in this station.
#### **Example**
STATION\_NUM=01

AUTOINDEX=NO

KEYSIZE=4

KEYED=YES

**LARGEDIAM=3.000000**

XWDEAD=8.000000

YHDEAD=4.000000

XLORANGE=-1.000000

YLORANGE=-1.000000

XHIRANGE=50.000000

YHIRANGE=30.000000
## <a name="chmtopic939"></a>**STATION\_NUM**
#### **Purpose**
Tool station number,
#### **Syntax**
**:STATION\_NUM=01**
#### **Comments**
This command defines the tool number.
#### **Example**
**STATION\_NUM=01**

AUTOINDEX=NO

KEYSIZE=4

KEYED=YES

LARGEDIAM=3.000000

XWDEAD=8.000000

YHDEAD=4.000000

XLORANGE=-1.000000

YLORANGE=-1.000000

XHIRANGE=50.000000

YHIRANGE=30.000000
## <a name="chmtopic941"></a>**XWDEAD**
#### **Purpose**
Define X dead zone.
#### **Syntax**
**:XWDEAD=8.000000**
#### **Comments**
This command defines how big the "X" width dead zone of a punch clamp is. If the system is not a punch, laser or plasma then it does not matter what you set this to.
#### **Example**
STATION\_NUM=01

AUTOINDEX=NO

KEYSIZE=4

KEYED=YES

LARGEDIAM=3.000000

**XWDEAD=8.000000**

YHDEAD=4.000000

XLORANGE=-1.000000

YLORANGE=-1.000000

XHIRANGE=50.000000

YHIRANGE=30.000000
## <a name="chmtopic943"></a>**YHDEAD**
#### **Purpose**
Define Y dead zone.
#### **Syntax**
**:YHDEAD=4.000000**
#### **Comments**
This command defines how big the "Y" height dead zone of a punch clamp is. If the system is not a punch, laser or plasma, you can set this to anything.
#### **Example**
STATION\_NUM=01

AUTOINDEX=NO

KEYSIZE=4

KEYED=YES

LARGEDIAM=3.000000

XWDEAD=8.000000

**YHDEAD=4.000000**

XLORANGE=-1.000000

YLORANGE=-1.000000

XHIRANGE=50.000000

YHIRANGE=30.000000
## <a name="chmtopic945"></a>**XHIRANGE**
#### **Purpose**
Define X travel high range.
#### **Syntax**
**:XHIRANGE=50.000000**
#### **Comments**
This command defines how far in the X plus direction you can travel. If the system is not a punch, plasma or laser, then you can set this to anything.
#### **Example**
STATION\_NUM=01

AUTOINDEX=NO

KEYSIZE=4

KEYED=YES

LARGEDIAM=3.000000

XWDEAD=8.000000

YHDEAD=4.000000

XLORANGE=-1.000000

YLORANGE=-1.000000

**XHIRANGE=50.000000**

YHIRANGE=30.000000
## <a name="chmtopic947"></a>**YHIRANGE**
#### **Purpose**
Define Y travel high range.
#### **Syntax**
**:YHIRANGE=50.000000**
#### **Comments**
This command defines how far in the Y plus direction you can travel. If the system is not a punch, plasma or laser, then you can set this to anything.
#### **Example**
STATION\_NUM=01

AUTOINDEX=NO

KEYSIZE=4

KEYED=YES

LARGEDIAM=3.000000

XWDEAD=8.000000

YHDEAD=4.000000

XLORANGE=-1.000000

YLORANGE=-1.000000

XHIRANGE=50.000000

**YHIRANGE=30.000000**
## <a name="chmtopic949"></a>**XLORANGE**
#### **Purpose**
Define X travel low range.
#### **Syntax**
**:XLORANGE=1.000000**
#### **Comments**
This command defines how far to the left side of the table you can travel or how far in the X minus direction you can travel. If the system is not a punch, plasma or laser, then you can set this to anything.
#### **Example**
STATION\_NUM=01

AUTOINDEX=NO

KEYSIZE=4

KEYED=YES

LARGEDIAM=3.000000

XWDEAD=8.000000

YHDEAD=4.000000

**XLORANGE=-1.000000**

YLORANGE=-1.000000

XHIRANGE=50.000000

YHIRANGE=30.000000
## <a name="chmtopic951"></a>**YLORANGE**
#### **Purpose**
Define Y travel low range.
#### **Syntax**
**:YLORANGE=1.000000**
#### **Comments**
This command defines how far in the Y minus direction you can travel. If the system is not a punch, plasma or laser, then you can set this to anything.
#### **Example**
STATION\_NUM=01

AUTOINDEX=NO

KEYSIZE=4

KEYED=YES

LARGEDIAM=3.000000

XWDEAD=8.000000

YHDEAD=4.000000

XLORANGE=-1.000000

**YLORANGE=-1.000000**

XHIRANGE=50.000000

YHIRANGE=30.000000
## <a name="chmtopic953"></a>**4AXIS\_X\_MILLING**
#### **Purpose**
Allows access to 4 axis milling.
#### **Syntax**
**:4AXIS\_X\_MILLING=TRUE or FALSE**
#### **Comments**
This command should be set to FALSE if not using 4 axis work.

This command should be set to TRUE if rotating about the X axis.

This can be done only in 3D CAD.
## <a name="chmtopic955"></a>**4AXIS\_Y\_MILLING**
#### **Purpose**
Allows access to 4 axis milling.
#### **Syntax**
**:4AXIS\_Y\_MILLING=TRUE or FALSE**
#### **Comments**
This command should be set to FALSE if not using 4 axis work.

This command should be set to TRUE if rotating about the Y axis.

This can be done only in 3D CAD.
## <a name="chmtopic957"></a>**5AXIS\_MILLING**
#### **Purpose**
Allows access to 5 axis milling.
#### **Syntax**
**:5AXIS\_MILLING=TRUE or FALSE**
#### **Comments**
This command should be set to FALSE if not using 5 axis work. This can be done only in 3D CAD.
## <a name="chmtopic212"></a>**:ALLOW\_B\_AXIS\_OFFSET\_REAR**
#### **Purpose**
For handling B Axis angles in Turn and Mill-Turn Turning operations.

If set to FALSE axis angles will not be available.

**If set to TRUE, then current post supports B Axis angles.**
#### **Syntax**
**:ALLOW\_B\_AXIS\_OFFSET\_REAR = TRUE or FALSE**
#### **Comments**
If this header is not in the post SRC file, then the B Axis angles will not be available.
## <a name="chmtopic77"></a>**:ALLOW\_B\_AXIS\_SIMULTANEOUS\_CUTTING**
#### **Purpose**
Allows Simultaneous B Axis movement in Rough and Contour Turn operations.

If set to FALSE, this option will not be available in post.

**If set to TRUE,** this option will be available in post**.**
#### **Syntax**
**:ALLOW\_B\_AXIS\_SIMULTANEOUS\_CUTTING = TRUE or FALSE**
#### **Comments**
If this header is not in the post SRC file, then this option will not be available.

To be used in CAMWorks 2019 and later versions.
## <a name="chmtopic99"></a>**:ALLOW\_FIRST\_FEED\_SYNC\_ON\_CANNED\_CYCLE**
#### **Purpose**
Used for handling first feed syncing of Canned Turn Roughing operations generated for OD/ID and Face Features.

If set to FALSE, this option will not be available in post.

**If set to TRUE, this option will be available in post**.
#### **Syntax**
**:ALLOW\_FIRST\_FEED\_SYNC\_ON\_CANNED\_CYCLE = TRUE or FALSE**
#### **Comments**
If this header is not present in the post SRC file, then this option will not be available. To be used in CAMWorks 2019 SP0 or higher versions.
## <a name="chmtopic209"></a>**:ALLOW\_GUN\_DRILLING**
#### **Purpose**
For handling Gun drilling in Mill and Mill-Turn drilling operations.

If set to FALSE Gun drilling will not be available.

**If set to TRUE, then current post supports Gun drilling.**
#### **Syntax**
**:ALLOW\_GUN\_DRILLING = TRUE or FALSE**
#### **Comments**
If this header is not in the post SRC file, then the Gun drilling will not be available.


## <a name="chmtopic211"></a>**:ALLOW\_GUN\_DRILLING\_CANNED\_CYCLE**
#### **Purpose**
For handling Canned Gun Drilling in Mill and Mill-Turn Drilling operations.

If set to FALSE canned gun drilling will not be available.

**If set to TRUE, then current post supports canned gun Drilling.**
#### **Syntax**
**:ALLOW\_GUN\_DRILLING\_CANNED\_CYCLE = TRUE or FALSE**
#### **Comments**
If this header is not in the post SRC file, then the canned gun drilling will not be available. Not available in CAMWorks 2016 but in a future version.
## <a name="chmtopic210"></a>**:ALLOW\_LONG\_CODE\_DRILLING\_CYCLES**
#### **Purpose**
For handling long code Drilling in Mill and Mill-Turn Drilling operations.

If set to FALSE long code drilling will not be available.

**If set to TRUE, then current post supports long code drilling.**
#### **Syntax**
**:ALLOW\_LONG\_CODE\_DRILLING\_CYCLES = TRUE or FALSE**
#### **Comments**
If this header is not in the post SRC file, then the long code drilling will not be available. Not available in CAMWorks 2016 but in a future version.


## <a name="chmtopic155"></a>**:ALLOW\_MAX\_RPM\_BY\_OPER**
#### **Purpose**
For handling maximum RPM output from the Operation Parameters dialog box of turning operations in Turn and Mill-Turn mode.
#### **Syntax**
**:ALLOW\_MAX\_RPM\_BY\_OPER = TRUE or FALSE**
#### **Comments**
[:ALLOW_PART_MAX_RPM](#chmtopic154) header must be set to TRUE  for this header to work properly.

If set to FALSE, then Maximum RPM in the Operation Parameters dialog box will not be available.

If set to TRUE, then Maximum RPM in the Operation Parameters dialog box will be available.

**If this header is not in the post SRC file, then this option will not be available.**
## <a name="chmtopic98"></a>**:ALLOW\_MIN\_PECK\_ON\_VARIABLE\_CANNED\_CYCLE**
#### **Purpose**
For handling minimum peck on canned variable pecking cycle for Mill and Mill-Turn drilling operations (Drill, Center Drill, Ream,Countersink, Counterbore).

If set to FALSE, minimum peck option will not be available.

**If set to TRUE, then** minimum peck option will be available.
#### **Syntax**
**:ALLOW\_MIN\_PECK\_ON\_VARIABLE\_CANNED\_CYCLE = TRUE or FALSE**
#### **Comments**
If this header is not in the post SRC file, then this option will not be available. To be used in CAMWorks 2019 SP0 or higher versions.


## <a name="chmtopic154"></a>**:ALLOW\_PART\_MAX\_RPM**
#### **Purpose**
For handling maximum RPM output from the TechDB for turning operations in Turn and Mill-Turn mode.
#### **Syntax**
**:ALLOW\_PART\_MAX\_RPM = TRUE or FALSE**
#### **Comments**
If set to FALSE, Maximum RPM from the TechDB will not be available.

If set to TRUE, then** Maximum RPM from the TechDB will be available.

If this header is not in the post SRC file, then this option will not be available.


## <a name="chmtopic15"></a>**:ALLOW\_PROBING=TRUE or FALSE**
#### **Type**
**INTEGER**
#### **Usage**
Sets the post to support probing cycles. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic969"></a>**ARC\_TO\_ARC**
#### **Purpose**
EDM 4 axis arc definition.
#### **Syntax**
**:ARC\_TO\_ARC=TRUE or FALSE**
#### **Comments**
Defines whether this post can do 4 axis GO2 or GO3 output if top and bottom surface arcs have equal radii. This can be done only in EDM.
## <a name="chmtopic971"></a>**ARCS**
#### **Purpose**
Global arc flag.
#### **Syntax**
**:ARCS=RADIAL or CENTER**
#### **Comments**
This command determines if arcs will output a radial command or I's and J's.

If set to RADIAL, then arc command output will output R's.

If set to CENTER, then arc command output will output I's and J's.
## <a name="chmtopic973"></a>**BCL\_FORMAT**
#### **Purpose**
Output BCL format.
#### **Syntax**
**:BCL\_FORMAT=TRUE or FALSE**
#### **Comments**
This command determines whether the output is BCL or not. BCL stands for Binary Cutter Location. The file is a fixed binary output called \*.BCL.
## <a name="chmtopic975"></a>**CHAMFER\_CORNER**
#### **Purpose**
EDM 2 axis corner definition.
#### **Syntax**
**:CHAMFER\_CORNER=TRUE or FALSE**
#### **Comments**
Defines whether this post can do 2 axis chamfer corners. This can only be done in EDM.
## <a name="chmtopic977"></a>**CONIC\_CORNER**
#### **Purpose**
EDM 2 axis corner definition.
#### **Syntax**
**:CONIC\_CORNER=TRUE or FALSE**
#### **Comments**
Defines whether this post can do 2 axis conic corners. This can be done only in EDM.
## <a name="chmtopic979"></a>**DECIMAL**
#### **Purpose**
Global decimal flag.
#### **Syntax**
**:DECIMAL=TRUE or FALSE**
#### **Comments**
This command if code output has decimals or not.
## <a name="chmtopic982"></a>**DUAL\_SPINDLE**
#### **Purpose**
Allows Turning or Mill/Turn system to machine from two different spindles.
#### **Command**
**DUAL\_SPINDLE=TRUE or FALSE**
#### **Comments**
See [DSPINDLE](#chmtopic981) for more information.
## <a name="chmtopic984"></a>**EDM4AXIS**
#### **Purpose**
EDM 4 axis definition.
#### **Syntax**
**:EDM4AXIS=TRUE or FALSE**
#### **Comments**
Defines whether this post can do X,Y,U,V 4-axis output. This can be done only in EDM.
## <a name="chmtopic986"></a>**EQUAL\_CORNER**
#### **Purpose**
EDM 2 axis corner definition.
#### **Syntax**
**:EQUAL\_CORNER=TRUE or FALSE**
#### **Comments**
Defines whether this post can do 2 axis equal corners. This can be done only in EDM.
## <a name="chmtopic988"></a>**FACE\_ARC**
#### **Purpose**
Lathe/Mill Face arc definition.
#### **Syntax**
**:FACE\_ARC=FREE, FIXED or BOTH**
#### **Comments**
Defines if the rotation axis on face arcs can be free, fixed or both free and fixed. This can be done only in Lathe/Mill.
## <a name="chmtopic990"></a>**FACE\_DRILL**
#### **Purpose**
Lathe/Mill Face drill definition.
#### **Syntax**
**:FACE\_DRILL=FREE, FIXED or BOTH**
#### **Comments**
Defines if the rotation axis on face drilling can be free, fixed or both free and fixed. This can only be done in Lathe/Mill.
## <a name="chmtopic992"></a>**FACE\_MILL**
#### **Purpose**
Lathe/Mill Face mill definition.
#### **Syntax**
**:FACE\_MILL=FREE, FIXED or BOTH**
#### **Comments**
Defines if the rotation axis on face milling can be free, fixed or both free and fixed. This can be done only in Lathe/Mill.
## <a name="chmtopic156"></a>**FACE\_MILL=FIXED\_OR\_X+\_ONLY**
#### **Purpose**
For handling features that are either done in all quadrants of a fixed operation or in the X+ quadrant only for Face Milling operations in Mill-Turn mode.
#### **Syntax**
**:MILL\_FACE = FIXED\_OR\_X+\_ONLY  (New option for CAMWorks 2017)**

**:MILL\_FACE = FREE   (Current Option)**

**:MILL\_FACE = FIXED  (Current Option)**

**:MILL\_FACE = BOTH   (Current Option)**
**\


There is a post question that can be associated with this header command.  Previously, there were only three selections available and the default selection was “Single About Y”. If the post did not have this question, then too the default was “Single About Y”.  To address this issue, a new option for selection “Force Rotation About Y” has been added in CAMWorks SP0. An example is given below for reference.



**:ATTRNAME=auto rotate type**

**:ATTRTYPE=SELECT**

**:ATTREMARK=Auto Rotate Type**

**:ATTRSEL=N**

**:ATTRTITLE=Auto Rotate Type**

**:ATTRSELSTR=Single About Y**

**:ATTRSELSTR=Single Y Plus**

**:ATTRSELSTR=Multiple About Y**

**:ATTRSELSTR=Force Rotation About Y**

**:ATTRDEFAULT=1**

**:ATTRUSED=1**

**:ATTREND**
## <a name="chmtopic157"></a>**FACE\_MILL=CONVERT\_X+\_ONLY\_TO\_FIXED\_OR\_X+\_ONLY**
#### **Purpose**
For handling features that are either done in all quadrants of a fixed operation or in the X+ quadrant only for face milling operations in Mill-Turn mode. This operation is the same as [FIXED_OR_X+_ONLY](#chmtopic156). However, by default, when legacy parts are loaded with the optional X+ option as TRUE.


#### **Syntax**
**:MILL\_FACE = CONVERT\_X+\_ONLY\_TO\_FIXED\_OR\_X+\_ONLY  (New option for CAMWorks 2017)**

**:MILL\_FACE = FREE   (Current Option)**

**:MILL\_FACE = FIXED  (Current Option)**

**:MILL\_FACE = BOTH   (Current Option)**


## <a name="chmtopic73"></a>**:FORCE\_UPPERCASE\_OUTPUT**
#### **Type**
Integer
#### **Usage:**
Sets the posted output to be all upper case. 

To be used in CAMWorks 2019 SP2 or higher versions.
#### **Syntax:**
:FORCE\_UPPERCASE\_OUTPUT= TRUE or FALSE


## <a name="chmtopic997"></a>**G\_INT\_LEFT\_PLACES**
#### **Purpose**
Global integer places to the left of the decimal.
#### **Syntax**
**:G\_INT\_LEFT\_PLACES=2**
#### **Comments**
This defines the integer places to the left of the decimal.
## <a name="chmtopic999"></a>**G\_LEFT\_PLACES**
#### **Purpose**
Global decimal places to the left of the decimal.
#### **Syntax**
**:G\_LEFT\_PLACES=3**
#### **Comments**
This defines the decimal places to the left of the decimal.
## <a name="chmtopic1001"></a>**G\_RIGHT\_PLACES**
#### **Purpose**
Global decimal places to the right of the decimal.
#### **Syntax**
**:G\_RIGHT\_PLACES=3**
#### **Comments**
This defines the decimal places to the right of the decimal.
## <a name="chmtopic277"></a>**GENERIC\_POST**
#### **Purpose**
Can be used with any post.
#### **Syntax**
**:GENERIC\_POST=TRUE or FALSE**
#### **Comments**
Set to “TRUE” if post will be used as a generic post for Eureka standard APT output. To be used in CAMWorks 2014 or newer version.
## <a name="chmtopic1004"></a>**HELICAL**
#### **Purpose**
This command allows helical arc moves at start of profile.
#### **Syntax**
**:HELICAL=TRUE or FALSE**
#### **Comments**
This command is used only for 2 axis milling in the ProCAM 2D system. For 2.5 axis milling in ProCAM 3D and in CAMWorks, no post customization is required for a spiral ramp at start hole.

To customize a post to include the option to spiral ramp at start hole, edit the .src post file, then recompile. In the global header section, add the line indicated in italics below:

:SYSTEM=MILL

:LEADING=FALSE

:TRAILING=FALSE

:DECIMAL=TRUE

:QUAD=NO181

.

.

.

:G\_INT\_LEFT\_PLACES=2

:INT\_LEADING=TRUE

:INT\_TRAILING=TRUE

*:HELICAL=TRUE*

:5AXIS\_MILLING=FALSE
## <a name="chmtopic1006"></a>**INDEPENDENT\_CORNER**
#### **Purpose**
EDM 2 axis corner definition.
#### **Syntax**
**:INDEPENDENT\_CORNER=TRUE or FALSE**
#### **Comments**
Defines whether this post can do 2 axis independent corners. This can only be done in EDM.
## <a name="chmtopic1008"></a>**INT\_LEADING**
#### **Purpose**
Global integer leading flag.
#### **Syntax**
**:INT\_LEADING=TRUE or FALSE**
#### **Comments**
This command defines if integer has leading zeros or not.
## <a name="chmtopic1010"></a>**INT\_TRAILING**
#### **Purpose**
Global integer trailing flag.
#### **Syntax**
**:INT\_TRAILING=TRUE or FALSE**
#### **Comments**
This command defines if integer has trailing zeros or not.
## <a name="chmtopic1012"></a>**LASER\_PLASMA\_CUT\_DATA**
#### **Purpose**
The laser and plasma systems to use the external fabrication database for special cutting parameters while posting.
#### **Syntax**
**:LASER\_PLASMA\_CUT\_DATA=TRUE or FALSE**
#### **Comments**
This command should be set to FALSE if you do not need special cutting parameters output to the post.

This command should be set to TRUE if you need special cutting parameters output to the post. The files that are used when accessing the data are "FABDBENGLISH.MDB" in Inch or "FABDBMETRIC.MDB" in metric. The post needs to be setup to use this function. See using access database in the online help.
## <a name="chmtopic1014"></a>**LATHE**
#### **Purpose**
Mill 4th axis lathe definition.
#### **Syntax**
**:LATHE=TRUE or FALSE**
#### **Comments**
This command should be set to FALSE if doing a mill 4th axis cutting post.
## <a name="chmtopic1016"></a>**LAYOUT\_MACROS**
#### **Purpose**
Layout of macro's flag.
#### **Syntax**
**:LAYOUT\_MACROS=YES or NO**
#### **Comments**
This command defines if post can output multiple macro calls.
## <a name="chmtopic1018"></a>**LEADING**
#### **Purpose**
Global leading flag.
#### **Syntax**
**:LEADING=TRUE or FALSE**
#### **Comments**
This command determines if the code output has leading zeros or not.
## <a name="chmtopic435"></a>**LENGTH\_DIAM\_OFFSET\_FROM\_TOOL**
#### **Purpose**
Determines whether the post supports using the Coolant, Length comp and diameter comp from the tool definition or the post.
#### **Syntax**
**:LENGTH\_DIAM\_OFFSET\_FROM\_TOOL=TRUE or FALSE**
#### **Comments**
Supported in CAMWorks 2008 and later. Not supported in any ProCAM product.
## <a name="chmtopic1021"></a>**LIVE\_Y\_AXIS**
#### **Purpose**
Lathe/Mill Y axis definition.
#### **Syntax**
**:LIVE\_Y\_AXIS=TRUE or FALSE**
#### **Comments**
Defines if controller can do Y axis moves in Live C post. This can only be done only in Lathe/Mill.
## <a name="chmtopic1023"></a>**LOOK\_AHEAD**
#### **Purpose**
EDM look ahead definition.
#### **Syntax**
**:LOOK\_AHEAD=1**
#### **Comments**
Defines how many entities to look ahead for compensation. This can only be done in EDM.
## <a name="chmtopic1025"></a>**MACRO\_ROTATE**
#### **Purpose**
Allow macro rotation.
#### **Syntax**
**:MACRO\_ROTATE=TRUE or FALSE**
#### **Comments**
If you set to MACRO\_ROTATE\_X=FALSE, MACRO\_ROTATE\_Y=FALSE and MACRO\_ROTATE\_Z=FALSE, then XY numbers will rotate instead OD an angle. This can be done only in Mill.
## <a name="chmtopic1027"></a>**MACRO\_ROTATE\_X**
#### **Purpose**
Allow X axis rotation.
#### **Syntax**
**:MACRO\_ROTATE\_X=TRUE or FALSE**
#### **Comments**
Allows macro to rotate about the X axis. This can be done only in Mill.
## <a name="chmtopic1029"></a>**MACRO\_ROTATE\_Y**
#### **Purpose**
Allow Y axis rotation.
#### **Syntax**
**:MACRO\_ROTATE\_Y=TRUE or FALSE**
#### **Comments**
Allows macro to rotate about the Y axis. This can be done only in Mill.
## <a name="chmtopic1031"></a>**MACRO\_ROTATE\_Z**
#### **Purpose**
Allow Z axis rotation.
#### **Syntax**
**:MACRO\_ROTATE\_Z=TRUE or FALSE**
#### **Comments**
Allows macro to rotate about the Z axis. This can be done only in Mill.
## <a name="chmtopic1033"></a>**MACROS\_CALL**
#### **Purpose**
Calling single macro flag.
#### **Syntax**
**:MACROS\_CALL=BEFORE or AFTER**
#### **Comments**
This command defines if post will call a single macro before or after the subroutine. Used only if MACROS\_MAIN=DURING.
## <a name="chmtopic1035"></a>**MACROS\_LAYOUT**
#### **Purpose**
Macro layout flag.
#### **Syntax**
**:MACROS\_LAYOUT=BEFORE or AFTER**
#### **Comments**
This command defines if post will call a section called CALC\_MULTIPLE\_MACRO\_DEFINE\_PUNCH.
## <a name="chmtopic1037"></a>**MACROS\_MAIN**
#### **Purpose**
Subroutine call flag.
#### **Syntax**
**:MACROS\_MAIN=BEFORE, DURING or AFTER**
#### **Comments**
This command defines if the subroutine will be called before, after or during the main program.
## <a name="chmtopic1039"></a>**MACROS\_MULT**
#### **Purpose**
Calling multiple macro flag.
#### **Syntax**
**:MACROS\_MULT=BEFORE or AFTER**
#### **Comments**
This command defines if post will call a single macro before or after the subroutine. Used only if MACROS\_MAIN=DURING.
## <a name="chmtopic1041"></a>**MACROS\_OUT**
#### **Purpose**
Macro output flag.
#### **Syntax**
**:MACROS\_OUT=CALLED or NESTED**
#### **Comments**
If set to CALLED, then the output will be in the order it was created in CAD.

If set to NESTED, then output will be in the reverse order.
## <a name="chmtopic1043"></a>**MACROS\_REDEFINE**
#### **Purpose**
Redefine macro flag.
#### **Syntax**
**:MACROS\_REDEFINE=YES or NO**
#### **Comments**
This command determines if a macro has to be redefined each time it is called.
## <a name="chmtopic1045"></a>**MACROS\_ROTATE**
#### **Purpose**
Allows Laser or Plasma controllers to utilize rotating a macro and then call it with a subroutine call.
#### **Command**
**:MACROS\_ROTATE=TRUE or FALSE**
#### **Comments**
This command should be set to FALSE if your machine does not support rotating a macro and then call it.

Most machines do not allow you to create a macro at lets say zero degrees and call it then rotate it at 90 degrees and call the same subroutine. Normally what has to happen is once you rotate the macro the system has to recreate another macro define and then call that macro. The post variable that holds the rotated angle is ROTATE\_ANGLE\_Z.
## <a name="chmtopic1047"></a>**MACROS\_TAPE**
#### **Purpose**
Macro output flag.
#### **Syntax**
**:MACROS\_TAPE=SAME or SEPARATE**
#### **Comments**
If set to SAME, then the output will be in the same file \*.TXT.

If set to SEPARATE, then output of subroutine will be in a file called \*.SUB.
## <a name="chmtopic1049"></a>**MACROS\_XYZ**
#### **Purpose**
Allow Z axis in macros.
#### **Syntax**
**:MACROS\_XYZ=TRUE or FALSE**
#### **Comments**
This command allows the Z axis to step and repeat in a macro. This can be done only in Mill.
## <a name="chmtopic1051"></a>**MAXIMUM\_LINE**
#### **Purpose**
This command lets you set the maximum line length of \*.TXT files.
#### **Syntax**
**:MAXIMUM\_LINE=100**
#### **Comments**
The system default for this command is 100. If 100 is not a problem, then you can leave this command out of your source.
## <a name="chmtopic1053"></a>**METRIC\_SHIFT**
#### **Purpose**
Global metric shift flag.
#### **Syntax**
**:METRIC\_SHIFT=1**
#### **Comments**
This defines the amount of shift in the output when switching to metric.
## <a name="chmtopic208"></a>**MILL\_ADVANCED\_ENTRY\_RETRACT**
#### **Purpose**
For handling mill advanced Entry and Retract strategies in Mill-Turn operations.

If set to FALSE advanced Entry/Retract will not be available.

**If set to TRUE, then current post supports advanced Entry/Retract options.**
#### **Syntax**
**:MILL\_ADVANCED\_ENTRY\_RETRACT = TRUE or FALSE**
#### **Comments**
If this header is not in the post SRC file, then the advanced Entry/retract option will not be available.

The post **variable POST\_ADV\_ENTRY\_RETRACT will be set to the value of this header command.**

**If MILL\_ADVANCED\_ENTRY\_RETRACT = FALSE, then POST\_ADV\_ENTRY\_RETRACT = 0.**

**If MILL\_ADVANCED\_ENTRY\_RETRACT = TRUE, then POST\_ADV\_ENTRY\_RETRACT = 1.**
## <a name="chmtopic144"></a>**:MILL\_3AXIS\_ONLY**
#### **Purpose**
Lets CAMWorks know if post supports 4 axis or 5 axis preposition and 4 axis or 5 axis simultaneous output.
#### **Syntax**
**:MILL\_3AXIS\_ONLY = TRUE or FALSE**
#### **Comments**
If this header is not present in the post SRC file, then this option will be set to FALSE as default.
## <a name="chmtopic1057"></a>**MILL\_FACE\_POLAR**
#### **Purpose**
Allows Lathe/Mill (Live C) machines to use special G-code for doing milling on the FACE in CAMWorks only.
#### **Command**
**:MILL\_FACE\_POLAR=TRUE or FALSE**
#### **Comments**
This command should be set to FALSE if your machine does not support special G-code for doing milling on the FACE.

Set this command to TRUE if you have a machine that supports the special G-code for doing milling on the FACE.

When your machine supports this the post will output polar G-code output. The reason for using this is the feedrate is in either IPM or MMPM and not degree minutes, which requires a different degree minute feedrate on almost every line of code. Another reason is it can have machine compensation added, plus it is shorter code to do the same operation then in degree minutes.
## <a name="chmtopic1059"></a>**MILL\_OD\_CYLINDRICAL**
#### **Purpose**
Allows Lathe/Mill (Live C) machines to use special G-code for doing milling on the OD in CAMWorks only.
#### **Command**
**:MILL\_OD\_CYLINDRICAL=TRUE or FALSE**
#### **Comments**
This command should be set to FALSE if your machine does not support special G-code for doing milling on the OD.

Set this command to TRUE if you have a machine that supports the special G-code for doing milling on the OD.

When your machine supports this the post will output cylindrical G-code output. The reason for using this is the feedrate is in either IPM or MMPM and not degree minutes, which requires a different degree minute feedrate on almost every line of code. Another reason is it can have machine compensation added, plus it is shorter code to do the same operation then in degree minutes.
## <a name="chmtopic1061"></a>**MIRROR\_MACROS**
#### **Purpose**
Mirror macro flag.
#### **Syntax**
**:MIRROR\_MACROS=YES or NO**
#### **Comments**
This command is reserved for future use.
## <a name="chmtopic1063"></a>**MOVE\_CLAMP**
#### **Purpose**
Allows punch system to move a clamp manually and then passes information to the post for output.
#### **Command**
**:MOVE\_CLAMP=TRUE or FALSE**
#### **Comments**
This command should be set to FALSE if you do not have a machine that supports commands to move the clamps.

Set this command to TRUE if you have a machine that supports output code to move the clamps.

When you trigger a clamp move it is then passed to the punch post calc section CALC\_MOVE\_CLAMPS. It stores the clamp positioned amount in absolute numbers only in post system variables CLAMP1\_POSITION, CLAMP2\_POSITION, CLAMP3\_POSITION, CLAMP4\_POSITION. Up to 4 clamps are supported for this command.
## <a name="chmtopic1065"></a>**MULT\_MACROS**
#### **Purpose**
Multiple macro flag.
#### **Syntax**
**:MULT\_MACROS=YES or NO**
#### **Comments**
This command defines if post can output multiple macro calls.
## <a name="chmtopic1067"></a>**NO\_SET\_FILE**
#### **Purpose**
Allows the posted \*.set file to be created or not.
#### **Syntax**
**:NO\_SET\_FILE=TRUE or FALSE**
#### **Comments**
This command should be set to FALSE if you want the \*.set file to be created every time you post. If you do not want the \*.set file to be created then this needs to be set to TRUE.
## <a name="chmtopic1069"></a>**OD\_ARC**
#### **Purpose**
Lathe/Mill OD arc definition.
#### **Syntax**
**:OD\_ARC=FREE, FIXED or BOTH**
#### **Comments**
Defines if the rotation axis on OD arcs can be free, fixed or both free and fixed. This can only be done in Lathe/Mill.
## <a name="chmtopic1071"></a>**OD\_DRILL**
#### **Purpose**
Lathe/Mill OD drill definition.
#### **Syntax**
**:OD\_DRILL=FREE, FIXED or BOTH**
#### **Comments**
Defines if the rotation axis on OD drilling can be free, fixed or both free and fixed. This can be done only in Lathe/Mill.
## <a name="chmtopic1073"></a>**OD\_MILL**
#### **Purpose**
Lathe/Mill OD mill definition.
#### **Syntax**
**:OD\_MILL=FREE, FIXED or BOTH**
#### **Comments**
Defines if the rotation axis on OD milling can be free, fixed or both free and fixed. This can only be done in Lathe/Mill.
## <a name="chmtopic1075"></a>**PQCOMP**
#### **Purpose**
P and Q compensation flag.
#### **Syntax**
**:PQCOMP=TRUE or FALSE**
#### **Comments**
This command is reserved for future use.
## <a name="chmtopic1077"></a>**RIGHT\_ANGLE\_SHEAR\_ATTACHED**
#### **Purpose**
Allows world coordinate posted output when indexing in 4 and 5 axis assembly parts using CAMWorks 2005 or newer versions.
#### **Syntax**
**:RIGHT\_ANGLE\_SHEAR\_ATTACHED=TRUE or FALSE**
#### **Comments**
This command should be set to FALSE if you don’t need shear.

This command should be set to TRUE if you need shear and even though the post ":SYSTEM=PUNCH" you can use this header command to exit into shear.
## <a name="chmtopic1079"></a>**QUAD**
#### **Purpose**
Global quadrant arc flag.
#### **Syntax**
**:QUAD=TRUE, FALSE, NO181 or COORD**
#### **Comments**
This command determines if code output has quadrant arcs or not. I

If QUAD=TRUE, a 360 degree arc will take four blocks of code to generate that arc.

If QUAD=FALSE, a 360 degree arc will take only one block of code to generate that arc.

If QUAD=NO181, the code will generate that arc in two moves.

If QUAD=COORD, the code will generate tiny line moves set by the chord\_length attribute instead of arcs.
## <a name="chmtopic1081"></a>**QUALIFIED\_TOOLING**
#### **Purpose**
To retrieve tool offset information from a fixed structured external file.
#### **Syntax**
**:QUALIFIED\_TOOLING=\PROCAD\TOOL\TOOLFILE.F6M**
#### **Comments**
The above syntax shows where the external file is located.

This command should be put in the post header info.

Below is an example of what the external file might look like for lathe.

1111 or 2222 must be entered in the TOOL COMMENT in the tool pulldown for this to work.

|*ID*|*ZGL*|*XGL*|*Tool*|*Comment*|
| :- | :- | :- | :- | :- |
|1111,|5,|10,|7,|80 Degree Diamond|
|2222,|6\.375,|12\.5,|11,|.5 Diameter Drill|



The external file has 5 fields.

1. Field 1 is used by PROUNIV.EXE. It will match the "ID" field with the TOOL\_HOLDER\_NAME in lathe and TOOL\_COMMENT in mill.
1. Field 2 is a decimal field for the Z gauge.
1. Field 3 is a decimal field for the X gauge.
1. Field 4 is an integer field for the tool number.
1. Field 5 is a character field.

A comma is used as a field delimiter.

Below is an example of what the external file might look like for mill.

|*ID*|*Z Feed*|*X Feed*|*RPM*|*Comment*|
| :- | :- | :- | :- | :- |
|1,|5,|10,|1200,|1" End Mill|
|7|6\.375,|12\.5,|1100,|2" Ball Nose|


#### **Example**
:T: Z FEED=<#:TOOL\_ZGL> X FEED=<#:TOOL\_XGL>

:T: RPM=<"%4T":TOOL\_QTN> COMMENT=<TOOL\_QT\_COMMENT><EOL>
## <a name="chmtopic1083"></a>**SHARP\_CORNER**
#### **Purpose**
EDM 2 axis corner definition.
#### **Syntax**
**:SHARP\_CORNER=TRUE or FALSE**
#### **Comments**
Defines whether this post can do 2 axis sharp corners. This can be done only in EDM.
## <a name="chmtopic1085"></a>**SINGLE\_MACROS**
#### **Purpose**
Single macro flag.
#### **Syntax**
**:SINGLE\_MACROS=YES or NO**
#### **Comments**
This command defines if post can output single macro calls.
## <a name="chmtopic347"></a>**SINGLE\_Y\_AXIS\_DIRECTION**
#### **Purpose**
To be used with Mill/Turn posts
#### **Syntax**
**:SINGLE\_Y\_AXIS\_DIRECTION = TRUE or FALSE**  
#### **Comments**
If this is set to “TRUE then this will allow the new system changes to the Main and sub spindle Y axis direction to be transferred to the post as corrected values If this is set to “FALSE” then it assumes the post will make all the corrected changes manually to the posted output. If this header is not in the post then it assumes “FALSE” and the post will work as originally built.  


## <a name="chmtopic1088"></a>**SLOW\_INDEXER**
#### **Purpose**
Allows optimized autoindex output.
#### **Syntax**
**:SLOW\_INDEXER=TRUE or FALSE**
#### **Comments**
If this command should be set to TRUE, the system will generate optimized autoindex angles. It will punch all entities with the same autoindex angle, then go to the next autoindex angle, then the next until finished.
## <a name="chmtopic346"></a>**SORT\_BY\_TURRET**
#### **Purpose**
For use with 2 or more turrets in turn or mill turn post.

If set to FALSE operations are posted out as operation tree order.

If set to TRUE operations are posted out with all rear turret operations first then the front turret operations
#### **Syntax**
**:SORT\_BY\_TURRET = TRUE or FALSE**
#### **Comments**
This command should be set to FALSE if not using 2 or more turrets.

This command can be set to TRUE if using 2 or more turrets and output needs to be in separate files.
## <a name="chmtopic1091"></a>**SORTER\_ARM**
#### **Purpose**
Allows Laser, Plasma or Punch system to have sorter arm options available in ProCAM 2D.
#### **Command**
**:SORTER\_ARM=TRUE or FALSE**
#### **Comments**
This command should be set to FALSE if you do not have a machine that supports sorter arm commands.

Set this command to TRUE if you have a machine that supports output code to support sorter arm commands.

When you trigger a sorter arm move it does an auto attachment of "sorter arm pickup" attribute, then it attaches a "sorter arm release" attribute and then attaches a "sorter arm hit releases part "attribute. In the definition of each of these attributes is or should be defined an ATTRFUNC command to call a calc section for necessary output for this operation. Available post variables are ARM\_PICKUP\_X, ARM\_PICKUP\_Y, ARM\_DESTINATION\_X, ARM\_DESTINATION\_Y, ARM\_OFFSET, ARM\_ACTIVE\_CUPS.
## <a name="chmtopic1093"></a>**SPACE**
#### **Purpose**
Global spaces flag.
#### **Syntax**
**:SPACE=TRUE or FALSE**
#### **Comments**
This command determines if code output has spaces or not.
## <a name="chmtopic471"></a>**SYSTEM**
#### **Purpose**
System type.
#### **Syntax**
**:SYSTEM=PUNCH**
#### **Comments**
This command determines what system you are in:

PLASMA

PUNCH

PLASMA/PUNCH

LASER

EDM

LATHE

MILL

LATHE/MILL

LATHE4AX
## <a name="chmtopic1096"></a>**TAPER**
#### **Purpose**
EDM 2 axis taper definition.
#### **Syntax**
**:TAPER=TRUE or FALSE**
#### **Comments**
Defines whether this post can do 2 axis with taper output. This can be done only in EDM.
## <a name="chmtopic1098"></a>**TAPER\_DURING**
#### **Purpose**
EDM 2 axis corner definition.
#### **Syntax**
**:TAPER\_DURING=TRUE or FALSE**
#### **Comments**
Defines whether this post can do 2 axis taper during a move. This can be done only in EDM.
## <a name="chmtopic1100"></a>**TAPER\_FILLET**
#### **Purpose**
EDM taper fillet definition.
#### **Syntax**
**:TAPER\_FILLET=TRUE or FALSE**
#### **Comments**
Defines if controller can do taper filleting. This can be done only in EDM.
## <a name="chmtopic1102"></a>**TRAILING**
#### **Purpose**
Global trailing flag.
#### **Syntax**
**:TRAILING=TRUE OR FALSE**
#### **Comments**
This command determines if the code output has trailing zeros or not.
## <a name="chmtopic1104"></a>**TRAPDOOR**
#### **Purpose**
Allows post to create an auto Open Chute to be attached to a closed boundary.
#### **Command**
**:TRAPDOOR=FALSE, DROP or TILT**
#### **Comments**
This command should be set to FALSE if you do not have a trap door. If you have a trap door you can set this to DROP or TILT depending on the style of the machines trap door. Only one style of trap door can be set per post.
## <a name="chmtopic1106"></a>**USE\_SPECIAL\_TOOL\_TYPE**
#### **Purpose**
This command allows special tooling.
#### **Syntax**
**:USE\_SPECIAL\_TOOL\_TYPE=TRUE or FALSE**
#### **Comments**
If not using special tool type, set this command to FALSE.

If this command is set to TRUE, a special tool dialog box displays.
## <a name="chmtopic145"></a>**:USE\_STATION\_ID\_AS\_NAME**
#### **Purpose**
When this variable is set to TRUE, the Tool list generated for the CAMWorks Virtual Machine will use the ToolStation ID as the Tool Code. To be used in CAMWorks 2017 SP1 or higher versions.
#### **Syntax**
**:USE\_STATION\_ID\_AS\_NAME = TRUE or FALSE**
#### **Comments**
- **Default value assigned to this header command is FALSE.**
- **If this header command is not in the post SRC file, then this option will be defaulted to FALSE.**
- This header command has no effect on the posted code. It only affects the tool list of the CAMWorks Virtual Machine. 


## <a name="chmtopic270"></a>**USE\_TOOL\_COMMENT\_AS\_NAME**
#### **Purpose**
This will instruct Machine Simulation to use the Tool Comment as the Tool Name.
#### **Syntax**
**:USE\_TOOL\_COMMENT\_AS\_NAME=TRUE or FALSE**
#### **Comments**
If you are not going to use tool comments for tool names, then this command should be set to FALSE.

If you are going to use tool comments for tool names, then this command can be set to TRUE.


## <a name="chmtopic1110"></a>**VECTOR\_COMP**
#### **Purpose**
Allows a CAMWorks mill post to output X,Y,Z,I, and J in vector coordinates.
#### **Syntax**
**:VECTOR\_COMP=TRUE or FALSE**
#### **Comments**
This command should be set to FALSE if you do not need vector coordinates output.

This command should be set to TRUE if you need vector coordinates output. This will only apply in the CAMWorks advanced cutting operations. The post system variable "V\_COMP" will be set to "0" if operations not using this option and will be set to "1" if it is. Post system variables "XC", "YC", "ZC", "IC", "JC" and "KC" hold endpoints for the posted output. XC=ABS\_X\_END, YC=ABS\_Y\_END, ZC=ABS\_Z\_END, IC=I\_VECTOR, JC=J\_VECTOR and KC=K\_VECTOR.
## <a name="chmtopic1112"></a>**WORLD\_POSITIONING**
#### **Purpose**
Allows world coordinate posted output when indexing in 4 and 5 axis assembly parts using CAMWorks 2005 or newer versions.
#### **Syntax**
**:WORLD\_POSITIONING=TRUE or FALSE**
#### **Comments**
This command should be set to FALSE if you no not need world coordinate posted output in 4 and 5 axis indexing.

This command should be set to TRUE if you need world coordinate posted output in 4 and 5 axis indexing, which means that the posted output will not translate the numbers when indexing to another plane.
## <a name="chmtopic1114"></a>**ABS\_C\_END**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>Absolute X,Y,Z,C end point of move.</p><p>EDM: Absolute U,V secondary surface end point of move.</p><p>Lathe: Absolute U,W front turret end point of move.</p>||
|*Options*|N\_ABS\_C\_END|N\_ = next move|
| |P\_ABS\_C\_END|P\_ = previous move|

## <a name="chmtopic1116"></a>**ABS\_C\_START**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>Absolute X,Y,Z,C start point of move.</p><p>EDM: Absolute U,V secondary surface start point of move.</p><p>Lathe: Absolute U,W front turret start point of move</p>||
|*Options*|N\_ABS\_C\_START|N\_ = next move|
| |P\_ABS\_C\_START|P\_ = previous move|

## <a name="chmtopic1118"></a>**ABS\_I\_CENTER**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>I,J absolute center point of arc.</p><p>EDM: K,L absolute center point of secondary surface arc.</p><p>Lathe: K,L absolute center point of front turret arc.</p>||
|*Options*|N\_ABS\_I\_CENTER|N\_ = next arc, secondary surface arc or front turret arc|
| |P\_ABS\_I\_CENTER|P\_ = previous arc, secondary surface arc or front turret arc|

## <a name="chmtopic1120"></a>**ABS\_J\_CENTER**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>I,J absolute center point of arc.</p><p>EDM: K,L absolute center point of secondary surface arc.</p><p>Lathe: K,L absolute center point of front turret arc.</p>||
|*Options*|N\_ABS\_J\_CENTER|N\_ = next arc, secondary surface arc or front turret arc|
| |P\_ABS\_J\_CENTER|P\_ = previous arc, secondary surface arc or front turret arc|

## <a name="chmtopic1122"></a>**ABS\_K\_CENTER**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>I,J absolute center point of arc.</p><p>EDM: K,L absolute center point of secondary surface arc.</p><p>Lathe: K,L absolute center point of front turret arc.</p>||
|*Options*|N\_ABS\_K\_CENTER|N\_ = next arc, secondary surface arc or front turret arc|
| |P\_ABS\_K\_CENTER|P\_ = previous arc, secondary surface arc or front turret arc|

## <a name="chmtopic1124"></a>**ABS\_L\_CENTER**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>I,J absolute center point of arc.</p><p>EDM: K,L absolute center point of secondary surface arc.</p><p>Lathe: K,L absolute center point of front turret arc.</p>||
|*Options*|N\_ABS\_L\_CENTER|N\_ = next arc, secondary surface arc or front turret arc|
| |P\_ABS\_L\_CENTER|P\_ = previous arc, secondary surface arc or front turret arc|

## <a name="chmtopic1126"></a>**ABS\_U\_END**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>Absolute X,Y,Z,C end point of move.</p><p>EDM: Absolute U,V secondary surface end point of move.</p><p>Lathe: Absolute U,W front turret end point of move.</p>||
|*Options*|N\_ABS\_U\_END|N\_ = next move|
| |P\_ABS\_U\_END|P\_ = previous move|

## <a name="chmtopic1128"></a>**ABS\_U\_START**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>Absolute X,Y,Z,C start point of move.</p><p>EDM: Absolute U,V secondary surface start point of move.</p><p>Lathe: Absolute U,W front turret start point of move</p>||
|*Options*|N\_ABS\_U\_START|N\_ = next move|
| |P\_ABS\_U\_START|P\_ = previous move|

## <a name="chmtopic1130"></a>**ABS\_V\_END**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>Absolute X,Y,Z,C end point of move.</p><p>EDM: Absolute U,V secondary surface end point of move.</p><p>Lathe: Absolute U,W front turret end point of move.</p>||
|*Options*|N\_ABS\_V\_END|N\_ = next move|
| |P\_ABS\_V\_END|P\_ = previous move|

## <a name="chmtopic1132"></a>**ABS\_V\_START**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>Absolute X,Y,Z,C start point of move.</p><p>EDM: Absolute U,V secondary surface start point of move.</p><p>Lathe: Absolute U,W front turret start point of move</p>||
|*Options*|N\_ABS\_V\_START|N\_ = next move|
| |P\_ABS\_V\_START|P\_ = previous move|

## <a name="chmtopic1134"></a>**ABS\_W\_END**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>Absolute X,Y,Z,C end point of move.</p><p>EDM: Absolute U,V secondary surface end point of move.</p><p>Lathe: Absolute U,W front turret end point of move.</p>||
|*Options*|N\_ABS\_W\_END|N\_ = next move|
| |P\_ABS\_W\_YEND|P\_ = previous move|

## <a name="chmtopic1136"></a>**ABS\_W\_START**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>Absolute X,Y,Z,C start point of move.</p><p>EDM: Absolute U,V secondary surface start point of move.</p><p>Lathe: Absolute U,W front turret start point of move</p>||
|*Options*|N\_ABS\_W\_START|N\_ = next move|
| |P\_ABS\_W\_START|P\_ = previous move|

## <a name="chmtopic1138"></a>**ABS\_X\_END**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>Absolute X,Y,Z,C end point of move.</p><p>EDM: Absolute U,V secondary surface end point of move.</p><p>Lathe: Absolute U,W front turret end point of move.</p>||
|*Options*|N\_ABS\_X\_END|N\_ = next move|
| |P\_ABS\_X\_END|P\_ = previous move|
| |O\_ABS\_X\_END|O\_ = original end point (Punch)|

## <a name="chmtopic447"></a>**ABS\_X\_PART\_END**


|*Type*|DECIMAL||
| :- | :- | :- |
|*Usage*|Stores the current X end value, next X end value and previous X end value as world coordinates in a multiaxis operation. Available in Mill only. Supported in CAMWorks 2008 and later. Not supported in any ProCAM product.||
|*Options*|N\_ABS\_X\_PART END| |
| |P\_ABS\_X\_PART\_END| |


## <a name="chmtopic1141"></a>**ABS\_X\_START**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>Absolute X,Y,Z,C start point of move.</p><p>EDM: Absolute U,V secondary surface start point of move.</p><p>Lathe: Absolute U,W front turret start point of move</p>||
|*Options*|N\_ABS\_X\_START|N\_ = next move|
| |P\_ABS\_X\_START|P\_ = previous move|
| |O\_ABS\_X\_START|O\_ = original start point (Punch)|

## <a name="chmtopic1143"></a>**ABS\_Y\_END**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>Absolute X,Y,Z,C end point of move.</p><p>EDM: Absolute U,V secondary surface end point of move.</p><p>Lathe: Absolute U,W front turret end point of move.</p>||
|*Options*|N\_ABS\_Y\_END|N\_ = next move|
| |P\_ABS\_Y\_END|P\_ = previous move|
| |O\_ABS\_Y\_END|O\_ = original end point (Punch)|

## <a name="chmtopic448"></a>**ABS\_Y\_PART\_END**


|*Type*|DECIMAL||
| :- | :- | :- |
|*Usage*|Stores the current Y end value, next Y end value and previous Y end value as world coordinates in a multiaxis operation. Available in Mill only. Supported in CAMWorks 2008 and later. Not supported in any ProCAM product.||
|*Options*|N\_ABS\_Y\_PART END| |
| |P\_ABS\_Y\_PART\_END| |


## <a name="chmtopic1146"></a>**ABS\_Y\_START**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>Absolute X,Y,Z,C start point of move.</p><p>EDM: Absolute U,V secondary surface start point of move.</p><p>Lathe: Absolute U,W front turret start point of move</p>||
|*Options*|N\_ABS\_Y\_START|N\_ = next move|
| |P\_ABS\_Y\_START|P\_ = previous move|
| |O\_ABS\_Y\_START|O\_ = original start point (Punch)|

## <a name="chmtopic1148"></a>**ABS\_Z\_END**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>Absolute X,Y,Z,C end point of move.</p><p>EDM: Absolute U,V secondary surface end point of move.</p><p>Lathe: Absolute U,W front turret end point of move.</p>||
|*Options*|N\_ABS\_Z\_END|N\_ = next move|
| |P\_ABS\_Z\_END|P\_ = previous move|

## <a name="chmtopic449"></a>**ABS\_Z\_PART\_END**


|*Type*|DECIMAL||
| :- | :- | :- |
|*Usage*|Stores the current Z end value, next Z end value and previous Z end value as world coordinates in a multiaxis operation. Available in Mill only. Supported in CAMWorks 2008 and later. Not supported in any ProCAM product.||
|*Options*|N\_ABS\_Z\_PART END| |
| |P\_ABS\_Z\_PART\_END| |


## <a name="chmtopic1151"></a>**ABS\_Z\_START**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>Absolute X,Y,Z,C start point of move.</p><p>EDM: Absolute U,V secondary surface start point of move.</p><p>Lathe: Absolute U,W front turret start point of move</p>||
|*Options*|N\_ABS\_Z\_START|N\_ = next move|
| |P\_ABS\_Z\_START|P\_ = previous move|

## <a name="chmtopic1153"></a>**ANGLE**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Angle of a Line, Rapid, Grid, Line Pattern or Window move.|

|*Options*|N\_ANGLE|N\_ = angle of next Line, Rapid, Grid, Line Pattern or Window move|
| :- | :- | :- |
| |P\_ANGLE|P\_ = angle of previous Line, Rapid, Grid, Line Pattern or Window move|
| |O\_ANGLE|O\_ = angle of original Line, Rapid, Grid, Line Pattern or Window move (Punch)|

## <a name="chmtopic1155"></a>**ARC\_END\_ANGLE**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Absolute arc end angle.|

|*Options*|N\_ARC\_END\_ANGLE|N\_ = next absolute arc end angle|
| :- | :- | :- |
| |P\_ARC\_END\_ANGLE|P\_ = previous absolute arc end angle|
| |O\_ARC\_END\_ANGLE|O\_ = original absolute arc end angle (Punch)|
| |S\_ARC\_END\_ANGLE|S\_ = absolute arc end angle of secondary surface (EDM)|
| |S\_ARC\_END\_ANGLE|S\_ = absolute arc end angle of front turret (Lathe)|
| |S\_N\_ARC\_END\_ANGLE|<p>S\_N\_ = next absolute arc end angle of secondary surface<br>`  `(EDM)</p><p>S\_N\_ = next absolute arc end angle of front turret (Lathe)</p>|
| |S\_P\_ARC\_END\_ANGLE|<p>S\_P\_ = previous absolute arc end angle of secondary<br>`  `surface (EDM)</p><p>S\_P\_ = previous absolute arc end angle of front turret<br>`  `(Lathe)</p>|

## <a name="chmtopic1157"></a>**ARC\_RADIUS**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|Arc radius.||
|*Options*|N\_ARC\_RADIUS|N\_ = next move|
| |P\_ARC\_RADIUS|P\_ = previous move|
| |O\_ARC\_RADIUS|O\_ = original arc radius (Punch)|
| |S\_ARC\_RADIUS|S\_ = front turret arc radius (Lathe)|
| | |S\_ = secondary surface arc radius (EDM)|
| |S\_N\_ARC\_RADIUS|S\_N\_ = next secondary surface arc radius (EDM)|
| | |S\_N\_ = next front turret arc radius (Lathe)|
| |S\_P\_ARC\_RADIUS|S\_P\_ = previous secondary surface arc radius (EDM)|
| | |S\_P\_ = previous front turret arc radius (Lathe)|

## <a name="chmtopic1159"></a>**ARC\_START\_ANGLE**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Absolute arc start angle.|

|*Options*|N\_ARC\_START\_ANGLE|N\_ = next absolute arc start angle|
| :- | :- | :- |
| |P\_ARC\_START\_ANGLE|P\_ = previous absolute arc start angle|
| |O\_ARC\_START\_ANGLE|O\_ = original absolute arc start angle (Punch)|
| |S\_ARC\_START\_ANGLE|S\_ = absolute arc start angle of secondary surface (EDM)|
| |S\_ARC\_START\_ANGLE|S\_ = absolute arc start angle of front turret (Lathe)|
| |S\_N\_ARC\_START\_ANGLE|<p>S\_N\_ = next absolute arc start angle of secondary surface<br>(EDM)</p><p>S\_N\_ = next absolute arc start angle of front turret (Lathe)</p>|
| |S\_P\_ARC\_START\_ANGLE|<p>S\_P\_ = previous absolute arc start angle of secondary<br>`  `surface (EDM)</p><p>S\_P\_ = previous absolute arc start angle of front turret<br>`  `(Lathe)</p>|

## <a name="chmtopic1161"></a>**ARC\_INC\_ANGLE**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Absolute incremental arc angle.|

|*Options*|N\_ARC\_INC\_ANGLE|N\_ = next absolute incremental arc angle|
| :- | :- | :- |
| |P\_ARC\_INC\_ANGLE|P\_ = previous absolute incremental arc angle|
| |O\_ARC\_INC\_ANGLE|O\_ = original absolute incremental arc angle (Punch)|
| |S\_ARC\_INC\_ANGLE|S\_ = absolute incremental arc angle of secondary surface<br>` `(EDM)|
| |S\_ARC\_INC\_ANGLE|S\_ = absolute incremental arc angle of front turret (Lathe)|
| |S\_N\_ARC\_INC\_ANGLE|<p>S\_N\_ = Next absolute incremental arc angle of secondary<br>`  `surface (EDM)</p><p>S\_N\_ = next absolute incremental arc angle of front turret<br>`  `(Lathe)</p>|
| |S\_P\_ARC\_INC\_ANGLE|<p>S\_P\_ = previous absolute incremental arc angle of secondary<br>`  `surface (EDM)</p><p>S\_P\_ = previous absolute incremental arc angle of front turret<br>`  `(Lathe)</p>|

## <a name="chmtopic1163"></a>**ARM\_LEN**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|5 axis arm extension length.|

## <a name="chmtopic1165"></a>**ATTROVERRIDE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|: <X:x\_preset> - anything after the colon makes ATTROVERRIDE=YES.|

## <a name="chmtopic1167"></a>**ATTRCVALUE**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|<P:{MILLING}> since "P" is a CHARACTER, the value is ATTRCVALUE.|

## <a name="chmtopic1169"></a>**ATTRDVALUE**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|<X:x\_preset> since "X" is a DECIMAL, the value is ATTRDVALUE.|

## <a name="chmtopic1171"></a>**ATTRIVALUE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<S:1000> - since "S" is an INTEGER, the value is ATTRIVALUE.|

## <a name="chmtopic129"></a>**BAR\_STOCK\_BACK\_FACE\_OFFSET**


|Type|DECIMAL|
| :- | :- |
|Usage|Stores the distance from the bar stock to the back face of the part. Available in Turn and  Mill-Turn posts. To be used in CAMWorks 2018 SP4 or higher versions.|


## <a name="chmtopic161"></a>**BAR\_STOCK\_FACE\_OFFSET**


|Type|DECIMAL|
| :- | :- |
|Usage|Stores the bar stock’s Face Offset value when ‘Bar’ stock is selected. Available in Mill and Mill-Turn posts. To be used in CAMWorks 2017 SP0 or higher versions. |




## <a name="chmtopic160"></a>**BAR\_STOCK\_ID\_DIAM**


|Type|DECIMAL|
| :- | :- |
|Usage|Stores the bar stock’s ID diameter when ‘Bar’ stock is selected. Available in Mill and Mill-Turn posts. To be used in CAMWorks 2017 SP0 or higher versions.|


## <a name="chmtopic1176"></a>**BYTE\_COUNT**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Byte count of the text output file \*.txt.|

## <a name="chmtopic162"></a>**CAP\_OPR\_MAX\_RPM**


|Type|INTEGER|
| :- | :- |
|Usage|Stores whether the *Surface Sped RPM Max* checkbox is checked or not in Turn Operation Parameters dialog box.  Available in Turn and Mill-Turn posts. To be used in CAMWorks 2017 SP0 or higher versions.|


## <a name="chmtopic146"></a>**CAP\_PART\_MAX\_RPM\_MAIN**


|Type|INTEGER|
| :- | :- |
|Usage|This variable is set to TRUE or FALSE depending on the status of the checkbox in the Setup tab. If it is set to FALSE, then the post will not output MAX RPM for Main Spindle. Available in Turn and Mill/Turn posts. To be used in CAMWorks 2017 SP1 or higher versions.|


## <a name="chmtopic147"></a>**CAP\_PART\_MAX\_RPM\_SUB**


|Type|INTEGER|
| :- | :- |
|Usage|This variable is set to TRUE or FALSE depending on the status of the checkbox in the Setup tab. If it is set to FALSE, then the post will not output MAX RPM for Sub Spindle. Available in Turn and Mill/Turn posts. To be used in CAMWorks 2017 SP1 or higher versions.|


## <a name="chmtopic1181"></a>**CCL\_STATUS**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Macro CCL file status.|

## <a name="chmtopic293"></a>**CHUCK\_WIDTH**

|Type|DECIMAL|
| :- | :- |
|Usage|Lets post know the chuck width of main spindle. To be used in CAMWorks 2014 or newer version. .|

## <a name="chmtopic48"></a>**CL\_COMMENT** 
#### **Type**
**CHARACTER**
#### **Usage**
Stores the CL comment. If comment is selected, then the string will be output as a comment to the controller. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic49"></a>**CL\_COMMAND** 
#### **Type**
**CHARACTER**
#### **Usage**
Stores the CL command. If command is selected, then the string will be output as a command to the controller. To be used in CAMWorks 2020 SP0 and later versions.
## <a name="chmtopic280"></a>**CONVENTIONAL\_AXIS\_LABELS**

|Type|INTEGER|
| :- | :- |
|Usage|Set this variable to either TRUE or FALSE. If variable is set to "TRUE" then this lets the posting system know that the rotary 4<sup>th</sup> and 5<sup>th</sup> axis are set to standard axis labels as follows. Rotating about X="A",  Rotating about Y="B" and Rotating about Z="C". If set to FALSE then the post is handling the axis labels for a special case. Currently this will be set in system calc section called "CALC\_PRE\_POST\_INITIALIZE". To be used in CAMWorks 2014 or newer version.|


## <a name="chmtopic1187"></a>**CORNER\_TYPE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>EDM: Taper corner type:</p><p>CORNER\_TYPE=</p><p>SHARP\_CORNER</p><p>EQUAL\_CORNER</p><p>INDEPENDANT\_CORNER</p><p>CONIC\_CORNER</p><p>CHAMFER\_CORNER</p>|

|*Options*|N\_CORNER\_TYPE|<p>EDM: Next taper corner type:</p><p>N\_CORNER\_TYPE=</p><p>SHARP\_CORNER</p><p>EQUAL\_CORNER</p><p>INDEPENDANT\_CORNER</p><p>CONIC\_CORNER</p><p>CHAMFER\_CORNER</p>|
| :- | :- | :- |
| |P\_CORNER\_TYPE|<p>EDM: Previous taper corner type:</p><p>P\_CORNER\_TYPE=</p><p>SHARP\_CORNER</p><p>EQUAL\_CORNER</p><p>INDEPENDANT\_CORNER</p><p>CONIC\_CORNER</p><p>CHAMFER\_CORNER</p>|

## <a name="chmtopic400"></a>**CTL\_PATH**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|Stores the path of the current post being used. Available in Mill, Turn and Mill/Turn. Supported in CAMWorks 2010 and later. Not supported in any ProCAM product.|

## <a name="chmtopic1190"></a>**CURRENT\_MACRO\_NAME**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|Current macro name.|

## <a name="chmtopic1192"></a>**CURRENT\_MACRO\_NUMBER**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Current macro name.|

## <a name="chmtopic1194"></a>**CURRENT\_SYSTEM**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Lathe/Mill post: What system you are in currently.</p><p>CURRENT\_SYSTEM=LATHE, MILL\_FACE or MILL\_OD</p>|

## <a name="chmtopic440"></a>**CW\_DWELL**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|<p>Stores the dwell amount that is entered in a Turn Finish operation. The dwell amount can be set on the Finish Turn tab when you set the Cut Type pattern to “Diameter and Length.” To get the post to output this value, you need to have a CALC section called CALC\_OUTPUT\_DWELL added to your post source LIB file. When this is called, you can then call a template section to output the dwell amount.</p><p> </p><p>Available in Turn and Mill/Turn. Support for additional operations may be available in future versions. Supported in CAMWorks 2008 SP3.0 and later. Not supported in any ProCAM product.</p>|


## <a name="chmtopic1197"></a>**DIE\_SERIAL\_NUM**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|Die serial number from feed and speed table.|

|*Options*|N\_DIE\_SERIAL\_NUM|N\_ = next entity die serial number from feed and speed table|
| :- | :- | :- |
| |NC\_DIE\_SERIAL\_NUM|NC\_ = next tool change die serial number from feed and speed table|

## <a name="chmtopic1199"></a>**DISPLACED\_X**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|5 axis modified X,Y,Z end point of move.||
|*Options*|N\_DISPLACED\_X|N\_ = next move|
| |P\_DISPLACED\_X|P\_ = previous move|

## <a name="chmtopic1201"></a>**DISPLACED\_Y**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|5 axis modified X,Y,Z end point of move.||
|*Options*|N\_DISPLACED\_Y|N\_ = next move|
| |P\_DISPLACED\_Y|P\_ = previous move|

## <a name="chmtopic1203"></a>**DISPLACED\_Z**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|5 axis modified X,Y,Z end point of move.||
|*Options*|N\_DISPLACED\_Z|N\_ = next move|
| |P\_DISPLACED\_Z|P\_ = previous move|

## <a name="chmtopic1205"></a>**DIST\_BET\_HOLES\_X**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Signed incremental X distance between holes in a grid.|

|*Options*|N\_DIST\_BET\_HOLES\_X|N\_ = signed incremental X distance between holes in next grid|
| :- | :- | :- |
| |P\_DIST\_BET\_HOLES\_X|P\_ = signed incremental X distance between holes in previous grid|

## <a name="chmtopic1207"></a>**DIST\_BET\_HOLES\_Y**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Signed incremental Y distance between holes in a grid.|

|*Options*|N\_DIST\_BET\_HOLES\_Y|N\_ = signed incremental Y distance between holes in next grid|
| :- | :- | :- |
| |P\_DIST\_BET\_HOLES\_Y|P\_ = signed incremental Y distance between holes in previous grid|

## <a name="chmtopic1209"></a>**DIST\_BET\_PARTS\_X**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|The signed incremental distance between parts in a multiple macro call.|

|*Options*|N\_DIST\_BET\_PARTS\_X|N\_ = signed incremental X distance between parts in next multiple macro call.|
| :- | :- | :- |
| |P\_DIST\_BET\_PARTS\_X|P\_ = signed incremental X distance between parts in previous multiple macro call.|

## <a name="chmtopic1211"></a>**DIST\_BET\_PARTS\_Y**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|The signed incremental distance between parts in a multiple macro call.|

|*Options*|N\_DIST\_BET\_PARTS\_Y|N\_ = signed incremental Y distance between parts in next multiple macro call|
| :- | :- | :- |
| |P\_DIST\_BET\_PARTS\_Y|P\_ = signed incremental Y distance between parts in previous multiple macro call|

# <a name="chmtopic256"></a>**DIST\_BETWEEN\_CHUCKS**

|Type|DECIMAL|
| :- | :- |
|Usage|Gives the distance between chucks in Turn and Mill-Turn posts that use two spindles. To be used in CAMWorks 2014 SP0 or newer versions.|


## <a name="chmtopic1214"></a>**DISTANCE**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|Length of a move.||
|*Options*|N\_DISTANCE|N\_ = next move|
| |P\_DISTANCE|P\_ = previous move|
| |O\_DISTANCE|O\_ = original move length (Punch)|
| |S\_DISTANCE|S\_ = length of a secondary surface move (EDM)|
| |S\_DISTANCE|S\_ = length of a front turret move (Lathe)|
| |S\_N\_DISTANCE|<p>S\_N\_ = length of next secondary surface move (EDM)</p><p>S\_N\_ = length of next front turret move (Lathe)</p>|
| |S\_P\_DISTANCE|<p>S\_P\_ = length of previous secondary surface move EDM)</p><p>S\_P\_ = length of previous front turret move (Lathe)</p>|

## <a name="chmtopic1216"></a>**EDM\_MODE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>EDM: EDM Mode:</p><p>EDM\_MODE=</p><p>EDM4AXIS</p><p>TAPER</p>|

## <a name="chmtopic1218"></a>**EOL**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|<p>End of line parameter.</p><p>The default is EOL={}</p><p>Example EOL={\*}.</p>|

## <a name="chmtopic1220"></a>**FILLET\_RADIUS**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|EDM: Fillet radius for XY surface.|

|*Options*|N\_FILLET\_RADIUS|N\_ = next fillet radius for XY surface|
| :- | :- | :- |
| |P\_FILLET\_RADIUS|P\_ = previous fillet radius for XY surface|
| |S\_FILLET\_RADIUS|S\_ = fillet radius for UV surface.|
| |S\_N\_FILLET\_RADIUS|S\_N\_ = next fillet radius for UV surface|
| |S\_P\_FILLET\_RADIUS|S\_P\_ = previous fillet radius for UV surface|

## <a name="chmtopic1222"></a>**FIXED**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Punch: Tool index angle. FIXED=YES or NO.|

## <a name="chmtopic1224"></a>**FRAME**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Punch: Grid or window. FRAME=YES or NO|

## <a name="chmtopic1226"></a>**FRONT\_TOOL**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>4-axis Lathe: Tool selection.</p><p>STATION\_NUM=F01</p>|

## <a name="chmtopic289"></a>**FRONT\_TURRET\_TYPE**

|Type|INTEGER|
| :- | :- |
|Usage|Lets post know the front turret type for a single front turret post. If passed as "TOOL\_CHANGER" then this would normally be a B axis mill/turn or turn machine that has a tool changer. If not "TOOL\_CHANGER" then it would be a standard turret type turret with no tool changer. To be used in CAMWorks 2014 or newer version. .|


## <a name="chmtopic284"></a>**FRONT\_TURRET\_1\_TYPE**

|Type|INTEGER|
| :- | :- |
|Usage|Lets post know the 1st front turret type. If passed as "TOOL\_CHANGER" then this would normally be a B axis mill/turn or turn machine that has a tool changer. If not "TOOL\_CHANGER" then it would be a standard turret type turret with no tool changer. To be used in CAMWorks 2014 or newer version. .|

## <a name="chmtopic290"></a>**FRONT\_TURRET\_2\_TYPE**

|Type|INTEGER|
| :- | :- |
|Usage|Lets post know the 2nd front turret type. If passed as "TOOL\_CHANGER" then this would normally be a B axis mill/turn or turn machine that has a tool changer. If not "TOOL\_CHANGER" then it would be a standard turret type turret with no tool changer. To be used in CAMWorks 2014 or newer version. .|

## <a name="chmtopic291"></a>**FRONT\_TURRET\_3\_TYPE**

|Type|INTEGER|
| :- | :- |
|Usage|Lets post know the 3rd front turret type. If passed as "TOOL\_CHANGER" then this would normally be a B axis mill/turn or turn machine that has a tool changer. If not "TOOL\_CHANGER" then it would be a standard turret type turret with no tool changer. To be used in CAMWorks 2014 or newer version.|

## <a name="chmtopic292"></a>**FRONT\_TURRET\_4\_TYPE**

|Type|INTEGER|
| :- | :- |
|Usage|Lets post know the 4th front turret type. If passed as "TOOL\_CHANGER" then this would normally be a B axis mill/turn or turn machine that has a tool changer. If not "TOOL\_CHANGER" then it would be a standard turret type turret with no tool changer. To be used in CAMWorks 2014 or newer version. .|

## <a name="chmtopic43"></a>**HAVE\_PROBE\_CYCLE**
#### **Type**
**INTEGER**
#### **Usage**
For a Probe Cycle, this variable stores a binary value that indicates whether the next move is a probe cycle or not. To be used in CAMWorks 2020 SP0 or later versions.



HAVE\_PROBE\_CYCLE=TRUE or FALSE


## <a name="chmtopic442"></a>**HAVE\_SURFACE\_CP**
#### ** 

|*Type*|INTEGER|
| :- | :- |
|*Usage*|This variable let the post know if the current, previous or next movement has a contact point. This is available only in CAMWorks Multiaxis operations. Supported in CAMWorks 2008 and later. Not supported in any ProCAM product.|
|*Options*|<p>HAVE\_SURFACE\_CP= TRUE or FALSE</p><p>P\_HAVE\_SURFACE\_CP= TRUE or FALSE</p><p>N\_HAVE\_SURFACE\_CP= TRUE or FALSE</p>|


## <a name="chmtopic1235"></a>**HEAD\_LEN**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|5 axis head length.|

## <a name="chmtopic1237"></a>**HEIGHT**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Tool compensated window Y height.|

|*Options*|N\_HEIGHT|N\_ = next tool compensated in window Y height|
| :- | :- | :- |
| |P\_HEIGHT|P\_ = previous tool compensated in window Y height|

## <a name="chmtopic1239"></a>**HOLDER\_COMMENT**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|**Holder comment.**|
|**Options**||

|N\_HOLDER\_COMMENT  N\_|Next entity holder comment.|
| :- | :- |
|NC\_HOLDER\_COMMENT  NC\_|Next tool change holder comment.|

|||
| :- | :- |

## <a name="chmtopic1241"></a>**HORIZ\_OR\_VERT**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Direction of punching in a grid, window or multiple macro call.|

|*Options*|N\_HORIZ\_OR\_VERT|N\_ = direction of punching in next grid, window or multiple macro call|
| :- | :- | :- |
| |P\_HORIZ\_OR\_VERT|P\_ = direction of punching in previous grid, window or multiple macro call|

## <a name="chmtopic1243"></a>**ID**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Lathe: Inside diameter flag. ID=1 or 0.</p><p>Mill: Thread Milling. ID=1 for Internal, ID=0 for External</p>|

## <a name="chmtopic1245"></a>**INC\_ANGLE**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Punch: Incremental angle of an arc pattern.|

|*Options*|N\_INC\_ANGLE|N\_ = incremental angle of next arc pattern|
| :- | :- | :- |
| |P\_INC\_ANGLE|P\_ = incremental angle of previous arc pattern|

## <a name="chmtopic1247"></a>**INC\_C\_END**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>X,Y,Z,C Signed incremental distance of move.</p><p>EDM: U,V secondary surface signed incremental distance of move.</p><p>Lathe: U,W front turret signed incremental distance of move.</p>||
|*Options*|N\_INC\_C\_END|N\_ = next move|
| |P\_INC\_C\_END|P\_ = previous move|

## <a name="chmtopic1249"></a>**INC\_I\_CENTER**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>I,J signed incremental distance from start of arc to center.</p><p>K,L signed incremental distance from start of secondary surface arc to center.</p>||
|*Options*|N\_INC\_I\_CENTER|N\_ = signed incremental distance from next start of arc to center|
| |P\_INC\_I\_CENTER|P\_ = signed incremental distance from previous start of arc to center|
| |REV\_INC\_I\_CENTER|REV\_ = signed incremental distance from center of arc to start of arc.|
| |N\_REV\_INC\_I\_CENTER|N\_REV\_ = signed incremental distance from center to start of next arc.|
| |P\_REV\_INC\_I\_CENTER|P\_REV\_ = signed incremental distance from center to start of previous arc.|

## <a name="chmtopic1251"></a>**INC\_J\_CENTER**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>I,J signed incremental distance from start of arc to center.</p><p>K,L signed incremental distance from start of secondary surface arc to center.</p>||
|*Options*|N\_INC\_I\_CENTER|N\_ = signed incremental distance from next start of arc to center|
| |P\_INC\_I\_CENTER|P\_ = signed incremental distance from previous start of arc to center|
| |REV\_INC\_I\_CENTER|REV\_ = signed incremental distance from center of arc to start of arc.|
| |N\_REV\_INC\_I\_CENTER|N\_REV\_ = signed incremental distance from center to start of next arc.|
| |P\_REV\_INC\_I\_CENTER|P\_REV\_ = signed incremental distance from center to start of previous arc.|

## <a name="chmtopic1253"></a>**INC\_K\_CENTER**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>I,J signed incremental distance from start of arc to center.</p><p>K,L signed incremental distance from start of secondary surface arc to center.</p>||
|*Options*|N\_INC\_I\_CENTER|N\_ = signed incremental distance from next start of arc to center|
| |P\_INC\_I\_CENTER|P\_ = signed incremental distance from previous start of arc to center|
| |REV\_INC\_I\_CENTER|REV\_ = signed incremental distance from center of arc to start of arc.|
| |N\_REV\_INC\_I\_CENTER|N\_REV\_ = signed incremental distance from center to start of next arc.|
| |P\_REV\_INC\_I\_CENTER|P\_REV\_ = signed incremental distance from center to start of previous arc.|

## <a name="chmtopic1255"></a>**INC\_L\_CENTER**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>I,J signed incremental distance from start of arc to center.</p><p>K,L signed incremental distance from start of secondary surface arc to center.</p>||
|*Options*|N\_INC\_I\_CENTER|N\_ = signed incremental distance from next start of arc to center|
| |P\_INC\_I\_CENTER|P\_ = signed incremental distance from previous start of arc to center|
| |REV\_INC\_I\_CENTER|REV\_ = signed incremental distance from center of arc to start of arc.|
| |N\_REV\_INC\_I\_CENTER|N\_REV\_ = signed incremental distance from center to start of next arc.|
| |P\_REV\_INC\_I\_CENTER|P\_REV\_ = signed incremental distance from center to start of previous arc.|

## <a name="chmtopic1257"></a>**INC\_ROT\_TILT\_A**


|*Type*|DECIMAL||
| :- | :- | :- |
|*Usage*|5 axis "A" signed incremental rotation move.||
|*Options*|N\_INC\_ROT\_TILT\_A|N\_ = next move|
| |P\_INC\_ROT\_TILT\_A|P\_ = previous move|

## <a name="chmtopic1259"></a>**INC\_ROT\_TILT\_B**


|*Type*|DECIMAL||
| :- | :- | :- |
|*Usage*|5 axis "B" signed incremental tilt move.||
|*Options*|N\_INC\_ROT\_TILT\_B|N\_ = next move|
| |P\_INC\_ROT\_TILT\_B|P\_ = previous move|

## <a name="chmtopic1261"></a>**INC\_TOOL\_INDEX\_ANGLE**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Punch: Signed incremental autoindex tool angle.|

|*Options*|N\_INC\_TOOL\_INDEX\_ANGLE|N\_ = next signed incremental autoindex tool angle|
| :- | :- | :- |
| |P\_INC\_TOOL\_INDEX\_ANGLE|P\_ = previous signed incremental autoindex tool angle|

## <a name="chmtopic1263"></a>**INC\_U\_END**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>X,Y,Z,C Signed incremental distance of move.</p><p>EDM: U,V secondary surface signed incremental distance of move.</p><p>Lathe: U,W front turret signed incremental distance of move.</p>||
|*Options*|N\_INC\_U\_END|N\_ = next move|
| |P\_INC\_U\_END|P\_ = previous move|

## <a name="chmtopic1265"></a>**INC\_V\_END**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>X,Y,Z,C Signed incremental distance of move.</p><p>EDM: U,V secondary surface signed incremental distance of move.</p><p>Lathe: U,W front turret signed incremental distance of move.</p>||
|*Options*|N\_INC\_V\_END|N\_ = next move|
| |P\_INC\_V\_END|P\_ = previous move|

## <a name="chmtopic1267"></a>**INC\_W\_END**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>X,Y,Z,C Signed incremental distance of move.</p><p>EDM: U,V secondary surface signed incremental distance of move.</p><p>Lathe: U,W front turret signed incremental distance of move.</p>||
|*Options*|N\_INC\_W\_END|N\_ = next move|
| |P\_INC\_W\_END|P\_ = previous move|

## <a name="chmtopic1269"></a>**INC\_X\_END**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>X,Y,Z,C Signed incremental distance of move.</p><p>EDM: U,V secondary surface signed incremental distance of move.</p><p>Lathe: U,W front turret signed incremental distance of move.</p>||
|*Options*|N\_INC\_X\_END|N\_ = next move|
| |P\_INC\_X\_END|P\_ = previous move|

## <a name="chmtopic1271"></a>**INC\_Y\_END**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>X,Y,Z,C Signed incremental distance of move.</p><p>EDM: U,V secondary surface signed incremental distance of move.</p><p>Lathe: U,W front turret signed incremental distance of move.</p>||
|*Options*|N\_INC\_Y\_END|N\_ = next move|
| |P\_INC\_Y\_END|P\_ = previous move|

## <a name="chmtopic1273"></a>**INC\_Z\_END**


|*Type*|METRIC DECIMAL||
| :- | :- | :- |
|*Usage*|<p>X,Y,Z,C Signed incremental distance of move.</p><p>EDM: U,V secondary surface signed incremental distance of move.</p><p>Lathe: U,W front turret signed incremental distance of move.</p>||
|*Options*|N\_INC\_Z\_END|N\_ = next move|
| |P\_INC\_Z\_END|P\_ = previous move|

## <a name="chmtopic429"></a>**IS\_5AXIS**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>IS\_5AXIS = 0 or IS\_5AXIS = FALSE</p><p>IS\_5AXIS = 1 or IS\_5AXIS = TRUE</p><p>If True, then it is either a Mill or Mill/Turn multiaxis operation.</p>|

## <a name="chmtopic427"></a>**IS\_MILL\_FACE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>IS\_MILL\_FACE = 0 or IS\_MILL\_FACE = FALSE</p><p>IS\_MILL\_FACE = 1 or IS\_MILL\_FACE = TRUE</p><p>If True, then it is a Mill/Turn operation on the FACE.</p>|

## <a name="chmtopic426"></a>**IS\_MILL\_OD**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>IS\_MILL\_OD = 0 or IS\_MILL\_OD = FALSE</p><p>IS\_MILL\_OD = 1 or IS\_MILL\_OD = TRUE</p><p>If True, then it is a Mill/Turn operation on the OD.</p>|

## <a name="chmtopic428"></a>**IS\_WRAPPED**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>IS\_WRAPPED = 0 or IS\_WRAPPED = FALSE</p><p>IS\_WRAPPED = 1 or IS\_WRAPPED = TRUE</p><p>If True, then it is a Mill operation on the OD.</p><p>OPR\_AXIS\_TYPE will also equal 4444 in this case.</p>|

## <a name="chmtopic1279"></a>**ISCOLLOP**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Inside scallop height of an arc or circle when nibbling.|

## <a name="chmtopic1281"></a>**LATHE\_HOLDER\_NAME**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|Lathe: Holder name.|

## <a name="chmtopic1283"></a>**LATHE\_TOOL\_NAME**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|Lathe: Tool name.|

## <a name="chmtopic1285"></a>**LEADIN**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Profile leadin flag:</p><p>LEADIN=YES or NO</p>|

|*Options*|N\_LEADIN|<p>Profile next leadin flag:</p><p>N\_LEADIN=YES or NO</p>|
| :- | :- | :- |
| |P\_LEADIN|<p>Profile previous leadin flag:</p><p>P\_LEADIN=YES or NO</p>|

## <a name="chmtopic1287"></a>**LEADOUT**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Profile leadout flag:</p><p>LEADOUT=YES or NO</p>|

|*Options*|N\_LEADOUT|<p>Profile next leadout flag:</p><p>N\_LEADIN=YES or NO</p>|
| :- | :- | :- |
| |P\_LEADOUT|<p>Profile previous leadout flag:</p><p>P\_LEADIN=YES or NO</p>|

## <a name="chmtopic1289"></a>**LINE\_COUNT**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Line count of the text output file \*.txt.|

## <a name="chmtopic446"></a>**MACH\_CJ**

|*Type*|DECIMAL||
| :- | :- | :- |
|*Usage*|These commands are the J axis vector contact point of the current, previous or next movement. This is available only in CAMWorks Multiaxis operations. Supported in CAMWorks 2008 and later. Not supported in any ProCAM product.||
|*Options*|N\_MACH\_CJ|N\_ = next move|
| |P\_MACH\_CJ|P\_ = previous move|


## <a name="chmtopic1292"></a>**MACH\_CK**

|*Type*|DECIMAL||
| :- | :- | :- |
|*Usage*|These commands are the Z axis vector contact point of the current, previous or next movement. This is available only in CAMWorks Multiaxis operations. Supported in CAMWorks 2008 and later. Not supported in any ProCAM product.||
|*Options*|N\_MACH\_CK|N\_ = next move|
| |P\_MACH\_CK|P\_ = previous move|


## <a name="chmtopic443"></a>**MACH\_CX**

|*Type*|DECIMAL||
| :- | :- | :- |
|*Usage*|These commands are the X axis contact points of the current, previous or next movement. This is available only in CAMWorks Multiaxis operations. Supported in CAMWorks 2008 and later. Not supported in any ProCAM product.||
|*Options*|N\_MACH\_CX|N\_ = next move|
| |P\_MACH\_CX|P\_ = previous move|


## <a name="chmtopic444"></a>**MACH\_CY**

|*Type*|DECIMAL||
| :- | :- | :- |
|*Usage*|These commands are the Y axis contact points of the current, previous or next movement. This is available only in CAMWorks Multiaxis operations. Supported in CAMWorks 2008 and later. Not supported in any ProCAM product.||
|*Options*|N\_MACH\_CY|N\_ = next move|
| |P\_MACH\_CY|P\_ = previous move|


## <a name="chmtopic445"></a>**MACH\_CZ**

|*Type*|DECIMAL||
| :- | :- | :- |
|*Usage*|These commands are the Z axis contact points of the current, previous or next movement. This is available only in CAMWorks Multiaxis operations. Supported in CAMWorks 2008 and later. Not supported in any ProCAM product.||
|*Options*|N\_MACH\_CZ|N\_ = next move|
| |P\_MACH\_CZ|P\_ = previous move|


## <a name="chmtopic295"></a>**MACH\_SIM\_CHANGER**

|Type|INTEGER|
| :- | :- |
|Usage|Returns what a mill LOADTOOL index for simulation is if single rear turret if turn type is a TOOL\_CHANGER, for mill or single turret mill/turn post. To be used in CAMWorks 2014 or newer version. .|

## <a name="chmtopic296"></a>**MACH\_SIM\_CHANGER\_1A**

|Type|INTEGER|
| :- | :- |
|Usage|Returns what a mill LOADTOOL index for simulation 1st rear turret if turret type is a TOOL\_CHANGER, for mill and multiple turret mill/turn post. To be used in CAMWorks 2014 or newer version. .|
# ** 

## <a name="chmtopic297"></a>**MACH\_SIM\_CHANGER\_2A**

|Type|INTEGER|
| :- | :- |
|Usage|Returns what a mill LOADTOOL index for simulation 2nd rear turret if turret type is a TOOL\_CHANGER, for mill and multiple turret mill/turn post. To be used in CAMWorks 2014 or newer version. .|


## <a name="chmtopic298"></a>**MACH\_SIM\_CHANGER\_1B**

|Type|INTEGER|
| :- | :- |
|Usage|Returns what a mill LOADTOOL index for simulation 1st front turret if turret type is a TOOL\_CHANGER, for mill and multiple turret mill/turn post. To be used in CAMWorks 2014 or newer version. .|


## <a name="chmtopic299"></a>**MACH\_SIM\_CHANGER\_2B**

|Type|INTEGER|
| :- | :- |
|Usage|Returns what a mill LOADTOOL index for simulation 2nd front turret if turret type is a TOOL\_CHANGER, for mill and multiple turret mill/turn post. To be used in CAMWorks 2014 or newer version. .|


## <a name="chmtopic300"></a>**MACH\_SIM\_CRIB\_OFF**

|Type|INTEGER|
| :- | :- |
|Usage|Returns a tool crib offset tool number from simulation for single turret. To be used in CAMWorks 2014 or newer version. .|


## <a name="chmtopic1303"></a>**MACH\_SIM\_CRIB\_OFF\_1A**

|Type|INTEGER|
| :- | :- |
|Usage|Returns a tool crib offset tool number from simulation for 1st rear turret. To be used in CAMWorks 2014 or newer version. .|


## <a name="chmtopic301"></a>**MACH\_SIM\_CRIB\_OFF\_2A**

|Type|INTEGER|
| :- | :- |
|Usage|Returns a tool crib offset tool number from simulation for 2nd rear turret. To be used in CAMWorks 2014 or newer version. .|


## <a name="chmtopic302"></a>**MACH\_SIM\_CRIB\_OFF\_1B**

|Type|INTEGER|
| :- | :- |
|Usage|Returns a tool crib offset tool number from simulation for 1st front turret. To be used in CAMWorks 2014 or newer version. .|


## <a name="chmtopic303"></a>**MACH\_SIM\_CRIB\_OFF\_2B**

|Type|INTEGER|
| :- | :- |
|Usage|Returns a tool crib offset tool number from simulation for 2nd front turret. To be used in CAMWorks 2014 or newer version. .|


## <a name="chmtopic304"></a>**MACH\_SIM\_TOOL\_SPINDLE**

|Type|INTEGER|
| :- | :- |
|Usage|Returns a tool crib offset tool number from simulation in mill or single turret mill/turn posts. To be used in CAMWorks 2014 or newer version.|


## <a name="chmtopic305"></a>**MACH\_SIM\_TOOL\_SPINDLE\_1A**

|Type|INTEGER|
| :- | :- |
|Usage|Returns what the mill tool motor number is for simulation in mill or multiple turret mill/turn posts in 1st rear turret. To be used in CAMWorks 2014 or newer version.|


## <a name="chmtopic306"></a>**MACH\_SIM\_TOOL\_SPINDLE\_1B**

|Type|INTEGER|
| :- | :- |
|Usage|Returns what the mill tool motor number is for simulation in mill or multiple turret mill/turn posts in 2nd rear turret. To be used in CAMWorks 2014 or newer version.|

## <a name="chmtopic307"></a>**MACH\_SIM\_TOOL\_SPINDLE\_1B**

|Type|INTEGER|
| :- | :- |
|Usage|Returns what the mill tool motor number is for simulation in mill or multiple turret mill/turn posts in 1st front turret. To be used in CAMWorks 2014 or newer version.|


## <a name="chmtopic308"></a>**MACH\_SIM\_TOOL\_SPINDLE\_2B**

|Type|INTEGER|
| :- | :- |
|Usage|Returns what the mill tool motor number is for simulation in mill or multiple turret mill/turn posts in 2nd front turret. To be used in CAMWorks 2014 or newer version.|


## <a name="chmtopic309"></a>**MACH\_SIM\_MAIN\_SPINDLE**

|Type|INTEGER|
| :- | :- |
|Usage|Returns the turn main spindle motor number for simulation. To be used in CAMWorks 2014 or newer version.|


## <a name="chmtopic310"></a>**MACH\_SIM\_SUB\_SPINDLE**

|Type|INTEGER|
| :- | :- |
|Usage|Returns the turn sub spindle motor number for simulation. To be used in CAMWorks 2014 or newer version.|


## <a name="chmtopic1315"></a>**MACRO\_A**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|<p>Internal macro variable used to pass information from the defined subroutine to the main calling program.</p><p>MACRO\_A and MACRO\_B can also pass information from the main calling program to defined subroutine. MACRO\_A will pass the 4th axis absolute preposition angle and MACRO\_B will pass the 5th axis absolute preposition angle. These values will only be the preposition angles of the first time they are called. For example, if you are doing a tombstone and the first time the subroutine is called the 4th axis is at 90 degrees and the 5th axis is at 0 degrees, then MACRO\_A will have a value of 90 and MACRO\_B will have a value of zero.</p>|

## <a name="chmtopic1317"></a>**MACRO\_B**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|<p>Internal macro variable used to pass information from the defined subroutine to the main calling program.</p><p>MACRO\_A and MACRO\_B can also pass information from the main calling program to defined subroutine. MACRO\_A will pass the 4th axis absolute preposition angle and MACRO\_B will pass the 5th axis absolute preposition angle. These values will only be the preposition angles of the first time they are called. For example, if you are doing a tombstone and the first time the subroutine is called the 4th axis is at 90 degrees and the 5th axis is at 0 degrees, then MACRO\_A will have a value of 90 and MACRO\_B will have a value of zero.</p>|

## <a name="chmtopic1319"></a>**MACRO\_C**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|<p>Internal macro variable used to pass information from the defined subroutine to the main calling program.</p><p>Only [MACRO_A](#chmtopic1315) and [MACRO_B](#chmtopic1317) can be used to pass information from the main calling program to the defined subroutine.</p>|

## <a name="chmtopic1321"></a>**MACRO\_D**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|<p>Internal macro variable used to pass information from the defined subroutine to the main calling program.</p><p>Only [MACRO_A](#chmtopic1315) and [MACRO_B](#chmtopic1317) can be used to pass information from the main calling program to the defined subroutine.</p>|

## <a name="chmtopic1323"></a>**MACRO\_E**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|<p>Internal macro variable used to pass information from the defined subroutine to the main calling program.</p><p>Only [MACRO_A](#chmtopic1315) and [MACRO_B](#chmtopic1317) can be used to pass information from the main calling program to the defined subroutine.</p>|

## <a name="chmtopic1325"></a>**MACRO\_F**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|<p>Internal macro variable used to pass information from the defined subroutine to the main calling program.</p><p>Only [MACRO_A](#chmtopic1315) and [MACRO_B](#chmtopic1317) can be used to pass information from the main calling program to the defined subroutine.</p>|

## <a name="chmtopic1327"></a>**MACRO\_G**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|<p>Internal macro variable used to pass information from the defined subroutine to the main calling program.</p><p>Only [MACRO_A](#chmtopic1315) and [MACRO_B](#chmtopic1317) can be used to pass information from the main calling program to the defined subroutine.</p>|

## <a name="chmtopic1329"></a>**MACRO\_H**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|<p>Internal macro variable used to pass information from the defined subroutine to the main calling program.</p><p>Only [MACRO_A](#chmtopic1315) and [MACRO_B](#chmtopic1317) can be used to pass information from the main calling program to the defined subroutine.</p>|

## <a name="chmtopic1331"></a>**MACRO\_I**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|<p>Internal macro variable used to pass information from the defined subroutine to the main calling program.</p><p>Only [MACRO_A](#chmtopic1315) and [MACRO_B](#chmtopic1317) can be used to pass information from the main calling program to the defined subroutine.</p>|

## <a name="chmtopic1333"></a>**MACRO\_J**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|<p>Internal macro variable used to pass information from the defined subroutine to the main calling program.</p><p>Only [MACRO_A](#chmtopic1315) and [MACRO_B](#chmtopic1317) can be used to pass information from the main calling program to the defined subroutine.</p>|

## <a name="chmtopic1335"></a>**MACRO\_NAME**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|Macro name.|

## <a name="chmtopic1337"></a>**MACRO\_ROTATE\_AXIS**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Mill: 4th axis rotation.</p><p>MACRO\_ROTATE\_AXIS=</p><p>X\_AXIS (about X axis)</p><p>Y\_AXIS (about Y axis)</p><p>Z\_AXIS (about Z axis)</p>|

## <a name="chmtopic1339"></a>**MACRO\_TIME**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Internal time calculation for macros.|

## <a name="chmtopic1341"></a>**METRIC\_FLAG**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Metric in flag:</p><p>0=inch</p><p>1=metric</p>|

## <a name="chmtopic1343"></a>**METRIC\_OUT**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Metric out flag:</p><p>1 = inch</p><p>2 = metric</p>|

## <a name="chmtopic1345"></a>**MICRO\_END**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Punch: Signed incremental micro joint end distance.|

| |N\_MICRO\_END|N\_ = next signed incremental micro joint end distance|
| :- | :- | :- |
| |P\_MICRO\_END|P\_ = previous signed incremental micro joint end distance|

## <a name="chmtopic1347"></a>**MICRO\_START**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Punch: Signed incremental micro joint start distance.|

| |N\_MICRO\_START|N\_ = next signed incremental micro joint start distance|
| :- | :- | :- |
| |P\_MICRO\_START|P\_ = previous signed incremental micro joint start distance|

## <a name="chmtopic1349"></a>**MILL\_FACE\_INC**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|5 axis head length.|

## <a name="chmtopic1351"></a>**MOVE\_COUNT**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Lathe: Cycle movement count. Used for canned Roughing cycles.|

## <a name="chmtopic1353"></a>**MOVE\_TYPE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Movement type - Line, Arc, Rapid, etc.|

|*Options*|N\_MOVE\_TYPE|N\_ = next movement type - Line, Arc, Rapid, etc.|
| :- | :- | :- |
| |P\_MOVE\_TYPE|P\_ = previous movement type - Line, Arc, Rapid, etc.|
| |O\_MOVE\_TYPE|O\_ = original signed incremental arc angle (Punch)|
| |S\_MOVE\_TYPE|S\_ = secondary or U,V plane (EDM and 4 axis Lathe)|
| |S\_N\_MOVE\_TYPE|S\_N\_ = next secondary or U,V plane (EDM and 4 axis Lathe)|
| |S\_P\_MOVE\_TYPE|S\_P\_ = previous secondary or U,V plane (EDM and 4 axis Lathe)|

## <a name="chmtopic177"></a><a name="chmbookmark66"></a><a name="chmbookmark67"></a>**MULTI\_AXIS\_MOVE\_TYPE**
## **P\_MULTI\_AXIS\_MOVE\_TYPE**
## **N\_MULTI\_AXIS\_MOVE\_TYPE**


|Type|DECIMAL|
| :- | :- |
|Usage|Stores the Move type for a Multiaxis operation. Available in Mill and Mill-Turn posts. To be used in CAMWorks 2017 SP0 or higher versions.    |




## <a name="chmtopic1356"></a>**N\_MICROJOINT**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Punch: Next signed incremental micro joint distance.|

## <a name="chmtopic1358"></a>**NEW\_SFPM**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Lathe: Flag for figuring out surface feed per minute in versions 70d and above. NEW\_SFPM=0 (if part was saved before version 8.0).</p><p>NEW\_SFPM=1 (if part was saved in version 8.0 and above).</p>|

## <a name="chmtopic1360"></a>**NEXT\_SYSTEM**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Lathe/Mill post: What system you will be in.</p><p>CURRENT\_SYSTEM=LATHE, MILL\_FACE OR MILL\_OD</p><p>Note:</p><p>This Variable will only be correct at CALC\_END\_OPERATION.</p>|

## <a name="chmtopic1362"></a>**NUM\_HITS\_X**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Number of hits in X on a grid or window.|

|*Options*|N\_NUM\_HITS\_X|N\_ = number of hits in X on next grid or window|
| :- | :- | :- |
| |P\_NUM\_HITS\_X|P\_ = number of hits in X on previous grid or window|

## <a name="chmtopic1364"></a>**NUM\_HITS**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Total number of hits in a grid or window.|

|*Options*|N\_NUM\_HITS|N\_ = total number of hits on next grid or window|
| :- | :- | :- |
| |P\_NUM\_HITS|P\_ = total number of hits on previous grid or window|

## <a name="chmtopic1366"></a>**NUM\_HITS\_Y**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Number of hits in Y on a grid or window.|

|*Options*|N\_NUM\_HITS\_Y|N\_ = number of hits in Y on next grid or window|
| :- | :- | :- |
| |P\_NUM\_HITS\_Y|P\_ = number of hits in Y on previous grid or window|

## <a name="chmtopic148"></a>**NUM\_OPS\_BET\_SYNCS\_OTHER\_TURRET**

|Type|INTEGER|
| :- | :- |
|Usage|This variable will store the number of real operations between the current sync code and the next sync code of other turret in a Turn or Mill-Turn post (available at CALC\_START\_OF\_OPERATION). To be used in CAMWorks 2017 SP1 or higher versions. |
|Example|At CALC\_START\_OPERATION, if you were on the REAR turret then this variable will give you the number of real operations for the front turret until the next matching sync code of the REAR turret. This lets the post know if you are syncing operations from the REAR and FRONT at the same time or not.|

## <a name="chmtopic149"></a>**NUM\_OPS\_BET\_SYNCS\_THIS\_TURRET**

|Type|INTEGER|
| :- | :- |
|Usage|This variable will store the number of real operations between the start and end sync codes of the current turret in a Turn or Mill-Turn post (available at CALC\_START\_OF\_OPERATION). To be used in CAMWorks 2017 SP1 or higher versions. |
|Example|At CALC\_START\_OPERATION, if you were on the REAR turret, then this variable will give you the number of real operations for the rear turret between the current sync code and the next sync code.|




## <a name="chmtopic1370"></a>**NUM\_PARTS\_X**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Number of parts in X in a macro.|

|*Options*|N\_NUM\_PARTS\_X|N\_ = number of parts in X in next macro|
| :- | :- | :- |
| |P\_NUM\_PARTS\_X|P\_ = number of parts in X in previous macro|

## <a name="chmtopic1372"></a>**NUM\_PARTS\_Y**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Number of parts in Y in a macro.|

|*Options*|N\_NUM\_PARTS\_Y|N\_ = number of parts in Y in next macro|
| :- | :- | :- |
| |P\_NUM\_PARTS\_Y|P\_ = number of parts in Y in previous macro|

## <a name="chmtopic281"></a>**NUM\_TURRETS\_FRONT**

|Type|INTEGER|
| :- | :- |
|Usage|Lets post know how many turrets are defined for the front turret. To be used in CAMWorks 2014 or newer version.|


## <a name="chmtopic282"></a>**NUM\_TURRETS\_REAR**

|Type|INTEGER|
| :- | :- |
|Usage|Lets post know how many turrets are defined for the rear turret. To be used in CAMWorks 2014 or newer version.|


## <a name="chmtopic1376"></a>**O\_DIRECTION**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Offset direction of tool:</p><p>O\_DIRECTION=</p><p>OFFSET\_LEFT or OFFSET\_RIGHT</p><p>CENTER\_LEFT or CENTER\_RIGHT</p>|

## <a name="chmtopic1378"></a>**OD**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Lathe: Outside diameter flag. OD=1 or 0.</p><p>Mill: Thread Milling. OD=0 for Internal, OD=1 for External.</p>|

## <a name="chmtopic1380"></a>**OFFSET\_REG**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|EDM: Offset tool register.|

## <a name="chmtopic1382"></a>**OPITCH**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Punch: Original nibbling pitch of a move.|

| |N\_OPITCH|N\_ = original nibbling pitch of next move|
| :- | :- | :- |
| |P\_OPITCH|P\_ = original nibbling pitch of previous move|

## <a name="chmtopic1384"></a>**OPR\_AXIS\_TYPE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Mill: Operation type: OPR\_AXIS\_TYPE =</p><p>2222- Any operation that has a preposition rotary movement (4<sup>th</sup> or 5<sup>th</sup> Axis) and “None” is not selected in the Indexer tab of the Setup. Normally, this will not be set to 2222 if on the top plane; however, if you rotate to another plane and then go back to the top plane, then it will still be 2222. If multiaxis operations, then IS\_5AXIS will be set to TRUE.</p><p>3333- Any 2 and 3 Axis operations on the top plane or any other plane with “None” selected in the Indexer tab of the Setup. Again, if you are rotating to another plane and then go back to the top plane, the value will be 2222.</p><p>4444- This will be set for a Mill 4 Axis wrapped toolpath. In this case, IS\_WRAPPED will also be set to TRUE.</p><p>5555- is not defined and not used.</p><p>6666- is not defined and not used.</p>|

## <a name="chmtopic1386"></a>**OPR\_CFIXED**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Lathe/Mill:</p><p>OPR\_CFIXED=CFIXED or CFREE</p>|

## <a name="chmtopic1388"></a>**OPR\_CLEARANCE**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|<p>Mill: Incremental Z clearance distance.</p><p>EDM: Incremental operation clearance amount.</p>|

## <a name="chmtopic1390"></a>**OPR\_CLEARANCE\_TYPE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Mill: Z clearance type.</p><p>OPR\_Z\_CLEARANCE\_TYPE=</p><p>1,single clearance</p><p>2,multiple clearance</p>|

## <a name="chmtopic1392"></a>**OPR\_CMODE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Lathe/Mill.|

## <a name="chmtopic1394"></a>**OPR\_COMMENT**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|Mill/Lathe: Operation comments.|

## <a name="chmtopic1396"></a>**OPR\_CORNER\_CLEAR**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Mill: Profiling corner clearance amount.|

## <a name="chmtopic1398"></a>**OPR\_CORNER\_EXT**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Mill: Profiling corner extension amount.|

## <a name="chmtopic1400"></a>**OPR\_CORNER\_TYPE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Mill: Profiling corner type.</p><p>OPR\_CORNER\_TYPE=</p><p>ROUND\_CORNERS</p><p>SHARP\_CORNERS</p><p>SQUARE\_CORNERS</p><p>TRIANGLE\_CORNERS</p><p>FANUC\_CORNERS</p>|

## <a name="chmtopic1402"></a>**OPR\_CUT\_AMOUNT**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Lathe: Roughing cycle cut amount.|

## <a name="chmtopic1404"></a>**OPR\_CYCLE\_CLEARANCE**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Lathe: Unsigned incremental cycle clearance.|

## <a name="chmtopic1406"></a>**OPR\_CYCLE\_TYPE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Lathe: Cycle type.</p><p>OPR\_CYCLE\_TYPE=</p><p>TURNING</p><p>FACING</p><p>Lathe canned drilling cycle:</p><p>OPR\_CYCLE\_TYPE=</p><p>SINGLE\_DEPTH</p><p>CONSTANT</p><p>PERCENTAGE</p>|

## <a name="chmtopic1408"></a>**OPR\_DEPTH\_TYPE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Lathe: Drilling depth type.</p><p>OPR\_DEPTH\_TYPE=</p><p>0 (tip)</p><p>1 (flat)</p>|

## <a name="chmtopic1410"></a>**OPR\_DRILL\_CYCLE\_TYPE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Mill: Drilling cycle type.</p><p>OPR\_DRILL\_CYCLE\_TYPE=</p><p>DRILLING</p><p>SPOT\_DRILLING</p><p>PECKING</p><p>HIGH\_SPEED\_PECKING</p><p>VARIABLE\_PECKING</p><p>TAPPING</p><p>REVERSE\_TAPPING</p><p>FINE\_BORING</p><p>REAMING</p><p>REAMING\_DWELL</p><p>BORING</p><p>BORING\_DWELL</p><p>BACK\_BORING</p>|

## <a name="chmtopic204"></a>**OPR\_END\_RETRACT\_TYPE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Mill-Turn/Turn: Retract type for canned cycles.</p><p>OPR\_END\_RETRACT\_TYPE=</p><p> </p><p>RT\_XZ\_ABSOLUTE\_PRESET = 2</p><p>RT\_XZ\_SAFE\_INDEX = 1</p><p>RT\_BOTH = 4</p><p>RT\_NONE = 0</p><p>RT\_AUTO = 5</p>|

## <a name="chmtopic1413"></a>**OPR\_FEED\_FPM**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Lathe: Feed per minute.|

## <a name="chmtopic1415"></a>**OPR\_FEED\_FPR**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Lathe: Feed per revolution.|

## <a name="chmtopic1417"></a>**OPR\_FEED\_TYPE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Lathe: Feed type. OPR\_FEED\_TYPE=</p><p>FPR</p><p>FPM</p>|

## <a name="chmtopic1419"></a>**OPR\_FIXED ANGLE**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Lathe/Mill: OD or FACE fixed angle.|

## <a name="chmtopic163"></a>**OPR\_FSPAGE\_X\_FEED**

|Type|DECIMAL|
| :- | :- |
|Usage|Stores the X feedrate in the *Mill Feeds and Speeds* dialog box. Available in Mill and Mill-Turn posts. To be used in CAMWorks 2017 SP0 or higher versions.|




## <a name="chmtopic164"></a>**OPR\_FSPAGE\_Z\_FEED**

|Type|DECIMAL|
| :- | :- |
|Usage|Stores the Z feedrate in the *Mill Feeds and Speeds* dialog box.  Available in Mill and Mill-Turn posts. To be used in CAMWorks 2017 SP0 or higher versions.|


## <a name="chmtopic1423"></a>**OPR\_INFEED\_ANGLE**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Lathe: Thread infeed angle.|

## <a name="chmtopic1425"></a>**OPR\_INFEED\_TYPE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Lathe thread infeed type.</p><p>OPR\_INFEED\_TYPE=</p><p>STRAIGHT\_INFEED</p><p>ANGLE\_INFEED</p>|

## <a name="chmtopic50"></a>**OPR\_IS\_PRIMARY**
#### **Type**
**INTEGER**
#### **Usage**
For Turn or Mill-Turn posts, this variable stores which operation is primary for the purpose of syncing turrets in Simultaneous Turning. To be used in CAMWorks 2020 SP0 or later versions.



OPR\_IS\_PRIMARY=TRUE or FALSE
## <a name="chmtopic1428"></a>**OPR\_LACE\_ANGLE**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Mill: lacing angle.|

## <a name="chmtopic1430"></a>**OPR\_LACE\_CUT**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Mill: Lacing cut amount.|

## <a name="chmtopic1432"></a>**OPR\_LEADIN**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Mill: Incremental leadin distance.|

## <a name="chmtopic1434"></a>**OPR\_LEADOUT**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Mill: Incremental leadout distance.|

## <a name="chmtopic165"></a>**OPR\_MAX\_RPM**

|Type|INTEGER|
| :- | :- |
|Usage|Stores the maximum RPM value in Turn operations for Sub Spindle or Main Spindle from the Operations dialog box when the *Surface Speed RPM Max* checkbox is checked.  Available in Turn and Mill-Turn posts. To be used in CAMWorks 2017 SP0 or higher versions.|
## ** 
## <a name="chmtopic1437"></a>**OPR\_POST\_CYCLE\_TYPE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Lathe: Cycle type.</p><p>OPR\_POST\_CYCLE\_TYPE=</p><p>SYSTEM</p><p>MACHINE</p>|

## <a name="chmtopic1439"></a>**OPR\_RETRACT\_TYPE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Mill: Retract type.</p><p>OPR\_RETRACT\_TYPE=</p><p>CLEARANCE\_PLANE</p><p>RAPID\_PLANE</p><p>Lathe: Retract type.</p><p>OPR\_RETRACT\_TYPE=</p><p>SINGLE\_RETRACT</p><p>MULTIPLE\_RETRACT</p>|

## <a name="chmtopic1441"></a>**OPR\_SPEED**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Mill: Spindle speed.|

## <a name="chmtopic1443"></a>**OPR\_SPEED\_DIR**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Mill/Lathe: Spindle direction.</p><p>OPR\_SPEED\_DIR=1, CW</p><p>OPR\_SPEED\_DIR=2, CCW</p>|

## <a name="chmtopic1445"></a>**OPR\_SPEED\_RPM**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Lathe: Spindle speed.|

## <a name="chmtopic1447"></a>**OPR\_SPEED\_SFPM**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Lathe: Constant surface feed per minute.|

## <a name="chmtopic1449"></a>**OPR\_SPEED\_TYPE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Lathe: Speed type.</p><p>OPR\_SPEED\_TYPE=</p><p>SFPM</p><p>RPM</p>|

## <a name="chmtopic1451"></a>**OPR\_THREAD\_ANGLE**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Lathe: Thread angle.|

## <a name="chmtopic1453"></a>**OPR\_THREAD\_CHAMFER**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Lathe: Thread unsigned incremental chamfer amount.|

## <a name="chmtopic1455"></a>**OPR\_THREAD\_FIRST\_CUT**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Lathe: Thread first pass amount.|

## <a name="chmtopic151"></a><a name="chmbookmark68"></a>**OPR\_THREAD\_LAST\_CUT**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|This variable will store the last thread pass cut amount in a turn canned threading cycle. To be used in CAMWorks 2017 SP1 or newer versions.|


## <a name="chmtopic1458"></a>**OPR\_THREAD\_LEADIN**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Lathe: Thread unsigned incremental leadin amount.|

## <a name="chmtopic1460"></a>**OPR\_THREAD\_LENGTH**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Lathe: Unsigned incremental thread length.|

## <a name="chmtopic1462"></a>**OPR\_THREAD\_MIN\_CUT**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Lathe: Thread unsigned minimum cut amount.|

## <a name="chmtopic1464"></a>**OPR\_THREAD\_MINOR\_DIAM**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Lathe: Thread minor diameter.|

## <a name="chmtopic1466"></a>**OPR\_THREAD\_NUM\_SPRING**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Lathe: Thread number of spring passes.|

## <a name="chmtopic1468"></a>**OPR\_THREAD\_PITCH**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Lathe: Thread pitch, feed or lead amount.|

## <a name="chmtopic1470"></a>**OPR\_TYPE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Mill or Lathe operation type - MILL\_DRILLING, PROFILING, etc.|
|*Options*|NEXT\_OPR\_TYPE|
|*Notes*|<p>OPR\_TYPE=1020    (When the operation is a multiaxis operation and either 4 axis or</p><p>`                           `5 axis is selected.)</p><p>OPR\_TYPR=0         (When the operation is a multiaxis operation and 3 axis is</p><p>`                           `selected.)</p>|

## <a name="chmtopic1472"></a>**OPR\_X\_FEED**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Mill: XY feed.|

## <a name="chmtopic1474"></a>**OPR\_X\_PART\_CLEARANCE**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Lathe: Unsigned incremental roughing X finish allowance.|

## <a name="chmtopic1476"></a>**OPR\_X\_POSITION**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Lathe and Mill: X Retract Safe Index position.|

## <a name="chmtopic1478"></a>**OPR\_Z\_CLEARANCE**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Mill: Absolute Z clearance plane.|

## <a name="chmtopic1480"></a>**OPR\_Z\_CUT\_METHOD\_TYPE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Mill: Z cut type.</p><p>OPR\_Z\_CUT\_METHOD\_TYPE=</p><p>1,z\_depth</p><p>2,distance along wall</p>|

## <a name="chmtopic1482"></a>**OPR\_Z\_CYCLE\_TYPE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Mill: Z cycle type.</p><p>OPR\_Z\_CYCLE\_TYPE=</p><p>1,z\_depth</p><p>2,z\_wall</p><p>3,z\_extrude</p>|

## <a name="chmtopic1484"></a>**OPR\_Z\_DEPTH**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Mill: Absolute Z depth.|

## <a name="chmtopic1486"></a>**OPR\_Z\_DIST\_ALONG**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Mill: Z distance along a wall.|

## <a name="chmtopic1488"></a>**OPR\_Z\_FACE**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Mill: Absolute Z face of part.|

## <a name="chmtopic1490"></a>**OPR\_Z\_FEED**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Mill: Z feed.|

## <a name="chmtopic1492"></a>**OPR\_Z\_FINISH**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Mill: Lacing and pocketing Z finish allowance.|

## <a name="chmtopic1494"></a>**OPR\_Z\_FIRST\_CUT**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Mill: Profiling, lacing or pocketing Z first depth. For ProCAM application only. Not to be used in CAMWorks.|

## <a name="chmtopic1496"></a>**OPR\_Z\_FIRST\_PECK**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Mill/Lathe: Incremental drill first peck amount.|

## <a name="chmtopic1498"></a>**OPR\_Z\_MIN\_PECK**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Mill/Lathe: Incremental drill minimum peck amount.|

## <a name="chmtopic1500"></a>**OPR\_Z\_PART\_CLEARANCE**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Lathe: Unsigned incremental roughing Z finish allowance.|

## <a name="chmtopic1502"></a>**OPR\_Z\_PER\_PECK**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Mill: variable drill pecking percentage.|

## <a name="chmtopic1504"></a>**OPR\_Z\_POSITION**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Lathe and Mill: Z Retract Safe Index position.|

## <a name="chmtopic1506"></a>**OPR\_Z\_RAPID\_PLANE**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Mill: Absolute Z rapid plane.|

## <a name="chmtopic1508"></a>**OPR\_Z\_RETRACT\_AMOUNT**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|<p>Mill: Profiling, lacing or pocketing Z retract amount.</p><p>Lathe: Drilling cycle multiple retract amount</p>|

## <a name="chmtopic1510"></a>**OPR\_Z\_SUB\_CUT**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Mill: Profiling, lacing or pocketing Z subsequent depth. For ProCAM application only. Not to be used in CAMWorks.|

## <a name="chmtopic1512"></a>**OPR\_Z\_SUB\_PECK**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Mill/Lathe: Incremental drill subsequent peck amount.|

## <a name="chmtopic1514"></a>**OSCOLLOP**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Outside scallop height of an arc or circle when nibbling.|

## <a name="chmtopic1516"></a>**OTHER\_SURF**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|EDM: U,V surface or plane of a part.|

## <a name="chmtopic1518"></a>**OUTPUT\_WCS\_OFFSETS**

|Type|INTEGER|
| :- | :- |
|Usage|Returns whether post should output the SETOFFSET command with offsets or not for simulation. To be used in CAMWorks 2014 or newer version.|
#
## <a name="chmtopic1520"></a>**P\_MICROJOINT**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Punch: Previous signed incremental micro joint distance.|

## <a name="chmtopic167"></a>**PART\_MAX\_RPM\_MAIN**


|Type|INTEGER|
| :- | :- |
|Usage|Stores the maximum RPM value in turn operations for Main Spindle from the TechDB.  Available in Turn and Mill-Turn posts. To be used in CAMWorks 2017 SP0 or higher versions.|

## <a name="chmtopic168"></a>**PART\_MAX\_RPM\_SUB**


|Type|INTEGER|
| :- | :- |
|Usage|Stores the maximum RPM value in turn operations for Sub Spindle from the TechDB.  Available in Turn and Mill-Turn posts. To be used in CAMWorks 2017 SP0 or higher versions.|

## <a name="chmtopic1524"></a>**PART\_NAME**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|Name of the CAD part \*.PRT.|

## <a name="chmtopic1526"></a>**PART\_TYPE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Plasma/punch post: What type of part is it.</p><p>PART\_TYPE=PLASMA or PUNCH</p>|

## <a name="chmtopic1528"></a>**PATH\_TYPE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>EDM: Path type.</p><p>PATH\_TYPE=</p><p>1 (Profiling)</p><p>2 (Tab cutting)</p>|

## <a name="chmtopic1530"></a>**PI**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Mathematical constant = 3.14159265.|

## <a name="chmtopic1532"></a>**PITCH**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Punch: Nibbling pitch of move.|

|*Options*|NPITCH|NPITCH = nibbling pitch of next move|
| :- | :- | :- |
| |PPITCH|PPITCH = nibbling pitch of previous move|

## <a name="chmtopic169"></a>**PLANE\_4AX\_ANGLE**

|Type|DECIMAL|
| :- | :- |
|Usage|Stores the current setup’s 4<sup>th</sup> axis angle from the *Indexing* tab. Available in Mill posts. To be used in CAMWorks 2017 SP0 or higher versions. |






## <a name="chmtopic170"></a>**PLANE\_5AX\_ANGLE**

|Type|DECIMAL|
| :- | :- |
|Usage|Stores the current setup’s 5<sup>th</sup> axis angle from the *Indexing* tab. Available in Mill posts. To be used in CAMWorks 2017 SP0 or higher versions. |






## <a name="chmtopic1536"></a>**POST\_NAME**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|Reserved for future use.|

## <a name="chmtopic1538"></a>**POWER\_REG**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|EDM: Power register.|

## <a name="chmtopic1540"></a>**PREV\_SYSTEM**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Lathe/Mill post: What system you were in.</p><p>CURRENT\_SYSTEM=LATHE, MILL\_FACE OR MILL\_OD</p>|

## <a name="chmtopic16"></a>**PROBE\_A\_1ST\_ANGLE**
#### **Type**
**DECIMAL**
#### **Usage**
Stores the Probe Cycle's 1st rotary angle. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic17"></a>**PROBE\_B\_2ND\_ANGLE\_OR\_TOL**
#### **Type**
**DECIMAL**
#### **Usage**
Stores the Probe Cycle's 2nd *Rotary Angle* or *Tolerance*. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic18"></a>**PROBE\_C\_3RD\_ANGLE**
#### **Type**
**DECIMAL**
#### **Usage**
Stores the Probe Cycle's 3rd *Rotary Angle*. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic36"></a>**PROBE\_CYCLE\_FEEDRATE**
#### **Type**
**DECIMAL**
#### **Usage**
Stores the Probe Cycle's *Feedrate*. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic41"></a>**PROBE\_CYCLE\_TYPE**
#### **Type**
**INTEGER**
#### **Usage**
Stores the Probe Cycle's *Type*. To be used in CAMWorks 2020 SP0 or later versions.



PROBE\_CYCLE\_TYPE=SURFACE\_X\_TOOLPATH

`     `SURFACE\_Y\_TOOLPATH

`     `SURFACE\_Z\_TOOLPATH

`     `WEB\_X\_TOOLPATH

`     `WEB\_Y\_TOOLPATH

`     `POCKET\_X\_TOOLPATH

`     `POCKET\_Y\_TOOLPATH

`     `POCKET\_WITH\_ISLAND\_X\_TOOLPATH

`     `POCKET\_WITH\_ISLAND\_Y\_TOOLPATH

`     `BOSS\_TOOLPATH

`     `BORE\_TOOLPATH

`     `BORE\_WITH\_ISLAND\_TOOLPATH

`     `THREE\_POINT\_BOSS\_TOOLPATH

`     `THREE\_POINT\_BORE\_TOOLPATH

`     `THREE\_POINT\_BORE\_WITH\_ISLAND\_TOOLPATH
## <a name="chmtopic19"></a>**PROBE\_D\_NOMINAL\_SIZE**
#### **Type**
**DECIMAL**
#### **Usage**
Stores the Probe Cycle's 3rd *Nominal size*. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic20"></a>**PROBE\_E\_EXPERIENCE\_VALUE**
#### **Type**
**INTEGER**
#### **Usage**
Stores the Probe Cycle's *Experience value*. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic21"></a>**PROBE\_F\_PERCENT\_FEEDBACK**
#### **Type**
**DECIMAL**
#### **Usage**
Stores the Probe Cycle's *Percent feedback*. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic40"></a>**PROBE\_FIXTURE\_OFFSET\_NUM**
#### **Type**
**INTEGER**
#### **Usage**
Stores the Probe Cycle's *Fixture Offset* number. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic22"></a>**PROBE\_H\_TOL\_VALUE**
#### **Type**
**DECIMAL**
#### **Usage**
Stores the Probe Cycle's *Tolerance value*. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic23"></a>**PROBE\_I\_CYCLE\_SPEC\_DIST\_X**
#### **Type**
**DECIMAL**
#### **Usage**
Stores the Probe Cycle's *Spec distance in X*. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic24"></a>**PROBE\_J\_CYCLE\_SPEC\_DIST\_Y**
#### **Type**
**DECIMAL**
#### **Usage**
Stores the Probe Cycle's *Spec Distance in Y*. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic25"></a>**PROBE\_K\_CYCLE\_SPEC\_DIST\_Z**
#### **Type**
**DECIMAL**
#### **Usage**
Stores the Probe Cycle's *Spec Distance in Z*. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic26"></a>**PROBE\_M\_POS\_TOL**
#### **Type**
**DECIMAL**
#### **Usage**
Stores the Probe Cycle's *Position Tolerance Z*. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic27"></a>**PROBE\_Q\_OVERTRAVEL\_DIST**
#### **Type**
**DECIMAL**
#### **Usage**
Stores the Probe Cycle's *Overtravel distance*. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic28"></a>**PROBE\_R\_CLEARANCE**
#### **Type**
**DECIMAL**
#### **Usage**
Stores the Probe Cycle's *Retract clearance*. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic29"></a>**PROBE\_T\_TOOL\_OFFSET\_NUMBER**
#### **Type**
**INTEGER**
#### **Usage**
Stores the Probe Cycle's *Tool Offset number*. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic30"></a>**PROBE\_U\_UPPER\_TOL\_LIMIT**
#### **Type**
**DECIMAL**
#### **Usage**
Stores the Probe Cycle's *Upper Tolerance*. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic42"></a>**PROBE\_UPDATE\_OFFSET\_TYPE**
#### **Type**
**INTEGER**
#### **Usage**
Stores the Probe Cycle's *Work Coordinate* Offset type. To be used in CAMWorks 2020 SP0 or later versions.



PROBE\_UPDATE\_OFFSET\_TYPE=NONE

`          `FIXTURE

`          `WORK\_COORDINATE

`          `WORK\_AND\_SUB\_COORDINATE
## <a name="chmtopic39"></a>**PROBE\_UPDATE\_WCS\_OFFSET**
#### **Type**
**INTEGER**
#### **Usage**
Stores the Probe Cycle's* whether you are updating the *Work Coordinate Offset* or not. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic31"></a>**PROBE\_V\_NULL\_BAND**
#### **Type**
**DECIMAL**
#### **Usage**
Stores the Probe Cycle's *Null Band*. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic32"></a>**PROBE\_W\_PRINT\_DATA**
#### **Type**
**INTEGER**
#### **Usage**
Stores the Probe Cycle's *Print Data*. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic38"></a>**PROBE\_WORK\_OFFSET\_NUM**
#### **Type**
**INTEGER**
#### **Usage**
Stores the Probe Cycle's *Work Coordinate Offset number*. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic37"></a>**PROBE\_WORK\_SUB\_OFFSET\_NUM**
#### **Type**
**INTEGER**
#### **Usage**
Stores the Probe Cycle's *Work Coordinate* with *sub offset* number. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic33"></a>**PROBE\_X\_POS\_OR\_SIZE\_X**
#### **Type**
**DECIMAL**
#### **Usage**
Stores the Probe Cycle's *X position or size*. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic34"></a>**PROBE\_Y\_POS\_OR\_SIZE\_Y**
#### **Type**
**DECIMAL**
#### **Usage**
Stores the Probe Cycle's *Y position or size*. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic35"></a>**PROBE\_Z\_POS\_OR\_SIZE\_Z**
#### **Type**
**DECIMAL**
#### **Usage**
Stores the Probe Cycle's *Z position or size*. To be used in CAMWorks 2020 SP0 or later versions.
## <a name="chmtopic1569"></a>**PRT\_PATH** 


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|Stores the SOLIDWORKS \*.sldprt file path.|

## <a name="chmtopic1571"></a>**PROGRAM\_SURF**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|EDM: X,Y surface or plane of a part.|

## <a name="chmtopic171"></a>**QUERY\_STATS\_X\_MAX**

|Type|DECIMAL|
| :- | :- |
|Usage|Stores the X maximum value from the *Statistics* page when using the QUERY command [QUERY_CONFIGURATION_NAME](#chmtopic158). To be used in CAMWorks 2017 SP0 or higher versions.  |




## <a name="chmtopic172"></a>**QUERY\_STATS\_X\_MIN**

|Type|DECIMAL|
| :- | :- |
|Usage|Stores the X minimum value from the *Statistics* page when using the QUERY command [QUERY_CONFIGURATION_NAME](#chmtopic158). To be used in CAMWorks 2017 SP0 or higher versions. |






## <a name="chmtopic173"></a>**QUERY\_STATS\_Y\_MAX**

|Type|DECIMAL|
| :- | :- |
|Usage|Stores the Y maximum value from the *Statistics* page when using the QUERY command [QUERY_CONFIGURATION_NAME](#chmtopic158). To be used in CAMWorks 2017 SP0 or higher versions. .   |








## <a name="chmtopic174"></a>**QUERY\_STATS\_Y\_MIN**

|Type|DECIMAL|
| :- | :- |
|Usage|Stores the Y minimum value from the *Statistics* page when using the QUERY command [QUERY_CONFIGURATION_NAME](#chmtopic158). To be used in CAMWorks 2017 SP0 or higher versions.   |






## <a name="chmtopic175"></a>**QUERY\_STATS\_Z\_MAX**

|Type|DECIMAL|
| :- | :- |
|Usage|Stores the Z maximum value from the *Statistics* page when using the QUERY command [QUERY_CONFIGURATION_NAME](#chmtopic158). To be used in CAMWorks 2017 SP0 or higher versions. .   |


## <a name="chmtopic176"></a>**QUERY\_STATS\_Z\_MIN**

|Type|DECIMAL|
| :- | :- |
|Usage|Stores the Z minimum value from the *Statistics* page when using the QUERY command [QUERY_CONFIGURATION_NAME](#chmtopic158). To be used in CAMWorks 2017 SP0 or higher versions. .   |




## <a name="chmtopic1579"></a>**REAR\_TOOL**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>4-axis Lathe: Tool selection.</p><p>STATION\_NUM=R01</p>|

## <a name="chmtopic285"></a>**REAR\_TURRET\_TYPE**

|Type|INTEGER|
| :- | :- |
|Usage|Lets post know the rear turret type for a single rear turret post. If passed as "TOOL\_CHANGER" then this would normally be a B axis mill/turn or turn machine that has a tool changer. If not "TOOL\_CHANGER" then it would be a standard turret type turret with not tool changer. To be used in CAMWorks 2014 or newer version.|


## <a name="chmtopic283"></a>**REAR\_TURRET\_1\_TYPE**

|Type|INTEGER|
| :- | :- |
|Usage|Lets post know the 1st rear turret type. If passed as "TOOL\_CHANGER" then this would normally be a B axis mill/turn or turn machine that has a tool changer. If not "TOOL\_CHANGER" then it would be a standard turret type turret with no tool changer. To be used in CAMWorks 2014 or newer version.|


## <a name="chmtopic286"></a>**REAR\_TURRET\_2\_TYPE**

|Type|INTEGER|
| :- | :- |
|Usage|Lets post know the 2nd rear turret type. If passed as "TOOL\_CHANGER" then this would normally be a B axis mill/turn or turn machine that has a tool changer. If not "TOOL\_CHANGER" then it would be a standard turret type turret with no tool changer. To be used in CAMWorks 2014 or newer version.|


## <a name="chmtopic287"></a>**REAR\_TURRET\_3\_TYPE**

|Type|INTEGER|
| :- | :- |
|Usage|Lets post know the 3rd rear turret type. If passed as "TOOL\_CHANGER" then this would normally be a B axis mill/turn or turn machine that has a tool changer. If not "TOOL\_CHANGER" then it would be a standard turret type turret with no tool changer. To be used in CAMWorks 2014 or newer version.|


## <a name="chmtopic288"></a>**REAR\_TURRET\_4\_TYPE**

|Type|INTEGER|
| :- | :- |
|Usage|Lets post know the 4th rear turret type. If passed as "TOOL\_CHANGER" then this would normally be a B axis mill/turn or turn machine that has a tool changer. If not "TOOL\_CHANGER" then it would be a standard turret type turret with no tool changer. To be used in CAMWorks 2014 or newer version.|

## <a name="chmtopic1586"></a>**ROT\_TILT\_A**


|*Type*|DECIMAL||
| :- | :- | :- |
|*Usage*|5 axis "A" absolute rotation move.||
|*Options*|N\_ROT\_TILT\_A|N\_ = next move|
| |P\_ROT\_TILT\_A|P\_ = previous move|

## <a name="chmtopic1588"></a>**ROT\_TILT\_B**


|*Type*|DECIMAL||
| :- | :- | :- |
|*Usage*|5 axis "B" absolute tilt move.||
|*Options*|N\_ROT\_TILT\_B|N\_ = next move|
| |P\_ROT\_TILT\_B|P\_ = previous move|

## <a name="chmtopic1590"></a>**ROTATE\_ANGLE\_X**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Mill: 4th axis rotation about the X axis in degrees.|

## <a name="chmtopic1592"></a>**ROTATE\_ANGLE\_Z**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Mill: 4th axis rotation about the Z axis in degrees.|

## <a name="chmtopic1594"></a>**ROTATE\_TILE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>4 and 5 axis rotate and tilt combinations.</p><p>ROTATE\_TILT=</p><p>6 (rotate table and tilt head about x-axis)</p><p>18 (rotate table and tilt head about y-axis)</p><p>10 (rotate table and tilt table about x-axis for 4th axis rotation use<br>` `this for rotate x-axis "A" axis is being held on 4th axis)</p><p>34 (rotate table and tilt table about y-axis for 4th axis rotation use<br>` `this for rotate y-axis "A" axis is being held on 4thaxis)</p><p>11 (rotate arm and tilt head)</p>|

## <a name="chmtopic1596"></a>**ROTATE\_ANGLE\_Y**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Mill: 4th axis rotation about the Y axis in degrees.|

## <a name="chmtopic1598"></a>**SEQ**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Sequence number.|

## <a name="chmtopic1600"></a>**SCALLOP**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Scallop height when nibbling.|

|*Options*|N\_SCALLOP|N\_ = next scallop height when nibbling|
| :- | :- | :- |
| |P\_SCALLOP|P\_ = previous scallop height when nibbling|

## <a name="chmtopic1602"></a>**SEQ\_INCREMENT**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Sets the sequence increment.|

## <a name="chmtopic1604"></a>**SKIP\_1ST\_HIT**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Punch: Skip first hit.</p><p>Mill: Skip first hole. - SKIP\_1ST\_HIT=YES or NO</p>|

## <a name="chmtopic1606"></a>**STOCK\_DIAMETER**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|4-axis Lathe: Stock diameter.|

## <a name="chmtopic294"></a>**SUB\_CHUCK\_WIDTH**

|Type|DECIMAL|
| :- | :- |
|Usage|Lets post know the chuck width of sub-spindle. To be used in CAMWorks 2014 or newer version. .|

## <a name="chmtopic1609"></a>**SYSTEM\_COMP**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Offset direction of tool:</p><p>SYSTEM\_COMP=</p><p>OFFSET\_LEFT or OFFSET\_RIGHT</p><p>CENTER\_LEFT or CENTER\_RIGHT</p>|

## <a name="chmtopic1611"></a>**TAPER\_ANGLE\_END**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|EDM: Absolute taper angle end.|

|*Options*|N\_TAPER\_ANGLE\_END|N\_ = next absolute taper angle end|
| :- | :- | :- |
| |P\_TAPER\_ANGLE\_END|P\_ = previous absolute taper angle end|

## <a name="chmtopic1613"></a>**TAPER\_ANGLE\_START**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|EDM: Absolute taper angle start.|

|*Options*|N\_TAPER\_ANGLE\_START|N\_ = next absolute taper angle start|
| :- | :- | :- |
| |P\_TAPER\_ANGLE\_START|P\_ = previous absolute taper angle start|

## <a name="chmtopic1615"></a>**TOOL**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Tool number.|

|*Options*|N\_TOOL|N\_ = next entity tool number|
| :- | :- | :- |
| |NC\_TOOL|NC\_ = next tool change tool number|

## <a name="chmtopic1617"></a>**TOOL\_COMMENT**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|Tool comment.|

|*Options*|N\_TOOL\_COMMENT|N\_ = next entity tool comment|
| :- | :- | :- |
| |NC\_TOOL\_COMMENT|NC\_ = next tool change comment|

## <a name="chmtopic436"></a><a name="chmbookmark69"></a><a name="chmbookmark70"></a>**TOOL\_COOLANT**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>These system variables pass the coolant information from the CAMWorks tool definition. Supported in CAMWorks 2008 and later. Not supported in any ProCAM product.</p><p>TOOL\_COOLANT</p><p>N\_TOOL\_COOLANT</p><p>NC\_TOOL\_COOLANT</p><p> </p><p>MILL\_COOLANT\_OFF=1</p><p>MILL\_COOLANT\_FLOOD=2</p><p>MILL\_COOLANT\_MIST=3</p><p>MILL\_COOLANT\_THROUGH\_TOOL=4</p><p>MILL\_COOLANT\_AIR\_BLAST=5</p><p>MILL\_COOLANT\_HIGH\_PRESSURE=6</p><p>MILL\_COOLANT\_SPECIAL1=7</p><p>MILL\_COOLANT\_SPECIAL2=8</p><p>LATHE\_COOLANT\_FLOOD=1</p><p>LATHE\_COOLANT\_OFF=2</p><p>LATHE\_COOLANT\_MIST=3</p><p>LATHE\_COOLANT\_THROUGH\_TOOL=4</p><p>LATHE\_COOLANT\_AIR\_BLAST=5</p><p>LATHE\_COOLANT\_HIGH\_PRESSURE=6</p><p>LATHE\_COOLANT\_SPECIAL1=7</p>|




## <a name="chmtopic1620"></a>**TOOL\_CORNER\_RADIUS**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Corner radius value of a corner radius punch tool.|

## <a name="chmtopic152"></a>**TOOL\_CORNER\_RADIUS\_BOT**

|Type|DECIMAL|
| :- | :- |
|Usage|This variable stores the bottom radius of a keyway cutter. To be used in CAMWorks 2017 SP1 or higher versions. |

## <a name="chmtopic153"></a>**TOOL\_CORNER\_RADIUS\_TOP**

|Type|DECIMAL|
| :- | :- |
|Usage|This variable stores the top radius of a keyway cutter. To be used in CAMWorks 2017 SP1 or higher versions. |

## <a name="chmtopic1624"></a>**TOOL\_DIAMETER**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Tool dimensions.|

|*Options*|N\_TOOL\_DIAMETER|N\_ = next entity tool dimensions|
| :- | :- | :- |
| |NC\_TOOL\_DIAMETER|NC\_ = next tool change tool dimensions|

## <a name="chmtopic437"></a>**TOOL\_DIAM\_OFFSET**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>These system variables pass the tool diameter offset number from the CAMWorks tool definition. Supported in CAMWorks 2008 and later. Not supported in any ProCAM product.</p><p>TOOL\_DIAM\_OFFSET</p><p>N\_TOOL\_DIAM\_OFFSET</p><p>NC\_TOOL\_DIAM\_OFFSET</p>|


## <a name="chmtopic1627"></a>**TOOL\_DIE\_CLEAR**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Tool die clearance amount from feed and speed table.|

|*Options*|N\_TOOL\_DIE\_CLEAR|N\_ = next entity tool die clearance amount from feed and speed table|
| :- | :- | :- |
| |NC\_TOOL\_DIE\_CLEAR|NC\_ = next tool change tool die clearance amount from feed and speed table|

## <a name="chmtopic434"></a>**TOOL\_EDGE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Stores the selected tool edge type from the turn tool definition. Available in Turn and Mill/Turn. Supported in CAMWorks 2008 SP3.0 and later. Not supported in any ProCAM product.</p><p>TOOL\_EDGE=SIDE\_EDGE  or END\_EDGE</p><p>SIDE\_EDGE=0</p><p>END\_EDGE=1</p>|

## <a name="chmtopic1630"></a>**TOOL\_INDEX\_ANGLE**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Punch: Autoindex tool angle.|

|*Options*|N\_TOOL\_INDEX\_ANGLE|N\_ = next autoindex tool angle|
| :- | :- | :- |
| |P\_TOOL\_INDEX\_ANGLE|P\_ = previous autoindex tool angle|

## <a name="chmtopic1632"></a>**TOOL\_LENGTH**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Tool dimensions.|

|*Options*|N\_TOOL\_LENGTH|N\_ = next entity tool dimensions|
| :- | :- | :- |
| |NC\_TOOL\_LENGTH|NC\_ = next tool change tool dimensions|

## <a name="chmtopic439"></a>**TOOL\_LENGTH\_DIAM\_OFFSET\_METHOD**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>These system variables passes whether you selected the length and diameter offset numbers from the post or the tool definition. Supported in CAMWorks 2008 and later. Not supported in any ProCAM product.</p><p>METHOD\_FROM\_TOOL=0</p><p>METHOD\_FROM\_POST=1</p>|


## <a name="chmtopic438"></a>**TOOL\_LENGTH\_OFFSET**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>These system variables pass the tool length offset number from the CAMWorks tool definition. Supported in CAMWorks 2008 and later. Not supported in any ProCAM product.</p><p>TOOL\_LENGTH\_OFFSET</p><p>N\_TOOL\_LENGTH\_OFFSET</p><p>NC\_TOOL\_LENGTH\_OFFSET</p><p> </p>|


## <a name="chmtopic1636"></a>**TOOL\_LOAD\_ANGLE**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Load angle of the tool in a punch turret.|

## <a name="chmtopic1638"></a>**TOOL\_MATERIAL**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|Tool material from feed and speed table.|

|*Options*|N\_TOOL\_MATERIAL|N\_ = next entity tool material from feed and speed table|
| :- | :- | :- |
| |NC\_TOOL\_MATERIAL|NC\_ = next tool change tool material from feed and speed table|

## <a name="chmtopic1640"></a>**TOOL\_NUM\_TEETH**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Tool: Number of flutes from feed and speed table.|

|*Options*|N\_TOOL\_NUM\_TEETH|N\_ = next tool: number of flutes from feed and speed table|
| :- | :- | :- |
| |NC\_TOOL\_NUM\_TEETH|NC\_ = previous tool: number of flutes from feed and speed table|

## <a name="chmtopic1642"></a>**TOOL\_QT\_COMMENT**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|Mill and Lathe: 5th field of a fixed external file.|

## <a name="chmtopic1644"></a>**TOOL\_QTN**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Mill and Lathe: 4th field of a fixed external file.|

## <a name="chmtopic1646"></a>**TOOL\_SERIAL\_NUM**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|Tool serial number from feed and speed table.|

|*Options*|N\_TOOL\_SERIAL\_NUM|N\_ = next entity tool serial number from feed and speed table|
| :- | :- | :- |
| |NC\_TOOL\_SERIAL\_NUM|NC\_ = next tool change tool serial number from feed and speed table|

## <a name="chmtopic1648"></a>**TOOL\_SPEC\_TYPE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Tool special type:</p><p>TOOL\_SPEC\_TYPE=</p><p>AIR\_BLOW</p><p>PRESS\_RAISE</p><p>PRESSURE\_IGNORE</p>|

|*Options*|N\_TOOL\_SPEC\_TYPE|<p>Next entity tool special type:</p><p>N\_TOOL\_SPEC\_TYPE=</p><p>AIR\_BLOW</p><p>PRESS\_RAISE</p><p>PRESSURE\_IGNORE</p>|
| :- | :- | :- |
| |NC\_TOOL\_SPEC\_TYPE|<p>Next tool change tool special type:</p><p>NC\_TOOL\_SPEC\_TYPE=</p><p>AIR\_BLOW</p><p>PRESS\_RAISE</p><p>PRESSURE\_IGNORE</p>|

## <a name="chmtopic1650"></a>**TOOL\_SUB\_TYPE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Tool sub type:</p><p>TOOL\_SUB\_TYPE=</p><p>FLAT\_BOTTOM</p><p>HEELED</p><p>FORM</p><p>SHEAR\_PROOF</p><p>LOUVER</p><p>MARKING</p>|

|*Options*|N\_TOOL\_SUB\_TYPE|<p>Next entity tool sub type:</p><p>N\_TOOL\_SUB\_TYPE=</p><p>FLAT\_BOTTOM</p><p>HEELED</p><p>FORM</p><p>SHEAR\_PROOF</p><p>LOUVER</p><p>MARKING</p>|
| :- | :- | :- |
| |NC\_TOOL\_SUB\_TYPE|<p>Next tool change tool sub type:</p><p>NC\_TOOL\_SUB\_TYPE=</p><p>FLAT\_BOTTOM</p><p>HEELED</p><p>FORM</p><p>SHEAR\_PROOF</p><p>LOUVER</p><p>MARKING</p>|

## <a name="chmtopic1652"></a>**TOOL\_TIP\_CENTER**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Lathe: Tool compensation.</p><p>TOOL\_TIP\_CENTER=</p><p>1 (center)</p><p>2 (tip)</p>|

## <a name="chmtopic1654"></a>**TOOL\_TYPE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Tool type.</p><p>TOOL\_TYPE=</p><p>201 (Endmill)</p><p>202 (Ballnose)</p><p>203 (Hognose)</p><p>221 (Tapered Endmill)</p><p>222 (Tapered Ballnose)</p><p>223 (Tapered Hognose)</p><p>204 (Drill)</p><p>205 (Bore)</p><p>206 (Ream)</p><p>207 (Tap)</p><p>208 (Center Drill)</p><p>209 (Corner Round)</p><p>210 (Counter Sink)</p><p>211 (SP Thread Mill)</p><p>212 (MP Thread Mill)</p><p>213 (Dovetail)</p><p>214 (Keyway)</p><p>215 (Unknown)</p><p>216 (Lollipop)</p><p>217 (Facemill)</p><p>218 (Unknown)</p><p>301 (Round)</p><p>302 (Square)</p><p>303 (Triangle)</p><p>304 (Diamond)</p><p>305 (Diamond)</p><p>306 (Diamond)</p><p>315 (Diamond)</p><p>316 (Thread)</p><p>308 (Groove)</p><p>309 (Drill)</p><p>310 (Center Drill)</p><p>311 (Tap)</p><p>317 (Trigon)</p><p>318 (Hexagon)</p>|

|*Options*|N\_TOOL\_TYPE|N\_ = next entity tool type|
| :- | :- | :- |
| |NC\_TOOL\_TYPE|NC\_ = next tool change tool type|

## <a name="chmtopic1656"></a>**TOOL\_WIDTH**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Tool dimensions.|

|*Options*|N\_TOOL\_WIDTH|N\_ = next entity tool dimensions|
| :- | :- | :- |
| |NC\_TOOL\_WIDTH|NC\_ = next tool change tool dimensions|

## <a name="chmtopic1658"></a>**TOOL\_XGL**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Mill and Lathe: 3rd field of a fixed external file.|

## <a name="chmtopic1660"></a>**TOOL\_ZGL**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Mill and Lathe: 2nd field of a fixed external file.|

## <a name="chmtopic1662"></a>**TURRET**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>4-axis Lathe: Turret.</p><p>TURRET=FRONT or REAR.</p>|

|*Options*|N\_TURRET|<p>4-axis Lathe: Turret next operation.</p><p>N\_TURRET=FRONT or REAR</p>|
| :- | :- | :- |
| |P\_TURRET|4-axis Lathe: Turret previous operation.<br>P\_TURRET=FRONT or REAR|

## <a name="chmtopic1664"></a>**UV\_GUIDE\_OFFSET**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|EDM: U,V surface or plane guide offset of a part.|

## <a name="chmtopic1666"></a>**VECTOR\_I**


|*Type*|DECIMAL||
| :- | :- | :- |
|*Usage*|5 axis "I" axis vector move.||
|*Options*|N\_VECTOR\_I|N\_ = next move|
| |P\_VECTOR\_I|P\_ = previous move|

## <a name="chmtopic1668"></a>**VECTOR\_J**


|*Type*|DECIMAL||
| :- | :- | :- |
|*Usage*|5 axis "J" axis vector move.||
|*Options*|N\_VECTOR\_J|N\_ = next move|
| |P\_VECTOR\_J|P\_ = previous move|

## <a name="chmtopic1670"></a>**VECTOR\_K**


|*Type*|DECIMAL||
| :- | :- | :- |
|*Usage*|5 axis "K" axis vector move.||
|*Options*|N\_VECTOR\_K|N\_ = next move|
| |P\_VECTOR\_K|P\_ = previous move|

## <a name="chmtopic178"></a>**VOLUMILL\_HIGH\_FEEDRATE**


|Type|DECIMAL|
| :- | :- |
|Usage|Stores the high feedrate in VoluMill operations. If not a VoluMill operation, then the value will be equal to 0.  Available in Mill and Mill-Turn posts. To be used in CAMWorks 2017 SP0 or higher versions|






## <a name="chmtopic1673"></a>**WIDTH**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Tool compensated window X width.|

|*Options*|N\_WIDTH|N\_ = next tool compensated in window X width|
| :- | :- | :- |
| |P\_WIDTH|P\_ = previous tool compensated in window X width|

## <a name="chmtopic1675"></a>**WINDOW\_HEIGHT**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|CAD entity window Y height.|

|*Options*|N\_WINDOW\_HEIGHT|N\_ = next CAD entity window Y height|
| :- | :- | :- |
| |P\_WINDOW\_HEIGHT|P\_ = previous CAD entity window Y height|

## <a name="chmtopic1677"></a>**WINDOW\_ORIGIN\_X**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Absolute window origin.|

|*Options*|N\_WINDOW\_ORIGIN\_X|N\_ = next absolute window origin|
| :- | :- | :- |
| |P\_WINDOW\_ORIGIN\_X|P\_ = previous absolute window origin|

## <a name="chmtopic1679"></a>**WINDOW\_ORIGIN\_Y**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Absolute window origin.|

|*Options*|N\_WINDOW\_ORIGIN\_Y|N\_ = next absolute window origin|
| :- | :- | :- |
| |P\_WINDOW\_ORIGIN\_Y|P\_ = previous absolute window origin|

## <a name="chmtopic1681"></a>**WINDOW\_WIDTH**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|CAD entity window X width.|

|*Options*|N\_WINDOW\_WIDTH|N\_ = next CAD entity window X width|
| :- | :- | :- |
| |P\_WINDOW\_WIDTH|P\_ = previous CAD entity window X width|

## <a name="chmtopic1683"></a>**WIRE\_INCLINATION**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>EDM: Wire taper direction:</p><p>WIRE\_INCLINATION=</p><p>LEFT</p><p>RIGHT</p>|

## <a name="chmtopic8"></a>**WRAPPED\_AXIS**

|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores whether a Mill Wrapped feature is about X or Y axis. Available in Mill mode only. To be used in CAMWorks 2020 SP2 and higher versions.</p><p>WRAPPED\_AXIS=X\_AXIS, Y\_AXIS or NONE  </p>|

## <a name="chmtopic1686"></a>**XY\_GUIDE\_OFFSET**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|EDM: X,Y surface or plane guide offset of a part.|

## <a name="chmtopic1688"></a>**System Variables Reserved for Future Use**


The following METRIC DECIMAL system variables are reserved for future use.

|<p>Z\_AXIS</p><p>X\_AXIS</p><p>Y\_AXIS</p><p>I\_AXIS</p><p>J\_AXIS</p><p>K\_AXIS</p><p>ABS\_PRESET\_X</p><p>ABS\_PRESET\_Y</p><p>ABS\_PRESET\_Z</p><p>ABS\_PRESET\_C</p><p>X\_START\_POSITION</p><p>Z\_START\_POSITION</p><p>ATTRLVALUE</p><p>OPR\_LOOKAHEAD</p>|
| :- |



The following DECIMAL system variables are reserved for future use.

|<p>Q\_TAPER\_ANGLE\_START</p><p>P\_Q\_TAPER\_ANGLE\_START</p><p>N\_Q\_TAPER\_ANGLE\_START</p><p>Q\_TAPER\_ANGLE\_END</p><p>P\_Q\_TAPER\_ANGLE\_END</p><p>N\_Q\_TAPER\_ANGLE\_END</p><p>R\_TAPER\_ANGLE\_START</p><p>P\_R\_TAPER\_ANGLE\_START</p><p>N\_R\_TAPER\_ANGLE\_START</p><p>R\_TAPER\_ANGLE\_END</p><p>P\_R\_TAPER\_ANGLE\_END</p><p>N\_R\_TAPER\_ANGLE\_END</p>|
| :- |



The following INTEGER system variables are reserved for future use.

|<p>DIRECTION</p><p>ESC</p><p>RECNUM</p><p>NEXT\_OPR\_TOOL</p><p>MONTH</p><p>DAY</p><p>YEAR</p><p>CURRENT\_MACRO\_QUADRANT</p><p>CURRENT\_MACRO\_DEFINED</p><p>MACHINE\_MAX\_RPM</p><p>MACRO\_COUNT</p><p>MACRO\_ERROR</p><p>MACRO\_DEFINED</p><p>SYS\_COUNT</p>|
| :- |

## <a name="chmtopic215"></a>**3AXIS\_RAPID\_PLANE\_TYPE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Sets what the value for OPR\_Z\_RAPID\_PLANE is for 3 Axis operations. To be used in CAMWorks 2015 SP2 or newer version.</p><p>- Uses Operation parameters for OPR\_Z\_RAPID\_PLANE (Default)</p><p>&emsp;:SECTION = CALC\_POST\_INITALIZE</p><p>&emsp;:C: 3AXIS\_RAPID\_PLANE\_TYPE = AS\_DEFINED</p><p>- Sets OPR\_Z\_RAPID\_PLANE to toolpath Z Safe height</p><p>&emsp;:SECTION = CALC\_POST\_INITALIZE</p><p>&emsp;:C: 3AXIS\_RAPID\_PLANE\_TYPE = TLP\_SAFE\_Z</p><p>- Sets OPR\_Z\_RAPID\_PLANE to toolpath Z Start height</p><p>&emsp;:SECTION = CALC\_POST\_INITALIZE</p><p>&emsp;:C: 3AXIS\_RAPID\_PLANE\_TYPE = TLP\_START\_Z</p>|


## <a name="chmtopic230"></a>**ABS\_ARC\_MID\_X**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the arc midpoint in the X Axis. To be used in CAMWorks 2015 SP2 or newer version.|


## <a name="chmtopic231"></a>**ABS\_ARC\_MID\_Y**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the arc midpoint in the Y Axis. To be used in CAMWorks 2015 SP2 or newer version.|


## <a name="chmtopic232"></a>**ABS\_ARC\_MID\_Z**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the arc midpoint in the Z Axis. To be used in CAMWorks 2015 SP2 or newer version.|


## <a name="chmtopic1694"></a>**ABS\_PICK\_LOCATION**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|This variable stores the absolute value of the Lathe Sub Spindle transfer location along the Z axis. This works only in CAMWorks.|

## <a name="chmtopic318"></a>**ABS\_SPINDLE\_Z\_END**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>ABS\_SPINDLE\_Z\_END=Amount entered in spindle operation.                               </p><p>- This variable can be used in a sub spindle operation to move the sub spindle to desired position.</p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Lathe and Mill-Turn.</p>|

## <a name="chmtopic1697"></a>**ARC\_DEVIATION**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>Stores a deviation amount for doing a SYS\_CANNED(5,???) arc breakup in 4 and 5 axis milling with arcs that are not on the top plane. This is also used in a CAMWorks Live C post for OD and FACE milling for arc breakup, but not using SYS\_CANNED.</p><p>If you are creating a new post and your machine does not support arcs on different planes, then you need to add the question "max\_arc\_dev" to either the Setup Info or operation questions to set the deviation amount. This value will then set the post variable ARC\_DEVIATION to this value.</p><p>:C: ARC\_DEVIATION=max\_arc\_dev</p><p>:C: SYS\_CANNED(5,CALC\_BREAK\_ARC)</p>|

## <a name="chmtopic397"></a>**ARC\_NORM\_X**


|**Type**|DECIMAL||
| :- | :- | :- |
|**Usage**|This variable stores the current,  previous and next X axis arc normal vector. Available in Mill, Turn and Mill/Turn.||
|**Options**|N\_ARC\_NORM\_X|N\_ = next X axis arc normal vector|
| |P\_ARC\_NORM\_X|P\_ = previous X axis arc normal vector|


## <a name="chmtopic398"></a>**ARC\_NORM\_Y**


|**Type**|DECIMAL||
| :- | :- | :- |
|**Usage**|This variable stores the current,  previous and next Y axis arc normal vector. Available in Mill, Turn and Mill/Turn.||
|**Options**|N\_ARC\_NORM\_Y|N\_ = next Y axis arc normal vector|
| |P\_ARC\_NORM\_Y|P\_ = previous Y axis arc normal vector|


## <a name="chmtopic399"></a>**ARC\_NORM\_Z**


|**Type**|DECIMAL||
| :- | :- | :- |
|**Usage**|This variable stores the current,  previous and next Z axis arc normal vector. Available in Mill, Turn and Mill/Turn.||
|**Options**|N\_ARC\_NORM\_Z|N\_ = next Z axis arc normal vector|
| |P\_ARC\_NORM\_Z|P\_ = previous Z axis arc normal vector|

## <a name="chmtopic1702"></a>**ARM\_ACTIVE\_CUPS**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|Stores the ProCAM 2D sorter arm operations active cups.|

## <a name="chmtopic1704"></a>**ARM\_DESTINATION\_X / ARM\_DESTINATION\_Y**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|Stores the ProCAM 2D sorter arm operations destination position in the X axis (ARM\_DESTINATION\_X) or Y axis (ARM\_DESTINATION\_Y).|

## <a name="chmtopic1706"></a>**ARM\_ENGLISH\_LASERDB**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|Stores the Punch system sorter arm database path. Is used with the OPENDB command. It stores the English database path.|

## <a name="chmtopic1708"></a>**ARM\_METRIC\_LASERDB**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|Stores the Punch system sorter arm database path. Is used with the OPENDB command. It stores the Metric database path.|

## <a name="chmtopic1710"></a>**ARM\_OFFSET**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|Stores the ProCAM 2D sorter arm operations offset distance.|

## <a name="chmtopic1712"></a>**ARM\_PICKUP\_X / ARM\_PICKUP\_Y**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|Stores the ProCAM 2D sorter arm operations destination position in the X axis (ARM\_PICKUP\_X) or Y axis (ARM\_PICKUP\_Y).|

## <a name="chmtopic1714"></a>**ARM\_SORTER\_DBPATH**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|Stores Punch system sorter arm database path. Is used with the OPENDB command. It stores either the Metric database path or the English database path depending on the current system selected when posting.|

## <a name="chmtopic1716"></a>**BOUNDARY\_AREA**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|Stores the boundary area of a closed laser of plasma toolpath. Used in conjunction with the external database. If it is not a closed toolpath, then the value will be set to a -1.|

## <a name="chmtopic467"></a>**CAMWORKS\_MATERIAL**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|<p>This variable stores the selected material from CAMWorks Stock Manager. Currently, the post used a variable called "material" which was asked in the posting setup tab. If you are loading old parts that used the "material" and it was set, then we will use that string. If you are creating new parts, you can ignore that question and CAMWorks will set "material" to the same value as CAMWORKS\_MATERIAL. You can also remove the "material" question from the post and just use CAMWORKS\_MATERIAL. It will still set "material" because that variable is used in the post's setup output.</p><p>Supported in CAMWorks 2007 and later. Not supported in any ProCAM product.</p>|

## <a name="chmtopic464"></a>**CAMWORKS\_VER**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>CAMWorks 2007 and later: this variable stores which version of CAMWorks is running. Any version of CAMWorks below CW2006 will register as zero. As new commands are inserted into the posting system they will be available when new CAMWorks versions are released. If you want to use a post for two different versions of CAMWorks, then you may need to use this variable depending on the commands used in the post.</p><p> </p><p>CAMWORKS\_VER= CAM\_REV2006</p><p>CAMWORKS\_VER= CAM\_REV2006EX</p><p>CAMWORKS\_VER= CAM\_REV2007</p><p>CAMWORKS\_VER= CAM\_REV2008</p><p>CAMWORKS\_VER= CAM\_REV2009</p><p> </p><p>CAM\_REV2006=0</p><p>CAM\_REV2006EX=0</p><p>CAM\_REV2007=1</p><p>CAM\_REV2007\_SP1=71</p><p>CAM\_REV2007\_SP2=72</p><p>CAM\_REV2007\_SP2\_2=73</p><p>CAM\_REV2007\_SP3=74</p><p>CAM\_REV2007\_SP3\_1=75</p><p>CAM\_REV2007\_SP4\_1=76</p><p>CAM\_REV2008=80</p><p>CAM\_REV2008\_SP1=81</p><p>CAM\_REV2009=90</p><p>CAM\_REV2009\_SP1=91</p><p> </p><p>:C: IF **CAMWORKS\_VER**>**CAM\_REV2006EX** THEN</p><p>:C: IF FLAGGED(CAM\_MOVE\_FLAG,CAM\_APPROACH)=TRUE THEN</p><p>:C: IF FLAGGED(CAM\_MOVE\_FLAG, CAM\_MOVE\_X)=TRUE AND</p><p>:C: FLAGGED(CAM\_MOVE\_FLAG, CAM\_MOVE\_Z)=TRUE THEN</p><p>:C: CALL(RAPID\_MOVE\_LATHE)</p><p>:C: RETURN</p><p>:C: ELSE</p><p>:C: IF FLAGGED(CAM\_MOVE\_FLAG,CAM\_MOVE\_X)=TRUE THEN</p><p>:C: CALL(RAPID\_MOVE\_LATHE\_X)</p><p>:C: RETURN</p><p>:C: ELSE</p><p>:C: IF FLAGGED(CAM\_MOVE\_FLAG,CAM\_MOVE\_Z)=TRUE THEN</p><p>:C: CALL(RAPID\_MOVE\_LATHE\_Z)</p><p>:C: RETURN</p><p>:C: ENDIF</p><p>:C: ENDIF</p><p>:C: ENDIF</p><p>:C: ENDIF</p><p>:C: ENDIF</p>|

## <a name="chmtopic456"></a>**CAM\_MOVE\_FLAG**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>CAMWorks 2007 and later: this variable shows what type of lathe move you are doing.</p><p> </p><p>:C: IF FLAGGED(**CAM\_MOVE\_FLAG**,CAM\_APPROACH)=TRUE THEN</p><p>:C: IF FLAGGED(**CAM\_MOVE\_FLAG**, CAM\_MOVE\_X)=TRUE AND</p><p>:C: FLAGGED(**CAM\_MOVE\_FLAG**, CAM\_MOVE\_Z)=TRUE THEN</p><p>:C: CALL(RAPID\_MOVE\_LATHE)</p><p>:C: RETURN</p><p>:C: ELSE</p><p>:C: IF FLAGGED(**CAM\_MOVE\_FLAG**,CAM\_MOVE\_X)=TRUE THEN</p><p>:C: CALL(RAPID\_MOVE\_LATHE\_X)</p><p>:C: RETURN</p><p>:C: ELSE</p><p>:C: IF FLAGGED(**CAM\_MOVE\_FLAG**,CAM\_MOVE\_Z)=TRUE THEN</p><p>:C: CALL(RAPID\_MOVE\_LATHE\_Z)</p><p>:C: RETURN</p><p>:C: ENDIF</p><p>:C: ENDIF</p><p>:C: ENDIF</p><p>:C: ENDIF</p><p> </p><p>CAM\_MOVE\_FLAG=CAM\_RAPID</p><p>CAM\_MOVE\_FLAG=CAM\_APPROACH</p><p>CAM\_MOVE\_FLAG=CAM\_RETRACT</p><p>CAM\_MOVE\_FLAG=CAM\_MOVE\_X</p><p>CAM\_MOVE\_FLAG=CAM\_MOVE\_Y</p><p>CAM\_MOVE\_FLAG=CAM\_MOVE\_Z</p><p>CAM\_MOVE\_FLAG=CAM\_LEADIN</p><p>CAM\_MOVE\_FLAG=CAM\_LEADOUT</p><p> </p><p> </p><p>Bit Values</p><p>CAM\_RAPID=1</p><p>CAM\_APPROACH =2</p><p>CAM\_RETRACT=4</p><p>CAM\_MOVE\_X=8</p><p>CAM\_MOVE\_Y=16</p><p>CAM\_MOVE\_Z=32</p><p>CAM\_LEADIN=64</p><p>CAM\_LEADOUT=128</p><p> </p><p>Options</p><p>**N\_CAM\_MOVE\_FLAG**  N\_ = next move</p><p>**P\_CAM\_MOVE\_FLAG**  P\_ = previous move</p>|

## <a name="chmtopic200"></a>**CL\_COOLANT\_TYPE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores the coolant type selected from the CLT file for Gun Drilling operations where long code has been selected. To be used in CAMWorks 2016 or newer version.</p><p> </p><p>CL\_COOLANT\_TYPE = MILL\_COOLANT\_ON</p><p>CL\_COOLANT\_TYPE = MILL\_COOLANT\_OFF</p><p>CL\_COOLANT\_TYPE = MILL\_COOLANT\_FLOOD</p><p>CL\_COOLANT\_TYPE = MILL\_COOLANT\_MIST</p><p>CL\_COOLANT\_TYPE = MILL\_COOLANT\_THROUGH\_TOOL</p><p>CL\_COOLANT\_TYPE = MILL\_COOLANT\_AIR\_BLAST</p><p>CL\_COOLANT\_TYPE = MILL\_COOLANT\_HIGH\_PRESSURE</p><p>CL\_COOLANT\_TYPE = MILL\_COOLANT\_SPECIAL1</p><p>CL\_COOLANT\_TYPE = MILL\_COOLANT\_SPECIAL2</p><p>CL\_COOLANT\_TYPE =</p><p> </p><p>` `MILL\_COOLANT\_ON = 0 - Currently not supported at this time.</p><p>` `MILL\_COOLANT\_OFF = 1</p><p>` `MILL\_COOLANT\_FLOOD = 2</p><p>` `MILL\_COOLANT\_MIST = 3</p><p>` `MILL\_COOLANT\_THROUGH\_TOOL = 4</p><p>` `MILL\_COOLANT\_AIR\_BLAST = 5</p><p>` `MILL\_COOLANT\_HIGH\_PRESSURE = 6</p><p>` `MILL\_COOLANT\_SPECIAL1 = 7</p><p>` `MILL\_COOLANT\_SPECIAL2 = 8</p>|


## <a name="chmtopic1722"></a>**CLAMP(n)\_POSITION**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|Stores the punch manual clamp move, which will be an absolute distance. This will be available only if the post has the post header command<br>:MOVE\_CLAMP=TRUE.|
|**Variables**|<p>CLAMP1\_POSITION</p><p>CLAMP2\_POSITION</p><p>CLAMP3\_POSITION</p><p>CLAMP4\_POSITION</p>|

## <a name="chmtopic1724"></a>**DRILL\_CLEAR\_X**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>Drilled cycle clearance plane in X, Y and Z.</p><p>Note: When using CAMWorks 2005 or later, this variable will output the world coordinate correctly if the post has WORLD\_POSITIONING set to TRUE.</p><p>When using ProCAM II 2004 or later, WORLD\_POSITIONING in ProCAM II 2004 does not need to be set in the post.</p>|

## <a name="chmtopic1726"></a>**DRILL\_CLEAR\_Y**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>Drilled cycle clearance plane in X, Y and Z.</p><p>Note: When using CAMWorks 2005 or later, this variable will output the world coordinate correctly if the post has WORLD\_POSITIONING set to TRUE.</p><p>When using ProCAM II 2004 or later, WORLD\_POSITIONING in ProCAM II 2004 does not need to be set in the post.</p>|

## <a name="chmtopic1728"></a>**DRILL\_CLEAR\_Z**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>Drilled cycle clearance plane in X, Y and Z.</p><p>Note: When using CAMWorks 2005 or later, this variable will output the world coordinate correctly if the post has WORLD\_POSITIONING set to TRUE.</p><p>When using ProCAM II 2004 or later, WORLD\_POSITIONING in ProCAM II 2004 does not need to be set in the post.</p>|

## <a name="chmtopic1730"></a>**DRILL\_DEPTH\_X**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>Drilled cycle depth in X, Y and Z.</p><p>Note: When using CAMWorks 2005 or later, this variable will output the world coordinate correctly if the post has WORLD\_POSITIONING set to TRUE.</p><p>When using ProCAM II 2004 or later, WORLD\_POSITIONING in ProCAM II 2004 does not need to be set in the post.</p>|

## <a name="chmtopic1732"></a>**DRILL\_DEPTH\_Y**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>Drilled cycle depth in X, Y and Z.</p><p>Note: When using CAMWorks 2005 or later, this variable will output the world coordinate correctly if the post has WORLD\_POSITIONING set to TRUE.</p><p>When using ProCAM II 2004 or later, WORLD\_POSITIONING in ProCAM II 2004 does not need to be set in the post.</p>|

## <a name="chmtopic1734"></a>**DRILL\_DEPTH\_Z**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>Drilled cycle depth in X, Y and Z.</p><p>Note: When using CAMWorks 2005 or later, this variable will output the world coordinate correctly if the post has WORLD\_POSITIONING set to TRUE.</p><p>When using ProCAM II 2004 or later, WORLD\_POSITIONING in ProCAM II 2004 does not need to be set in the post.</p>|

## <a name="chmtopic225"></a>**DRILL\_DWELL**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the canned drilling cycles dwell amount. This system variable shares the value with the lowercase master.atr attribute "Dwell". For Turning operations, this variable will be used for canned cycles but for none canned cycles CW\_DWELL will be used. To be used in CAMWorks 2015 SP2 or newer version.|


## <a name="chmtopic1737"></a>**DRILL\_FACE\_X**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>Drilled cycle face plane in X, Y and Z.</p><p>Note: When using CAMWorks 2005 or later, this variable will output the world coordinate correctly if the post has WORLD\_POSITIONING set to TRUE.</p><p>When using ProCAM II 2004 or later, WORLD\_POSITIONING in ProCAM II 2004 does not need to be set in the post.</p>|

## <a name="chmtopic1739"></a>**DRILL\_FACE\_Y**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>Drilled cycle face plane in X, Y and Z.</p><p>Note: When using CAMWorks 2005 or later, this variable will output the world coordinate correctly if the post has WORLD\_POSITIONING set to TRUE.</p><p>When using ProCAM II 2004 or later, WORLD\_POSITIONING in ProCAM II 2004 does not need to be set in the post.</p>|

## <a name="chmtopic1741"></a>**DRILL\_FACE\_Z**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>Drilled cycle face plane in X, Y and Z.</p><p>Note: When using CAMWorks 2005 or later, this variable will output the world coordinate correctly if the post has WORLD\_POSITIONING set to TRUE.</p><p>When using ProCAM II 2004 or later, WORLD\_POSITIONING in ProCAM II 2004 does not need to be set in the post.</p>|

## <a name="chmtopic1743"></a>**DRILL\_PECK\_DEPTH\_X**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>Pecking cycle peck depth per peck in X, Y and Z. Works in conjunction with SYS\_CANNED(????). See SYS\_CANNED.</p><p>Note: When using CAMWorks 2005 or later, this variable will output the world coordinate correctly if the post has WORLD\_POSITIONING set to TRUE.</p><p>When using ProCAM II 2004 or later, WORLD\_POSITIONING in ProCAM II 2004 does not need to be set in the post.</p>|

## <a name="chmtopic1745"></a>**DRILL\_PECK\_DEPTH\_Y**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>Pecking cycle peck depth per peck in X, Y and Z. Works in conjunction with SYS\_CANNED(????). See SYS\_CANNED.</p><p>Note: When using CAMWorks 2005 or later, this variable will output the world coordinate correctly if the post has WORLD\_POSITIONING set to TRUE.</p><p>When using ProCAM II 2004 or later, WORLD\_POSITIONING in ProCAM II 2004 does not need to be set in the post.</p>|

## <a name="chmtopic1747"></a>**DRILL\_PECK\_DEPTH\_Z**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>Pecking cycle peck depth per peck in X, Y and Z. Works in conjunction with SYS\_CANNED(????). See SYS\_CANNED.</p><p>Note: When using CAMWorks 2005 or later, this variable will output the world coordinate correctly if the post has WORLD\_POSITIONING set to TRUE.</p><p>When using ProCAM II 2004 or later, WORLD\_POSITIONING in ProCAM II 2004 does not need to be set in the post.</p>|

## <a name="chmtopic1749"></a>**DRILL\_PECK\_RAPID\_TO\_X**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>Pecking cycle rapid back into hole clearance plane in X, Y and Z. Works in conjunction with SYS\_CANNED(????). See SYS\_CANNED.</p><p>Note: When using CAMWorks 2005 or later, this variable will output the world coordinate correctly if the post has WORLD\_POSITIONING set to TRUE.</p><p>When using ProCAM II 2004 or later, WORLD\_POSITIONING in ProCAM II 2004 does not need to be set in the post.</p>|

## <a name="chmtopic1751"></a>**DRILL\_PECK\_RAPID\_TO\_Y**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>Pecking cycle rapid back into hole clearance plane in X, Y and Z. Works in conjunction with SYS\_CANNED(????). See SYS\_CANNED.</p><p>Note: When using CAMWorks 2005 or later, this variable will output the world coordinate correctly if the post has WORLD\_POSITIONING set to TRUE.</p><p>When using ProCAM II 2004 or later, WORLD\_POSITIONING in ProCAM II 2004 does not need to be set in the post.</p>|

## <a name="chmtopic1753"></a>**DRILL\_PECK\_RAPID\_TO\_Z**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>Pecking cycle rapid back into hole clearance plane in X, Y and Z. Works in conjunction with SYS\_CANNED(????). See SYS\_CANNED.</p><p>Note: When using CAMWorks 2005 or later, this variable will output the world coordinate correctly if the post has WORLD\_POSITIONING set to TRUE.</p><p>When using ProCAM II 2004 or later, WORLD\_POSITIONING in ProCAM II 2004 does not need to be set in the post.</p>|

## <a name="chmtopic1755"></a>**DRILL\_RAPID\_X**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>Drilled cycle rapid plane in X, Y and Z.</p><p>Note: When using CAMWorks 2005 or later, this variable will output the world coordinate correctly if the post has WORLD\_POSITIONING set to TRUE.</p><p>When using ProCAM II 2004 or later, WORLD\_POSITIONING in ProCAM II 2004 does not need to be set in the post.</p>|

## <a name="chmtopic1757"></a>**DRILL\_RAPID\_Y**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>Drilled cycle rapid plane in X, Y and Z.</p><p>Note: When using CAMWorks 2005 or later, this variable will output the world coordinate correctly if the post has WORLD\_POSITIONING set to TRUE.</p><p>When using ProCAM II 2004 or later, WORLD\_POSITIONING in ProCAM II 2004 does not need to be set in the post.</p>|

## <a name="chmtopic1759"></a>**DRILL\_RAPID\_Z**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>Drilled cycle rapid plane in X, Y and Z.</p><p>Note: When using CAMWorks 2005 or later, this variable will output the world coordinate correctly if the post has WORLD\_POSITIONING set to TRUE.</p><p>When using ProCAM II 2004 or later, WORLD\_POSITIONING in ProCAM II 2004 does not need to be set in the post.</p>|

## <a name="chmtopic1761"></a>**DRILL\_SAFE\_X**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>Drilled cycle safe retract plane in X, Y and Z.</p><p>Note: When using CAMWorks 2005 or later, this variable will output the world coordinate correctly if the post has WORLD\_POSITIONING set to TRUE.</p><p>When using ProCAM II 2004 or later, WORLD\_POSITIONING in ProCAM II 2004 does not need to be set in the post.</p>|

## <a name="chmtopic1763"></a>**DRILL\_SAFE\_Y**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>Drilled cycle safe retract plane in X, Y and Z.</p><p>Note: When using CAMWorks 2005 or later, this variable will output the world coordinate correctly if the post has WORLD\_POSITIONING set to TRUE.</p><p>When using ProCAM II 2004 or later, WORLD\_POSITIONING in ProCAM II 2004 does not need to be set in the post.</p>|

## <a name="chmtopic1765"></a>**DRILL\_SAFE\_Z**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>Drilled cycle safe retract plane in X, Y and Z.</p><p>Note: When using CAMWorks 2005 or later, this variable will output the world coordinate correctly if the post has WORLD\_POSITIONING set to TRUE.</p><p>When using ProCAM II 2004 or later, WORLD\_POSITIONING in ProCAM II 2004 does not need to be set in the post.</p>|

## <a name="chmtopic226"></a>**DRILL\_SHIFT**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the canned boring cycles shift amount. This system variable shares the value with the lowercase master.atr attribute "Shift Amount". For Turning operations CW\_DWELL will be used. To be used in CAMWorks 2015 SP2 or newer version.|


## <a name="chmtopic459"></a>**DRIVE\_POINT\_TYPE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>**P\_DRIVE\_POINT\_TYPE**</p><p>**DRIVE\_POINT\_TYPE**</p><p>**N\_DRIVE\_POINT\_TYPE**</p><p>This variable stores the drive point of a finish grooving cycle tool during posting. This variable will be updated in a called section "CALC\_SHIFT\_TOOL\_LATHE".</p><p>Supported in CAMWorks 2007 and later. Not supported in any ProCAM product.</p><p> </p><p>DRIVE\_CENTER=0</p><p>DRIVE \_RIGHT=1</p><p>DRIVE \_LEFT=2</p><p>DRIVE \_TOOL\_NOSE=3</p>|

## <a name="chmtopic981"></a>**DSPINDLE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>This variable stores whether you are using a main or sub spindle in the lathe system. This works in ProCAM 2D and CAMWorks.</p><p>DSPINDLE=MAIN\_SPINDLE</p><p>DSPINDLE=SUB\_SPINDLE</p><p> </p><p>MAIN\_SPINDLE =1</p><p>SUB\_SPINDLE =2</p>|

## <a name="chmtopic142"></a>**FACET\_DEVIATION**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|This variable stores the Facet Deviation from the Operation Parameters dialog box. To be used in CAMWorks 2017 SP2 or higher versions.|

## <a name="chmtopic395"></a>**FRONT\_SYNC\_CODE**


|**Type**|INTEGER||
| :- | :- | :- |
|**Usage**|This variable stores the current and previous front turret sync code number. Available in Turn and Mill/Turn. These variables are set in CW2010, however the option of syncing turrets is not implemented in CW2010.||
|**Options**|P\_FRONT\_SYNC\_CODE| |

## <a name="chmtopic396"></a>**FRONT\_SYNC\_CODE\_TYPE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>This variable stores the front turret sync code type. Available in Turn and Mill/Turn. These variables are set in CW2010, however the option of syncing turrets is not implemented in CW2010.</p><p>FRONT\_SYNC\_CODE\_TYPE= SYNC\_CODE\_UNKNOWN</p><p>FRONT\_SYNC\_CODE\_TYPE= SYNC\_CODE\_BEFORE\_START</p><p>FRONT\_SYNC\_CODE\_TYPE= SYNC\_CODE\_BEFORE\_FIRST\_MOVE</p><p>FRONT\_SYNC\_CODE\_TYPE= SYNC\_CODE\_AFTER\_END</p><p> </p><p>SYNC\_CODE\_UNKNOWN = 0</p><p>SYNC\_CODE\_BEFORE\_START = 1</p><p>SYNC\_CODE\_BEFORE\_FIRST\_MOVE = 2</p><p>SYNC\_CODE\_AFTER\_END = 3</p>|

## <a name="chmtopic194"></a>**GUN\_DRILL\_DWELL\_BEFORE\_DRILL**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the dwell amount at pilot hole depth before starting to drill in Mill and Mill-Turn operations. Not available in CAMWorks 2016 but in some future version.|


## <a name="chmtopic198"></a>**GUN\_DRILL\_CHANGE\_RPM\_AT**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores whether to change the RPM at pilot depth or feedrate point in Mill and Mill-Turn operations. Not available in CAMWorks 2016 but in a future version.</p><p> </p><p>GUN\_DRILL\_CHANGE\_RPM\_AT = FEEDBACK</p><p>GUN\_DRILL\_CHANGE\_RPM\_AT = PILOT\_DEPTH</p><p> </p><p>FEEDBACK = 1</p><p>PILOT\_DEPTH = 2</p>|


## <a name="chmtopic193"></a>**GUN\_DRILL\_ENTRY\_RETRACT\_SPEED**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|Stores the RPM while feeding in the pilot hole and retracting out of the hole in Mill and Mill-Turn operations. Not available in CAMWorks 2016 but in a future version.|


## <a name="chmtopic195"></a>**GUN\_DRILL\_FEEDBACK\_AMOUNT**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the feedback amount after drilling in Mill and Mill-Turn operations. Not available in CAMWorks 2016 but in a future version.|


## <a name="chmtopic197"></a>**GUN\_DRILL\_IS\_RAPID\_RETRACT**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores whether rapid retract was selected in Mill and Mill-Turn operations. Not available in CAMWorks 2016 but in a future version.</p><p> </p><p>GUN\_DRILL\_IS\_RAPID\_RETRACT = FALSE</p><p>GUN\_DRILL\_IS\_RAPID\_RETRACT = TRUE</p>|


## <a name="chmtopic191"></a>**GUN\_DRILL\_PILOT\_FEEDIN\_DIST**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the feedin distance before starting to Drill in Mill and Mill-Turn operations. Not available in CAMWorks 2016 but in a future version.|


## <a name="chmtopic192"></a>**GUN\_DRILL\_PILOT\_FEEDRATE**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the feedrate while feeding in the pilot hole in Mill and Mill-Turn operations. Not available in CAMWorks 2016 but in a future version.|


## <a name="chmtopic196"></a>**GUN\_DRILL\_RETRACT\_FEEDRATE**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the feedrate while retracting out of drilled hole in Mill and Mill-Turn operations. Not available in CAMWorks 2016 but in a future version.|


## <a name="chmtopic182"></a>**HAVE\_COORDINATE\_SYS**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores whether programmer selected Fixture Coordinate System in CAMWorks main Setup area. To be used in CAMWorks 2016 SP2 or newer version.</p><p> </p><p>HAVE\_COORDINATE\_SYS = FALSE or TRUE</p>|


## <a name="chmtopic329"></a>**HAVE\_END\_OPER\_SYNC\_CODES**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>HAVE\_END\_OPER\_SYNC\_CODES = TRUE or FALSE    </p><p>- This variable can be used to find out if CAMWorks has passed sync codes at end of an operation.        </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Lathe and Mill-Turn.</p>|

## <a name="chmtopic100"></a>**HAVE\_FIRST\_FEED\_SYNC\_CODES**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>HAVE\_FIRST\_FEED\_SYNC\_CODES=TRUE or FALSE</p><p>This variable can be used to find out whether CAMWorks has passed sync codes at the first feed move of an operation.</p><p>Not supported in any ProCAM product or CAMWorks product earlier than CAMWorks 2019 SP0 version.</p><p>Available in Turn and Mill-Turn.      </p>|


## <a name="chmtopic328"></a>**HAVE\_FIRST\_MOVE\_SYNC\_CODES**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>HAVE\_FIRST\_MOVE\_SYNC\_CODES = TRUE or FALSE   </p><p>- This variable can be used to find out if CAMWorks has passed sync codes at first rapid move of an operation.       </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Lathe and Mill-Turn.</p>|

## <a name="chmtopic327"></a>**HAVE\_START\_OPER\_SYNC\_CODES**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>HAVE\_START\_OPER\_SYNC\_CODES = TRUE or FALSE  </p><p>- This variable can be used to find out if CAMWorks has passed sync codes at the start of an operation.      </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Lathe and Mill-Turn.</p>|

## <a name="chmtopic326"></a>**HAVE\_SUB\_STATIONS**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>HAVE\_SUB\_STATIONS = TRUE or FALSE</p><p>- This variable can be used to find out if user selected to use sub stations when defining tools.     </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Mill, Lathe and Mill-Turn.</p>|

## <a name="chmtopic1787"></a>**INC\_PICK\_LOCATION**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|This variable stores the incremental value of the Lathe Sub Spindle transfer location along the Z axis. This works only in CAMWorks.|

## <a name="chmtopic1789"></a>**INIT\_TOOL\_LENGTH**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>Stores the internal tool length that is defined in the tool definition and is used in the system calc section called :SECTION=CALC\_TOOL\_INITIALIZE. This is used when the machine is 4 or 5 axis and the head rotates and or tilts. In this case the posted output may need to have the numbers modified for tool length.</p><p>Note: Can be used only with CAMWorks 2005 or ProCAM II 2004 or later versions.</p>|

## <a name="chmtopic190"></a>**IS\_CANNED\_DRILL\_CYCLE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|Returns a TRUE or FALSE value whether the drilling operation is canned or not in Mill and Mill-Turn operations. To be used in CAMWorks 2016 or newer version.|


## <a name="chmtopic314"></a>**IS\_COMMENT**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>IS\_COMMENT=TRUE or FALSE</p><p>- This variable can be used in a sub spindle operation if user selected to output code or comment to the program.</p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Lathe and Mill-Turn.</p>|

## <a name="chmtopic235"></a>**IS\_PATTERN\_FEATURE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|Passes information to the post whether the feature is patterned or not. The value will either be TRUE or FALSE. To be used in CAMWorks 2015 SP1 or newer version.|


## <a name="chmtopic51"></a>**IS\_SUB\_SPINDLE\_REVERSE\_Z**
#### **Type**
**INTEGER**
#### **Usage**
Stores a binary value (TRUE or FALSE) to indicate if the user has flipped the Z direction on the Sub Spindle coordinate system. To be used in CAMWorks 2020 SP0 and higher versions.


#### **Syntax**
**IS\_SUB\_SPINDLE\_REVERSE\_Z=TRUE or FALSE**
**\

## <a name="chmtopic236"></a>**IS\_TLP\_COMPENSATED**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|Passes information to the post whether the toolpath is compensated or not. The value will either be TRUE or FALSE. To be used in CAMWorks 2015 SP1 or newer version.|


## <a name="chmtopic1796"></a>**KOMBID**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|Stores the CAMWorks assembly mode tool ID information per tool change.|

## <a name="chmtopic461"></a>**LATHE\_X\_TOOL\_OFFSET**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|<p>**P\_LATHE\_X\_TOOL\_OFFSET**</p><p>**LATHE\_X\_TOOL\_OFFSET**</p><p>**N\_LATHE\_X\_TOOL\_OFFSET**</p><p>This variable stores the lathe finish grooving cycle's shift amount. This is an incremental signed distance from the center of the groove tool to the driven touch off point in the X direction.</p><p>Supported in CAMWorks 2007 and later. Not supported in any ProCAM product.</p>|

## <a name="chmtopic462"></a>**LATHE\_Z\_TOOL\_OFFSET**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|<p>**P\_LATHE\_Z\_TOOL\_OFFSET**</p><p>**LATHE\_Z\_TOOL\_OFFSET**</p><p>**N\_LATHE\_Z\_TOOL\_OFFSET**</p><p>This variable stores the lathe finish grooving cycle's shift amount. This is an incremental signed distance from the center of the groove tool to the driven touch off point in the Z direction.</p><p>Supported in CAMWorks 2007 and later. Not supported in any ProCAM product.</p>|

## <a name="chmtopic52"></a>**MACH\_NUMBER\_AXIS**

|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores how many axes the system has been setup for and what was selected in a Multiaxis operation. To be used in CAMWorks 2020 SP0 or higher versions.</p><p> </p><p>MACH\_NUMBER\_AXIS=3, 4 OR 5</p>|

## <a name="chmtopic53"></a>**MACH\_ROTARY\_4AXIS\_TYPE**

|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores what 4-Axis type the system has been setup for. To be used in CAMWorks 2020 SP0 or higher versions.</p><p>MACH\_ROTARY\_4AXIS\_TYPE=ROTATE\_ABOUT\_X</p><p>`                                        `ROTATE\_ABOUT\_Y</p><p>`                                        `ROTATE\_ABOUT\_Z</p><p>`                                        `ROTATE\_ABOUT\_MULTIPLE</p>|

## <a name="chmtopic54"></a>**MACH\_ROTARY\_VEC\_4X**

|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the 4th axis rotary vector for X. To be used in CAMWorks 2020 SP0 or higher versions.|

## <a name="chmtopic55"></a>**MACH\_ROTARY\_VEC\_4Y**

|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the 4th axis rotary vector for Y. To be used in CAMWorks 2020 SP0 or higher versions.|

## <a name="chmtopic56"></a>**MACH\_ROTARY\_VEC\_4Z**

|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the 4th axis rotary vector for Z. To be used in CAMWorks 2020 SP0 or higher versions.|

## <a name="chmtopic57"></a>**MACH\_ROTARY\_VEC\_5X**

|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the 5th axis tilt vector for X. To be used in CAMWorks 2020 SP0 or higher versions.|

## <a name="chmtopic58"></a>**MACH\_ROTARY\_VEC\_5Y**

|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the 5th axis tilt vector for Y. To be used in CAMWorks 2020 SP0 or higher versions.|

## <a name="chmtopic59"></a>**MACH\_ROTARY\_VEC\_5Z**

|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the 5th axis tilt vector for Z. To be used in CAMWorks 2020 SP0 or higher versions.|

## <a name="chmtopic101"></a>**MACHINE\_MAX\_FEEDRATE**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|<p>Stores the maximum feedrate in Mill operations. Available in Mill and Mill-Turn posts. To be used in CAMWorks 2019 SP0 or higher versions.</p><p> </p>|


## <a name="chmtopic81"></a>**MAX\_B\_AXIS\_INCREMENT**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|<p>This needs to be set for breaking up a Turn operation's X, Z and B axis simultaneous toolpath using the [SYS_CANNED(7,????)](#chmbookmark64) command when in a line or arc move.  </p><p>To be used in CAMWorks 2019 SP1 or later versions.</p>|
|**Example**|<p>:SECTION=CALC\_ARC\_MOVE\_LATHE</p><p>:C: MAX\_B\_AXIS\_INCREMENT=Post Variable</p><p>:C: SYS\_CANNED(7,CALC\_BREAK\_ARC\_TO\_ARC\_LATHE)</p><p>\*:C: SYS\_CANNED(7, CALC\_BREAK\_RADIAL\_ARC\_TO\_ARC\_LATHE)</p><p>:C: RETURN</p><p> </p><p>:SECTION=CALC\_BREAK\_ARC\_TO\_ARC\_LATHE</p><p>:C: X\_POS=ABS\_X\_END</p><p>:C: Z\_POS=ABS\_Z\_END</p><p>:C: CALL(ARC\_MOVE\_LATHE)</p><p>\*-----------------------------------</p><p>:SECTION=CALC\_BREAK\_RADIAL\_ARC\_TO\_ARC\_LATHE</p><p>:C: X\_POS=ABS\_X\_END</p><p>:C: Z\_POS=ABS\_Z\_END</p><p>:C: CALL(RADIUS\_MOVE\_LATHE)</p><p> </p><p>**Lines can also be broken as follows:**</p><p> </p><p>:SECTION=CALC\_LINE\_MOVE\_LATHE</p><p>:C: MAX\_B\_AXIS\_INCREMENT=1.</p><p>:C: SYS\_CANNED(7,CALC\_BREAK\_LINE\_LATHE)</p><p>:C: RETURN</p><p> </p><p> </p><p>:SECTION= CALC\_BREAK\_LINE\_LATHE</p><p>:C: X\_POS=ABS\_X\_END</p><p>:C: Z\_POS=ABS\_Z\_END</p><p>:C: CALL(LINE\_MOVE\_LATHE)</p>|


## <a name="chmtopic332"></a>**MCS\_TYPE**


|`  `**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>MCS\_TYPE=1</p><p>MCS\_TYPE=2</p><p>MCS\_TYPE=3</p><p>1=Fixture coordinate</p><p>2=Work coordinate</p><p>3=Work coordinate with Sub work coordinate</p><p>- This variable can be used to find the selected Fixture coordinate type.         </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Mill, Lathe and Mill-Turn.</p>|

## <a name="chmtopic271"></a>**MCS\_U\_NAME**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|<p>Tells Simulator what is the axis label for the X axis move of the sub spindle. Can be used in the QUERY\_ITEM\_ID=QUERY\_GCODE\_WCS section.</p><p>To be used in CAMWorks 2014 or newer version.</p>|


## <a name="chmtopic274"></a>**MCS\_U\_OFFSET**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|<p>Tells Simulator what the X axis offset is for the sub spindle. Can be used in the QUERY\_ITEM\_ID=QUERY\_GCODE\_WCS section.</p><p>To be used in CAMWorks 2014 or newer version.</p>|


## <a name="chmtopic272"></a>**MCS\_V\_NAME**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|<p>Tells Simulator what is the axis label for the Y axis move of the sub spindle.  Can be used in the QUERY\_ITEM\_ID=QUERY\_GCODE\_WCS section.</p><p>To be used in CAMWorks 2014 or newer version.</p>|


## <a name="chmtopic275"></a>**MCS\_V\_OFFSET**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|<p>Tells Simulator what the Y axis offset is for the sub spindle. Can be used in the QUERY\_ITEM\_ID=QUERY\_GCODE\_WCS section.</p><p>To be used in CAMWorks 2014 or newer version.</p>|


## <a name="chmtopic273"></a>**MCS\_W\_NAME**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|<p>Tells Simulator what is the axis label for the Z axis move of the sub spindle. Can be used in the QUERY\_ITEM\_ID=QUERY\_GCODE\_WCS section.</p><p>To be used in CAMWorks 2014 or newer version.</p>|


## <a name="chmtopic276"></a>**MCS\_W\_OFFSET**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|<p>Tells Simulator what the Z axis offset is for the sub spindle. Can be used in the QUERY\_ITEM\_ID=QUERY\_GCODE\_WCS section.</p><p>To be used in CAMWorks 2014 or newer version.</p>|


## <a name="chmtopic1817"></a>**MCS\_X\_OFFSET**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|Stores the Machine coordinate System as an absolute position in X using ProCAM II or CAMWorks assembly mode.|

## <a name="chmtopic1819"></a>**MCS\_Y\_OFFSET**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|Stores the Machine coordinate System as an absolute position in Y using ProCAM II or CAMWorks assembly mode.|

## <a name="chmtopic1821"></a>**MCS\_Z\_OFFSET**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|Stores the Machine coordinate System as an absolute position in Z using ProCAM II or CAMWorks assembly mode.|

## <a name="chmtopic441"></a>**MULTIAXIS\_CNC\_COMP**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Allows the post to detect whether 3D+ CNC cutter comp has been selected in a multiaxis operation. There are specific machines that can use 3D+ CNC cutter comp. This is available only in CAMWorks Multiaxis operations. Supported in CAMWorks 2008 and later. Not supported in any ProCAM product.</p><p>MULTIAXIS\_CNC\_COMP=TRUE or FALSE</p>|
#### ** 

## <a name="chmtopic141"></a>**MULTIAXIS\_MAX\_MOVE\_DISTANCE**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|This variable stores the maximum move distance in a multiaxis operation. To be used in CAMWorks 2017 SP2 or higher versions.|

## <a name="chmtopic115"></a><a name="chmbookmark71"></a><a name="chmbookmark72"></a>**TURRET\_NUM**
## **P\_TURRET\_NUM**  
## **N\_TURRET\_NUM**  


|**Type**|INTEGER|
| :- | :- |
|**Usage**|Stores the current operations turret number and previous and next turret. To be used in CAMWorks 2019 SP0 or higher versions.|


## <a name="chmtopic324"></a>**NC\_SUB\_STATION**


|**Type**|<p>INTEGER</p><p> </p>|
| :- | :- |
|**Usage**|<p>- This variable can be used find the next tool sub station number.   </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Mill, Lathe and Mill-Turn.</p>|

## <a name="chmtopic337"></a>**NC\_SUB\_STATION\_ID**


|**Type**|<p>CHARACTER</p><p> </p>|
| :- | :- |
|**Usage**|<p>- This variable can be used to find the next tool sub station description.                 </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Mill, Lathe and Mill-Turn.</p>|

## <a name="chmtopic135"></a><a name="chmbookmark73"></a><a name="chmbookmark74"></a>**TOOL\_INEFFECTIVE\_LENGTH**
## **N\_TOOL\_INEFFECTIVE\_LENGTH**
## **NC\_TOOL\_INEFFECTIVE\_LENGTH**


|Type|DECIMAL|
| :- | :- |
|Usage|This variable stores the current move, next move and next tool change tool’s ineffective length. To be used in CAMWorks 2018 SP0 or higher versions.  |


## <a name="chmtopic339"></a>**NC\_TOOL\_X\_GAGE\_OFFSET**
## **NC\_TOOL\_Y\_GAGE\_OFFSET**
## **NC\_TOOL\_Z\_GAGE\_OFFSET**


|**Type**|<p>METRIC DECIMAL</p><p> </p>|
| :- | :- |
|**Usage**|<p>- This variable can be used to find the next tool X,Y and Z gage offset.                 </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Mill, Lathe and Mill-Turn</p>|

## <a name="chmtopic136"></a><a name="chmbookmark75"></a>**TOOL\_TIP\_OFFSET**
## **N\_TOOL\_TIP\_OFFSET**
## **NC\_TOOL\_TIP\_OFFSET**


|Type|DECIMAL|
| :- | :- |
|Usage|<p>This variable stores information whether the current move, next move and next tool change tool use the tool tip or the center.</p><p>`  `If the value is zero then it is tool tip and if it is not zero then it is from center.</p><p>This is in accordance to the selection of option “Output Through” the tip or center of tool for the toolpath. The values will be available only if the variable [**OPR_SUPPORTS_TOOL_TIP_OFFSET**](#chmtopic137) is not zero. To be used in CAMWorks 2018 SP0 or higher versions.    </p>|

## <a name="chmtopic325"></a>**N\_SUB\_STATION**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>- This variable can be used find the next movement tool sub station number.    </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Mill, Lathe and Mill-Turn.</p>|

## <a name="chmtopic420"></a>**NEXT\_IS\_LATHE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores if the next operation is lathe or not. Available in Mill-Turn. Supported in CAMWorks 2009 and later. Not supported in any ProCAM product.</p><p>NEXT\_IS\_LATHE=TRUE or FALSE</p>|

## <a name="chmtopic1833"></a>**NEXT\_KOMBID**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|Stores the CAMWorks assembly mode tool ID information per tool change for the next tool to be output.|

## <a name="chmtopic1835"></a>**NEXT\_MOVE\_KOMBID**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|Stores the CAMWorks assembly mode tool ID information for the next movement.|

## <a name="chmtopic82"></a>**NEXT\_OPR\_BAXIS\_TURNING**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores whether the next operation is a simultaneous X,Z, B axis turning operation or not. The value will be TRUE or FALSE. To be used in CAMWorks 2019 SP1 or newer versions.</p><p>NEXT\_OPR\_BAXIS\_TURNING=TRUE or FALSE</p>|

## <a name="chmtopic322"></a>**NEXT\_OPR\_SUB\_STATION**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>- This variable can be used find the next operation tool sub station number.  </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Mill, Lathe and Mill-Turn.</p>|

## <a name="chmtopic419"></a>**NEXT\_OPR\_SUB\_TYPE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|Stores the next operation drill cycle type. Available in Mill and Mill-Turn. Supported in CAMWorks 2009 and later. Not supported in any ProCAM product.|

## <a name="chmtopic418"></a>**NEXT\_OPR\_TYPE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|Stores the next operation type. Available in Mill, Turn and Mill-Turn. Supported in CAMWorks 2009 and later. Not supported in any ProCAM product.|

## <a name="chmtopic414"></a>**NEXT\_SETUP\_4AX\_ANGLE**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the next 4th axis preposition setup angle. Available in Mill only. Supported in CAMWorks 2009 and later. Not supported in any ProCAM product.|

## <a name="chmtopic415"></a>**NEXT\_SETUP\_5AX\_ANGLE**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the next 5th axis preposition setup angle. Available in Mill only. Supported in CAMWorks 2009 and later. Not supported in any ProCAM product.|

## <a name="chmtopic227"></a>**NEXT\_USER\_TOOL**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|Stores the next tool but does not include any post or sub-spindle operations as you cannot pick a tool, so it gets the next tool after those operations. To be used in CAMWorks 2015 SP2 or newer version.|


## <a name="chmtopic189"></a>**NEXT\_USER\_TURRET**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|Stores the next turret but does not include ant post or sub-spindle operations as you cannot pick a tool, so it gets the next turret after those operations. To be used in CAMWorks 2015 SP2 or newer version.|


## <a name="chmtopic102"></a>**NEXT\_USER\_TURRET\_NUM**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores the next real operations turret number.</p><p>To be used in CAMWorks 2019 SP0 or higher versions.</p>|


## <a name="chmtopic83"></a>**NUM\_OPERATIONS\_FRONT1**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores the total number of operations in any part that are associated with FRONT1 turret. </p><p>To be used in CAMWorks 2019 SP1 or higher versions.</p>|


## <a name="chmtopic84"></a>**NUM\_OPERATIONS\_FRONT2**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores the total number of operations in any part that are associated with FRONT2 turret. </p><p>To be used in CAMWorks 2019 SP1 or higher versions.</p>|


## <a name="chmtopic85"></a>**NUM\_OPERATIONS\_REAR1**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores the total number of operations in any part that are associated with REAR1 turret. </p><p>To be used in CAMWorks 2019 SP1 or higher versions.</p>|


## <a name="chmtopic86"></a>**NUM\_OPERATIONS\_REAR2**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores the total number of operations in any part that are associated with REAR2 turret. </p><p>To be used in CAMWorks 2019 SP1 or higher versions.</p>|




## <a name="chmtopic89"></a>**NUM\_SYNC\_CODES\_FRONT1**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores the total number of sync codes in any part that are associated with FRONT1 turret.  </p><p>To be used in CAMWorks 2019 SP1 or higher versions.</p>|


## <a name="chmtopic90"></a>**NUM\_SYNC\_CODES\_FRONT2**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores the total number of sync codes in any part that are associated with FRONT2 turret.  </p><p>To be used in CAMWorks 2019 SP1 or higher versions.</p>|


## <a name="chmtopic87"></a>**NUM\_SYNC\_CODES\_REAR1**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores the total number of sync codes in any part that are associated with REAR1 turret.  </p><p>To be used in CAMWorks 2019 SP1 or higher versions.</p>|


## <a name="chmtopic88"></a>**NUM\_SYNC\_CODES\_REAR2**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores the total number of sync codes in any part that are associated with REAR2 turret.  </p><p>To be used in CAMWorks 2019 SP1 or higher versions.</p>|


## <a name="chmtopic250"></a>**O\_CYCLE\_START\_X**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Passes the X start point of Turn Canned OD, ID and Face cycle. This value will be used before the canned cycle is output. To be used in CAMWorks 2015 or newer versions.|


## <a name="chmtopic251"></a>**O\_CYCLE\_START\_Z**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Passes the Z start point of Turn Canned OD, ID and Face cycle. This value will be used before the canned cycle is output. To be used in CAMWorks 2015 or newer versions.|


## <a name="chmtopic1856"></a>**OPER\_CURRENT\_SKIM\_CUT**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>This variable stores the EDM operation type. This is used in ProCAM 2D only.</p><p>SKIM\_CUT=CURRENT</p><p>SKIM\_CUT=PREVIOUS</p><p>SKIM\_CUT=NEXT</p><p> </p><p>CURRENT=0</p><p>PREVIOUS=1</p><p>NEXT=2</p>|

## <a name="chmtopic1858"></a>**OPER\_CURRENT\_TAB\_CUT**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>This variable stores the EDM operation type. This is used in ProCAM 2D only.</p><p>TAB\_CUT=CURRENT</p><p>TAB\_CUT=PREVIOUS</p><p>TAB\_CUT=NEXT</p><p> </p><p>CURRENT=0</p><p>PREVIOUS=1</p><p>NEXT=2</p>|

## <a name="chmtopic1860"></a>**OPER\_TOTAL\_SKIM\_CUTS**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|This variable stores the total number of skim cuts in an operation. This is used in ProCAM 2D only.|

## <a name="chmtopic1862"></a>**OPER\_TOTAL\_TAB\_CUTS**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|This variable stores the total number of tab cuts in an operation. This is used in ProCAM 2D only.|

## <a name="chmtopic185"></a>**OPR\_APPROACH\_AUTO\_CORRECT**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores whether user selected Auto Correct or not in the Approach options in Mill-Turn system. To be used in CAMWorks 2016 SP1 or newer version.</p><p> </p><p>OPR\_APPROACH\_AUTO\_CORRECT = TRUE or FALSE</p><p> </p>|


<a name="chmtopic201"></a>\
**OPR\_APPROACH\_STRATEGY**
---------------------------


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>This variables is the current Mill-Turn's Mill operation's approach strategy to the start of the cut. To be used in CAMWorks 2016 or newer version.</p><p> </p><p>OPR\_APPROACH\_STRATEGY = Z\_THEN\_X</p><p>OPR\_APPROACH\_STRATEGY = X\_THEN\_Z</p><p>OPR\_APPROACH\_STRATEGY = DIRECT</p><p>OPR\_APPROACH\_STRATEGY = AUTO</p><p> </p><p>Z\_THEN\_X = 1</p><p>X\_THEN\_Z = 2</p><p>DIRECT = 3</p><p>AUTO = No Value (CAMWorks attempts to maintain the Approach strategy where possible. For approach moves, CAMWorks will attempt to avoid the WIP model by specified Clearance. This option allows you to set the Approach type to automatically avoid collisions with the WIP model.)</p>|


## <a name="chmtopic199"></a>**OPR\_B\_AXIS\_OFFSET**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the B Axis angle for Turn and Mill-Turn turning operations. If post header command ALLOW\_B\_AXIS\_OFFSET\_REAR is not in SRC file or is set to FALSE, then this variable will not be set. To be used in CAMWorks 2016 or newer version.|


## <a name="chmtopic91"></a>**OPR\_BAXIS\_TURNING**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores whether the operation is a simultaneous X,Z, B axis turning operation or not. The value will be TRUE or FALSE. To be used in CAMWorks 2019 SP1 or newer versions.</p><p>OPR\_BAXIS\_TURNING=TRUE or FALSE</p>|

## <a name="chmtopic116"></a>**OPR\_FACET\_DEVIATION**


|Type|DECIMAL|
| :- | :- |
|Usage|Stores the operation's facet deviation. To be used in CAMWorks 2019 SP0 or higher versions.|

#### <a name="chmtopic207"></a>**OPR\_FIRST\_MOVE\_COMP\_DIR**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|Stores the CNC comp direction "Left or Right" before the first rapid move of an operation. To be used in CAMWorks 2014 or newer version.|


## <a name="chmtopic1870"></a>**OPR\_GLUE\_DISTANCE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|Stores the EDM Glue Stop distance amount. If you are using a glue stop, it is set the distance entered in the operation dialog box.|

## <a name="chmtopic1872"></a>**OPR\_GLUE\_STOP**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|Stores the EDM Glue Stop option setting. If you are using a glue stop, it is set to 1 (YES). If not, then it is set to 0 (NO).|

## <a name="chmtopic103"></a>**OPR\_IS\_ARC\_FEEDRATE\_OVERRIDE\_ENABLED**

|Type|INTEGER|
| :- | :- |
|Usage|<p>Indicates and stores information on whether the user has selected *Feedrate Override* in the *Operation Parameters* dialog box. To be used in CAMWorks 2019 SP0 or higher version.</p><p>OPR\_IS\_ARC\_FEEDRATE\_OVERRIDE\_ENABLED=TRUE or FALSE</p>|


## <a name="chmtopic104"></a>**OPR\_IS\_CORNER\_SLOWDOWN\_ENABLED**


|Type|INTEGER|
| :- | :- |
|Usage|<p>Indicates and stores information on whether the user has selected C*orner Slowdown feedrate* in the *Operation Parameters* dialog box. To be used in CAMWorks 2019 SP0 or higher versions.</p><p>OPR\_IS\_CORNER\_SLOWDOWN\_ENABLED=TRUE or FALSE</p>|

## <a name="chmtopic105"></a>**OPR\_IS\_SYS\_CALCULATED\_FEEDRATES\_ENABLED**

|Type|INTEGER|
| :- | :- |
|Usage|<p>Indicates and stores information on whether the user has selected *System Calculated Feedrates* in the *Operation Parameters* dialog box. To be used in CAMWorks 2019 SP0 or higher version.</p><p>OPR\_IS\_SYS\_CALCULATED\_FEEDRATES\_ENABLED=TRUE or FALSE</p>|


## <a name="chmtopic454"></a>**OPR\_LATHE\_APPROACH\_STRATEGY**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>CAMWorks 2007 and later: this variable is the current lathe operation's approach strategy to the start of the cut.</p><p> </p><p>OPR\_LATHE\_APPROACH\_STRATEGY=Z\_THEN\_X</p><p>OPR\_LATHE\_APPROACH\_STRATEGY=X\_THEN\_Z</p><p>OPR\_LATHE\_APPROACH\_STRATEGY=DIRECT</p><p>OPR\_LATHE\_APPROACH\_STRATEGY=AUTO</p><p> </p><p>Z\_THEN\_X=1</p><p>X\_THEN\_Z=2</p><p>DIRECT=3</p><p>AUTO=no value (CAMWorks attempts to maintain the Approach strategy where possible. For approach moves, CAMWorks will attempt to avoid the WIP model by the specified Clearance. This option allows you to set the Approach type to automatically avoid collisions with the WIP model.)</p>|

## <a name="chmtopic455"></a>**OPR\_LATHE\_RETRACT\_STRATEGY**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>CAMWorks 2007 and later: this variable is the current lathe operation's retract strategy at the end of the cut.</p><p> </p><p>OPR\_LATHE\_RETRACT\_STRATEGY=Z\_THEN\_X</p><p>OPR\_LATHE\_RETRACT\_STRATEGY=X\_THEN\_Z</p><p>OPR\_LATHE\_RETRACT\_STRATEGY=DIRECT</p><p>OPR\_LATHE\_RETRACT\_STRATEGY=AUTO</p><p> </p><p>Z\_THEN\_X=1</p><p>X\_THEN\_Z=2</p><p>DIRECT=3</p><p>AUTO=no value (CAMWorks attempts to maintain the Retract strategy where possible. For retract moves, CAMWorks will attempt to avoid the WIP model by the specified Clearance. This option allows you to set the Retract type to automatically avoid collisions with the WIP model.)</p>|

## <a name="chmtopic1879"></a>**OPR\_LATHE\_RETRACT\_TYPE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores the retract type when using Lathe canned cycles:</p><p>(1) Z then X</p><p>(2) X then Z</p><p>(3) Direct</p>|

## <a name="chmtopic1881"></a>**OPR\_LATHE\_TAPPING**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores whether you need to do a lathe tapping cycle while in the lathe drilling operation. This currently only works in ProCAM 2D Lathe.</p><p>OPR\_LATHE\_TAPPING=FALSE</p><p>OPR\_LATHE\_TAPPING=TRUE</p>|

# <a name="chmtopic379"></a>**OPR\_LEADIN\_FEEDRATE**

|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>This variable stores the operation leadin feedrate in milling.  </p><p>Not supported in any ProCAM product or CAMWorks product earlier then version CW2011 SP1.</p><p>Available in Mill and Mill-Turn.</p>|


## <a name="chmtopic106"></a>**OPR\_MACH\_DEVIATION**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|<p>Stores the operations machine deviation. Available in Mill and Mill-Turn posts. To be used in CAMWorks 2019 SP0 or higher versions.</p><p> </p>|


## <a name="chmtopic320"></a>**OPR\_MOVE\_ID**


|**Type**|<p>INTEGER</p><p> </p>|
| :- | :- |
|**Usage**|<p>- This variable can be used find the current, next or previous movement ID number.</p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Mill, Lathe and Mill-Turn.</p>|
|**Options**|<p>N\_OPR\_MOVE\_ID</p><p>P\_OPR\_MOVE\_ID</p>|

## <a name="chmtopic118"></a>**OPR\_PINCH\_TURNING**


|Type|INTEGER|
| :- | :- |
|Usage|Indicates whether the operation is a Simultaneous (Pinch) Turning operation or not. The values will be either TRUE or FALSE. To be used in CAMWorks 2019 SP0 or higher versions.|


## <a name="chmtopic1887"></a>**OPR\_POLAR**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>OPR\_POLAR=TRUE or FALSE</p><p>This command should be set to FALSE if your machine does not support special G-code for doing milling on the OD and or FACE.</p><p>Set this command to TRUE if you have a machine that supports the special G-code for doing milling on the OD and or FACE.</p><p>When you are in a lathe/mill milling operation and on the NC tab, you will have a selection of Rotary Axis Mode either Fixed or Free. If you select Free, you will also get a selection of Polar/Cylindrical interpolation. When you select the Polar/Cylindrical interpolation, this variable will store a value of 1. Otherwise, it is set to zero.</p>|

## <a name="chmtopic186"></a>**OPR\_RETRACT\_AUTO\_CORRECT**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores whether user selected Auto Correct or not in the Retract options in Mill-Turn system. To be used in CAMWorks 2016 SP1 or newer version.</p><p> </p><p>OPR\_RETRACT\_AUTO\_CORRECT = TRUE or FALSE</p><p> </p>|


## <a name="chmtopic202"></a>**OPR\_RETRACT\_STRATEGY**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>This variables is the current Mill-Turn's Mill operation's retract strategy at end of cut. To be used in CAMWorks 2016 or newer version.</p><p> </p><p>OPR\_RETRACT\_STRATEGY = Z\_THEN\_X</p><p>OPR\_RETRACT\_STRATEGY = X\_THEN\_Z</p><p>OPR\_RETRACT\_STRATEGY = DIRECT</p><p>OPR\_RETRACT\_STRATEGY = AUTO</p><p> </p><p>Z\_THEN\_X = 1</p><p>X\_THEN\_Z = 2</p><p>DIRECT = 3</p><p>AUTO = No Value (CAMWorks attempts to maintain the Retract strategy where possible. For retract moves, CAMWorks will attempt to avoid the WIP model by specified Clearance. This option allows you to set the Retract type to automatically avoid collisions with the WIP model.)</p>|


## <a name="chmtopic257"></a>**OPR\_REVERSE\_ARC\_DIR=TRUE or FALSE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|Tells the post in a Mill-Turn or Mill arc move whether the arcs need to be reversed. Affects MILL\_OD, MILL\_FACE arcs on Main and Sub spindles. To be used in CAMWorks 2014 SP2 or newer versions.|


## <a name="chmtopic248"></a>**OPR\_REVERSE\_ARC\_DIR**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|<p>Detects if the Mill operations OD or FACE arcs need to be reversed or not in a Mill-Turn post. To be used in CAMWorks 2014 SP2.0 or newer versions.</p><p> </p><p>OPR\_REVERSE\_ARC\_DIR=0 - No reversal is needed.</p><p>OPR\_REVERSE\_ARC\_DIR=1 - The arc directions should be reversed.</p>|


## <a name="chmtopic321"></a>**OPR\_RPM**




|Type|INTEGER|
| :- | :- |
|Usage|<p>This variable stores the RPM value from a Turn or Mill/turn speed dialog box.</p><p>Not supported in any ProCAM product or CAMWorks product earlier then version CW2013 SP1.</p><p>Available in Turn and Mill/Turn.</p>|

## <a name="chmtopic458"></a>**OPR\_SHIFT\_TYPE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>This variable stores the shift orientation selected in the Lathe finish grooving cycle. This will be the called section at the time of a shift "CALC\_SHIFT\_TOOL\_LATHE". This section will be called for selecting cutter comp direction "CALC\_CUTTER\_COMP\_LATHE".</p><p> </p><p>Supported in CAMWorks 2007 and later. Not supported in any ProCAM product.</p><p> </p><p>SHIFT\_ORIENTATION=0</p><p>SHIFT\_RIGHT=1</p><p>SHIFT\_LEFT=2</p><p>SHIFT\_LEFT\_AND\_RIGHT=3</p><p>SHIFT\_CENTER=4</p><p> </p>|

## <a name="chmtopic117"></a>**OPR\_SPLINE\_DEVIATION**


|Type|DECIMAL|
| :- | :- |
|Usage|Stores the operation's spline deviation. To be used in CAMWorks 2019 SP0 or higher versions.|


## <a name="chmtopic78"></a>**OPR\_START\_APPROACH\_TYPE**


|Type|INTEGER|
| :- | :- |
|Usage|<p>Stores the Turn operations approach type for canned cycles. To be used in CAMWorks 2019 SP1 or higher versions.</p><p>OPR\_START\_APPROACH\_TYPE=AUTO</p><p>Or</p><p>OPR\_START\_APPROACH\_TYPE=FROM\_PREVIOUS\_POS</p><p>Or</p><p>OPR\_START\_APPROACH\_TYPE=FROM\_APPROACH\_POS</p>|


## <a name="chmtopic107"></a>**OPR\_STEPOVER**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|<p>Stores the operations stepover amount. Available in Mill and Mill-Turn posts. To be used in CAMWorks 2019 SP0 or higher versions.</p><p> </p>|


## <a name="chmtopic137"></a>**OPR\_SUPPORTS\_TOOL\_TIP\_OFFSET**


|Type|INTEGER|
| :- | :- |
|Usage|<p>This variable determines if values will be stored in the variables [**TOOL_TIP_OFFSET**](#chmtopic136), [**N_TOOL_TIP_OFFSET**](#chmtopic136) and [**NC_TOOL_TIP_OFFSET**](#chmtopic136) or not.  </p><p>If the value is FALSE, then no value will be stored in these variables. If value is TRUE, then a value will be passed on to these variables. This is in accordance to the selection of the option “Output Through” the tip or center of tool for the toolpath. To be used in CAMWorks 2018 SP0 or higher versions.  </p>|

## <a name="chmtopic150"></a>**OPR\_SUB\_TYPE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|This variable will have a value of “1” or “0” depending on whether the Contour operation is Thread Milling or not. If Thread milling is selected, then the value will be “1” and if not, then the value will be “0”.  To be used in CAMWorks 2017 SP1 or higher versions.|

## <a name="chmtopic466"></a>**OPR\_THREAD\_CHAMFER\_ANG**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|This variable stores the lathe threading cycles chamfer angle from entered angle. Supported in CAMWorks 2007 and later. Not supported in any ProCAM product.|

# <a name="chmtopic380"></a>**OPR\_THREAD\_DEPTH**

|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>This variable stores the thread depth of a canned lathe threading cycle.  </p><p>Not supported in any ProCAM product or CAMWorks product earlier then version CW2011 SP1.</p><p>Available in Mill and Mill-Turn.</p>|


## <a name="chmtopic237"></a>**OPR\_THREAD\_NUM\_STARTS**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>This variable stores the number of a turn thread operations thread starts. To be used in CAMWorks 2015 SP1 or newer versions.</p><p>Available in Mill and Mill-Turn.</p>|


## <a name="chmtopic92"></a>**OPR\_TOOL\_TIP\_CENTER**

|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores whether the user has selected *Tool Nose Center* or *Tool Nose tip* for a Turn operation.   </p><p>To be used in CAMWorks 2019 SP1 and later versions.</p>|


## <a name="chmtopic79"></a>**OPR\_X\_APPROACH\_POS**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores X Approach Position in Turning associated with canned cycles. To be used in CAMWorks 2019 SP1 or higher versions. |

## <a name="chmtopic166"></a>**OPR\_XPLUS\_ONLY**

|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores whether the **X Plus only** checkbox has been checked or not . To be used in CAMWorks 2017 SP0 or newer versions.</p><p>Available in Mill and Mill-Turn.</p><p>OPR\_XPLUS\_ONLY=TRUE or FALSE</p>|

## <a name="chmtopic383"></a>**OPR\_XY\_ALLOWANCE**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|<p>- This variable stores the XY allowance in milling operations.             </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2010 SP2.</p><p>- Available in Mill and Mill-Turn.</p>|

## <a name="chmtopic80"></a>**OPR\_Z\_APPROACH\_POS**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores Z Approach Position in Turning associated with canned cycles. To be used in CAMWorks 2019 SP1 or higher versions. |

## <a name="chmtopic249"></a>**OPR\_Z\_DEPTH**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>Drill: Absolute Z depth.</p><p> </p><p>This is used for Drilling only and not available for Milling.</p>|


## <a name="chmtopic1909"></a>**OPR\_Z\_ROTARY\_RETRACT\_PLANE**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|Stores the CAMWorks assembly mode operation global retract plane in Z axis when you are doing a 4 or 5 axis rotary position move to another plane. The value is also assigned to the last Z value (ABS\_Z\_END) just before you rotate to another plane.|

## <a name="chmtopic93"></a><a name="chmbookmark76"></a>**TLP\_B\_AXIS\_OFFSET**
## **P\_TLP\_B\_AXIS\_OFFSET**

|**Type**|DECIMAL|
| :- | :- |
|**Usage**|<p>Stores the current and previous incremental B axis rotation of a Turn operation that uses simultaneous X,Z and B axis toolpath.</p><p>To be used in CAMWorks 2019 SP1 and later versions.</p>|


## <a name="chmtopic228"></a>**PART\_PULL\_DISTANCE**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the part pull distance if using the Sub-spindle operation as a part pull. To be used in CAMWorks 2015 SP2 or newer version.|


## <a name="chmtopic416"></a>**PART\_STOCK\_DIAM**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the stock diameter from the stock definition. Available in Turn and Mill-Turn. Supported in CAMWorks 2009 and later. Not supported in any ProCAM product.|

## <a name="chmtopic417"></a>**PART\_STOCK\_LENGTH**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the stock length from the stock definition. Available in Turn and Mill-Turn. Supported in CAMWorks 2009 and later. Not supported in any ProCAM product.|

## <a name="chmtopic1915"></a>**PART\_TOTAL\_TAB\_CUTS**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|This variable stores the total number of tab cuts in a part file. This is used in ProCAM 2D only.|

## <a name="chmtopic1917"></a>**PART\_TOTAL\_SKIM\_CUTS**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|This variable stores the total number of skim cuts in a part file. This is used in ProCAM 2D only.|

## <a name="chmtopic203"></a>**POST\_ADV\_ENTRY\_RETRACT**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>This variables holds the same value as the header command [MILL_ADVANCED_ENTRY_RETRACT](#chmtopic208). To be used in CAMWorks 2016 or newer version.</p><p> </p><p>POST\_ADV\_ENTRY\_RETRACT = 0 or FALSE</p><p>POST\_ADV\_ENTRY\_RETRACT = 1 or TRUE</p><p> </p><p>If the header command MILL\_ADVANCED\_ENTRY\_RETRACT is not in the post SRC file then the value of this variable will be 0 or FALSE.</p>|


## <a name="chmtopic331"></a>**POST\_LIBRARY\_SUBVERSION**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>- This variable can be used to find out if when post is compiled what the library sub version is.        </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Mill, Lathe and Mill-Turn.</p>|

## <a name="chmtopic330"></a>**POST\_LIBRARY\_VERSION**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>- This variable can be used to find out if when post is compiled what the library version is.        </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Mill, Lathe and Mill-Turn.</p>|

## <a name="chmtopic1922"></a>**POST\_PATH**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|Stores the posted output path.|

## <a name="chmtopic188"></a>**POST\_RESETS\_CAXIS\_ON\_TOOL\_CHANGE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Sets the posting system in Mill-Turn either reset the INC\_C\_END at each tool change or not. If not defined in post, then default is not to reset the INC\_C\_END. To be used in CAMWorks 2016 SP0 or newer version.</p><p> </p><p>POST\_RESETS\_CAXIS\_ON\_TOOL\_CHANGE = TRUE or FALSE</p><p> </p>|


## <a name="chmtopic389"></a>**PRE\_POSITION\_ROTARY\_TYPE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>This variable can be set to either have the A axis or the B axis as the 4th axis rotary.</p><p>- PRE\_POSITION\_ROTARY\_TYPE = ROTARY\_TYPE\_A or ROTARY\_TYPE\_B.</p><p>- In ProCAM the B axis was setup to be the 4th axis rotary and normal software has the A axis as the 4th axis rotary.</p><p>- Not supported in any ProCAM product or CAMWorks product earlier then version CW2010.</p><p>- Available in Mill.</p>|

## <a name="chmtopic205"></a>**QUERY\_CHAR\_VAL**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|<p>Stores the integer value of the QUERY\_SYSTEM() command. Available in Mill, Turn and Mill-Turn. Supported in CAMWorks 2009 and later verions. Not supported in any ProCAM product.</p><p>QUERY\_CHAR\_VAL will equal ant string information retrieved from the QUERY\_SYSTEM() command.</p>|


## <a name="chmtopic425"></a>**QUERY\_DEC\_VAL**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores the decimal value of the QUERY\_SYSTEM() command. Available in Mill, Turn and Mill-Turn. Supported in CAMWorks 2009 and later. Not supported in any ProCAM product.</p><p>QUERY\_DEC\_VALUE will equal any decimal information retrieved from the QUERY\_SYSTEM() command.</p>|




## <a name="chmtopic423"></a>**QUERY\_ERROR**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores the error value of the QUERY\_SYSTEM() command. Available in Mill, Turn and Mill-Turn. Supported in CAMWorks 2009 and later. Not supported in any ProCAM product.</p><p>QUERY\_ERROR=0 for no error. If greater than zero, then it could be different types of errors currently not returned.</p>|




## <a name="chmtopic424"></a>**QUERY\_INT\_VAL**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores the integer value of the QUERY\_SYSTEM() command. Available in Mill, Turn and Mill-Turn. Supported in CAMWorks 2009 and later. Not supported in any ProCAM product.</p><p>QUERY\_INT\_VALUE will equal any integer information retrieved from the QUERY\_SYSTEM() command.</p>|




## <a name="chmtopic421"></a>**QUERY\_ITEM\_ID**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores the ID of the object you are trying to get information from. Available in Mill, Turn and Mill-Turn. Supported in CAMWorks 2009 and later. Not supported in any ProCAM product.</p><p> </p><p>QUERY\_ITEM\_ID=QUERY\_INT\_X\_SETUP\_DIR</p><p>QUERY\_INT\_X\_SETUP\_DIR holds the object ID of X Axis machining direction in the mill setup Axis tab.</p><p> </p><p>Part Mode:</p><p>QUERY\_INT\_VAL= 1  Angle is selected.</p><p>QUERY\_INT\_VAL= 2  Automatic to stock is selected.</p><p>QUERY\_INT\_VAL= 3  Edge is selected.</p><p>QUERY\_INT\_VAL= 4  Sketch is selected.</p><p> </p><p>Assembly Mode:</p><p>QUERY\_INT\_VAL= 1  Angle is selected.</p><p>QUERY\_INT\_VAL= 2  Automatic to stock is selected.</p><p>QUERY\_INT\_VAL= 3  Edge is selected.</p><p>QUERY\_INT\_VAL= 4  Sketch is selected.</p><p>QUERY\_INT\_VAL= 5  Fixture Coordinate System.</p>|

## <a name="chmtopic422"></a>**QUERY\_RESULT**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores the return value of the QUERY\_SYSTEM() command. Available in Mill, Turn and Mill-Turn. Supported in CAMWorks 2009 and later. Not supported in any ProCAM product.</p><p>QUERY\_RESULT=1 if successful.</p>|

## <a name="chmtopic260"></a>**QUERY\_TLP\_Z\_MAX**

|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Holds the feature Z max. depth associated to the current toolpath when used in conjunction with QUERY\_MILL\_TLP\_Z\_EXTENTS. To be used in CAMWorks 2014 SP3  or later versions.  |


## <a name="chmtopic259"></a>**QUERY\_TLP\_Z\_MIN**

|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Holds the feature Z min. depth associated to the current toolpath when used in conjunction with QUERY\_MILL\_TLP\_Z\_EXTENTS. To be used in CAMWorks 2014 SP3  or later versions.|


## <a name="chmtopic465"></a>**RAPID\_DURING\_DRILL\_CYCLE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>This variable tells the system whether your post supports a rapid move in a drilling cycle via editing the toolpath. This section will be called to check for its value "CALC\_ALLOW\_RAPID\_DURING\_DRILL". If this variable or section is not in the post, then it will assume the post does not support this option.</p><p>Supported in CAMWorks 2007 and later. Not supported in any ProCAM product.</p><p> </p><p>RAPID\_DURING\_DRILL\_CYCLE=TRUE</p><p>RAPID\_DURING\_DRILL\_CYCLE=FALSE</p>|

## <a name="chmtopic393"></a>**REAR\_SYNC\_CODE**


|**Type**|INTEGER||
| :- | :- | :- |
|**Usage**|This variable stores the current and previous rear turret sync code number. Available in Turn and Mill/Turn. These variables are set in CW2010, however the option of syncing turrets is not implemented in CW2010.||
|**Options**|P\_REAR\_SYNC\_CODE| |


## <a name="chmtopic394"></a>**REAR\_SYNC\_CODE\_TYPE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>This variable stores the rear turret sync code type. Available in Turn and Mill/Turn. These variables are set in CW2010, however the option of syncing turrets is not implemented in CW2010.</p><p>REAR\_SYNC\_CODE\_TYPE= SYNC\_CODE\_UNKNOWN</p><p>REAR\_SYNC\_CODE\_TYPE= SYNC\_CODE\_BEFORE\_START</p><p>REAR\_SYNC\_CODE\_TYPE= SYNC\_CODE\_BEFORE\_FIRST\_MOVE</p><p>REAR\_SYNC\_CODE\_TYPE= SYNC\_CODE\_AFTER\_END</p><p> </p><p>SYNC\_CODE\_UNKNOWN = 0</p><p>SYNC\_CODE\_BEFORE\_START = 1</p><p>SYNC\_CODE\_BEFORE\_FIRST\_MOVE = 2</p><p>SYNC\_CODE\_AFTER\_END = 3</p>|

## <a name="chmtopic1937"></a>**RUNNING\_SYSTEM**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>The current running system.</p><p>RUNNING\_SYSTEM=CAMWORKS</p><p>RUNNING\_SYSTEM=PROCAM\_2D</p><p>RUNNING\_SYSTEM=PROCAM\_3D</p><p>CAMWORKS=1</p><p>PROCAM\_2D=2</p><p>PROCAM\_3D=3</p>|

## <a name="chmtopic264"></a>**SETUP\_MACH\_I**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Gives the vector distance in X axis between the rotary and tilt axis that is passed from the KIN file. To be used in CAMWorks 2014 SP3  or later versions.|


## <a name="chmtopic265"></a>**SETUP\_MACH\_J**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Gives the vector distance in Y axis between the rotary and tilt axis that is passed from the KIN file. To be used in CAMWorks 2014 SP3  or later versions.|


## <a name="chmtopic266"></a>**SETUP\_MACH\_K**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Gives the vector distance in Z axis between the rotary and tilt axis that is passed from the KIN file. To be used in CAMWorks 2014 SP3  or later versions.  |


## <a name="chmtopic261"></a>**SETUP\_MACH\_X**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Gives the distance in X axis between the rotary and tilt axis that is passed from the KIN file. To be used in CAMWorks 2014 SP3  or later versions.|


## <a name="chmtopic262"></a>**SETUP\_MACH\_Y**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Gives the distance in Y axis between the rotary and tilt axis that is passed from the KIN file. To be used in CAMWorks 2014 SP3  or later versions.|


## <a name="chmtopic263"></a>**SETUP\_MACH\_Z**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Gives the distance in Z axis between the rotary and tilt axis that is passed from the KIN file. To be used in CAMWorks 2014 SP3  or later versions.|


## <a name="chmtopic412"></a>**SETUP\_ID**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>**P\_SETUP\_ID**</p><p>**SETUP\_ID**</p><p>**N\_SETUP\_ID**</p><p>Stores current, next and previous setup ID number. Available in Mill, Turn and Mill-Turn. Supported in CAMWorks 2009 and later. Not supported in any ProCAM product.</p>|

# <a name="chmtopic376"></a>**SETUP\_MCS\_X\_OFFSET**
# **P\_SETUP\_MCS\_X\_OFFSET**
## **N\_SETUP\_MCS\_X\_OFFSET**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>This variable stores the distance in X from the selected World Coordinate System to the current  mill Setup coordinate system. This is a non rotated value.</p><p>Not supported in any ProCAM product or CAMWorks product earlier then version CW2011 SP1.</p><p>Available in Mill and Mill/Turn.</p>|
|**Options**|<p>N\_SETUP\_MCS\_X\_OFFSET N\_ = next setup</p><p>P\_SETUP\_MCS\_X\_OFFSET P\_ = previous setup</p>|


## <a name="chmtopic377"></a>**SETUP\_MCS\_Y\_OFFSET**
## **P\_SETUP\_MCS\_Y\_OFFSET**
## **N\_SETUP\_MCS\_Y\_OFFSET**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>This variable stores the distance in Y from the selected World Coordinate System to the current  mill Setup coordinate system. This is a non rotated value.</p><p>Not supported in any ProCAM product or CAMWorks product earlier then version CW2011 SP1.</p><p>Available in Mill and Mill-Turn.</p>|
|**Options**|<p>N\_SETUP\_MCS\_Y\_OFFSET N\_ = next setup</p><p>P\_SETUP\_MCS\_Y\_OFFSET P\_ = previous setup</p>|


## <a name="chmtopic378"></a>**SETUP\_MCS\_Z\_OFFSET**
## **P\_SETUP\_MCS\_Z\_OFFSET**
## **N\_SETUP\_MCS\_Z\_OFFSET**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>This variable stores the distance in Z from the selected World Coordinate System to the current  mill Setup coordinate system. This is a non rotated value.</p><p>Not supported in any ProCAM product or CAMWorks product earlier then version CW2011 SP1.</p><p>Available in Mill and Mill-Turn.</p>|
|**Options**|<p>N\_SETUP\_MCS\_Z\_OFFSET N\_ = next setup</p><p>P\_SETUP\_MCS\_Z\_OFFSET P\_ = previous setup</p>|


## <a name="chmtopic313"></a>**SETUP\_REVERSE\_Z\_DIR**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>SETUP\_REVERSE\_Z\_DIR=TRUE or FALSE</p><p>- This variable can be used to find out if user selected reverse Z axis in turn setup.</p><p>- Not supported in any ProCAM product or CAMWorks product earlier then version CAMWorks 2013.</p><p>- Available in Lathe and Mill-Turn.</p>|

## <a name="chmtopic333"></a>**SETUP\_WORLD\_X\_OFFSET**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>- This variable can be used find the current, next or previous X world offset none rotated.               </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Mill</p>|
|**Options**|<p>N\_SETUP\_WORLD\_X\_OFFSET   </p><p>P\_SETUP\_WORLD\_X\_OFFSET</p>|

## <a name="chmtopic334"></a>**SETUP\_WORLD\_Y\_OFFSET**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>- This variable can be used find the current, next or previous Y world offset none rotated.               </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Mill</p>|
|**Options**|<p>N\_SETUP\_WORLD\_Y\_OFFSET   </p><p>P\_SETUP\_WORLD\_Y\_OFFSET</p>|

## <a name="chmtopic335"></a>**SETUP\_WORLD\_Z\_OFFSET**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>- This variable can be used find the current, next or previous Z world offset none rotated.               </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Mill.</p>|
|**Options**|<p>N\_SETUP\_WORLD\_Z\_OFFSET   </p><p>P\_SETUP\_WORLD\_Z\_OFFSET</p>|

## <a name="chmtopic1953"></a>**SHAPE\_DIAMETER**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|Stores the diameter of a laser or plasma toolpath if SHAPE\_TYPE is set to CIRCLE\_SHAPE.|

## <a name="chmtopic1955"></a>**SHAPE\_INSIDE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|Stores a 0 or 1 and is used if the laser or plasma tool path is closed. If it stores a 0, then the tool path is to the outside of the geometry if it stores a 1, then the toolpath is to the inside of the geometry.|

## <a name="chmtopic1957"></a>**SHAPE\_TYPE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>This variable stores a 0, 1 or 2 and is used for checking the type of laser or plasma tool path. If it stores a 0, then the tool path is open. If it stores a 1, then the tool path is closed. If it stores a 2, then it is a full circle toolpath.</p><p>The system constants that are associated are:</p><p>OPEN\_SHAPE=0</p><p>CLOSED\_SHAPE=1</p><p>CIRCLE\_SHAPE=2</p>|

## <a name="chmtopic1959"></a>**SKIM\_CUT**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>This variable stores the EDM operation type. This is used in ProCAM 2D only.</p><p>SKIM\_CUT=CURRENT</p><p>SKIM\_CUT=PREVIOUS</p><p>SKIM\_CUT=NEXT</p><p> </p><p>CURRENT=0</p><p>PREVIOUS=1</p><p>NEXT=2</p>|

## <a name="chmtopic267"></a>**SOLIDWORKS\_FILENAME**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|Stores the SOLIDWORKS file name - only 100 characters max. will be stored. To be used in CAMWorks 2014 SP3  or later versions.   |


## <a name="chmtopic340"></a>**SPINDLE\_I**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|<p>- This variable can be used to find the spindle I vector in a Sub Spindle Operation when a Reference Point step is inserted.                  </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than CAMWorks 2013 Version.</p><p>- Available in Turn (Lathe) and Mill-Turn.</p>|

## <a name="chmtopic341"></a>**SPINDLE\_J**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|<p>- This variable can be used to find the spindle J vector in a Sub Spindle Operation when a Reference Point step is inserted.                  </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than CAMWorks 2013 Version.</p><p>- Available in Turn (Lathe) and Mill-Turn.</p>|

## <a name="chmtopic342"></a>**SPINDLE\_K**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|<p>- This variable can be used to find the spindle K vector in a Sub Spindle Operation when a Reference Point step is inserted.                  </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than CAMWorks 2013 Version.</p><p>- Available in Turn (Lathe) and Mill-Turn.</p>|

## <a name="chmtopic143"></a>**SPLINE\_DEVIATION**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|This variable stores the Spline Deviation from the Operation Parameters dialog box. To be used in CAMWorks 2017 SP2 or higher versions.|

## <a name="chmtopic317"></a>**SPINDLE\_ORIENTATION**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|<p>SPINDLE\_ORIENTATION=Amount entered in spindle operation.               </p><p>- This variable can be used in a sub spindle operation to set the spindle orientation before a transfer.</p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Lathe and Mill-Turn.</p>|

## <a name="chmtopic315"></a>**SPINDLE\_STATE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>SPINDLE\_STATE=OFF</p><p>SPINDLE\_STATE=ON</p><p>SPINDLE\_STATE=LOCK</p><p>OFF=0</p><p>ON=1</p><p>LOCK=2</p><p>- This variable can be used in a sub spindle operation to see if the spindle is on,off or locked.</p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Lathe and Mill-Turn.</p>|

## <a name="chmtopic316"></a>**SPINDLE\_SYNC\_TYPE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>SPINDLE\_SYNC\_TYPE= SYNC**\_**SPEED</p><p>SPINDLE\_SYNC\_TYPE= SYNC**\_**PHASE</p><p>SYNC**\_**SPEED=0</p><p>SYNC**\_**PHASE=1</p><p>- This variable can be used in a sub spindle operation to see if the spindle is used for speed or phase.</p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Lathe and Mill-Turn.</p>|

## <a name="chmtopic388"></a>**STOCK\_HEIGHT**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|<p>- This variable stores the stock height in milling. Customer must create a Fixture Coordinate System in order to get value.             </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2010 SP1.</p><p>- Available in Mill and Mill-Turn.</p>|

## <a name="chmtopic386"></a>**STOCK\_LENGTH**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|<p>- This variable stores the stock length in milling. Customer must create a Fixture Coordinate System in order to get value.                     </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2010 SP1.</p><p>- Available in Mill and Mill-Turn.</p>|

## <a name="chmtopic239"></a>**STOCK\_MAX\_X**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the Stock Maximum value in X axis. To be used in CAMWorks 2015 SP0 or newer version.|


## <a name="chmtopic240"></a>**STOCK\_MAX\_Y**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the Stock Maximum value in Y axis. To be used in CAMWorks 2015 SP0 or newer version.|


## <a name="chmtopic241"></a>**STOCK\_MAX\_Z**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the Stock Maximum value in Z axis. To be used in CAMWorks 2015 SP0 or newer version.|


## <a name="chmtopic242"></a>**STOCK\_MIN\_X**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the Stock Minimum value in X axis. To be used in CAMWorks 2015 SP0 or newer version.|


## <a name="chmtopic243"></a>**STOCK\_MIN\_Y**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the Stock Minimum value in Y axis. To be used in CAMWorks 2015 SP0 or newer version.|


## <a name="chmtopic244"></a>**STOCK\_MIN\_Z**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the Stock Minimum value in Z axis. To be used in CAMWorks 2015 SP0 or newer version.|


## <a name="chmtopic387"></a>**STOCK\_WIDTH**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|<p>- This variable stores the stock width in milling. Customer must create a Fixture Coordinate System in order to get value.                 </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2010 SP1.</p><p>- Available in Mill and Mill-Turn.</p>|

## <a name="chmtopic323"></a>**SUB\_STATION**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>- This variable can be used find the current tool sub station number.  </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Mill, Lathe and Mill-Turn.</p>|

## <a name="chmtopic336"></a>**SUB\_STATION\_ID**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|<p>- This variable can be used to find the current tool sub station description.                </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Mill, Lathe and Mill-Turn.</p>|

## <a name="chmtopic392"></a>**SYNC\_CODE\_COMMENT**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|This variable stores the sync code comment. Available in Turn and Mill/Turn. These variables are set in CW2010, however the option of syncing turrets is not implemented in CW2010.|

## <a name="chmtopic108"></a>**SYNCED\_WITH\_FRONT1**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Indicates whether Front1 turret has been synced to another turret. The value will be either “0” or “1”.</p><p>To be used in CAMWorks 2019 SP0 or higher versions.  </p>|


## <a name="chmtopic109"></a>**SYNCED\_WITH\_FRONT2**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Indicates whether Front2 turret has been synced to another turret. The value will be either “0” or “1”.</p><p>To be used in CAMWorks 2019 SP0 or higher versions.  </p>|


## <a name="chmtopic110"></a>**SYNCED\_WITH\_REAR1**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Indicates whether Rear1 turret has been synced to another turret. The value will be either “0” or “1”.</p><p>To be used in CAMWorks 2019 SP0 or higher versions.  </p>|


## <a name="chmtopic111"></a>**SYNCED\_WITH\_REAR2**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Indicates whether Rear2 turret has been synced to another turret. The value will be either “0” or “1”.</p><p>To be used in CAMWorks 2019 SP0 or higher versions.  </p>|


## <a name="chmtopic1985"></a>**TAB\_CUT**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>This variable stores the EDM operation type. This is used in ProCAM 2D only.</p><p>TAB\_CUT=CURRENT</p><p>TAB\_CUT=PREVIOUS</p><p>TAB\_CUT=NEXT</p>|

## <a name="chmtopic258"></a>**TLP\_2AX\_FEAT\_DEPTH**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Holds the feature machining depth associated to the current 2 Axis toolpath. To be used in CAMWorks 2014 SP3  or later versions.|


## <a name="chmtopic319"></a>**TLP\_FEATURE\_ID**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>- This variable can be used find the current, next or previous movement feature ID number.</p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Mill, Lathe and Mill-Turn.</p><p>- **Options:** N\_TLP\_FEATURE\_ID     and    P\_TLP\_FEATURE\_ID</p>|

## <a name="chmtopic409"></a>**TLP\_FEAT\_DESC**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|Stores the toolpath feature description. In the APT CL output, keywords and associated values are output for each of the node names. Available in Mill, Turn and Mill-Turn. Supported in CAMWorks 2009 and later. Not supported in any ProCAM product.|

## <a name="chmtopic408"></a>**TLP\_FEAT\_NAME**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|Stores the toolpath feature name. In the APT CL output, keywords and associated values are output for each of the node names. Available in Mill, Turn and Mill-Turn. Supported in CAMWorks 2009 and later. Not supported in any ProCAM product.|

## <a name="chmtopic390"></a>**TLP\_FEAT\_SETUP\_DESC**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|<p>- This variable stores the setup description for the current toolpath feature.              </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2010.</p><p>- Available in Mill, Turn and Mill-Turn.</p>|

## <a name="chmtopic391"></a>**TLP\_FEAT\_SETUP\_NAME**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|Stores the setup name for the current toolpath feature. Available in Mill, Turn and Mill-Turn. Supported in CAMWorks 2010 and later. Not supported in any ProCAM product.|

## <a name="chmtopic411"></a>**TLP\_OPER\_DESC**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|Stores the toolpath operation description. In the APT CL output, keywords and associated values are output for each of the node names. Available in Mill, Turn and Mill-Turn. Supported in CAMWorks 2009 and later. Not supported in any ProCAM product.|

## <a name="chmtopic410"></a>**TLP\_OPER\_NAME**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|Stores the toolpath operation name. In the APT CL output, keywords and associated values are output for each of the node names. Available in Mill, Turn and Mill-Turn. Supported in CAMWorks 2009 and later. Not supported in any ProCAM product.|

## <a name="chmtopic405"></a>**TLP\_PART\_DESC**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|Stores the toolpath part description. In the APT CL output, keywords and associated values are output for each of the node names. Available in Mill, Turn and Mill-Turn. Supported in CAMWorks 2009 and later. Not supported in any ProCAM product.|

## <a name="chmtopic404"></a>**TLP\_PART\_NAME**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|Stores the toolpath part name. In the APT CL output, keywords and associated values are output for each of the node names. Available in Mill, Turn and Mill-Turn. Supported in CAMWorks 2009 and later. Not supported in any ProCAM product.|

## <a name="chmtopic407"></a>**TLP\_SETUP\_DESCRIPTION**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|Stores the toolpath setup description. In the APT CL output, keywords and associated values are output for each of the node names. Available in Mill, Turn and Mill-Turn. Supported in CAMWorks 2009 and later. Not supported in any ProCAM product.|

## <a name="chmtopic406"></a>**TLP\_SETUP\_NAME**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|Stores the toolpath setup name. In the APT CL output, keywords and associated values are output for each of the node names. Available in Mill, Turn and Mill-Turn. Supported in CAMWorks 2009 and later. Not supported in any ProCAM product.|

## <a name="chmtopic384"></a>**TOOL\_ANGLE**
## **N\_TOOL\_ANGLE**
## **NC\_TOOL\_ANGLE**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|<p>- This variable stores the taper angle of a tapered mill tool and the drill angle of a drill tool.          </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2010 SP1.</p><p>- Available in Mill and Mill-Turn.</p>|

## <a name="chmtopic206"></a>**TOOL\_FLUTE\_LENGTH**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the Flute Length of any Mill Tool from the Tool Definition tab. To be used in CAMWorks 2016 or newer version.|


## <a name="chmtopic229"></a>**TOOL\_INCLUDED\_ANGLE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|Stores the Thread inserts included angle on a Turn Threading operation. To be used in CAMWorks 2013 or newer version.|


## <a name="chmtopic457"></a>**TOOL\_ORIENT**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>CAMWorks 2007 and later: this variable stores the current lathe tool orientation.</p><p> </p><p>TOOL\_ORIENT=UP\_RIGHT</p><p>TOOL\_ORIENT=UP\_LEFT</p><p>TOOL\_ORIENT=DOWN\_RIGHT</p><p>TOOL\_ORIENT=DOWN\_LEFT</p><p>TOOL\_ORIENT=LEFT\_UP</p><p>TOOL\_ORIENT=LEFT\_DOWN</p><p>TOOL\_ORIENT=RIGHT\_UP</p><p>TOOL\_ORIENT=RIGHT\_DOWN</p><p> </p><p>UP\_RIGHT=1</p><p>UP\_LEFT=2</p><p>DOWN\_RIGHT=3</p><p>DOWN\_LEFT=4</p><p>LEFT\_UP=5</p><p>LEFT\_DOWN=6</p><p>RIGHT\_UP=7</p><p>RIGHT\_DOWN=8</p>|

## <a name="chmtopic385"></a><a name="chmbookmark77"></a>**TOOL\_PROTRUSION**
## **N\_TOOL\_PROTRUSION**
## **NC\_TOOL\_PROTRUSION**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|<p>- This variable stores the tool protrusion from the bottom of the tool holder to the end of a mill tool or a drill tool.           </p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2010 SP1.</p><p>- Available in Mill and Mill-Turn.</p>|




## <a name="chmtopic112"></a>**TOOL\_SHANK\_DIAMETER**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|<p>Stores the tool shank diameter. Available in Mill and Mill-Turn posts. To be used in CAMWorks 2019 SP0 or higher versions.</p><p> </p>|


## <a name="chmtopic2005"></a>**TOOL\_SPEC\_NAME**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|This variable stores the special tool name for the current tool station. There will be a name for each station that uses a special tool. This variable can also be used in the GETTOOLS(???) command. This works only in ProCAM 2D Punch.|

## <a name="chmtopic2007"></a>**TOOL\_SPEC\_PATH**


|**Type**|CHARACTER|
| :- | :- |
|**Usage**|This variable stores the special tool path for the current tool station. There will be a path for each station that uses a special tool. This variable can also be used in the GETTOOLS(???) command. This works only in ProCAM 2D Punch.|

## <a name="chmtopic181"></a>**TOOL\_SPINDLE\_USAGE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>Stores to which spindle a tool is associated with in Turn or Mill-Turn post. To be used in CAMWorks 2016 SP2 or newer version.</p><p> </p><p>TOOL\_SPINDLE\_USAGE = MAIN\_SPINDLE      or</p><p>SUB\_SPINDLE         or</p><p>BOTH\_SPINDLES    or</p><p>NONE</p>|


## <a name="chmtopic338"></a>**TOOL\_X\_GAGE\_OFFSET**
## **TOOL\_Y\_GAGE\_OFFSET**
## **TOOL\_Z\_GAGE\_OFFSET**




|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>- This variable can be used to find the current tool X,Y and Z gage offset.</p><p>- Not supported in any ProCAM product or CAMWorks product earlier than version CAMWorks 2013.</p><p>- Available in Mill, Lathe and Mill-Turn.</p>|

## <a name="chmtopic413"></a>**TOOLPATH\_ID**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>**P\_TOOLPATH\_ID**</p><p>**TOOLPATH\_ID**</p><p>**N\_TOOLPATH\_ID**</p><p>Stores current, next and previous toolpath ID number. Available in Mill, Turn and Mill-Turn. Supported in CAMWorks 2009 and later. Not supported in any ProCAM product.</p>|

## <a name="chmtopic460"></a>**TOUCHOFF\_POINT\_TYPE**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>**P\_TOUCHOFF\_POINT\_TYPE**</p><p>**TOUCHOFF\_POINT\_TYPE**</p><p>**N\_TOUCHOFF\_POINT\_TYPE**</p><p>This variable stores the current touch off point of a finish grooving cycle tool during posting. This is the current active edge when you are in a called section "CALC\_SHIFT\_TOOL\_LATHE".</p><p> </p><p>Supported in CAMWorks 2007 and later. Not supported in any ProCAM product.</p><p> </p><p>PROG\_POINT\_CENTER=0</p><p>PROG\_POINT \_PRIMARY=1</p><p>PROG\_POINT \_SECONDARY=2</p>|

## <a name="chmtopic2013"></a>**TRANSFER\_DISTANCE**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|This variable stores the distance traveled when a transfer takes place between the lathe main and sub spindle along the Z axis. Supported only in CAMWorks.|

## <a name="chmtopic114"></a>**TURN\_PART\_DIAMETER**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|<p>Stores the Turn part diameter. Available in Turn and Mill-Turn posts. To be used in CAMWorks 2019 SP0 or higher versions.</p><p> </p>|


## <a name="chmtopic113"></a>**TURN\_PART\_LENGTH**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|<p>Stores the Turn part length. Available in Turn and Mill-Turn posts. To be used in CAMWorks 2019 SP0 or higher versions.</p><p> </p>|


## <a name="chmtopic245"></a>**USE\_FEATURE\_OD\_ID**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>·        Setting this variable to = "1" will set the post system variables OD and ID to be the correct value in Rough Turn Canned Cycle.</p><p>·        This variable can be set in a Turn or Mill-Turn post at either CALC\_START\_OF\_TAPE in your post library file or CALC\_INIT\_CODES in the SRC file.</p><p>·        To be used in CAMWorks 2015 SP0 or newer version.</p>|


## <a name="chmtopic183"></a>**USE\_NON\_ROTATED\_WCS\_FOR\_VM**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|<p>This is to be used with a post for Virtual Machine that uses G68 plane rotation commands.</p><p>When TRUE, the Work Coordinates passed to Virtual Machine will be in World coordinates.</p><p>When FALSE, the Work Coordinates are computed in the default machine plane after all axis rotations occur.</p><p>To be used in CAMWorks 2016 SP2 or newer version.</p>|


## <a name="chmtopic140"></a>**USE\_MULTIAXIS\_MAX\_MOVE\_DISTANCE**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|This variable will either be set to TRUE or FALSE depending on whether the **Max move distance** checkbox option in the Finish tab of the Operation Parameters dialog box for a multiaxis operation was checked or not. If the checkbox option is checked then, MULTIAXIS\_MAX\_MOVE\_DISTANCE will be set to TRUE. If unchecked then, MULTIAXIS\_MAX\_MOVE\_DISTANCE will be set to FALSE. To be used in CAMWorks 2017 SP3 or higher versions.|

## <a name="chmtopic216"></a>**WORK\_PLANE\_X\_VEC\_X**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the X work plane vector along the X Axis. To be used in CAMWorks 2015 SP2 or newer version.|


## <a name="chmtopic217"></a>**WORK\_PLANE\_X\_VEC\_Y**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the X work plane vector along the Y Axis. To be used in CAMWorks 2015 SP2 or newer version.|


## <a name="chmtopic218"></a>**WORK\_PLANE\_X\_VEC\_Z**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the X work plane vector along the Z Axis. To be used in CAMWorks 2015 SP2 or newer version.|


## <a name="chmtopic219"></a>**WORK\_PLANE\_Y\_VEC\_X**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the Y work plane vector along the X Axis. To be used in CAMWorks 2015 SP2 or newer version.|


## <a name="chmtopic220"></a>**WORK\_PLANE\_Y\_VEC\_Y**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the Y work plane vector along the Y Axis. To be used in CAMWorks 2015 SP2 or newer version.|


## <a name="chmtopic221"></a>**WORK\_PLANE\_Y\_VEC\_Z**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the Y work plane vector along the Z Axis. To be used in CAMWorks 2015 SP2 or newer version.|


## <a name="chmtopic222"></a>**WORK\_PLANE\_Z\_VEC\_X**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the Z work plane vector along the X Axis. To be used in CAMWorks 2015 SP2 or newer version.|


## <a name="chmtopic223"></a>**WORK\_PLANE\_Z\_VEC\_Y**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the Z work plane vector along the Y Axis. To be used in CAMWorks 2015 SP2 or newer version.|


## <a name="chmtopic224"></a>**WORK\_PLANE\_Z\_VEC\_Z**


|**Type**|DECIMAL|
| :- | :- |
|**Usage**|Stores the Z work plane vector along the Z Axis. To be used in CAMWorks 2015 SP2 or newer version.|


# <a name="chmtopic370"></a>**WORLD\_FCS\_TO\_SETUP\_X**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>This variable stores the distance in X from the selected World Coordinate System to the current  mill Setup. This is a non rotated value.</p><p>Not supported in any ProCAM product or CAMWorks product earlier then version CW2011 SP1.</p><p>Available in Mill and Mill-Turn.</p>|


# <a name="chmtopic371"></a>**WORLD\_FCS\_TO\_SETUP\_Y**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>This variable stores the distance in Y from the selected World Coordinate System to the current  mill Setup. This is a non rotated value.</p><p>Not supported in any ProCAM product or CAMWorks product earlier then version CW2011 SP1.</p><p>Available in Mill and Mill-Turn.</p>|


# <a name="chmtopic372"></a>**WORLD\_FCS\_TO\_SETUP\_Z**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>This variable stores the distance in Z from the selected World Coordinate System to the current  mill Setup. This is a non rotated value.</p><p>Not supported in any ProCAM product or CAMWorks product earlier then version CW2011 SP1.</p><p>Available in Mill and Mill/Turn.</p>|


# <a name="chmtopic373"></a>**WORLD\_VECTOR\_X**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>This variable stores the X signed vector from the selected World Coordinate System to the current  mill Setup. This is a non rotated value.</p><p>Not supported in any ProCAM product or CAMWorks product earlier then version CW2011 SP1.</p><p>Available in Mill and Mill/Turn.</p>|


# <a name="chmtopic374"></a>**WORLD\_VECTOR\_Y**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>This variable stores the Y signed vector from the selected World Coordinate System to the current  mill Setup. This is a non rotated value.</p><p>Not supported in any ProCAM product or CAMWorks product earlier then version CW2011 SP1.</p><p>Available in Mill and Mill/Turn.</p>|


# <a name="chmtopic375"></a>**WORLD\_VECTOR\_Z**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|<p>This variable stores the Z signed vector from the selected World Coordinate System to the current  mill Setup. This is a non rotated value.</p><p>Not supported in any ProCAM product or CAMWorks product earlier then version CW2011 SP1.</p><p>Available in Mill and Mill/Turn.</p>|


## <a name="chmtopic2035"></a>**IC**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|Stores the vector of "I" in a line movement in a CAMWorks 3 Axis cutting operation if the post has the :VECTOR\_COMP header set to TRUE.|

## <a name="chmtopic2037"></a>**JC**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|Stores the vector of "J" in a line movement in a CAMWorks 3 Axis cutting operation if the post has the :VECTOR\_COMP header set to TRUE.|

## <a name="chmtopic2039"></a>**KC**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|Stores the vector of "K" in a line movement in a CAMWorks 3 Axis cutting operation if the post has the :VECTOR\_COMP header set to TRUE.|

## <a name="chmtopic2041"></a>**XC**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|Stores the X end point of a line movement in a CAMWorks 3 Axis cutting operation if the post has the :VECTOR\_COMP header set to TRUE.|

## <a name="chmtopic2043"></a>**YC**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|Stores the Y end point of a line movement in a CAMWorks 3 Axis cutting operation if the post has the :VECTOR\_COMP header set to TRUE.|

## <a name="chmtopic2045"></a>**ZC**


|**Type**|METRIC DECIMAL|
| :- | :- |
|**Usage**|Stores the Z end point of a line movement in a CAMWorks 3 Axis cutting operation if the post has the :VECTOR\_COMP header set to TRUE.|

## <a name="chmtopic2047"></a>**V\_COMP**


|**Type**|INTEGER|
| :- | :- |
|**Usage**|Stores a 0 or 1 depending on whether the post has a header command :VECTOR\_COMP set to TRUE and you are in CAMWorks 3 Axis cutting operations. It will store a 1 if you are in an Advanced cutting operation, if not then the value is 0.|

## <a name="chmtopic2049"></a>**ABS\_B\_END**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|<p>Stores the B axis in an absolute end angle from zero position. It stores the 5th preposition (B axis) value in any true B axis operation along with any OD and Face operation. This variable will be available in CAMWorks 2017 and higher versions. Available in Mill-Turn system.</p><p>Options:</p><p>N\_ABS\_B\_END N\_ = next move</p><p>P\_ABS\_B\_END P\_ = previous move</p>|

## <a name="chmtopic2051"></a>**ABS\_B\_START**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|<p>Stores the B axis in an absolute start angle from zero position. It stores the 5th preposition (B axis) value in any true B axis operation along with any OD and Face operation. This variable will be available in CAMWorks 2017 and higher versions. Available in Mill-Turn system.</p><p>Options:</p><p>N\_ABS\_B\_START N\_ = next move</p><p>P\_ABS\_B\_START P\_ = previous move</p>|

## <a name="chmtopic2053"></a>**INC\_B\_END**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|<p>Stores the B axis in an incremental angle from last position. It stores the 5th preposition (B axis) value in any true B axis operation along with any OD and Face operation. This variable will be available in CAMWorks 2017 and higher versions. Available in Mill-Turn system.</p><p>Options:</p><p>N\_INC\_B\_END N\_ = next move</p><p>P\_INC\_B\_END P\_ = previous move</p>|

## <a name="chmtopic2055"></a>**OPR\_B\_AXIS**


|*Type*|METRIC DECIMAL|
| :- | :- |
|*Usage*|Stores the B axis in an absolute angle from defined setup parameters. This variable can only be used in CAMWorks 2005 or later versions for lathe/mill (live c) combination machines.|

## <a name="chmtopic2057"></a>**LASER\_DBPATH**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|Laser or Plasma: Stores the system database path. Is used with the OPENDB command. It stores either the Metric database path or the English database path depending on the current system selected when posting.|

## <a name="chmtopic2059"></a>**ENGLISH\_LASERDB**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|Laser or Plasma: Stores the system database path. Is used with the OPENDB command. It stores the English database path.|

## <a name="chmtopic2061"></a>**METRIC\_LASERDB**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|Laser or Plasma: Stores the system database path. Is used with the OPENDB command. It stores the Metric database path.|

## <a name="chmtopic2063"></a>**LASER\_MATERIAL**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|Stores the material name from the setup information and updates the material name in the laser, plasma database, so it matches.|

## <a name="chmtopic2065"></a>**LASER\_THICKNESS**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|Stores the sheet thickness from the setup information and updates the sheet thickness in the laser, plasma database, so it matches.|

## <a name="chmtopic2067"></a>**LD\_ASSIST\_GAS**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Laser or Plasma: When using the standard database, this variable stores the assist gas type.</p><p>(1) Oxygen</p><p>(2) Nitrogen</p><p>(3) Carbon Dioxide</p><p>(4) n/a</p><p>The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.</p>|

## <a name="chmtopic2069"></a>**LD\_2ND\_ASSIST\_GAS**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|<p>Laser or Plasma: When using the standard database, this variable stores the second assist gas type.</p><p>(1) Oxygen</p><p>(2) Nitrogen</p><p>(3) Carbon Dioxide</p><p>(4) n/a</p><p>The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE</p>|

## <a name="chmtopic2071"></a>**LD\_AUTOBREAK\_IN\_LENGTH**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores what the Auto break distance into the cut is. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2073"></a>**LD\_AUTOBREAK\_OUT\_LENGTH**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores what the Auto break distance out of the cut is. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2075"></a>**LD\_CC\_MODE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Laser or Plasma: When using the standard database, this variable stores what the Cutting condition mode is:</p><p>(1) Area</p><p>(2) Line Length/Arc Radius</p><p>The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.</p>|

## <a name="chmtopic2077"></a>**LD\_CHOICE\_START\_POSITION**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores the user's choice start position. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2079"></a>**LD\_COLOR**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Laser or Plasma: When using the standard database, this variable stores the color of the different path sizes and shapes.</p><p>(1) BLACK</p><p>(2) BLUE</p><p>(3) GREEN</p><p>(4) CYAN</p><p>(5) RED</p><p>(6) MAGENTA</p><p>(7) BROWN</p><p>(8) GRAY</p><p>(9) WHITE</p><p>(10)LTBLUE</p><p>(11)LTGREEN</p><p>(12)LTCYAN</p><p>(13)LTRED</p><p>(14)LTMAGEN</p><p>(15)YELLOW</p><p>(16)HIWHITE</p><p>The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE</p>|

## <a name="chmtopic2081"></a>**LD\_COMMENT**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores the comment. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2083"></a>**LD\_COOLANT\_MODE**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|<p>Laser or Plasma: When using the standard database, this variable stores the coolant type used.</p><p>(1) On</p><p>(2) Off</p><p>(3) n/a</p><p>The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.</p>|

## <a name="chmtopic2085"></a>**LD\_DATA\_GROUP**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|<p>Laser or Plasma: When using the standard database, this variable stores the Data Group. These are the different data groups:</p><p>General</p><p>Pierce Conditions</p><p>Area size 1 Cut Conditions</p><p>Area size 2 Cut Conditions</p><p>Area size 3 Cut Conditions</p><p>Area size 4 Cut Conditions</p><p>Area size 5 Cut Conditions</p><p>Line Length 1 Cut Conditions</p><p>Line Length 2 Cut Conditions</p><p>Line Length 3 Cut Conditions</p><p>Line Length 4 Cut Conditions</p><p>Line Length 5 Cut Conditions</p><p>Arc Radius 1 Cut Conditions</p><p>Arc Radius 2 Cut Conditions</p><p>Arc Radius 3 Cut Conditions</p><p>Arc Radius 4 Cut Conditions</p><p>Arc Radius 5 Cut Conditions</p><p>External Boundary Parameters</p><p>Internal Boundary Parameters</p><p>Hole size 1 Parameters</p><p>Hole size 2 Parameters</p><p>Hole size 3 Parameters</p><p>Hole size 4 Parameters</p><p>Hole size 5 Parameters</p><p>Hole size 1 cut Conditions</p><p>Hole size 2 cut Conditions</p><p>Hole size 3cut Conditions</p><p>Hole size 4 cut Conditions</p><p>Hole size 5 cut Conditions</p><p>Microjoints</p><p>The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE</p>|

## <a name="chmtopic2087"></a>**LD\_DIRECTION**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Laser or Plasma: When using the standard database, this variable stores what the Cutting direction is:</p><p>(1) Clockwise</p><p>(2) Counter Clockwise</p><p>(3) Original</p><p>(4) n/a</p><p>The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.</p>|

## <a name="chmtopic2089"></a>**LD\_DURATION**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores the duration amount. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2091"></a>**LD\_DUTY\_CYCLE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores the laser duty cycle. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2093"></a>**LD\_END\_AT\_HOLE\_CENTER**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Laser or Plasma: When using the standard database, this variable stores whether you are ending at hole center or not:</p><p>(1) On</p><p>(2) Off</p><p>(3) n/a</p><p>The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.</p>|

## <a name="chmtopic2095"></a>**LD\_FEEDRATE**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores the federate used. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2097"></a>**LD\_FEEDRATE\_PERCENT**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores the federate percentage used. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2099"></a>**LD\_FREQUENCY**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores the laser frequency. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2101"></a>**LD\_GAS\_PRESSURE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores the gas pressure used. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2103"></a>**LD\_2ND\_GAS\_PRESSURE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores the second gas pressure used. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2105"></a>**LD\_GO\_AROUND\_DISTANCE**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores what the Go around distance is. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2107"></a>**LD\_LASER\_MODE**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|<p>Laser or Plasma: When using the standard database, this variable stores the laser mode type.</p><p>(3)Continuous Wave</p><p>(4)Dynamic Power</p><p>(1)Gated Pulse</p><p>(5) n/a</p><p>(2) Super Power</p><p>The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.</p>|

## <a name="chmtopic2109"></a>**LD\_LEADIN\_MODE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Laser or Plasma: When using the standard database, this variable stores what type of leadin is used:</p><p>(1) Arc</p><p>(2) n/a</p><p>(3) None</p><p>(4) Parallel</p><p>(5) Perpendicular</p><p>The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.</p>|

## <a name="chmtopic2111"></a>**LD\_LEADIN\_ARC\_ANGLE**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores what the leadin arc angle is. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2113"></a>**LD\_LEADIN\_LENGTH**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores what the leadin distance is. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2115"></a>**LD\_LEADIN\_ARC\_RADIUS**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores what the leadin arc radius is. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2117"></a>**LD\_LEADIN\_ANGLE**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores what the leadin angle is. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2119"></a>**LD\_LEADOUT\_MODE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Laser or Plasma: When using the standard database, this variable stores what type of leadout is used:</p><p>(1) Clockwise</p><p>(2) Counter Clockwise</p><p>(3) Original</p><p>(4) None</p><p>The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.</p>|

## <a name="chmtopic2121"></a>**LD\_LEADOUT\_OVERLAP**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores what the leadout overlap is. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2123"></a>**LD\_LEADOUT\_LENGTH**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores what the leadout distance is. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2125"></a>**LD\_LEADOUT\_ARC\_ANGLE**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores what the leadin arc angle is. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2127"></a>**LD\_LEADOUT\_ARC\_RADIUS**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores what the leadout arc radius is. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2129"></a>**LD\_LEADOUT\_ANGLE**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores what the leadout angle is. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2131"></a>**LD\_LIFTHEAD**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Laser or Plasma: When using the standard database, this variable stores whether you need the Lift Head option or not:</p><p>(1) On</p><p>(2) Off</p><p>(3) n/a</p><p>The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.</p>|

## <a name="chmtopic2133"></a>**LD\_MATERIAL**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores what Material type is being used. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2135"></a>**LD\_METRIC**


|*Type*|CHARACTER|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores what units the database is using. Either English or Metric. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2137"></a>**LD\_OFFSET\_VALUE**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores the offset value used. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2139"></a>**LD\_OPTION\_START\_POSITION**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores the optional start position. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2141"></a>**LD\_OVERLAP**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores what the leadin overlap is. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2143"></a>**LD\_PART\_CLEARANCE**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores what the Part clearance is. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2145"></a>**LD\_POWER\_LEVEL**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores the size of the Area, Line Length, Arc Radius and Holes. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2147"></a>**LD\_SENSOR\_RADIUS**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores what the Sensor radius is. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2149"></a>**LD\_SIZE**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores the size of the Area, Line Length, Arc Radius and Holes. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2151"></a>**LD\_START\_AT\_HOLE\_CENTER**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Laser or Plasma: When using the standard database, this variable stores if you want to start at hole center or not:</p><p>(1) On</p><p>(2) Off</p><p>(3) n/a</p><p>The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.</p>|

## <a name="chmtopic2153"></a>**LD\_START\_AT\_MICROJOINT**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Laser or Plasma: When using the standard database, this variable stores whether you are using microjoints:</p><p>(1) On</p><p>(2) Off</p><p>(3) n/a</p><p>The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.</p>|

## <a name="chmtopic2155"></a>**LD\_START\_POSITION**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Laser or Plasma: When using the standard database, this variable stores what the where cutting is to start from:</p><p>(1) Auto</p><p>(2) Long edge midpoint</p><p>(3) n/a</p><p>The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.</p>|

## <a name="chmtopic2157"></a>**LD\_SUBROUTINE\_NUMBER**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores the subroutine number used. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2159"></a>**LD\_SYSTEM\_COMP**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|<p>Laser or Plasma: When using the standard database, this variable stores what the System comp is:</p><p>(3) for n/a</p><p>(2) for Off</p><p>(1) for On</p><p>The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.</p>|

## <a name="chmtopic2161"></a>**LD\_THICKNESS**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores what the Material thickness is. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2163"></a>**LD\_USER\_DBL01 through LD\_USER\_DBL10**


|*Type*|DECIMAL|
| :- | :- |
|*Usage*|When using the Plasma or Laser standard database this variable stores the expansion decimal fields. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2165"></a>**LD\_USER\_INT01 through LD\_USER\_INT10**


|*Type*|INTEGER|
| :- | :- |
|*Usage*|Laser or Plasma: When using the standard database, this variable stores the expansion integer fields. The file used for English is FABDBENGLISH.MDB and for Metric FABDBMETRIC.MDB. These files are in the \procad\defaults folder. The post header command called LASER\_PLASMA\_CUT\_DATA must be set to TRUE.|

## <a name="chmtopic2167"></a>**System Symbolic Constants**


|**Name**|**Value**|
| :-: | :-: |
|ABSOLUTE|1|
|ANGLE\_INFEED|1|
|ARCS|0|
|BACK\_BORING|12|
|BORE\_DWELL|11|
|BORING|5|
|BOTH|0|
|CAM\_REV2011|110|
|CAM\_REV2011\_SP1|111|
|CAM\_REV2011\_SP2|112|
|CAM\_REV2012|120|
|CAM\_REV2012\_SP1|121|
|CAM\_REV2012\_SP2|122|
|CAM\_REV2012\_PLUS|125|
|CAM\_REV2013|130|
|CAM\_REV2013\_SP1|131|
|CAM\_REV2013\_SP2|132|
|CAM\_REV2013\_SP3|133|
|CAM\_REV2014|140|
|CCW|2|
|CCW\_ARC|3|
|CENTER|0|
|CENTER\_LEFT|2|
|CENTER\_RIGHT|3|
|CFIXED|2|
|CFREE|1|
|CHAMFER\_CORNER|2009|
|CLEARANCE\_PLANE|1|
|CONIC\_CORNER|1011|
|CONSTANT|1|
|CONSTANT\_CUT|1|
|CONSTANT\_DEPTH|0|
|CROSS|4|
|CURRENT|0|
|CW|1|
|CW\_ARC|2|
|DIST\_ALONG|2|
|DOUBLED|8|
|DRILLING|1|
|EDM|EDM|
|EDM4AXIS|1|
|END\_EDGE|1|
|ENGLISH|1|
|EQUAL\_CORNER|1010|
|F|0|
|FACING|1|
|FALSE|0|
|FANUC\_CORNERS|4|
|FINE\_BORING|13|
|FLAT|1|
|FLAT\_BOTTOM|1|
|FORM|5|
|FPM|2|
|FPR|1|
|FRONT|1|
|FULL\_CIRCLE|360|
|HALF\_CIRCLE|180|
|HAVE\_SYNC\_CODE\_ERROR|1|
|HEELED|2|
|HIGH\_SPEED\_PECKING|6|
|HOME|2|
|HORIZONTAL|1|
|INCREMENTAL|2|
|INDEPENDENT\_CORNER|2010|
|JIG|JIG|
|LASER|LASER|
|LATHE|LATHE|
|LEFT|1|
|LINE|1|
|LOCK|2|
|LOUVER|4|
|MACHINE|2|
|MARC|ARC|
|MARKING|6|
|MCCW\_ARC|ARC|
|MCIRCLE|CIRCLE|
|MCW\_ARC|ARC | ARC\_DIR|
|METRIC|2|
|MGRID|0x10|
|MILL|MILL|
|MILL\_FACE|512|
|MILL\_OD|256|
|MLINE|LINE|
|MPOINT|POINT|
|MTEXT|0x10|
|MULTIPLE|2|
|MULTIPLE\_RETRACT|0|
|NEXT|2|
|NO|0|
|NONE|0|
|OBROUND|5|
|OFF|0|
|OFFSET\_LEFT|0|
|OFFSET\_RIGHT|1|
|ON|1|
|OPSETUP\_AXIS\_ANGLE|1|
|OPSETUP\_AXIS\_ASM\_FCS|5|
|OPSETUP\_AXIS\_EDGE|3|
|OPSETUP\_AXIS\_SKETCH|4|
|OPSETUP\_AXIS\_WORKPIECE\_AUTOMATIC|2|
|PECKING|3|
|PERCENTAGE|2|
|PLASMA|PLASMA|
|PREVIOUS|1|
|PROFILE|1|
|PUNCH|PUNCH|
|RADIAL|1|
|RAPID|4|
|RAPID\_PLANE|2|
|REAMING|9|
|REAMING\_DWELL|10|
|REAR|2|
|RECRAD|7|
|RECTANGLE|2|
|REVERSE\_TAPPING|8|
|RIGHT|2|
|ROUND|1|
|ROUND\_CORNERS|0|
|RPM|2|
|SFPM|1|
|SHARP\_CORNER|1009|
|SHARP\_CORNERS|1|
|SHEAR\_PROOF|3|
|SIDE\_EDGE|0|
|SINGLE|1|
|SINGLE\_DEPTH|0|
|SINGLE\_HIT|5|
|SINGLE\_RETRACT|1|
|SINGLED|9|
|SPETOOL|10|
|SPOT\_DRILLING|2|
|SQUARE|6|
|SQUARE\_CORNERS|2|
|STRAIGHT\_INFEED|0|
|SYNC\_CODE\_AFTER\_END|3|
|SYNC\_CODE\_BEFORE\_FIRST\_MOVE|2|
|SYNC\_CODE\_BEFORE\_START|1|
|SYNC\_PHASE|1|
|SYNC\_SPEED|0|
|SYNC\_CODE\_UNKNOWN|0|
|SYSTEM|1|
|T|1|
|TABCUT|2|
|TAPER|2|
|TAPPING|4|
|TIP|0|
|TRIANGLE|3|
|TRIANGLE\_CORNERS|3|
|TRUE|1|
|TURNING|0|
|VARIABLE\_PECKING|7|
|VERTICAL|0|
|WASINO|WASINO|
|X\_AXIS|7|
|XZPOS|1|
|Y\_AXIS|8|
|YES|1|
|Z\_AXIS|6|
|Z\_DEPTH|1|
|Z\_EXTRUDE|3|
|Z\_WALL|2|
|ZERO|0|

## <a name="chmtopic126"></a>**Mill Operation Symbolic Constants**


|***Name***|***Value***|
| :- | :- |
|MILL\_CURVE\_CUT|1010|
|MILL\_DRILLING|1001|
|MILL\_LACE|1003|
|MILL\_MACRO|1007|
|MILL\_MISC|1005|
|MILL\_POCKET|1004|
|MILL\_PROFILING|1002|
|MILL\_ROUGH\_CUT|1009|
|MILL\_SLICE\_CUT|1008|
|MILL\_SPECIAL|1006|
|MILL\_UV\_CUT|1020|
|MILL\_FEATURE\_SUB\_TYPE\_BLIND|0|
|MILL\_FEATURE\_SUB\_TYPE\_THROUGH|1|
|MILL\_FEATURE\_SUB\_TYPE\_DOUBLE\_BLIND|2|
|MILL\_FEATURE\_SUB\_TYPE\_UNKNOWN|3|
|MILL\_FEATURE\_SUB\_TYPE\_DRILLED|4|
|MILL\_PROCESS\_TOOLPATH\_BY\_NONE|0|
|MILL\_PROCESS\_TOOLPATH\_BY\_TOOL|1|
|MILL\_PROCESS\_TOOLPATH\_BY\_FEATURE|2|
|MILL\_PROCESS\_TOOLPATH\_BY\_PART|3|
|<a name="chmbookmark7"></a>SURFACE\_X\_TOOLPATH|1|
|<a name="chmbookmark8"></a>SURFACE\_Y\_TOOLPATH|2|
|<a name="chmbookmark9"></a>SURFACE\_Z\_TOOLPATH|3|
|<a name="chmbookmark10"></a>WEB\_X\_TOOLPATH|4|
|<a name="chmbookmark11"></a>WEB\_Y\_TOOLPATH|5|
|<a name="chmbookmark12"></a>POCKET\_X\_TOOLPATH|6|
|<a name="chmbookmark13"></a>POCKET\_Y\_TOOLPATH|7|
|<a name="chmbookmark14"></a>POCKET\_WITH\_ISLAND\_X\_TOOLPATH|8|
|<a name="chmbookmark15"></a>POCKET\_WITH\_ISLAND\_Y\_TOOLPATH|9|
|<a name="chmbookmark16"></a>BOSS\_TOOLPATH|10|
|<a name="chmbookmark17"></a>BORE\_TOOLPATH|11|
|<a name="chmbookmark18"></a>BORE\_WITH\_ISLAND\_TOOLPATH|12|
|<a name="chmbookmark19"></a>THREE\_POINT\_BOSS\_TOOLPATH|13|
|<a name="chmbookmark20"></a>THREE\_POINT\_BORE\_TOOLPATH|14|
|<a name="chmbookmark21"></a>THREE\_POINT\_BORE\_WITH\_ISLAND\_TOOLPATH|15|
|<a name="chmbookmark22"></a>FIXTURE|1|
|<a name="chmbookmark23"></a>UPDATE\_WORK\_OFFSETS\_CYCLE|1|
|<a name="chmbookmark24"></a>WORK\_COORDINATE|2|
|<a name="chmbookmark25"></a>WORK\_AND\_SUB\_COORDINATE|3|
|<a name="chmbookmark26"></a>MILL\_PROBING|1060|
|<a name="chmbookmark27"></a>ROTATE\_ABOUT\_X|1|
|<a name="chmbookmark28"></a>ROTATE\_ABOUT\_Y|2|
|<a name="chmbookmark29"></a>ROTATE\_ABOUT\_Z|3|
|<a name="chmbookmark30"></a>ROTATE\_ABOUT\_MULTIPLE|0|

## <a name="chmtopic2170"></a>**Drill Operation Symbolic Constants**


|*Name*|*Value*|
| :- | :- |
|BACK\_BORING|2012|
|BORE\_DWELL|2011|
|BORING|2005|
|DRILLING|2001|
|FINE\_BORING|2013|
|HIGH\_SPEED\_PECKING|2006|
|PECKING|2003|
|REAMING|2009|
|REAMING\_DWELL|2010|
|REVERSE\_TAPPING|2008|
|SPOT\_DRILLING|2002|
|TAPPING|2004|
|VARIABLE\_PECKING|2007|

## <a name="chmtopic2172"></a>**Lathe Operation Symbolic Constants**


|*Name*|*Value*|
| :- | :- |
|LATHE\_DRILLING|1011|
|LATHE\_GROOVING|1014|
|LATHE\_MISC|1016|
|LATHE\_PROFILING|1012|
|LATHE\_ROUGHING|1013|
|LATHE\_SPECIAL|1017|
|LATHE\_THREADING|1015|

## <a name="chmtopic184"></a>**Additional System Constants**


|**Name**|**Value**|
| :- | :- |
|**OPEN SHAPE**|0|
|**CLOSED SHAPE**|1|
|**CIRCLE SHAPE**|2|
|**DROP**|1|
|**TILT**|1|
|**MAIN\_SPINDLE**|1|
|**SUB\_SPINDLE**|2|
|**CAMWORKS**|1|
|**PROCAM\_2D**|2|
|**PROCAM\_3D**|3|
|**OPSETUP\_AXIS\_ANGLE**|1|
|**OPSETUP\_AXIS\_WORKPIECE\_AUTOMATIC**|2|
|**OPSETUP\_AXIS\_EDGE**|3|
|**OPSETUP\_AXIS\_SKETCH**|4|
|**OPSETUP\_AXIS\_ASM\_FCS**|5|
|**SIDE\_EDGE**|0|
|**END\_EDGE**|1|
|**HAVE\_SYNC\_CODE\_ERROR**|1|
|**SYNC\_CODE\_UNKNOWN**|0|
|**SYNC\_CODE\_BEFORE\_START**|1|
|**SYNC\_CODE\_BEFORE\_FIRST\_MOVE**|2|
|**SYNC\_CODE\_AFTER\_END**|3|
|**LOCK**|2|
|**SYNC\_SPEED**|0|
|**SYNC\_PHASE**|1|
|**MILL\_ROUGH\_TYPE\_SPIRALIN**|0|
|**MILL\_ROUGH\_TYPE\_SPIRALOUT**|1|
|**MILL\_ROUGH\_TYPE\_ZIG**|2|
|**MILL\_ROUGH\_TYPE\_ZIGZAG**|3|
|**MILL\_ROUGH\_TYPE\_TRUESPIRALIN**|4|
|**MILL\_ROUGH\_TYPE\_TRUESPIRALOUT**|5|
|**MILL\_ROUGH\_TYPE\_PLUNGEROUGH**|6|
|**MILL\_ROUGH\_TYPE\_POCKETIN\_COR**|7|
|**MILL\_ROUGH\_TYPE\_VOLUMILL**|8|
|**MILL\_ROUGH\_TYPE\_ADAPTIVE**|19|
|**CAM\_REV2011**|110|
|**CAM\_REV2011\_SP1**|111|
|**CAM\_REV2011\_SP2**|112|
|**CAM\_REV2012**|120|
|**CAM\_REV2012\_SP1**|121|
|**CAM\_REV2012\_SP2**|122|
|**CAM\_REV2012\_PLUS**|125|
|**CAM\_REV2013**|130|
|**CAM\_REV2013\_SP1**|131|
|**CAM\_REV2013\_SP2**|132|
|**CAM\_REV2013\_SP3**|133|
|**CAM\_REV2014**|140|
|**CAM\_REV2014\_SP0.1**|141|
|**CAM\_REV2014\_SP1**|142|
|**UNLOCK**|3|
|**ENGAGE\_MILL\_MODE**|4|
|**DISENGAGE\_MILL\_MODE**|5|
|**SYNC\_OFF**|2|
|**SYNC\_MILL\_CAXIS**|3|
|**SYNC\_MILL\_OFF**|4|
|**CAM\_REV2014\_SP2**|143|
|**CAM\_REV2014\_SP3**|144|
|**CAM\_REV2015**|150|
|**CAM\_REV2015\_SP1**|151|
|**CAM\_REV2015\_SP2**|152|
|**AS\_DEFINED**|0|
|**TLP\_SAFE\_Z**|1|
|**TLP\_START\_Z**|2|
|**CAM\_REV2015\_SP1.2**|152|
|**CAM\_REV2015\_SP2**|153|
|**CAM\_REV2016**|160|
|**RT\_NONE**|0|
|**RT\_BOTH**|4|
|**RT\_XZ\_SAFE\_INDEX**|1|
|**RT\_XZ\_ABSOLUTE\_PRESET**|2|
|**GUN\_DRILLING**|14|
|**MILL\_COOLANT\_ON**|0|
|**MILL\_COOLANT\_OFF**|1|
|**MILL\_COOLANT\_FLOOD**|2|
|**MILL\_COOLANT\_MIST**|3|
|**MILL\_COOLANT\_THROUGH\_TOOL**|4|
|**MILL\_COOLANT\_AIR\_BLAST**|5|
|**MILL\_COOLANT\_HIGH\_PRESSURE**|6|
|**MILL\_COOLANT\_SPECIAL1**|7|
|**MILL\_COOLANT\_SPECIAL2**|8|
|**LATHE\_COOLANT\_FLOOD**|1|
|**LATHE\_COOLANT\_OFF**|2|
|**LATHE\_COOLANT\_MIST**|3|
|**LATHE\_COOLANT\_THROUGH\_TOOL**|4|
|**LATHE\_COOLANT\_AIR\_BLAST**|5|
|**LATHE\_COOLANT\_HIGH\_PRESSURE**|6|
|**LATHE\_COOLANT\_SPECIAL1**|7|
|**LATHE\_COOLANT\_SPECIAL2**|8|
|**FEEDBACK**|1|
|**PILOT\_DEPTH**|2|
|**CAM\_REV2016\_SP1**|161|
|**CAM\_REV2016\_SP2**|162|
|**BOTH\_SPINDLES**|3|
|<a name="chmbookmark40"></a>**MX\_REWIND\_RETRACT\_MOVE**|7|
|**MX\_REWIND\_MOVE**|8|
|**MX\_REWIND\_APPROACH\_MOVE**|9|
|**X\_ONLY**|4|
|**Z\_ONLY**|5|
|**CAM\_REV2017**|170|
|**CAM\_REV2017\_SP3**|173|
|**THREAD\_MILLING**|1|
|**ENTRY\_TYPE\_NONE**| |
|**ENTRY\_TYPE\_PLUNGE**| |
|**ENTRY\_TYPE\_DRILL**| |
|**ENTRY\_TYPE\_RAMP**| |
|**ENTRY\_TYPE\_HOLE**| |
|**ENTRY\_TYPE\_SPIRAL**| |
|**ENTRY\_TYPE\_RAMP\_ON\_LEADIN**| |
|**CAM\_REV2018\_SP4**|184|
|**CAM\_REV2018\_SP5**|185|
|**CAM\_REV2019**|190|
|**CAM\_REV2019\_SP1**|191|
|<a name="chmbookmark36"></a>**FRONT1**|1|
|<a name="chmbookmark38"></a>**REAR1**|2|
|<a name="chmbookmark39"></a>**REAR2**|3|
|<a name="chmbookmark37"></a>**FRONT2**|4|
|<a name="chmbookmark34"></a>**CAM\_REV2019\_SP2**| |
|<a name="chmbookmark32"></a>**FROM\_PREVIOUS\_POS**|1|
|<a name="chmbookmark33"></a>**FROM\_APPROACH\_POS**|2|
|<a name="chmbookmark31"></a>**CAM\_REV2020**|200|
|<a name="chmbookmark1"></a>**CAM\_REV2020\_SP3**|203|

# <a name="chmtopic67"></a>**System Constants for SOLIDWORKS** 


|**Name**|**Value**|
| :- | :- |
|SW\_INFO\_TITLE|0|
|SW\_INFO\_SUBJECT|1|
|SW\_INFO\_AUTHOR|2|
|SW\_INFO\_KEYWORDS|3|
|SW\_INFO\_COMMENTS|4|
|SW\_INFO\_SAVED\_BY|5|
|SW\_INFO\_CREATION\_DATE|6|
|SW\_INFO\_SAVED\_DATE|7|
|SW\_UNKNOWN|0|
|SW\_NUMBER|3|
|SW\_DOUBLE|5|
|SW\_YES\_NO|11|
|SW\_TEXT|30|
|SW\_DATE|64|




## <a name="chmtopic2176"></a>**Programming Examples: Mill Example 1**
### **Adding an Operation Question and Using its Value to Change the Output**
1. If you want to save the previous example, then copy the source files (master.atr, class.src and class.lib) to a save folder and recopy the original files back into the class folder.
1. Add an attribute to (master.atr) called "changing pallets". This attribute will be a select type as described below. You will place it after ID number 17502

\*-----------------------------------

:ATTRNAME=shots to be fired

:ATTRTYPE=VALUE

:ATTRVTYPE=DECIMAL

:ATTRID=17501

:ATTREND

**\*-------**

**:ATTRNAME=changing pallets** **ß------------ Attrname**

**:ATTRTYPE=SELECT**

**:ATTRID=17502** **ß------------------------- New ID number**

**:ATTREND**



3. Change the IDHIGH=17502 at the start of the (master.atr) file.

   Note: If you use an ID number that is lower than 17501, then you would not have to do this step.

4. Open (class.src) and add the new attrname you created in master.atr to all the operation lists as shown below. Since this question will be asked in the operation list, then the value is valid for that operation only. Make sure you add the line to all the :OPERID= (Operations). If you add it to just the Drilling one in the example below, then the drilling operation is the only operation that will get the question asked.

\*----------------------------------------------------------

\* Operation List Questions

\*----------------------------------------------------------

:OPERID=MILL\_DRILLING

:OPERSUB=DRILLING

:OPERLIST=abs inc

:OPERLIST=work coord

:OPERLIST=coolant

:OPERLIST=changing pallets ß------ Add this line to all ":OPERID=" lists

:OPEREND

5. Go to the template section :SECTION=INIT\_TOOL\_CHANGE\_MILL in (class.src) and add the line below.

   Since this will only happen at every tool change, you need to change the init tool change section and the subtool change sections.

\*

**:SECTION=INIT\_TOOL\_CHANGE\_MILL**

:T:<N><TOOL\_COMMENT><EOL>

:T:<N><T><M:06><EOL>

:T:<N><S!><M!:SPINDLE\_DIR><EOL>

:T:<N><G!:work\_coord><EOL>

**:T:<N><P\_CHANGE><EOL>** **ß----------------------Add this line**

:T:<N><M!:COOLANT\_TYPE><EOL>

\*

**:SECTION=SUB\_TOOL\_CHANGE\_MILL**

:T:<N><G:00><G:91><G:28> Z0<EOL>

:T:<N><TOOL\_COMMENT><EOL>

:T:<N><T><M:06><EOL>

:T:<N><S!><M!:SPINDLE\_DIR><EOL>

:T:<N><G!:work\_coord><EOL>

**:T:<N><P\_CHANGE><EOL>** **ß----------------------Add this line**

:T:<N><M!:COOLANT\_TYPE><EOL>

6. Open (class.lib) file and add the new attribute "changing pallets" you created in (master.atr). Even though you defined it in (master.atr), you still need to define it in the library file. See below for position.

` `\*------------------------------ ß-------- Add these lines

` `:ATTRNAME=changing pallets

` `:ATTRTYPE=SELECT

` `:ATTREMARK=Changing Pallets

` `:ATTRSEL=N

` `:ATTRTITLE=Changing Pallets

` `:ATTRSELSTR=No

` `:ATTRSELSTR=Left

` `:ATTRSELSTR=Right

` `:ATTRDEFAULT=1

` `:ATTRUSED=1

` `:ATTREND ß--------------------------------------- To here

` `\*------------------------------

` `:ATTRNAME=material type

` `:ATTRTYPE=SELECT

` `:ATTREMARK=Material type

` `:ATTRSEL=N

` `:ATTRTITLE=Material Type

` `:ATTRSELSTR=Rolled Steel

` `:ATTRSELSTR=Aluminum

` `:ATTRSELSTR=Stainless Steel

` `:ATTRDEFAULT=1

` `:ATTRUSED=1

` `:ATTREND

7. Add the attribute listed below at the end of (class.lib) file.

   Notice that the attrername P CHANGE is a select type attribute. What ever the value of P CHANGE equals is the select value. If the value of P CHANGE is not 2 or 3, then there is no output. In the lower case attribute "changing pallets" the :ATTRSELSTR= are No, Left or Right. The value of "changing pallets" equals one (1) if you pick the first one in the list, etc. So if you select "No" in the operation question, then the value of "changing pallets" equals one (1) and you will not get any output from P\_CHANGE.

` `\*-----------------------------------

` `:ATTRNAME=CURRENT MACRO NAME

` `:ATTRTYPE=POST

` `:ATTREMARK=

` `:CODETYPE=FORMAT

` `:WORD\_ADDRESS\_BEF=|(

` `:VAR=CURRENT MACRO NAME

` `:WORD\_ADDRESS\_AFT=)

` `:LEFT\_PLACES=0

` `:RIGHT\_PLACES=0

` `:UNITFLAG=NON\_CONVERT

` `:ATTRSPACES=YES

` `\*:MODAL=YES

` `:ATTRUSED=1

` `:ATTREND

` `**\*------------------------** **ß--- Add these lines**

` `**:ATTRNAME=P CHANGE**

` `**:ATTRTYPE=POST**

` `**:ATTRVTYPE=INTEGER**

` `**:ATTREMARK=Pallet Change**

` `**:CODETYPE=SELECT**

` `**:SELECT=2**

` `**:CODE=M51**

` `**:SELECT=3**

` `**:CODE=M52**

` `**:ATTREND** **ß------------------- To here**

8. Now you need to add some logic to handle the output. You need to have this happen at every tool change, so you have to change the calc sections :SECTION=CALC\_INIT\_TOOL\_CHANGE\_MILL and :SECTION=CALC\_SUB\_TOOL\_CHANGE\_MILL. Since both of these sections are not in (class.lib), you have to copy them from (general.lib) to the end of (class.lib). See below for position.

\*-----------------------------------

**:SECTION=CALC\_INIT\_TOOL\_CHANGE\_MILL**

:C: IF SECTIONEXIST(DEBUG) THEN

:C: DEBUG=4 CALL(DEBUG)

:C: ENDIF

\*

\*:C: IF OPER\_COUNT>1 THEN CALL(CALC\_SUB\_TOOL\_CHANGE\_MILL) RETURN ENDIF

:C: IF MACH(REG\_T2)<>0 THEN CALL(CALC\_SUB\_TOOL\_CHANGE\_MILL) RETURN ENDIF

\*

\* If you are defining a macro then you stop here!

\*

:C: P\_MOVE\_TYPE=TOOL\_CHANGE

:C: IF DEFINING\_MACRO=(YES) THEN CALL(CALC\_CHECK\_OPER\_COMMENTS) RETURN ENDIF

:C: IF MACH(REG\_T)<>0 AND MACH(REG\_T)=TOOL THEN RETURN ENDIF

:C: CALC\_CHANGE\_TOOL=1

:C: TOOL\_ARRAY(ARRAY\_COUNT)=NC\_TOOL

:C: TOOL\_DIAM\_ARRAY(ARRAY\_COUNT)=NC\_TOOL\_DIAMETER

:C: IF NC\_TOOL=(-1) THEN TOOL\_DIAM\_ARRAY(ARRAY\_COUNT)=TOOL\_DIAM\_ARRAY(0) ENDIF

:C: NEXT\_TOOL=TOOL\_ARRAY(ARRAY\_COUNT)

:C: POT\_NUMBER=10

:C: IF TOOL\_DIAMETER>LARGE\_POT THEN POT\_NUMBER=90 ENDIF

:C: NEXT\_POT\_NUMBER=10

:C: IF TOOL\_DIAM\_ARRAY(ARRAY\_COUNT)>LARGE\_POT THEN NEXT\_POT\_NUMBER=90 ENDIF

:C: ARRAY\_COUNT=(ARRAY\_COUNT+1)

:C: IF SECTIONEXIST(OUTPUT\_ESTIMATED\_TIME) THEN

:C: CALL(CALC\_TOOL\_CHANGE\_TIME)

:C: ENDIF

:C: IF TOOL\_COMMENT={} THEN

:C: SETOFF(<TOOL\_COMMENT>) ELSE

:C: SETON(<TOOL\_COMMENT>)

:C: ENDIF

**:C: P\_CHANGE=changing\_pallets** **ß----------- Add this line**

:C: IF SECTIONEXIST(INIT\_PRELOAD\_TOOL\_CHANGE\_MILL) THEN

:C: CALL(CALC\_INIT\_PRELOAD\_TOOL\_CHANGE)

:C: CALL(CALC\_CHECK\_OPER\_COMMENTS)

:C: MACH(REG\_T)=TOOL

:C: FIRST\_TOOL=TOOL

:C: LAST\_TOOL=TOOL

:C: RETURN

:C: ENDIF

:C: IF SECTIONEXIST(INIT\_TOOL\_CHANGE\_MILL) THEN

:C: CALL(INIT\_TOOL\_CHANGE\_MILL)

:C: ENDIF

:C: CALL(CALC\_CHECK\_OPER\_COMMENTS)

:C: MACH(REG\_T)=TOOL

:C: FIRST\_TOOL=TOOL

:C: LAST\_TOOL=TOOL

\*



:SECTION=CALC\_SUB\_TOOL\_CHANGE\_MILL

:C: IF SECTIONEXIST(DEBUG) THEN

:C: DEBUG=5 CALL(DEBUG)

:C: ENDIF

\*

\* Startup Seton Codes

\*

:C: CALL(CALC\_BEF\_SETON\_CODES)

:C: G=GC(G\_LEN\_COMP) SETON(<G>)

:C: M=MC(M\_COOL\_OFF) SETON(<M>)

\*

\* If you are defining a macro then you stop here!

\*

:C: P\_MOVE\_TYPE=TOOL\_CHANGE

:C: IF DEFINING\_MACRO=(YES) THEN CALL(CALC\_CHECK\_OPER\_COMMENTS) RETURN ENDIF

:C: IF MACH(REG\_T)<>0 AND MACH(REG\_T)=TOOL THEN RETURN ENDIF

:C: CALC\_CHANGE\_TOOL=(CALC\_CHANGE\_TOOL+1)

:C: IF OFFSET\_RESIDENT=YES THEN CALL(CALC\_REMOVE\_OFFSET) ENDIF

:C: IF TOOL=NC\_TOOL THEN NC\_TOOL=(-1) ENDIF

:C: TOOL\_ARRAY(ARRAY\_COUNT)=NC\_TOOL

:C: TOOL\_DIAM\_ARRAY(ARRAY\_COUNT)=NC\_TOOL\_DIAMETER

:C: IF NC\_TOOL=(-1) THEN TOOL\_DIAM\_ARRAY(ARRAY\_COUNT)=TOOL\_DIAM\_ARRAY(0) ENDIF

:C: NEXT\_TOOL=TOOL\_ARRAY(ARRAY\_COUNT)

:C: POT\_NUMBER=10

:C: IF TOOL\_DIAMETER>LARGE\_POT THEN POT\_NUMBER=90 ENDIF

:C: NEXT\_POT\_NUMBER=10

:C: IF TOOL\_DIAM\_ARRAY(ARRAY\_COUNT)>LARGE\_POT THEN NEXT\_POT\_NUMBER=90 ENDIF

:C: ARRAY\_COUNT=(ARRAY\_COUNT+1)

:C: CALL(CALC\_TOOL\_CHANGE\_TIME)

:C: IF TOOL\_COMMENT={} THEN

:C: SETOFF(<TOOL\_COMMENT>) ELSE

:C: SETON(<TOOL\_COMMENT>)

:C: ENDIF

**:C: P\_CHANGE=changing\_pallets** **ß----------- Add this line**

:C: IF SECTIONEXIST(SUB\_PRELOAD\_TOOL\_CHANGE\_MILL) THEN

:C: CALL(CALC\_SUB\_PRELOAD\_TOOL\_CHANGE)

:C: CALL(CALC\_CHECK\_OPER\_COMMENTS)

:C: CALL(CALC\_AFT\_SETON\_CODES)

:C: MACH(REG\_T)=TOOL

:C: LAST\_TOOL=TOOL

:C: MACH(REG\_Z)=MILL\_Z\_HOME

:C: RETURN

:C: ENDIF

:C: IF SECTIONEXIST(SUB\_TOOL\_CHANGE\_MILL) THEN

:C: CALL(SUB\_TOOL\_CHANGE\_MILL)

:C: ENDIF

:C: CALL(CALC\_CHECK\_OPER\_COMMENTS)

:C: CALL(CALC\_AFT\_SETON\_CODES)

:C: MACH(REG\_T)=TOOL

:C: LAST\_TOOL=TOOL

:C: MACH(REG\_Z)=MILL\_Z\_HOME

9. Assuming you put master.atr in the same folder as your source, you can save all the files you edited and exit your editor.

   To compile you will need to type this at your **DOS** prompt –

   **WINMAKE CLASS.SRC MASTER.ATR [Drive]:\PROCAD\CTL**.

   If you have installed the UPG, then you can compile the source in the UPG by selecting the File menu and picking "Compile Post."
## <a name="chmtopic2178"></a>**Programming Examples: Mill Example 2**
### **Adding an Operation Question and Using its Value to Change the Output Depending on if it is Modal or Not**
1. If you want to save the previous example, copy the source files (master.atr, class.src and class.lib) to a save folder and recopy the original files back into the class folder.
1. You are going to add an attribute to (class.lib) called "spindle range". Since this attribute is already defined in (master.atr), you do not have to edit (master.atr). Add "spindle range" to (class.lib) as shown below.

\*----------------------------------- ß-------- Add these lines

:ATTRNAME=spindle range

:ATTRTYPE=VALUE

:ATTRVTYPE=INTEGER

:ATTREMARK=Spindle Range

:ATTRSEL=N

:ATTRINLEN=3

:ATTRSHORT=Spindle Range

:ATTRLONG=ENTER Spindle Range

:ATTRHIGH=41

:ATTRLOW=40

:ATTRDEFAULT=40

:ATTRUSED=1

:ATTREND ß------------------------------ To here

\*------------------------------

:ATTRNAME=material type

:ATTRTYPE=SELECT

:ATTREMARK=Material type

:ATTRSEL=N

:ATTRTITLE=Material Type

:ATTRSELSTR=Rolled Steel

:ATTRSELSTR=Aluminum

:ATTRSELSTR=Stainless Steel

:ATTRDEFAULT=1

:ATTRUSED=1

:ATTREND

3. Open (class.src) and add the new attrname you created to all the operation lists as shown below.

   Since this question will be asked in the operation list, then the value is valid for that operation only. Make sure you add the line to all the :OPERID= (Operations). If you add it to just the Drilling one in the example below, then the drilling operation is the only operation that will get the question asked.



\*----------------------------------------------------------

\* Operation List Questions

\*----------------------------------------------------------

:OPERID=MILL\_DRILLING

:OPERSUB=DRILLING

:OPERLIST=abs inc

:OPERLIST=work coord

:OPERLIST=coolant

:OPERLIST=spindle range ß-- Add this line to all ":OPERID=" lists

:OPEREND

4. Find :SECTION=INIT\_TOOL\_CHANGE\_MILL and add the following code to both tool change sections as shown below.

\*

:SECTION=INIT\_TOOL\_CHANGE\_MILL

:T:<N><TOOL\_COMMENT><EOL>

:T:<N><T><M:06><EOL>

**:T:<N><M:spindle\_range><EOL>** **ß------------------ Add this line**

:T:<N><S!><M!:SPINDLE\_DIR><EOL>

:T:<N><G!:work\_coord><EOL>

:T:<N><M!:COOLANT\_TYPE><EOL>

\*

:SECTION=SUB\_TOOL\_CHANGE\_MILL

:T:<N><G:00><G:91><G:28> Z0<EOL>

:T:<N><TOOL\_COMMENT><EOL>

:T:<N><T><M:06><EOL>

**:T:<N><M:spindle\_range><EOL>** **ß------------------ Add this line**

:T:<N><S!><M!:SPINDLE\_DIR><EOL>

:T:<N><G!:work\_coord><EOL>

:T:<N><M!:COOLANT\_TYPE><EOL>

5. In the same file go to :SECTION=CALC\_INIT\_MCODES and add the bold underlined lines as shown below. Adding these lines of code to the (class.src) makes these codes modal.

:SECTION=CALC\_INIT\_MCODES

\*---------------------------------------------------------------\*

\* M Code M Group M Modal \*

\*---------------------------------------------------------------\*

|<p>:C: MC(M\_STOP)</p><p>:C: MC(M\_OPT\_STOP)</p><p>:C: MC(M\_PROG\_END)</p><p>:C: MC(M\_SPIN\_CW)</p><p>:C: MC(M\_SPIN\_CCW)</p><p>:C: MC(M\_SPIN\_STOP)</p><p>:C: MC(M\_TOOL\_CHANGE</p><p>:C: MC(M\_COOL\_MIST)</p><p>:C: MC(M\_COOL\_FLOOD)</p><p>:C: MC(M\_COOL\_OFF)</p><p>:C: MC(M\_LOCK\_OFF)</p><p>:C: MC(M\_LOCK\_ON)</p><p>:C: MC(M\_ORIENT)</p><p>**:C: MC(M\_SPIN\_LOW)**  </p><p>**:C: MC(M\_SPIN\_HI)**   </p><p>:C: MC(M\_END\_PROG)</p><p>:C: MC(M\_SUB\_CALL)</p><p>:C: MC(M\_SUB\_END)</p>|<p>= 0 MG(M\_STOP)</p><p>= 1 MG(M\_OPT\_STOP)</p><p>= 2 MG(M\_PROG\_END)</p><p>= 3 MG(M\_SPIN\_CW)</p><p>= 4 MG(M\_SPIN\_CCW)</p><p>= 5 MG(M\_SPIN\_STOP)</p><p>= 6 MG(M\_TOOL\_CHANGE)</p><p>= 7 MG(M\_COOL\_MIST)</p><p>= 8 MG(M\_COOL\_FLOOD)</p><p>= 9 MG(M\_COOL\_OFF)</p><p>= 10 MG(M\_LOCK\_OFF)</p><p>= 11 MG(M\_LOCK\_ON)</p><p>= 19 MG(M\_ORIENT)</p><p>**= 40 MG(M\_SPIN\_LOW)**  </p><p>**= 41 MG(M\_SPIN\_HI)**   </p><p>= 30 MG(M\_END\_PROG)</p><p>= 98 MG(M\_SUB\_CALL)</p><p>= 99 MG(M\_SUB\_END)</p>|<p>= 0 MM(M\_STOP)</p><p>= 0 MM(M\_OPT\_STOP)</p><p>= 0 MM(M\_PROG\_END)</p><p>= 1 MM(M\_SPIN\_CW)</p><p>= 1 MM(M\_SPIN\_CCW)</p><p>= 1 MM(M\_SPIN\_STOP)</p><p>= 0 MM(M\_TOOL\_CHANGE)</p><p>= 2 MM(M\_COOL\_MIST)</p><p>= 2 MM(M\_COOL\_FLOOD)</p><p>= 2 MM(M\_COOL\_OFF)</p><p>= 3 MM(M\_LOCK\_OFF)</p><p>= 3 MM(M\_LOCK\_ON)</p><p>= 0 MM(M\_ORIENT)</p><p>**= 4 MM(M\_SPIN\_LOW)**   </p><p>**= 4 MM(M\_SPIN\_HI)**    </p><p>= 0 MM(M\_END\_PROG)</p><p>= 0 MM(M\_SUB\_CALL)</p><p>= 0 MM(M\_SUB\_END)</p>|<p>= NO</p><p>= NO</p><p>= NO</p><p>= YES</p><p>= YES</p><p>= YES</p><p>= NO</p><p>= YES</p><p>= YES</p><p>= YES</p><p>= YES</p><p>= YES</p><p>= NO</p><p>**= YES**</p><p>**= YES**</p><p>= NO</p><p>= NO</p><p>= NO</p><p> </p>|
| :- | :- | :- | :- |

6. Assuming you put master.atr in the same folder as your source, you can save all the files you edited and exit your editor.
6. To compile you will need to type this at your **DOS** prompt –

   **WINMAKE CLASS.SRC MASTER.ATR ?:\PROCAD\CTL**.

   If you have installed the UPG, then you can compile the source in the UPG by selecting the File menu and picking "Compile Post".
## <a name="chmtopic2180"></a>**Using Access Database During Posting: Commands**
### **OPENDB**
#### **Purpose**
Opens database and defines record variables.
#### **Syntax**
OPENDB(FileNumber, FileName, TableName, RecordList, Status)
### **CLOSEDB**
#### **Purpose**
Closes database.
#### **Syntax**
CLOSEDB(FileNumber)
### **LOOKUPDB**
#### **Purpose**
Lookup record based on variables in KeyList.
#### **Syntax**
LOOKUPDB(FileNumber, KeyList, Status)
#### **Comments**

|*Parameter*|*Description*|
| :- | :- |
|FileNumber|Access database file ID number - range (0 to 19)|
|FileName|Access database filename – character string or character variable with full path|
|TableName|Access database table name – character string or character variable|
|RecordList|Attribute list that describes database fields 1 to 1|
|KeyList|<p>Attribute list that describes key fields to be used for lookup – all members of</p><p>This list must also be members of the RecordList</p>|
|Status|Integer variable to return status of the command – 1 = Success, 0 = Fail|

## <a name="chmtopic2182"></a>**Using Access Database During Posting: Example**


For this example, the database has three fields **Material, Thickness and Feedrate**. In this demo post, you are going to use the database to lookup values in the fld1 and fld2 attributes to find a match and set the posts **feedrate=fld3.**

1. Unzip **Demo.zip** on any drive and in any folder.
1. Edit **Demo.lib**.
- Look at the attributes that were created for the use of this database.
- For this example, the database has three fields **Material, Thickness and Feedrate**. You will open the database later in this example.
- The attribute **fld1** represents the material and it is a character type, **fld2** represents the thickness and it is a decimal type, **fld3** represents the feedrate and it is a decimal type.
- Below is the list of attributes needed for this example. In this demo post, you are going to use the database to lookup values in fld1 and fld2 to find a match and set the post's **feedrate=fld3.**

\*----------------------------------------------------

\* Define Database Attributes

\*----------------------------------------------------

:ATTRNAME=fld1

:ATTRTYPE=VALUE

:ATTRVTYPE=CHARACTER

:ATTREMARK=Material

:ATTRSEL=N

:ATTRINLEN=25

:ATTRSHORT=Material

:ATTRLONG=ENTER Material Type

:ATTRHIGH=~

:ATTRLOW=

:ATTRDEFAULT=

:ATTRUSED=1

:ATTREND



\*-----------------------------------

:ATTRNAME=fld2

:ATTRTYPE=VALUE

:ATTRVTYPE=DECIMAL

:ATTREMARK=Thickness

:ATTRSEL=N

:ATTRSHORT=Thickness

:ATTRLONG=ENTER Thickness

:ATTRHIGH=9999

:ATTRLOW=0

:ATTRDEFAULT=0

:ATTRUSED=1

:ATTREND



\*-----------------------------------

:ATTRNAME=fld3

:ATTRTYPE=VALUE

:ATTRVTYPE=DECIMAL

:ATTREMARK=Feedrate

:ATTRSEL=N

:ATTRSHORT=Feedrate

:ATTRLONG=ENTER Feedrate

:ATTRHIGH=9999

:ATTRLOW=0

:ATTRDEFAULT=0

:ATTRUSED=1

:ATTREND

3. Along with defining the fields, you must also define the field attributes in a List type attribute. In this post it is called **demo fields**. You must place these attributes in the position that matches the database. See below.

\*--------------------------------------------------

:ATTRNAME=demo fields

:ATTRTYPE=LIST

:ATTRSEL=N

:ATTRTITLE=Demo Database Fields

:ATTRLIST=fld1

:ATTRLIST=fld2

:ATTRLIST=fld3

:ATTRUSED=1

:ATTRDEFAULT=1

:ATTREND

4. You must also define the lookup attributes in a list type attribute. In this post, it is called **demo lookup.** Since you are going to use fields 1 and 2 for the lookup, then **fld1** & **fld2** are placed in the lookup attribute list as shown below.

\*--------------------------------------------------

:ATTRNAME=demo lookup

:ATTRTYPE=LIST

:ATTRSEL=N

:ATTRTITLE=Demo Database Lookup

:ATTRLIST=fld1

:ATTRLIST=fld2

:ATTRUSED=1

:ATTRDEFAULT=1

:ATTREND

5. In this demo post, you are allowing the user to enter the path and filename of the database from the Setup Information command on the CAM menu. As shown below, the default path and name are C:\DEMO\DEMO.MDB.

\*-----------------------------------

:ATTRNAME=comment 1

:ATTRTYPE=VALUE

:ATTRVTYPE=CHARACTER

:ATTREMARK=Database Name & Location

:ATTRSEL=N

:ATTRINLEN=25

:ATTRSHORT=Database Name & Location

:ATTRLONG=ENTER Database Name & Location

:ATTRHIGH=~

:ATTRLOW=

:ATTRDEFAULT=C:\DEMO\DEMO.MDB

:ATTRUSED=1

:ATTREND

6. You also need to define an attribute to represent the status of opening the database and the lookup of the database as shown below.

\*-----------------------------------

:ATTRNAME=DATABASE\_STATUS

:ATTRTYPE=POST

:ATTRVTYPE=INTEGER

:ATTREMARK=

:ATTREND

\*-----------------------------------

7. Edit **Demo.src** and search for **:ATTRNAME=attachable**, as shown below.

   You also need to place all the field attributes and list attributes that were defined in **demo.lib** in the attachable list. Since all these attributes have the **:ATTRSEL=N**, none of these will show up in the attachable list in CAM.

\----------------------------------------------------

\* Define Attachable Questions

\*---------------------------------------------------

:ATTRNAME=attachable

:ATTRTYPE=LIST

:ATTRSEL=N

:ATTRTITLE=Attachable

:ATTRLIST=program stop

:ATTRLISTDEF=1

:ATTRLIST=optional stop

:ATTRLISTDEF=

:ATTRLIST=machine compensation

:ATTRLISTDEF=1

:ATTRLIST=feedrate

:ATTRLISTDEF=10

:ATTRLIST=abs inc

:ATTRLISTDEF=1

\*\*\*\*\*\*\*\*\*\*\*\*\* Add the database attributes to the Attachable list

:ATTRLIST=fld1

:ATTRLIST=fld2

:ATTRLIST=fld3

:ATTRLIST=demo fields

:ATTRLIST=demo lookup

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

:ATTRUSED=1

:ATTRDEFAULT=1

:ATTREND

8. In **demo.src**, search for **:ATTRNAME=setup**, as shown below.

   Notice that the **material**, and **thickness** are in most posts already, but the attribute **comment 1** has been added that will ask the database path and filename.

\*-----------------------------------------------------

\* Define Setup Questions

\*-----------------------------------------------------

:ATTRNAME=setup

:ATTRTYPE=LIST

:ATTRSEL=N

:ATTRTITLE=Setup

:ATTRLIST=program number

:ATTRLISTDEF=1

:ATTRLIST=x sheet width

:ATTRLISTDEF=0

:ATTRLIST=y sheet height

:ATTRLISTDEF=0

:ATTRLIST=material ß------------------

:ATTRLISTDEF=

:ATTRLIST=thickness ß-----------------

:ATTRLISTDEF=.125

:ATTRLIST=init abs inc

:ATTRLISTDEF=1

:ATTRLIST=init feedrate

:ATTRLISTDEF=10

:ATTRLIST=i machine compensation

:ATTRLISTDEF=1

:ATTRLIST=d offset reg

:ATTRLISTDEF=1

\*\*\*\*\*\*\*\*\*\*\*\*\*\* Add this for the database name and path

:ATTRLIST=comment 1

:ATTRLISTDEF=

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

:ATTRUSED=1

:ATTRDEFAULT=1

:ATTREND

9. In **Demo.src**, search for **:SECTION=CALC\_INIT\_CODES**, as shown below.

   Now look for the **CALL(CALC\_OPEN\_DATABASE)** command.

\*-----------------------------------

**:SECTION=CALC\_INIT\_CODES**

:C: DEFINING\_MACRO=NO

:C: OFFSET\_RESIDENT=NO

\*

\* Sequence number configuration

\*

:C: SEQ=10

:C: SEQ\_INCREMENT=10

:C: MAX\_SEQUENCE=9999

:C: LASER\_ON=NO

\*

\* Sequence Number configuration

\*

\* SEQ\_CONFIG = 0 - Floating Sequence N1, N2 etc.

\* SEQ\_CONFIG = 1 - Four Place Sequence N0001, N0002 etc.

\* SEQ\_CONFIG = 2 - Three Place Sequence N001, N002 etc.

\* SEQ\_CONFIG > 2 - No Sequence Numbers.

\*

:C: SEQ\_CONFIG=3

\*

\* Arc Center configuration

\*

\* AIC = 0 - Absolute Center

\* AIC = 1 - Incremental distance from Start to Center

\* AIC = 2 - Absolute or Incremental distance from Start to Center

\* AIC = 3 - Incremental distance from Center to Start

:C: AIC = 1

\*

\* D Offset Register Number

\*

\* If COMP\_OFFSET=20 and TOOL=1 then COMP\_NUMBER=(TOOL+COMP\_OFFSET)

\* COMP\_NUMBER=21 - <COMP\_NUMBER>

\*

:C: COMP\_OFFSET=0

\*

\* Open the database and call the lookup

\*

10. Now I called a calc section to do the open database. Six lines down in the src file shows the **OPENDB** command line.

:C: CALL(CALC\_OPEN\_DATABASE)

11. Once I have opened the database, then I can do a lookup or multiple lookups until I close the database.

:C: CALL(CALC\_LOOKUP\_DATABASE)

12. Now we will close the database after the lookup.

:C: CLOSEDB(1)

\*

\*-----------------------------------

13. In the example below, **comment\_1** stores the path and file name of the database, **DEMO** is the databases table name, **demo\_fields** stores a list of the fields in the database and **DATABASE\_STATUS** stores the status of the open database command.

    Notice that if it cannot open the database then, we call an error message close the database. In this case, you might want to set a flag to not do a lookup, because the database is not open and might error out.



:SECTION=CALC\_OPEN\_DATABASE

:C: OPENDB(1,comment\_1,{DEMO},demo\_fields,DATABASE\_STATUS)

:C: IF DATABASE\_STATUS=0 THEN CALL(OPEN\_ERROR) CLOSEDB(1) RETURN ENDIF

\*-----------------------------------

\*

:SECTION=OPEN\_ERROR

:T: Could Not Open Demo Database<EOL>

\*-----------------------------------

\*

14. In the example below, you can set **fld1=material** and **fld2=thickness** because material and thickness are asked in the Setup info.

    In the example below, the lookup command uses **demo\_lookup** list attribute that uses **fld1** and **fld2** to find a match. If it finds a match, then **feedrate** is set to **fld3.** If it cannot find a match, then we will default the **feedrate** to 999.



:SECTION=CALC\_LOOKUP\_DATABASE

:C: fld1=material

:C: fld2=thickness

:C: LOOKUPDB(1,demo\_lookup,DATABASE\_STATUS)

:C: IF DATABASE\_STATUS=0 THEN

:C: CALL(LOOKUP\_ERROR)

:C: fld1={0}

:C: fld2=0

:C: fld3=999

:C: ENDIF

:C: feedrate=fld3

\*

:SECTION=LOOKUP\_ERROR

:T: Error in Lookup In Demo Database or<EOL>

:T: Lookup found no matches in Demo Database<EOL>

\*

15. Open the **Demo.mdb** and select the **design** button.

    Notice that all the fields are set to text and the field length is set to 255. **All fields must always be set to text**. You do not need to set an index field. Access will ask you that, but you do not have to.

![image\img00001.gif](data:image/gif;base64,R0lGODlh0AFqAfcAAAAAAAAAewAA/3t7e729vd7e3v///wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAAAAAAALAAAAADQAWoBAAj+AAkIHEiwoMGDCBMqXMiwocOHECNKnEixosWLGDNq3Mixo8ePIEOKHEmypMmTKFOq3BigpcuXMGPKnEmzps2bOHPq3Mmzp8+fQIMKHUq0qNGjSIkSTMq0qdOnUKNKnUq1qtWnS69q3cq1q9evYLUaGEu2rFkAZtOWBdBSrVu2AbKGnUu3rt27eKEaKMC3r9++A9D+Hcw3cFvCgw3HHQjULNW0NMfClJy3suXLmIXuZRh4M4DPoEELVLx5oWK5AdC6NQDXJWXKU2HPlB2AdubbuHNfLq2wcwECoYOPhlv6M0HjBE4zdon2M+vmzScbcD09dvXI19tm1829u3euvBP++gZ+EMDwwwORI08OF7Xqt9KpU38NWbtt29ql0yebvzb/7wAGKGBR4SE0nnkGIUjab+mJNpByAr0E3XMUttaff/1JpuF0G154E34Y0hdidSAOaOKJKKJnmmDkJXhebQw2WBCEBEi4GmvxZehYhx1imBNtO5LI4ZBlpWjkkSYWeNCB5b0YXmgE0Wijc1RG9xJsIl455Ige2iSbiGBuieSYZHqnpEFMusieisAhuJ6UzN1ooY9YCslljyXG9KWdYdK5XZmABkpXccI9yCKCBSlIHIPrtfmiexVOOKdjWva5358gAlkkpZcK6umnYBEKpaGeBefggpy1t1xL76k1J6j+sMYqa2Mxisfiimza2pJ7pgY366/ABluTAQMUa+yxx6KF7LLGEscss6pGKOy01FZLU6/YZostq9r6upi01oYr7rhboUbuueimW9RK7Lbr7rvwxivvvO0+a++9+Oar77789uvvvwAHLPDABBds8MEIJ6zwwgMbEGW3EEcs8cQUV2zxxRhnrPHGHHfs8ccghyzyyBQX4DCpN56V8sost+zyyzDHLPNbM9ds881y4qzzzjz37LPNACBGWNAnD1c0Q2jRq3RJSS+NUtNORy21QkSvHJjJDx+9ENRRIyqQ11M7xHXYII1N9tlLE50q1qQ+ZPZJwoH9daLHISo32W+77WD+k1uP+rTWYftN0d12oy02272p3bbYgMPdENher3d34I27nR5Ck6upUt5dX95R5oZjjrito3fmduVM092mm1/vTR7rq7dunuSNrsT548fJrnvsmhcuuOuDo+505LvzLtrsrzt4/O6Cn6144qXfnqjwI8Xd4uvXEw/75bAjP3e70m+de+6E986954VbFD692p/veetz++4+9t+j/Xz9hkZP/XH7hwT56sbx3vVa5D0odQ+AoCPJ+hJCPAAOsHkPJCD6IBiRBcpLewZMX/0EyMHsedBw9wPe1Y5mOsaBj27/06AEO3jABMKtfwwk3/xUiL8Com8jFoxX+xIkQA/KL37+Mwzd8wo1HP2d7oQyBKIK7cbC73UQfDDE3A2BuEHNVdGJ7wueEKcYwQbS74tNxB/e2Nar/JHQgjn8nOqUJzsvqmd5EuQdFNXnulG9sXYDzF4d8SiRNL7rd3dsEAv3FkDmZXGM+xth1o4YukYiLYpPG1/ZIOlI8VWyj6Mz0P1K+DhKXlJqfkzdIT/nyU9a0ZRIy+SSNkmyVrrylbCMpSxnScta2tKVqkQTK1/Wque48mfADOZqCCDMYvqMmMZMpjKXWUwCFGBfuzxles7ySmZa82bIvKY2U5bNbXrzm+BEYLeMmCjCUZNkrAGnOoe5znV2s53wjCfPnCm0v0SznHL+e09wxtIrX2rLn6BJpzzbmc19rqyXA33ZOxPK0IZy02RWu2fdaqfP0PDTVAClmEAdus13InQ1H+UoO0VK0pI6M5ESFWSj9MnPdDrnomR5aYVcWtGNlnSZHl3LS1ka0JuO1KdAledJ13ZGwJlqmi11KUBpCp3mwHSfTg1qMnOaVIFGNaRSXahUt6rNoa6InBNdaUxpSqGx9tSsVVqLTbn6M6outapYDapW2UpXY3oVekXlIUXNOtOANnWpfvWlUuvaVpVVVa2HpetcCcvYnt2VdHnFZ4LQSiXB/jWwmK1sXBsbM7eydLCb9eliOUvamj1Wk2CV0WRbalGZllWmVZr+EF9LizO3CnajqnEtV0dL29627LSrTK0YkRrTavrWtMd1GW+Ty1yzAFeXwqXaOVvZ3M5Wl5vXza5bnjsjVlYMleANr3jHO7Vcdld/Lgutdju6XrUst7295e7DostA+ArVvmV5L345K18zLpJxNEuZevfLMv0m18AErqszoUlfzBU3sIiNcIKRe9Gz5oyxCJ7wbksW2U5GOLQD1vB2DcuyEIs0wyKWq8NWTMwWs9hhDS4PiS1q1coytaI4rjCBbdtTnup2qyhOsWhdTOQXEzPGqx0rXAfL2iXzVML79aySr9rYIAvZpEbOcouRPL0P87VVsKVsWmGaYM/SGLdVvnL+fIvM5hVzmX9ebjKYrTpbahZ3xzN2lZIJa2U1c7TNgH4zcZcsZ8RGlclz3rN9pZxUKmPYz6UViJazLOiv5bnJlr1zo3fKaRP7lsc7nbKnGdpnSJN60myuNHBMrcxSp5nVGAY0pTv8SFg3s8y25jOqjRy975L318AOtrBDsmsXo7dlo861cnGtbLbKOtW03lqzgenqR08byM9+saqTnRZuT7jaur52VovN4m0/+McCTrefC3rmC4db3ECVdLaPHG3pJpaX6lazbfOtYHireN4wrnd9733WgmNWx7e1cJRJnHDKvtvfJgU4vf/rYcDW+dCyVetn17roS9M5t6+GOJb+JW7uxEK1tXX2J27bjV8zF1zRihX5TeVN7pKvtZc4v7jOU8xoj/db5iSVeMApXuub6/zJTt6zt0nbc5CD3NpA/7PQbY5Qg+P40Cp/LbrhC+qn1/jhUT81yQXu4LDLDNw/Nzupp052GasdZmiP+dsTKvTHBsbXw8673vfO94OQe+IoQ/bcFcrswcez7jY3PHbxrHh40jzbiW/8iBkveXUivu1Jrrx7C695bz5+15HvPFni7mzRf/PyRJe26Z3L+dUz8/OyDr3pSb9b13f170NfXMVtT3sg2/6asJ+07EXf+3H//vW4tzsaj79iyjPfrmxPvb1/X3wVP3+qyR9+56v+H+/rTzX6ui8671vv/cKO/WF477v6189+VOL+2CVmPvdFW/5bnz/8qqc++es/T/Ab7XTHN38zx3/BhHr4N33j53wE2H/vh3ldpn8KuIA6Y4D/B2AQuHAS6Fj+xx5RtHRAJ4BYloHzlH0OCGcX2HIiyIAAp32aB4JBl4I7Q4EcCIAn2HEwWFsbyEni53oueGI3WFskKH0DV4Nc94PYlIPLF4D7Z4TLdn/DkX7tF4VSOIVL04BZk17yt4RMWGBBeIBDmIAYuIWdhYQdmIURKIZc6IQzaIFgiIJoCHdkSINtaINv2IR/x4KV14N/VocKFYdsyINayIdpIYM6mH9zWIT+glhgfrh7gHiGiTiIXViBjLh6euhQlUh9i7iDlBiIjzgWhJiERNhel8h7mWiIjRiGnThianh3FEOFrviKsKgSVhh48aeEjpiKnhiJaziJs8eJnRh8bYaHkjeKdIeL7LSKoHiIomiM21WKCHiKbsiMrIeMZWiLqCiNnuiMXwiNdIiNuUiNcsiNiOiN2TiLkqiJvXiLuPiJ1RiK60WMlKiNZeeO2gWPvQiOf7iJ6piK9FRPfZFSpqiP14iNJxVRvdaKsZiQCrmQGGFe81VUWGiN0UiO/VVEJTho4riM5OiJDulfXjiPyviOG8mRKCWMjWePhzeSuVdGFimEIJmRIjn+kndFROxhkoqHko6nko8lQgD5jAI5kd54WnKjSB/pdvSYXTjZgh3ZkkWZeTBZjzq5lDV5kZYmkd0YlFJJlOcYkOk4kNJYkVPpkkYZklApk8+kLz25jT95lQTJYVHij3AZl3I5l3RZl3Z5l3iZl3q5l3zZl375l4AZmII5mHV5NCp5mN/GkIq5mIzZmI75mJAZmZI5mZRZmZapd/9zmZq5mVFoPacUOcCDETTEmaRZmgqEO5L0QRrhQqbZmq4pmmukHm0kScjjJspDSLI5O4UkR6H5mr75m3pVSPKzRNyzPWDkQ9sTRsC5nMyZmsmzPEvERjWEnHBEnQHEms2ZnZf+mUIolEWZ2UXzc0VfVDfaWZ6tyZ1K5J2qA55UdJzt6UXmGZ/bGZvdU0fr6UD4aTzkaZv8KZ/++Z8TgZ0AOqAEupoFeqAImqCVyTAM2qAO+qAQGqESOqEUWqEWOjBRgpgaumgK2qEe+qEgGqIiOqIkWqImeqIomqIquqIs2qIu+qLM6Xgwmp0XWqMDkBF7QZh1KaAzepk3ynelVBBnshKdcXo9mnc/undBShBDqhJXo6NwyaNH2khJqndLOhBNmhKB4S5bOqXAVqV5d6WSViuipEtcKqVeejZgOmxiemSY05vqo0lnmqa/tqbC1qZngqaWs0oXoaeGQqfkZafBhqf+ZJpHzIObrNOfhjoc0kQ1FtGlgBpeggpshCpNP3SceNRDD9OoMVQRkBqpqDSpv1ap9IlA1tlDBiSn98mbsompcPqpoPpJokpepJqamnqp4qmpf3qfl1qbVTSa7BGr4DWr41WrtOlDQaRBusqovJqsyqqamyqspkSs4mWsYWVITtSqszk5sBpB70k/vcqn0iqrfWet9ZJPx/pDynk33TquhkOt4WWu7NKtdkQ7yelAFBSs7lpJ8Ape8kqkfio2K7Kv/FquGJGlKNGuODSwBEulBnsRCHsSCmsSE9uwUdOv7newhTqvAZsRFWuxS4OxpvSvTuqBG5pc7PqwFhGxKAH+pS77sjAbszI7s4LZriL7SSQ7hSdbgBRhsypbESzLfjtLbT2bskCqsYOzqiM7tMdUtEvysxShJJ65qpBTnWeDcCencEw7iE6LJlA7EVKLmuqJs0gHc1s7TF07I18rEWE7PtL5Oyh0mx0LEiqTc2e7Mp5qtEqKtPgknOdDQ9L5rfRiaD2mtXc7emkbJWsbEW1bnNA5SoJLk/FitkZ3uFw7ET57tBBbqOgZRE1yr1FzbyZnuZcrEZm7t5v7mcgKrNjjRkpTuYhGus6VuA+yuBDRuNlanyvFRvU6tx/xVlYnu7OLuXprpXyrkMJrWrQ7Grb7EEG7fsk7M3n7tJq7shv+C7IKerrGm7rYG6LaG6bHm5DRe3bLmxzN6xDPq37jO4bES72oa70Mub5w2L5eW71Ay7n5WkGNJL99SL9qa79Ry7lqFDr8q1zle7OXZK75lJuxY6/FQzYF/FsHfL4NIbWpGj8HlEfLOjURrIj+q7gADLYCnK5TxJ8bLDUdjLcTXBECIAAJ4cIEAcPsosDr+USJGp5Xm8I3Mr31uxAtbBAyLMMxXBBCLIvhK0bhukI4DME6jLYfXLsM8cNE7MNT3C40LFkfpLu2aThN7MSmW7wIAcNF3MIuLMZSbMZSLBBkHMRn/MNpTMZse8Sw2MXN+MTMS8UEMMYDUcZ7nMd+rMb+QwzIQyzGgBzEjCvHr0jH7rXCCkHIgezHa8zHhtzHgrzGf0zIkXzI3Nu9H/q9QJzJlAzJUzzJgizKhVzJfwy2iMzJB+rJVVzKqczHp0zKsVzLjizLqYy+q0yFily6EeHKj5zLkwzHl0zMpYzGsnzLaey8u6yzvZxfjLy98Ks0vguxz4y4dmy+Icy2+KunC6xajuou14zNX+y+0ny/fNNHPATOnWrF47ykwEypiGzCs0mdMlRADmycKPHO8AzGElHEKDzPv5qsLuKrSdSesvjOPPy/LNwRAB3GepwQ8nqv4YqucZRB7JzQ47zQINzQHPHQQPzJCjHRA/2tFn3DG2T+0CvBzxwNxWrcxshMxMZszMecxzRt02j8yn0M0vK2yW5L0AiNxNBqQyut0IwM0rgsxIZMy0sdyrUMy5Z8ySMtx9Wpm/a6xYdEz4FbzWxr1NmcpGMMx0y901Fd02Nd06FcxmVtEDnLqaPq1eXcw0q9007d1Adh18Kc1o881xLdzG5Nq3D9y3rL16ac16cM1XSN2Gi92LnM1n7Nyv+pvcRsyUw908v80m580zaN2Z8c0QjR1pDtn/E8EjxNt4/dfiwdzShR2r972kIb2BAx2rTq2tAL2w8h28W6yvl7rO5n2w6B22G8vwINEVwtL6n91RTB2g+h3BpxxVjcuwR0R8X+LRLHHdcMHRHM3RDZfbBU7agV7bkc7NsNAdx7nNlvfMbFzMZqndOmrNnM7NPDha9A7Z7hvdGq3ch7PcoAjctPDcmOvLLdXcPIatKQ+7rinSrmjMdoTdkxLNZ7zeAvDbHD/T7rOuCLauD2jdwOQdhJ3d/8TcuNfdm3q9tya9VMFN2gW9/X3NJ3rN35jdd47eGNPePvPc36y6YHzrDXHcVuTMkQjtnsDdPHLOIjDt8Ci+MZbt0dfc4BHNodSt7+SttOTqP+fKdSXq45njgJzqZXDqRZbitbTuMgwdrbvRCg/aZie+NFneSCHeZljt8KHtxv7ndUDacX/rnm89cjUd3+bd7DwUzacQ7gRs66AqqrwDrdjPvlqrrjlQzT6o3UOK3ehR3T6/3oDOHcKH6oFC1HWczAuUvdii6ujD7ptuzUg5zYh03qHQ7idD7oB72sTVQ+6FrhdBvqZurnqL7qpp7reQ3jqr7rju3qjrub2/q3eF7svrPb1szmsV3lup7qkB7jzy7Kvm7mAR7Uzzqcx67tQV3rzH7bzl7q0A7Lv87rTV3tUy3scUTfsS5FA53Ev2vr3eXmnP3UUa3Hw9zjkQ7kpL7v1j7oe2ScvYvPVnTB0E1s8h6to/7P5H4Syn3mr/3tv13ly43eKeHewW7j4pvwu7rw8mzkUw6gUJ6xIB/+8qJN8R+v8bHI580e5iqx1h0B8bUt8eON8qsN7Dja5eUTSd6+4veN0/4O9PVu2WRO1+wt9BjPpNcu60oLrUhj54jOpBzPrIzO4aP84htO1mb95+mu8k4f3zuvzvF95wc79fpa9aRM6Q0u1sx97+XN9uWty+quqPgcSA2s6d+56Zxe9jSP4Lge975O2A0e6Ky+2RH+714/nukJuBb+RFfE7WSf6H2v40t+9eNu9T4e3Pmt2A2f8ehc0CrVuhNE7LRez6ur7Ldr9p482UQf5ELe+SG+9kNP5J7f5KC/uo2f+8SpmirNESwP7i6P8470r9mOqfPt+Fls7GMPtqpv82L+Pvy6fa11T8+OQvdjm7t17/vNH/yj2uVKuv1/b+Ulz8vg7/Ebnt1FT2zeb/Kv6cqgPONlnv6mPf7sX57uL9I6HcWBHvPrH6blX/kAQYCAAIEFBRI0OFAAwoUMBxpsiFChw4gJJx5saFEjAQMbPWo0UODjSJIlTZ5EOdLASpYtXb6EGVPmTJo1bd7EmVPnTp49Y6Y0OACAxgEaI0qUWBCpUoUJlz59eBAi06UkOwJNGBLoUItcsX4FW9LnWLJlzZ5Fm3YsWKFEjb51ylRqUqlzKxKsWvdh3o9Xw2pN6NWrwaGDCRgWKBglAMaMSyL+q1byZMqVLadlC7moRbp65Ub+3cuZaly+UD179AsWMOGCkF1rhHwyNuywFi/fxp1bd+XMbkX/nqoXL/Dhc0EnNQ26b22OIgO3Tuz48PTDjaNztY5deuPXrbdDt86c427y5c2fh9nb4ua4The2x+gQPsP3ezO6l68cNfPVrBEXnk4x/8AjMLGuoDMwwATFGw89Bx+EUDL1EmKPQeY6YzC1r/orsDrHABSQO+oUNFBA1q6TbsTZsIqwRRdfzGnCoCxkEEPxNGTRueewIxDAEjv0kcQRERySyBWBgjFJJZeUsaAKaYTyRv50fG5BEFXEUjEtiTQSQR+PTGlJMcd8sEmBnowyzQ2n3GgwEb8MT8TqqIv+k8sFPbQyugzJ5LNP3MwkAM2N6oPrMzVZZPNQRRX1s1FH1QJUUOIKPW1Rk3BEkkpLN73xUU8/5SnSkmw0VD9OVUr0VFVXZbVVV199ta31Rn2PPvkqUuq+iy4iVFddw0wVVmGHJbZYY4WVlcJRRzOutFKLo4hZ1YI9FlZQr8WWJlFJeuqu44KLyttwJ6qVVLGordbVbNdld6VtR0rOOM+Sg1Ze99asjUNWwWS1XX+vffcjekObV9p6CVYuv0vRlRMrfu8s1gDGWALgX4vHDNijqu6zFTm5xL21Pl+BzVdTLBd9WFWJK16J5YtffjHjdC3ENEyTTQzPwyCv1E6wnI3+lThooRuDuWj0ZJ5ZypIPTHDLH3/87ukiiQ2a5Ypddtlorf/8KtkZk4ayZpT0bZi7nbNU8U07qba6aoq3hvs2pMH+i+E8TxTySohNBLrtq9+OO/DJ5qYb379u9hJItHE++VihV348a8EnL4vwwpG028sU5VTbzc1/jhhrqyemvPTKu9bs8gzRTSll1QUyPXbeUPft9bqXDsv112XnHVLaZ7X99sODJ754448fyWsnkSd5eOafhz76dJU/U3qrWLd+w963Px0r6gPNfjncw8+Xe/N7sjx7sU/Slzbdq035fPl1St/69S81WU+pZWu49dzXRg3pHjc/ArKkftK7n1j+8jen/W3lK+/DW/wEKLkCzu+A0UugVfLHIxLViU60uc7TQGeYOOXsTR8CHUj+NjQBVpB7F4ReBlWywabl7YNTY1zUhuQmxTmtcRtxWxAH6ELewfB5MuwLDT94Np4xTWdnu5PnstPDLvXFb5Ej4gt/pyzygYRhZlPQlvTGJRJWMYpVsiHjrNgyIVIwi6UzIvOQiBrE9ehkfCuSD/nGQ6kx0YxAFB0W31jELX6ti1nJHNRCeDfvlJCDi2xkz+7GOSgGkGKjc+MgJxdH5M0RiAuEHgRhp0kXcvJ4ngQJKI+XwrGRsoKmNB4qbaPKQ9bSlrekUOpwyRHs7dKXv7Te9yT+RT5ZZoWWwCyIK19ZyOXtspgGaR8ybaNMAsKyeM9M5jHbVBtRboqa1WRm9Zz5xSN1E2KOm+A3Cek9XeISm7BT4kfMObW+YU2dsrMm8d7ZHBCWzZGT/FyK0hVETN5TcPkM3j7b90g/1pChP6wWQQVp0K0h1HYKVaIen2gktZ2zb2xc4RApCjOL7o51D/VhBNE4T0Zd0Z4j1VpJVYfRflLRoXnCIzovOVGYkjSc4Bvn+Bp5x38S1WcCjWggV5bJnvpLppejqTRV0tTYPbVwUZUqaqhqOqvSDatZBWtYCydMX35VrGdFK7HIGlTnpdWtb2XVWt3ZS7jW1a4MkustFTq1AL721a9/BWxgBTtYwhbWsIdFbGIVu1jGNtaxj4VsZCU7Wca2U6/MMVtmNbtZznbWs58FbWhFO1rSlta0p0VtalW7Wta2tn/NnOtdZTvbyw0gcLTFbW51u1ve9ta3vwVucIU7XOIW17jHRW5ylbtc5jbXuc+FbnSlO13q2pKy18VudrW7Xe5217vfBW94xTvewbrWvOdFb3rVu172tte974VvfNtLXvrW1773xW9+9btf/jY2IAA7 "image\img00001.gif")

16. Close the design window in the **Demo.mdb** and select the **open** button.

    The form below shows the three fields with information filled in. This example only has 6 records. You can have as many fields and records as you want.

    ![image\img00002.gif](data:image/gif;base64,R0lGODlhQAK2APcAAAAAAAAAe3t7e729vd7e3v///wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAAAAAAALAAAAABAArYAAAj+AAcIHEiwoMGDCBMqXMiwocOHECNKnEixosWLGDNq3Mixo8ePIEM6FCCypMmTKFOqXMmypcuXMGMiJDkggM2bOHPq3Mmzp8+fQIMKHUq0qNGjSJMqXcq0qdOnUKNKnUq1qk+BNK1q3cq1q9evYMOKHUu2rFmcWAWeXcu2rdu3cOPKfVugrt27eAHg3WsXgE2+fP0GSFtzruHDiBMrXsx4awECkCNLjixA7+TLBCr/xTxZ8+ABWY/i5bqXZ92cpxurXs26tWupjxlWjg2gtu3aWAXHVuiZME69gAXfTJ3acQGfxf8ef828ufPnrnfztjzg9u3cmwXiHggA++fQNvX+3i5Qmzzq5QGSV1V/vj309/DjyycrPeFsAtUNdgetG7/2/fvxZ5NvNwEXmHvpoWeXcqMxiJ5ypj2Y4HINErfgfBhmqOGGQtU3E3UBcuddfdd5R2B45NmWonk4FUcchKfFeJyFHUoII4Uz5gghhzz26CN8Hh50X34F7eeZh9uZCJpaBaZY3pMIvtiijjLuCFRyVdJY5Y9cdumlakEaNGSI2o3oX3UADtTbkoWhGJx7Lt6Y4Jw0BoUllTjSmeeXfPbpZ1m7WRfimPqZ+R9BRgp2YgDiqQjllBcOp6WOE0rInpUOVrrnXX926umnVAVqHUFjCppodtMNyOZvgLEI6qv+sMb6Y5gFDZlqemd+qCp4jJpqm6zABissdAUIYOyxyCKrV7LMGqtbs8wquuqw1FZrrXO+ZqvtbeFt++t3TF4r7rjkArtoueimq66PhMnk7rvwxivvvPTWa69MNEGr77789uvvvwAHLPDABBds8MEIJ6zwwgw37PDDEEcs8cTHFkBYZd5mrPHGHHfs8ccghyzyyCSXbPLJKKes8sost+zyy7YRYDGbs7UamM0456zzzjz37PPPQAfds4FCF2300UgnrbTORC/t9NNQR720zBfrBZHV92attXYzb+31vVh/LXa8VNMcdkNnj632S2mv7XZLbb8tt0ll5xt3QndnbRv+d2RWlORBf2+dt7y+oqlf34fOTdHg9I66OOKKJ1R3bl2jXfnXeyeOt0OBFwm5vYzP+3fnnWse+dWXa116RKsj9LnXk/OXukKhN7535q6/frXuos8OdoitA8776fr5DvrwCwXv+dyxz4b62tfhXuL0mUcfYImGi117vKN3l+R21B+K2/fSV4+73sbXS/r52OcHvvnvj3/+1s1vzzX03qOZZuLvl5l99tcDEPLgZb93dc97AvSf/AC4QCI1MHyqS5/tlsdA/kGQSBV04ADdVT8JFsmDE0Qg8MzHP80dMIHaAyH3RmhB//GNfCU0XPk2KJMCustx/cvgA8kEQRTCbmb+dlPh/dQ2Pv3xTYcXhGEOMSdEA7JQh56DIQPhJ0DlEbCJN+QhDreYQfGh0HE/rFoTbehE/eXwjFo8IhLHRsaYdK+FGPQiHCE3Q8FhsYZppCCiEGjCL+5PbR18HhFFiMY59nGONKzhHd34xDPKsZAanKIPwbZImAQOkvFbIiZNp7VAPqSNxAsl7SopylK6jpSmTOUAPMk5VKpSlKB8pSpjKUtRstJytcxl8lypy9PRspeKuyVDfgnMtxGzmHI7JjIBCcTcwOyZ0IymNKdJzWpa85rYzKY2Q9bBoUntm+AMpzj3MoBxmvOc6ExaOdPJzna6ky/CfJ2BovnOer5znfb+zKc+wYnPffrzn0aL5+fmCU2AGvRp/TyoQhfaqoQy9KELFSgd+1JQiFqUZw69qEb3mdGNerSdEkUcQfNys72UJy+NUtFHV2qXjo6nLtZhqUyR1lGYqnSmOA1oM2UXRdL1xUmCAipQx2OqoebUoxklGnCadtSm7iyh87wLU51KVcCE9JI/zZZQfTXUJ720qgxNqlRhCtayNnSsP02rWddal6sWj6xaJWpR5/pVtv5TrFm1q15rqlS9rjWkgKMoReV6UpSaNKWF9as+8QrXuir2qHxF62OpKtFT2lSlhEVsZh3l2Mm6k7HkCa1aPTvTyI6WtDgVKN4Gy9XNcjamMUX+7T1LSlaSylampq3tbWcaz1E2lq5eDSpwE7vbc4KWqVMtLkRzK1rlrlSYu/ytcF8L2+ne1LnjPG5zt4vd5baqr931KHR9uyKpUjcwyE1ueMPZT4IWtrPrVWhNhRpfjY53tZeFWX35uV+wzre/4t2p8z7J2pcBOGr/PfBGE6xgiN7Xsl1tWYOdxuAJP7TCFj5oN3mm3gyH1cO4BfFHHxxYEWsUwyb2J4pTbE8Sv5XFF4bxiWXsYAEXsMM0zueKc9zOHfP4nC7+oHmpS+STBpW7P36qzXCcZPYOmbVNRmeQESVZk1b5yrqNss74ymQtI1it4sGyl6E2Ze6IOcvJnWr+l8fsUiSP2clWBu+bpVZmrp22ymmm7ZwBM98175mmN5Pzn51W5+qgFLlDfumR/azlPg9anGIV9KOTVug0CzrPVp40Xhytaak5dKln7jTQKr0zSd/ZzY/mtKgR+t1Qr7pnpD41moOj506r+tVKg+poGY1reNp4jKE2dZZlPehb9/po7cXzsYUW6wLjedGxPXKqr8zrZZ81v0u9rrVh/WvUbRtqPv42RsVN5m4TmNxLCze6cabudftajN52N7LlnW56I61+HlumvvfN737XcsOltrfR2i3wlha8aM0+uM8IfnCG2zvhCh93xIPmcHpDfOI5q7i9Ne5uiFf344qONq7+bx1bhbf3vdqOeMLVK2w3VzvJbW55wSPtaoubu5XEbrmaR75kYs880DWXt8eJu92idnXYmlZ1yU1u2KJjvK03txx6lV1rpE9a6UEnN819bnN4nztnOq/61Xsudnpv3eoFX3mrZb3zVxub6+g+O6oFrnZas73sxSa70yOOz6jK/OFRH+ahE6tUaIccvm9O9rOJLvCTu/fl27740689eYlXPmeSv/ymNa9kztss8563WOjZPXqr2jjf/k696lfP+nsBnGmlJ2fs+Tx7vIDe8xyXd+7RfXvO737dvxd37zUffK3X/i5DL7Kk257ery596Qd26U2h3/hEj77uVQ9zWsH+i+hMb9+2Ctbu3KsPd4xj3/t5BfP3wU/tYUOetOJ//7IVX/rzsx+uko0qktuO/gxrV/7zV37mF3jRNVj9p397B2qDh3LN52H/h3hmB2XXR4Dk1XTup37r133fpWYAOFn/l3Xi1ncCmHYUiF9gl2iYRVIKmHWYFn56poENh3cD6HU4h3bNtXPphXT8V1tN04GK9YEjuG0iaIMzaDbAhoL5B3SZZl3TV1fU11/053wpR36XVX8lCGG1V3wheHx2MXyXp4XfBobL5oWVJ4bWZoa9hm8d03ps2IZu+IYi8XonyIVoeGx1+GpkOHl3yHNc+BhXWGLHt4du14d+SINSF4j+hFgXgthpyRdcTnh/PHhYUnhdT7hfb6eHSzaFB2d/WKZ9kbh+YtaDF9hgXBZ6ujZrT8eJd+aJNwiKpyaK3OWDfhVzpkh1RNh1Rhhvc4docqZ/MHh3InaJT8dcsihqyXeAGPiJzdeEDeh/ekd8a3eLQveHL2aBsZiMorWCXMd4jGeJz/iF0Th+uBhEuviMRieK2iiNqFaMdiWMGEeMk6eKqOiKoZWOLmdbsOiC4QiOdqeO6yaPrRhnh6WDtZaO7MhW7jhx8JiK1ChkzoaN6YePIMeAhAeB8UV//kiF6NWNJGiIgkeHiSh6fZiHwxiSi6hpJPmOJkmIcogzB2l8iXj+kpOWkgq5kiPZkFQGkjHJkjhpZjpJiDL5aI2oWYQHidkoicxYkZpYXyRnkcCXiUsJeB5ZgLsokK5ojzt4lCCoXKUYhDC5a5wHkLyYhJ8YivholExJa3+3ce2neWJplbrli/2Hdi/5g3pXl2PXj5d3jPeHgNyngyWXclGZltFYiREYHE45jpRTjoJ1Wn6JVljpkhxoYVjnlQGol3j5Z2RYeCI3VpE5h3PpjftomXYYcAw5lRXIcm2JjgSJjNdIit9Imr1WYZm5Z29pdaxoU63Zl6Ooj/24lnEXjrU5Z0NJlipYUkxIkZzJkRfZlvmlkhvInFKZi1+XhTbJhTTJd9f+eXzZyXQ7eZNVg3pwOJ7kWZ7meRAtGZulF5R5iZ09aWeI+J3uiZoT9ZN9yJ6aSYF/BJ/WKZ/cSYDzw5+zh595B57U+R+CkpPxCZQ8OZUBamj2GaGz11v545D9yaAGSo6FEkcQuqD32aAHiihYOKDbWXvdGYP+aaLv2aEX+qEZupjVSaIpOqErOpylOaOxd6I/h6NWiJom2KISmqOnt4bnWaRGeqSqVz8Us6RM2qRO+qRQGqVSOqVUWqVWOjH1g6RauqVc2npZCkxX6i9dehKcgRkAUKZomqZquqZs2qaX0R2iV05yGqd0Kqdzeqd1Wqd4uqd5KhB9+qdzCqiCKqj+fLpOhWoxbHqmNhYTP1Ntg7JN2lI5jTqpPpNItqQzlSEzj2U1hJqnncqnn+qphzqqowqopVqopaqpNpOpiwoTTTRgI/Go8iWpEAGrDWGrsmGpoVQ208GruQSnp6qnoXqnwbqnxSqqwyqSxxqoo+qrQqKoVcOotVpAlUEqNio0duqn0/qq1KqrxOOszwqur8Spy6qIyWqo52qu5aqt57quMyOo4mqtXyoSr8Ot3Gqts0oQ9rqt0zpM3tpJqUMmrApMwNqu6cquy+qu6FquB6uufeqrfTOwZnM4/1okCtE1l1Qrd0MTGouv+0Q02RqyHKqxGKtHMCpSHUs7yVOxMeH+rIEjsbpErsnasDSrsDZ7sKlaOS8LrRPrOhpRr2rESbiKFQKQOtWqJtdaaiBLq3tkH2HzRvhqOvkTIEe7OVYrNxC7s/GaSgWbsDj7te5as+lKqFn7qPO6oUaEoGpbodNzEBgbQALbNhUjJrL6sXcRspfzoDyltkKLNezzN1XbtGlrscH0tlrLSykUtoo7tje7ro37p2VLtTxrNxT7QkUkIiaEuQjxti9EsmJiLEZbt/q0tPoaRR9iuEF7sgdkrRtaoYCjucxksvyxtaYks8cqtgz7uF7ruPCqs3F7tiLqQsIbQJoLtFIbt7MDunTrsaN7t0ybup57vNE7Ou6DtK3+O7LF+zbg+ruIizm6O6zfe7uLm7uACrF0C7zBez1xRLwutJ8DwbnBi7S+U7TLK792a3ClG7/PWrKCK7/CC7v8cb0DBcBiQ7u5YcCwhLszO74Gy7sODLkSJLGUa7V1ZEQjBD5uy6+bW7+UM7qFhbcaHKv3ejj/a7ra60Ew+6vh+6krHKwKLL7lG8GTmxvS+hBDOx3MC1AgbMPdOsL7hsApXEu2G6ovTMQtTKhHXE4GLME07KoCsywBI7o6LKlPXCxRbMUAw7LM8y9nGqZP2rXgC7YNzLhkTL6Fmhn9MsMBbEnPlMN35buQCkb6Fsd0PB4MDMNmPMa7q8d5ujHN46ZLgBzIgjzIhFzIhnzIiJzIirzIjNzIjvzIkBzJkjzJhrxTIXnJmNwz7TKmnNzJnqxLHPvJojzKpCw3XnzKqJzKqrzKrNzKrvzKERMQADs= "image\img00002.gif")
# <a name="chmtopic10"></a>**Adding Wrapped Cylindrical to Mill Posts**
## **Information Added or Modified in Mill.LIB**
The following has been added/modified in **Mill.lib**:
1. #### **Attributes Added**
1. Added **WHICH\_AXIS** attribute.
1. Added **CYLINDRICAL** attribute.


2. #### **Attributes Modified**
Modified **DEBUG** attribute to handle main cylindrical sections. 


3. #### **CALC sections Added**
CALC sections listed below have been added:

- **CALC\_RAPID\_MOVE\_MILL\_CYLINDRICAL**
- **CALC\_RAPID\_FROM\_TOOL\_CHANGE\_MILL\_CYLINDRICAL**
- **CALC\_RAPID\_TO\_TOOL\_CHANGE\_MILL\_CYLINDRICAL**
- **CALC\_RAPID\_Z\_UP\_MILL\_CYLINDRICAL**
- **CALC\_RAPID\_Z\_MOVE\_UP\_LEN\_COMP\_MILL\_CYLINDRICAL**
- **CALC\_RAPID\_Z\_DOWN\_MACRO\_CYLINDRICAL**
- **CALC\_FIRST\_RAPID\_Z\_PRELOAD\_DOWN\_MILL\_CYLINDRICAL**
- **CALC\_FIRST\_RAPID\_Z\_MOVE\_DOWN\_MILL\_CYLINDRICAL**
- **CALC\_FEED\_Z\_MOVE\_DOWN\_MILL\_CYLINDRICAL**
- **CALC\_LINE\_MOVE\_MILL\_CYLINDRICAL**
- **CALC\_LINE\_LEADOUT\_MOVE\_CYLINDRICAL**
- **CALC\_LINE\_LEADIN\_MOVE\_CYLINDRICAL**
- **CALC\_ARC\_MOVE\_MILL\_CYLINDRICAL**
- **CALC\_BREAK\_ARC\_CYLINDRICAL**
- **CALC\_RADIAL\_ARCS\_CYLINDRICAL**
- **CALC\_DO\_MACRO\_CALL\_MILL\_WRAPPED**
- **CALC\_DO\_MACRO\_CALL\_WORK\_COORD\_MILL\_WRAPPED**
- **CALC\_CYLINDRICAL**


4. #### **CALC Sections Modified**
CALC sections listed below have been modified:

- **CALC\_RAPID\_Z\_DOWN\_MILL**
- **CALC\_RAPID\_Z\_UP\_MILL**
- **CALC\_RAPID\_MOVE\_MILL**
- **CALC\_FEED\_Z\_MILL**
- **CALC\_LINE\_MOVE\_MILL**
- **CALC\_ARC\_MOVE\_MILL**
- **CALC\_START\_OPERATION**
- **CALC\_DO\_MACRO\_CALL\_MILL**
- **CALC\_DO\_MACRO\_CALL\_WORK\_COORD\_MILL**


## **Information needed in SRC file for Adding Wrapped Cylindrical to Mill Posts**
1. #### **Header command required**
Header  command **":MILL\_OD\_CYLINDRICAL=TRUE"**


2. #### **Line to be added**
Added this line in **CALC\_INIT\_CODES ":C: CYLINDRICAL=999"**


3. #### **Added Below Template Sections**
- **RAPID\_MOVE\_MILL\_CYLINDRICAL**
- **RAPID\_LEADOUT\_MOVE\_MILL\_CYLINDRICAL**
- **RAPID\_LEADIN\_MOVE\_MILL\_CYLINDRICAL**
- **RAPID\_FROM\_TOOL\_CHANGE\_MILL\_CYLINDRICAL**
- **RAPID\_Z\_MOVE\_UP\_MILL\_CYLINDRICAL**
- **LAST\_RAPID\_Z\_MOVE\_UP\_MILL\_CYLINDRICAL**
- **FIRST\_RAPID\_Z\_MOVE\_DOWN\_MILL\_CYLINDRICAL**
- **RAPID\_Z\_MOVE\_DOWN\_MILL\_CYLINDRICAL**
- **FEED\_Z\_MOVE\_DOWN\_MILL\_CYLINDRICAL**
- **LINE\_MOVE\_MILL\_CYLINDRICAL**
- **LINE\_LEADIN\_MOVE\_CYLINDRICAL**
- **LINE\_LEADOUT\_MOVE\_CYLINDRICAL**
- **ARC\_MOVE\_MILL\_CYLINDRICAL**
- **RADIUS\_MOVE\_MILL\_CYLINDRICAL**
- **CYLINDRICAL\_ON**
- **CYLINDRICAL\_OFF**
- **ROTATE\_X\_CYLINDRICAL**
- **ROTATE\_Y\_CYLINDRICAL**
- **ROTATE\_X\_WRAPPED**
- **ROTATE\_Y\_WRAPPED**
- **ROTATE\_MULTIAXIS**


4. #### **Optional Template Sections**
Following are the optional template sections:

- **RAPID\_LEADOUT\_TO\_TOOL\_CHANGE\_MILL\_CYLINDRICAL**
- **MACRO\_RAPID\_CALL\_MILL\_CYLINDRICAL**
- **RAPID\_Z\_MOVE\_UP\_LEN\_COMP\_MILL\_CYLINDRICAL**
- **LAST\_RAPID\_Z\_MOVE\_UP\_LEN\_COMP\_MILL\_CYLINDRICAL**
- **FIRST\_RAPID\_Z\_PRELOAD\_DOWN\_MILL\_CYLINDRICAL**
- **RAPID\_Z\_MOVE\_DOWN\_LEN\_COMP\_MILL\_CYLINDRICAL**
- **FEED\_Z\_MOVE\_DOWN\_LEN\_COMP\_MILL\_CYLINDRICAL**
- **FIRST\_FEED\_Z\_DOWN\_MILL\_CYLINDRICAL**
# <a name="chmtopic2"></a>**Supporting Probing Cycles in Mill-Turn Posts**
From *CAMWorks 2021* version onwards, the support for Probing Cycles has been extended to Mill-Turn post processors in addition to the existing Mill post processors.

Details of the necessary coding to be added in Mill-Turn Post Processors are given below:


## **1.**     **Add Probing Header Command in Header section of Post**
Add the header command **ALLOW\_PROBING** in the header section of Mill-Turn post to enable support for Probe Cycles.

**: ALLOW\_PROBING=TRUE**


## **2.**     **Add New Library Command Line in Mill-Turn Post Source Files**
Add the new library command line for MILLTURN\_PROBE.LIB in Mill-Turn Post Source files. MILLTURN\_PROBE.LIB is located in the same  directory as MILLTURN.LIB, viz.:

**C:\CAMWorksData\UPG-2\MasterLibraryFiles**

The main advantage of this method is that your existing lib file doesn’t need to be edited. Also, the MILLTURN\_PROBE.LIB can be referred in various other lib files. It is important to ensure that MILLTURN\_PROBE.LIB is the first lib in the list of lib files.

**:LIBRARY=PATH\MILLTURN\_PROBE.LIB**

**:LIBRARY=PATH\POST-LIBRARY-FILE.LIB**

**:LIBRARY=PATH\MILLTURN.LIB**


## **3.   Add New Attribute Names**
Add the following attribute names. These are to be defined in MILLTURN.LIB and MILLTURN\_PROBE.LIB.

**:ATTRNAME=DEBUG PROBE**

**:ATTRNAME=PROBE ERROR**

**:ATTRNAME=P**


## **4.**     **Adding Probe CALC Section in Post Library**
New Calc sections are needed to support Mill-Turn. These are to be defined in MILLTURN.LIB and MILLTURN\_PROBE.LIB. Alternatively, they can be added to your post LIB file.

- CALC\_LINE\_MOVE\_PROBE\_MILL
- CALC\_LINE\_MOVE\_PROBE\_MILL\_BAXIS
- CALC\_LINE\_MOVE\_OD\_FIXED\_PROBE
- CALC\_LINE\_MOVE\_OD\_FREE\_PROBE
- CALC\_LINE\_MOVE\_FACE\_FIXED\_PROBE
- CALC\_LINE\_MOVE\_FACE\_FREE\_PROBE
- CALC\_RAPID\_MOVE\_PROBE\_MILL
- CALC\_RAPID\_MOVE\_BAXIS\_PROBE
- CALC\_RAPID\_MOVE\_OD\_FIXED\_PROBE
- CALC\_RAPID\_MOVE\_OD\_FREE\_PROBE
- CALC\_RAPID\_MOVE\_FACE\_FIXED\_PROBE
- CALC\_RAPID\_MOVE\_FACE\_FREE\_PROBE
- CALC\_RAPID\_Z\_UP\_PROBE\_MILL
- CALC\_RAPID\_UP\_BAXIS\_PROBE
- CALC\_RAPID\_X\_UP\_OD\_FIXED\_PROBE
- CALC\_RAPID\_X\_UP\_OD\_FREE\_PROBE
- CALC\_RAPID\_Z\_UP\_FACE\_FIXED\_PROBE
- CALC\_RAPID\_Z\_UP\_FACE\_FREE\_PROBE
- CALC\_RAPID\_Z\_DOWN\_PROBE\_MILL
- CALC\_RAPID\_DOWN\_BAXIS\_PROBE
- CALC\_RAPID\_X\_DOWN\_OD\_FIXED\_PROBE
- CALC\_RAPID\_X\_DOWN\_OD\_FREE\_PROBE
- CALC\_RAPID\_Z\_DOWN\_FACE\_FIXED\_PROBE
- CALC\_RAPID\_Z\_DOWN\_FACE\_FREE\_PROBE
- CALC\_FEED\_Z\_PROBE\_MILL
- CALC\_FEED\_DOWN\_BAXIS\_PROBE
- CALC\_FEED\_X\_OD\_FIXED\_PROBE
- CALC\_FEED\_X\_OD\_FREE\_PROBE
- CALC\_FEED\_Z\_FACE\_FIXED\_PROBE
- CALC\_FEED\_Z\_FACE\_FREE\_PROBE
- CALC\_FEED\_Z\_PROBE\_UP\_MILL
- CALC\_OUTPUT\_PROBE\_CYCLE\_MILL


## **5.**     **Adding Probe Template Section in Mill-Turn Post Source**
Following new template sections are required SRC (Mill-Turn Post Source files). These will be available in the latest Mill-Turn tutorial posts.

- RAPID\_FROM\_TC\_BAXIS\_PROBE
- RAPID\_FROM\_TC\_OD\_FIXED\_PROBE
- RAPID\_FROM\_TC\_OD\_FREE\_PROBE
- RAPID\_FROM\_TC\_FACE\_FIXED\_PROBE
- RAPID\_FROM\_TC\_FACE\_FREE\_PROBE
- RAPID\_MOVE\_BAXIS\_PROBE
- RAPID\_OD\_FIXED\_PROBE
- RAPID\_OD\_FREE\_PROBE
- RAPID\_FACE\_FIXED\_PROBE
- RAPID\_FACE\_FREE\_PROBE
- RAPID\_UP\_BAXIS\_PROBE
- RAPID\_X\_UP\_OD\_FIXED\_PROBE
- RAPID\_X\_UP\_OD\_FREE\_PROBE
- RAPID\_Z\_UP\_FACE\_FIXED\_PROBE
- RAPID\_Z\_UP\_FACE\_FREE\_PROBE
- LAST\_RAPID\_UP\_BAXIS\_PROBE
- LAST\_RAPID\_X\_UP\_OD\_FIXED\_PROBE
- LAST\_RAPID\_X\_UP\_OD\_FREE\_PROBE
- LAST\_RAPID\_Z\_UP\_FACE\_FIXED\_PROBE
- LAST\_RAPID\_Z\_UP\_FACE\_FREE\_PROBE
- FIRST\_RAPID\_DOWN\_BAXIS\_PROBE
- FIRST\_RAPID\_X\_DOWN\_OD\_FIXED\_PROBE
- FIRST\_RAPID\_X\_DOWN\_OD\_FREE\_PROBE
- FIRST\_RAPID\_Z\_DOWN\_FACE\_FIXED\_PROBE
- FIRST\_RAPID\_Z\_DOWN\_FACE\_FREE\_PROBE
- RAPID\_DOWN\_BAXIS\_PROBE
- RAPID\_X\_DOWN\_OD\_FIXED\_PROBE
- RAPID\_X\_DOWN\_OD\_FREE\_PROBE
- RAPID\_Z\_DOWN\_FACE\_FIXED\_PROBE
- RAPID\_Z\_DOWN\_FACE\_FREE\_PROBE
- FEED\_DOWN\_BAXIS\_PROBE
- FEED\_X\_OD\_FIXED\_PROBE
- FEED\_X\_OD\_FREE\_PROBE
- FEED\_Z\_FACE\_FIXED\_PROBE
- FEED\_Z\_FACE\_FREE\_PROBE
- FEED\_Z\_PROBE\_UP\_BAXIS
- FEED\_X\_UP\_OD\_FIXED\_PROBE
- FEED\_X\_UP\_OD\_FREE\_PROBE
- FEED\_X\_UP\_FACE\_FIXED\_PROBE
- FEED\_X\_UP\_FACE\_FREE\_PROBE
- LINE\_MOVE\_PROBE\_MILL\_BAXIS
- LINE\_OD\_FIXED\_PROBE
- LINE\_OD\_FREE\_PROBE
- LINE\_FACE\_FIXED\_PROBE
- LINE\_FACE\_FREE\_PROBE
- PROBE\_SURFACE\_X\_TOOLPATH
- PROBE\_SURFACE\_Y\_TOOLPATH
- PROBE\_SURFACE\_Z\_TOOLPATH
- PROBE\_WEB\_X\_TOOLPATH
- PROBE\_WEB\_Y\_TOOLPATH
- PROBE\_POCKET\_X\_TOOLPATH
- PROBE\_POCKET\_Y\_TOOLPATH
- PROBE\_ISLAND\_POCKET\_X\_TOOLPATH
- PROBE\_ISLAND\_POCKET\_Y\_TOOLPATH
- PROBE\_BOSS\_TOOLPATH
- PROBE\_BORE\_TOOLPATH
- PROBE\_ISLAND\_BORE\_TOOLPATH
- PROBE\_3POINT\_BOSS\_TOOLPATH
- PROBE\_3POINT\_BORE\_TOOLPATH
- PROBE\_3POINT\_ISLAND\_BORE\_TOOLPATH
- DEBUG\_PROBE
- OUTPUT\_PROBE\_ERROR  
# <a name="chmtopic2186"></a>**Header Errors**

|**Sr. No.**|**Error Message**|**Reason Behind Error Message**|**Posts in which Message is Displayed**|
| :- | :- | :- | :- |
|1\.|NO\_LENGTH\_DIAM\_OFFSETS|:LENGTH\_DIAM\_OFFSET\_FROM\_TOOL=FALSE or Post Header does not exist.|Mill posts|
|2\.|EXCEEDED\_X\_MINUS\_LIMIT |:FACE\_MILL=FIXED\_OR\_X+\_ONLY - Feature is greater than 180 degrees |MillTurn posts|
|3\.|GUN\_DRILLING\_NOT\_SUPPORTED|:ALLOW\_GUN\_DRILLING=FALSE or post header does not exist.|Mill and MillTurn posts|
|4\.|PROBING\_NOT\_SUPPORTED |:ALLOW\_PROBING=FALSE or post header does not exist. |Mill posts|


# <a name="chmtopic2188"></a>**CALC Section Errors**

|**Sr. No.**|**Error Message**|**Reason Behind Error Message**|**Posts in which Message is Displayed**|
| :- | :- | :- | :- |
|1\.|NO\_SPEED\_SLOWDOWN|No :SECTION=CALC\_SLOWDOWN\_SPEED Found|Turning and MillTurn posts|
|2\.|NO\_TOOL\_SHIFT |No :SECTION=CALC\_SHIFT\_TOOL\_LATHE Found |Turning and MillTurn posts|
|3\.|NO\_CUTTER\_COMP|No :SECTION=CALC\_CUTTER\_COMP\_LATHE Found|Turning and MillTurn posts|
|4\.|NO\_OUTPUT\_FEEDRATE\_CHANGE |No :SECTION=CALC\_OUTPUT\_FEEDRATE for Sub Spindle Operation |Turning and MillTurn posts|
|5\.|NO\_OUTPUT\_CLAMP\_OPEN\_CLOSE|No :SECTION=CALC\_OUTPUT\_CHUCK\_OPEN or :SECTION=CALC\_OUTPUT\_CHUCK\_CLOSE for Sub Spindle Operation|Turning and MillTurn posts|
|6\.|NO\_OUTPUT\_SPINDLE\_ORIENT|No :SECTION=CALC\_OUTPUT\_SPINDLE\_ORIENTATION for Sub Spindle Operation |Turning and MillTurn posts|
|7\.|NO\_OUTPUT\_RAPID\_SPINDLE\_TO\_POSITION|No :SECTION=CALC\_OUTPUT\_RAPID\_SPINDLE\_TO\_POSITION for Sub Spindle Operation|Turning and Millturn posts|
|8\.|NO\_OUTPUT\_FEED\_SPINDLE\_TO\_POSITION|No :SECTION=CALC\_OUTPUT\_FEED\_SPINDLE\_TO\_POSITION for Sub Spindle Operation|Turning and MillTurn posts|
|9\.|NO\_OUTPUT\_SPEED\_CHANGE|No :SECTION=CALC\_CHANGE\_MILL\_SPEED|Mill and MillTurn posts|


# <a name="chmtopic2190"></a>**Multiaxis Errors**

|**Sr. No.**|**Error Message**|**Reason Behind Error Message**|**Posts in which Message is Displayed**|
| :- | :- | :- | :- |
|1\.|5AXIS\_NOT\_SUPPORTED|No KIN file present for selected post.|Mill posts|


## <a name="chmtopic11"></a>**MACH\_IS\_4TH\_AXIS\_REV\_DIR**

|***Type***|INTEGER|
| :- | :- |
|***Usage***|Stores whether the reverse checkbox has been checked in the Rotary tab of the Machine dialog box in the CAMWorks user interface. To be used in CAMWorks 2020 SP1 or higher versions.|
|***Syntax***|MACH\_IS\_4TH\_AXIS\_REV\_DIR=TRUE or FALSE |


## <a name="chmtopic12"></a>**MACH\_IS\_5TH\_AXIS\_REV\_DIR**

|***Type***|INTEGER|
| :- | :- |
|***Usage***|Stores whether the reverse checkbox has been checked in the Tilt tab of the Machine dialog box in the CAMWorks user interface. To be used in CAMWorks 2020 SP1 or higher versions.|
|***Syntax***|MACH\_IS\_5TH\_AXIS\_REV\_DIR=TRUE or FALSE |


