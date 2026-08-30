

## **Industrial Robotics Lab Report** 

**Group 2A** 

**Student Names Matriculation Number** Arjun Rameshbhai Beladiya 28744163 Dhaval Jagdish Mistry 20644015 Tarang Chimanbhai Italiya 12543942 

July 4, 2025 

Prof. Dr.-Ing. Konrad Wöllhaf 



## **Contents** 

|List|of Figures and Flowcharts . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>3|
|---|---|---|
|**1**<br>**Tea**|**ching Tool and Base, Simple Program**|**5**|
|1.1|Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>5|
|1.2|Objective<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>5|
|1.3|Methodology . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>5|
||1.3.1<br>Teach the Tool using 4-point method . . . . . . . . . . . . .|. . . . . . . . . . . .<br>5|
|1.4|Teaching the Base of the Box . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>8|
||1.4.1<br>Base Calibration . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>8|
|1.5|Create a Box-Following Program<br>. . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>9|
||1.5.1<br>Re-Teaching the Base . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>11|
|1.6|Results<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>11|
||1.6.1<br>Observations<br>. . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>11|
|1.7|Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>11|
|**2**<br>**KUK**|**A.Sim Programming**|**12**|
|2.1|Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>12|
|2.2|Objectives . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>12|
|2.3|Methodology . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>12|
||2.3.1<br>Scribing rectangle using throne<br>. . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>13|
||2.3.2 Drawing the “House of Santa Claus” . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>14|
|2.4|operating the simulation . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>14|
|2.5|Results<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>16|
||2.5.1<br>Observations<br>. . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>16|
||2.5.2 Challenges and Solutions<br>. . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>16|
|2.6|Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>16|
|**3**<br>**Sort**|**ing Balls by Color using KUKA Robot**|**17**|
|3.1|Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>17|
|3.2|Objectives . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>17|
|3.3|Methodology . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>17|
||3.3.1<br>Flow Chart Preparation<br>. . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>17|
||3.3.2 Programming . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>18|
|3.4|Flowchart . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>19|
|3.5|code<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>21|
|3.6|Testing<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>22|
|3.7|Extended version<br>. . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>23|
|3.8|Flowchart for Ball Sorting Program<br>. . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>24|
|3.9|Code<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>26|
|3.10|Testing of extended version. . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>28|



2 



|3.11|Results<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>28|
|---|---|---|
||3.11.1<br>Observations<br>. . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>28|
|3.12|Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>28|
|**4**<br>**Imp**|**lementation of Ball Sorting Program on Robot**|**29**|
|4.1|Introduction . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>29|
|4.2|Objectives . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>29|
|4.3|Methodology . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>29|
||4.3.1<br>Programming . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>29|
||4.3.2 Validation . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>30|
|4.4|Real-Robot Implementation . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>30|
||4.4.1<br>Preparing the Code . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>30|
||4.4.2 Testing and Adapting the Code . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>30|
|4.5|Results<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>35|
||4.5.1<br>Observations<br>. . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>35|
|4.6|Conclusion . . . . . . . . . . . . . . . . . . . . . . . . . . . . .|. . . . . . . . . . . .<br>35|



3 



## **List of Figures and Flowcharts** 

|1.1|First reference point . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>6|
|---|---|
|1.2|Second reference point<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>6|
|1.3|Fourth reference point . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>6|
|1.4|Third reference point<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>6|
|1.5|Tool teaching dialog . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>7|
|1.6|Tool Accuracy . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>7|
|1.7|Position of work piece on table . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>8|
|1.8|First point for base calibration<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>8|
|1.9|Second Point for base calibration . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>9|
|1.10|Third Point for base calibration . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>9|
|1.11|Planned path for box-following program. . . . . . . . . . . . . . . . . . . . . . . . . . .<br>10|
|1.12|Completed box-following program structure. . . . . . . . . . . . . . . . . . . . . . . . .<br>10|
|2.1|Environment<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>13|
|2.2|Drawing rectangle . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>13|
|2.3|Drawing Santa Claus’s house . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>14|
|2.4|Red-Green-Blue Buttons . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>14|
|2.5|Program<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>15|
|3.1|Ball Sorting Program . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>19|
|3.1|Code in KUKA.Sim . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>20|
|3.2|Code in KUKA.Sim (cont.) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>20|
|3.3|Code in KUKA.Sim (cont.) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>20|
|3.2|Extended version of Ball Sorting Program . . . . . . . . . . . . . . . . . . . . . .<br>24|
|3.4|Ext. Ver. Code in KUKA.Sim<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>25|
|3.5|Ext. Ver. Code in KUKA.Sim (cont.)<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>25|
|3.6|Ext. Ver. Code in KUKA.Sim (cont.)<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>25|
|4.1|Peaking up the ball<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>31|
|4.2|Color detection on the sensor. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>31|
|4.3|Move on tho the pallet . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>32|
|4.4|Placing ball on the right pallet<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>32|
|4.5|Home position after one pallet full<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>32|
|4.6|Pallets<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>32|
|4.7|Program in Controller<br>. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>33|
|4.8|Program in Controller (cont.) . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .<br>34|



4 



## **Lab Test 1 Teaching Tool and Base, Simple Program** 

### **1.1 Introduction** 

This lab focused on practical training with KUKA industrial robots, which are widely used in automation due to their precision, flexibility, and ability to perform complex tasks. The main goal was to gain hands-on experience in operating and programming these robots while following strict safety procedures. The tasks included moving the robot in different coordinate systems (axes, world, tool), teaching the tool center point (TCP), teaching the base coordinates of a box, and creating a robot program that moves the tool tip along the box’s edges. Additionally, the lab explored how the robot program can adapt when the box’s position is changed by re-teaching and updating the base coordinates. 

### **1.2 Objective** 

- Move the robot in the diferent coordinate systems (axes, world, tool) 

- Teach the tool 

- Teach the base of the box 

- Code the tool tip to trace the box edges 

- Moves the box, then re-teaches and updates its base values. 

### **1.3 Methodology** 

#### **1.3.1 Teach the Tool using 4-point method** 

To teach the tool, the robot is jogged to four points in space where the tool tip will be located. The KUKA robot uses a 4-point method for this purpose. 

1. Specify the tool number and name. Select tool number 5 and use a name of your choice. Confirm with Continue or Ok. 

2. The dialog then appears with the request to align the tool by moving the robot to the first reference point. The goal is for the tip of the tool to point to the same place from four different directions. 

3. Move the robot to the first reference point as shown in Figures 1.7 and 1.8, and press Continue or Ok. 

4. Repeat this for the next three reference points, ensuring that the tool tip is aligned correctly each time. 

5 

RW RAVENSBHOCHSCH **U** RG-WEINGARTENLE aD U OFUNIVERS APPL ED **I** TY SCIENCES 



