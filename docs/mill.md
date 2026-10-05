<a name="chmtopic4"></a>**Welcome to UPG Online Help\
\
The Universal Post Generator allows to you to customize mill post processors for both basic and complex code generation requirements.**
=======================================================================================================================================
# ![image\do-it.gif]** In order to learn how to use the UPG, we recommend you read the topics in the **[Getting Started](#chmtopic2)** book. The information and the exercises in Getting Started will help you understand the process of customizing a post processor. Then, go through the topics in** the **[CAMWorks: Learning by Example](#chmtopic3)** book. These topics provide step-by-step exercises.
# ![image\do-it.gif]** Use the Contents, Index and Search tabs on the left to quickly find the information you need.
# ![image\do-it.gif]** In general, the information in the online help applies to post processors for CAMWorks.
# <a name="chmtopic6"></a>**UPG Overview**


CAMWorks uses a post processor to convert information into machine tool specific NC code. Each post processor is designed to generate quality NC code that meets the requirements of the machine control. The UPG allows you to customize the post processor for both basic and complex code generation requirements. With the flexible and easy-to-use interface, you can configure the post processor to output NC code that conforms to your production methods or that supports sophisticated controls.



The UPG allows you to change:

- The G code that is generated when a part is post processed in CAMWorks.
- Parameters on the Posting tab in the CAMWorks Machining Parameters dialog box.
## **Features**
- Pre-defined defaults for common control types minimize the configuration necessary.
- Similar controls can be configured using a copy of a customized template.
- Easily set up the sequence of events for functions such as tool changes, rapids, start and end of tape, system cycles, canned cycles, etc.
- Quickly compile, debug and test the code.

![image\pin_bl.gif] Some of the information in this help document is specific to Fanuc and Fanuc compatible controllers and may not apply to other controllers.
# <a name="chmtopic2"></a>**Steps to Customize a Post Processor**
The following steps are used to generate a customized post processor:

