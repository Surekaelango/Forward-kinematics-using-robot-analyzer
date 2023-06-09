# Forward-kinematics-using-robo-analyzer

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
STEP 1:
Open the roboanalyzer software.

STEP 2:
Select the robot and its degrees of freedom.

STEP 3:
Change the values with the link lenght wherever necessary.

STEP 4:
Simulate the model for forward kinematics.

STEP 5:
Plot the graph between the link and the joints.

STEP 6:
Update the DH parameters of the link configuration and end effector configuration.





### DH PARAMETERS
## 6 DOF
![image](https://github.com/Surekaelango/Forward-kinematics-using-robot-analyzer/assets/127727904/5d709332-d5d5-44fc-b925-a066e278546e)
## 4 DOF
![image](https://github.com/Surekaelango/Forward-kinematics-using-robot-analyzer/assets/127727904/0270b55d-f083-4a85-a938-f54370b29c71)

## SIMULATION:
## 6 DOF:
![image](https://github.com/Surekaelango/Forward-kinematics-using-robot-analyzer/assets/127727904/701af5f3-f2e1-4a9b-80a0-30bbb4a51652)
## 4 DOF:
![image](https://github.com/Surekaelango/Forward-kinematics-using-robot-analyzer/assets/127727904/0b6f761f-2102-4d60-9ef1-0e051862e68b)

## PLOT :
## 6 DOF:
![image](https://github.com/Surekaelango/Forward-kinematics-using-robot-analyzer/assets/127727904/9a61793a-f19e-490f-98dc-f78e55d29654)
## 4 DOF:
![image](https://github.com/Surekaelango/Forward-kinematics-using-robot-analyzer/assets/127727904/836e7bd6-8650-4a6a-89a0-5da597ca0fc5)
## EE CONFIGURATION:
## 6 DOF:
![image](https://github.com/Surekaelango/Forward-kinematics-using-robot-analyzer/assets/127727904/5630e1c7-d510-402c-9822-b6ac3b9e44da)
## 4 DOF:
![image](https://github.com/Surekaelango/Forward-kinematics-using-robot-analyzer/assets/127727904/fdec2361-0ef2-4ac4-877f-fcbe807ae914)

### RESULTS : 
The forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer has been analyzed and the graph for link cordinates and joint angles has been ploted.