<!-- Start of picture text -->
for’ Ei,<br>3 : _<br>_.. »<br><!-- End of picture text -->



<!-- Start of picture text -->
S| (2<br>¥<br><!-- End of picture text -->



<!-- Start of picture text -->
f =" Eee Nica<br><!-- End of picture text -->



<!-- Start of picture text -->
, eS,<br>:<br>. oF ws 4 S<br><!-- End of picture text -->



Figure 1.5: Tool teaching dialog 

5. After the fourth point, the tool is considered taught. The robot will calculate the tool’s position and orientation based on these points. 



Figure 1.6: Tool Accuracy 

7 



### **1.4 Teaching the Base of the Box** 

1. The supervisor first positioned the box on the workbench. 

2. Afterwards, we selected the tool that we had previously taught and used it to touch key corners of the box. 

3. Next, we recorded the coordinates of three non-collinear points: the origin, a point along the X-axis, and a point in the XY-plane to define the Y-axis. 

4. Using these reference points, we were able to define and teach the base coordinate system of the box successfully. 

#### **1.4.1 Base Calibration** 

1. Once the base was taught, we verified the calibration by moving the robot’s tool tip to the recorded points and checking the alignment. 

2. Finally, we fine-tuned the base coordinates as needed to ensure that the tool tip accurately followed the edges of the box. 



Figure 1.7: Position of work piece on table 



Figure 1.8: First point for base calibration 

8 



Figure 1.9: Second Point for base calibration 



Figure 1.10: Third Point for base calibration 

### **1.5 Create a Box-Following Program** 

1. First, we defined the tool number and name in the project settings to ensure the correct tool data is used during the program. 

2. Then, we taught tool to move the robot along the edges of the box as part of the boxfollowing task. 

3. Next,we have moved the tool to the starting position of the box and assign a PTP (Pointto-Point) movement to position the robot quickly and safely at the start. 

4. After setting the starting position,we have moved the robot arm to the first corner of the box. 

5. At this point,we assigned a LIN (linear) movement type to enable the robot to follow the edges of the box precisely. 

6. Then,we move the robot arm to the second corner of the box using a linear movement. 

7. Continue by moving the robot to the remaining corners of the box in a similar manner, following the planned path shown below. 

9 

RW RAVENSBHOCHSCH **U** RG-WEINGARTENLE aD U OFUNIVERS APPL ED **I** TY SCIENCES 



<!-- Start of picture text -->
i Hox<br>Ore @ fir)Nor<br>P re pre<br>ee es BPRearls ae Rome<br>eslegWl ae 0 A BY Emabyee Ee {+{aa Heh Dell afee<br>a<br>EERE<br>HEE EEEEEEEHEH<br><!-- End of picture text -->



<!-- Start of picture text -->
lrfoant |<br>BE | 14 [PrP HOME Uel= 100 % DEFAULT ie)<br>|<br>| | if ;<br>PID 1314. 120 ts Loan : "a ie<br><!-- End of picture text -->



11. Ensure the program logic combines both joint (PTP) and Cartesian (LIN CIRC) movements effectively to achieve accurate and efficient box following. 

#### **1.5.1 Re-Teaching the Base** 

- First, the professor repositioned the box on the workbench. 

- Next, we re-taught the base coordinate system by probing the new corners of the box and recording their coordinates. 

- Then, we updated the control software by overwriting the old base coordinates with the new ones. 

- After that, we ran the existing program to check that the robot correctly followed the edges of the box at its new position. 

### **1.6 Results** 

#### **1.6.1 Observations** 

1. The robot moved accurately within all three coordinate systems: **Axes** , **World** , and **Tool** . Each system presented unique advantages and posed specific challenges when controlling the robot’s movements. 

2. The **tool teaching** process was successful, with the tool tip precisely calibrated to reach all predefined points without error. 

3. The **base coordinate system** was accurately defined and calibrated, providing reliable and precise reference points for the robot program. 

4. During **program execution** , the robot’s tool tip smoothly traced the edges of the box, confirming the program’s effectiveness and precision. 

5. After **re-teaching the base** , the robot adapted seamlessly to the new box position without requiring any program modifications. This demonstrated the robustness and flexibility of the teaching and calibration processes. 

### **1.7 Conclusion** 

This laboratory task effectively demonstrated the movement, calibration, and programming of a KUKA robot across different coordinate systems. We successfully performed tool and base teaching, enabling the robot to accurately follow the edges of a box through a custom program. Furthermore, the robot’s ability to adapt to changes in the base position without program adjustments highlights the critical importance of precise teaching and calibration in robotic automation. The experiment underlines how careful programming and system configuration can overcome common challenges, ensuring reliable and efficient robotic operation. 

11 



## **Lab Test 2 KUKA.Sim Programming** 

### **2.1 Introduction** 

In this task, we programmed the KUKA robot in KUKA.Sim (A robot simulation tool provieded by KUKA) to draw various shapes, beginning with a basic rectangle and advancing to more intricate figures such as the ”house of Santa Claus.” The goal was to gain hands-on experience with robot motion, tool manipulation, and the application of control structures in programming. We directed the robot’s actions using different coordinate systems and utilized commands like WAIT, WHILE, and IF, with digital inputs controlling the flow of the program. 

### **2.2 Objectives** 

This task aimed to achieve the following: 

1. Understand how to control the robot’s movement by working with multiple coordinate systems. 

2. Gain expertise in manipulating and exchanging tools via the robot’s gripper mechanism. 

3. Write programs that enable the robot to draw both basic and complex shapes accurately. 

4. Employ programming logic commands like `WAIT` , `WHILE` , and `IF` to guide the robot’s movements. 

5. Integrate digital inputs to effectively steer the program’s operation and decision-making. 

### **2.3 Methodology** 

The original simulation file, `_RWU_KukaZelle_9.vcmx` , was duplicated and saved under the new name `_RWU_KUKAZelle_9_Group2a.vcmx` . This copied file was then opened to explore the robot’s movements using different coordinate systems, such as axes, world, and tool coordinates. The robot’s gripper was manually guided along the contour of a white sheet placed in the foreground, with all movement points recorded by the software for further use. 

12 

RW RAVENSBHOCHSCH **U** RG-WEINGARTENLE UNIVERSITY OF APPLIED SCIENCES 



<!-- Start of picture text -->
i Ri RWU_KukaZelle_9 Group2a.vemx - KUKASim 4.3<br>Sh eee aoe ie Gawnime Beemer<br>DP rwoFirstMove 3 o = 7<br>Tr LIN PI Vel=2ms CPDAT2. a Sori oue oe, «<br>Suet . w ie i ; > a oe<br>ee —— m\ 2. = -_ ery i] Global i<br>UN P33 Ve=2mi Output FX voement ts<br>PPE © Suchen Bi a: | 10% tence ADE OG asim<br>7 =<br>ae ”” ———L_ LL sl<br>p] ‘ ‘ ‘ , q j<br>nor, v | ! ed a Ges BS.<br>“+ 0 Of4+ ‘ 7 ‘ 7 4 ’ « , jee F& y /y ,  foj sl, u L) +‘ on' = 'jy<br>\ G 7] t ’ 5 , ; ( t , ' ‘ ‘<br>ne es | 2 9 9 ate<br>\ / y 70 (Rab Rak ia, ¢ 4 ’ ' e-<br>\ \ i ¢ -38 : ffaaGe : ‘ =o<br>7 / . F ' ' ' rt<br>DN 7. on L ' ' ' ' { )<br>i} ‘ ' ' ' ' t t<br><!-- End of picture text -->

RW RAVENSBHOCHSCH **U** RG-WEINGARTENLE UNIVERSITY OF APPLIED SCIENCES 



<!-- Start of picture text -->
\<br>v y [Pome<br>‘ ¥ ~\ ' ‘ ‘ \ \ x<br>: ’ ’ y<br>Z ‘ ‘ ‘ ‘<br>\) r 4 ‘ ‘ ’ ! ‘ , ‘ ‘ , ;<br>, , : ,<br>‘ ‘ ‘ ,<br>‘ ’ ‘ ' ,<br>' f F | ; ‘<br>; 4 ve ‘ Y ‘ ’ ry<br>, ; 10 Ee KUICA ’ M M =<br>‘<br>»~ , wl oY = ; a<br>ay 64 ' ‘ . ,<br>¢ ‘ fo =<br>= aa _| ‘ ‘ ‘4 4<br>¢¢3<br>_' ' ‘ ‘<br><!-- End of picture text -->

# =e 



<!-- Start of picture text -->
=e<br><!-- End of picture text -->

RW RAVENSBHOCHSCH **U** RG-WEINGARTENLE aD U UNIVERSOF APPL ED **I** TY SCIENCES 



<!-- Start of picture text -->
=] Main<br><!-- End of picture text -->



<!-- Start of picture text -->
f=) rwuBallTeach<br>[=| rwuFirstMove<br><!-- End of picture text -->

|a ee<br>|<br>Tl.<br>Div>By)<br>dorByElyBr|(Tx)(io)|
|---|---|
|<br>   <br>Jos rwuFirstMove_3{<br>}||
|+<br>*2 Default initialization||
|~~” SPTP HOME Vel=100% DEFAULT Tool[1]:TOOL_DATA[1] Base[0]|0.156 &|
|Je=<br>WAIT FOR $IN[12]==true|1512 E|
|- +, IF SIN[12]==true||
|=<br>Then||
|*<br>SLIN Pl Vel=2 m/s CPDAT?1 Tool[12];Greifer Base[0]|1.140 &|
|“<br>SLIN P2 Vel=2 m/s CPDAT1 Tool[12]:Greifer Base[0]|0.300 &|
|C2 nwuGripperClose(TRUE)||
|*<br>SLIN P3 Vel=? m/s CPDAT2? Tool[12]:Greifer Base[0]|O288 &|
|-"SPTPP14Vel=100%PDATSTool[1}:TOOL_DATA[1]Base[0)|o504©|