1. [Open the database template](#chmtopic8) to be used to create the post source.
1. [Modify the template](#chmtopic9) by changing parameters, add sections of Post Processor Language code, etc.
1. [Save the changes](#chmtopic10) in a post source file.
1. [Compile the post source](#chmtopic11) into an executable post processor.
1. [Post process](#chmtopic12) a part in CAMWorks to check the code output.

The next series of exercises show you how to create a finished post processor using the Universal Post Generator (UPG). As you create the post processor, you will follow steps that are not explained in depth. This is done to show you the basics of generating a post processor from start to finish without getting into the details at this time.

` `Click the Next ![ref1] button at the top of the window to go to the [exercise for step 1](#chmtopic8).


# <a name="chmtopic8"></a>**Step 1: Open Database Template**
This topic begins a series of exercises that explain the [steps to customize a post processor](#chmtopic2).

The UPG creates a post processor from a source file that uses Post Processor Language code to define:

- all the capabilities of a machine/controller.
- a generalized format for outputting complete G code part programs.

A source file is created by modifying the defaults for a specific machine/controller.
#### **Exercise**
1. Click the New Source button on the toolbar.

![image\tbbuttons-new.gif](data:image/gif;base64,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 "image\tbbuttons-new.gif")

New Source



In addition to clicking the New Source button, you can click New on the File menu or use the shortcut key, ctrl + n. The Controller selection parameters display.



![image\pin_bl.gif] The Controller parameters display only when you are creating a new source. When you open an existing source file, the Machine tab displays.

2. Select Mill from the Machine Type list.

This defines the new post as a mill post processor and displays the mill type controllers in the Controller Type list.

3. Select Fanuc from the Controller Type list.

This selection defines the new post processor as a Fanuc controller and the Controller Name list displays the Fanuc controllers that can be accessed.

4. Select Generic Fanuc in the Controller Name list and click OK.

The UPG opens the Generic Fanuc database template and the Machine tab displays.
# <a name="chmtopic9"></a>**Step 2: Modify Database Template**
This topic is a continuation of the series of exercises that explain the [steps to customize a post processor](#chmtopic2).

Now that you have opened the database template for a Generic Fanuc, you will modify some of the post parameters to get an understanding of how the Universal Post Generator (UPG) works.
## **Change Controller Information**
**Machine Tab**

The Machine tab allows you to change information about the controller. This information is for reference only and does not affect the output of the code.

In CAMWorks, the he controller information entered in the Machine tab displays on the Controller tab in the Machine dialog box.


## **Change the Controller Information**
#### **Exercise**
1. Type **LEADWELL** in the Machine Name text box.
1. Type **FANUC 11MF** in the Controller Name text box.
1. Type **40** in the Z Home text box.
1. Type **300** in the Traverse Rate text box.

As you type, notice that the information in the Machine Code window is changing. This window displays the Post Processor Language to achieve the changes you are typing. For example, when you type LEADWELL for the Machine Name, ATTRDEFAULT= GENERIC changes to ATTRDEFAULT= LEADWELL in the window.

It is not necessary that you understand this code. The code may be of interest to advanced users who plan to modify the source file after initially using the UPG to customize the post processor.
## **Change Sequence Number Format**
#### **Exercise**
Change the sequence number format to see the effect it has on the post processor G code output:

1. Click the Misc. tab. The Misc. tab allows you to change general information about the controller including how sequence numbers are formatted in the G code output.
1. In the Sequence Output group, change the sequence output from Floating Seq. Numbers to Three Place Seq. Numbers.
1. Change the Starting Seq. Number from 1 to 5.
1. Change the Seq. Increment from 1 to 10.

![image\btn-help.gif](data:image/gif;base64,R0lGODlhGgAYAPcAAAAAAAEBAQICAgMDAwQEBAUFBQYGBgcHBwgICAkJCQoKCgsLCwwMDA0NDQ4ODg8PDxAQEBERERISEhMTExQUFBUVFRYWFhcXFxgYGBkZGRoaGhsbGxwcHB0dHR4eHh8fHyAgICEhISIiIiMjIyQkJCUlJSYmJicnJygoKCkpKSoqKisrKywsLC0tLS4uLi8vLzAwMDExMTIyMjMzMzQ0NDU1NTY2Njc3Nzg4ODk5OTo6Ojs7Ozw8PD09PT4+Pj8/P0BAQEFBQUJCQkNDQ0REREVFRUZGRkdHR0hISElJSUpKSktLS0xMTE1NTU5OTk9PT1BQUFFRUVJSUlNTU1RUVFVVVVZWVldXV1hYWFlZWVpaWltbW1xcXF1dXV5eXl9fX2BgYGFhYWJiYmNjY2RkZGVlZWZmZmdnZ2hoaGlpaWpqamtra2xsbG1tbW5ubm9vb3BwcHFxcXJycnNzc3R0dHV1dXZ2dnd3d3h4eHl5eXp6ent7e3x8fH19fX5+fn9/f4CAgIGBgYKCgoODg4SEhIWFhYaGhoeHh4iIiImJiYqKiouLi4yMjI2NjY6Ojo+Pj5CQkJGRkZKSkpOTk5SUlJWVlZaWlpeXl5iYmJmZmZqampubm5ycnJ2dnZ6enp+fn6CgoKGhoaKioqOjo6SkpKWlpaampqenp6ioqKmpqaqqqqurq6ysrK2tra6urq+vr7CwsLGxsbKysrOzs7S0tLW1tba2tre3t7i4uLm5ubq6uru7u7y8vL29vb6+vr+/v8DAwMHBwcLCwsPDw8TExMXFxcbGxsfHx8jIyMnJycrKysvLy8zMzM3Nzc7Ozs/Pz9DQ0NHR0dLS0tPT09TU1NXV1dbW1tfX19jY2NnZ2dra2tvb29zc3N3d3d7e3t/f3+Dg4OHh4eLi4uPj4+Tk5OXl5ebm5ufn5+jo6Onp6erq6uvr6+zs7O3t7e7u7u/v7/Dw8PHx8fLy8vPz8/T09PX19fb29vf39/j4+Pn5+fr6+vv7+/z8/P39/f7+/v///yH5BAAAAAAALAAAAAAaABgAAAiwAH8JHEiwoEGD/xIqXMiwYUIAAv99m0ixosWLfyD+kniwY8GMEb95HPkL5EaRvzQabMCS5Z+BJjmmVDmQpcA/Lm9qlAmgJ8GcAlvqDCmwp8+gDV4ibTD0ZFGjGnEyLQk0JkqoR38mhbnzKlaaNglaffoVqVKuRGcaLQgUrdOZcEmW7Fp0YNZfQsXSLXg3r1uZfGkeHGvw7uC9cg0STvxx55/HkCNLnmzyq+XLaxnLDQgAOw== "image\btn-help.gif") If you need a quick reminder of the meaning or function of an option on any of the tabs, click the Help button, then click on the option. An explanation displays. You can print this information by right clicking in the help popup window and selecting Print Topic on the shortcut menu.
# <a name="chmtopic10"></a>**Step 3: Save Post Source**
This topic is a continuation of the series of exercises that explain the [steps to customize a post processor](#chmtopic2).

When the modifications are completed, you need to save the changes in a post source file before you compile.
#### **Exercise**
Save a post source file:

1. Click Save Source As on the File menu. The Save File As dialog box displays.
1. Open the \millsrc folder. You can save the source in any folder.
1. Save the source as **CW\_MPOST2** (CAMWorks). The program automatically adds a .SRC extension to the file name.
- You can type a unique name or use the default file name. If you use the default name (for example, fanuc6m), a new source file is created. The original database template is not overwritten.
- The title bar in the UPG window changes to the name and path of the new source file
- The UPG saves the source in the file **CW\_MPOST2.SRC**. If you needed to make changes to this post after saving the source, you would click the Open button on the toolbar (or select Open on the File menu) and pick this file.
- An additional library file is created with the same name and a .LIB extension (CW\_MPOST.LIB). This file contains information required by the UPG for compiling the post processor.

![image\pin_bl.gif] If you are customizing posts for similar controls, you can use the Save As command to save a copy of an existing source file under a different file name. The original file is retained and you can customize the new source file for the similar control.
# <a name="chmtopic11"></a>**Step 4: Compile Post Source**
This topic is a continuation of the series of exercises that explain the [steps to customize a post processor](#chmtopic2).
#### **Exercise**
1. Click Compile Post on the File menu. The Compile Post dialog box displays.
1. Make sure **CW\_MPOST2.SRC** is selected, then click OK.
- A message displays indicating that the post is being compiled.
- The UPG compiles the post and generates 2 files:

CW\_MPOST2.CTL - the executable post file that is run when you pick the controller in the CAM system.

CW\_MPOST2.LGN - the language file containing the post parameters and terms.

- The post processor files generated by the UPG are saved automatically in the \posts folder. This is the folder that contains the post processor files for your CAMWorks system. The \posts folder is located under the main CAMWorks folder.
2. When the compiler finishes, a message displays to indicate that the source was compiled successfully.

If errors are detected, a message displays asking if you want to view the errors. If you click Yes, the errors display in Notepad. The errors are also saved in an ERRORS.TXT file in the \millsrc folder.
# <a name="chmtopic12"></a>**Step 5: Post Process Part in CAM**
This topic is the last of the series of exercises that explain the [steps to customize a post processor](#chmtopic2).

After modifying a post processor, you need to test the changes by post processing a part in either ProCAM or CAMWorks.
#### **Exercise**
1. In SolidWorks, open the part file CW\_MPOST2.SLDPRT.

When you install the UPG, the CAMWorks parts for the exercises in this help file are automatically installed in the \cw examples folder inside the folder where you installed the UPG.

2. Click the CAMWorks Feature Tree button at the bottom of the tree.
2. Right click on Mill Machine – Inch in the tree and select Parameters on the shortcut menu. The Machine dialog box displays.
2. Click the Controller tab.
2. Select CW\_MPOST2 in the list of post processors. Notice the Current Information corresponds to the information you entered on the UPG Machine tab.
2. Click the Select button.
2. Click OK.
2. Click the Post Process button on the CAMWorks toolbar.

View the changes in the code. The sequence numbers start at N005 and increment by 10.

O0001

N005 G17 G20 G40 G80

N015 (1/2 COBALT JOBBER DRILL)

N025 T01 M06

N035 S1500 M03

N045 G54

N055 M08

N065 G90 G00 X0 Y0

N075 G43 Z.1 H01

N085 G81 G99 R.1 Z-1.2001 F8.

N095 G80 Z1. M09

N105 G91 G28 Z0

N115 (E, 1/4 COBALT JOBBER DRILL)

N125 T02 M06

N135 S1500 M03

N145 G54

N155 M08

N165 G90 X-1. Y-1.

N175 G43 Z.1 H02

N185 G81 G99 R.1 Z-1.125 F8.

N195 G80 Z1. M09

N205 G91 G28 Z0

N215 G28 X0 Y0

N225 M30
# <a name="chmtopic19"></a>**File Menu**
The File menu contains the commands for managing files in the UPG.
## **New**
Open a database template to use for creating the post source.
## **Close**
Close the current source. If there are unsaved changes in the source, you will be asked if you want to save them.
## **Open**
Open an existing source file. Only source files created using the UPG can be opened.
## **Save Source**
Save changes to the current source.
## **Save Source As**
Name and save the source in a new file. This option allows you to save the customized source to a new file. The original source file is retained. Similar controls can be configured using a copy of a customized source file.
## **Delete**
Delete a source file. This option allows you to remove source files from your hard drive when they are no longer needed.
## **Compile Source**
Compile the post source. All CAMWorks source files can be compiled using this option including source files that have been created using a text editor instead of the UPG.
## **Preferences**
Set preferences used by the UPG.

- Language - Select the language you want the information to display on the tabs.
- CTL Path - Specify the path to the folder where the post processor files are saved when you compile the post source.
- General - Choose the Post Compiler (DOS or Windows)
- Font - Set the font style and size and background/foreground colors used by the UPG
- Master ATR Path - change the path to the master.atr file if necessary.
## **Multiaxis MPS File Editor**
Allows you to customize the MPS file. The MPS file sets up the Machine Simulator posting environment. The parameters in this file should match the CAMWorks post's \*.kin file.
## **Multiaxis Simulator Help**
Opens a PDF file containing directions for editing the Machine Simulator in CAMWorks and the XML file.
## **EDM Post Editor**
Allows you to customize CAMWorks EDM posts.
## **EDM Post Setup**
Allows you to create new CAMWorks EDM posts. This utility adds the information to the registry so that the new post is listed in CAMWorks. Posts created using this utility can be edited using the EDM Post Editor.
## **EDM Editor Help**
Reserved for future implementation.
## **EC Post Editor**
Allows you to fully customize CAMWorks mill, turn and mill/turn posts.  
## **Exit**
Exit the UPG. If you have an open file with unsaved changes, you will be prompted to save the file.
# <a name="chmtopic3"></a>**CAMWorks: Learning by Example**


The topics in this section provide an opportunity to learn how to customize a post processor through step-by-step exercises.

Click the Next ![ref1]  button or the Browse buttons at the top of the topic windows to go through the series of exercises.

When you install CAMWorks, the parts for the exercises in this section are installed automatically in the \cw examples inside the folder where you installed the UPG (e.g., upg\cw examples).

For more detailed information about a particular function, see the applicable topic.

![image\pin_bl.gif] Before you do any of the exercises in this section, make sure you read the topics in the [Getting Started](#chmtopic2) book. The information and the exercises in these topics will help you understand the process of customizing a post processor and you will be able to learn more from the exercises.
# <a name="chmtopic22"></a>**CAMWorks Exercise: Number Format**
#### **Exercise**
Change the format for floating point numbers (Decimal and Metric) and integers that are output:

1. Start the UPG and open the Generic Fanuc post.
1. Click the Header tab and make the following changes:
- Check the Floating Point Leading Zeros check box.
- Check the Floating Point Trailing Zeros check box.
- Uncheck the Integer Leading Zeros check box.
- Change Left Places to 4.
- Change Right Places to 5.
- Change Metric Place Shift to 2.
3. Save the source as CW\_MPOST3 and compile.
3. In SolidWorks, open the part file CW\_MPOST3.SLDPRT. When you install the UPG, the parts for the exercises are automatically installed in the \cw examples folder inside the folder where you installed the UPG (e.g., upg\cw examples). This part was saved with the Linear units set to Inches.
3. Change to the CAMWorks Operation tree.
3. Post process the part and review the output. Notice you have floating point leading and trailing zeros with 4 places to the left of the decimal and 5 places to the right.
3. Click Tools on the SolidWorks menu bar and select Options.
3. Click the Document Properties tab.
3. Select Units in the navigation tree and change the Linear units to Millimeters, then click OK.
3. Post process the part again and review the output. Notice that numbers have floating point leading and trailing zeros with 6 places to the left of the decimal and 3 places to the right because Metric Place Shift is set to 2.

   ![image\pin_bl.gif] Typically, if you are converting the units of a part for machining, you would also want to change the machine so that the tools would be correct. For more information on converting part units for machining, see the CAMWorks online help.


## **Code Output Changes for Decimal Units and Integers**
O0001

N1 G17 G20 G40 G80

N2 (1/2 COBALT JOBBER DRILL)

N3 T1 M6

N4 S1500 M3

N5 G54

N6 M8

N7 G90 G0 X0002.00000 Y0002.00000

N8 G43 Z0000.10000 H01

N9 G81 G99 X0002.00000 Y0002.00000 R0000.10000 Z-0001.20008 F0008.00000

N10 G80 Z0001.00000 M9

N11 G91 G28 Z0

N12 (E, 1/4 COBALT JOBBER DRILL)

N13 T2 M6

N14 S1500 M3

N15 G54

N16 M8

N17 G90 X0001.00000 Y0001.00000

N18 G43 Z0000.10000 H02

N19 G81 G99 R0000.10000 Z-0001.12504 F0008.00000

N20 G80 Z0001.00000 M9

N21 G91 G28 Z0

N22 G28 X0 Y0

N23 M30


## **Code Output Changes for Metric Units and Integers**
O0001

N1 G17 G21 G40 G80

N2 (1/2 COBALT JOBBER DRILL)

N3 T1 M6

N4 S1500 M3

N5 G54

N6 M8

N7 G90 G0 X000050.800 Y000050.800

N8 G43 Z000002.540 H01

N9 G81 G99 X000050.800 Y000050.800 R000002.540 Z-000030.482 F000203.200

N10 G80 Z000025.400 M9

N11 G91 G28 Z0

N12 (E, 1/4 COBALT JOBBER DRILL)

N13 T2 M6

N14 S1500 M3

N15 G54

N16 M8

N17 G90 X000025.400 Y000025.400

N18 G43 Z000002.540 H02

N19 G81 G99 R000002.540 Z-000028.576 F000203.200

N20 G80 Z000025.400 M9

N21 G91 G28 Z0

N22 G28 X0 Y0

N23 M30
# <a name="chmtopic24"></a>**CAMWorks Exercise: Spaces Between Code and Line Length**

#### **Exercise**
Change the post source to output spaces between code blocks and limit the length of output lines:

1. Start the UPG and open the Generic Fanuc post.
1. Click the Header tab.
1. In the Miscellaneous group:
- Uncheck Spaces Between Commands
- Change Maximum Line Length to 11
4. Save the source as CW\_MPOST6 and compile.
4. In SolidWorks, open the part file CW\_MPOST6.SLDPRT. This part is in the \cw examples folder inside the folder where you installed the UPG.
4. Change to the CAMWorks Operation tree.
4. Post process the part and review the output. Notice that the output lines are a maximum of 11 characters long and there are no spaces between commands.
## **Code Output for Spaces Between Code and Line Length**
O0001

N1G17G20G40G80

N2 (3/8 2 FLUTE HSS EM)

N3T14M06

N4S2500M03

N5G54

N6M08

N7G90G41D34G00

X-1.6875Y0

N8G43Z.1H14

N9G01Z-.5F10.

N10G02X1.6875

R-1.6875F30.

N11X-1.6875R-1.6875

N12G00Z.1

N13G01Z-.5F10.

N14Z-1.

N15G02X1.6875

R-1.6875F30.

N16X-1.6875R-1.6875

N17G00Z.1

N18Z1.

N19G40X-1.6875

Y0

N20G41D34X-2.1875

Y0

N21Z.1

N22G01Z-1.5F10.

N23G02X2.1875

R-2.1875F30.

N24X-2.1875R-2.1875

N25G00Z.1

N26G01Z-1.5F10.

N27Z-2.

N28G02X2.1875

R-2.1875F30.

N29X-2.1875R-2.1875

N30G00Z.1

N31Z1.M09

N32G40X-2.1875

Y0

N33G91G28Z0

N34G28X0Y0

N35M30
# <a name="chmtopic26"></a>**CAMWorks Exercise: Sequence Number Format, Starting Number and Increment**
#### **Exercise**
Start the UPG and open the Generic Fanuc post.

1. Click the Misc. tab.
1. In the Sequence group:
- Pick Three Place Seq. Numbers
- Type **5** for the Starting Seq. Number
- Type **10** for the Seq. Increment
3. Save the source as CW\_MPOST9 and compile.
3. In SolidWorks, open the part file CW\_MPOST9.SLDPRT. This part is in the \cw examples folder inside the folder where you installed the UPG.
3. Change to the CAMWorks Operation tree.
3. Post process the part and review the output. Notice that the first sequence number is 5, the next sequence number is 15 and all sequence numbers have three places.
## **Code with Sequence Number Changes**
O0001

N005 G17 G20 G40 G80

N015 (1/2 COBALT JOBBER DRILL)

N025 T01 M06

N035 S1500 M03

N045 G54

N055 M08

N065 G90 G00 X2. Y2.

N075 G43 Z.1 H01

N085 G81 G99 X2. Y2. R.1 Z-1.2001 F8.

N095 G80 Z1. M09

N105 G91 G28 Z0

N115 (E, 1/4 COBALT JOBBER DRILL)

N125 T02 M06

N135 S1500 M03

N145 G54

N155 M08

N165 G90 X1. Y1.

N175 G43 Z.1 H02

N185 G81 G99 R.1 Z-1.125 F8.

N195 G80 Z1. M09

N205 G91 G28 Z0

N215 G28 X0 Y0

N225 M30
# <a name="chmtopic28"></a>**CAMWorks Exercise: Sequence Number by Tool**
#### **Exercise**
Change the sequence number format to sequence number by tool:

1. Start the UPG and open the Generic Fanuc post.
1. Click the Misc. tab and pick Sequence Number by Tool in the Sequence group.
1. Click the Sections tab and pick Tool in the Section Categories list.
1. Select Init Tool Change in the Section List.
1. In the section code text box, delete <N> from the 2nd line: :T:**<N>**<T><M:06><EOL>.
1. Place the cursor after the :T: and click the Tool Sequence button.

The line reads :T:N<%:TOOL><T><M:06><EOL>.

7. Select Sub Tool Change in the Section List.
7. Repeat steps 5 and 6 to change the 3rd line.
7. Save the source as CW\_MPOST10 and compile.
7. In SolidWorks, open the part file CW\_MPOST10.SLDPRT. This part is in the \cw examples folder inside the folder where you installed the UPG.
7. Change to the CAMWorks Operation tree.
7. Post process the part and review the output. Notice that the sequence numbers are only on the tool line and the sequence number is the same number as the tool.
## **Sample Code with Sequence Numbers by Tool**
O0001

G17 G20 G40 G80

(1" 4 FLUTE HSS EM)

N01 T01 M06

S2500 M03

G54

M08

G90 G00 X0 Y2.5

G43 Z.1 H01

G01 Z-1. F10.

Y4. F30.

G02 X1. Y5. R1.

G01 X4.

G02 X5. Y4. R1.

G01 Y1.

G02 X4. Y0 R1.

G01 X1.

G02 X0 Y1. R1.

G01 Y2.5

G00 Z.1

Z1. M09

G91 G28 Z0

(E, 1/4 COBALT JOBBER DRILL)

N09 T09 M06

S1500 M03

G54

M08

G90 X1. Y1.

G43 Z.1 H09

G81 G99 R.1 Z-1. F5.

Y4.

X4. Y1.

Y4.

G80 Z1. M09

G91 G28 Z0

G28 X0 Y0

M30
# <a name="chmtopic30"></a>**CAMWorks Exercise: Sequence Number by Operation**
#### **Exercise**
Change the sequence number format to sequence number by operation:

1. Start the UPG and open the Generic Fanuc post.
1. Click the Misc. tab.
1. In the Sequence group, pick Sequence Number by Operation.
1. Click the Sections tab and pick Tool in the Section Categories list.
1. Select Init Tool Change in the Section List.
1. In the section code text box, delete <N> from the 2nd line: <N><T><M:06><EOL>.
1. Place the cursor after the :T: and click the Tool Sequence button.

The line reads :T:N<%:CALC\_CHANGE\_TOOL><T><M:06><EOL>.

8. Select Sub Tool Change.
8. Delete <N> from the 3rd line: <N><T><M:06><EOL>.
8. Place the cursor after the :T: and click the Tool Sequence button.

The line reads :T:N<%:CALC\_CHANGE\_TOOL><T><M:06><EOL>.

11. Save the source as CW\_MPOST11 and compile.
11. In SolidWorks, open the part file CW\_MPOST11.SLDPRT. This part is in the \cw examples folder inside the folder where you installed the UPG.
11. Change to the CAMWorks Operation tree.
11. Post process the part and review the output. Notice that the sequence numbers are only on the tool line and they increment by one.
## **Sample Code with Sequence Numbers by Operation**
O0001

G17 G20 G40 G80

(1" 4 FLUTE HSS EM)

N01 T01 M06  { Operation Sequence

S2500 M03

G54

M08

G90 G00 X0 Y2.5

G43 Z.1 H01

G01 Z-1. F10.

Y4. F30.

G02 X1. Y5. R1.

G01 X4.

G02 X5. Y4. R1.

G01 Y1.

G02 X4. Y0 R1.

G01 X1.

G02 X0 Y1. R1.

G01 Y2.5

G00 Z.1

Z1. M09

G91 G28 Z0

(E, 1/4 COBALT JOBBER DRILL)

N02 T02 M06  { Operation Sequence

S1500 M03

G54

M08

G90 X1. Y1.

G43 Z.1 H02

G81 G99 R.1 Z-1. F5.

Y4.

X4. Y1.

Y4.

G80 Z1. M09

G91 G28 Z0

G28 X0 Y0

M30
# <a name="chmtopic32"></a>**CAMWorks Exercise: Arc Output for Center or Radial Format**
#### **Exercise**
Format the arc output for either center or radial format:

To output arcs using Center format:

1. Start the UPG and open the Generic Fanuc post.
1. Click the Header tab.
1. In the Arc group:
- Pick Center – X,Y,I,J
- Change Arc Quadrants to 180 Degrees Max.
4. Save the source as CW\_MPOST4 and compile.
4. In SolidWorks, open the part file CW\_MPOST4.SLDPRT. This part is in the \cw examples folder inside the folder where you installed the UPG.
4. Change to the CAMWorks Operation tree.
4. Post process the part and review the output. Notice the arc centers are now output in X,Y,I,J format.

To output arcs using Radial format:

1. In the Header tab, change the Arc Center to Radial – X, Y, R.
1. Save the source as CW\_MPOST4 and compile.
1. Post process CW\_MPOST4.SLDPRT and review the output.
## **Arc Output Using Center Format**
O0001

N1 G17 G20 G40 G80

N2 (3/8 2 FLUTE HSS EM)

N3 T01 M06

N4 S2500 M03

N5 G54

N6 M08

N7 G90 G00 X-1. Y0

N8 G43 Z.1 H01

N9 G01 Z-1. F10.

N10 G02 X1. I1. J0

N11 X-1. I-1. J0

N12 G00 Z.1

N13 Z1. M09

N14 G91 G28 Z0

N15 G28 X0 Y0

N16 M30
## **Arc Output Using Radial Format**
O0001

N1 G17 G20 G40 G80

N2 (3/8 2 FLUTE HSS EM)

N3 T01 M06

N4 S2500 M03

N5 G54

N6 M08

N7 G90 G00 X-1. Y0

N8 G43 Z.1 H01

N9 G01 Z-1. F10.

N10 G02 X1. R-1.

N11 X-1. R-1.

N12 G00 Z.1

N13 Z1. M09

N14 G91 G28 Z0

N15 G28 X0 Y0

N16 M30
# <a name="chmtopic34"></a>**CAMWorks Exercise: Arc Center Output and Smallest Arc Resolution**
#### **Exercise**
Change the arc center output to absolute or incremental and define the smallest arc resolution:

1. Start the UPG and open the Generic Fanuc post.
1. Click the Header tab.
1. In the Arc Centers group, pick Center – X,Y,I,J.
1. Click the Misc. tab.
1. In the Arc Centers group, pick Absolute or Incremental Distance from Start to Center. This option allows setting the code output for all values in the operation to either absolute or incremental on an operation by operation basis.
1. In the Arc Resolution group:
- Check Small Arc Checking
- Type **.2** for Arc Rounding Point
7. Save the source as CW\_MPOST12 and compile.
7. In SolidWorks, open the part file CW\_MPOST12.SLDPRT. This part is in the \cw examples folder inside the folder where you installed the UPG.
7. Change to the CAMWorks Operation tree.
7. Right click FinishMill2 in the tree and select Parameters on the shortcut menu.
7. Click the Post tab. The Absolute Incremental parameter displays. This parameter was activated using the Absolute or Incremental Distance from Start to Center in the Misc. tab. The parameter is set to Absolute for this operation.
7. Click OK to exit the dialog box.
7. Post process the part and review the output. The first operation has no arcs. The second operation has Absolute I's and J's and the third operation has incremental I's and J's.
## **Sample Code for Arc Centers and Resolution**
O0001

N1 G17 G20 G40 G80  { 1st Operation

N2 (1/4 2 FLUTE HSS EM)

N3 T01 M06

N4 S2200 M03

N5 G54

N6 M08

N7 G90 G00 X-.2652 Y.2348

N8 G43 Z.1 H01

N9 G01 Z-2. F10.

N10 X0 Y.125 F30.

N11 X2.

N12 X2.375 Y.5

N13 Y2.5

N14 X2. Y2.875

N15 X0

N16 X-.375 Y2.5

N17 Y.5

N18 X-.2652 Y.2348

N19 G00 Z.1

N20 Z1. M09

N21 G91 G28 Z0

N22 (1" 4 FLUTE HSS EM)

N23 T02 M06  { 2nd Operation

N24 S2500 M03

N25 G54

N26 M08

N27 G90 X-1.5 Y1.5

N28 G43 Z.1 H02

N29 G01 Z-1. F10.

N30 Y3. F30.

N31 G02 X-.5 Y4. I-.5 J3.

N32 G01 X2.5

N33 G02 X3.5 Y3. I2.5 J3.

N34 G01 Y0

N35 G02 X2.5 Y-1. I2.5 J0

N36 G01 X-.5

N37 G02 X-1.5 Y0 I-.5 J0

N38 G01 Y1.5

N39 G00 Z.1

N40 Z1.

N41 Z.1

N42 G01 Z-.5 F10.  { 3rd Operation

N43 G91 Y1.5 F30.

N44 G02 X1. Y1. I1. J0

N45 G01 X3.

N46 G02 X1. Y-1. I0 J-1.

N47 G01 Y-3.

N48 G02 X-1. Y-1. I-1. J0

N49 G01 X-3.

N50 G02 X-1. Y1. I0 J1.

N51 G01 Y1.5

N52 G90 G00 Z.1

N53 G01 Z-.5 F10.

N54 Z-1.

N55 G91 Y1.5 F30.

N56 G02 X1. Y1. I1. J0

N57 G01 X3.

N58 G02 X1. Y-1. I0 J-1.

N59 G01 Y-3.

N60 G02 X-1. Y-1. I-1. J0

N61 G01 X-3.

N62 G02 X-1. Y1. I0 J1.

N63 G01 Y1.5

N64 G90 G00 Z.1

N65 Z1. M09

N66 G91 G28 Z0

N67 G28 X0 Y0

N68 M30
# <a name="chmtopic36"></a>**CAMWorks Exercise: Output Arcs as Linear Moves**
#### **Exercise**
Change the source to output arcs as linear moves:

1. Start the UPG and open the Generic Fanuc post.
1. Click the Header tab.
1. In the Arc Quadrants group, pick Simulate with Linear Moves.
1. Click the Setup tab.
1. For Chord Distance:
- Check the Prompt For check box
- Type **.01** for the Default Distance
6. Save the source as CW\_MPOST20 and compile.
6. In SolidWorks, open the part file CW\_MPOST20.SLDPRT. This part is in the \cw examples folder inside the folder where you installed the UPG.
6. Change to the CAMWorks Operation tree.
6. Right click Mill Machine – Inch in the tree and select Parameters on the shortcut menu.
6. Click the Parameters tab. The Arc Chord Length parameter displays and the value can be changed.
6. Click the Controller tab and make sure a controller is selected.
6. Click OK to exit the dialog box.
6. Post process the part and review the output. Notice that small line moves replace the arc moves.
## **Arc Output as Linear Moves**
O0001

N1 G17 G20 G40 G80

N2 (1" 4 FLUTE HSS EM)

N3 T23 M06

N4 S2500 M03

N5 G54

N6 M08

N7 G90 G41 D43 G00 X-.5 Y1.5

N8 G43 Z.1 H23

N9 G01 Z-.5 F10.

N10 Y3. F30.

N11 X-.4808 Y3.1951

N12 X-.4239 Y3.3827

N13 X-.3315 Y3.5556

N14 X-.2071 Y3.7071

N15 X-.0556 Y3.8315

N16 X.1173 Y3.9239

N17 X.3049 Y3.9808

N18 X.5 Y4.

N19 X3.5

N20 X3.6951 Y3.9808

N21 X3.8827 Y3.9239

N22 X4.0556 Y3.8315

N23 X4.2071 Y3.7071

N24 X4.3315 Y3.5556

N25 X4.4239 Y3.3827

N26 X4.4808 Y3.1951

N27 X4.5 Y3.

N28 Y0

N29 X4.4808 Y-.1951

N30 X4.4239 Y-.3827

N31 X4.3315 Y-.5556

N32 X4.2071 Y-.7071

N33 X4.0556 Y-.8315

N34 X3.8827 Y-.9239

N35 X3.6951 Y-.9808

N36 X3.5 Y-1.

N37 X.5

N38 X.3049 Y-.9808

N39 X.1173 Y-.9239

N40 X-.0556 Y-.8315

N41 X-.2071 Y-.7071

N42 X-.3315 Y-.5556

N43 X-.4239 Y-.3827

N44 X-.4808 Y-.1951

N45 X-.5 Y0

N46 Y1.5

N47 G00 Z.1

N48 G01 Z-.5 F10.

N49 Z-1.

N50 Y3. F30.

N51 X-.4808 Y3.1951

N52 X-.4239 Y3.3827

N53 X-.3315 Y3.5556

N54 X-.2071 Y3.7071

N55 X-.0556 Y3.8315

N56 X.1173 Y3.9239

N57 X.3049 Y3.9808

N58 X.5 Y4.

N59 X3.5

N60 X3.6951 Y3.9808

N61 X3.8827 Y3.9239

N62 X4.0556 Y3.8315

N63 X4.2071 Y3.7071

N64 X4.3315 Y3.5556

N65 X4.4239 Y3.3827

N66 X4.4808 Y3.1951

N67 X4.5 Y3.

N68 Y0

N69 X4.4808 Y-.1951

N70 X4.4239 Y-.3827

N71 X4.3315 Y-.5556

N72 X4.2071 Y-.7071

N73 X4.0556 Y-.8315

N74 X3.8827 Y-.9239

N75 X3.6951 Y-.9808

N76 X3.5 Y-1.

N77 X.5

N78 X.3049 Y-.9808

N79 X.1173 Y-.9239

N80 X-.0556 Y-.8315

N81 X-.2071 Y-.7071

N82 X-.3315 Y-.5556

N83 X-.4239 Y-.3827

N84 X-.4808 Y-.1951

N85 X-.5 Y0

N86 Y1.5

N87 G00 Z.1

N88 Z1. M09

N89 G40 X-.5 Y1.5

N90 G91 G28 Z0

N91 G28 X0 Y0

N92 M30
# <a name="chmtopic39"></a>**CAMWorks Exercise: Preload Tool at End of Tape**
#### **Exercise**
Change the source to output the code to preload the tool at the end of the program:

1. Start the UPG and open the Generic Fanuc post.
1. Click the Misc. tab and check Preload Tool at End of Tape in the Miscellaneous group.
1. Type **0** in the text box for What Tool to Preload at End of Tape.
1. Click the Sections tab.
1. Pick Miscellaneous in the Section Categories list.
1. Select End of Tape in the Section List and copy the section code in the text box.

![image\pin_bl.gif] For information on how to copy and paste, see the [Moving and Copying Text](#chmtopic38) topic.

7. Select the End of Tape Preload section, click the Clear button, then paste the code you copied.
7. Place the cursor at the end of the 2nd line and press Enter to create a new line.
7. In the Modal Flag group, select Modal.
7. Click the :T:, N, Next Tool, M06 & EOL buttons.

The 3rd line should read: :T:<N><T:NEXT\_TOOL><M:06><EOL>

11. Save the source as CW\_MPOST15 and compile.
11. In SolidWorks, open the part file CW\_MPOST15.SLDPRT. This part is in the \cw examples folder inside the folder where you installed the UPG.
11. Change to the CAMWorks Operation tree.
11. Post process the part and review the output. Notice on line N36 the first tool is preloaded.
11. Return to the UPG and click the Misc. tab.
11. In the Miscellaneous group, type **99** in the text box for What Tool to Preload at End of Tape.
11. Save the source as CW\_MPOST15 and compile.
11. In SolidWorks, open the part file CW\_MPOST15.SLDPRT again.
11. Post process the part and review the output. Notice on line N36 the tool 99 is preloaded.
## **Code to Preload First Tool**
O0001

N1 G17 G20 G40 G80

N2 (1" 4 FLUTE HSS EM)

N3 T01 M06

N4 S2500 M03

N5 G54

N6 M08

N7 G90 G00 X0 Y2.5

N8 G43 Z.1 H01

N9 G01 Z-1. F10.

N10 Y4. F30.

N11 G02 X1. Y5. R1.

N12 G01 X4.

N13 G02 X5. Y4. R1.

N14 G01 Y1.

N15 G02 X4. Y0 R1.

N16 G01 X1.

N17 G02 X0 Y1. R1.

N18 G01 Y2.5

N19 G00 Z.1

N20 Z1. M09

N21 G91 G28 Z0

N22 (E, 1/4 COBALT JOBBER DRILL)

N23 T09 M06

N24 S1500 M03

N25 G54

N26 M08

N27 G90 X1. Y1.

N28 G43 Z.1 H09

N29 G81 G99 R.1 Z-1. F5.

N30 Y4.

N31 X4. Y1.

N32 Y4.

N33 G80 Z1. M09

N34 G91 G28 Z0

N35 G28 X0 Y0

N36 T01 M06  } Preload 1st Tool

N37 M30


## **Code to Preload Tool 99**
O0001

N1 G17 G20 G40 G80

N2 (1" 4 FLUTE HSS EM)

N3 T01 M06

N4 S2500 M03

N5 G54

N6 M08

N7 G90 G00 X0 Y2.5

N8 G43 Z.1 H01

N9 G01 Z-1. F10.

N10 Y4. F30.

N11 G02 X1. Y5. R1.

N12 G01 X4.

N13 G02 X5. Y4. R1.

N14 G01 Y1.

N15 G02 X4. Y0 R1.

N16 G01 X1.

N17 G02 X0 Y1. R1.

N18 G01 Y2.5

N19 G00 Z.1

N20 Z1. M09

N21 G91 G28 Z0

N22 (E, 1/4 COBALT JOBBER DRILL)

N23 T09 M06

N24 S1500 M03

N25 G54

N26 M08

N27 G90 X1. Y1.

N28 G43 Z.1 H09

N29 G81 G99 R.1 Z-1. F5.

N30 Y4.

N31 X4. Y1.

N32 Y4.

N33 G80 Z1. M09

N34 G91 G28 Z0

N35 G28 X0 Y0

N36 T99 M06  { Preload Tool 99

N37 M30
# <a name="chmtopic41"></a>**CAMWorks Exercise: Compensation and Debug Output**
#### **Exercise**
Format the compensation number output and turn on Debug messages:

1. Start the UPG and open the Generic Fanuc post.
1. Click the Misc. tab.
1. In the Misc. group:
- Check Output Debug
- Type **50** for Define Compensation Number
4. Save source as CW\_MPOST16 and compile.
4. In SolidWorks, open the part file CW\_MPOST16.SLDPRT. This part is in the \cw examples folder inside the folder where you installed the UPG.
4. Change to the CAMWorks Operation tree.
4. Post process this part and review the output. Notice the debug text in the posted output identifying the sections called. The "D" offset number on line N9 is the tool number plus the Define Compensation Number value.
## **Code Output**
Start of Tape

O0001

N1 G17 G20 G40 G80

Start Operation

N2 (1" 4 FLUTE HSS EM)

N3 T23 M06

N4 S2500 M03

N5 G54

N6 M08

Every Move

Rapid XY Move

Rapid From Tool Chan

N7 G90 G41 D73 G00 X-.5 Y1.5

Every Move

Rapid Z Move Down

N8 G43 Z.1 H23

Every Move

Z Feed Move

N9 G01 Z-.5 F10.

Every Move

Line Move

N10 Y3. F30.

Every Move

Arc Move

N11 G02 X.5 Y4. R1.

Every Move

Line Move

N12 G01 X3.5

Every Move

Arc Move

N13 G02 X4.5 Y3. R1.

Every Move

Line Move

N14 G01 Y0

Every Move

Arc Move

N15 G02 X3.5 Y-1. R1.

Every Move

Line Move

N16 G01 X.5

Every Move

Arc Move

N17 G02 X-.5 Y0 R1.

Every Move

Line Move

N18 G01 Y1.5

Every Move

Rapid Z Move Up

N19 G00 Z.1

Every Move

Z Feed Move

N20 G01 Z-.5 F10.

Every Move

Z Feed Move

N21 Z-1.

Every Move

Line Move

N22 Y3. F30.

Every Move

Arc Move

N23 G02 X.5 Y4. R1.

Every Move

Line Move

N24 G01 X3.5

Every Move

Arc Move

N25 G02 X4.5 Y3. R1.

Every Move

Line Move

N26 G01 Y0

Every Move

Arc Move

N27 G02 X3.5 Y-1. R1.

Every Move

Line Move

N28 G01 X.5

Every Move

Arc Move

N29 G02 X-.5 Y0 R1.

Every Move

Line Move

N30 G01 Y1.5

Every Move

Rapid Z Move Up

N31 G00 Z.1

Every Move

Rapid Z Move Up

N32 Z1. M09

End Operation

N33 G40 X-.5 Y1.5

Program End

N34 G91 G28 Z0

N35 G28 X0 Y0

N36 M30
# <a name="chmtopic43"></a>**CAMWorks Exercise: Post Parameters for CAM Operations**
#### **Exercise**
Add post parameters that display on the Post tab in the Machining Parameters dialog box when you define operations in CAMWorks:

1. Start the UPG and open the Generic Fanuc post.
1. Click the Mill 2D tab and check X Tool Change Pos. & Y tool Change Pos. for the Pocket, Lace, Profile and Miscellaneous operations.
1. Click the Mill 3D tab and check X Tool Change Pos. & Y tool Change Pos. for all operations.
1. Click the Drill/Tap tab and check X Tool Change Pos. & Y tool Change Pos. for all operations.
1. Click the Bore/Ream tab and check X Tool Change Pos. & Y tool Change Pos. for all operations.
1. Click the Sections tab and pick Tool in the Section Categories list.
1. Select Init Tool Change in the Section List.
1. Place the cursor at the start of the 1st line in the text box and press Enter to create a new line.
1. Place the cursor at the start of the blank line, then click the :T: and N buttons.
1. In the Modal flag group, select Non Modal.
1. Click the G90, G00, X, Y and EOL buttons.
1. Place the cursor after the X! and type a colon (**:**), then in lower case type **x\_tool\_change**.
1. Place the cursor after the Y! and type a colon (**:**), then in lower case type **y\_tool\_change**.

The line should read: :T:<N><G!:90><G!:00><X!:x\_tool\_change><Y!:y\_tool\_change><EOL>

14. Copy this line.

![image\pin_bl.gif] For information on how to copy and paste, see the [Moving and Copying Text](#chmtopic38) topic.

15. Select Sub Tool Change in the Section List.
15. Place the cursor at the end of the 1<sup>st</sup> line and press Enter.
15. Paste the line you copied on the blank line.
15. Save the source as CW\_MPOST17 and compile.
15. In SolidWorks, open the part file CW\_MPOST17.SLDPRT. This part is in the \cw examples folder inside the folder where you installed the UPG.
15. Change to the CAMWorks Operation tree.
15. Right click Finish Mill1 in the tree and select Parameters on the shortcut menu.
15. Click the Post tab. Notice the X & Y tool change position parameters display.
15. Post process this part and review the output. Notice the tool change position on line N2.
## **Code for Tool Change Position**
O0001

N1 G17 G20 G40 G80

N2 G90 G00 X1. Y1.

N3 (1" 4 FLUTE HSS EM)

N4 T23 M06

N5 S2500 M03

N6 G54

N7 M08

N8 G41 D43 X-.5 Y1.5

N9 G43 Z.1 H23

N10 G01 Z-.5 F10.

N11 Y3. F30.

N12 G02 X.5 Y4. R1.

N13 G01 X3.5

N14 G02 X4.5 Y3. R1.

N15 G01 Y0

N16 G02 X3.5 Y-1. R1.

N17 G01 X.5

N18 G02 X-.5 Y0 R1.

N19 G01 Y1.5

N20 G00 Z.1

N21 G01 Z-.5 F10.

N22 Z-1.

N23 Y3. F30.

N24 G02 X.5 Y4. R1.

N25 G01 X3.5

N26 G02 X4.5 Y3. R1.

N27 G01 Y0

N28 G02 X3.5 Y-1. R1.

N29 G01 X.5

N30 G02 X-.5 Y0 R1.

N31 G01 Y1.5

N32 G00 Z.1

N33 Z1. M09

N34 G40 X-.5 Y1.5

N35 G91 G28 Z0

N36 G28 X0 Y0

N37 M30
# <a name="chmtopic45"></a>**CAMWorks Exercise: Setup Parameters for CAM Operations**
#### **Exercise**
Add setup parameters that display on the Parameters tab in the Machine dialog box.

1. Start the UPG and open the Generic Fanuc post.
1. Click the Setup tab.
1. For Program Name, check Prompt For.
1. Click the Sections Tab and pick Miscellaneous in the Section Categories list.
1. Select Start of Tape in the Section List.
1. Place the cursor at the start of the 1st line and press Enter.
1. Place the cursor at the start of the blank line, then click the :T:, Program Name & EOL buttons.
1. Save the source as CW\_MPOST19 and compile.
1. In SolidWorks, open the part file CW\_MPOST19.SLDPRT. This part is in the \cw examples folder inside the folder where you installed the UPG.
1. Change to the CAMWorks Operation tree.
1. Right click Mill Machine – Inch in the tree and select Parameters.
1. Click the Parameters tab. The Program Name parameter displays.
1. Click OK to exit the Machine dialog box.
1. Post process the part and review the output. Notice the first line of code has the Program Name.
## **Code Output with Program Name**
cw\_mpost19  { Program Name

O0001

N1 G17 G20 G40 G80

N2 (1/2 COBALT JOBBER DRILL)

N3 T01 M06

N4 S1500 M03

N5 G54

N6 M08

N7 G90 G00 X2. Y2.

N8 G43 Z.1 H01

N9 G81 G99 X2. Y2. R.1 Z-1.2001 F8.

N10 G80 Z1. M09

N11 G91 G28 Z0

N12 (E, 1/4 COBALT JOBBER DRILL)

N13 T02 M06

N14 S1500 M03

N15 G54

N16 M08

N17 G90 X1. Y1.

N18 G43 Z.1 H02

N19 G81 G99 R.1 Z-1.125 F8.

N20 G80 Z1. M09

N21 G91 G28 Z0

N22 G28 X0 Y0

N23 M30
# <a name="chmtopic47"></a>**CAMWorks Exercise: 5 Axis Output**
![image\pin_bl.gif] **BEFORE YOU CONTINUE:** This exercise covers advanced procedures for multiaxis support. The exercise is complex and typically is not of interest to the average user. You should not try this exercise unless you have advanced NC programming skills. If you decide not to do this exercise, but you need to make a 5 axis post, you can select the Generic Fanuc 5 Axis post template.
#### **Exercise**
Change the source to support 5 axis output in CAMWorks:

1. Start the UPG and open the Generic Fanuc post.
1. Click the Header tab.

Turn on 5 axis milling and define the rotate and tilt axis labels:

1. In the Multiaxis Milling group:
- Uncheck None
- Select True for 5 Axis Milling
- Type **A** for the Rotation Axis Label
- Type **C** for the Tilt Axis label
- Select Rotate Table Tilt Table about X Axis in the list box
- Select Incremental Output for Multiaxis Type
- Select CW Rotation Positive for Rotation Direction

Next, you are going to create 5 axis rapid, drilling and cut sections from similar 3 axis sections by copying the 3 axis section code into the 5 axis sections, then adding the 5 axis rotate and tilt code:

1. Click the Sections tab and pick Rapid Moves in the Section Categories list.
1. Select 1st Rapid Z Down in the Section List and copy the section code in the text box.

![image\pin_bl.gif] For information on how to copy and paste, see the [Moving and Copying Text](#chmtopic38) topic.

3. Select 5 Axis 1st Rapid Z Down in the Section List, click the Clear button, then paste the code you copied in step 5.
3. Repeat steps 5 and 6 to copy and paste the following section code:

|Copy section code from|Paste to|
| :- | :- |
|Rapid Z Down|5 Axis Rapid Z Down|
|Rapid Z Up|5 Axis Rapid Z Up|
|Last Rapid Z Up|5 Axis Last Rapid Z Up|
|Rapid Move|5 Axis Rapid Move|

The rapid move section code you copied into the 5 Axis Rapid Move section can now be edited to add the 5 axis rotary and tilt code:

5. In the Modal Flag group, pick Modal.
5. In the text box for the 5 Axis Rapid Move section, place the cursor after the <Y!> and click the A button, then click the B button.

<A><B> is inserted after <Y!>.



Add the 5 axis rotary and tilt codes to the Continue Drilling section:

7. Pick Drilling in the Section Categories list and select Continue Drilling in the Section List.
7. In the text box, place the cursor after the <Y>, and click the A button, then click the B button.

The line reads :T:<N><G:ABSINC><G:work\_coord><X><Y><A><B><attributes><EOL>



Copy 3 axis cut move section code into the 5 axis cut move sections, then add the 5 axis rotate and tilt code to the 5 Axis Line Move section:

9. Pick Cut Moves in the Section Categories list.
9. Select Feed Z Down in the Section List, copy the section code in the text box and paste it in the text box for the 5 Axis Feed Z Down section.
9. Select Line Move in the Section List, copy the section code and paste it in the text box for the 5 Axis Line Move section.
9. In the Modal Flag group, pick Modal.
9. In the text box, place the cursor after the <Z> and click the A button, then click the B button.
9. Save the source as CW\_MPOST7 and compile.
9. In SolidWorks, open the part file CW\_MPOST7.SLDPRT. This part is in the \cw examples folder inside the folder where you installed the UPG.
9. Change to the CAMWorks Operation tree. This part has been setup for 5th axis output. If you need help on setting up 5 axis, see the CAMWorks online help.
9. Post process the part and review the output. Notice the A and B tilt and rotate moves.

![image\pin_bl.gif] Because of product modifications, your output may not look exactly the same as the following example.


## **Sample 5 Axis Milling Code**
O0001

N1 G17 G20 G40 G80

N2 (1/4 2 FLUTE HSS EM)

N3 T43 M06

N4 S2500 M03

N5 G54

N6 M08

N7 G90 G54 G00 X-2.3714 Y1.0315 C26.5651 A146.3099

N8 G43 Z.1 H43

N9 G01 Z-.25 F10.

N10 X-4.84 Y2.4029 F30.

N11 X-4.8162 Y2.6581

N12 X.1581 Y4.3162

N13 X.25 Y4.25

N14 Y-.25

N15 X.0971 Y-.34

N16 X-2.3714 Y1.0315

N17 G00 Z.1

N18 Z1. M09

N19 G91 G28 Z0

N20 G28 X0 Y0

N21 M30
# <a name="chmtopic49"></a>**CAMWorks Exercise: 4th Axis Rotating About X**
![image\pin_bl.gif] **BEFORE YOU CONTINUE:** This exercise covers advanced procedures for multiaxis. The exercise is complex and typically is not of interest to the average user. You should not try this exercise unless you have advanced NC programming skills. If you decide not to do this exercise, but need to do a 4th axis post, you can select one of the Generic Fanuc 4th Axis post templates.
#### **Exercise**
Add the source code for 4th axis rotating about X:

1. Start the UPG and open the Generic Fanuc post.
1. Click the Header tab.

Turn on 4 axis X milling and define the rotate axis label:

1. In the Multiaxis Milling group:
- Uncheck None
- Select True for 4 Axis X Milling
- Type **A** for the Rotation Axis Label
- Select Incremental Output for Multiaxis Type
- Select CW Rotation Positive for Rotation Direction

Next, you are going to create 5 axis rapid, drilling and cut sections from similar 3 axis sections by copying the 3 axis section code into the 5 axis sections, then adding the 4<sup>th</sup> axis rotate code:

1. Click the Sections tab and pick Rapid Moves in the Section Categories list.
1. Select 1st Rapid Z Down in the Section List and copy the section code in the text box.
1. Select 5 Axis 1st Rapid Z Down in the Section List, click the Clear button, then paste the code you copied in step 5.
1. Repeat steps 5 and 6 to copy and paste the following section code:

|Copy section code from|Paste to|
| :- | :- |
|Rapid Z Down|5 Axis Rapid Z Down|
|Rapid Z Up|5 Axis Rapid Z Up|
|Last Rapid Z Up|5 Axis Last Rapid Z Up|
|Rapid Move|5 Axis Rapid Move|



5. In the Modal Flag group, pick Modal.
5. In the section code text box for the 5 Axis Rapid Move section, place the cursor after the <Y!> and click the B button.

Add the 4th axis rotary code to Continue Drilling section:

7. Pick Drilling in the Section Categories list and select Continue Drilling in the Section List.
7. In the text box, place the cursor after the <Y> and click the B button.

Copy 3 axis cut move section code into the 5 axis cut move sections, then add the 4th axis rotate code to the 5 Axis Line Move section:

9. Pick Cut Moves in the Section Categories list.
9. Select Feed Z Down in the Section List, copy the section code in the text box and paste it in the text box for the 5 Axis Feed Z Down section.
9. Select Line Move in the Section List, copy the section code and paste it in the text box for the 5 Axis Line Move section.
9. In the Modal Flag group, pick Modal.
9. In the text box, place the cursor after the <Z> and click the B button.
9. Save the source as CW\_MPOST8 and compile.
9. In SolidWorks, open the part file CW\_MPOST8.SLDPRT. This part is in the \cw examples folder inside the folder where you installed the UPG.
9. Change to the CAMWorks Operation tree. This part has been setup for 4th axis output. If you need help on setting up 4th axis, see the CAMWorks online help.
9. Post process the part and review the output. Notice the A rotate moves.
## **4th Axis Rotate About X Output**
O0001

N1 G17 G20 G40 G80

N2 (1" 4 FLUTE HSS EM)

N3 T23 M06

N4 S2500 M03

N5 G54

N6 M08

N7 G90 G54 G00 X1.5 Y.5 A0

N8 G43 Z.1 H23

N9 G01 Z-.5 F10.

N10 X3.5 F30.

N11 Y-5.5

N12 X-.5

N13 Y.5

N14 X1.5

N15 G00 Z.1

N16 Z1. M09

N17 G91 G28 Z0

N18 (#3 60 DEG CENTERDRILL)

N19 T28 M06

N20 S2800 M03

N21 G54

N22 M08

N23 G90 G54 G00 X1.5 Y-4.5

N24 G43 Z1. H28

N25 G81 G98 R.1 Z-.2311 F6.

N26 Y-.5

N27 G80 Z1. M09

N28 G91 G28 Z0

N29 (1/2 COBALT JOBBER DRILL)

N30 T43 M06

N31 S1500 M03

N32 G54

N33 M08

N34 G90 G54 G00 X1.5 Y-4.5

N35 G43 Z.1 H43

N36 G81 G99 R.1 Z-1. F5.

N37 Y-.5

N38 G80 Z1. M09

N39 G91 G28 Z0

N40 (1" 4 FLUTE HSS EM)

N41 T23 M06

N42 S2500 M03

N43 G54

N44 M08

N45 G90 G54 G00 X1.5 Y.5 A90.

N46 G43 Z.1 H23

N47 G01 Z-.5 F10.

N48 X3.5 F30.

N49 Y-5.5

N50 X-.5

N51 Y.5

N52 X1.5

N53 G00 Z.1

N54 Z1. M09

N55 G91 G28 Z0

N56 (#3 60 DEG CENTERDRILL)

N57 T28 M06

N58 S2800 M03

N59 G54

N60 M08

N61 G90 G54 G00 X1.5 Y-4.

N62 G43 Z1. H28

N63 G81 G98 R.1 Z-.2311 F6.

N64 Y-1.

N65 G80 Z1. M09

N66 G91 G28 Z0

N67 (1/2 COBALT JOBBER DRILL)

N68 T43 M06

N69 S1500 M03

N70 G54

N71 M08

N72 G90 G54 G00 X1.5 Y-4.

N73 G43 Z.1 H43

N74 G81 G99 R.1 Z-1. F5.

N75 Y-1.

N76 G80 Z1. M09

N77 G91 G28 Z0

N78 (1" 4 FLUTE HSS EM)

N79 T23 M06

N80 S2500 M03

N81 G54

N82 M08

N83 G90 G54 G00 X-1.5 Y-.5 A180.

N84 G43 Z.1 H23

N85 G01 Z-.5 F10.

N86 X-3.5 F30.

N87 Y5.5

N88 X.5

N89 Y-.5

N90 X-1.5

N91 G00 Z.1

N92 Z1. M09

N93 G91 G28 Z0

N94 (#3 60 DEG CENTERDRILL)

N95 T28 M06

N96 S2800 M03

N97 G54

N98 M08

N99 G90 G54 G00 X-1.5 Y4.5

N100 G43 Z1. H28

N101 G81 G98 R.1 Z-.2311 F6.

N102 Y.5

N103 G80 Z1. M09

N104 G91 G28 Z0

N105 (1/2 COBALT JOBBER DRILL)

N106 T43 M06

N107 S1500 M03

N108 G54

N109 M08

N110 G90 G54 G00 X-1.5 Y4.5

N111 G43 Z.1 H43

N112 G81 G99 R.1 Z-1. F5.

N113 Y.5

N114 G80 Z1. M09

N115 G91 G28 Z0

N116 (1" 4 FLUTE HSS EM)

N117 T23 M06

N118 S2500 M03

N119 G54

N120 M08

N121 G90 G54 G00 X1.5 Y.5 A270.

N122 G43 Z.1 H23

N123 G01 Z-.5 F10.

N124 X3.5 F30.

N125 Y-5.5

N126 X-.5

N127 Y.5

N128 X1.5

N129 G00 Z.1

N130 Z1. M09

N131 G91 G28 Z0

N132 (#3 60 DEG CENTERDRILL)

N133 T28 M06

N134 S2800 M03

N135 G54

N136 M08

N137 G90 G54 G00 X1.5 Y-4.

N138 G43 Z1. H28

N139 G81 G98 R.1 Z-.2311 F6.

N140 Y-1.

N141 G80 Z1. M09

N142 G91 G28 Z0

N143 (1/2 COBALT JOBBER DRILL)

N144 T43 M06

N145 S1500 M03

N146 G54

N147 M08

N148 G90 G54 G00 X1.5 Y-4.

N149 G43 Z.1 H43

N150 G81 G99 R.1 Z-1. F5.

N151 Y-1.

N152 G80 Z1. M09

N153 G91 G28 Z0

N154 G28 X0 Y0

N155 M30
# <a name="chmtopic51"></a>**CAMWorks Exercise: 4th Axis Indexing Output**
![image\pin_bl.gif] **BEFORE YOU CONTINUE:** This exercise covers advanced procedures for multiaxis support. The exercise is complex and typically is not of interest to the average user. You should not try this exercise unless you have advanced NC programming skills. If you decide not to do this exercise, but want to see the Indexer output, you can select one of the Generic Fanuc 4th Axis post templates and follow steps 3-6 below.
#### **Exercise**
Change the source for 4th axis indexing output in CAMWorks.

1. Start the UPG and open the CW\_MPOST8.SRC (the post source you created in the previous exercise).
1. Click the Header tab.
1. In the Multiaxis Milling group:
- Type **M20 (** for the Rotation Axis Label. Include a space after the 0. The left parenthesis indicates the start of the trailing label.
- Type **DEGREES)** for the Trailing Label. Include 1 space before the word DEGREES and close the label with the right parenthesis.
4. Save the source as MPOST22 and compile.

![image\pin_bl.gif] You can use the Save As command to configure similar controls. The original source file (e.g., CW\_MPOST8.SRC) is retained.

5. In SolidWorks, open the part file CW\_MPOST22.SLDPRT. This part is in the \cw examples folder inside the folder where you installed the UPG.
5. Change to the CAMWorks Operation tree.
5. Post process this part and review the output. Notice the M20 ( DEGREES) Index moves.
## **4th Axis Indexing Output**
O0001

N1 G17 G20 G40 G80

N2 (1" 4 FLUTE HSS EM)

N3 T23 M06

N4 S2500 M03

N5 G54

N6 M08

N7 G90 G54 G00 X1.5 Y.5 M20 (0 DEGREES)

N8 G43 Z.1 H23

N9 G01 Z-.5 F10.

N10 X3.5 F30.

N11 Y-5.5

N12 X-.5

N13 Y.5

N14 X1.5

N15 G00 Z.1

N16 Z1. M09

N17 G91 G28 Z0

N18 (#3 60 DEG CENTERDRILL)

N19 T28 M06

N20 S2800 M03

N21 G54

N22 M08

N23 G90 G54 G00 X1.5 Y-4.5

N24 G43 Z1. H28

N25 G81 G98 R.1 Z-.2311 F6.

N26 Y-.5

N27 G80 Z1. M09

N28 G91 G28 Z0

N29 (1/2 COBALT JOBBER DRILL)

N30 T43 M06

N31 S1500 M03

N32 G54

N33 M08

N34 G90 G54 G00 X1.5 Y-4.5

N35 G43 Z.1 H43

N36 G81 G99 R.1 Z-1. F5.

N37 Y-.5

N38 G80 Z1. M09

N39 G91 G28 Z0

N40 (1" 4 FLUTE HSS EM)

N41 T23 M06

N42 S2500 M03

N43 G54

N44 M08

N45 G90 G54 G00 X1.5 Y.5 M20 (90. DEGREES)

N46 G43 Z.1 H23

N47 G01 Z-.5 F10.

N48 X3.5 F30.

N49 Y-5.5

N50 X-.5

N51 Y.5

N52 X1.5

N53 G00 Z.1

N54 Z1. M09

N55 G91 G28 Z0

N56 (#3 60 DEG CENTERDRILL)

N57 T28 M06

N58 S2800 M03

N59 G54

N60 M08

N61 G90 G54 G00 X1.5 Y-4.

N62 G43 Z1. H28

N63 G81 G98 R.1 Z-.2311 F6.

N64 Y-1.

N65 G80 Z1. M09

N66 G91 G28 Z0

N67 (1/2 COBALT JOBBER DRILL)

N68 T43 M06

N69 S1500 M03

N70 G54

N71 M08

N72 G90 G54 G00 X1.5 Y-4.

N73 G43 Z.1 H43

N74 G81 G99 R.1 Z-1. F5.

N75 Y-1.

N76 G80 Z1. M09

N77 G91 G28 Z0

N78 (1" 4 FLUTE HSS EM)

N79 T23 M06

N80 S2500 M03

N81 G54

N82 M08

N83 G90 G54 G00 X-1.5 Y-.5 M20 (180. DEGREES)

N84 G43 Z.1 H23

N85 G01 Z-.5 F10.

N86 X-3.5 F30.

N87 Y5.5

N88 X.5

N89 Y-.5

N90 X-1.5

N91 G00 Z.1

N92 Z1. M09

N93 G91 G28 Z0

N94 (#3 60 DEG CENTERDRILL)

N95 T28 M06

N96 S2800 M03

N97 G54

N98 M08

N99 G90 G54 G00 X-1.5 Y4.5

N100 G43 Z1. H28

N101 G81 G98 R.1 Z-.2311 F6.

N102 Y.5

N103 G80 Z1. M09

N104 G91 G28 Z0

N105 (1/2 COBALT JOBBER DRILL)

N106 T43 M06

N107 S1500 M03

N108 G54

N109 M08

N110 G90 G54 G00 X-1.5 Y4.5

N111 G43 Z.1 H43

N112 G81 G99 R.1 Z-1. F5.

N113 Y.5

N114 G80 Z1. M09

N115 G91 G28 Z0

N116 (1" 4 FLUTE HSS EM)

N117 T23 M06

N118 S2500 M03

N119 G54

N120 M08

N121 G90 G54 G00 X1.5 Y.5 M20 (270. DEGREES)

N122 G43 Z.1 H23

N123 G01 Z-.5 F10.

N124 X3.5 F30.

N125 Y-5.5

N126 X-.5

N127 Y.5

N128 X1.5

N129 G00 Z.1

N130 Z1. M09

N131 G91 G28 Z0

N132 (#3 60 DEG CENTERDRILL)

N133 T28 M06

N134 S2800 M03

N135 G54

N136 M08

N137 G90 G54 G00 X1.5 Y-4.

N138 G43 Z1. H28

N139 G81 G98 R.1 Z-.2311 F6.

N140 Y-1.

N141 G80 Z1. M09

N142 G91 G28 Z0

N143 (1/2 COBALT JOBBER DRILL)

N144 T43 M06

N145 S1500 M03

N146 G54

N147 M08

N148 G90 G54 G00 X1.5 Y-4.

N149 G43 Z.1 H43

N150 G81 G99 R.1 Z-1. F5.

N151 Y-1.

N152 G80 Z1. M09

N153 G91 G28 Z0

N154 G28 X0 Y0

N155 M30
# <a name="chmtopic53"></a>**CAMWorks Exercise: Work Coordinate in Macro Call**
![image\pin_bl.gif] **BEFORE YOU CONTINUE:** This exercise covers advanced procedures for macro support. The exercise is complex and typically is not of interest to the average user. You should not try this exercise unless you have advanced NC programming skills.
#### **Exercise**
Format the macro call with work coordinates and all rapids inside the subroutine:

1. Start the UPG and open the Generic Fanuc post.
1. Click the Misc. tab and check Use Work Coordinate in Macro Call in the Miscellaneous group.
1. Click the Sections tab and pick Macros in the Section Categories list.
1. Select Single Macro Call in the Section List.
1. Change the 2nd line in the text box:
- Delete <X\_OFFSET>, <Y\_OFFSET>
- Change <G:52> to <G!:sub\_work\_coord>.
- The 2nd line should read :T:<N><G!:sub\_work\_coord><EOL>
6. Copy the section code in the text box.
6. Select Single\_Macro\_Rotate\_Call in the Section list, click the Clear button, then paste the code you copied in step 6.
6. Select Offset Part in the Section list and delete the 2nd line:

:T:<N><G:52><X\_OFFSET><Y\_OFFSET><EOL>

9. Select Tool in the Section Categories list.
9. Select Init Tool Change in the Section List and delete the 4th line: :T:<N><G!:work\_coord><EOL>.
9. Select Sub Tool Change in the Section List and delete the 5th line: :T:<N><G!:work\_coord><EOL>.
9. Save the source as CW\_MPOST13 and compile.
9. Start SolidWorks and open the part file CW\_MPOST13.SLDPRT.
9. Click the CAMWorks Operation tree tab.
9. Post process the part and review the output. Notice the work coordinate callout in lines N8, N10 and N12 just before the subroutine call lines N9, N11 and N13. All rapids are inside the subroutine.
## **Work Coordinates in Macro Call**
O0001

N1 G17 G20 G40 G80

N2 G00 G91 G28 Z0

N3 (1" 4 FLUTE HSS EM)

N4 T23 M06

N5 S4000 M03

N6 M08

N7 G90

N8 G54

N9 M98 P0002

N10 G55

N11 M98 P0002

N12 G56

N13 M98 P0002

N14 G91 G28 Z0

N15 (3/8 4 FLUTE HSS EM)

N16 T13 M06

N17 S2500 M03

N18 M08

N19 G90

N20 G54

N21 M98 P0003

N22 G55

N23 M98 P0003

N24 G56

N25 M98 P0003

N26 G91 G28 Z0

N27 (1" 4 FLUTE HSS EM)

N28 T23 M06

N29 S2500 M03

N30 M08

N31 G90

N32 G54

N33 M98 P0004

N34 G55

N35 M98 P0004

N36 G56

N37 M98 P0004

N38 G91 G28 Z0

N39 (#3 60 DEG CENTERDRILL)

N40 T28 M06

N41 S2800 M03

N42 M08

N43 G90

N44 G54

N45 M98 P0005

N46 G55

N47 M98 P0005

N48 G56

N49 M98 P0005

N50 G91 G28 Z0

N51 (1/2 JOBBER DRILL)

N52 T43 M06

N53 S1500 M03

N54 M08

N55 G90

N56 G54

N57 M98 P0006

N58 G55

N59 M98 P0006

N60 G56

N61 M98 P0006

N62 G91 G28 Z0

N63 G28 X0 Y0

N64 M30

O0002

N1 S4000 M03

N2 G90 G00 X-.5 Y.7475

N3 G43 Z.1 H23 M08

N4 G01 Z-.5 F30.

N5 X5.5 F60.

N6 X5.7475

N7 Y.5

N8 Y-7.5

N9 Y-7.7475

N10 X5.5

N11 X-.5

N12 X-.7475

N13 Y-7.5

N14 Y.5

N15 Y.7475

N16 X-.5

N17 G00 Z.1

N18 Z1. M09

N19 M99

O0003

N1 S2500 M03

N2 G90 G41 D33 G00 X-.1875 Y-3.5

N3 G43 Z.1 H13 M08

N4 G01 Z-.5 F10.

N5 Y.1875 F30.

N6 X5.1875

N7 Y-7.1875

N8 X-.1875

N9 Y-3.5

N10 G00 Z.1

N11 Z1. M09

N12 G40 X-.1875 Y-3.5

N13 M99

O0004

N1 M03

N2 G90 G41 D43 G00 X2.5 Y.5

N3 G43 Z.1 H23 M08

N4 G01 Z-.5 F10.

N5 X5.5 F30.

N6 Y-7.5

N7 X-.5

N8 Y.5

N9 X2.5

N10 G00 Z.1

N11 Z1. M09

N12 G40 X2.5 Y.5

N13 M99

O0005

N1 S2800 M03

N2 G90 G00 X1. Y-6.

N3 G43 Z1. H28 M08

N4 G81 G98 R1.6 Z-.2311 F6.

N5 Y-1.

N6 X4. Y-6.

N7 Y-1.

N8 G80 Z1. M09

N9 M99

O0006

N1 S1500 M03

N2 G90 G00 X1. Y-6.

N3 G43 Z1.6 H43 M08

N4 G81 G99 R1.6 Z-.5 F5.

N5 Y-1.

N6 X4. Y-6.

N7 Y-1.

N8 G80 Z1. M09

N9 M99
# <a name="chmtopic55"></a>**Header Tab**
The header refers to the first part of a post processor program that defines general information such as number formats, how arcs are defined and whether macros are supported.

The Header tab allows you to define the following areas:

- Integer and floating point number formats
- How arcs are defined
- Macro support
- 4 & 5 axis support
- Spaces between commands
- Helical leadins
- Maximum line length
- Metric shift
## **Header Code Window**
As you select options or type information in the Header tab, the Header Code window displays the Post Processor Language that is created to achieve the changes you are making. It is not necessary that you understand this code. It will be of interest to advanced users who plan to modify the Post Processor Language file after using the UPG to initially customize the post processor.
# <a name="chmtopic57"></a>**Format (Header tab)**
The following format options can be set on the Header tab:
## **Floating Point**
The Floating Point group defines how floating point numbers will be formatted for output. Examples of floating point numbers are 1.123, 100.001 and 0.001. Controllers define floating point numbers using leading zeros, trailing zeros and decimal points.
## **Leading Zeros**
Leading zero format places zeros a certain number of places to the left of the decimal place as holders. If the number is a three place leading zero, 1 becomes 001, 10 becomes 010 and 100 becomes 100. The Leading Zero check box turns on and off leading zeros.
## **Trailing Zeros**
Trailing zero format places zeros a certain number of places to the right of the decimal place as holders. If the number is a three place trailing zero, .1 becomes .100, .01 becomes .010 and .001 becomes .001. The Trailing Zero check box turns on and off trailing zeros.
## **Decimals**
The Decimals check box determines whether floating point numbers have a decimal place (checked) or whether decimal places are implied (not checked).

For example, 100.125 is 100.125 with 3 leading zeros, 3 trailing zeros and decimals on. 100.125 is 100125 with 3 leading zeros, 3 trailing zero and decimals off.

|Number|Leading Zeros|Trailing Zeros|<p>Left</p><p>Places</p>|<p>Right</p><p>Places</p>|Decimals|Formatted|
| :- | :- | :- | :- | :- | :- | :- |
|100\.125|On|On|3|3|Off|100125|
|1\.25|On|On|3|3|Off|001250|
|1\.25|Off|On|3|3|On|1250|
|1\.25|On|Off|0|0|On|00125|
## **Integer Format**
The Integer Format group defines how integer numbers will be formatted for output. Examples of integer numbers are 1, 123, and 100001. Controllers define integer numbers using leading zeros and trailing zeros.
## **Leading Zeros**
Leading zero format places zeros a certain number of places to the left of the number as holders. If the number is a three place leading zero, 1 becomes 001, 10 becomes 010 and 100 becomes 100. The Leading Zero check box turns on and off leading zeros.
## **Trailing Zeros**
Trailing zero format places zeros a certain number of places to the right of the number as holders. If the number is three place trailing zero, 1 becomes 100, 10 becomes 010 and 100 becomes 100. The Trailing Zero check box turns on and off trailing zeros.

|Number|Leading Zeros|Trailing Zeros|<p>Left</p><p>Places</p>|Formatted|
| :- | :- | :- | :- | :- |
|1|On|On|3|001|
|10|On|On|3|010|
|1|Off|On|3|1|
|10|Off|Off|0|10|
## **Global Places**
The Global Places group defines how floating point and integer numbers will be formatted for output. The Global Places group defines the number of leading zeros and trailing zeros.

|Number|Leading Zeros|Trailing Zeros|<p>Left</p><p>Places</p>|<p>Right</p><p>Places</p>|Decimals|Formatted|
| :- | :- | :- | :- | :- | :- | :- |
|100\.125|On|On|3|3|Off|100125|
|1\.25|On|On|3|3|Off|001250|
|1\.25|Off|On|3|3|On|1250|
|1\.25|On|Off|0|0|On|00125|

**Left Places**

Defines the number of floating point leading zeros. An example of a floating point number (1.25) with 3 leading zeros and no trailing is 00125.

**Right Places**

Defines the number of floating point trailing zeros. An example of a floating point number (1.25) with 3 trailing zeros and no leading is 1250.

**Integer Places Left**

Defines the number of integer leading zeros.
## **Metric Place Shift**
The Metric Place Shift option defines how many places to the right to shift the decimal place for metric floating point number output.

![image\pin_bl.gif] Internally all numbers in the Universal Post Generator are stored in English units. Numbers are converted to metric before output by multiplying by 25.4 and shifting the decimal place to the right a number of places (Metric Shift).



|Number|Leading Zeros|Trailing Zeros|<p>Left</p><p>Places</p>|<p>Right</p><p>Places</p>|Decimals|Shift|Formatted|
| :- | :- | :- | :- | :- | :- | :- | :- |
|1|On|On|3|4|On|1|025\.400|
|1|On|On|3|4|On|2|0254\.00|

# <a name="chmtopic59"></a>**Arcs (Header tab)**
The options in the Arcs group on the Header tab define arc centers and quadrants.
## **Arc Centers**
The Arc Centers option describes how arcs are defined by the controller. Arcs can be defined using either:

- Center format that outputs the X, Y, I and J coordinates

For example: G03 X5. Y3. I2.2 J3.1



or

- Radial format using X, Y and R

For example: G03 X5. Y3. R4.
## **Arc Quadrants**
Arc moves, especially on older controllers, may be limited to how many quadrants an arc can be defined through at one time. Depending on the controller, full circular moves or large arc moves may need to be broken into one or more smaller arc moves.

The Arc Quadrants group describes the maximum size arc move that can be defined by the controller. Larger arc and circular moves will automatically be broken into small arc moves by the post processor.

On very old controllers it is possible that arc and circular moves are not supported at all. The post processor can simulate arc and circular moves by breaking these moves into small linear moves. Choose this option by picking Simulate With Linear Moves.

**90 Degrees Maximum (Quadrant)**

If the largest arc move supported by the controller is 90 degrees, pick this option. Arc and circular moves larger than 90 degrees will be broken into one or more 90 degree arc moves and a smaller arc move to complete the arc move.

**180 Degrees Maximum**

If the largest arc move supported by the controller is 180 degrees, pick this option. Arc and circular moves larger than 180 degrees will be broken into one 180 degree arc move and a smaller arc move to complete the arc move.

**359 Degrees Maximum**

If the largest arc move supported by the controller is 359 degrees, pick this option. Arc and circular moves larger than 359 degrees will be broken into one 359 degree arc move and a smaller arc move to complete the arc move.

**360 Degrees (Full)**

If the largest arc move supported by the controller is 360 degrees, pick this option. This selection basically means that all arc and circular moves are supported and do not need to be broken into smaller arc moves.

**Simulate With Linear Moves**

If you want to replace all arc and circular moves with small linear moves, pick the Simulate With Linear Moves option.
# <a name="chmtopic61"></a>**Miscellaneous (Header tab)**
The Miscellaneous options on the Header tab include helical leadins, spaces between commands and maximum line length.
## **Helical Leadins**
For Profile, Lace, and Pocket Operations, this start type option allows you to ramp into the part in a helical motion at a definable radius with a definable depth per revolution. This option is available only for machine/controllers that support helical interpolation.

With this start type, the following steps are output in the NC program:

- Rapid XY to the center of the start hole.
- Rapid Z axis to the clearance plane.
- Feed XY to the start point of the helix.
- Feed in a helical motion Z in increments of Depth per Rev until the depth is reached.
- Feed XY to the start of the pocket.

If the controller supports helical leadins, select the check box. If helical leadins are not supported, leave the check box unchecked.
## **Spaces Between Commands**
G code can be output with spaces between all commands or without spaces. Using the Spaces Between Commands option makes the code much easier to read; however, it also increases the size of the G code file and may require more memory on the controller.

If you want spaces between each G code command, check this box. A typical line of code with spaces may look like N1 G01 X1.125 Y 3.45 S100. If spaces are not wanted between each G code command, leave this box unchecked. A typical line of code without spaces may look like N1G01X1.125Y3.45S100.
## **Maximum Line Length**
Controllers may not accept G code lines with more than a certain number of characters. The Maximum Line Length text box allows you to restrict the maximum number of G code characters that will be put one line. If more characters are required than are allowed, the line will be broken into two or more G code lines.
# <a name="chmtopic64"></a>**Macros (Header tab)**
**ProCAM** The Macros group on the Header tab defines whether the controller supports macro calls and macro rotates.

- If supported, macro calls, grid and rotates created in ProCAM will be output using the controller's macro calls and rotate commands.
- If not supported, macro calls, grid and rotates created in ProCAM will be broken into individual moves supported by the controller.

The actual format for the [macro code output](#chmtopic63) is defined in the Sections tab.
## **Macro Calls**
If macro calls are supported by the controller, pick True; otherwise, pick False.
## **Macro Rotate**
If macro rotates are supported about the X, Y or Z axis, select the appropriate check box. All or none of the three check boxes can be selected.
# <a name="chmtopic66"></a>**Multiaxis Milling (Header tab)**
The Multiaxis Milling group defines whether the controller supports 5 axis or 4 axis preposition milling.
## **None**
The None check box defines whether 4 and 5 axis milling is supported.

- If 4 and 5 axis milling is not supported, check the None check box.
- If 4 or 5 axis milling is supported, the None check box should not be checked.
## **5 Axis Milling**
If the controller supports 5 axis milling, pick True; otherwise, pick False. If you select True, additional parameters display and the drop down list next to the None check box will be activated allowing selection of the type of rotary table/head supported.
## **Type of Rotary Table/Head**
If 5 axis milling is set to True, the drop down list describing the type of rotary table/head is enabled. The post processor supports only these six machine configurations and the tool is always normal or perpendicular to the surface you are cutting. In this release the post does not support limiting the 4th and 5th axis to any degree, such as the tilt axis of + or - 30 degrees, etc.

When you select an option in this list, the post variable :C:ROTATE\_TILT= is set to one of the following values:

|Rotate Table and Tilt Head about X Axis|:C: ROTATE\_TILT=RT\_THX|
| :- | :- |
|Rotate Table and Tilt Head about Y Axis|:C: ROTATE\_TILT=RT\_THY|
|Rotate Table and Tilt Table about X Axis|:C: ROTATE\_TILT=RT\_TTX|
|Rotate Table and Tilt Table about Y Axis|:C: ROTATE\_TILT=RT\_TTY|
|Rotate Arm and Tilt Head about X Axis|:C: ROTATE\_TILT=RA\_THX|
|Rotate Table about Y Axis and Rotate<br>Table about X Axis|:C: ROTATE\_TILT=RTY\_RTX|


## **Rotation Axis Label and Trailing Label**
The Rotation Axis label option allows you to enter the address label you need for 4th and 5th axis. The rotation definition has a leading label (the Rotation Axis Label) and optionally a trailing label (Trailing Label). The leading label is output before the rotation angle and the trailing label is output after the rotation angle.

For example: if the Rotation Axis Label is B, the Trailing Label is (Degrees) and the rotation angle is 90 degrees, the G code output would be B90 (Degrees).

The Rotation Axis Label and Trailing Label are enabled when you select either True or Center in one of the 4 or 5 axis groups.

**Tilt Axis Label and Trailing Label**

The Tilt Axis Label option allows you to enter the address label you need for 5th axis. The 5th axis tilt definition is composed of an address (Tilt Axis Label), a tilt angle and optionally a trailing label (Trailing Label). The leading label is output before the tilt angle and the trailing label is output after the tilt angle.

For example, if the Tilt Axis Label is A, the Trailing Label is (Degrees), and the tilt angle is 20 degrees, the G code output would be A20 (Degrees).

The Tilt Axis Label and Trailing Label are enabled when you select True for 5 axis milling.

**4 Axis X Milling**

These choices are dependent on the machine capabilities.

- If the controller supports 4 axis X milling with the tool perpendicular to the part edge, pick True.
- If the controller supports 4 axis X milling with the tool perpendicular to the center, pick Center.
- Otherwise, pick False.

If you pick True or Center, the Rotation Axis Label and Trailing Label parameters display allowing you to specify the address label.

**4 Axis Y Milling**

These choices are dependent on the machine capabilities.

- If the controller supports 4 axis Y milling with the tool perpendicular to the part edge, pick True.
- If the controller supports 4 axis Y milling with the tool perpendicular to the center, pick Center.
- Otherwise, pick False.

If you pick True or Center, the Rotation Axis Label and Trailing Label parameters display allowing you to specify the address label.
# <a name="chmtopic68"></a>**Misc. Tab**
The Misc. (Miscellaneous) tab covers information that is general to the entire post processor.

The following information can be changed on the Misc. tab:

- Sequence number formats
- Arc center definition
- Small arc replacement
- Work coordinates in macro calls
- Hold downs
- Tool preloading
- Compensation number definition
- Number of tools
- Feedrate format
- Code output in debug mode
## **Library File**
The Library File text box is for display only and cannot be changed in this release. The Library File has the name of the post template file currently being edited and a .LIB extension.
## **Miscellaneous Code Window**
As you select options or type information in the Header tab, the Header Code window displays the Post Processor Language to achieve the changes you are making. It is not necessary that you understand this code. It may be of interest to advanced users who plan to modify the source file after using the UPG to initially customize the post processor.
# <a name="chmtopic70"></a>**Sequence (Misc.tab)**
The following options can be set in the Sequence group on the Misc. tab:
## **Sequence Output**
The Sequence Output option defines if and how sequence numbers will be formatted for output. Examples of sequence numbers are N1, N005 and N100.

**Floating Sequence Numbers**

Outputs sequence numbers without leading zeros. Examples of Floating Sequence Numbers are N1, N10 and N100.

**Four Place Sequence Numbers**

Outputs sequence numbers with four leading zeros. This means that there are four digits in the sequence number and empty digits are padded with a "0". Examples of Four Place Sequence Numbers are N0001, N0010 and N0100.

**Three Place Sequence Numbers**

Outputs sequence numbers with three leading zeros. This means that there are three digits in the sequence number and empty digits are padded with a "0". Examples of Three Place Sequence Numbers are N001, N010 and N100.

**No Sequence Numbers**

Suppresses sequence numbers from being output.

**Sequence Number by Tool**

Outputs sequence number on each line with a tool number. The tool number and the sequence number are the same. This makes it easy to locate tool changes on the controller.

For example:

O0001

G20 G40 G80 G90

N22 T22 M06

S1000 M03

G90 G54 G00 X5. Y5.

G43 Z.1 H01 M08

G01 Z-1. F10.

.

.

.

**Sequence Number by Operation**

Outputs a sequence number on each line that starts a new operation. This makes it easy to locate operations on the controller.

For example:

O0001

G20 G40 G80 G90

N1 T22 M06

S1000 M03

G90 G54 G00 X5. Y5.

G43 Z.1 H01 M08

G01 Z-1. F10.
## **Starting Sequence Number**
The numeric value that the first sequence number will have. If the Starting Sequence Number is 5 the first sequence number will be N005.
## **Sequence Increment**
The numeric value that each sequence number will be incremented by. If the Starting Sequence Number is 10 and the Sequence Increment is 5, the sequence numbers will be N010, N015, N020…
## **Maximum Sequence Number**
The highest numeric value that a sequence number can have. After the highest sequence number is reached, the next sequence number will start over with the Starting Sequence Number.

For example:

If Starting Sequence Number = 10

Sequence Increment = 5

Maximum Sequence Number = 9999

The G code output would be:

N9990 G90 G54 G00 X5. Y5.

N9995 G43 Z.1 H01 M08

N0010 G01 Z-1. F10.

.

.

.
# <a name="chmtopic72"></a>**Arcs (Misc. tab)**
The following options can be set in the Arcs group on the Misc. tab:
## **Arc Centers**
The Arc Centers option is defined in relation to the current cutter location. Arc centers can be defined as absolute or incremental, from the start to the center and from the center to the start.

**Absolute Center**

Arc centers will be defined using absolute coordinates. An example would be G03 X5. Y3. I2.2 J3.1 F10 where 2.2 and 3.1 are absolute values.

**Incremental Distance From Start to Center**

Arc center values are incremental signed values from the start (current cutter location) to the center of the arc. An example would be G03 X5. Y3. I2.2 J3.1 F10 where 2.2 and 3.1 are incremental signed distance from the current cutter position to the center of the arc.

**Absolute or Incremental Distance From Start to Center**

Arc centers will be defined using absolute incremental X and Y values from the current cutter location (the start) to the center of the arc. The arc center location is absolute if the X & Y are absolute. The arc center location is incremental from the start to the center if the X & Y are incremental. An example would be G03 X5. Y3. I2.2 J3.1 F10 where X, Y, I and J are all incremental values.

**Incremental Distance From Center to Start**

Arc center values are incremental from arc center the start (the current cutter location). An example would be G03 X5. Y3. I2.2 J3.1 F10 where 2.2 and 3.1 are incremental distances from the arc to the start (current cutter position).
## **Arc Resolution**
This option allows very small arc moves to be replaced by a linear move from the start of the arc to the end of the arc. The small arc move size can be defined by the user.

**Small Arc Checking**

If small arcs are to be replaced by linear moves, select the Small Arc Checking box. If small arc moves are not to be replaced by linear moves, leave the Small Arc Checking box unselected.

**Use Linear Move for Arc Move At**

If the Small Arc Checking box is selected, the Use Linear Move for Arc Move At is used to define when an arc move should be replaced by a linear move.

Two conditions must be used for this to happen.

- First, the angle between a line drawn from the arc center to the arc start and a line drawn between the arc center and the arc end must be greater than .00005 and less than 180 degrees. The less than 180 degrees insures that the arc is not a circle or a very large arc with the start and end near each other.
- Second, than the Use Linear Move for Arc Move At value is multiplied times 2 and the resulting value is compared with the incremental distance in the X and the incremental distance in the Y between the arc move start and end.

If both of these conditions are met, then a linear move is substituted for the arc move.
# <a name="chmtopic74"></a>**Miscellaneous (Misc. tab)**
The following options can be set in the Miscellaneous group on the Misc. tab:


## **Use Work Coordinate in Macro Call**
**ProCAM** If Use Work Coordinate in Macro Call is not checked, then macro calls are called the way macro calls are normally done in G code.

If Use Work Coordinate in Macro Call is checked, then all macros are called using work coordinates and the work coordinate is not called in the subroutine definition.

The example below illustrates code using work coordinate macro calls. A macro was defined in the CAM system as a G81 drill cycle at X0 and Y0 and the macro was called at X5 and Y5. The Use Work Coordinate in Macro Call option is checked.

![image\pin_bl.gif] To make this work properly, you must check the Use Work Coordinate option in the Mill 2D tab.



Main Program

O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G54 X0 Y0   } Macro Work Coordinate

N5 M98 P0002

N6 G00 G91 G28 Z0

N7 M30



Sub Program

O0002    }

N1 G90 G00 X0   }

N2 G43 Z.1 H01   } Subroutine Definition

N3 G99 G81 R.1 Z-1 F10 }

N4 G80 Z1. M09  }

N5 M99    }


## **Hold Z Down Between Operations with Same Tool**
![image\pin_bl.gif] This option is for very special conditions and should be used sparingly and with care to avoid tool crashes.

The Hold Z Down Between Operations with Same Tool controls the Z level the tool rapids to between operations.

- If unselected, at the end of each operation the tool rapids in Z to the rapid plane. This is the normal case that you will most often use.
- If selected, at the end of each operation, the following check is performed:

The last operation end point is compared with the next operation start point to see if the end at exactly the same coordinate in X, Y and Z. If the points are the same, the Z rapid between operations is not performed.

This will work only in the milling portion of the post, not drilling.

The following example code is a profile of two squares with the Hold Z Down Between Operations unselected. Notice the movement to Z rapid plane between operations.



O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X5. Y5.

N5 G43 Z.1 H01 M08

N6 G01 Z-1. F20.

N7 G41 D01 X10. F10.

N8 Y10.

N9 X5.

N10 G40 Y5.

N11 G00 Z1.    } Rapid to Z rapid plane

N12 Z.1

N13 G01 Z-1. F20.

N14 G41 D01 X10. F10.

N15 Y0

N16 X5.

N17 G40 Y5.

N18 G00 Z1. M09

N19 G91 G28 Z0

N20 M30



The following example code is a profile of two squares with the Hold Z Down Between Operations selected. Notice there is no movement to Z rapid plane between operations.



O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X5. Y5.

N5 G43 Z.1 H01 M08

N6 G01 Z-1. F20.

N7 G41 D01 X10. F10.

N8 Y10.

N9 X5.

N10 G41 D01 X10. F10.

N11 Y0   } No Rapid to Z Rapid Plane

N12 X5.

N13 G40 Y5.

N14 G00 Z1. M09

N15 G91 G28 Z0

N16 M30


## **Preload Tool at End of Tape**
This option allows machines that have tool carousels to load the tool that will be used in the next operation into the carousel while the machine is performing other commands. The section of code that preloads the tool will be called only if there is more than one tool being used in the part.

For example, you have a rouging and a finish operation in a part. The roughing operation uses tool 1 and the finishing operation uses tool 2. The rouging operation will load tool 1 and preload tool 2. The second operation will preload tool 1 so that if the part is run again, the tool is ready to go.

The following preload example has two drilling operations that use different tools.



O0001

N1 G20 G40 G80 G90

N2 T01 M06    } Tool Change

N3 S1000 M03

N4 G90 G54 G00 X5. Y5.

N5 G43 Z.1 H01 M08 T02  } Preload Next Tool

N6 G99 G81 R.1 Z-1 F10.

N7 G80 Z1. M09

N8 G00 G91 G28 Z0

N9 M06     } Tool Change

N10 S2000 M03

N11 G90 G54 G00 X6.Y6

N12 G43 Z.1 H01 M08 T01  } Preload First Tool

N13 G99 G81 R.1 Z-1 F10.

N14 G80 Z1. M09

N15 G00 G91 G28 Z0

N16 M06     } Tool Change at End of Tape

N17 M30



For more information on preloading tools, see the End of Tape Preload section.
## **What Tool To Preload at End of Tape**
This option allows you to define the tool to preload at the end of the G code program.

- If the value is zero, the tool used in the first operation of the part is preloaded assuming that part will be run again.
- If the value is greater than zero, the tool preloaded will be the value.

Using the preload example shown above with the What Tool To Preload at End of Tape option set to preload tool number 99, the code would change as shown below:



O0001

N1 G20 G40 G80 G90

N2 T01 M06    } Tool Change

N3 S1000 M03

N4 G90 G54 G00 X5. Y5.

N5 G43 Z.1 H01 M08 T02  } Preload Next Tool

N6 G99 G81 R.1 Z-1 F10.

N7 G80 Z1. M09

N8 G00 G91 G28 Z0

N9 M06     } Tool Change

N10 S2000 M03

N11 G90 G54 G00 X6.Y6

N12 G43 Z.1 H01 M08 T99  } Preload Dummy Tool

N13 G99 G81 R.1 Z-1 F10.

N14 G80 Z1. M09

N15 G00 G91 G28 Z0

N16 M06     } Tool Change at End of Tape

N17 M30
## **Output Debug**
This option allows you to control the output of post debug code. If you check this option, the post will output debug code. If you uncheck this check box, the post outputs normal code.

The example below shows code output using debug mode.

- The next line after a debug message starts the code output for that template section. Any code output before the first Start Operation message is from the Start Of Tape section.
- If there are two lines of debug messages, there is no code output in that template section. In most posts there is no code output for Start Operation, Every Move and End Operation debug messages.

In the example notice that after the Init Tool Change debug message, lines N2-N5 were output. This means that the code was output from the INIT\_TOOL\_CHANGE section. This allows you to see the flow of the output, for example what happens after a tool change, etc.



O0001

N1 G17 G20 G40 G80

Start Operation    } Debug

Init Tool Change   } Debug

N2 T01 M06

N3 S2000 M03

N4 G54

N5 M08

Every Move    } Debug

Rapid XY Move    } Debug

Rapid From Tool Chan  } Debug

N6 G90 G00 X2.5 Y-1.

Every Move

Rapid Z Move Down

N7 G43 Z.1 H01

Every Move

Z Feed Move

N8 G01 Z-.9 F20.

Every Move

Line Move

N9 G42 D21 X2.5 Y0 F10.

Every Move

Line Move

N10 X4.5

Every Move

Arc Move

N11 G03 X5. Y.5 R.5

Every Move

Line Move

N12 G01 Y4.5

Every Move

Arc Move

N13 G03 X4.5 Y5. R.5

Every Move

Line Move

N14 G01 X.5

Every Move

Arc Move

N15 G03 X0 Y4.5 R.5

Every Move

Line Move

N16 G01 Y.5

Every Move

Arc Move

N17 G03 X.5 Y0 R.5

Every Move

Line Move

N18 G01 X2.5

Every Move

Line Move

N19 G40 Y-1.

Every Move

Rapid Z Move Up

N20 G00 Z5. M09

End Operation

Program End

N21 G91 G28 Z0

N22 G28 X0 Y0

N23 M30
## **Define Compensation Number**
By entering a value in this text box, you control what compensation number is output in the code. In most Fanuc controllers the "D" value is the compensation number. "D01" is offset number "1".

- If the compensation number is zero (0), the "D" number is always the tool number you are using.
- If you enter a number greater than 0, the post will add the tool number to the value you entered in the text box.

The post source code for this post attribute is shown below:

:C: COMP\_OFFSET=0

The following example shows code output for a profile operation with tool number 10 and the compensation number of 20. Notice that the "D" number is 30. The post took the tool number plus the COMP\_OFFSET number and output 30.



Example COMP\_OFFSET=20

O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X5. Y5.

N5 G43 Z.1 H01 M08

N6 G01 Z-1. F10.

N7 G41 D30 X10. Y5. F5.  } "D" offset number

N8 Y10.

N9 X5.

N10 G40 Y5.

N11 G00 Z1. M09

N12 G91 G28 Z0

N13 M30
## **Number of Tools**
This option controls how many tools can be defined in the Mill Tools dialog box. For Fanuc controllers, you have a choice of either 32 or 99.
# <a name="chmtopic76"></a>**Feedrate (Misc. tab)**
This option on the Misc. tab controls the estimated machine time output.

If you check Inches Per Minute, the code will output the estimated machine time in IPM. If you select Inches Per Revolution, the code will output the time in IPR. Most programmers use Inches Per Minute (IPM) for the feedrate input. If you check the IPM check box and you enter IPR for the feedrate input, then the estimated machine time will not be correct.

![image\pin_bl.gif] Estimated machine time is just an estimate. The post does not handle accel and decel times. If you need a more accurate machine time, contact your dealer.
# <a name="chmtopic79"></a>**Setup Tab**


The Setup tab allows you to [set parameters](#chmtopic78) that provide:

- Information required to generate the NC program. The options vary depending on the machine. You can use the Setup tab to determine which information the user will have to provide when an operation is created in ProCAM and CAMWorks.

If the following options have a check in the Prompt For check box, they will display in the CAMWorks Controller Parameters tab. For checked options, you can also specify a default value to display in the dialog box.

- Program Number
- Material Type
- Material Thickness
- ISO9000 options
- Information for the Setup Sheet, a file that is created when the NC program file is generated. If the following options have a check in the Prompt For check box, they will be included in the Setup Sheet:
- Program Number
- Material Type
- Material Thickness
- Information for programmers that use ISO9000. The following information is normally output in the Start of Tape section:
- Part Number
- Part Name
- Programmer
- Customer Name
- Operation Number
- Date
## **Setup Code Window**
As you select options or type information in the Setup tab, the Setup Code window displays the Post Processor Language to achieve the changes you are making. It is not necessary that you understand this code. It may be of interest to advanced users who plan to modify the source file after using the UPG to initially customize the post processor.
# <a name="chmtopic78"></a>**Changing Setup Parameters**
The following options can be selected on the Setup tab:
## **Program Number**
If Prompt For is checked, the post will use the program number specified by the user in the CAMWorks Controller Parameters tab. The Default Program Number option in the Setup tab allows you to set a default value from 1 - 9999.

This parameter is used mainly for the very first line of output and is output in the Setup Sheet. For example:

O0001    } Program Number

N1 G20 G40 G80 G90

If the Prompt For is unchecked, the post will always default to 1.
## **Program Name**
If Prompt For is checked, the post will use the program name specified by the user in the CAMWorks Controller Parameters tab. The Default Program Name option in the Setup tab allows you to set a default program name (maximum 8 characters).



This parameter is used if the programmer wants a program identification number. For example:

O0001

(JLKM9000)  } Program Name

N1 G20 G40 G80 G90

If the Prompt For is unchecked, the Program Name button will be disabled in the Sections tab.
## **Material Type**
If Prompt For is checked, the post will use the material type specified by the user in the CAMWorks Controller Parameters tab. The Default Material Type option in the Setup tab allows you to set a default material type (maximum 25 characters).

This parameter is used by the optional ProCAM Feeds and Speed Library. The material type is also output in the Setup Sheet. For example:

(MATERIAL=STEEL)

If the Prompt For is unchecked, the post will always default to steel.
## **Material Thickness**
If Prompt For is checked, the post will use the material thickness specified by the user in the CAMWorks Controller Parameters tab. The Default Material Thickness option in the Setup tab allows you to set a default material thickness (decimal value).

This value is output in the Setup Sheet. For example:

(THICKNESS=.5)

If the Prompt For is unchecked, the post will always default to 1.
## **Chord Distance**
If Prompt For is checked, the post will use the chord distance specified by the user in the CAMWorks Controller Parameters tab. The Default Chord Distance is a decimal value. This option should be checked only if you need to break up arc moves into line moves. You cannot check this check box unless you have selected Simulate With Linear Moves for the Arc Quadrants option on the Header tab.
## **Part Number**
If Prompt For is checked, the post will use the part number specified by the user in the CAMWorks Controller Parameters tab. The Default Part Number option in the Setup tab allows you to set a default part number (maximum 25 characters).

This parameter is used for programmers that use ISO9000. For example:

O0001

(BMJTJ999-10896)

If the Prompt For is unchecked, the Part Number button will be disabled in the Sections tab.
## **Part Name**
If Prompt For is checked, the post will use the part name specified by the user in the CAMWorks Controller Parameters tab. The Default Part Name option in the Setup tab allows you to set a default part name (maximum 25 characters).

You would normally output the information in the Start of Tape section.

O0001

(FLANGE HOUSING)

If the Prompt For is unchecked, the Part Name button will be disabled in the Sections tab.
## **Customer Name**
If Prompt For is checked, the post will use the customer name specified by the user in the CAMWorks Controller Parameters tab. The Default Customer Name option in the Setup tab allows you to set a default customer name (maximum 60 characters).

This parameter is used for programmers that use ISO9000. For example:

O0001

(ALFREDS CUSTOM MACHINE SHOP)

If the Prompt For is unchecked, the Customer Name button will be disabled in the Sections tab.
## **Programmer**
If Prompt For is checked, the post will use the programmer specified by the user in the CAMWorks Controller Parameters tab. The Default Programmer option in the Setup tab allows you to set a default programmer (maximum 25 characters).

This parameter is used for programmers that use ISO9000. For example:

O0001

(JOHN SMITH)

If the Prompt For is unchecked, the Programmer button will be disabled in the Sections tab.
## **Operation No.**
If Prompt For is checked, the post will use the operation number specified by the user in the CAMWorks Controller Parameters tab. The Default Operation Number option in the Setup tab allows you to set a default operation number (maximum 60 characters).

This parameter is used for programmers that use ISO9000. For example:

O0001

FINISH MILLING FRONT FACE)

If the Prompt For is unchecked, the Operation No. button will be disabled in the Sections tab.
## **Date**
If Prompt For is checked, the post will use the date specified by the user in the CAMWorks Controller Parameters tab. The Default Date option allows you to set a default date (maximum 25 characters).

This parameter is used for programmers that use ISO9000. For example:

O0001

(AUG. 25th, 1997)

If the Prompt For is unchecked, the Date button will be disabled in the Sections tab.
## **Controller Parameters Tab**
When you select the Select Post Processor command on the shortcut menu, then select the Parameters tab, the information required to generate the NC program displays. The options vary depending on the machine. This dialog box also provides information for the Setup sheet, a file that is created when the NC program file is generated.
# <a name="chmtopic83"></a>**Attributes Tab**
**ProCAM** Attributes are non-geometric properties, values and identifiers that are attached to geometric entities. Inserted attributes can be attached to entities before, during or after the entity is output in the NC code. The Insert Attribute command on the Mill toolbar allows you to insert either a single attribute or a sequence of attributes (attribute list).

The Attributes tab allows you to [control which attributes are available](#chmtopic82) in the ProCAM system and what G code is output for the attribute.


## **Attribute Code Window**
As you select options or type information in the Attribute tab, the Attribute Code window displays the Post Processor Language that is created to achieve the changes you are making. It is not necessary that you understand this code. It may be of interest to advanced users who plan to modify the source file after using the UPG to initially customize the post processor
# <a name="chmtopic82"></a>**Changing Attributes**
The following attributes on the Attributes tab can be available as attachable attributes in ProCAM:
## **Program Stop**
If Make Available in CAM is checked, the program stop will be available as an attachable attribute in the ProCAM Select Attribute dialog box.

The Program Stop Code text box allows you to define the G code output for the program stop attribute. The Program Stop Code will be output at the location in the tool path where the attribute is attached.

For example, on most Fanuc controllers, the program stop code is "M00". When the program stop is encountered, the machine will stop. The operator must press cycle start to continue running the program.

If program stop is not checked, the program stop attribute will not display in the Select Attribute dialog box.
## **Optional Stop**
If Make Available in CAM is checked, the optional stop will be available as an attachable attribute in the ProCAM Select Attribute dialog box.

The Optional Stop Code text box allows you to define the G code output for the optional stop attribute. The Optional Stop Code will be output at the location in the tool path where the attribute is attached.

For example, on most Fanuc controllers, the program stop code is "M01". When the program stop is encountered and if the operator has the option stop toggle switch set to on, the machine will stop. The operator must press cycle start to continue running the program.

If optional stop is not checked, the optional stop attribute will not display in the Select Attribute dialog box.
# <a name="chmtopic96"></a>**Mill 2D, Mill 3D, Drill/Tap, Bore/Ream Tabs**


Operations in the CAM system are classified by type: profile, pocket, drill, etc. When an operation is inserted, the user provides information about the operation that is required by the post processor. This information is controlled using the Mill 2D, Mill 3D, Drill/Tap and Ream/Bore tabs.

The Mill 2D, Mill 3D, Drill/Tap, and Bore/Ream tabs control the following information required to generate the NC program:

- [Absolute or incremental](#chmtopic86) code output
- [Work Coordinate on/off](#chmtopic87)
- [Coolant](#chmtopic88)
- [X/Y Tool Change Position](#chmtopic89)
- [Machine Compensation](#chmtopic90)
- [Display Tool Offset](#chmtopic91)
- [Rigid Tap](#chmtopic92)
- [Dwell](#chmtopic93)
- [Shift Amount](#chmtopic94)
- [Use Work Coordinate](#chmtopic95)

The post outputs code by default for all of the options on these tabs, except X and Y Tool Change Position. These tabs allow you to decide which options the user will have the ability to set when an operation is created in CAMWorks.

Options that are checked will display on the Post tab in the CAMWorks Machining Parameters dialog box.
## **Source Code Window**
As you select options or type information in the Mill 2D, Mill 3D, Drill/Tap or Bore/Ream tabs, the Source Code window displays the Post Processor Language to achieve the changes you are making. It is not necessary that you understand this code. It may be of interest to advanced users who plan to modify the source file after using the UPG to initially customize the post processor.
# <a name="chmtopic86"></a>**Absolute or Incremental**
The Absolute or Incremental option can be set for:

- Pocket, Lace, Profile and Miscellaneous operations on the Mill 2D tab
- All Surface operations on the Mill 3D tab
- All drill type operations on the Drill/Tap and Bore/Ream tabs

If Absolute or Incremental is checked, when you create an operation, you can select whether the code should be output in absolute or incremental format. For example, in most Fanuc controllers the G code for absolute output is "G90" and incremental output is "G91". The post will output "G90" or "G91" and the corresponding X,Y and Z values according to the user's selection.

If Absolute or Incremental is not selected, the code is always output in absolute format.
# <a name="chmtopic88"></a>**Coolant**
The Coolant option can be set for:

- Pocket, Lace, Profile and Miscellaneous operations on the Mill 2D tab
- All Surface operations on the Mill 3D tab
- All drill type operations on the Drill/Tap, and Bore/Ream tabs

If Coolant is checked, when you create an operation, you can set the coolant to on, off, flood, mist or through hole so that the appropriate code will be output. For example, most Fanuc controllers use M08 for coolant on, M09 for coolant off, M07 for mist and M50 for through hole.

If Coolant is not selected, the code for coolant on will always be output.
# <a name="chmtopic91"></a>**Display Tool Offset**
The Display Tool Offset option can be set for the Profile operation on the Mill 2D tab.

This option applies when Machine Compensation is used. With machine compensation the tool path is output to the controller with the tool path centerline down the boundary centerline. The controller is told the machine compensation is either to the left or right and the controller does the tool path compensation.

Since there is no system compensation with machine compensation, the tool path displayed on the boundary centerline can be confusing. The Display Tool Offset options tells the CAM system to display the tool path in its compensated position.

- If Display Tool Offset is checked, when you create an operation, you can specify whether the tool offset display should be turned on or off. If the parameter is set to Yes, the CAM system will display the tool path in its compensated position. If the parameter is set to No, the CAM system will display the tool path on the boundary centerline.
- If Display Tool Offset is not checked, the tool path centerline is always displayed on the boundary centerline.
# <a name="chmtopic93"></a>**Dwell**
The Dwell option can be set for:

- Spot drilling on the Drill, Tap tab
- Bore w/dwell and Ream w/dwell operations on the Bore/ Ream tab

If Dwell is checked, when you create an operation, you can specify the dwell time to be output during the cycle.

For Fanuc, an integer is entered for the dwell which represents 1000ths of a second. For example, if 2 is entered for dwell, the following code will be output:

N10 G90 G99 G82 X10. Y10. R.1 Z-1. **P2000** F10.

If Dwell is not checked, the code will always output a dwell time of zero.
# <a name="chmtopic90"></a>**Machine Compensation**
The Machine Compensation option can be set for the Profile operation on the Mill 2D tab.

If Machine Compensation is checked, when you create an operation, you can specify the compensation code that is output. If set to off, code is output to turn compensation off; if set to on, code is output to turn compensation on; if set to left or right, code is output for machine compensation to either the left or the right of the tool path.

For example, most Fanuc controllers use the following G code to control machine compensation:

|Machine Compensation|G Code Output|
| :- | :- |
|off|G40|
|left|G41|
|right|G42|
|on|G41 or G42 depending on which compensation side is indicated by the digitize|



If Machine Compensation is not selected, the code always outputs compensation on.
# <a name="chmtopic92"></a>**Rigid Tap**
The Rigid Tap option can be set for Tapping and reverse tapping operations on the Drill/Tap tab.

If Rigid Tap is checked, when you create an operation, you can specify whether code should be output for a rigid tap cycle.

If the parameter is set to Yes, the post will see if a section called "rigid tapping cycle" or "reverse rigid tapping cycle" exists, if not the tapping cycle is called.

If set to No, the section for outputting the standard float tapping cycle will always be called to output code for the tapping cycle.
# <a name="chmtopic94"></a>**Shift Amount**
The Shift Amount option can be set for Back Boring and Fine Boring operations on the Bore/Ream tab.

If Shift Amount is checked, when you create an operation, you can specify the shift amount to be output during the cycle.

For Fanuc, a decimal value is entered. For example, if .01 is entered for shift amount, the following code will be output:

N10 G90 G99 G87 X10. Y10. R.1 Z-1. **Q.01** F10.



If Shift Amount is not checked, a default shift amount of 1" is always used.
# <a name="chmtopic95"></a>**Use Work Coordinate**
The Using Work Coordinate option can be set for the Macro operation on the Mill 2D tab.



**ProCAM** If Use Work Coordinate is checked, when you create an operation, you can specify whether the code should output work coordinates in macro calls. If the parameter is set to Yes, the post will output work coordinates in macro calls. If set to No, the post will not output work coordinates in macro calls.

If you are customizing a post processor to use work coordinates in macro calls, see the [Macro sections](#chmtopic63) topics.
# <a name="chmtopic87"></a>**Work Coordinate**
The Work Coordinate option can be set for:

- Pocket, Lace, Profile and Miscellaneous operations on the Mill 2D tab
- All Surface operations on the Mill 3D tab
- All drill type operations on the Drill/Tap, and Bore/Ream tabs

If Work Coordinate is checked, when you create an operation, you can select the work coordinate value the code should output. For example, most Fanuc controllers have work coordinate numbers from 54 to 59. If a work coordinate of 54 is entered, the post will output G54.

If Work Coordinate is not selected, the code will always output 54.
# <a name="chmtopic89"></a>**X/Y Tool Change Position**
The X/Y Tool Change Position option can be set for:

- Pocket, Lace, Profile and Miscellaneous operations on the Mill 2D tab
- All Surface operations on the Mill 3D tab
- All drill type operations on the Drill/Tap, and Bore/Ream tabs

If X/Y Tool Change Position is checked:

- The code to output the tool change positions must be added to the Init Tool Change and Sub Tool Change sections.
- When you create an operation, you can specify the X/Y tool change positions to be output in the code. If no position is specified, the code outputs X1Y1.

If X/Y Tool Change Position is not selected, the code will not output any tool change position.
# <a name="chmtopic115"></a>**Sections Tab**
The Sections tab is used to define post processor sections. Sections consist of several lines of Post Processor Language code that have a specific purpose and are called at a specific time during post processing.

As a part is post processed, sections are called automatically by the post processor as they are needed. For example, if a line cut move is encountered, the Line Move section is called. The Sections tab allows you to define the G code that will be output as each section is called.

The Sections tab groups the sections into the following categories:

[Tool](#chmtopic108)

[Miscellaneous](#chmtopic109)

[Rapid Moves](#chmtopic110)

[Cut Moves](#chmtopic111)

[Drilling](#chmtopic112)

[Drill Patterns](#chmtopic113)

[Macro](#chmtopic63)

[Rotate](#chmtopic114)



The Section tab has four areas: Section categories, the Sections list box, the Section code text box and the G code keyboard.
## **Section Categories**
The Section categories allow you to select the type of section to be defined. When you select a category, the sections for that category display in the Sections list box.

There are several sections in each category. For example, there are five sections in the Tool category: Init Tool, Preload Init Tool Change, Sub Tool Change and Sub Preload Tool Change.
## **Section List**
The Section List displays the sections for the selected Section category. When you select a Section in the list, the G code for that section displays in the Section Code text box.
## **Section Code Text Box**
The Section Code text box lists the Post Processor Language code for the selected section. To change the output for the section, you can modify the code using the G code keyboard or by manually typing the code. The Clear button deletes all code currently displayed in the text box.
## **G Code Keyboard**
The G Code keyboard automatically inserts the most common post processor key words. When you click a button on the keyboard, the G code or symbol shown on the button is inserted at the current cursor position in the Section Code text box. You can also manually type in the key words in the Section Code text box if you prefer.
# <a name="chmtopic117"></a>**Section Syntax**
The post processor uses the Post Processor Language to describe how to output the G code. This language uses a specific syntax.

An example section for Init Tool Change is shown below:

:T:<N><TOOL\_COMMENT><EOL>

:T:<N><T><M:06><EOL>

:T:<N><S!><M!:SPINDLE\_DIR><EOL>

:T:<N><G!:work\_coord><EOL>



Sections are made up of lines of Post Processor Language code. Section lines are made up of statements. Several statements are generally used to define a line of section code. Each line ends with an <EOL> statement.

To define how each line of G code is output, the section statements include:

- variables such as <X> for the X coordinate
- constants such as G: to output the letter "G"
- control syntax such as <EOL> for the end of a line



Each statement defines G code output as explained below:

|**Section Line**|**Possible G Code Output**|
| :- | :- |
|:T:<N><T><M:06><EOL>|N001 T01 M06|



|Section|Description|G Code|
| :- | :- | :- |
|**:T:**|This line of code will output a text line of G code.<br>Text lines handle only integers, decimals and hardcode. When hardcoding text in a text line, all lowercase must be used.| |
|**<N>**|<p>Output a sequence number.</p><p>The sequence number format is defined in the<br>Misc. tab.</p>|N001|
|**<T>**|<p>Current Tool.</p><p>The tool number format is defined using the Post Processor Language and is not available in the Universal Post Generator (i.e., the tool number format is fixed and there is no reason to change it).</p>|T01|
|**<M:06>**|Tool change|M06|
|**<EOL>**|End of line| |


## **Control Syntax**
The following syntax is used in section code lines:

|Syntax|Description|
| :- | :- |
|**L**|<p>Formats the output for leading zeros.</p><p>Example Section</p><p>:SECTION=LINE\_MOVE\_MILL</p><p>:T:<N><G:01> X<”#34L”:ABS\_X\_END><EOL></p><p>Example G Code, where ABS\_X\_END is 1”</p><p>N10 G01 X001</p>|
|**l**|<p>A lowercase "l" formats the output for leading spaces.</p><p>Example Section</p><p>:SECTION=LINE\_MOVE\_MILL</p><p>:T:<N><G:01> X<"#34l":ABS\_X\_END><EOL></p><p>Example G Code, where ABS\_X\_END is 1”</p><p>N10 G01 X\_\_1</p>|
|**N**|<p>An uppercase "N" tells the system not to convert output if decimal.</p><p>Example Section</p><p>:SECTION=LINE\_MOVE\_MILL</p><p>:T:<N><G:01>A<”#33N”:ARC\_START\_ANGLE><EOL></p><p>Example G Code, where A is 180 degrees</p><p>N10 G01 A180</p>|
|**T**|<p>Formats the output for trailing zeros.</p><p>Example Section</p><p>:SECTION=LINE\_MOVE\_MILL</p><p>:T:<N><G:01> X<”#34T”:ABS\_X\_END><EOL></p><p>Example G Code, where ABS\_X\_END is 1”</p><p>N10 G01 X10000</p>|
|**t**|<p>Formats the output for trailing spaces.</p><p>Example Section</p><p>:SECTION=LINE\_MOVE\_MILL</p><p>:T:<N><G:01> X<”#34t”:ABS\_X\_END><EOL></p><p>Example G Code, where ABS\_X\_END is 1”</p><p>N10 G01 X1\_\_\_\_</p>|
|**@**|<p>Formats the output for a space in place of a plus or minus sign if a sign is not output.</p><p>Example Section</p><p>:SECTION=LINE\_MOVE\_MILL</p><p>:T:<N><G:01> X<”#-34@”:ABS\_X\_END><EOL></p><p>Example G Code, where ABS\_X\_END is 1”</p><p>N10 G01 X\_1</p>|
|**-**|<p>Formats the output for a minus sign if number is negative.</p><p>Example Section</p><p>:SECTION=LINE\_MOVE\_MILL</p><p>:T:<N><G:01> X<”#-34”:ABS\_X\_END><EOL></p><p>Example G Code, where ABS\_X\_END is -1”</p><p>N10 G01 X-1</p>|
|**+**|<p>Formats the output to force a plus or minus sign.</p><p>Example Section</p><p>:SECTION=LINE\_MOVE\_MILL</p><p>:T:<N><G:01> X<”#+34”:ABS\_X\_END><EOL></p><p>Example G Code, where ABS\_X\_END is 1”</p><p>N10 G01 X+1</p>|
|**" "**|<p>Double quotation marks are used to group output format.</p><p>Example Section</p><p>#1: Not using HEADER default decimal output</p><p>:SECTION=LINE\_MOVE\_MILL</p><p>:T:<N><G:01> X<"#-34":ABS\_X\_END><EOL></p><p>Example G Code, where ABS\_X\_END is 1.5</p><p>N10 G01 X15</p><p>#2: Using HEADER defaults</p><p>:SECTION=LINE\_MOVE\_MILL</p><p>:T:<N><G:01> X<#:ABS\_X\_END><EOL></p><p>Example G Code, where ABS\_X\_END is 1.5</p><p>N10 G01 X1.5</p>|
|**#**|<p>Formats decimal output.</p><p>Example Section</p><p>#1: Not using HEADER default decimal output</p><p>:SECTION=LINE\_MOVE\_MILL</p><p>:T:<N><G:01> X<"#-34":ABS\_X\_END><EOL></p><p>Example G Code, where ABS\_X\_END is 1.5</p><p>N10 G01 X15</p><p>#2: Using HEADER defaults</p><p>:SECTION=LINE\_MOVE\_MILL</p><p>:T:<N><G:01> X<#:ABS\_X\_END><EOL></p><p>Example G Code, where ABS\_X\_END is 1.5</p><p>N10 G01 X1.5</p>|
|**.**|<p>Formats the output to force a decimal point (.)</p><p>Example Section</p><p>#1: Not using a decimal point</p><p>:SECTION=LINE\_MOVE\_MILL</p><p>:T:<N><G:01> X<”#-34”:ABS\_X\_END><EOL></p><p>Example G Code: N100 G01 X15</p><p>#2: Using a decimal point</p><p>:SECTION=LINE\_MOVE\_MILL</p><p>:T:<N><G:01> X<”#-3.4”:ABS\_X\_END><EOL></p><p>Example G Code: N10 G01 X1.5</p>|
|**%**|<p>Formats the output for an integer.</p><p>Example Section</p><p>#1: Using HEADER default integer output</p><p>:SECTION=START\_OF\_TAPE\_MILL</p><p>:T:O<"%4LT":program\_number><EOL></p><p>Returns: O0001</p><p>#2: Using HEADER defaults</p><p>:SECTION=START\_OF\_TAPE\_MILL</p><p>:T:O<%:program\_number><EOL></p>|
|**!**|<p>Forces non modal output.</p><p>For example, G!:20 outputs G20 in every section this code occurs.</p>|
|**:**|<p>Outputs a constant in modal format.</p><p>For example, G:20 outputs G20. This is a simplified explanation of a complex concept; however, this should be sufficient for most non-programmers.</p>|
|**\***|This is a comment line that will be ignored by the compiler.|


## **Modal/Non Modal Flag**
The Modal/Non Modal flag is set using the two radio buttons in the middle of the G Code keyboard labeled Modal and Non Modal.

- Modal

Modal means that registers set remain set until changed. If the Modal/Non Modal flag is set to Modal, G01 needs to be output only once until a G00, G02, etc. is output.

- Non Modal

Non modal means that registers must be reset each time. If Modal/Non Modal flag is set to Non modal, G01 is output each time a line command is given.

The Modal/Non Modal flag is global. Whatever it is set to covers the entire post processor.
# <a name="chmtopic119"></a>**Editing Section Code**
![image\sectbox1.gif](data:image/gif;base64,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 "image\sectbox1.gif")

When you select a section, the section code displays in the Section code text box.

To start working in this text box, position the I-beam cursor where you want to type, insert or delete, then click the mouse button. A blinking vertical bar (insertion point) indicates where the text you type, cut, copy, insert using the G code keyboard, etc., will start.

![image\pin_bl.gif] **CAUTION!** If you click the Clear button, insert code using the G code keyboard or type new code, there is no way to undo the changes. If you are modifying a database template, reload the template to restore the default code. To restore the original section code from an existing source, close the source file without saving the changes and open the source again.

The procedures for typing text, correcting errors and editing text explained below are similar to most Windows applications.
## **Typing**
To insert text into a section line, position the I-beam cursor where you want to type and click the mouse button, then type the text.

![image\pin_bl.gif] **IMPORTANT!** Use the EOL key on the G code keyboard. If you type <EOL>, you must press the Enter key on the keyboard (to add the carriage return/line feed), then press the Delete key on the keyboard to delete the blank line.
# <a name="chmtopic121"></a>**Selecting Text**
Before you can delete, copy, or cut text, you must select (highlight) the applicable text.

To select text using the mouse:

1. Point to the first character you want to select, then click and hold down the left mouse button.
1. Drag the pointer across the text to the last character you want to select.
1. Release the button.

![image\pin_bl.gif] To cancel highlighted text, click anywhere outside the selection.



To select text using the keyboard:

1. Use the Arrow keys to move the insertion point to the first character you want to select.
1. Press and hold down Shift, then use the Arrow keys to move the insertion point to the last character you want to select.

You can also use Shift + End to select from the insertion point to the end of the line or Shift + Home to select from the insertion point to the beginning of the line.

3. Release the keys.

![image\pin_bl.gif] To cancel the selection, press an Arrow key.
# <a name="chmtopic123"></a>**Inserting a New Line**
If you want to insert a new line of code at the start of a section, position the cursor at the start of the first line and press enter. Move the cursor to the start of the blank line, then insert the code.

If you want to insert a new line of code between existing lines, position the cursor at the *end* of the code line before where you want the new line or the start of the line that you want to come after the new line, then press Enter. For example, to insert a blank line between the third and fourth lines below, you could position the cursor at the end of line 3, then press Enter.



![image\sectbox2.gif](data:image/gif;base64,R0lGODlhYwJ/APcAAAAAABAQECEhISkpKTExMUJCQkpKSlJSUlpaWmNjY2tra3Nzc3t7e4SEhIyMjJSUlJycnKWlpa2trbW1tb29vcbGxs7OztbW1t7e3ufn5+/v7/f39////wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAEAABwALAAAAABjAn8AAAj+ACtQEEih4ECDBQkaVKhw4cGGCB0ihEgQYsSJDyNavJjwIMaPHCWG7EjxokCGI0daPOlRJEqWIFPKnEmzps2bOHPq3Mmzp8+fQHWy3Bi0aE+YDkuSdJlRY0akHWMuHdoUY0mqUKG2rPjUKVarSVuK/fp1qsmtIsGCJduVrdu2cN/KjUt3rt26eO/qzct3r9++gNmeDUz4r+HBYaMy5aj17MuwRBkrrirzatqQjRFPlhpZsueGKD+CFmu0tOnTqFOrXs06JdfWsCUrvRwasuiutDGbzaxUcO7dlLlSjTk8ON7biB9r9ni4eeHnzqNDny69OvXrd70e5MC9u/fv4MP+ix9Pvjx5AImZ1s5MWjdI4TWLb1ZJunblmVpXLnfdvrh93JfFJuCABBZo4IG2RcQBBhlg4OCDEEYoYYMPUiihgxQ2qCGGF3LYYYQMoDcWWu85hpZvSBE1l3bAyZeiRCjSlV5Vr8EIV4IlRqXfY9b1iN2PPgYJ5JBCFklZWAvmSOKIOOI343oGNSDib4vNOJ9n6h3JH5PxOXUllvd5GSB7YKq1JHJfIqjmmmy26aZ2DS34omK1JQDAnQgIdCecN/ZXpUAhVpBfesqZ2aKYncEn32++0WlbWccxh6hxb62l5KKbGakpkZxu6mmnoBp5VpJ/pmWnAxQsAECed2Lq3lL+jiomJYv1jTkZmbCS6KpsJ3YJpU2dzTfnfvSpWKWlub6p7LLMNntajXIuaV8FqjpA1Z6DwfTiaLEeFGKys422UW8Anmlio5lGau6KMpYb2qDtmtWtjsspGuq9n+aL7776buoUqd1yiwAAFu0pkJ0ALJCQAwPfiSoFdyaAwKUizZrcusgGiCWPWhYrJk1QBvsxseZayZ9+jo5bq7Mst+zyy7rBFO2vk2GbUasUDLyAqgrn/AAFDxjsMI2lBurfpNzSWmnJ5/ZJdKT/SRrj0U87zS6huQ3Kcb/8ds31116HfbVBAJ/5ksERYas2egI5sEDDBaFdqqxTcmYrmu1tbGn+jU5KFeaIIo+sMdODfzapyXwHDvPijDce21CkTpuWzR0JfeflBamagAM4U04zSt8edDnbGAtHea2QzoaQzYKF29S1IqouF86wog376JAuhTNLo7ONreodWwb28GIXT/zxoCIU7a2LVYtU56SLLuLaw9JsMcTT111o3FMeHez2Q+0+0u8ln449+DWxDpL53J+cdt3YG7Qn7ZRmjKvj+Oevf1AERU5x5QCwlgJahS2dcS57brPc/9BitPNhzStyE5y9hHWR08EngrqKX/hidzFJ3Sx6jrLdQ0TIt6iIkITkk2CZ7IW8FhrvhS6MYZ8qsLyAuaRhq0LV7xqGgJ+l6k7+qsqeDbt1vRRyD22jO6IGk1iB3nGEidhDIhOT+L7sKXB+p3OinjAXPyxW0IpXZF8WMbdFBa4OflGUouXImEbfcXF/cIyjHG/SPwzMTVp3/FweHRK6MpIujNxrohvj10UCEswjayOkFws5EPEJspGDxOIjN9g+6kmyLdAjmBdJCEneCTGR4nOgJzXZvUKSconosZwMVwnDVrJShgVJkh6HiEdazrIl1wPgETFHP0Wm8pCL9FwEoedALFJRfmBcY/vet8ViWjEliWQk+wgZyEI2U5hoTKQgefnJbh5zjuAMpzhpyIAGlPOc5kwnOtepznay853ujCc852lOgj1vkLr+BOA1uwnJDzoElPyklyCbaUJV+pORqCTdcBT4yEvCboQB9aIndQRIRjYUmL+00StdydGNenRfvQupSEdK0pKa9KQkRSZBAXnRSkZSiGfcZz9ZOsZqbjKj75vpS6mpkWjeNCSUoylOVerSorYUoRKdpjiXytSmOus1fhzlIbc5VUNG1Zm3q+rlTtK7q27wqlYVJSS3OlaMDtSRWD0f9LDiSNyVdYtZNaszt0rMNr61o3j9qF7zyteNOvWvzOKKUgFL2MIa9nEP2ati+9q1rjJ2sZB9rGQj66PDWvaymM2sZsFJ2cl6trOg/axoQ0varm32tKhNrWpX+7gK0PO18oz+LWxnK9va0va2ts0tbner297y9re+DS5whyvc4hL3uMZNLnKXq9zmMve5zk0nBwoSIpRa97rYza52t8vd7nr3u+ANr3jHS97ymve86E2vetfL3uxiYLoUkJJ55kvf+tr3vvjNr373y9/++ve/AA6wgAdM4AIb+MAITvB/PwShBgHgvQMJkYInTOEKW/jCGM6whjfM4Q57OMPvNU+IIEwBCX/4xChOsYpXzOIWu/jFKoZw1KREYvnC+MY4zrGOd8zjHvt4vyTulWsBkIHpDvk7I53vnSDAnTvdN8nTrS4DKOCdEt9pyt1xMn2rC4AGdMfKAMByk7XMgcuNGQBZ1nL+SMfM5DKjGcr1XTN3wCxmN//4znjOs55BbOQAjRi+JgYPmZWsZjTnd9BNbEBBpERDDiR60QQb85YjDYEwO7rLkG405qZrZjejh9OFFnSo06zfQXPn0fGNtJ33zOpWu/rV9w2yuFJdY0OLujwlTjMAmKxlBjQ6PLn2zqBD1GaIMYA7xJ6zpVddngh8+jvJ5vSxPR0BDlS60ACo9rUNbWpP89rWzOaAr8cT7HAje9fKnna3xw3rdrv73T1+L0xAaGUZm3jQ+La1s8k8ulVfrs3d2Te4w51vSZPa3OIJtLDBXWhziltK3O7yscs56oU7ueC6Bjh3BH7whXsc4f+Gt8j+R07yDwc5ig6hMaAj/nFJX5sBEaAym3etZQpAAOJMfnnMkczwnhvc4N0OT9AxvuQ3X3vmZT66pztddKX/fLo3X7K1r7zzMzPd5wi3Oc5LzvWue73AMrYrQf4MafEM/dke73eVL452nrfc31gP+q3nDvRUVhp7Y4bY3StOarU//ctsl/nbn8737+D964hPvOLpS2KRRunBRlb44Llz7QZo3Mnb7k7U0V15jRM+7qAntNBDb+ZQl57lbs98xym/9c5PnugDZ73UF0/72tNe3nQhu5XNHnvNdxruEUe3d1S/eim1udLTNj7lly3379wdPNFGvqRPP322/x34bw/58H/+323lT13dsde+7cdPfq6fPCQqLzvBsf7laa9a6ewGtvuf7kyZ1//6vKfh0e9vZyl5OdT+B3dz53ThFn/gUW7dxn/r9mvl14AO2G5hRxYhUmQRhnqfdx621nzlYWp0xoAdqGu/l3CXw24f6HLoFmqV9m1WV3EYh19yFmVX9msv+IA0WIOsRoEyoXuSZ4M82IM++IMahgG0BXnqB4RGeIRImIT8hV321nvtJlJKGIVSOIUAxmANRoS7R4VauIVc6IAhVh66Z2NdOIZkWIYkF4FtMYGR54Rm2IZu+IY6dn4coYMDB2cY2GYaOHozSGgZuG5X5nut4oK9035XJnh5CIf+iJiIFYZ7bJF+qcZ79nV1pcaGG7gnoDZwzgYBzlZtTQQBTTR/9NVtqMZo+KeIpniKCCaHF0F2RzZ6uOZ+IddrDGh4oDhss1hlsHgn2haC4sZtExd7BkiLq3duxcZ8wHiLU3g5AXAAFmBfGBAAE9AdG+AdA6AAqHiN3oGGw+GI98Z+zMZxVgd8ngeOqyd+G8d9Evdwpsdy3WaOHECO7Rh6PCd8WrgqFQABBAAA0UhfGmAAF8AdAjB/CiAB2FiQqjgRYWiB6zd1YVZ1bpaCNbd5OUd1gkd/EsmQMGeINJd061h9UuJ+Wid1OqeRagd7B3iRVNhl3SEABtAdF1ABX8j+AS9ZZILmZeKhAQMBHhlAARpAHgLBeI32k94hED35HRXwjwXpaowIF6y4g/hniW7nd8r2Zm03eaDmZhWZdzR3eAcXeMZmeIFHd+WokGBJiUC4bBxQAAXAARqQj3dyANxRAJcjAeezdGt5JzYpAQFwJwEgbwEgAZsGHg+wlwAQADSEliqplvlIABogAHzZk884l02mAHsJikmZZweJENzohEHneqRGfBfpmYMXmnh5eVRJlW5nZxVHml1mmmJZeLJHj1KokhyQAQGwABxgAAHQjBYQZk30ADKZARkQNDJHm5fmZRcAAAegAf0YADipnMwZAAQAHhPQZT1ZbWVmk2X+dmxy6WVCCAD/GI0aIJ1FJiXNeCcWwJyX2Wra+BRqWISpGR7Eh21n5nnE93myyZB96GnmZmOW5p/BZ5/oCB7eJ30gN3v1WAAMsAABEADCGUDdYQACkAEAYI3d0USaNn+WxqAumW0Q02g7OAADIGiw6GUEIAABp2ocUJ1IyQEBkABlhgDr+WqZaRBNqZAtOGe5uHyGFoy4GJ/ihow6SmoBiILZVmm7GHPL5qPtN4yg1kzXx6SzKQBq6QA92USCJ2GAKQD7CDHFqZ3ZmZZrmWWK9mximGWWaZyJOabccQAAQAD/eKYEcJdgOqN6tpRfsZkX6KQtd4iQeGholoIC2Iv+aCllgOp3Jbh0fqqEaKlsv2ZjGWAA2cZpGSps3DmdZPqh3HGmTVan24mmYvodFjAARKZwavmpdspqNUpdWMipqVqPdaoBCdMdIkqNa4mlnSpsXqYqRVmdE+Cl5wYeA4CiSDZtsmqibNodssoAvsodsoqbxnlqr+pj7QkT6deK07qFjcodlBkBFSCp0UgAETABL0qpABkAFLCPlmabBnCPATCiGLqpsdebBjABE2AARUYA6DoB3Rmq3HEB9Ro01Sai9joADoqq3ME52JmtObaqQ0ZiTsmwSVgAC+sdDbCXXFqbkgoABtCTF1AASHkBjhkA/0ix/+qWCeCxILtxmPr+HRNAqhz7jxeQjwJgAeLKAQpgoY5GqgFgoRrQMHAalxV7AQHgqRLbYnjaFQl5tO62qF04AC3KtC62qrS2hlILa067hQygs1eLtH0mgUS2cl3ralmrhUI6tidGtUtrcYNoHrNXtucWg6WIgX1IlnHrmyuonYWGh8EHlQcqlfPot9gmt0/WtjAYZhopemi7uKnoaHRxrRGbtZJ4X99ylQjntpYYRVH6aYenZQZKn4MaKNfnp72maqP2lYULHqNoumY5t4z7uvyltlgYuWaJgFIni+S2o3MnpVGma7sIm2fXlQE6qKgbj4pbvBaIu+Jhu9AnfMgLfbMIt7A7veNRrR7+4YgAmn36ho7W523fAY9+W3f5Cb4OR3Goh21ZyW/nS33MBryt277rK7zjO6BA6r70KL3Um7/ZCF8qcaN7aoINqZEQaWghyXkUCYh4u6nTVsATGcBpVmkcaWgO934jKIOGVmk2ubc0l7x2u4d9Gr9TZ5MMjJEOKWcmaXgXaWrjZR4wqb8G6bhsQYd/ynNZqZq8iHfh+2UQJ3wMAIo4XJVYuZW9ZpnTtcN8O4LCu3Q/576KO6i9Y5k/XMPGm8TL270g+F3hUZS5ymMhRcTeocUunGJUi72c2XuiaWeg2XqlCWydpomap8atmXbd68ZVDJsCqHrqO7rvm8cCCDFgypr+lvd68uh8W4e/+AXBoMrFeXIQNBkeRHu2Ybxh1nsS74mtQOp89Ht1+XmfgrzJA8q+ihu82Ldqn6jHilvKgyqo3rt9fGyxwve54YeghnxfZ2qdLewdO9nILgnJjha13LGTRZnLuEwBjSzMNXmTxHyhKvrLyfwdwBzJCoaDKSHDCzmMzMuQyHa2tqt/tKm88kekKjlqhcbNGdx7o6Z0pVucsay4lTuobkZO2qy7a4dR6gy9l2xgOxxpb0qYBMmWbnonjCluCfDPB/sdBSAAhDkARRYiQeOcGvDPb9qTQRMxHDDRAACjSOap+kiY1phGx/bQlxPQDF2YYAzNYDeEtfb+v5fbcXALZoj5vql3giDs0vL8cXw8OvFnwoYraoTrzgYaZ4abqB7MpwVWywodqQDQk5TJm+UqJcCZnJZ5okVmAdLJAVLSsUW21BxA1TDKsbV5mC2ZAbdYmGrJpgCg0LmZ1ObKrbu51U3NsRqgyyZdYExotXMNY7NsXwq3bBhKoQurKr3YHXMKHqeasKUatmw5qdwB2AIQ0ADp2IJWANLVZNMWr8Ca2H+NZmp41wlGZZ49XaD92RQAsTDN2RqW1/VVyyLsRoMohoXtHa/tpWJIVWZGtEX7rw1qtNsappxGZfF6aWvmqqYtYKId2sZNZSl9tFCYZ6hNX7Vc2cB0i67+nazcMdinRjCBpqngoQEhgtHcfdHHXKzXTUOXrd2uPNwIVtzqPV0UaMnojXh7vdo8OavQZmvWDdtsCthi+KzjAdjd4d+6Gt7A+tv8Xd/vXWDrvd6kfeCK52wHUAHnCd3k1GUVMAEWOt2EHQDeqirWeKb+V+EWujkVMKwcIOIkjmQE0ADpRGV8HWkYcNY/+eEWLq8MTmAJftzJXeNfN0DKmZbY+bFIebGFmbLv2LI5S9gCwLM2GQEtu6l7+aI9mQB7CbUlPuW+LKZlbbImK5MrywF6CQDEKuRQXuQ6HmA3XtxNGLiAy3t8q19cprelDdSnHecraGt0lrhmeN9lrnj+Zx7aOEi7kWjH5jEr3+e6kzjngqi6mJZqmkbnRvjae454ff7ZOX7Pwlifq8a75abKlt5fzQ2o2Zy7ThptzwttvPyDRx7pfH7crD7adp2jZAa+3euO4PunYZmJBrdvAHdl/xeou52iCazr3iHsY1ZO8orOCHqOrTyWepyfqv7s+jXpoL3g1QzAGfnAGzxnrHntpTjBmDepIeJluJ6CuI6VWmm0y+eJlkbur7xr5Q6VxAZx2g7H3K6oOGq3Iwzt+p5f0p7M8GmVOWzDHBiWqal2PQyWx2ZmlSvOdevFf8fwdUfFgEeVUrzOEn+An77vDN7vC2LXYgmIgfyZvwfIGkf+6AZHxwuXib8U8fAb8MMI8e68mnAc8qZ88W+c7Bqf8+TR79T+8ay8n/y5ygjsewurgZmnfTD/kNF6yTDPguvryct+7MsHfjzteTp/9QfY6qye3LA+cNcMf/HsHaKL7AaHPccGcTKHpKqcx5yOyUp6bGrf7hGw9rYWInPvzQdY01MJpQjHu1j/91qv3u3djdqLgUQtYiOInU7fwKy860Dv8hjZaNemcZO/esQGty8o1DsN+Jz/HVZYIbPr6J0/+pEck+OxtqSf+jVOYoMCuaLftEOt+rJPrY5rJtQ8+7h/17I2ImSc+75v0mEnJv77+8Svv40XUgehp8W//LAbdk7+ZKOt+vrMP/3YKGtkRRCuT/3af7XB76UIGfrbH/4Su/v0gvrif/4z2v0Wkf3o3/6XSf7uGbas6v70j43t7WfRX//6b4pCmFtE6N4AwUHgQIIFDR5EmFDhQoYNHT6EGFHiRIoVLV7EmFHjRo4dPX4EGfIiAJIlTZ4EgIEDBQoMUmKAGVOmTAArbVK4mRPnTp09ef70GRToUKFFiR41mhTpUqVNmT51GhXqVKlVqV61mhXrVq1duX71GhbnTLIwM2AAwFLtWpYVKLitoJJlg5QN6YLFK1ZvXr57/fYF/FdwYMKDDRdGfFirSoYu4b6F/Hit3AouM6xsy1atS8WJPXf+Bv1ZdGjSo02XRn1adU+5kNW6VXtXs2a4rV22hh0Z8t3UvVf/9h0c+HDhxYkfP3yZbe62jnU/lkyhNV3Krxmw5Yxcu3Hu2713B/9dfPimKh83yAzb5Wz2cVdWBqDcegMO59OSH58f/379/fn/92+p1lhiAD227oLuOddsqysyBh7EjMCaAgSwQgovtDBDDDfsCjcKGigwvfXYo226BgkEkb7MeOOwRQ1fdDFGGGfUTj4UQ9wMgAR3hIwyy957q0AG6suRRiNlRPJIJZNkMirzdoMQSNlIZIvBAQkccsX7muRySS+7BPNL/q4sUKC1nOMxQROfPA/IliYUM0w546T+c047BfOQPiJhm5JKtZSD70q1IvxwyzoPvTNRRBdVdCgbWSI0SB0V5NFKINPMjlFNG920U05lZJPSN/2sEjO6HmVvPU9X/ZRVV1vVTtDZEBQVOh9TEjLFXHOFE9ZXf/U1WGD9wkBXY3dNi1S1GESp2ZKEhXbYaKeV1ilnnYUt28xcc2+usr4FN1xxxyW3XHPPRTdddddlt11334U3Xnnnpbdee+/FN198MROpX3//BThggQcmuGCDD0Y4YYKVZbhhhx+GOGKJJ6a4YosvxjhjjTfmuGOPPwY5ZJEtTrNWk0tG+WSVU2Z5ZZdbhvllmWOmeWaba8b5Zp1z5nlnn3seBvpnoYMmemiZR0Y6aaWXZrppp5+GOmqpp6aagoAAADs= "image\sectbox2.gif")



Do not use the Blank button on the G code keyboard to insert a new line. The Blank button inserts a <BLANK> code to output a blank line in the G code.
# <a name="chmtopic125"></a>**Undoing Edits**
If you have used the Cut, Copy or Paste commands on the Edit menu, you can use the Undo command on the Edit menu or press Alt + Backspace to undo the last edit command.

When reversing a delete operation, the deleted text is restored in its original format.
# <a name="chmtopic38"></a>**Moving and Copying Text**
You can use the Cut, Copy and Paste commands on the Edit menu to move and copy sections of a program.

- When you move text, you use the Cut command to remove the selected text from one location and insert (paste) it in another location.
- When you copy text, you use the Copy command to make a copy of the selected text and insert it into another location, leaving the original unchanged.

The Cut and Copy functions place the selected text into the Clipboard, a temporary holding area for text. Each time you use the Cut or Copy commands, the selected text replaces the contents of the Clipboard. After you paste that text into a file, a copy remains in the Clipboard, so you can paste the text again whenever you want. The text remains in the Clipboard until you cut or copy again or quit Windows.

You can use the Edit menu commands or the following shortcut keys:

|Press|to|
| :- | :- |
|Shift + Del or<br>Ctrl + X|cut (delete) selected text to the Clipboard|
|Ctrl + Ins or<br>Ctrl + C|copy selected text to the Clipboard|
|Shift + Ins or<br>Ctrl + V|paste (insert) text from the clipboard at the insertion point|



**To cut or copy text into the Clipboard:**

1. Select the text to cut or copy.
1. Choose Cut or Copy on the Edit menu or press Shift + Del (cut) or Ctrl + Ins (copy).

**To paste text from the Clipboard to another location:**

1. Place the insertion point where you want to insert the text.
1. Select Paste on the Edit menu or press Shift + Ins or Ctrl + V.  The text is inserted.

![image\pin_bl.gif] You can also move and copy text from one section to another.
# <a name="chmtopic128"></a>**Deleting Text**
To correct mistakes or delete section code:

|Press|to delete|
| :- | :- |
|Delete or Del|character to the right of the insertion point or selected text|
|Back space|character to the left of the insertion point|
|Shift + Del or Ctrl + X|cuts (deletes) selected text to the clipboard|
|Clear (button at the top of the text box)|all the section code in the text box|



You can also use the Cut and Delete commands on the Edit menu to delete text. For more information on cutting text, see the next section on Moving and Copying Text.
# <a name="chmtopic130"></a>**Using the G Code Keyboard**
You can use the G Code keyboard on the Sections tab to automatically insert common post processor key words. When you click a button on the keyboard, the G code or symbol shown on the button is inserted at the current cursor position in the section code text box.

Buttons that are grayed out (not available) indicate that the options have not been enabled on other tabs.

![image\ebx_1795631195.gif](data:image/gif;base64,R0lGODlhGgAYAPcAAAAAAAgICHt7e729vd7e3v///wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAAAAAAALAAAAAAaABgAAAi8AAcIHEiwoEGDBRIqXMiwYUIAAgsQmEixosWLAgJEJHCwY0EBEAdI9EiQI8eBGTcKDGkwgEuXAk6CVDkAAEuBBFwKzBgg5oCZIk/avAnz5MudGoOuHDoQZlOXHIGOrDk0JE+kPZHSrGqz5ACnO0NO5dr1aUmpQskmLUowpVKqTAmCRZl0agCIdwue/CjWaFOiOtv2bQk4wF4CaA/mJel2asHAHhvvJXlQMuXIYgVo3sy5s2egZEOLjnu5dEAAOw== "image\ebx_1795631195.gif") If you need a quick reminder of the function of a G code or symbol, click the Help button, then click the applicable button on the keyboard. An explanation of the code displays. You can print this information by right clicking in the help popup window and selecting Print Topic on the shortcut menu.
# <a name="chmtopic108"></a>**Tool Sections**
There are four types of tool sections:

[Init Tool Change](#chmtopic132)

[Init Preload Tool Change](#chmtopic133)

[Sub Tool Change](#chmtopic134)

[Sub Preload Too Change](#chmtopic135)



Either Init Tool Change or Init Preload Tool Change is called immediately after the Start of Tape section to load the first tool.

- If there are code blocks in the Init Preload Tool Change section, the Universal Post Generator assumes the user wants to preload tools and this section is called.
- If there are no code blocks in the Init Preload Tool Change section the UPG assumes the user’s machine does not support tool preloading and the Init Tool Change is called instead.
- The exception to this is if no more tools are needed to complete the part, preloading is not required. Therefore, the Init Tool Change section is called.

The same logic is used for tool changes after the first tool change. In this case either the Sub Tool Change section (no preloading) or the Sub Preload Tool Change section (preloading) is called for a tool change.

The UPG uses similar logic throughout a post processor to determine which sections are called to generate the correct output.
# <a name="chmtopic132"></a>**Init Tool Change**
The Initialize Tool Change section loads the first tool to be used. It can also be used to perform other tool-related functions such as starting the spindle, turning the coolant on and outputting tool comments.
## **When Section Is Called**
The Initialize Tool Change is the second section called and is called immediately after the Start of Tape section. This section is called only one time.

- If there is no tool preloading, delete all code blocks from the Init Preload Tool Change section and this section will be called.
- If you want to preload a tool, add the necessary code blocks to the Init Preload Tool Change section and that section will be called.
- If there is only one tool in the part and preloading is not necessary, this section will be called regardless of whether there is code in the Init Preload Tool Change section.
## **Description**

|**Section Lines**|**Possible G Code Output**|
| :- | :- |
|:T:<N><TOOL\_COMMENT><EOL>|N001 (½" ball nose)|
|:T:<N><T><M:06><EOL>|N002 T01 M06|
|:T:<N><S!><M!:SPINDLE\_DIR><EOL>|N003 S1000 M08|
|:T:<N><G!:work\_coord><EOL>|N004 G54|
|:T:<N><M!:COOLANT\_TYPE><EOL>|N005 M08|



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<TOOL\_COMMENT>|Tool comment|½" ball nose|
|<EOL>|End of line| |
|<M:06>|Tool change|M06|
|<S!>|Spindle speed|S1000|
|<M!:SPINDLE\_DIR>|Spindle direction|M03|
|<G!:work\_coord>|Work coordinate|G54|
|<M!:COOLANT\_TYPE>|Type of coolant|M08|

# <a name="chmtopic133"></a>**Init Preload Tool Change**
The Initialize Preload Tool Change section loads the first tool used and then preloads the next tool to be used. It can also be used to perform other tool-related functions such as starting the spindle, turning the coolant on and outputting tool comments.
## **When Section Is Called**
The Init Preload Tool Change is the second section called and is immediately after the Start of Tape section. This section is called only one time.

- If you want to preload a tool, add the necessary code blocks to the Init Preload Tool Change section and that section will be called.
- If there is no tool preloading, delete all code blocks from the Init Preload Tool Change section and the Init Tool Change section will be called.
## **Description**

|**Section Lines**|**Possible G Code Output**|
| :- | :- |
|:T:<N><TOOL\_COMMENT><EOL>|N001 (½" ball nose)|
|:T:<N><T><M:06><EOL>|N002 T01 M06|
|:T:<N><T:NEXT\_TOOL><EOL>|N003 T02|
|T:<N><S!><M!:SPINDLE\_DIR><EOL>|N004 M03|



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<TOOL\_COMMENT>|Tool comment|½" ball nose|
|<EOL>|End of line| |
|<T>|Current tool|T01|
|<M:06>|Tool change|M06|
|<T!:NEXT\_TOOL>|Next tool|T02|
|<S!>|Spindle speed|S1000|
|<M!:SPINDLE\_DIR>|Spindle direction|M03|


## **Comments**
In the above description, notice how the first tool is called and the tool change command given. The second tool is called without a tool change command to preload the tool.
# <a name="chmtopic134"></a>**Sub Tool Change**
The Subsequent Tool Change section loads tools after the first tool. It can also be used to perform other tool-related functions such as starting the spindle, turning the coolant on and outputting tool comments.
## **When Section Is Called**
The Subsequent Tool Change is called at the start of an operation whenever the tool is different from the current tool.

- If you want to preload a tool, add the necessary code blocks to the Sub Preload Tool Change section and that section will be called.
- If there is no tool preloading, delete all code blocks from the Sub Preload Tool Change section and the Sub Tool Change section will be called.
## **Description**

|**Section Lines**|**Possible G Code Output**|
| :- | :- |
|:T:<N><G:00><G:91><G:28> Z0<EOL> |N001 G00 G91 Z0|
|:T:<N><TOOL\_COMMENT><EOL>|N002 (½" ball nose)|
|:T:<N><T><M:06><EOL>|N003 T01 M06|
|T:<N><S!><M!:SPINDLE\_DIR><EOL>|N004 M03|



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Sequence number|N001|
|<G:00>|Rapid move|G00|
|<G:91>|Incremental positioning|G91|
|<G:28>|Return to zero|G28|
|Z0|Rapid to Z0|Z0|
|<EOL>|End of line| |
|<TOOL\_COMMENT>|Tool comment|½" ball nose|
|<T>|Current tool|T01|
|<M:06>|Tool change|M06|
|<S!>|Spindle speed|S1000|
|<M!:SPINDLE\_DIR>|Spindle direction|M03|

# <a name="chmtopic135"></a>**Sub Preload Tool Change**
The Subsequent Preload Tool Change section loads tools after the first tool and then preloads the next tool to be used. This section can also be used to perform other tool-related functions such as starting the spindle, turning the coolant on and outputting tool comments.
## **When Section Is Called**
The Subsequent Tool Change is called at the start of an operation whenever the tool is different from the current tool and a subsequent operation has a different tool to preload.

- If a subsequent operation does not use a different tool, no preloading is required; therefore, the Sub Tool Change section is called.
- If you want to preload a tool, add the necessary code blocks to this section and it will be called. If there is no tool preloading, delete all code blocks from this section and the Sub Tool Change section will be called.
## **Description**

|**Section Lines**|**Possible G Code Output**|
| :- | :- |
|:T:<N><G:00><G:91><G:28> Z0<EOL>|N001 G00 G91 Z0|
|:T:<N><TOOL\_COMMENT><EOL>|N002 (½" ball nose)|
|:T:<N><T><M:06><EOL>|N003 T01 M06|
|:T:<N><T:NEXT\_TOOL><EOL>|N004 T02|



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Sequence number|N001|
|<G:00>|Rapid move|G00|
|<G:91>|Incremental positioning|G91|
|<G:28>|Return to zero|G28|
|Z0|Rapid to Z0|Z0|
|<EOL>|End of line| |
|<TOOL\_COMMENT>|Tool comment|½" ball nose|
|<T>|Current tool number|T01|
|<M:06>|Tool change|M06|
|<S!>|Spindle speed|S1000|
|<T:NEXT\_TOOL>|Next tool number|T02|
## **Comments**
In the above description, notice how the first tool is called and the tool change command given. The second tool is called without a tool change command to preload the tool.
# <a name="chmtopic109"></a>**Miscellaneous Sections**
Miscellaneous sections define the first and last lines of G code output, the absolute preset and the program stop.

There are five types of Miscellaneous sections:

[Start of Tape](#chmtopic141)

The Start of Tape section is always the first section called by the post processor.

**Absolute Preset**

This section is included for future implementation and will not be called by the post processor.

**Program Stop**

This section is included for future implementation and will not be called by the post processor.

[End of Tape](#chmtopic142)

[End of Tape Preload](#chmtopic143)

Either the End of Tape or the End of Tape Preload is the last section called in a part program.
# <a name="chmtopic141"></a>**Start of Tape**
The Start of Tape section is normally used to declare the program name or number and to output safety start up lines.

The Start of Tape section has access to all information in the [Setup tab](#chmtopic79). The Start of Tape section does not have access to any information about the first operation such as tool number, spindle direction, feed and speeds, etc., so no G code dealing with this information can be output by this section.
## **When Section Is Called**
The Start of Tape section is always the first section called and is called only one time.

If there are no code blocks in this section, it will not be called.
## **Description**

|**Section Lines**|**Possible G Code Output**|
| :- | :- |
|:T:O<"%4LT":program\_number><EOL>|N001 O0001|
|:T:<N><G:17><G!:ENGMET><G!:40><G!:80><EOL>|N002 G17 G20 G40 G80|



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|O<"%4LT":program\_number>|Program number|O0001|
|<EOL>|End of line| |
|<G:17>|XY Plane|G17|
|<G!:ENGMET>|Inch/Metric programming|G20|
|<G!:40>|Cancel cutter compensation|G40|
|<G:80>|Cancel fixed cycle|G80|
## **Comments**
**Outputting Setup Tab Information**

If you checked any of the following options for ISO9000 users on the [Setup tab](#chmtopic78), you would normally output the information in the Start of Tape section.

**Part Number**

|Section Line|Possible G Code Output|
| :- | :- |
|:T:<S\_PART\_NUMBER><EOL>|( PART NUMBER=BMJTJ999-10896 )|



**Part Name**

|Section Line|Possible G Code Output|
| :- | :- |
|:T:<S\_PART\_NAME><EOL>|( PART NAME=BMJTJ999-10896 )|



**Programmer**

|Section Line|Possible G Code Output|
| :- | :- |
|:T:<S\_PROGRAMMER><EOL>|( PROGRAMMER=JOHN SMITH )|



**Customer Name**

|Section Line|Possible G Code Output|
| :- | :- |
|:T:<S\_CUSTOMER\_NAME><EOL>|( CUSTOMER NAME=ABC MACHINE SHOP )|



**Operation No.**

|Section Line|Possible G Code Output|
| :- | :- |
|:T:<S\_OPERATION\_NUMBER><EOL>|( OPERATION NUMBER=FINISH MILL FRONT FACE )|



**Date**

|Section Line|Possible G Code Output|
| :- | :- |
|:T:<S\_DATE><EOL>|( DATE=SEPT. 25th, 1997 )|
## **Example**
:0001

( PART NUMBER=BMJTJ999-10896 )   } Part Number

( PART NAME=BMJTJ999-10896)    } Part Name

( PROGRAMMER=JOHN SMITH)    } Programmer

( CUSTOMER NAME=ABC MACHINE SHOP   } Customer Name

( OPERATION NUMBER=FINISH MILL FRONT FACE) } Operation Number

( DATE=SEPT. 25th, 1997)    } Date

N1 G20 G40 G80 G90

N2 T01 M06
# <a name="chmtopic142"></a>**End of Tape**
The End of Tape section is a good place to home Z and XY, turn the coolant off, turn the spindle off and rewind the program.
## **When Section Is Called**
The End of Tape section is always the last section called and is called only one time.

- If you checked the Preload Tool at End of Tape check box in the Misc. tab and there are code blocks in the End of Tape Preload section, the UPG assumes you want to preload the first tool found in the part because the part will be run again.
- If you did not check the Preload Tool at End of Tape check box in the Misc. tab or there are no code blocks in End of Tape Preload section, the UPG assumes no preloading will be done at the end of the program and the End of Tape section is called instead.
- The exception to this is if the last tool used in the part is the same as the first tool used in the part, preloading is not required and the End of Tape section is called.

If there are no code blocks in this section, it will not be called.
## **Description**

|**Section Lines**|**Possible G Code Output**|
| :- | :- |
|:T:<N><G:00><G:91><G:28> Z0<EOL>|N001 G00 G91 G28 Z0|
|:T:<N><G:28> X0 Y0<EOL>|N002 G28 X0 Y0|
|:T:<N><M:30><EOL>|N003 M30|



|Section|Description|G Code Output|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:00>|Rapid mode|G00|
|<G:91>|Incremental positioning|G91|
|<G:28>|Return to zero|G28|
|Z0|Rapid to Z0|Z0|
|<EOL>|End of line| |
|<G:28>|Return to zero|G28|
|X0 Y0|Rapid to X0 Y0|X0 Y0|
|<M:30>|Tape Rewind|M30|


## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 Z.1 M08

N6 G01 Z-1. F20.

N7 X11. F10.

N8 Y11.

N9 X10.

N10 Y10.

N11 G00 Z1. M09

N12 G91 G28 Z0 }

N13 G28 X0 Y0  } End of Tape Section

N14 M30   }
# <a name="chmtopic143"></a>**End of Tape Preload**
The End of Tape Preload section is a good place to home Z and XY, turn the coolant off, turn the spindle off, rewind the program and of course preload the next tool.
## **When This Section Is Called**
The End of Tape Preload section is always the last section called and is called only one time.

- If you checked the Preload Tool at End of Tape check box in the Misc. tab and there are code blocks in the End of Tape Preload section, the UPG assumes you want to preload the first tool found in the part because the part will be run again.
- If you did not check the Preload Tool at End of Tape check box in the Misc. tab or there are no code blocks in End of Tape Preload section the UPG assumes no preloading will be done at the end of the program and the End of Tape section is called instead.
- The exception to this is, if the last tool used in the part is the same as the first tool used in the part, preloading is not required and the End of Tape section is called.

If there are no code blocks in this section, it will not be called.
## **Description**

|**Section Lines**|**Possible G Code Output**|
| :- | :- |
|:T:<N><G:00><G:91><G:28> Z0<EOL>|N001 G00 G91 G28 Z0|
|:T:<N><G:28> X0 Y0<EOL>|N002 G28 X0 Y0|
|:T:<N><M:06><EOL>|N003 M06|
|:T:<N><M:30><EOL>|N004 M30|



|Section|Description|G Code Output|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:00>|Rapid mode|G00|
|<G:91>|Incremental positioning|G91|
|<G:28>|Return to zero|G28|
|Z0|Rapid to Z0|Z0|
|<EOL>|End of line| |
|<G:28>|Return to zero|G28|
|X0 Y0|Rapid to X0 Y0|X0 Y0|
|<M:06>|Preload next tool|M06|
|<M:30>|Tape Rewind|M30|
## **Comments**
Note that the M06 command preloads an already specified tool. The tool to be preloaded would be specified in one of the four tool sections.


## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 T02    } Preload 2nd Tool

N4 S1000 M03

N6 G90 G54 G00 X10. Y10.

N7 G43 Z.1 M08

N8 G01 Z-1. F20.

N9 X11. F10.

N10 Y11.

N11 X10.

N12 Y10.

N13 G00 Z1. M09

N14 G91 G28 Z0

N15 M06

N16 T01    } Preload 1st Tool

N17 S2000 M03

N18 G90 G54 G00 X10. Y10.

N19 G43 Z.1 M08

N20 G01 Z-1. F20.

N21 X21. F10.

N22 Y21.

N23 X20.

N24 Y20.

N25 G00 Z1. M09

N26 G91 G28 Z0    }

N27 T01    }

N28 G28 X0 Y0    } End Of Tape

} Preload Section

N29 M06 }*-*- Load 1st Tool }

N30 M30     }
# <a name="chmtopic110"></a>**Rapid Moves Sections**


For 2½, 3 and multiaxis parts, the Rapid Move sections define how to rapid in/out of a part and to/from tool changes with and without leadins and leadouts.

Sections are called in a predictable order to cut a part. The example below illustrates the order that sections are called to start a part program, make a cut and retract.



|<p>Start of Tape</p><p>Init Tool Change</p><p>Rapid from Tool Change</p><p>Rapid Z Down</p><p>Feed Z Down</p><p>Cut pocket moves</p><p>Rapid Z Up</p><p>Rapid Move</p><p>Rapid Z Down</p><p>Feed Z Down</p><p>Cut pocket moves</p><p>Rapid Z Up</p>|<p>} Initialize part program</p><p>} First tool change</p><p>} X,Y</p><p>} To clearance plane</p><p>} To cut depth</p><p>} Cut part</p><p>} To rapid plane</p><p>} X,Y</p><p>} Rapid Z down</p><p>} To cut depth</p><p>} Cut part</p><p>} To rapid plane</p>|
| :- | :- |



Remember the following definitions when working with rapid sections:

**Rapid plane**

The rapid plane is the absolute Z location at which all XY rapid moves are executed. This is the distance above Z0.000 that the Z axis rapids to in the Tool Offset line on the program.

**Clearance plane**

The clearance plane is the Z plane where the tool is free to rapid vertically at a specific X,Y location to a safe distance above the material without fear of collision.
# <a name="chmtopic149"></a>**1st Rapid Z Down**


The 1st Rapid Z Down section moves from the initial tool change position to the clearance plane after the first rapid X,Y move. This section is where most Fanuc controllers make the tool length callout.
## **When Section Is Called**
The 1st Rapid Z Down section is called after the initial tool change and the first rapid X,Y move. If there is no tool preloading, delete all code blocks from the 1st Rapid Z Down Preload Tool section and this section will be called.

If you want to preload a tool, add the necessary code blocks to the 1st Rapid Z Down Preload Tool section and that section will be called. If there is only one tool in the part and preloading is not necessary, this section will be called regardless of whether there is code in the 1st Rapid Z Down Preload Tool section.
## **Description**
**Section Line**

:T:<N><G:90><G:work\_coord><G:43><G:00><Z!> H<"%2LT":TOOL>

<M:COOLANT\_TYPE><EOL>

**Possible G Code Output**

N001 G90 G54 G43 G00 Z.1 H01 M08



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:90>|Absolute positioning|G90|
|<G:work\_coord>|Work coordinate|G54-G59|
|<G:43>|Tool length compensation +|G43|
|<G:00>|Rapid move|G00|
|<Z!>|Z rapid to clearance plane|Z.1|
|H<"%2LT":TOOL>|Tool length offset|H01|
|<M!:COOLANT\_TYPE>|Type of coolant|M07, M08 or M09|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08 } 1st Rapid Z Down After Tool Change

N6 GO1 Z-1. F10.

N7 X15. Y15. Z-1.25 F20.
# <a name="chmtopic151"></a>**Rapid Z Down Preload Tool**


The 1st Rapid Z Down Preload Tool section moves from the initial tool change position to the clearance plane after the first rapid X,Y move and preloads the next tool. Whether the tool is preloaded in the tool change sections or here is a user preference. This section is where most Fanuc controllers make the tool length callout.
## **When Section Is Called**
The 1st Rapid Z Down Preload Tool section is called after the initial tool change and the first rapid X,Y move. This section is always called unless there are no code blocks in this section.

If you want to preload a tool, add the necessary code blocks to the 1st Rapid Z Down Preload Tool section and that section will be called. If there is no tool preloading, delete all code blocks from the 1st Rapid Z Down Preload Tool section and the 1st Rapid Z Down section will be called.
## **Description**
**Section Line**

:T:<N><G:90><G:work\_coord><G:43><G:00><Z!> H<"%2LT":TOOL>

<M:COOLANT\_TYPE><T!:NEXT\_TOOL><EOL>



**Possible G Code Output**

N001 G90 G54 G43 G00 Z.1 H01 M08 T02



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:90>|Absolute positioning|G90|
|<G:work\_coord>|Work coordinate|G54-G59|
|<G:43>|Tool length compensation|G43|
|<G:00>|Rapid move|G00|
|<Z!>|Z rapid to clearance plane|Z.1|
|H<"%2LT":TOOL>|Tool length offset|H01|
|<M!:COOLANT\_TYPE>|Type of coolant|M07, M08 or M09|
|<EOL>|End of line| |
|<T!:NEXT\_TOOL>|Next tool|T02|
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08 T02 } 1st Rapid Z Down After Tl Change

N6 GO1 Z-1. F10.

N7 X15. Y15. F20.
# <a name="chmtopic153"></a>**5 Axis 1st Rapid Z Down**


The 5 Axis 1st Rapid Z Down section moves from the initial tool change position to the clearance plane after the first rapid X,Y move. This section is where most Fanuc controllers make the tool length callout.
## **When Section Is Called**
The 5 Axis 1st Rapid Z Down section is called after the initial tool change and the first rapid X,Y move and if the following conditions are met:

- In the Header tab, a 4 or 5 Axis Milling option is selected for Multiaxis Milling.
- This is a 5 axis, 4 axis X or 4 axis Y type operation.
## **Description**
**Section Line**

:T:<N><G:90><G:work\_coord><G:43><G:00><Z!>H<"%2LT":TOOL>

<M:COOLANT\_TYPE><EOL>

**Possible G Code Output**

N001 G90 G54 G43 G00 Z.1 H01 M08



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:90>|Absolute positioning|G90|
|<G!:work\_coord>|Work coordinate|G54-G59|
|<G:43>|Tool length compensation +|G43|
|<G:00>|Rapid move|G00|
|<Z!>|Z rapid to clearance plane|Z.1|
|H<"%2LT":TOOL>|Tool length offset|H01|
|<M!:COOLANT\_TYPE>|Type of coolant|M07, M08 or M09|
|<EOL>|End of line| |

# <a name="chmtopic155"></a>**Rapid Z Down**


The Rapid Z Down section rapids the tool from the rapid plane to the clearance plane.
## **When Section Is Called**
The Rapid Z Down section is generally called after an X,Y rapid move and before the feed Z down move of a cutting move (line, arc, drill, etc.).
## **Description**
**Section Line**

:T:<N><G:90><G:00><Z><EOL>



**Possible G Code Output**

N001 G90 G00 Z0.1



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:90>|Absolute positioning|G90|
|<G:00>|Rapid move|G00|
|<Z>|Z rapid to clearance plane|Z.1|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 GO1 Z-1. F10.

N7 X15.

N8 Y20.

N9 G00 Z1.

N10 X50. Y50.

N11 Z.1   } Rapid Z Down

N12 G01 Z-1. F10.

N13 X55. F20.
# <a name="chmtopic157"></a>**5 Axis Rapid Z Down**


The 5 Axis Rapid Z Down section rapids the tool from the Z home position after a tool change or from the rapid plane to the clearance plane after other sections.
## **When Section Is Called**
The 5 Axis Rapid Z Down section is generally called after an X,Y rapid move and before the feed Z down move of a cutting move (line, arc, drill, etc.) and if the following conditions are met:

- In the Header tab, a 4 or 5 Axis Milling option is selected for Multiaxis Milling.
- This is a 5 axis, 4 axis X or 4 axis Y type operation.
## **Description**
**Section Line**

:T:<N><G:90><G:00><Z><EOL>



**Possible G Code Output**

N001 G90 G00 Z0.1



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:90>|Absolute positioning|G90|
|<G:00>|Rapid move|G00|
|<Z>|Z rapid to clearance plane|Z.1|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 GO1 Z-1. F10.

N7 X15.

N8 Y20.

N9 G00 Z1.

N10 X50. Y50.

N11 Z.1    } Rapid Z Down

N12 G01 Z-1. F10.

N13 X55. F20.
# <a name="chmtopic159"></a>**Rapid Z Up**


The Rapid Z Up section rapids the tool from the Z cut depth to the rapid plane.
## **When Section Is Called**
The Rapid Z Up section is called after a cutting move (line, arc, drill, etc.) and before an X,Y rapid move. The Rapid Z Up section is also called after a cutting move and immediately before a tool change if there are no code blocks in the Last Rapid Z Up section.
## **Description**
**Section Line**

:T:<N><G:90><G:00><Z><EOL>



**Possible G Code Output**

N001 G90 G00 Z1.0



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:90>|Absolute positioning|G90|
|<G:00>|Rapid move|G00|
|<Z>|Z rapid to rapid plane|Z1.0|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08   } 1<sup>st</sup> Rapid Z Down After Tool Change

N6 GO1 Z-1. F10.

N7 X15.

N8 Y20.

N9 G00 Z1.    } Rapid Z Up Move

N10 X50. Y50.

N11 Z.1

N12 G01 Z-1. F10.

N13 X55. F20.
## **Comments**
Note that the code blocks are the same for this section and the Rapid Z Down section. This is because the Z value in the variable <Z> is set to the cut depth for Rapid Z Down and to the Rapid Plane for Rapid Z Up.
# <a name="chmtopic161"></a>**5 Axis Rapid Z Up**


The 5 Axis Rapid Z Up section rapids the tool from the Z cut depth to the rapid plane.
## **When Section Is Called**
The 5 Axis Rapid Z Up section is called after a cutting move (line, arc, drill, etc.) and before an X,Y rapid move. The 5 Axis Rapid Z Up section is also called after a cutting move and immediately before a tool change if there are no code blocks in the 5 Axis Last Rapid Z Up section.

The 5 Axis Rapid Z Up section is called if the following conditions are met:

- In the Header tab, a 4 or 5 Axis Milling option is selected for Multiaxis Milling.
- This is a 5 axis, 4 axis X or 4 axis Y type operation.
## **Description**
**Section Line**

:T:<N><G:90><G:00><Z><EOL>



**Possible G Code Output**

N001 G90 G00 Z1.0



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:90>|Absolute positioning|G90|
|<G:00>|Rapid move|G00|
|<Z>|Z rapid to rapid plane|Z1.0|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08  } 1st Rapid Z Down After Tool Change

N6 GO1 Z-1. F10.

N7 X15.

N8 Y20.

N9 G00 Z1.   } Rapid Z Up Move

N10 X50. Y50.

N11 Z.1

N12 G01 Z-1. F10.

N13 X55. F20.
## **Comments**
Note that the code blocks are the same for this section and the 5 Axis Rapid Z Down section. This is because the Z value in the variable <Z> is set to the cut depth for 5 Axis Rapid Z Down and to the Rapid Plane for 5 Axis Rapid Z up.
# <a name="chmtopic163"></a>**Last Rapid Z Up**


The Last Rapid Z Up section rapids the tool from the Z cut depth to the rapid plane immediately before a tool change. This section allows turning the coolant off, spindle off, cancel length compensation, etc., before a tool change.
## **When Section Is Called**
The Last Rapid Z Up section is called after a cutting move (line, arc, drill, etc.) and immediately before a tool change. If there are no code blocks in this section, the Rapid Z Up section is called.
## **Description**
**Section Line**

:T:<N><G:90><G><Z><M:09><EOL>



**Possible G Code Output**

N001 G90 G00 Z1.0 M09



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:90>|Absolute positioning|G90|
|<G:00>|Rapid move|G00|
|<Z>|Z rapid to rapid plane|Z1.0|
|<M:09>|Turn coolant off|M09|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 GO1 Z-1. F10.

N7 X15.

N8 Y20.

N9 G00 Z1. M09   } Last Rapid Z Up Move

N10 G91 G28 Z0

N11 T02 M06

N12 S2000 M03

N13 G90 G55 G00 X15. Y15.

N14 G43 H01 Z.1 M08

N15 GO1 Z-1. F10.

N16 X15.
# <a name="chmtopic165"></a>**5 Axis Last Rapid Z Up**


The 5 Axis Last Rapid Z Up section rapids the tool from the Z cut depth to the rapid plane immediately before a tool change. This section allows turning the coolant off, spindle off, cancel length compensation, etc. before a tool change.
## **When Section Is Called**
The 5 Axis Last Rapid Z Up section is called after a cutting move (line, arc, drill, etc.) and immediately before a tool change if the following conditions are met:

- In the Header tab, a 4 or 5 Axis Milling option is selected for Multiaxis Milling.
- This is a 5 axis, 4 axis X or 4 axis Y type operation.

If there are no code blocks in this section, the Rapid Z Up section is called.
## **Description**
**Section Line**

:T:<N><G:90><G><Z><M:09><EOL>



**Possible G Code Output**

N001 G90 G00 Z1.0 M09



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:90>|Absolute positioning|G90|
|<G:00>|Rapid move|G00|
|<Z>|Z rapid to rapid plane|Z1.0|
|<M:09>|Turn coolant off|M09|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 GO1 Z-1. F10.

N7 X15.

N8 Y20.

N9 G00 Z1. M09  } Last Rapid Z Up Move

N10 G91 G28 Z0

N11 T02 M06

N12 S2000 M03

N13 G90 G55 G00 X15. Y15.

N14 G43 H01 Z.1 M08

N15 GO1 Z-1. F10.

N16 X15.
# <a name="chmtopic167"></a>**Rapid From Tool Change**


The Rapid From Tool Change section moves from the initial tool change position in the X,Y plane. This is a good place to output code for absolute or incremental, work coordinate, spindle speed or spindle direction.
## **When Section Is Called**
The Rapid From Tool Change section is called after a tool change and before the 1st Rapid Z Down move. If there are no code blocks in this section, the Rapid Move section will be called instead.
## **Description**
**Section Line**

:T:<N><G!:ABSINC><G!:work\_coord><G!:00><X!><Y!> <attributes><EOL>



**Possible G Code Output**

N001 G90 G54 G00 X10. Y10.



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G!:ABSINC>|Absolute positioning|G90 or G91|
|<G!:work\_coord>|Work coordinate|G54-G59|
|<G:00>|Rapid move|G00|
|<X!>|X movement|X10.|
|<Y!>|Y movement|Y10.|
|<attributes>|Attribute|M00 or M01|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.  } Rapid From Tool Change

N5 G43 H01 Z.1 M08

N6 GO1 Z-1. F10.

N7 X15.

N8 Y20.

N9 G00 Z1. M09

N10 G91 G28 Z0

N11 T02 M06

N12 S2000 M03

N13 G90 G55 G00 X15. Y15.

N14 G43 H01 Z.1 M08

N15 GO1 Z-1. F10.
# <a name="chmtopic169"></a>**Rapid Leadin From Tool Change**


The Rapid Leadin From Tool Change section moves from the initial tool change position in the X,Y plane and sets the machine compensation. This is a good place to output code for absolute or incremental, work coordinate, spindle speed or spindle direction.

The difference between this section and the Rapid From Tool Change section is that this section will output the machine compensation on, left or right because no leadin type was selected in the operation.
## **When Section Is Called**
The Rapid Leadin From Tool Change section is called after a tool change and before the 1st Rapid Z Down move if the following conditions are met:

- A tool change immediately preceded the rapid move.
- There are code blocks in this section.

If there are no code blocks in this section, the Rapid Move section will be called instead.
## **Description**
**Section Line**

:T:<N><G!:ABSINC><G!:work\_coord><G:COMP><G!:00><COMP\_NUMBER><X!><Y!>\
<attributes><EOL>



**Possible G Code Output**

N001 G90 G54 G41 G00 D01 X10. Y10.



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G!:ABSINC>|Absolute positioning|G90 or G91|
|<G!:work\_coord>|Work coordinate|G54-G59|
|<G:COMP>|Machine compensation|G41|
|<G!:00>|Rapid move|G00|
|<COMP\_NUMBER>|Compensation number|D01|
|<X!>|X movement|X10.|
|<Y!>|Y movement|Y10.|
|<attributes>|Attribute|M00 or M01|
|<EOL>|End of line| |


## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G41 G00 D01 X10. Y10.  } Rapid Leadin From Tool Change

N5 G43 H01 Z.1 M08

N6 GO1 Z-1. F10.

N7 X15.

N8 G40 Y20.

N9 G00 Z1. M09

N10 G91 G28 Z0

N11 T02 M06

N12 S2000 M03

N13 G90 G55 G41 G00 D02 X15. Y15.

N14 G43 H01 Z.1 M08

N15 GO1 Z-1. F10.
# <a name="chmtopic171"></a>**5 Axis Rapid From Tool Change**


The 5 Axis Rapid To Tool Change section rapids in the X,Y plane to the next tool change position.
## **When Section Is Called**
The 5 Axis Rapid To Tool Change section is called when a tool change is encountered after a Rapid Z Up move if the following conditions are met:

- In the Header tab, a 4 or 5 Axis Milling option is selected for Multiaxis Milling.
- This is a 5 axis, 4 axis X or 4 axis Y type operation.
- There are code blocks in this section.

If there are no code blocks in this section, the Rapid To Tool Change section will be called instead.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:00><X!><Y!><A><B><M:05><attributes><EOL>



**Possible G Code Output**

N001 G90 G00 X10. Y10. A20. B30. M05



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute positioning|G90 or G91|
|<G:00>|Rapid movement|G00|
|<X!>|X movement|X10.|
|<Y!>|Y movement|Y10.|
|<A>|Tilt angle|A20.|
|<B>|Rotate angle|B30.|
|<M:05>|Spindle off|M05|
|<attributes>|Attribute|M00 or M01|
|<EOL>|End of line| |


## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 GO1 Z-1. F10.

N7 X15.

N8 Y20.

N9 G00 Z1. M09

N10 X40 Y40 A20. B30. M05  } Rapid to Tool Change

N10 G91 G28 Z0

N11 T02 M06

N12 S2000 M03

N13 G90 G55 G00 X15. Y15.

N14 G43 H01 Z.1 M08

N15 GO1 Z-1. F10.
# <a name="chmtopic173"></a>**Rapid Move**


The Rapid Move section rapids in the X,Y plane to the next position.
## **When Section Is Called**
The Rapid Move section is called after a Rapid Z Up move if the following condition is met:

- A rapid was inserted before the tool change.
## **Description**
**Section Lines**

:T:<N><S><M:SPINDLE\_DIR><EOL>

:T:<N><G:ABSINC><G:work\_coord><G:00><X><Y><attributes><EOL>



**Possible G Code Output**

N001 S1000 M03

N002 X10. Y10.



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<S>|Spindle speed|S1000|
|<G:SPINDLE\_DIR>|Spindle direction|M03|
|<EOL>|End of line| |
|<G:ABSINC>|Absolute positioning|G90 or G91|
|<G:work\_coord>|Work coordinate|G54-G59|
|<G:00>|Rapid Move|G00|
|<X>|X move|X10.|
|<Y>|Y move|Y10.|
|<attributes>|Attribute|M00 or M01|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 GO1 Z-1. F10.

N7 X15.

N8 Y20.

N9 G00 Z1.

N10 X15. Y15.   } Rapid Move

N11 Z.1

N12 GO1 Z-1. F10.

N13 X15.
# <a name="chmtopic175"></a>**5 Axis Rapid Move**


The 5 Axis Rapid Move section rapids in the X,Y plane to the next position.
## **When Section Is Called**
The 5 Axis Rapid Move section is called after a 5 Axis Rapid Z Up move if the following conditions are met:

- In the Header tab, a 4 or 5 Axis Milling option is selected for Multiaxis Milling.
- This is a 5 axis, 4 axis X or 4 axis Y type operation.
## **Description**
**Section Lines**

:T:<N><S><M:SPINDLE\_DIR><EOL>

:T:<N><G:ABSINC><G:work\_coord><G:00><X!><Y!><A><B><attributes><EOL>



**Possible G Code Output**

N001 S1000 M03

N002 G90 G54 G00 X10. Y10. A20. B30.



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<S>|Spindle speed|S1000|
|<G:SPINDLE\_DIR>|Spindle direction|M03|
|<EOL>|End of line| |
|<G:ABSINC>|Absolute positioning|G90 or G91|
|<G:work\_coord>|Work coordinate|G54-G59|
|<G:00>|Rapid Move|G00|
|<X!>|X move|X10.|
|<Y!>|Y move|Y10.|
|<A>|Tilt angle|A20.|
|<B>|Rotate angle|B30.|
|<attributes>|Attribute|M00 or M01|
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 GO1 Z-1. F10.

N7 X15.

N8 Y20.

N9 G00 Z1.

N10 X15. Y15.   } Rapid Move

N11 Z.1

N12 GO1 Z-1. F10.

N13 X15.
# <a name="chmtopic177"></a>**Rapid Leadin Move**


The Rapid Leadin section rapids in the X,Y plane to the next cut and turns the machine compensation on. This is a good place to output code for absolute or incremental, work coordinate, spindle speed or spindle direction.

The difference between this section and the Rapid From Tool Change section is that this section will output the machine compensation on, left or right because no leadin type was selected in the operation.
## **When Section Is Called**
The Rapid Leadin section is called before a Rapid Z Down move if the following conditions are met:

- A tool change *did not* immediately preceded the rapid move.
- There are code blocks in this section.

If there are no code blocks in this section, the Rapid Move section will be called instead.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:COMP><G:00><COMP\_NUMBER><X!><Y!><attributes><EOL>



**Possible G Code Output**

N001 G90 G41 G00 D01 X10. Y10



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute positioning|G90 or G91|
|<G:COMP>|Machine comp on, left, right|G41|
|<G:00>|Rapid move|G00|
|<COMP\_NUMBER>|Compensation number|D01|
|<X!>|X movement|X10.|
|<Y!>|Y movement|Y10.|
|<attributes>|Attribute|M00 or M01|
|<EOL>|End of line| |


## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G41 G00 D01 X10. Y10.

N5 G43 H01 Z.1 M08

N6 GO1 Z-1. F10.

N7 X15.

N8 G40 Y20.

N9 G00 Z1.

N10 G41 D02 X15. Y15.  } Rapid Leadin Move

N11 Z.1

N12 GO1 Z-1. F10.

N13 X15.
# <a name="chmtopic179"></a>**Rapid Leadout Move**


The Rapid Leadout section rapids in the X,Y plane to the next cut and turns the machine compensation off. It is a good practice to turn the machine compensation off between cuts or the controller could get confused when rapiding. You can then turn the compensation on again before the next cut if needed.
## **When Section Is Called**
The Rapid Leadout section is called after a Rapid Z Up move if the following conditions are met:

- There are code blocks in this section.

If there are no code blocks in this section, the Rapid Move section will be called instead and machine compensation will not be turned off.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:COMP><X!><Y!> <attributes><EOL>



**Possible G Code Output**

N001 G90 G40 X10. Y10.



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute positioning|G90 or G91|
|<G:COMP>|Machine compensation|G41|
|<X!>|X movement|X10.|
|<Y!>|Y movement|Y10.|
|<attributes>|Attribute|M00 or M01|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G41 G00 D01 X10. Y10.

N5 G43 H01 Z.1 M08

N6 GO1 Z-1. F10.

N7 X15.

N8 Y20.

N9 G00 Z1.

N10 G40 X15. Y20.   } Rapid Leadout Move

N10 G41 G00 D02 X15. Y15.

N11 Z.1

N12 GO1 Z-1. F10.

N13 X15.
# <a name="chmtopic181"></a>**Rapid To Tool Change**


The Rapid To Tool Change section rapids in the X,Y plane to the next tool change position.
## **When Section Is Called**
The Rapid To Tool Change section is called when a tool change is encountered after a Rapid Z Up move if the following conditions are met:

- A rapid was inserted before the tool change.
- There are code blocks in this section.

If there are no code blocks in this section, the Rapid Move section will be called instead.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:00><X!><Y!><M:05> <attributes><EOL>



**Possible G Code Output**

N001 G90 G00 X10. Y10. M05



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute positioning|G90 or G91|
|<G:00>|Rapid movement|G00|
|<X!>|X movement|X10.|
|<Y!>|Y movement|Y10.|
|<M:05>|Spindle off|M05|
|<attributes>|Attribute|M00 or M01|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 GO1 Z-1. F10.

N7 X15.

N8 Y20.

N9 G00 Z1. M09

N10 X40 Y40 M05  } Rapid to Tool Change

N10 G91 G28 Z0

N11 T02 M06

N12 S2000 M03

N13 G90 G55 G00 X15. Y15.

N14 G43 H01 Z.1 M08

N15 GO1 Z-1. F10.
# <a name="chmtopic183"></a>**Rapid Leadout to Tool Change**


The Rapid Leadout to Tool Change section rapids in the X,Y plane to the next tool change position and turns the machine compensation off. It is a good practice to turn the machine compensation off between cuts or the controller could get confused. You can then turn on the compensation again before the next cut if needed.
## **When Section Is Called**
The Rapid Leadout To Tool Change section is called when a tool change is encountered after a Rapid Z Up move if the following conditions are met:

- A rapid was inserted before the tool change.
- There are code blocks in this section.

If there are no code blocks in this section, the Rapid Move section will be called instead.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:40><X!><Y!>M:05><attributes><EOL>



**Possible G Code Output**

N001 G90 G40 X10. Y10. M05



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute positioning|G90 or G91|
|<G:COMP>|Machine compensation|G41|
|<X!>|X movement|X10.|
|<Y!>|Y movement|Y10.|
|<M:05>|Spindle off|M05|
|<attributes>|Attribute|M00 or M01|
|<EOL>|End of line| |


## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G41 G00 D01 X10. Y10.

N5 G43 H01 Z.1 M08

N6 GO1 Z-1. F10.

N7 X15.

N8 Y20.

N9 G00 Z1. M09

N10 G40 X40 Y40 M05 } Rapid Leadout to Tool Change

N10 G91 G28 Z0

N11 T02 M06

N12 S2000 M03

N13 G90 G55 G00 X15. Y15.

N14 G43 H01 Z.1 M08

N15 GO1 Z-1. F10.
# <a name="chmtopic111"></a>**Cut Moves Sections**
The Cut Moves sections on the Sections tab define the cutting moves including leadin and leadout moves and cut moves in X,Y and Z.

There are eight types of Cut Moves sections:

[Feed Z Down](#chmtopic185)

[5 Axis Feed Z Down](#chmtopic186)

[Line Leadin Move](#chmtopic187)

[Line Move](#chmtopic188)

[5 Axis Line Move](#chmtopic189)

[Line Leadout Move](#chmtopic190)

[Arc Move](#chmtopic191)

[Radius Move](#chmtopic192)

[Fast Line](#chmtopic193)
# <a name="chmtopic185"></a>**Feed Z Down**
The Feed Z Down section feeds the tool from the clearance plane to the cut depth. This is a good place to include the Z feedrate.
## **When Section Is Called**
The Feed Z Down section is called when the tool feeds from the clearance plane to the cut depth and occurs immediately before a leadin move or the first cut move.
## **Description**
**Section Line**

:T:<N><G:90><G:01><Z><F><M:COOLANT\_TYPE><EOL>

**Possible G Code Output**

N001 G90 G01 Z-1 F10 M08



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:90>|Absolute positioning|G90|
|<G:01>|Linear interpolation|G01|
|<Z>|Z move|Z-1.|
|<F>|Feedrate|F10.|
|<M:COOLANT\_TYPE>|Type of coolant|M07, M08 or M09|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 GO1 Z-1. F10.   } Feed Z Down

N7 X15. F20.

N8 Y20.

N9 G00 Z1.
# <a name="chmtopic186"></a>**5 Axis Feed Z Down**
The 5 Axis Z Feed Down section feeds the tool from the clearance plane to the cut depth. This is a good place to include the Z feedrate.
## **When Section Is Called**
The 5 Axis Z Feed Down section is called when the tool feeds from the clearance plane to the cut depth and the following conditions are met:

- In the Header tab, a 4 or 5 Axis Milling option is selected for Multiaxis Milling.
- This is a 5 axis, 4 axis X or 4 axis Y type operation.
## **Description**
**Section Line**

:T:<N><G:90><G:01><Z><F><M:COOLANT\_TYPE><EOL>

**Possible G Code Output**

N001 G90 G01 Z-1 F10 M08



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:90>|Absolute positioning|G90|
|<G:01>|Linear interpolation|G01|
|<Z>|Z move|Z-1.|
|<F>|Feedrate|F10.|
|<M:COOLANT\_TYPE>|Type of coolant|M07, M08 or M09|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 GO1 Z-1. F10.  } Feed Z Down

N7 X15. F20.

N8 Y20.

N9 G00 Z1.
# <a name="chmtopic187"></a>**Line Leadin Move**


The Line Leadin Move section makes a linear cutting movement and turns the machine compensation on.
## **When Section Is Called**
The Line Leadin Move section is called when a cutting movement is encountered and the following conditions are met:

- **ProCAM** In the CAM operation the Compensation parameter in the Set operation – Post Parameters dialog box is set to Machine Compensation (On, Right or Left) and a leadin type modifier was selected.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:COMP><COMP\_NUMBER><G:01><X!><Y!><F><Attributes><EOL>

**Possible G Code Output**

N001 G90 G41 D01 G01 X10. Y10. F10.



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:COMP>|Machine comp on, left, right|G41|
|<COMP\_NUMBER>|Compensation number|D01|
|<G:01>|Linear interpolation|G01|
|<X!>|X movement|X10.|
|<Y!>|Y movement|Y10.|
|<F>|Feedrate|F10.|
|<attributes>|Attribute|M00 or M01|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 GO1 Z-1. F10.

N7 G41 D01 X15. F20.  } Line leadin Move

N8 Y20.

N9 G00 Z1.
# <a name="chmtopic188"></a>**Line Move**
The Line Move section makes a linear cutting movement.
## **When Section Is Called**
The Line Move section is called when a linear cutting movement is encountered.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:01><X><Y><Z><F><attributes><EOL>

**Possible G Code Output**

N001 G90 G01 X10. Y10. Z-1 F10



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute/Incremental|G90|
|<G:01>|Linear interpolation|G01|
|<X>|X movement|X10.|
|<Y>|Y movement|Y10.|
|<Z>|Z movement|Z-1.|
|<F>|Feedrate|F10.|
|<attributes>|Attribute|M00 or M01|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 GO1 Z-1. F10.

N7 G41 D01 X15. F20.

N8 G01 X10. Y20. F10  } Line Move

N9 G00 Z1.
# <a name="chmtopic189"></a>**5 Axis Line Move**
The 5 Axis Line Move section makes a linear cutting movement for a multiaxis operation.
## **When Section Is Called**
The 5 Axis Line Move section is called when a linear cutting movement is encountered and the following conditions are met:

- In the Header tab, a 4 or 5 Axis Milling option is selected for Multiaxis Milling.
- This is a 5 axis, 4 axis X or 4 axis Y type operation.
- If you create an operation with the Z clearance the same as the Z depth, then you will get to this section after the 5 Axis Rapid Z Down.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:01><X><Y><Z><A><B><F><attributes><EOL>

**Possible G Code Output**

N001 G90 G01 X10. Y10. Z-1 A20. B30. F20



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute/Incremental|G90|
|<G:01>|Linear interpolation|G01|
|<X>|X movement|X10.|
|<Y>|Y movement|Y10.|
|<Z>|Z movement|Z-1.|
|<A>|Tilt angle|A20.|
|<B>|Rotate angle|B30.|
|<F>|Feedrate|F20.|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X5. Y5.

N5 G43 H01 Z.1 M08

N6 GO1 Z-1. F10.

N7 X10. Y10. A20. B30. F20. } Line Move

N8 G01 X10. Y20.   } Line Move

N9 G00 Z1.
# <a name="chmtopic190"></a>**Line Leadout Move**
The Line Leadout Move section makes a linear cutting movement and turns the machine compensation off.
## **When Section Is Called**
The Line Leadin Move section is called when a cutting movement is encountered and the following conditions are met:

- **ProCAM** In the CAM operation the Compensation parameter in the Set Operation – Post Parameters dialog box is set to Machine Compensation (On, Right or Left) in the CAM operation and a leadout type modifier was selected.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:40><G:01><X><Y><Z><F><EOL>

**Possible G Code Output**

N001 G90 G40 G01 X10. Y10. F10.



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute/Incremental|G90|
|<G:40>|Machine compensation off|G40|
|<G:01>|Linear interpolation|G01|
|<X>|X movement|X10.|
|<Y>|Y movement|Y10.|
|<Z>|Z movement|Z10.|
|<F>|Feedrate|F10.|
|<attributes>|Attribute|M00 or M01|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 GO1 Z-1. F10.

N7 G41 D01 X15. F20.

N8 Y20.

N9 G40 X20.   } Line Leadout Move

N9 G00 Z1.
# <a name="chmtopic191"></a>**Arc Move**
The Arc Move section makes an arc cutting movement using the Center - X,Y,I, J output format.
## **When Section Is Called**
The Arc Move section is called when an arc cutting movement is encountered and the Arc Centers type is set to Center - X,Y,I, J in the Header tab.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:ARC\_DIR><X><Y><Z><I><J><F><attributes><EOL>

**Possible G Code Output**

001 G90 G03 X15. Y15. I0. J5. F10.



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute/Incremental|G90 or G91|
|<G:ARC\_DIR>|Arc interpolation|G02 or G03|
|<X>|X arc endpoint|X10.|
|<Y>|Y arc endpoint|Y10.|
|<Z>|Z arc endpoint|Z10.|
|<I>|X arc center|I0.|
|<J>|Y arc center|J5.|
|<F>|Feedrate|F10.|
|<attributes>|Attribute|M00 or M01|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 GO1 Z-1. F10.

N7 X15. F20.

N8 Y20.

N9 G03 X15. Y15. I0. J5.  } Arc Move

N9 G00 Z1.
## **Comment**
For information on arc moves with a radius output format, see the Radius Move section on the next page.
# <a name="chmtopic192"></a>**Radius Move**
The Radius Move section makes an arc cutting movement using the Radius - X,Y, R output format.
## **When Section Is Called**
The Radius Move section is called when an arc cutting movement is encountered and the Arc Centers type is set to Radius - X,Y, R in the Header tab.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:ARC\_DIR><G><X><Y><Z><R><F><attributes><EOL>

**Possible G Code**

N001 G90 G03 X15. Y15. R5. F10



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute/Incremental|G90 or G91|
|<G:ARC\_DIR>|Arc interpolation|G02 or G03|
|<X>|X arc endpoint|X10.|
|<Y>|Y arc endpoint|Y10.|
|<Z>|Z arc endpoint|Z10.|
|<R>|Arc radius|R5.|
|<F>|Feedrate|F10.|
|<attributes>|Attribute|M00 or M01|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 GO1 Z-1. F10.

N7 X15. F20.

N8 Y20.

N9 G03 X15. Y15. R5.  } Radius Move

N9 G00 Z1.
## **Comment**
For more information on arc moves with an arc output format, see the Arc Move section on the previous page.
# <a name="chmtopic193"></a>**Fast Line**
The Fast Line section makes a linear cutting movement in 3D cutting only.
## **When Section Is Called**
The Fast Line section is called after the first leadin move when a linear cutting movement is encountered.
## **Description**
**Section Line**

:T:<N><G:01><FX><FY><FZ><EOL>

**Possible G Code Output**

N001 G90 G01 X10. Y10. Z-1 F10



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:01>|Linear interpolation|G01|
|<FX>|X movement|X10.|
|<FY>|Y movement|Y10.|
|<FZ>|Z movement|Z-1.|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 GO1 Z-1. F10.

N7 G41 D01 X15. F20.

N8 G01 X10. Y20.  } Fast Line

N9 G00 Z1.
# <a name="chmtopic112"></a>**Drilling Sections**


The Drilling sections define the drill, tap, bore and ream sections that output G code to define these cycles.

The drill cycle sections in this section will be called:

- if the holes are to be drilled one at a time. This would be the case if the holes were inserted using the Insert Point Tool Path command (2D Pro CAM) or Insert Drill command (3D ProCAM).
- if the holes were inserted using the Insert Pattern Tool Path command (2D ProCAM) and the controller did not support pattern drill cycle commands. The post processor would break up the pattern drill cycles into individual drill cycles and call the cycles in this section. If the controller did support pattern drill cycles, the cycles in the Pattern Drill Sections will be called instead.
# <a name="chmtopic205"></a>**Drill Position**


The Drill Position section outputs G code to position the machine over the first drill location. Any special code that is required before a drilling section call should be put in this section.
## **When Section Is Called**
The Drill Position section is called before the first hole is to be drilled in a new operation.

If there are no code blocks in this section, one of the rapid move sections will be called (Rapid From Tool Change, etc.).
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:work\_coordinate><G:00><X><Y><EOL>



**Possible G Code Output**

N4 G90 G54 G00 X10. Y10.



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute positioning|G90 or G91|
|<G:work\_coordinate>|Work coordinate|G54-G59|
|<G:00>|Rapid Move|G00|
|<X>|X movement|X10.|
|<Y>|Y movement|Y10.|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.  } Drill Position

N5 G43 H01 Z.1 M08

N6 G81 G99 R.1 Z-1. F10.

N7 G80 Z1. M09
# <a name="chmtopic207"></a>**Drill Cycle**
The Drill Cycle section outputs G code to support a standard drilling cycle.
## **When Section Is Called**
**ProCAM** The Drill Cycle section is called when the Cycle Type in the Set Operation – Drill dialog box is set to Drilling.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:81><G:PLANE><X><Y><Z\_CLEAR><Z\_DEPTH><F!>\
<M:COOLANT\_TYPE><EOL>



**Possible G Code Output**

N6 G90 G81 G99 X10. Y10. R.1 Z-1. F10. M08



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute positioning|G90 or G91|
|<G:81>|Drill cycle|G81|
|<G:PLANE>|Rapid/Clearance plane|G98 or G99|
|<X>|X movement|X10.|
|<Y>|Y movement|Y10.|
|<Z\_CLEAR>|Z Clearance|Z.1|
|<Z\_DEPTH>|Z Depth|Z-1.|
|<F!>|Feedrate|F10.|
|<M:COOLANT\_TYPE>|Type of coolant|M07, M08 or M09|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 G81 G99 R.1 Z-1. F10.  } G81 Drill Cycle

N7 G80 Z1. M09
# <a name="chmtopic209"></a>**Spot Drill Cycle**


The Spot Drill Cycle section outputs G code to support a spot drilling cycle.
## **ProCAM**
## **When Section Is Called**
**ProCAM** The Spot Drill Cycle section is called when the Cycle Type in the Set Operation - Drill dialog box is set to Spot Drilling.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:82><G:PLANE><X><Y><Z\_CLEAR><Z\_DEPTH>\
P<%:(dwell\*1000)><F!><M:COOLANT\_TYPE><EOL>

**Possible G Code Output**

N6 G90 G82 G99 X10. Y10. R.1 Z-1. P1000 F10. M08



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute positioning|G90 or G91|
|<G:82>|Spot drill cycle|G82|
|<G:PLANE>|Rapid/Clearance plane|G98 or G99|
|<X>|X movement|X10.|
|<Y>|Y movement|Y10.|
|<Z\_CLEAR>|Z Clearance|Z.1|
|<Z\_DEPTH>|Z Depth|Z-1.|
|P<%:(dwell\*1000)>|Dwell|P1000|
|<F!>|Feedrate|F10.|
|<M:COOLANT\_TYPE>|Type of coolant|M07, M08 or M09|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 G82 G99 R.1 Z-1. P1000 F10. } G82 Spot Drill Cycle

N7 G80 Z1. M09
# <a name="chmtopic211"></a>**Peck Drill Cycle**


The Peck Drill Cycle section outputs G code to support a peck drilling cycle.
## **When Section Is Called**
**ProCAM** The Peck Drill Cycle section is called when the Cycle Type in the Set Operation – Drill dialog box is set to Pecking.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:83><G:PLANE><X><Y><Z\_CLEAR><Z\_DEPTH><SUB\_PECK>\
<F!><M:COOLANT\_TYPE><EOL>

**Possible G Code Output**

N6 G90 G83 G99 X10. Y10. R.1 Z-1. Q.25 F10. M08



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute positioning|G90 or G91|
|<G:83>|Peck drill cycle|G83|
|<G:PLANE>|Rapid/Clearance plane|G98 or G99|
|<X>|X movement|X10.|
|<Y>|Y movement|Y10.|
|<Z\_CLEAR>|Z Clearance|Z.1|
|<Z\_DEPTH>|Z Depth|Z-1.|
|<SUB\_PECK>|Peck Depth|Q.25|
|<F!>|Feedrate|F10.|
|<M:COOLANT\_TYPE>|Type of coolant|M07, M08 or M09|
|<EOL>|End of line| |



If this section is left blank, the post processor will automatically output long G code using "G00", "G01" moves to simulate the Peck Drilling Cycle.

|**"G83" Peck<br>Cycle**|<p>O0001</p><p>N1 G20 G40 G80 G90</p><p>N2 T01 M06</p><p>N3 S1000 M03</p><p>N4 G90 G54 G00 X10. Y10.</p><p>N5 G43 H01 Z.1 M08</p><p>N6 G83 G99 R.1 Z-1. Q.25 F10. } G83 Cycle</p><p>N7 G80 Z1. M09</p>|
| :- | :- |
| | |
|**Simulated Peck Cycle**|<p>O0001</p><p>N1 G20 G40 G80 G90</p><p>N2 T01 M06</p><p>N3 S1000 M03</p><p>N4 G90 G54 G00 X10. Y10.</p><p>N5 G43 H01 Z.1 M08</p><p>N6 G01 Z-.25 F10.   } Long Code</p><p>N8 G00 Z.1</p><p>N9 Z-.2</p><p>N10 G01 Z-.5</p><p>N11 G00 Z.1</p><p>N12 Z-.45</p><p>N13 G01 Z-.75</p>|

# <a name="chmtopic213"></a>**Variable Peck Cycle**


The Variable Peck Cycle section outputs G code to support a peck drilling cycle.
## **When Section Is Called**
The Variable Peck Cycle section is called when the Cycle Type in the Set Operation – Drill dialog box is set to Variable Pecking.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:83><G:PLANE><X><Y><Z\_CLEAR><Z\_DEPTH>\
<SUB\_PECK><F!><M:COOLANT\_TYPE><EOL>

**Possible G Code Output**

N6 G90 G83 G99 X10. Y10. R.1 Z-1. Q.25 F10. M08



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute positioning|G90 or G91|
|<G:83>|Variable peck drill cycle|G83|
|<G:PLANE>|Rapid/Clearance plane|G98 or G99|
|<X>|X movement|X10.|
|<Y>|Y movement|Y10.|
|<Z\_CLEAR>|Z Clearance|Z.1|
|<Z\_DEPTH>|Z Depth|Z-1.|
|<SUB\_PECK>|Peck Depth|Q.25|
|<F!>|Feedrate|F10.|
|<M:COOLANT\_TYPE>|Type of coolant|M07, M08 or M09|
|<EOL>|End of line| |



If this section is left blank, the post processor will automatically output long G code using "G00", "G01" moves to simulate the Variable Peck Drilling cycle.

|**"G83" Peck Cycle**|<p>O0001 </p><p>N1 G20 G40 G80 G90 </p><p>N2 T01 M06 </p><p>N3 S1000 M03 </p><p>N4 G90 G54 G00 X10. Y10. </p><p>N5 G43 H01 Z.1 M08 </p><p>N6 G83 G99 R.1 Z-1. Q.25 F10 } G83 cycle</p><p>N7 G80 Z1. M09</p>|
| :- | :- |
| | |
|<p>**Simulated Variable**</p><p>**Peck Cycle**</p>|<p>O0001</p><p>N1 G20 G40 G80 G90</p><p>N2 T01 M06</p><p>N3 S1000 M03</p><p>N4 G90 G54 G00 X10. Y10.</p><p>N5 G43 H01 Z.1 M08</p><p>N6 G01 Z-.25 F10.   } Long code</p><p>N8 G00 Z.1</p><p>N9 Z-.2</p><p>N10 G01 Z-.45</p><p>N11 G00 Z.1</p><p>N12 Z-.4</p><p>N13 G01 Z-.6</p><p>N10 G01 Z-.5</p><p>N11 G00 Z.1</p><p>N12 Z-.45</p><p>N13 G01 Z-.75</p>|

# <a name="chmtopic215"></a>**High Speed Peck Cycle**


The High Speed Peck Cycle section outputs G code to support a high speed peck drilling cycle.
## **When Section Is Called**
The High Speed Peck Cycle section is called when the Cycle Type in the Set Operation – Drill dialog box is set for High Speed Pecking.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:73><G:PLANE><X><Y><Z\_CLEAR><Z\_DEPTH><SUB\_PECK>\
<F!><M:COOLANT\_TYPE><EOL>

**Possible G Code Output**

N6 G90 G73 G99 10. Y10. R.1 Z-1. Q.25 F10



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute positioning|G90 or G91|
|<G:73>|High speed peck drill cycle|G73|
|<G:PLANE>|Rapid/Clearance plane|G98 or G99|
|<X>|X movement|X10.|
|<Y>|Y movement|Y10.|
|<Z\_CLEAR>|Z Clearance|Z.1|
|<Z\_DEPTH>|Z Depth|Z-1.|
|<SUB\_PECK>|Peck Depth|Q.25|
|<F!>|Feedrate|F10.|
|<M:COOLANT\_TYPE>|Type of coolant|M07, M08 or M09|
|<EOL>|End of line| |



If this section is left blank, the post processor will automatically output long G code using "G00", "G01" moves to simulate the High Speed Peck Drilling cycle.

|<p>**"G73" High Speed**</p><p>**Peck Cycle**</p>|<p>O0001</p><p>N1 G20 G40 G80 G90</p><p>N2 T01 M06</p><p>N3 S1000 M03</p><p>N4 G90 G54 G00 X10. Y10.</p><p>N5 G43 H01 Z.1 M08</p><p>N6 G73 G99 R.1 Z-1. Q.25 F10 } G73 Cycle</p><p>N7 G80 Z1. M09</p>|
| :- | :- |
| | |
|**Simulated High Speed Peck Cycle**|<p>O0001</p><p>N1 G20 G40 G80 G90</p><p>N2 T01 M06</p><p>N3 S1000 M03</p><p>N4 G90 G54 G00 X10. Y10.</p><p>N5 G43 H01 Z.1 M08</p><p>N6 G01 Z-.25 F10. } Long code</p><p>N8 G00 Z-.24</p><p>N9 G01 Z-.5</p><p>N10 G00 Z-.49</p><p>N11 G01 Z-.75</p>|

# <a name="chmtopic217"></a>**Tapping Cycle**


The Tapping Cycle section outputs G code to support a tapping cycle.
## **When Section Is Called**
**ProCAM** The Tapping Cycle section is called when the Cycle Type in the Set Operation – Drill dialog box is set to Tapping.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:84><G:PLANE><X><Y><Z\_CLEAR><Z\_DEPTH>\
<F!><M:COOLANT\_TYPE><EOL>

**Possible G Code Output**

N6 G90 G84 G99 X10. Y10. R.1 Z-1. F10. M08



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute positioning|G90 or G91|
|<G:84>|Tapping cycle|G84|
|<G:PLANE>|Rapid/Clearance plane|G98 or G99|
|<X>|X movement|X10.|
|<Y>|Y movement|Y10.|
|<Z\_CLEAR>|Z Clearance|Z.1|
|<Z\_DEPTH>|Z Depth|Z-1.|
|<F!>|Feedrate|F10.|
|<M:COOLANT\_TYPE>|Type of coolant|M07, M08 or M09|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 G84 G99 R.1 Z-1. F10. } G84 Tapping Cycle

N7 G80 Z1. M09
# <a name="chmtopic219"></a>**Rigid Tapping Cycle**


The Rigid Tapping Cycle section outputs G code to support a rigid tapping cycle.
## **When Section Is Called**
**ProCAM** The Rigid Tapping Cycle section is called when Rigid Tapping is selected for the Cycle Type in the Set Operation – Drill dialog box.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:84><POINT\_ONE><G:PLANE><X><Y><Z\_CLEAR>

<Z\_DEPTH><F!><M:COOLANT\_TYPE><EOL>

**Possible G Code Output**

N6 G90 G99 G84.1 X10. Y10. R.1 Z-1. F10. M08



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute positioning|G90 or G91|
|<G:84>|Rigid tapping cycle|G84|
|<POINT\_ONE>|Hard coded .1|.1|
|<G:PLANE>|Rapid/Clearance plane|G98 or G99|
|<X>|X movement|X10.|
|<Y>|Y movement|Y10.|
|<Z\_CLEAR>|Z Clearance|Z.1|
|<Z\_DEPTH>|Z Depth|Z-1.|
|<F!>|Feedrate|F10.|
|<M:COOLANT\_TYPE>|Type of coolant|M07, M08 or M09|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 M29 S1000

N6 G99 G84.1 R.1 Z-1. F10. } G84.1 Rigid Tap Cycle

