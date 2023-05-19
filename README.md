# EXP-2-Forward-kinematics-using-robo-analyzer

## AIM: 
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles
### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
Forward Kinematics

A manipulator is composed of serial links which are affixed to each other revolute or prismatic joints from the base frame through the endeffector. 
Calculating the position and orientation of the endeffector in terms of the joint variables is called as forward kinematics. 
In order to have forward kinematics for a robot mechanism in a systematic manner, one should use a suitable kinematics model. 
Denavit-Hartenberg method that uses four parameters is the most common method for describing the robot kinematics. 
These parameters ai1, α −,1idi and θ the link length, link twist, link offset and joint angle, respectively. 
A coordinate frame is attached to each joint to determine DH parameters. Zi axis of the coordinate frame is pointing along the rotary or sliding direction general manipulator.

Denavit Hartenberg Parameters
With DH Parameters, solving for the Forward Kinematics is easy.  only need to take four parameters for each joint 
i: θifor the joint angle, 
αi for the link twist, 
difor the link offset, and 
ai for the link length. Once I’ve obtained them, I can just plug them in to this transformation matrix:


![image](https://user-images.githubusercontent.com/36288975/170172719-ed7befc9-2894-4344-bfd5-be831bb05308.png)

 ![image](https://user-images.githubusercontent.com/36288975/170172766-b8aeb788-7fd7-4de7-b340-f04656707ebd.png)

 

### PROCEDURE:
PROCEDURE:
1.open the roboanalyzer software.
2.select the robot and its degrees of freedom.
3.change the values with the link lenght wherever necessary.
4.simulate the model for forward kinematics.
5.plot the graph between the link and the joints.
6.update the DH parameters of the link configuration and end effector configuration.




### SIMULATION 
 
 ## 6DOF: 
 ![6DOF1](https://github.com/hemanth2110/Forward-kinematics-using-robot-analyzer/assets/121078629/c1465e7a-60c3-48cb-8537-b6b605122dfc)
## 4DOF: 
![4DOF1](https://github.com/hemanth2110/Forward-kinematics-using-robot-analyzer/assets/121078629/4d9c7b6c-a56b-4b0b-9f42-644fc729e95a)

 
 
 
 
 ### PLOT 
 ## 6 DOF :
 ![6DOF2](https://github.com/hemanth2110/Forward-kinematics-using-robot-analyzer/assets/121078629/a57f9bbb-c468-49f9-843d-cdb467027908)

## 4 DOF :
![4DOF2](https://github.com/hemanth2110/Forward-kinematics-using-robot-analyzer/assets/121078629/7cf44f68-e680-49f3-a7b0-edca33adac40)

![4DOF3](https://github.com/hemanth2110/Forward-kinematics-using-robot-analyzer/assets/121078629/ee8ccfa1-9236-4fe5-91c0-71495529de26)
   
 
 
 
 
 
 
 
 
 
 
 

 
 














### RESULTS :  
Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted.