= Hse 

<empty> 

- ¢] WHILE $IN[12]==true | 

|—<br>+] WHILE $IN[13]==true||
|---|---|
|C7 rwuTraceOn(TRUE)||
|“<br>SLIN P27 Vel=2 m/s CPDAT40Tool[13]}:dorm Base[0]|0.156 (0.936) 6|
|“S SLIN P31 Vel=2 m/s CPDAT41 Tool[1]:TOOL_DATA[1] Base[0]|0.408 (2.448) 6|
|“S SLIN P32 Vel=2 m/s CPDAT42 Tool[1]:TOOL_DATA[1] Base[0]|0.384 (2.304) 6|
|“S<br>SLIN P33 Vel=2 m/s CPDAT43 Tool[1]:;TOOL_DATA[1] Base[0]|0.432 (2.592) 6|
|“<br>SLIN P34 Vel=2 m/s CPDAT49Tool[13]:dorm Base[0]|0.348 (2.088) &|
|C7 wolraceOn(FALSE)||
|—<br>¢] WHILE $IN[14]==true<br>-<br>SPTP P15 Vel=100% PDATS Tool[1}:TOOL_DATA[1] Base[0)<br>C7 rwulraceOn(TRUE}|0.312 (0.948) 6|
|“S SUIN P16 Vel=2 m/s CPDAT30Tool[1]:TOOL_DATA[1] Base[0]|0.300 (0.900) 6|
|“S SLIN P17 Vel=2 m/s CPDAT31 Tool[1]:TOOL_DATA[1] Base[0]|0.300 (0.900) 4|
|“S<br>SLIN P23 Vel=2 m/s CPDAT32 Tool[1];TOOL_DATA[1] Base[0]|0276 (0.828) 6|
|“S SLIN P24 Vel=2 m/s CPDAT33 Tool[1]:TOOL_DATA[1] Base[0]|0.312 (0.936) 6|
|“S SLIN P25 Vel=2 m/s CPDAT35 Tool[1]:TOOL_DATA[1] Base[0]|0.324 (0.972) 6|
|“S SLIN P26 Vel=2 m/s CPDAT36Tool[1]:TOOL_DATA[1] Base[0]|0.312 (0.936) 6|
|“S SLIN P30 Vel=2 m/s CPDAT39Tool[1]:TOOL_DATA[1] Base[0]|0.348 (1.044) 6|
|“.SLINP6Vel=2m/sCPDAT44Tool[1]:TOOL_DATA[1]Base[0]|0312(0.936)6|



“. SLIN P6 Vel=2 m/s CPDAT44 Tool[1]:TOOL_DATA[1] Base[0] C7 rwulraceOn(FALSE) 

" SLIN P13 Vel=2 m/s CPDAT29 Tool[1]:TOOL_DATA[1] Base[0] 

|03486|
|---|





### **2.5 Results** 

#### **2.5.1 Observations** 

- The robot precisely traced the perimeter of the white sheet using its open gripper, demonstrating accurate basic movement. 

- The thorn was successfully grasped by the robot, enabling it to draw a clean rectangle on the paper as intended. 

- The complex figure, known as the “house of Santa Claus,” was drawn in a single, continuous motion of eight lines, without lifting the tool or intersecting lines. 

#### **2.5.2 Challenges and Solutions** 

- Achieving precise movement across different coordinate systems initially required trial and error as we familiarized ourselves with how each system influenced the robot’s behavior. Regular hands-on adjustments and testing helped us master this. 

### **2.6 Conclusion** 