N8 G80 Z1. M09
# <a name="chmtopic221"></a>**Reverse Tapping Cycle**


The Reverse Tapping Cycle section outputs G code to support a reverse tapping cycle.
## **When Section Is Called**
**ProCAM** The Reverse Tapping Cycle section is called when Reverse Tapping is selected for the Cycle Type in the Set Operation – Drill dialog box.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:74><G:PLANE><X><Y><Z\_CLEAR><Z\_DEPTH><F!>

<M:COOLANT\_TYPE><EOL>

**Possible G Code Output**

N6 G90 G99 G74 X10. Y10. R.1 Z-1. F10. M08



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute positioning|G90 or G91|
|<G:74>|Reverse tapping cycle|G74|
|<G:PLANE>|Rapid/Clearance plane|G98 or G99|
|<X>|X movement|X10.|
|<Y>|Y movement|Y10.|
|<Z\_CLEAR>|Z Clearance|Z.1|
|<Z\_DEPTH>|Z Depth|Z-1.|
|<F!>|Feedrate|F10.|
|<M:COOLANT\_TYPE>|Type of coolant|M07, M08 or M09|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M04

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 G99 G74 R.1 Z-1. F10. } G74 Reverse Tap Cycle

N7 G80 Z1. M09
# <a name="chmtopic223"></a>**Reverse Rigid Tapping Cycle**


