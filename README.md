# Designing and Modelling of a Three Degrees Of Freedom Planar Parallel Manipulator
This project involves designing and modelling of a three degree of freedom planar parallel manipulator
#### Aim 
To design a three degrees of freedom planar parallel manipulator with a cylindrical regular workspace of diameter equal to 100 mm, its height corresponding to the range of rotation of the moving-platform.
## Mechanism and Architecture
For a planar parallel manipulator all the component and motions, including the end effectors generate planar motions. There a several mechanisms for 3DOF PPMs like 3-RRR, 3-RPR, 3-PRR and 3-PPP. For the 3DOF PPM, we have chosen to be 3-RRR where 3 denotes three limbs of the manipulator and R stands for revolute joints. The schematics of the mechanism is shown in Figure 1. As seem in the figure each limb is comprised of three revolute joints out of which the first joint of each limb is actuated. The axis of rotation of all the joints are parallel to each other and are all on the same plane. The workspace of the manipulator is a cylinder with diameter equal to 100 mm.

<img width="467" alt="Capture" src="https://user-images.githubusercontent.com/47361086/126361873-fef3ded1-b7cc-40c0-a313-b598a4ef02e4.PNG">

Figure above illustrates a 3DOF RRR Planar Parallel Manipulator with a cylindrical workspace. Each kinematic chain is RRR type, which has three revolute joints out of which the first one in each limb is the actuating joint. The intention of the manipulator is to move, position and orient the triangle C1C2C3. P denotes the geometric center of the moving platform. The angle α1, α 2 and α 3 are the angles made by the actuating joints. O denotes the center of the base triangle A1A2A3 and it is the origin of the reference frame.

<img width="427" alt="model" src="https://user-images.githubusercontent.com/47361086/126362911-4d120adf-fc11-49be-b74c-394ae35165cf.PNG">
The described mechanism was modelled as a 3-RRR parallel planar manipulator in CATIA as shown in the figure above.The manipulator is modelled in x-y plane. As depicted the manipulator has a cylindrical workspace of base diameter equal to 100mm.The constraints are followed throughout the workspace.
## Installation and Running Procedure
Clone this github repository and open the parts in CATIA

```
git clone https://github.com/NithaElizabeth/3DOFParallelManipulatorModelling
```
## Author
The system was developed by Nitha Elizabeth John and Raghuveer under the guidance of Prof.Stephane Caro. \
Author  : Nitha Elizabeth John \
Contact : nithaelizabethjohn@gmail.com