This exercise demonstrated the ability to program and simulate the KUKA robot in KUKA.Sim to perform both basic and advanced drawing tasks. We successfully simulated the Robot in software and within KUKA.sim handled tools with precision, and carried out complex drawing operations. The integration of control structures and digital inputs enhanced the flexibility and accuracy of the program. The task highlighted the critical role of careful calibration, thoughtful planning, and structured programming in achieving reliable robotic performance. 

16 



## **Lab Test 3 Sorting Balls by Color using KUKA Robot** 

### **3.1 Introduction** 

In this set of tasks, we focused on simulating a common industrial application using a KUKA robot: sorting balls based on their color. The process consists of picking up balls from a feeder, detecting their color with a sensor, and placing them onto specific pallets according to their color. This experiment covers the simulation phase of the project, while the final implementation and code optimization will be addressed in next experiment. 

### **3.2 Objectives** 

The main goals of this experiment are as follows: 

- **Flow Chart Creation:** Design a comprehensive flow chart to outline the steps of the sorting process. 

- **Programming:** Build a robot control program based on the provided framework, incorporating the sorting logic and movement commands. 

- **Simulation and Testing:** Run simulations to test and fine-tune the program, ensuring both precision and efficiency. 

- **Implementation Readiness:** Prepare the finalized program for deployment on the physical robot for future testing. 

### **3.3 Methodology** 

#### **3.3.1 Flow Chart Preparation** 

A detailed flow chart was created to represent each stage of the ball sorting process. The diagram included key steps such as initializing the robot, verifying ball availability, picking up the balls, identifying their color, and placing them onto the correct pallets. 

17 



#### **3.3.2 Programming** 

1. The programming began by duplicating the provided template `rwuBallTeach` . The duplicated program was renamed (for example, `Gr6MoEx3 V1` ), with comments added to include the date, group number, and team members’ names. 

2. Initialization commands were added after the `rwuInitToolBase` subprogram, configuring `Tool[1]` with the specified parameters. The robot’s movements and actions were programmed according to the flow chart, using the provided position points. 

3. Both PTP and LIN movements were coded with care, ensuring proper gripper operation and integration of sensor readings. Conditional statements ( `IF` ) were used to handle ball presence and color detection, while `WHILE` loops enabled continuous sorting until set conditions were satisfied. The program ensured that the robot always started and returned to the HOME position at the beginning and end of the sequence. 

18 



### **3.4 Flowchart** 



<!-- Start of picture text -->
Start<br>Initialize:<br>Signals, Counters, Tool<br>Move to HOME<br>Open Gripper<br>Wait for Ball Signal<br>Ball present?<br>Redcount ≤ 9 or Yes Pick Ball Sequence:<br>Bluecount ≤ 9 or Move to Feeder →Down →Close<br>Greencount ≤ 9 ?<br>Move to Sensor Position<br>No<br>Move to HOME<br>HALT<br>Red Green<br>Set color=’r’ Detect Ball Color Set color=’g’<br>Blue<br>Programm End<br>Set color=’b’<br>Move to Palette Area<br>Red Check Color Green<br>Place Red Ball Place Green Ball<br>& Counter<br>Blue<br>Redcount = +1 Greencount = +1<br>Place Blue Ball<br>Bluecount = +1<br>Return to Palette Start<br><!-- End of picture text -->

Flowchart 3.1: Ball Sorting Program 

19 



<!-- Start of picture text -->
RW RAVENSBHOCHSCH U RG-WEINGARTENLE<br>aD U UNIVERSOF APPL ED I TY SCIENCES<br><!-- End of picture text -->



<!-- Start of picture text -->
Program editor +x<br>~) [E) rwuBallTeach_Group_2A &<br>Program<br>f Main<br>B® rwuBallleach<br> rwuBallTeach_Group_2A<br>NAS Ny © fv] for By Biv | By Ov licallita}<br>~ fo rwuBallTeach Group 2A( )<br>© :Anjun(28744163)<br> :Dhaval(206446015)<br>© sTarang(12543942)<br>[+] SIGNAL signalBall $IN[15] ;Feed has ball<br>[4] SIGNAL signalRed $IN[16] ;Ball is red<br>[+] SIGNAL signalGreen $IN[17] ;Ball is green<br>[4] SIGNAL signalBlue $IN[18] :Ball is blue<br>[x] DECL INT Redcount<br>[x] DECL CHAR colour<br>[x] DECL INT Bluecount<br>[x] DECL INT Greencount<br>X= colour="x"<br>X= Redcount=1<br>Xz Bluecount=1<br>X. Greencount=1<br>+ *z Default initialization<br><7 SPTP HOME Vel=100 % DEFAULT Tool[1]:TOOL_DATA[1] Base[0] 0.156 ©<br>7 rwulnitToolBase)<br>C3 rwuGripperClose(FALSE)<br>J> WAIT FOR signalBall == TRUE<br>— £1] WHILE (ignalBall==TRUE)and (Redcount<=9)and (Greencount<=9) and (Bluecount<=9)<br>2" SPTP P2_FeederUp Vel=100 % PDAT19 Tool[1}:TOOL_DATAI1] Base[1]: BASE_DATA(1] 0516 6<br>"\, SLIN P2_FeederDown Vel=2 m/s CPDAT12 Toolf12]:Greifer Base[1]: BASE_DATA[1] 0276 ©<br>3. rwuGripperClose(TRUE)<br>“\, SLIN P8 Vel=2 m/s CPDAT9 Toolf1]:TOOL_DATA[1] Base1]:BASE_DATA[1] 0276 6<br>“\, SLIN P9_FeederHigh Vel=2 m/s CPDAT13 Toolf1]:TOOL_DATA[1] Base[1}: BASE_DATA[1] 0276 ©<br>2" SPTP P10_OverSensor Vel=100 % PDAT16 Tool[1]:TOOL_DATA[1] Base[1]: BASE_DATA[1] 0432 6<br>“\, SLIN P11_DownSensor Vel=2 m/s CPDATS Tool[1]:TOOL_DATA[1] Base[1]: BASE_DATA[1] 0300 6<br>® WAIT SEC 1.0<br>— 1, IF signalRed==TRUE<br>— Then<br>| Gx. colour="*<br>— Else<br>LL cempty><br>~_], IF signalBlue==TRUE<br><!-- End of picture text -->