The Reverse Rigid Tapping Cycle section outputs G code to support a reverse rigid tapping cycle.
## **When Section Is Called**
**ProCAM** The Reverse Rigid Tapping Cycle section is called when Reverse Rigid Tapping is selected for the Cycle Type in the Set Operation – Drill dialog box.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:74><POINT\_ONE><G:PLANE><X><Y><Z\_CLEAR>

<Z\_DEPTH><F!><M:COOLANT\_TYPE><EOL>

**Possible G Code Output**

N6 G90 G99 G74.1 X10. Y10. R.1 Z-1. F10. M08



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute positioning|G90 or G91|
|<G:74>|Reverse Rigid tapping cycle|G74|
|<POINT\_ONE>|Hard coded .1|.1|
|<G:PLANE>|Rapid/Clearance plane|G98 or G99|
|<X>|X movement|X10.|
|<Y>|Y movement|Y10.|
|<Z\_CLEAR>|Z Clearance|Z.1|
|<Z\_DEPTH>|Z Depth|Z-1.|
|<F!>|Feedrate|F10.|
|<M:COOLANT\_TYPE>|Type of coolant|M07, M08 or M09|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M04

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 M29 S1000

N6 G99 G74.1 R.1 Z-1. F10. }G74.1 Reverse Rigid Tapping Cycle

