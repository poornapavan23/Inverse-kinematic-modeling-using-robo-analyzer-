### Ex-04 Inverse-kinematic-modeling-using-robo-analyzer-

### AIM:
To analyze the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer and polt the graph of joint angle for a given input end effector position .

### COMPONENTS REQUIRED:
1.Robo analyzer software

### THEORY:
Inverse Kinematics
Inverse kinematics is the use of kinematic equations to determine the motion of a robot to reach a desired position. For example, to perform automated bin picking, a robotic arm used in a manufacturing line needs precise motion from an initial position to a desired position between bins and manufacturing machines. The grasping end of a robot arm is designated as the end-effector. The robot configuration is a list of joint positions that are within the position limits of the robot model and do not violate any constraints the robot has.

Most industrial robots are constructed of several independently controllable articulated joints. Each joint is connected to one or more of the other joints, sometimes in complex configurations. The end effector is attached at the end of the entire “kinematic chain”. When you move any one joint, this will affect the end effector’s pose in various ways.

This means that there is no simple, direct relationship between the end effector position and any one particular joint.

For example, if you want the robot’s end effector to move 1 mm linearly along the Z-axis, you may need to move all of the joints by a different amount.

Finally, inverse kinematics algorithms calculate the exact position of each of the robot’s joints required to reach your desired end effector pose.

### solving inverse kinematic model

![image](https://user-images.githubusercontent.com/115688029/199712444-2f0efb17-7979-4ce9-b8df-72dd76f322d0.png)

![image](https://user-images.githubusercontent.com/115688029/199712608-0df86483-06f8-437e-86bb-2c11345a731f.png)
![image](https://user-images.githubusercontent.com/115688029/199712809-3f58faf5-3a53-4ad8-9dde-ba4b7c2ab029.png)
![image](https://user-images.githubusercontent.com/115688029/199713006-4c38c467-ffde-4780-a00f-b461b1b1cdad.png)






### PROCEDURE:
1.open the roboanalyzer software.

2.select the robot and its degrees of freedom.

3.change the values of X and Y wherever necessary.

4.simulate the model for inverse kinematics.

5.plot the graph between the joints.

6.update the DH parameters of the link configuration and end effector configuration.

### SIMULATION
![image](https://user-images.githubusercontent.com/115688029/199713422-4c790675-3c64-404d-805a-ff8d79cc0ef0.png)
![image](https://user-images.githubusercontent.com/115688029/199713562-0134405d-4173-47a4-8a47-36a6e717ce28.png)
### RESULTS :
Thus,the inverse kinematics using DH parameters for a 3 dof planer robot using roboanalyzer is analysed and the graph of joint angle for a given input end effector position is plotted.