<!-- Start of picture text -->
Program editor * x<br>~) [E) rwuBallTeach_Group_2A o<br>Program<br>® Main<br>& rwuBallleach<br>B rwuBallTeach_Group2A<br>GSSfd 32 GSE fy | for By Ely | Br Or calito}<br>2" SPTP P10_OverSensor Vel=100 % PDAT16 Tool[1}:TOOL_DATA[1] Base[1]: BASE_DATA[1] 0432<br>“\, SLIN P11_DownSensor Vel=2 m/s CPDATS Tool[1}:TOOL_DATA[1] Base[1]: BASE_DATA[1] 0300 @<br>® WAIT SEC 1.0<br>~— 1, IF signalRed==TRUE<br>- Then<br>| Ux. colour=""<br>- Else<br>LL cempty><br>— 1, IF signalBlue==TRUE<br>- Then<br>| Cx. colour="b"<br>= Fas<br>LL cempty><br>— 1, IF signalGreen==TRUE<br>— Then<br>| Lxs colour="9*<br>— Else<br>L cempty><br>“\, SLIN P10_OverSensor Vel=2 m/s CPDAT7 Tool[1}:TOOL_DATA[1] Base[1]: BASE_DATA[1] 0300<br>2" SPTP P13_OverPalette Vel=100 % PDAT23 Tool[1]:TOOL_DATA[1] Base[1]: BASE_DATA[1] 0456 6<br>— 1 IF (colour=="r") and (Redcount<=9)<br>- Then<br>| 03 nwuPalette(Redcount, XP_OverRed)<br>- Else<br>L cempty><br>— 1, IF (colour=="b*) and (Bluecount<=9)<br>— Then<br>| 03 rwuPalette(Biuecount, XP_OverBiue)<br>— Else<br>LL cempty><br>— &, IF (colour=="g") and (Greencount <=9)<br>— Then<br>| ‘3 rwuPalette(Greencount, XP_OverGreen)<br>~ Else<br>L cempty><br>2" SPTP P13_OverPalette Vel=100 % PDAT24 Tool[1}:TOOL_DATA[1] Base[1}: BASE_DATA[1] 0636 @<br><!-- End of picture text -->