N8 G80 Z1. M09
# <a name="chmtopic225"></a>**Ream Cycle**


The Ream Cycle section outputs G code to support a ream cycle.
## **When Section Is Called**
**ProCAM** The Ream Cycle section is called when Reaming is selected for the Cycle Type in the Set Operation – Drill dialog box.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:85><G:PLANE><X><Y><Z\_CLEAR><Z\_DEPTH><F!>

<M:COOLANT\_TYPE><EOL>

**Possible G Code Output**

N6 G90 G85 G99 X10. Y10. R.1 Z-1. F10. M08



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute positioning|G90 or G91|
|<G:85>|Ream tapping cycle|G85|
|<G:PLANE>|Rapid/Clearance plane|G98 or G99|
|<X>|X movement|X10.|
|<Y>|Y movement|Y10.|
|<Z\_CLEAR>|Z Clearance|Z.1|
|<Z\_DEPTH>|Z Depth|Z-1.|
|<F!>|Feedrate|F10.|
|<M:COOLANT\_TYPE>|Type of coolant|M07, M08 or M09|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 G85 G99 R.1 Z-1. F10.   } G85 Ream Cycle

N7 G80 Z1. M09
# <a name="chmtopic227"></a>**Ream w/Dwell Cycle**


The Ream w/Dwell Cycle section outputs G code to support a ream with dwell cycle.
## **When Section Is Called**
**ProCAM** The Ream w/Dwell Cycle section is called when Ream with Dwell is selected for the Cycle Type in the Set Operation – Drill dialog box.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:89><G:PLANE><X><Y><Z\_CLEAR><Z\_DEPTH>