<!-- Start of picture text -->
Program Editor *+ x<br>~) © rwuFirstMove_3 Fe)<br>Program<br>B Main<br>[B rwuBallTeach<br>[| rwuFirstMove<br>niet tone 9<br>ANS Nie By | for By Ely | By6 Ho<br>— fay rwoFirstMove_3( )<br>+ *2 Default initialization<br><” SPTP HOME Vel=100 % DEFAULT Tool[1}:TOOL_DATA[1] Base[0] 0.156 ©<br>J~ WAIT FOR SIN[12]==true 15128<br>— 1, IF SIN[12}==true<br>— Then<br>“\, SLIN P1 Vel=2 m/s CPDAT21 Tool[12}:Greifer Base[0] 1.140 6<br>"\, SLIN P2 Vel=2 m/s CPDAT1 Tool[12]:Greifer Base[0] 0300 ©<br>(3 rwuGripperClose(TRUE)<br>“\, SLIN P3 Vel=2 m/s CPDAT22 Tool[12}:Greifer Base[0] 0288 6<br>27 SPTP P14 Vel=100 % PDATS Tool[1}:TOOL_DATA[1] Base[0] 0504 ©<br>— Else<br>L <empty><br>— {] WHILE $IN[12]==true<br>[{S. SLIN P9 Vel=2 m/s CPDAT46 Tool[13]:dorn Base[0] 0.156 (8076) 6<br>— £] WHILE SIN[13]==true<br>(23 rwuTraceOn(TRUE)<br>“, SLIN P27 Vel=2 m/s CPDATA0 Tool[13]:dom Base[0] 0.156 (0.936) 6<br>“\, SLIN P31 Vel=2 m/s CPDATA1 Tool[1]:TOOL_DATAI1] Base[0] 0.408 (2.448) ©<br>“\., SLIN P32 Vel=2 m/s CPDATA2 Tool[1}:TOOL_DATAI1] Base[0] 0.384 (230) 6<br>“\., SLIN P33 Vel=2 m/s CPDATA3 Tool[1]:TOOL_DATAI1] Base[0] 0.432 (2.592) 6<br>“\, SLIN P34 Vel=2 m/s CPDATA9 Tool[13}:dom Base[0] 0.348 (2.088) 6<br>(7 rwuTraceOn(FALSE)<br>— £] WHILE SIN[14]==true<br>2" SPTP P15 Vel=100 % PDAT9 Tool[1}:TOOL_DATA[1] Base{0] 0312 (0.948) 6<br>(2) rwuTraceOn(TRUE)<br>“\, SLIN P16 Vel=2 m/s CPDAT30 Tool{1]:TOOL_DATAI1] Base[0] 0.300 (0.900) 6<br>“\, SLIN P17 Vel=2 m/s CPDAT31 Tool[1]:TOOL_DATAI1] Base[0] 0.300 (0.900) 6<br>“\, SLIN P23 Vel=2 m/s CPDAT32 Toolf1]:TOOL_DATA[] Base[0] 0.276 (0.828) 6<br>“\, SLIN P24 Vel=2 m/s CPDAT33 Tool[1]:TOOL_DATAI1] Base[0] 0312 (0.936) 6<br>"\., SLIN P25 Vel=2 m/s CPDAT35 Tool[1]:TOOL_DATAI1] Base[0] 0324 (0.972) 6<br>“\, SLIN P26 Vel=2 m/s CPDAT36 Tool{1]:TOOL_DATAI1] Base[0] 0.312 (0.936) 6<br>“\., SLIN P30 Vel=2 m/s CPDAT39 Tool[1]:TOOL_DATAI1] Base[0] 0.348 (1.044)<br>"\, SLIN P6 Vel=2 m/s CPDAT44 Tool[1]:TOOL_DATA[1] Base[0] 0312 (0.936) 6<br>(2 rwuTraceOn(FALSE)<br>“\, SLIN P13 Vel=2 m/s CPDAT29 Tool[1}:TOOL_DATA[1] Base[0] 0348 6<br><!-- End of picture text -->



### **3.5 code** 

```
DEFrwuBallTeach_Group_2A()
;Arjun(28744163)
;Dhaval(206446015)
;Tarang(12543942)
SIGNALsignalBall$IN[15];Feedhasball
SIGNALsignalRed$IN[16];Ballisred
SIGNALsignalGreen$IN[17];Ballisgreen
SIGNALsignalBlue$IN[18];Ballisblue
DECLINTRedcount
DECLCHARcolour
DECLINTBluecount
DECLINTGreencount
colour="x"
Redcount=1
Bluecount=1
Greencount=1
;FOLDINI;%{PE}
;FOLDBASISTECHINI
GLOBALINTERRUPTDECL3WHEN$STOPMESS==TRUEDOIR_STOPM()
INTERRUPTON3
BAS(#INITMOV,0)
;ENDFOLD(BASISTECHINI)
;FOLDUSERINI
;Makeyourmodificationshere
;ENDFOLD(USERINI)
;ENDFOLD(INI)
SPTPHOME
rwuInitToolBase()
rwuGripperClose(FALSE)
WAITFORsignalBall==TRUE
WHILE(SignalBall==TRUE)and(Redcount<=9)and(Greencount<=9)and(Bluecount<=9)
SPTPXP2_FeederUp
SLINXP2_FeederDown
rwuGripperClose(TRUE)
SLINXP8
SLINXP9_FeederHigh
SPTPXP10_OverSensor
SLINXP11_DownSensor
WAITSEC1.0
IFsignalRed==TRUETHEN
colour="r"
ELSE
ENDIF
IFsignalBlue==TRUETHEN
colour="b"
ELSE
ENDIF
```

21 



```
IFsignalGreen==TRUETHEN
colour="g"
ELSE
ENDIF
SLINXP10_OverSensor
SPTPXP13_OverPalette
```

```
IF(colour=="r")and(Redcount<=9)THEN
rwuPalette(Redcount,XP_OverRed)
ELSE
ENDIF
IF(colour=="b")and(Bluecount<=9)THEN
rwuPalette(Bluecount,XP_OverBlue)
ELSE
ENDIF
IF(colour=="g")and(Greencount<=9)THEN
rwuPalette(Greencount,XP_OverGreen)
ELSE
ENDIF
SPTPXP13_OverPalette
ENDWHILE
;FOLDSPTPHOME
SPTPXHOME
HALT
HALT
HALT
```

### **3.6 Testing** 

For testing, We started by running simulation to check how well the program worked and to observe how the robot moved through the sorting process. As we tested, we made small adjustments to the code wherever improvements were needed to ensure smoother and more efficient operation. Once we were satisfied with the performance, we exported the `.src` and `.dat` files so they would be ready for use in the next task, where the program will be implemented on the actual robot. 

22 



### **3.7 Extended version** 

- In the previous version, the robot returned to the home position as soon as **any one pallet became full** , interrupting the sorting process. 

- In the updated version, we allow the robot to continue operating even if one pallet is full. 

- When a pallet became full, the robot: 

   - **Does not stop** , but instead checks the color of the next incoming ball. 

   - If the detected ball’s color corresponds to a **non-full pallet** , the robot proceeds with **normal placement** . 

   - If the ball’s color matches the **full pallet** , the robot **discards the ball** by moving to the home position and opening the gripper. 

- This updated strategy ensures that the robot continues sorting until **all three pallets are full** , reducing unnecessary halts and improving overall **system efficiency** . 

23 



### **3.8 Flowchart for Ball Sorting Program** 



<!-- Start of picture text -->
Start Program<br>Initialize Variables:<br>TotalRGB=0<br>colour=”x”<br>Redcount=1<br>Bluecount=1<br>Greencount=1<br>Move to XHOME<br>Open Gripper<br>Ball Present?<br>No Move to HOME<br>AND End Program<br>HALT<br>TotalRGB ≤ 29?<br>Yes<br>Pick Ball Sequence:<br>Move to Feeder<br>Down →Close →Up<br>Move to Sensor<br>Position<br>Wait 1 Second<br>signalRed No signalBlue No signalGreen No<br>== TRUE? == TRUE? == TRUE?<br>Yes Yes Yes<br>Set colour=”r” Set colour=”b” Set colour=”g”<br>colour==”r”AND No colour==”b”AND No colour==”g”AND No<br>Redcount ≤ 9? Bluecount ≤ 9? Greencount ≤ 9?<br>Yes Yes Yes<br>Place Red Ball MoveOpentoGripperHOME Place Blue Ball MoveOpentoGripperHOME Place Green Ball MoveOpentoGripperHOME<br>Redcount=+1 Bluecount=+1 Greencount=+1<br>TotalRGB=+1 TotalRGB=+1 TotalRGB=+1<br>End of Loop<br><!-- End of picture text -->

Flowchart 3.2: Extended version of Ball Sorting Program 

24 



<!-- Start of picture text -->
RW RAVENSBHOCHSCH U RG-WEINGARTENLE<br>aD U UNIVERSOF APPL ED I TY SCIENCES<br><!-- End of picture text -->



<!-- Start of picture text -->
— fi rwuBallTeach<br>( ;Arjun(28744163)Group 2A( )<br>I :Dhaval(206446015)<br>© ;Tarang(12543942)<br>[4] SIGNAL signalBall $1N[12] ;Feed has ball<br>[+] SIGNAL signalRed $IN[9] ;Ball is red<br>[+] SIGNAL signalGreen $IN[10] ;Ball is green<br>[+] SIGNAL signalBlue $IN[11] :Ball is blue<br>[*] DECL INT Redcount<br>[x] DECL CHAR colour<br>[*] DECL INT Bluecount<br>[*] DECL INT Greencount<br>[] DECL INT TotalRGB<br>*=xs TotalRGB=0colour="x"<br>x Redcount=1<br>*= Bluecount=1<br>* Greencount=1<br>+ * Default initialization<br>-” SPTP HOME Vel=100 % DEFAULT Tool[1]:TOOL_DATA[1] Base[0]<br>C7 rwulnitToolBase()<br>(C3 rwuGripperClose(FALSE)<br>J WAIT FOR signalBall == TRUE<br>— ¢] WHILE (signalBall==TRUE) and (TotalIRGB<=29)<br>-” SPTP P2_FeederUp Vel=100 % PDAT19 Tool[1}:TOOL_DATA[1] Base[1]: BASE...<br>“| SLIN P2_FeederDown Vel=2 m/s CPDAT12 Tool[12]:Greifer Base[1]: BASE_D...<br>(2) rwuGripperClose(TRUE)<br>“\, SLIN P8 Vel=2 m/s CPDAT9 Tool[1]:TOOL_DATA[1] Base[1]: BASE_DATA[1]<br>~~" SPTP P10_OverSensor Vel=100 % PDAT16 Tooll11:TOOL DATAI1] Basel 11: B...<br>“\ SLIN P11_DownSensor\ SLIN P9_FeederHigh Vel=2 m/s CPDAT13 Tool |; B...<br>§@ WAIT SEC 1.0 [1]:TOOL_DATA[1] Base[1]: BASE_DATA[1]<br>- IF signalRed==TRUE<br>— Then<br>X= colour="""<br>“ss, SLIN P10_OverSensor Vel=2 m/s CPDAT15 Tool[1]:TOOL_DATA[1] Ba...<br><!-- End of picture text -->



<!-- Start of picture text -->
| J*) WAITrwuGripperClose(FALSE) FOR signalBall == TRUE<br>— ¢] WHILE (signalBall==TRUE) and (TotalRGB<=29)<br>-” SPTP P2_FeederUp Vel=100 % PDAT19 Tool[1]:TOOL_DATA[1] Base[1]: BASE...<br>“\ SLIN P2_FeederDown Vel=2 m/s CPDAT12 Tooll12]:Greifer Base[1]: BASE_D...<br>a rwuGripperClose(TRUE)<br>. SLIN P8 Vel=2 m/s CPDAT9 Tool[1]:TOOL_DATA[1] Base[1]: BASE_DATA[1]<br>“, SLIN P9_FeederHigh Vel=2 m/s CPDAT13 Tool[1]:TOOL_DATA[1] Base[1]: BA...<br>2” SPTP P10_OverSensor Vel=100 % PDAT16 Tool[1}:TOOL_DATA[1] Base[1]: B...<br>. SLIN P11_DownSensor Vel=2 m/s CPDAT6 Tool[1]:TOOL_DATA[1] Base[1]: B...<br>8 WAIT SEC 1.0<br>— &, IF signalRed==TRUE<br>— Then<br>| “|X= colour="r"SLIN P10_OverSensor Vel=2 m/s CPDAT15 Tool[1}:TOOL_DATA[1] Ba...<br>— , IF (colour=="r") and (Redcount<=9)<br>— Then< ; SPTP P13_OverPalette Vel=100 % PDAT25 Tool[1]}:TOOL_DAT...<br>C3 rwuPalette(Redcount, XP_OverRed)<br>-” SPTP P13_OverPalette Vel=100 % PDAT35 Tooll1}:TOOL_DAT...<br>X= TotalRGB=Redcount+Bluecount+Greencount<br>— Else<br>- SPTP HOME Vel=100 % PDAT27 Toolf1]:TOOL_DATA[1] Base...<br>"9 rwuGripperClose(FALSE)<br>~ Else<br><empty><br>— &, IF signalBlue==TRUE<br>~ Then<br>™s, SLIN P10_OverSensor Vel=2 m/s CPDAT18 Tool[1}:TOOL_DATA[1] Ba...<br>— &, IF (colour=="b*) and (Bluecount<=9)<br>— Then<br>< SPTP P13_OverPalette Vel=100 % PDAT29 Tool[1]:TOOL_DAT...<br>C2 rwuPalette(Bluecount, XP_OverBlue)<br>| 2” SPTP P13_OverPalette Vel=100 % PDAT36 Tool|[1]:TOOL_DAT...<br>X= TotalRGB=Redcount+Bluecount+Greencount<br><!-- End of picture text -->