P<%:(dwell\*1000)>F!><M:COOLANT\_TYPE><EOL>

**Possible G Code Output**

N6 G90 G89 G99 X10. Y10. R.1 Z-1. P1000 F10. M08



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute positioning|G90 or G91|
|<G:89>|Ream with Dwell cycle|G89|
|<G:PLANE>|Rapid/Clearance plane|G98 or G99|
|<X>|X movement|X10.|
|<Y>|Y movement|Y10.|
|<Z\_CLEAR>|Z Clearance|Z.1|
|<Z\_DEPTH>|Z Depth|Z-1.|
|P<%:(dwell\*1000)>|Dwell time|P1000|
|<F!>|Feedrate|F10.|
|<M:COOLANT\_TYPE>|Type of coolant|M07, M08 or M09|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 G89 G99 R.1 Z-1. P1000 F10. } G89 Ream w/Dwell Cycle

N7 G80 Z1. M09
# <a name="chmtopic229"></a>**Boring Cycle**
The Boring Cycle section outputs G code to support a bore cycle.
## **When Section Is Called**
**ProCAM** The Boring Cycle section is called when Boring is selected for the Cycle Type in the Set Operation – Drill dialog box.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:86><G:PLANE><X><Y><Z\_CLEAR><Z\_DEPTH>