<!-- Start of picture text -->
| — E l se <empty><br>— &, IF signalBlue==TRUE<br>— Then<br>| "\..X= SLINcolour="b"P10_OverSensor Vel=2 m/s CPDAT18 Tool[1}:TOOL_DATA[1] Ba...<br>- br (colour=="b") and (Bluecount<=9)<br>— Then<br>-” SPTP P13_OverPalette Vel=100 % PDAT29 Tool[1]:TOOL_DAT...<br>(2 rwuPalette(Bluecount, XP_OverBlue)<br>-” SPTP P13_OverPalette Vel=100 % PDAT36 Tool[1]:TOOL_DAT...<br>*= TotalRGB=Redcount+Bluecount+Greencount<br>— Else<br>-” SPTP HOME Vel=100 % PDAT31 Tooll[1]:TOOL_DATA[1] Base...<br>*] rwuGripperClose(FALSE)<br>— Else<br>L <empty><br>— , IF signalGreen==TRUE<br>— Then<br>| “S,X= SLINcolour="g"P10_OverSensor Vel=2 m/s CPDAT7 Tool[1]:TOOL_DATA[1] Bas...<br>— &, IF (colour=="g" ) and (Greencount <=9)<br>— Then<br>2 SPTP P13_OverPalette Vel=100 % PDAT23 Tool[1]:TOOL_DAT...<br>*] rwuPalette(Greencount, XP_OverGreen)<br>- SPTP P13_OverPalette Vel=100 % PDAT37 Tool[1]:TOOL_DAT...<br>*= TotalRGB=Redcount+Bluecount+Greencount<br>— Else<br>-* SPTP HOME Vel=100 % PDAT33 Toolf1}:TOOL_DATA[1] Base...<br>(2? rwuGripperClose(FALSE)<br>— Else<br>l <empty><br>2” SPTP HOME Vel=100 % PDAT20 Tooll1}:TOOL_DATA[1] Base[0]<br>© HALT<br>© HALT<br><!-- End of picture text -->



### **3.9 Code** 

```
DEFrwuBallTeach_Group_2A()
;Arjun(28744163)
;Dhaval(206446015)
;Tarang(12543942)
SIGNALsignalBall$IN[15];Feedhasball
SIGNALsignalRed$IN[16];Ballisred
SIGNALsignalGreen$IN[17];Ballisgreen
SIGNALsignalBlue$IN[18];Ballisblue
DECLINTRedcount
DECLCHARcolour
DECLINTBluecount
DECLINTGreencount
DECLINTTotalRGB
TotalRGB=0
colour="x"
Redcount=1
Bluecount=1
Greencount=1
;FOLDINI;%{PE}
;FOLDBASISTECHINI
GLOBALINTERRUPTDECL3WHEN$STOPMESS==TRUEDOIR_STOPM()
INTERRUPTON3
BAS(#INITMOV,0)
;ENDFOLD(BASISTECHINI)
;FOLDUSERINI
;Makeyourmodificationshere
;ENDFOLD(USERINI)
;ENDFOLD(INI)
SPTPXHOME
rwuInitToolBase()
rwuGripperClose(FALSE)
WAITFORsignalBall==TRUE
WHILE(signalBall==TRUE)AND(TotalRGB<=29)
SPTPXP2_FeederUp
SLINXP2_FeederDown
rwuGripperClose(TRUE)
SLINXP2_FeederUp
SLINXP9_FeederHigh
SPTPXP10_OverSensor
SLINXP11_DownSensor
WAITSEC1.0
IF(signalRed==TRUE)THEN
colour="r"
SLINXP10_OverSensor
IF(colour=="r")AND(Redcount<=9)THEN
SPTPXP13_OverPalette
rwuPalette(Redcount,XP_OverRed)
```

26 



```
SPTPXP13_OverPalette
TotalRGB=Redcount+Bluecount+Greencount
ELSE
SPTPXHOME
rwuGripperClose(FALSE)
ENDIF
ELSE
ENDIF
IFsignalBlue==TRUETHEN
colour="b"
SLINXP10_OverSensor
IF(colour=="b")AND(Bluecount<=9)THEN
SPTPXP13_OverPalette
rwuPalette(Bluecount,XP_OverBlue)
SPTPXP13_OverPalette
TotalRGB=Redcount+Bluecount+Greencount
ELSE
SPTPXHOME
rwuGripperClose(FALSE)
ENDIF
ELSE
ENDIF
IFsignalGreen==TRUETHEN
colour="g"
SLINXP10_OverSensor
IF(colour=="g")AND(Greencount<=9)THEN
SPTPXP13_OverPalette
rwuPalette(Greencount,XP_OverGreen)
SPTPXP13_OverPalette
TotalRGB=Redcount+Bluecount+Greencount
ELSE
SPTPXHOME
rwuGripperClose(FALSE)
ENDIF
ELSE
ENDIF
ENDWHILE
SPTPXHOME
HALT
HALT
HALT
```