<F!><M:COOLANT\_TYPE><EOL>



**Possible G Code Output**

N6 G90 G86 G99 X10. Y10. R.1 Z-1. F10. M08



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute positioning|G90 or G91|
|<G:86>|Bore cycle|G86|
|<G:PLANE>|Rapid/Clearance plane|G98 or G99|
|<X>|X movement|X10.|
|<Y>|Y movement|Y10.|
|<Z\_CLEAR>|Z Clearance|Z.1|
|<Z\_DEPTH>|Z Depth|Z-1.|
|<F!>|Feedrate|F10.|
|<M:COOLANT\_TYPE>|Type of coolant|M07, M08 or M09|
|<EOL>|End of line| |
## **Example**
N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 G86 G99 R.1 Z-1. F10.   } G86 Bore Cycle

N7 G80 Z1. M09
# <a name="chmtopic231"></a>**Bore w/Dwell Cycle**
The Bore w/Dwell Cycle section outputs G code to support a bore with dwell cycle.
## **When Section Is Called**
**ProCAM** The Bore w/Dwell Cycle section is called when the Cycle Type in the Set Operation – Drill dialog box is set to Bore with Dwell.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:88><G:PLANE><X><Y><Z\_CLEAR><Z\_DEPTH>

P<%:(dwell\*1000)><F!><M:COOLANT\_TYPE> <EOL>



**Possible G Code Output**

N6 G90 G88 G99 X10. Y10. R.1 Z-1. P1000 F10. M08



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute positioning|G90 or G91|
|<G:89>|Bore with Dwell cycle|G88|
|<G:PLANE>|Rapid/Clearance plane|G98 or G99|
|<X>|X movement|X10.|
|<Y>|Y movement|Y10.|
|<Z\_CLEAR>|Z Clearance|Z.1|
|<Z\_DEPTH>|Z Depth|Z-1.|
|P<%:(dwell\*1000)>|Dwell|P1000|
|<F!>|Feedrate|F10.|
|<M:COOLANT\_TYPE>|Type of coolant|M07, M08 or M09|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 G88 G99 R.1 Z-1. P1000 F10. } G88 Bore w/Dwell Cycle

N7 G80 Z1. M09
# <a name="chmtopic233"></a>**Back Boring Cycle**
The Back Boring Cycle section outputs G code to support a back boring cycle.
## **When Section Is Called**
**ProCAM** The Back Boring Cycle section is called when Back Boring is selected for the Cycle Type in the Set Operation – Drill dialog box.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:87><G:PLANE><X><Y><Z\_CLEAR><Z\_DEPTH>

Q<#:SHIFT\_AMOUNT><F!><M:COOLANT\_TYPE> <EOL>



**Possible G Code Output**

N6 G90 G87 G99 R.1 Z-1. Q.01 F10.



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute positioning|G90 or G91|
|<G:87>|Back Boring cycle|G87|
|<G:PLANE>|Rapid/Clearance plane|G98 or G99|
|<X>|X movement|X10.|
|<Y>|Y movement|Y10.|
|<Z\_CLEAR>|Z Clearance|Z.1|
|<Z\_DEPTH>|Z Depth|Z-1.|
|Q<#:SHIFT\_AMOUNT>|Shift amount|Q.01|
|<F!>|Feedrate|F10.|
|<M:COOLANT\_TYPE>|Type of coolant|M07, M08 or M09|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 G87 G99 R.1 Z-1. Q.01 F10. } G87 Back Boring Cycle

N7 G80 Z1. M09
# <a name="chmtopic235"></a>**Fine Boring Cycle**


The Fine Boring Cycle section outputs G code to support a fine boring cycle.
## **When Section Is Called**
**ProCAM** The Fine Boring Cycle section is called when Fine Boring is selected for the Cycle Type in the Set Operation – Drill dialog box.
## **Description**
**Section Line**

:T:<N><G:ABSINC><G:76><G:PLANE><X><Y><Z\_CLEAR><Z\_DEPTH>

Q<#:SHIFT\_AMOUNT> <F!><M:COOLANT\_TYPE> <EOL>

**Possible G Code Output**

N6 G90 G76 G99 X10. Y10. R.1 Z-1. Q.01 F10. M08



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute positioning|G90 or G91|
|<G:76>|Fine Back Boring cycle|G76|
|<G:PLANE>|Rapid/Clearance plane|G98 or G99|
|<X>|X movement|X10.|
|<Y>|Y movement|Y10.|
|<Z\_CLEAR>|Z Clearance|Z.1|
|<Z\_DEPTH>|Z Depth|Z-1.|
|Q<#:SHIFT\_AMOUNT>|Shift amount|Q.01|
|<F!>|Feedrate|F10.|
|<M:COOLANT\_TYPE>|Type of coolant|M07, M08 or M09|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 G76 G99 R.1 Z-1. Q.01 F10. }G76 Fine Boring Cycle

N7 G80 Z1. M09
# <a name="chmtopic237"></a>**Drill Pattern at Angle**


The Drill Pattern at Angle section outputs G code to support a linear drill pattern at an angle. Any canned drilling cycle can be chosen to be drilled at an angle.
## **When Section Is Called**
The Drill Pattern at Angle section is called when Drilling is selected for the Cycle Type in the Set Operation – Drill dialog box and the drill cycle is at an angle. If this section is left blank, the post will explode the drill locations into individual drills.
## **Description**
**Section Line**

:T:<N><G:91><X><Y>L<%((NUM\_HITS-1)-SKIP\_1ST\_HIT)><EOL>

**Possible G Code Output**

N6 G91 X10. Y10.L04



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:91>| | |
|<X>|X start|X10.|
|<Y>|Y start|Y10.|
|L<%((NUM\_HITS-1)-SKIP\_1ST\_HIT>|Number of holes|L04|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 G99 G81 R.1 Z-1. F10.  } G81 Drilling Cycle

N7 G91 X1. Y1. L04   } Linear Pattern

N8 G80 G90 Z1. M09
## **Comment**
Notice that in the example the drill cycle is called out first and then "modified" by the next line. The Drill Pattern at Angle cycle can modify any canned cycle.
# <a name="chmtopic239"></a>**Continue Drilling**
The Continue Drilling section is called to output additional holes by specifying only the new drill coordinates as all other cycle information is the same.
## **When Section Is Called**
The Continue Drilling section is called when the drill cycle type and all cycle information are unchanged and additional coordinates are to be drilled. Some controllers allow outputting just the new coordinates to be drilled.
## **Description**
**Section Line**

:T:<N><G:ABSINC><X><Y><attributes><EOL>



**Possible G Code Output**

N7 G90 X11. Y11



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:ABSINC>|Absolute positioning|G90 or G91|
|<X>|X movement|X11.|
|<Y>|Y movement|Y11.|
|<attributes>|Attribute|M00 or M01|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 G99 G81 R.1 Z-1. F10.  } "G81" Drilling Cycle

N7 X11. Y11.    } Continue Drilling

N8 X12. Y12   } Continue Drilling

N9 G80 Z1. M09
# <a name="chmtopic241"></a>**End Drill Cycle**


The End Drill Cycle section cancels the canned drill cycle and rapids in the Z to the rapid plane, but does not turn off the coolant. The idea of this cycle is that there are more canned cycles to follow, so the coolant should not be turned off. The Cancel Drill Cycle section performs the same function except it turns off the coolant.
## **When Section Is Called**
The End Drill Cycle section is called at the completion of two or more canned drilling cycle operations in a row with the same tool. More canned drill cycles immediately follow.
## **Description**
**Section Line**

:T:<N><G:90><G:80><Z!:OPR\_Z\_RAPID\_PLANE><EOL>

**Possible G Code Output**

N6 G90 G80 Z1.



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:90>|Absolute positioning|G90|
|<EOL>|End of line| |
|<G:80>|Cancel canned cycle|G80|
|<Z!:OPR\_Z\_RAPID\_PLANE>|Z rapid plane|Z1.0|
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 G99 G81 R.1 Z-1. F10.

N7 X11. Y11.

N8 G80 Z1.    } End Drill Cycle

N9 X12. Y12.

N9 G99 G81 R.1 Z-2. F10.

N10 X13. Y13.

N9 G80 Z1. M09
# <a name="chmtopic243"></a>**Cancel Drill Cycle**
The Cancel Drill Cycle section cancels the canned drill cycle and rapids in the Z to the rapid plane. The idea of this cycle is this is the last canned cycle so the coolant can be turned off. The End Drill Cycle section performs the same function except it leaves the coolant on.
## **When Section Is Called**
The Cancel Drill Cycle section is called at the completion of two or more canned drilling cycle operations in a row with the same tool. A tool change or end of program will follow this section.
## **Description**
**Section Line**

:T:<N><G:90><G:80><Z!:OPR\_Z\_RAPID\_PLANE><M:09><EOL>



**Possible G Code Output**

N8 G90 G80 Z1. M09



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:90>|Absolute positioning|G90|
|<EOL>|End of line| |
|<G:80>|Cancel canned cycle|G80|
|<Z!:OPR\_Z\_RAPID\_PLANE>|Z rapid plane|Z1.0|
|<M:09>|Coolant off|M09|
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X10. Y10.

N5 G43 H01 Z.1 M08

N6 G99 G81 R.1 Z-1. F10.

N7 X11. Y11.

N8 G80 Z1. M09    } End Drill Cycle

N9 X12. Y12.

N9 G99 G81 R.1 Z-2. F10.

N10 X13. Y13.

N9 G80 Z1. M09
# <a name="chmtopic113"></a>**Drill Pattern Sections**
The Drill Pattern sections define the drill, tap, bore and ream sections that output G code for multiple hole pattern cycles.

- If the controller supports patterns, Drill Patterns sections are the same as Drill sections except the drilling is done on patterns of holes rather than individual holes.
- If the controller does not support patterns, then the UPG breaks the patterns into individual drill holes and calls a similar single hole section instead.

For example, if you inserted a linear pattern of peck drilled holes, the UPG would first check to see if there was code in the Pattern Peck Drill section. If there is code, then this section would be called to output the linear pattern of drilled holes. If there were no code blocks in the Pattern Peck Drill section, the UPG would break up the holes into individual holes and call the Peck Drill section to output the G code. Generally speaking, the G code output for pattern drill holes is similar to drill holes except that a pattern is output rather than individual drill holes.
# <a name="chmtopic246"></a>**Arc Pattern**
The Arc Pattern section drills holes using an arc pattern command that is supported by the controller when an arc pattern entity is encountered.

![image\pin_bl.gif] Fanuc and Fanuc compatible controllers do not support this canned cycle, so an example for another controller is used. Additional calculations are required to support this canned cycle on a Fanuc or Fanuc compatible controller. For more information, contact your CAMWorks Reseller.
## **When This Section is Called**
The Arc Pattern section is executed when an arc pattern is encountered and there is code in this section. Code in this section indicates that the controller supports an arc pattern command.

If the controller does not support arc patterns, then the UPG breaks the arc pattern into individual drill holes and calls a similar single hole section instead.
## **Description**


|**Section Lines**|**Possible G Code Output**|
| :- | :- |
|:T:<N><G:36><X!:ABS\_I\_CENTER><Y!:ABS\_J\_CENTER>|N7 G36 X1. Y1.|
|:T:I<#:ARC\_RADIUS>|I2.|
|:T:J<"#3.3N":ARC\_START\_ANGLE>|J0|
|<p>:T:P<"#-3.3N":((ARC\_INC\_ANGLE/(NUM\_HITS-1))</p><p>\*((MOVE\_TYPE+MOVE\_TYPE)-5))></p>|P15|
|:T:K<"%-2T":NUM\_HITS><attributes><EOL>|K5|



![image\pin_bl.gif] Notice how the multiple :T:'s are used to break up a long section block. Since there is only one <EOL>, the G code would be output as one line.



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:36>|Arc pattern|G36|
|<X!:ABS\_I\_CENTER >|X arc center|X1.|
|<Y!:ABS\_J\_CENTER >|Y arc center|Y1.|
|I<#:ARC\_RADIUS>|Arc radius|I2.|
|J<"#3.3N":ARC\_START\_ANGLE>|Arc start angle|J0|
|<p>P<"#-3.3N":((ARC\_INC\_ANGLE/ NUM\_HITS -1))</p><p>\*((MOVE\_TYPE +MOVE\_TYPE)-5))></p>|Incremental angle|P15|
|K<"%-2T":NUM\_HITS>|Number of drill holes|K5|
|<attributes>|Attribute|M00 or M01|
|<EOL>|End of line| |
| | | |


## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X5. Y5.

N5 G43 H01 Z.1 M08

N6 G99 G81 R.1 Z-1. F10. } Arc pattern definition

N7 G36 X1. Y1. I2. J0 P15 K5 } Arc pattern call

N8 G80 Z1. M09

N9 G91 G28 Z0

N10 M30
# <a name="chmtopic248"></a>**Bolt Hole Pattern**
The Bolt Hole Pattern section drills holes using a Bolt Hole Pattern command that is supported by the controller when a Bolt Hole Pattern entity is encountered.

![image\pin_bl.gif] Fanuc and Fanuc compatible controllers do not support this canned cycle, so an example for another controller is used. Additional calculations are required to support this canned cycle on a Fanuc or Fanuc compatible controller. For more information, contact your CAMWorks Reseller.
## **When This Section is Called**
The Bolt Hole Pattern section is executed when a Bolt Hole Pattern is encountered and there is code in this section. Code in this section indicates that the controller supports a Bolt Hole Pattern command.

If the controller does not support Bolt Hole Patterns, then the UPG breaks the Bolt Hole Pattern into individual drill holes and calls a similar single hole section instead.
## **Description**


|**Section Lines**|**Possible G Code Output**|
| :- | :- |
|:T:<N><G:34><X!:ABS\_I\_CENTER><br><Y!:ABS\_J\_CENTER>|N7 G34 X1. Y1.|
|:T:I<#:ARC\_RADIUS>|I2.|
|:T:J<"#3.3N":ARC\_START\_ANGLE>|J0|
|:T:K<"%-2T":(NUM\_HITS\*((MOVE\_TYPE+MOVE\_TYPE)-5))>|K5|
|:T:<attributes><EOL>|M00|



![image\pin_bl.gif] Notice that multiple :T:'s are used to break up a long section block. Since there is only one <EOL>, the G code would be output as one line.



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:34>|Bolt hole pattern|G34|
|<X!:ABS\_I\_CENTER >|X arc center|X1.|
|<Y!:ABS\_J\_CENTER >|Y arc center|Y1.|
|I<#:ARC\_RADIUS>|Arc radius|I2.|
|J<"#3.3N":ARC\_START\_ANGLE>|Arc start angle|J0|
|K<"%-2T":NUM\_HITS>|Number of drill holes|K5|
|<attributes>|Attribute|M00 or M01|
|<EOL>|End of line| |
| | | |


## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X5. Y5.

N5 G43 H01 Z.1 M08

N6 G99 G81 R.1 Z-1. F10.  } Bolt hole pattern definition

N7 G34 X1. Y1. I2. J0 K5  } Bolt hole pattern call

N8 G80 Z1. M09

N9 G91 G28 Z0

N10 M30
# <a name="chmtopic250"></a>**Grid X Pattern**
The Grid X Pattern section drills holes starting in the X direction first using a Grid X Pattern command that is supported by the controller when an Grid X Pattern entity is encountered.

![image\pin_bl.gif] Fanuc and Fanuc compatible controllers do not support this canned cycle, so an example for another controller is used. Additional calculations are required to support this canned cycle on a Fanuc or Fanuc compatible controller. For more information, contact your CAMWorks Reseller.
## **When This Section is Called**
The Grid X Pattern section is executed when a Grid X Pattern is encountered and there is code in this section. Code in this section indicates that the controller supports a Grid X Pattern command.

If the controller does not support Grid X Patterns, then the UPG breaks the Grid Pattern into individual drill holes and calls a similar single hole section instead.
## **Description**


|**Section Lines**|**Possible G Code Output**|
| :- | :- |
|<p>:T:<N><G:37><G37.1><X!:ABS\_X\_START></p><p><Y!:ABS\_Y\_START></p>|N7 G37.1 X1. Y1.|
|:T:I<#:DIST\_BET\_HOLES\_X>|I1.|
|:T:P<"%-2T":(NUM\_HITS\_X-1)>|P4|
|:T:J<#:DIST\_BET\_HOLES\_Y>|J1.|
|:T:K<"%-2T":(NUM\_HITS\_Y-1)><EOL>|K4|



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:37>|Grid pattern|G37|
|<G:37.1>|Hard coded .1|.1|
|<X!:ABS\_X\_START >|X pattern start|X1.|
|<Y!:ABS\_Y\_START >|Y pattern start|Y1.|
|I<#:DIST\_BET\_HOLES\_X>|X distance between holes|I1.|
|P<"%-2T":(NUM\_HITS\_X-1)>|X number of holes|P4|
|J<#:DIST\_BET\_HOLES\_Y>|Y distance between holes|J1.|
|K<"%-2T":(NUM\_HITS\_Y-1)>|Y number of holes|K4|
|<EOL>|End of line| |


## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X5. Y5.

N5 G43 H01 Z.1 M08

N6 G99 G81 R.1 Z-1. F10. } Grid X pattern definition

N7 G37.1 X1. Y1. I1. P4 J1 K4 } Grid X pattern call

N8 G80 Z1. M09

N9 G91 G28 Z0

N10 M30
# <a name="chmtopic252"></a>**Grid Y Pattern**
The Grid Y Pattern section drills holes starting in the Y direction first using a Grid Y Pattern command that is supported by the controller when an Grid Y Pattern entity is encountered.

![image\pin_bl.gif] Fanuc and Fanuc compatible controllers do not support this canned cycle, so an example for another controller is used. Additional calculations are required to support this canned cycle on a Fanuc or Fanuc compatible controller. For more information, contact your CAMWorks Reseller.
## **When This Section is Called**
The Grid Y Pattern section is executed when a Grid Y Pattern is encountered and there is code in this section. Code in this section indicates that the controller supports a Grid Y Pattern command.

If the controller does not support Grid Y Patterns, then the UPG breaks the Grid Pattern into individual drill holes and calls a similar single hole section instead.
## **Description**


|**Section Lines**|**Possible G Code Output**|
| :- | :- |
|:T:<N><G:68><X!:ABS\_X\_START><Y!:ABS\_Y\_START>|N7 G68 X0 Y0 R90|
|:T:R<#:ANGLE><EOL>| |
|<p>:T:<N><G37><G37.1><X!:ABS\_X\_START></p><p><Y!:ABS\_Y\_START></p>|N8 G37.1 X1. Y1.|
|:T:I<#:DIST\_BET\_HOLES\_X>|I1.|
|:T:P<"%-2T":(NUM\_HITS\_X-1)>|P4|
|:T:J<#:DIST\_BET\_HOLES\_Y>|J1.|
|:T:K<"%-2T":(NUM\_HITS\_Y-1)><EOL>|K4|



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:68>|Rotate|G68|
|<X!:ABS\_X\_START >|X pattern start|X1.|
|<Y!:ABS\_Y\_START >|Y pattern start|Y1.|
|R<#:ANGLE>|Rotation angle|R90|
|<G37>|Grid Pattern|G37|
|<G37.1>|Hard coded .1|.1|
|I<#:DIST\_BET\_HOLES\_X>|X distance between holes|I1.|
|P<"%-2T":(NUM\_HITS\_X-1)>|X number of holes|P4|
|J<#:DIST\_BET\_HOLES\_Y>|Y distance between holes|J1.|
|K<"%-2T":(NUM\_HITS\_Y-1)>|Y number of holes|K4|
|<EOL>|End of line| |


## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X5. Y5.

N5 G43 H01 Z.1 M08

N6 G99 G81 R.1 Z-1. F10. } Grid pattern definition

N7 G68 X0 Y0 R90. } Rotate 90 degrees

N8 G37.1 X1. Y1. I1. P4 J1. K4 *}* Grid pattern call

N9 G80 Z1. M09

N10 G91 G28 Z0

N11 M30
# <a name="chmtopic254"></a>**Square X Pattern**
The Square X Pattern section drills holes starting in the X direction first using a Square X Pattern command that is supported by the controller when an Square X Pattern entity is encountered.

![image\pin_bl.gif] Fanuc and Fanuc compatible controllers do not support this canned cycle, so an example for another controller is used. Additional calculations are required to support this canned cycle on a Fanuc or Fanuc compatible controller. For more information, contact your CAMWorks Reseller.
## **When This Section is Called**
The Square X Pattern section is executed when a Square X Pattern is encountered and there is code in this section. Code in this section indicates that the controller supports a Square X Pattern command.

If the controller does not support Square X Patterns, then the UPG breaks the Square Pattern into individual drill holes and calls a similar single hole section instead.
## **Description**


|**Section Lines**|**Possible G Code Output**|
| :- | :- |
|<p>:T:<N><G:38><G37.1><X!:ABS\_X\_START></p><p><Y!:ABS\_Y\_START></p>|N7 G38.1 X1. Y1.|
|:T:I<#:DIST\_BET\_HOLES\_X>|I1.|
|:T:P<"%-2T":(NUM\_HITS\_X-1)><EOL>|P4|



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:38>|Square pattern|G38|
|<G37.1>|Hardcoded .1|.1|
|<X!:ABS\_X\_START >|X pattern start|X1.|
|<Y!:ABS\_Y\_START >|Y pattern start|Y1.|
|I<#:DIST\_BET\_HOLES\_X>|X,Y distance between holes|I1.|
|P<"%-2T":(NUM\_HITS\_X-1)>|X,Y Number of holes|P4|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X5. Y5.

N5 G43 H01 Z.1 M08

N6 G99 G81 R.1 Z-1. F10.  } Square X pattern definition

N7 G38.1 X1. Y1. I2. J0 } Square X pattern call

N8 G80 Z1. M09

N9 G91 G28 Z0

N10 M30
# <a name="chmtopic256"></a>**Square Y Pattern**
The Square Y Pattern section drills holes starting in the Y direction first using a Square Y Pattern command that is supported by the controller when a Square Y Pattern entity is encountered.

![image\pin_bl.gif] Fanuc and Fanuc compatible controllers do not support this canned cycle, so an example for another controller is used. Additional calculations are required to support this canned cycle on a Fanuc or Fanuc compatible controller. For more information, contact your CAMWorks Reseller.
## **When This Section is Called**
The Square Y Pattern section is executed when a Square Y Pattern is encountered and there is code in this section. Code in this section indicates that the controller supports a Square Y Pattern command.

If the controller does not support Square Y Patterns, then the UPG breaks the Square Pattern into individual drill holes and calls a similar single hole section instead.
## **Description**


|**Section Lines**|**Possible G Code Output**|
| :- | :- |
|:T:<N><G:68><X!:ABS\_X\_START><Y!:ABS\_Y\_START>|N7 G68 X1. Y1. R90|
|R<#:ANGLE><EOL>| |
|<p>:T:<N><G:38><G37.1><X!:ABS\_X\_START></p><p><Y!:ABS\_Y\_START></p>|N8 G38.1 X1. Y1.|
|:T:I<#:DIST\_BET\_HOLES\_X>|I1.|
|:T:P<"%-2T":(NUM\_HITS\_X-1)><EOL>|P4|



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:68>|Rotate|G68|
|<X!:ABS\_X\_START >|X pattern start|X1.|
|<Y!:ABS\_Y\_START >|Y pattern start|Y1.|
|R<#:ANGLE>|Rotation angle|R90|
|<G:38>|Square pattern|G38|
|<G37.1>|Hardcoded .1|.1|
|I<#:DIST\_BET\_HOLES\_X>|X,Y distance between holes|I1.|
|P<"%-2T":(NUM\_HITS\_X-1)>|X,Y number of holes|P4|
|<EOL>|End of line| |


## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G90 G54 G00 X5. Y5.

N5 G43 H01 Z.1 M08

N6 G99 G81 R.1 Z-1. F10.   } Square Y pattern definition

N7 G68 X0 Y0 R90.    } Rotate 90 degrees

N8 G38.1 X1. Y1. I1. P4 J1. K4  } Square Y pattern call

N9 G80 Z1. M09

N10 G91 G28 Z0

N11 M30
# <a name="chmtopic63"></a>**Macro Sections**
Macro sections define the G code output format for macros. Macros and subroutines are different terminology for the same thing. The Universal Post Generator uses the terminology interchangeably.



|**Section**|**Description**|
| :- | :- |
|<p>Begin Macro</p><p>End Macro</p>|<p>} Defines start of subroutine</p><p>} Defines end of subroutine</p>|
|<p>Single Macro Call</p><p>Single Macro Rotate Call</p>|<p>} All Rapids Inside the Subroutine</p><p>} All Rapids Inside the Subroutine</p>|
|<p>Single 1st Macro Rapid</p><p>Single Macro Rapid</p>|<p>} Initial Rapids Outside the Subroutine</p><p>} Initial Rapids Outside the Subroutine</p>|
|<p>Macro Rotate 1st Rapid</p><p>Macro Rotate Rapid</p>|<p>} Initial Rapids Outside the Subroutine</p><p>} Initial Rapids Outside the Subroutine</p>|
|<p>Macro 1st Rapid Work Coord</p><p> </p><p>Macro Rapid Work Coord</p>|<p>} Initial Rapids Outside the Subroutine<br>Using Work Coord</p><p>} Initial Rapids Outside the Subroutine<br>Using Work Coord.</p>|
|Macro Work Coord|} Use Work Coordinates to Define Call<br>Position All Rapids Inside Subroutine|
|<p>Offset X</p><p>Offset Y</p><p>Offset Part</p><p>Offset Rotate Part</p><p>Offset Rotate X</p><p>Offset Rotate Y</p>|<p>} Not implemented in this release.</p><p>} Not implemented in this release.</p><p>} Not implemented in this release.</p><p>} Not implemented in this release.</p><p>} Not implemented in this release.</p><p>} Not implemented in this release.</p>|

# <a name="chmtopic259"></a>**Turning on Macro Calls and Rotates**


Options in the Header, Misc., and Mill 2D tabs control whether the post supports macro calls and macro rotates and whether work coordinates can be used with macros. The settings for these options affect the CAM capabilities and the G code output.

**Header Tab Options**

The Macros options define whether the controller supports macro calls and macro rotates.

- If supported, macro calls, grid and rotates are available in the ProCAM system and when created will be output using the controller's macro calls and rotate commands.
- If the controller does not support macro calls, grid and rotates, then the Universal Post Generator will be break macro calls into individual moves supported by the controller.

**Settings for Macros Options**

- [Macro Calls](#chmtopic64)

If the controller supports macro calls, select True. This allows the macro call sections to be called. Otherwise, pick False.

- [Macro Rotate](#chmtopic64)

If macro rotates are supported about the X, Y or Z axis, select the appropriate check box: Rotate About X, Y or Z. All or none of the three check boxes can be selected. Picking one of these options allows the Macro Rotate sections to be called.



**Misc. Tab Option**

The Use Work Coordinate in Macro Call option controls if work coordinates can be used when generating G code for macros.

- If [Use Work Coordinate in Macro Call](#chmtopic74) is selected, then all macros can be called using work coordinates.
- If Use Work Coordinate in Macro Call is not selected, then macro calls cannot be called using work coordinates.

**Mill 2D Tab Options**

The Macro options define whether the work coordinate parameters display in the ProCAM Set Operation – Post Parameters dialog box.

- [Use Work Coordinate](#chmtopic95)

If you set Macro Calls to True in the Header tab, you should check this parameter, which allows the user to decide if work coordinates should be used for a macro operation.

- [Work Coordinate](#chmtopic87)

If Use Work Coordinates is set to Yes in the Set Operation – Post Parameters dialog box, this parameter allows the user to set the work coordinate to be used for a macro call. If you check the Use Work Coordinates option, this parameter should also be checked.

This option should also be checked if you are using the Macro Work Coord section to define a subroutine with work coordinates before the subroutine call and all rapids are inside the subroutine.
# <a name="chmtopic265"></a>**Defining Subroutines to Output Macros**
In ProCAM, you can define macros, call macros, multiple macros (grid macros) and rotate macros. Macros are supported in the UPG by defining subroutines to output the macros defined in the CAM system. Begin Macro and End Macro define how to start and end a subroutine. For example, in a Fanuc controller a subroutine start is defined by outputting a line of G code with the new program number on it. The subroutine code is then output and the subroutine end is defined with an M99.

In the example below the subroutine starts at Sub Program Number O0002 and ends with the code M99. Line N4 in the main program sets the local coordinate system of the macro, while line N5 does a macro call. Lines N6-7 reset the local coordinates and other variables after the macro call.



O0001    } Main Program Number

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G52 X5.Y5.    } Local Coordinate System

N5 M98 P0002   } Subroutine Call

N6 G52 X0 Y0

N7 G91 G28 Z0

N8 M30     } End Main Program

O0002    } Sub Program Number

N1 G90 G54 G00 X5. Y5.

N2 G43 H01 Z.1 M08

N3 G99 G81 R.1 Z-1. F10.

N4 G80 Z1. M09

N5 M99     } End Macro



There are four methods of defining subroutines in the UPG. Each method is supported with a different set of sections. Regardless of the type of subroutine definition, a subroutine is created and called. The difference comes down to the programmer's preference of how this is done. For example, some programmers want to do the initial rapids before the subroutine call and some want to do all rapiding within the subroutine.

When creating the post processor, you, the programmer, must decide which of the four methods you want to use. Your choice is fixed unless you change the post again. You choose between the four types of subroutines by putting code blocks in the preferred type and leaving the other types blank. The four methods are explained below.

![image\pin_bl.gif] The [Begin Macro](#chmtopic261) and [End Macro](#chmtopic262) sections are used with all four methods of defining subroutines.



The four methods of defining subroutines are discussed in the following topics:

[All Rapids Inside Subroutine](#chmtopic263)

[Initial Rapids Outside Subroutine](#chmtopic264)
# <a name="chmtopic263"></a>**All Rapids Inside Subroutine**
**No Work Coordinates in Macro Call**

This method of [defining subroutines](#chmtopic265) can first set the local coordinate system, then calls the subroutine with all rapids inside the subroutine.
## **Required Settings**
- Header tab: Macros Calls is set to True.
- Misc. tab: Use Work Coordinate in Macro Call is *not* checked.
- Mill 2D tab: For Macro operations, Use Work Coordinate and Work Coordinate are *not* checked.
## **Sections Used for This Method**
- Single Macro Call
- Single Macro Rotate Call

O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G52 X5.Y5.   } Local Coordinate System

N5 M98 P0002   } Subroutine Call

N6 G52 X0 Y0

N7 G91 G28 Z0

N8 M30

O0002   } Sub Program Number

N1 G90 G54 G00 X5. Y5. } Initial XY Rapid Inside Sub

N2 G43 H01 Z.1 M08 } Initial Rapid Z Down Inside Subroutine

N3 G99 G81 R.1 Z-1. F10.

N4 G80 Z1. M09

N5 M99



**Work Coordinates in Macro Call**

First output the work coordinate with all rapid moves done inside the subroutine.
## **Required Settings**
- Header tab: Macro Calls is set to True.
- Misc. tab: Use Work Coordinate in Macro Call is checked.
- Mill 2D tab: For Macro operations, Use Work Coordinate is not checked and Work Coordinate is checked.
- **ProCAM** Set Operation - Post Parameters dialog box: Work Coordinate parameter can be set to 54-59.
## **Section Used for This Method**
- Macro Work Coord



O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G54   } Work Coordinates

N5 M98 P0002   } Subroutine Call

N8 G91 G28 Z0

N9 M30

O0002    } Sub Program Number

N1 G90 G00 X5. Y5.  } Rapid XY Move Inside Subroutine

N2 G43 H01 Z.1 M08 } Rapid Z Down Inside Subroutine

N3 G99 G81 R.1 Z-1. F10.

N4 G80 Z1. M09

N5 M99
# <a name="chmtopic264"></a>**Initial Rapids Outside Subroutine**
**No Work Coordinates in Macro Call**

When you use this method of [defining subroutines](#chmtopic265), the initial rapid moves are done outside the subroutine with no work coordinates and before the macro call.
## **Required Settings**
- Header tab: Macro Calls is set to True.
- Misc. tab: Use Work Coordinate in Macro Call is checked.
- Mill 2D tab: For Macro operations, Use Work Coordinate and Work Coordinate are checked.
- **ProCAM** Set Operation - Post Parameters dialog box: Using Work Coordinates parameter is set to No.
## **Sections Used for This Method**
- Single 1st Macro Rapid
- Single Macro Rapid
- Macro Rotate 1st Rapid
- Macro Rotate Rapid
- Macro 1<sup>st</sup> Rapid Work Coord
- Macro Rapid Work Coord

O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G52 X5.Y5.  } Local Coordinate

N5 G00 X5. Y5.  } Rapid XY Move Outside Subroutine

N6 G43 H01 Z.1 M08  } Rapid Z Down Outside Subroutine

N7 M98 P0002   } Subroutine Call

N8 G52 X0 Y0

N9 G91 G28 Z0

N10 M30

O0002    } Sub Program Number

N1 G99 G81 R.1 Z-1. F10.

N3 G80 Z1. M09

N3 M99



**Work Coordinates in Macro Call**

The rapid moves are done outside the subroutine before the macro call using work coordinates.
## **Required Settings**
- Header tab: Macro Calls is set to True.
- Misc. tab: Use Work Coordinate in Macro Call is checked.
- Mill 2D tab: For Macro operations, Use Work Coordinate and Work Coordinate are checked.
- **ProCAM** Set Operation - Post Parameters dialog box: Using Work Coordinates parameter is set to Yes.
## **Sections Used for This Method**
- Single 1st Macro Rapid
- Single Macro Rapid
- Macro Rotate 1st Rapid
- Macro Rotate Rapid
- Macro 1st Rapid Work Coord
- Macro Rapid Work Coord

O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G00 G54 X5. Y5.  } Rapid XY Move Outside Subroutine Using Work Coordinates

N5 G43 H01 Z.1 M08  } Rapid Z Down Outside Subroutine

N6 M98 P0002   } Subroutine Call

N7 G91 G28 Z0

N8 M30

O0002    } Sub Program Number

N1 G99 G81 R.1 Z-1. F10.

N3 G80 Z1. M09

N3 M99
# <a name="chmtopic261"></a>**Begin Macro**
The Begin Macro section defines the start of a subroutine.
## **When Section Is Called**
The Begin Macro section is the first section called at the start of a subroutine definition. The Begin Macro section is used with all four [methods of defining subroutines](#chmtopic265).
## **Description**
**Section Line**

:T:O<"%4LT":(program\_number+CURRENT\_MACRO\_NUMBER)><EOL>

**Possible G Code Output**

O0002



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|O<"%4LT":(program\_number+<br>CURRENT\_MACRO\_NUMBER)>|Subroutine program number|O0001|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G52 X5.Y5.

N5 M98 P0002

N6 G52 X0 Y0

N7 G91 G28 Z0

N8 M30

O0002   } Sub Program Start (Begin Macro)

N1 G90 G54 G00 X5. Y5.

N2 G43 H01 Z.1 M08

N3 G99 G81 R.1 Z-1. F10.

N4 G80 Z1. M09

N5 M99
# <a name="chmtopic262"></a>**End Macro**
The End Macro section defines the end of a subroutine.
## **When Section Is Called**
The End Macro section is the last section called in a subroutine definition. The End Macro section is used with all four [methods of defining subroutines](#chmtopic265).
## **Description**
**Section Lines**

:T:<N><G:90><EOL>

:T:<N><M:99><EOL>

**Possible G Code Output**

N4 G90

N5 M99



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:90>|Absolute positioning|G90|
|<EOL>|End of line| |
|<M:99>|End of subroutine|M99|
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G52 X5.Y5.

N5 M98 P0002

N6 G52 X0 Y0

N7 G91 G28 Z0

N8 M30

O0002

N1 G90 G54 G00 X5. Y5.

N2 G43 H01 Z.1 M08

N3 G99 G81 R.1 Z-1. F10.

N4 G80 Z1. M09

N5 M99    } Sub Program End (End Macro)
# <a name="chmtopic271"></a>**Single Macro Call**


The Single Macro Call section defines a subroutine with all rapids inside the subroutine.
## **When Section Is Called**
The Single Macro Call section is called whenever a Macro Call is encountered and the Macro Calls option in the Header tab is set to True. This section is used regardless of whether it is immediately after a tool change or not.
## **Description**
**Section Lines**

:T:<N><G:90><EOL>

:T:<N><G:52><X\_OFFSET><Y\_OFFSET><EOL>

:T:<N><M:98> P<"%4LT":(program\_number+CURRENT\_MACRO\_NUMBER)><EOL>

**Possible G Code Output**

N1 G90

N2 G52 X5. Y10.

N3 M98 P0002



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:90>|Absolute positioning|G90|
|<EOL>|End of line| |
|<G:52>|Local coordinate system|G52|
|<X\_OFFSET>|X offset|X5.|
|<Y\_OFFSET>|Y offset|Y5.|
|<M:98>|Subroutine call|M98|
|<p>P<"%4LT":(program\_number+</p><p>CURRENT\_MACRO\_NUMBER)></p>|Subroutine program number|P0002|
## **Example**
O0001

N1 G20 G40 G80

N2 T01 M06

N3 S1000 M03

N4 G90

N5 G52 X5.Y5.   } Local Coordinate System

N6 M98 P0002   } Subroutine Call

N7 G91 G28 Z0

N8 M30

O0002    } Sub Program Number

N1 G90 G54 G00 X5. Y5. } Initial XY Rapid Inside Sub

N2 G43 H01 Z.1 M08 } Initial Rapid Z Down Inside Subroutine

N3 G99 G81 R.1 Z-1. F10.

N4 G80 Z1. M09

N5 M99
# <a name="chmtopic274"></a>**Single Macro Rotate Call**


The Single Macro Rotate Call section defines a subroutine with rotation angle and all rapids inside the subroutine.
## **When Section Is Called**
The Single Macro Rotate Call section is called whenever a Macro Rotate is encountered and the Macro Rotate in the Header tab is set to support the correct Rotate About option. This section is used regardless of whether it is immediately after a tool change or not.
## **Description**
**Section Line**

:T:<N><G:52><X\_OFFSET><Y\_OFFSET><Z\_OFFSET> <EOL>

:T:<N><M:98> P<"%4LT":(program\_number+CURRENT\_MACRO\_NUMBER)><EOL>

**Possible G Code Output**

N2 G52 X5. Y10.

N3 M98 P0002



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:52>|Local coordinate system|G52|
|<X\_OFFSET>|X offset|X5.|
|<Y\_OFFSET>|Y offset|Y5.|
|<Z\_OFFSET>|Z offset|Z5.|
|<EOL>|End of line| |
|<M:98>|Subroutine call|M98|
|<p>P<"%4LT":(program\_number+</p><p>CURRENT\_MACRO\_NUMBER)></p>|Subroutine program number|P0002|
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 A90.    } Subroutine Rotate Angle

(see [Rotate About X](#chmtopic273) section)

N5 G52 X5.Y5.    } Local Coordinate System

N6 M98 P0002   } Subroutine Call

N7 G52 X0 Y0

N8 G91 G28 Z0

N9 M30

O0002     } Sub Program Number

N1 G90 G54 G00 X5. Y5.  } Initial XY Rapid Inside Sub

N2 G43 H01 Z.1 M08  } Initial Rapid Z Down Inside Subroutine

N3 G99 G81 R.1 Z-1. F10.

N4 G80 Z1. M09

N5 M99
# <a name="chmtopic276"></a>**Single 1st Macro Rapid**


The Single 1st Macro Rapid section defines a subroutine with initial rapid positioning before the subroutine call with no work coordinate and a tool change immediately preceding this section.
## **When Section Is Called**
The Single 1st Macro Call section is called whenever a Macro Call is encountered and the following conditions are met:

- A tool change immediately preceded this section.
- There are code blocks in this section.
- Header tab: Macro Calls is set to True.
- Misc. tab: Use Work Coordinate in Macro Call is checked.
- Mill 2D tab: for Macro operations, Use Work Coordinate and Work Coordinate are checked.
## **Description**

|**Section Line**|**Possible G Code Output**|
| :- | :- |
|:T:<N><G:90><EOL>|N1 G90|
|:T:<N><G:52><X\_OFFSET><Y\_OFFSET><EOL>|N2 G52 X5. Y10.|
| | |
|:T:<N><G!:00><X!><Y!><EOL>|N3 G00 X10. Y10.|
|<p>:T:<N><G:43><G:00>H<"%2LT":TOOL><Z!></p><p><M:COOLANT\_TYPE><EOL></p>|N4 G43 G00 H01 Z.1 M08|
|<p>:T:<N><M:98><"%4LT":(program\_number+</p><p>CURRENT\_MACRO\_NUMBER)><EOL></p>|N5 M98 P0002|



|Section Code|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:90>|Absolute positioning|G90|
|<EOL>|End of line| |
|<G:52>|Local coordinate system|G52|
|<X\_OFFSET>|X offset|X5.|
|<Y\_OFFSET>|Y offset|Y5.|
|<M:98>|Subroutine call|M98|
|P<"%4LT":(program\_number+ CURRENT\_MACRO\_NUMBER)>|Subroutine program number|P0002|
|<G:00>|Rapid move|G00|
|<X!>|X movement|X10.|
|<Y!>|Y movement|Y10.|
|<G:43>|Tool length compensation +|G43|
|H<"%2LT":TOOL>|Tool length offset|H01|
|<Z!>|Z rapid to clearance plane|Z.1|
|<M!:COOLANT\_TYPE>|Type of coolant|M07, M08, or M09|
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G52 X5.Y5.  } Local Coordinate System

N5 G00 X5. Y5.   } Rapid XY Move Outside Subroutine

N6 G43 H01 Z.1 M08  } Rapid Z Down Outside Subroutine

N7 M98 P0002   } Subroutine Call

N8 G52 X0 Y0

N9 G91 G28 Z0

N10 M30

O0002    } Sub Program Number

N1 G99 G81 R.1 Z-1. F10.

N3 G80 Z1. M09

N3 M99
# <a name="chmtopic278"></a>**Single Macro Rapid**


The Single Macro Rapid section defines a subroutine with initial rapid positioning before the subroutine call with no work coordinate and a tool change does not immediately precede this section.
## **When Section Is Called**
The Single Macro Rapid section is called whenever a Macro Call is encountered and the following conditions are met:

- A tool change does not immediately precede this section.
- There are code blocks in this section.
- Header tab: Macro Calls is set to True.
- Misc. tab: Use Work Coordinate in Macro Call is checked.
- Mill 2D tab: for Macro operations, Use Work Coordinate and Work Coordinate are checked.
## **Description**

|**Section Lines**|**Possible G Code Output**|
| :- | :- |
|:T:<N><G:90><EOL>|N1 G90|
|:T:<N><G:52><X\_OFFSET><Y\_OFFSET><EOL>|N2 G52 X5. Y10.|
|:T:<N><G!:00><X!><Y!><EOL>|N3 G00 X10. Y10.|
|:T:<N><G:00><Z><EOL>|N4 G00 Z.1|
|<p>:T:<N><M:98><"%4LT":(program\_number+</p><p>CURRENT\_MACRO\_NUMBER)><EOL></p>|N5 M98 P0002|



|Section Code|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:90>|Absolute positioning|G90|
|<EOL>|End of line| |
|<G:52>|Local coordinate system|G52|
|<X\_OFFSET>|X offset|X5.|
|<Y\_OFFSET>|Y offset|Y5.|
|<M:98>|Subroutine call|M98|
|P<"%4LT":(program\_number+ CURRENT\_MACRO\_NUMBER)>|Subroutine program number|P0002|
|<G:00>|Rapid move|G00|
|<X!>|X movement|X10.|
|<Y!>|Y movement|Y10.|
|<Z>|Z rapid to clearance plane|Z.1|
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G52 X5.Y5.  } Local Coordinate System

N5 G00 X5. Y5.   } Rapid XY Move Outside Subroutine

N6 G43 H01 Z.1 M08  } Rapid Z Down Outside Subroutine

N7 M98 P0002   } Subroutine Call

N8 G52 X5.Y5.   } Local Coordinate System

N9 G00 X10. Y10.  } Rapid XY Move Outside Subroutine

N10 Z.1    } Rapid Z Down Outside Subroutine

N11 M98 P0002   } Subroutine Call

N12 G52 X0 Y0

N13 G91 G28 Z0

N14 M30

O0002    } Sub Program Number

N1 G99 G81 R.1 Z-1. F10.

N3 G80 Z1. M09

N3 M99
# <a name="chmtopic280"></a>**Macro Rotate 1st Rapid**
The Macro Rotate 1st Rapid section defines a subroutine with rotation angle, initial rapids outside the subroutine and no work coordinate.
## **When Section Is Called**
The Macro Rotate 1st Rapid section is called whenever a Macro Rotate is encountered and the following conditions are met:

- A tool change immediately preceded this section.
- There are code blocks in this section.
- Header tab: Macro Rotate is set to support the correct Rotate About option.
- Misc. tab: Use Work Coordinate in Macro Call is checked.
- Mill 2D tab: for Macro operations, Use Work Coordinate is not checked and Work Coordinate is checked.
## **Description**

|**Section Lines**|**Possible G Code Output**|
| :- | :- |
|:T:<N><G:52><X\_OFFSET><Y\_OFFSET><EOL>|N2 G52 X5. Y10.|
|:T:<N><G!:00><X!><Y!><EOL>|N3 G00 X10. Y10.|
|<p>:T:<N><G:43><G:00>H<"%2LT":TOOL><Z!></p><p><M:COOLANT\_TYPE><EOL></p>|N4 G43 G00 H01 Z.1 M08|
|<p>:T:<N><M:98><"%4LT":(program\_number+</p><p>CURRENT\_MACRO\_NUMBER)><EOL></p>|N5 M98 P0002|



|Section Code|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<EOL>|End of line| |
|<G:52>|Local coordinate system|G52|
|<X\_OFFSET>|X offset|X5.|
|<Y\_OFFSET>|Y offset|Y5.|
|<M:98>|Subroutine call|M98|
|<p>P<"%4LT":(program\_number+</p><p>CURRENT\_MACRO\_NUMBER)></p>|Subroutine program number|P0002|
|<G!:00>|Rapid move|G00|
|<X!>|X movement|X10.|
|<Y!>|Y movement|Y10.|
|<G:43>|Tool length compensation +|G43|
|<Z!>|Z rapid to clearance plane|Z.1|
|H<"%2LT":TOOL>|Tool length offset|H01|
|<M!:COOLANT\_TYPE>|Type of coolant|M07, M08 or M09|
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 A90.   } Subroutine Rotate Angle

(see [Rotate About X](#chmtopic273) section)

N5 G52 X5.Y5.  } Local Coordinate System

N6 G00 X5. Y5.   } Rapid XY Move Outside Subroutine

N7 G43 H01 Z.1 M08  } Rapid Z Down Outside Subroutine

N8 M98 P0002   } Subroutine Call

N9 G52 X0 Y0

N10 G91 G28 Z0

N11 M30

O0002    } Sub Program Number

N1 G99 G81 R.1 Z-1. F10.

N3 G80 Z1. M09

N3 M99
# <a name="chmtopic282"></a>**Macro Rotate Rapid**
The Macro Rotate Rapid section defines a subroutine with rotation angle, initial rapids outside the subroutine and no work coordinate.
## **When Section Is Called**
The Macro Rotate Rapid section is called whenever a Macro Rotate is encountered and the following conditions are met:

- A tool change does *not* immediately precede this section.
- There are code blocks in this section.
- Header tab: Macro Rotate is set to support the correct Rotate About option.
- Misc. tab: Use Work Coordinate in Macro Call is checked.
- Mill 2D tab: for Macro operations, Use Work Coordinate and Work Coordinate are checked.
## **Description**

|**Section Lines**|**Possible G Code Output**|
| :- | :- |
|:T:<N><G:52><X\_OFFSET><Y\_OFFSET><EOL>|N1 G52 X5. Y10.|
|:T:<N><G!:00><X!><Y!><EOL>|N2 G00 X10. Y10.|
|:T:<N><G:00><Z><EOL>|N3 G00 Z.1|
|<p>:T:<N><M:98><"%4LT":(program\_number+</p><p>CURRENT\_MACRO\_NUMBER)><EOL></p>|N4 M98 P0002|



|Section Code|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<EOL>|End of line| |
|<G:52>|Local coordinate system|G52|
|<X\_OFFSET>|X offset|X5.|
|<Y\_OFFSET>|Y offset|Y5.|
|<M:98>|Subroutine call|M98|
|P<"%4LT":(program\_number+ CURRENT\_MACRO\_NUMBER)>|Subroutine program number|P0002|
|<G:00>|Rapid move|G00|
|<X!>|X movement|X10.|
|<Y!>|Y movement|Y10.|
|<Z>|Z rapid to clearance plane|Z.1|
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 A90.

N5 G52 X5.Y5.

N6 G00 X5. Y5.

N7 G43 H01 Z.1 M08  

N8 M98 P0002   

N9 A180.    } Subroutine Rotate Angle

(see [Rotate About X](#chmtopic273) section)

N10 G52 X10. Y10.  } Local Coordinate System

N11 G00 X10. Y10.  } Rapid XY Move Outside Subroutine

N12 Z.1   } Rapid Z Down Outside Subroutine

N13 M98 P0002  } Subroutine Call

N14 G52 X0 Y0

N15 G91 G28 Z0

N16 M30

O0002    } Sub Program Number

N1 G99 G81 R.1 Z-1. F10.

N3 G80 Z1. M09

N3 M99
# <a name="chmtopic284"></a>**Macro Work Coord**
The Macro Work Coord section defines a subroutine with work coordinates before the subroutine call and all rapids are inside the subroutine.
## **When Section Is Called**
The Macro Work Coord section is called whenever a Macro Call is encountered and the following conditions are met:

- This section is used regardless of whether it is immediately after a tool change or not.
- There are code blocks in this section.
- Header tab: Macro Calls is set to True.
- Misc. tab: Use Work Coordinate in Macro Call is checked.
- Mill 2D tab: For Macro operations, Use Work Coordinates is not checked and Work Coordinate is checked.
## **Description**


|**Section Line**|**Possible G Code Output**|
| :- | :- |
|:T:<N><G:90><EOL>|N1 G90|
|:T:<N><G!:sub\_work\_coord><EOL>|N2 G54|
|<p>:T:<N><M:98><"%4LT":(program\_number+</p><p>CURRENT\_MACRO\_NUMBER)><EOL></p>|N3 M98 P0002|



|Section Code|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:90>|Absolute positioning|G90|
|<EOL>|End of line| |
|<G!:sub\_work\_coord>|Work Coordinate|G54|
|<M:98>|Subroutine call|M98|
|P<"%4LT":(program\_number+ CURRENT\_MACRO\_NUMBER)>|Subroutine program number|P0002|


## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G54    } Work Coordinates

N5 M98 P0002   } Subroutine Call

N8 G91 G28 Z0

N9 M30

O0002    } Sub Program Number

N1 G90 G00 X5. Y5. } Rapid XY Move Inside Subroutine

N2 G43 H01 Z.1 M08 } Rapid Z Down Inside Subroutine

N3 G99 G81 R.1 Z-1. F10.

N4 G80 Z1. M09

N5 M99
# <a name="chmtopic286"></a>**Macro 1st Rapid Work Coord**
The Macro 1st Rapid Work Coord section defines a subroutine with initial rapid positioning before the subroutine call using work coordinates and a tool change immediately preceded this section.
## **When Section Is Called**
The Macro 1st Rapid Work Coord section is called whenever a Macro Call is encountered and the following conditions are met:

- A tool change immediately preceded this section.
- There are code blocks in this section.
- Header tab: Macro Calls is set to True.
- Misc. tab: Use Work Coordinate in Macro Call is checked.
- Mill 2D tab: for Macro operations, Use Work Coordinate and Work Coordinate are checked.
- **ProCAM** Set Operation – Post Parameters dialog box: Using Work Coordinates parameter is set to Yes.
## **Description**

|**Section Line**|**Possible G Code Output**|
| :- | :- |
|:T:<N><G:90><EOL>|N1 G90|
|<p>:T:<N><G!:00><G!:sub\_work\_coord></p><p><X\_OFFSET><Y\_OFFSET><EOL></p>|N2 G00 G54 X5. Y5.|
|<p>:T:<N><G:43><G:00>H<"%2LT":TOOL><Z!></p><p><M:COOLANT\_TYPE><EOL></p>|N3 G43 G00 H01 Z.1 M08|
|<p>:T:<N><M:98><"%4LT":(program\_number+</p><p>CURRENT\_MACRO\_NUMBER)><EOL></p>|N4 M98 P0002|



|Section Code|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:90>|Absolute positioning|G90|
|<EOL>|End of line| |
|<G!:00>|Rapid move|G00|
|<G!:sub\_work\_coord>|Work Coordinate|G54 – G59|
|<X\_OFFSET>|X offset|X10.|
|<Y\_OFFSET>|Y offset|Y10.|
|<G:43>|Tool length compensation +|G43|
|H<"%2LT":TOOL>|Tool length offset|H01|
|<Z!>|Z rapid to clearance plane|Z.1|
|<M!:COOLANT\_TYPE>|Type of coolant|M07, M08 or M09|
|<M:98>|Subroutine call|M98|
|P<"%4LT":(program\_number+ CURRENT\_MACRO\_NUMBER)>|Subroutine program number|P0002|


## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G00 G54 X5. Y5.  } Start Position of Subroutine

Using Work Coordinates

N5 G43 H01 Z.1 M08  } Rapid Z Down Outside Subroutine

N6 M98 P0002   } Subroutine Call

N7 G91 G28 Z0

N8 M30

O0002    } Sub Program Number

N1 G99 G81 R.1 Z-1. F10.

N3 G80 Z1. M09

N3 M99
# <a name="chmtopic288"></a>**Macro Rapid Work Coord**


The Macro Rapid Work Coord section defines a subroutine with initial rapid positioning before the subroutine call using work coordinates and no tool change immediately precedes this section.
## **When Section Is Called**
The Macro Rapid Work Coord section is called whenever a Macro Call is encountered and the following conditions are met:

- A tool change does *not* immediately precede this section.
- There are code blocks in this section.
- Header tab: Macro Calls is set to True.
- Misc. tab: Use Work Coordinate in Macro Call is checked.
- Mill 2D tab: for Macro operations, Use Work Coordinate and Work Coordinate are checked.
- **ProCAM** Set Operation - Post Parameters dialog box: Using Work Coordinates parameter is set to Yes.
## **Description**

|**Section Line**|**Possible G Code Output**|
| :- | :- |
|:T:<N><G:90><EOL>|N1 G90|
|<p>:T:<N><G!:00><G!:sub\_work\_coord></p><p><X\_OFFSET><Y\_OFFSET><EOL></p>|N2 G00 G55 X5. Y5.|
|:T:<N><Z!><EOL>|N3 Z.1|
|<p>:T:<N><M:98><"%4LT":(program\_number+</p><p>CURRENT\_MACRO\_NUMBER)><EOL></p>|N4 M98 P0002|



|Section Code|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|<G:90>|Absolute positioning|G90|
|<EOL>|End of line| |
|<G!:00>|Rapid move|G00|
|<G!:sub\_work\_coord>|Work Coordinate|G55|
|<X\_OFFSET>|X offset|X10.|
|<Y\_OFFSET>|Y offset|Y10.|
|<Z>|Z rapid to clearance plane|Z.1|
|<M:98>|Subroutine call|M98|
|P<"%4LT":(program\_number+ CURRENT\_MACRO\_NUMBER)>|Subroutine program number|P0002|
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 G00 G54 X5. Y5

N5 G43 H01 Z.1 M08

N6 M98 P0002

N7 G00 G55 X10. Y10. } Start Position of Subroutine

Using Work Coordinates

N8 Z.1     } Rapid Z Down Outside Subroutine

N9 M98 P0002   } Subroutine Call

N10 G52 X0 Y0

N11 G91 G28 Z0 M09

N12 M30

O0002    } Sub Program Number

N1 G99 G81 R.1 Z-1. F10.

N3 G80 Z1.

N3 M99
# <a name="chmtopic114"></a>**Rotate Sections**


There are six types of rotate sections that can be called if the controller supports 4th axis rotation in Macro Calls:

[Rotate About X](#chmtopic273)

[Rotate About Y](#chmtopic290)

[Rotate About Z](#chmtopic291)

[Return X](#chmtopic292)

[Return Y](#chmtopic293)

[Return Z](#chmtopic294)
# <a name="chmtopic296"></a>**4th Axis Rotation Support**


If the controller supports 4th axis rotation, the [Macro Rotate](#chmtopic64) group must be set in the Header tab. The check boxes allow setting the 4th axis rotation about the X,Y and Z axis.



These modifiers allow you to select the rotation axis.

If 4th axis rotation occurs in a Macro Call:

- The Rotate About X, Y or Z section is called to set the rotation axis. Next, the Single Macro Rotate Call section is called. This section is probably similar to the Single Macro Call section, but may have some special code for a rotation call.
- If there is no code in the Single Macro Rotate Call section, the Single Macro Call section is called and no rotation is called.
- At the end of the program, the Return X, Y or Z sections are called resetting the 4th axis rotation back to zero.
# <a name="chmtopic273"></a>**Rotate About X**


This section defines the 4th axis rotation command about the X axis for a macro rotation.
## **When Section is Called**
The Rotate About X section is called whenever a 4th axis rotation about the X is encountered and the following conditions are met:

- In the Header tab, the Rotate About X check box in the [Macro Rotate](#chmtopic64) group is selected.
- The rotation angle is different from the currently set rotation angle.
- There are code blocks in this section.
- **ProCAM** The Rotate About X modifier is selected in the ProCAM Macro Call command.
## **Description**
**Section Line**

:T:<N> A<"#3.3n":ROTATE\_ANGLE\_X><EOL>

**Possible G Code Output**

N1 A90



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N1|
|A<"#3.3n":ROTATE\_ANGLE\_X>|Rotate About X|A90|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 A90.   } Rotate About X Angle

N5 G52 X5.Y5.   } Local Coordinate System

N6 M98 P0002  } Subroutine Call

N7 G52 X0 Y0

N8 G91 G28 Z0

N9 M30

O0002    } Sub Program Number

N1 G90 G54 G00 X5. Y5. } Work Coordinates

N2 G43 H01 Z.1 M08 } 1st Rapid Z Down Inside Subrout.

N3 G99 G81 R.1 Z-1. F10.

N4 G80 Z1. M09

N5 M99
# <a name="chmtopic290"></a>**Rotate About Y**


This section defines the 4th axis rotation command about the Y axis for a macro rotation.
## **When Section is Called**
The Rotate About Y section is called whenever a 4th axis rotation about the Y is encountered and the following conditions are met:

- In the Header tab, the Rotate About Y check box in the [Macro Rotate](#chmtopic64) group is selected.
- The rotation angle is different from the currently set rotation angle.
- There are code blocks in this section.
- **ProCAM** The Rotate About Y modifier is selected in the ProCAM Macro Call command.
## **Description**
**Section Line**

:T:<N> B<”#3.3n”:ROTATE\_ANGLE\_Y><EOL>

**Possible G Code Output**

N1 B90



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|B<”#3.3n”:ROTATE\_ANGLE\_Y >|Rotate About Y|B90|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 B90.    } Rotate About Y Angle

N5 G52 X5.Y5.    } Local Coordinate System

N6 M98 P0002   } Subroutine Call

N7 G52 X0 Y0

N8 G91 G28 Z0

N9 M30

O0002     } Sub Program Number

N1 G90 G54 G00 X5. Y5  } Work Coordinates

N2 G43 H01 Z.1 M08  } 1<sup>st</sup> Rapid Z Down Inside Subrout.

N3 G99 G81 R.1 Z-1. F10.

N4 G80 Z1. M09

N5 M99
# <a name="chmtopic291"></a>**Rotate About Z**


This section defines the 4th axis rotation command about the Z axis for a macro rotation.
## **When Section is Called**
The Rotate About Z section is called whenever a 4th axis rotation about the Z is encountered and the following conditions are met:

- In the Header tab, the Rotate About Z check box in the [Macro Rotate](#chmtopic64) group is selected.
- The rotation angle is different from the currently set rotation angle.
- There are code blocks in this section.
- **ProCAM** The Rotate About Z modifier is selected in the ProCAM Macro Call command.
## **Description**
**Section Line**

:T:<N> C<”#3.3n”:ROTATE\_ANGLE\_Z><EOL>

**Possible G Code Output**

N1 C90



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N001|
|C<”#3.3n”:ROTATE\_ANGLE\_Z >|Rotate About Z|C90|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 C90.    } Rotate About Z Angle

N5 G52 X5.Y5.    } Local Coordinate System

N6 M98 P0002   } Subroutine Call

N7 G52 X0 Y0

N8 G91 G28 Z0

N9 M30

O0002     } Sub Program Number

N1 G90 G54 G00 X5. Y5  } Work Coordinates

N2 G43 H01 Z.1 M08  } 1<sup>st</sup> Rapid Z Down Inside Subrout.

N3 G99 G81 R.1 Z-1. F10.

N4 G80 Z1. M09

N5 M99
# <a name="chmtopic292"></a>**Return X Section**


This section resets the 4th axis rotation about the X axis to zero at the end of the program.
## **When This Section is Called**
The Return X section is called after a 4th axis rotation about the X axis and the following conditions are met:

- The rotation angle is not already zero.
- You are at the end of the program.
- There are code blocks in this section.
## **Description**
**Section Line**

:T:<N> A0<EOL>

**Possible G Code Output**

N1 A0



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N1|
|A0|Rotate about X to 0 degrees|A0|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 A90.   } Rotate About X Angle

N5 G52 X5.Y5.   } Local Coordinate System

N6 M98 P0002  } Subroutine Call

N7 G52 X0 Y0

N9 A0.   } Reset X Axis Rotation

N10 G91 G28 Z0

N11 M30

O0002    } Sub Program Number

N1 G90 G54 G00 X5. Y5 } Work Coordinates

N2 G43 H01 Z.1 M08 } 1<sup>st</sup> Rapid Z Down Inside Subrout.

N3 G99 G81 R.1 Z-1. F10.

N4 G80 Z1. M09

N5 M99
# <a name="chmtopic293"></a>**Return Y Section**


This section resets the 4th axis rotation about the Y axis to zero at the end of the program.
## **When Section is Called**
The Return Y section is called after a 4th axis rotation about the Y axis and the following conditions are met:

- The rotation angle is not already zero.
- You are at the end of the program.
- There are code blocks in this section.
## **Description**
**Section Line**

:T:<N> B0<EOL>

**Possible G Code Output**

N1 B0



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N1|
|B0|Rotate about Y to 0 degrees|B0|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 B90.   } Rotate About Y Angle

N5 G52 X5.Y5.   } Local Coordinate System

N6 M98 P0002  } Subroutine Call

N7 G52 X0 Y0

N9 B0.   } Reset Y Axis Rotation

N10 G91 G28 Z0

N11 M30

O0002    } Sub Program Number

N1 G90 G54 G00 X5. Y5 } Work Coordinates

N2 G43 H01 Z.1 M08 } 1<sup>st</sup> Rapid Z Down Inside Subrout.

N3 G99 G81 R.1 Z-1. F10.

N4 G80 Z1. M09

N5 M99
# <a name="chmtopic294"></a>**Return Z Section**


This section resets the 4th axis rotation about the Z axis to zero at the end of the program.
## **When Section is Called**
The Return Z section is called after a 4th axis rotation about the Z axis and the following conditions are met:

- The rotation angle is not already zero.
- You are at the end of the program.
- There are code blocks in this section.
## **Description**
**Section Line**

:T:<N> C0<EOL>

**Possible G Code Output**

N1 C0



|Section|Description|G Code|
| :- | :- | :- |
|:T:|Output a line of G code| |
|<N>|Output a sequence number|N1|
|C0|Rotate about Z to 0 degrees|C0|
|<EOL>|End of line| |
## **Example**
O0001

N1 G20 G40 G80 G90

N2 T01 M06

N3 S1000 M03

N4 C90.   } Rotate About Z Angle

N5 G52 X5.Y5.   } Local Coordinate System

N6 M98 P0002  } Subroutine Call

N7 G52 X0 Y0

N9 C0.   } Reset Z Axis Rotation

N10 G91 G28 Z0

N11 M30

O0002    } Sub Program Number

N1 G90 G54 G00 X5. Y5 } Work Coordinates

N2 G43 H01 Z.1 M08 } 1<sup>st</sup> Rapid Z Down Inside Subrout.

N3 G99 G81 R.1 Z-1. F10.

N4 G80 Z1. M09

N5 M99

[image\do-it.gif]: data:image/gif;base64,R0lGODlhCAAQALMAAAAAAIAAAACAAICAAAAAgIAAgACAgMDAwICAgP8AAAD/AP//AAAA//8A/wD//////yH5BAAAAAAALAAAAAAIABAAAAQZ8MlJAZ3A3qwxr1wXip/XSdn1nGrrvvATAQA7 "image\do-it.gif"
[image\pin_bl.gif]: data:image/gif;base64,R0lGODlhFQAVALMAAB8pRF5eXmtra3NzcwQxqgBE8WN0mUh14ZSUlKCgoK2traSvy8bGxs7Oxs7Ozv///yH5BAEAAA8ALAAAAAAVABUAAASA8MlJq7046835WsfxdQ9YnIXoHehJGMvGFp/7ym1B7AZu74Ce5rArEgBBgWCQUFgWhiISEFgolQjnhOGATqnWqzJBcTwSUIM6LF5OHA4BgDJoXwcSLoJKSdjHEg4JSBMKCQh/WQ8MD0gJj48DCJFKTFoOAVRMj1oaCgMBTSSjGBEAOw== "image\pin_bl.gif"
[ref1]: data:image/gif;base64,R0lGODlhEAAIAIcAAAAAAOzp2P///wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAAAAP8ALAAAAAAQAAgAAAgwAAMIHEgwAAAABRMOBCAAocGDECMeFNDQIMWLGDNOzMiRosSPGx0qXFhxJMGDAwMCADs=