27 



### **3.10 Testing of extended version** 

For testing, we initially ran simulations to evaluate the correctness and performance of the updated sorting logic. The goal was to verify whether the robot could correctly detect ball colors, track individual pallet counts, and handle full pallet conditions as intended. During simulation, we carefully observed the robot’s movements and decision-making at each stage of the process. 

Throughout testing, we identified and refined specific parts of the code to enhance the robot’s behavior—particularly in handling cases where one or more pallets were full. These iterative improvements helped ensure the robot continued sorting efficiently without unnecessary interruptions. After confirming the program’s stability and accuracy in the simulated environment, we exported the final version of the `.src` and `.dat` files. These files are now ready for deployment in the next phase, where the program will be transferred to the physical robot for real-world implementation. 

### **3.11 Results** 

#### **3.11.1 Observations** 

- A detailed flowchart outlining the complete ball sorting logic was successfully designed and approved. 

- The program was developed and implemented according to the provided framework and predefined coordinates. 

- Simulations confirmed that the robot accurately sorted balls by color with smooth and coordinated movements. 

- Logical improvements, such as handling full pallets more efficiently, were integrated and tested successfully. 

### **3.12 Conclusion** 

This task demonstrated the successful development and simulation of a ball-sorting program for a KUKA robot. The process began with designing a flowchart to visualize the control logic, followed by structured implementation and iterative improvements during simulation testing. Key functionalities, including accurate color detection, pallet tracking, and handling of full pallet conditions, were validated in a controlled virtual environment. The refined logic not only improved operational efficiency but also ensured continuous processing until all pallets reached their limits. Overall, the results of this simulation provide a strong foundation for deploying the program on the physical robot in the next phase of the project. 

28 



## **Lab Test 4 Implementation of Ball Sorting Program on Robot** 

### **4.1 Introduction** 

In this phase, we moved from simulation to practical implementation by deploying the ballsorting program on an actual KUKA robot. This section covers the final testing stages, including position verification and validation of the robot’s performance to ensure precise and smooth sorting operations at progressively higher speeds. 

### **4.2 Objectives** 

- Prepare and adapt the program which was developed during the simulation phase for real-robot use. 

- Verifying robot points to ensure precise and accurate movements. 

- Conducting incremental testing starting at low speed and gradually increasing to normal operational speed. 

- Validate all program functions and obtain final approval from the lab supervisor. 

### **4.3 Methodology** 

#### **4.3.1 Programming** 

- First, we copied the provided program template, `rwuBallTeach` , and renamed it, adding the current date, group number, and member names as comments. We then inserted the program after the `rwuInitToolBase` subroutine. 

- Next, we implemented the movements and actions according to the flowchart, ensuring that both PTP and LIN motions were correctly programmed using the provided points. 

- Additionally, we incorporated key functions such as `rwuGripperClose` for gripping and `rwuPalette` for palletizing. We also used IF statements to verify ball availability and detect colors accurately. 

29 



- Finally, we employed WHILE loops to continuously sort balls until the feeder was empty or all pallets were full. Throughout the process, we ensured the program started and ended with the robot positioned at HOME for safety and consistency. 

#### **4.3.2 Validation** 

- We presented the finalized program to the lab supervisor for evaluation and approval. 

- After approval, we exported the `.src` and `.dat` files to prepare for real-robot implementation. 

- We saved the source files for documentation purposes and future reference. 

### **4.4 Real-Robot Implementation** 

#### **4.4.1 Preparing the Code** 

##### 1. **Loading the Program:** 

- We have successfully transferred the program files ( `*.src` and `*.dat` ) from the simulation environment to the PC. 

- Afterwards, We have configured the digital inputs as follows: 

|**Signal**|**Digital Input (DI)**|
|---|---|
|Red ball|9|
|Green ball|10|
|Blue ball|11|
|Ball availability signal|12|



Table 4.1: Digital Input Configuration for Ball Detection 

- Lastly, We provided the program to the lab supervisor to load onto the robot. 

#### **4.4.2 Testing and Adapting the Code** 

##### 1. **Initial Setup:** 

- First, We confirmed the robot was positioned at HOME before starting. 

- then, We thoroughly checked and verified all connections and sensor configurations. 

##### 2. **Points Verification:** 

- In this, We moved the robot sequentially through all taught points using specific commands such as `PTP HOME` . 

30 



- The robot began testing from the HOME position. 

##### 3. **Incremental Speed Testing:** 

- We started the program testing at low speed and gradually increased it. 

- Then, We closely monitored the robot’s movements to maintain safe operation. 

- afterwards, We verified the proper functioning of the gripper, sensors, and program termination conditions. 

##### 4. **Final Validation:** 

- We presented the fully tested and validated program to the lab supervisor for approval. 



Figure 4.1: Peaking up the ball 



Figure 4.2: Color detection on the sensor 

31 

RW RAVENSBHocHSCH **U** RG-WEINGARTENLE aD U OFUNIVERS APPL ED **I** TY SCIENCES 



<!-- Start of picture text -->
iF<br>H<br>ay<br><!-- End of picture text -->



<!-- Start of picture text -->
; i<br>fa<br>,<br>|<br>Ge f<br>, a, a i<br><!-- End of picture text -->



<!-- Start of picture text -->
| |<br>es<br><!-- End of picture text -->



<!-- Start of picture text -->
| \a —<br>e \ a<br>| 00<br>* y e008<br>. AS 7 +4 tl tl RD:<br>a <=<br><!-- End of picture text -->



Figure 4.7: Program in Controller 

33 



Figure 4.8: Program in Controller (cont.) 

34 



### **4.5 Results** 

#### **4.5.1 Observations** 

- We successfully verified and fine-tuned all the taught points to ensure accuracy. 

- The program ran smoothly at low speeds and maintained reliable performance as the speed increased. 

- All components, including the gripper and sensors, functioned properly throughout the tests. 

- The robot was successfully initialized and positioned at HOME. 

- It accurately detected and picked up balls from the feeder. 

- The ball colors were correctly identified and recorded. 

- Balls were placed onto their respective pallets according to color. 

- Upon task completion or when pallets reached full capacity, the robot returned to the HOME position. 

### **4.6 Conclusion** 

This task effectively showcased the transition from simulation to actual robot deployment for the ball sorting operation. Careful validation of taught positions combined with gradual speed testing guaranteed precise and safe robot movements. The successful execution of this phase lays a strong foundation for further program enhancements and optimization geared toward industrial use. 

35 

