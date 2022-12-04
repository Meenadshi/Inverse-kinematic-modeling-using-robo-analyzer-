# Inverse-kinematic-modeling-using-robo-analyzer-

 
## AIM: 
To analyze the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer and polt the graph of joint angle for a given  input end effector position .


### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
### Inverse Kinematics
 

Inverse kinematics is the use of kinematic equations to determine the motion of a robot to reach a desired position. For example, to perform automated bin picking, a robotic arm used in a manufacturing line needs precise motion from an initial position to a desired position between bins and manufacturing machines. The grasping end of a robot arm is designated as the end-effector. The robot configuration is a list of joint positions that are within the position limits of the robot model and do not violate any constraints the robot has.

 Most industrial robots are constructed of several independently controllable articulated joints. Each joint is connected to one or more of the other joints, sometimes in complex configurations. The end effector is attached at the end of the entire “kinematic chain”. When you move any one joint, this will affect the end effector’s pose in various ways.

This means that there is no simple, direct relationship between the end effector position and any one particular joint.

For example, if you want the robot’s end effector to move 1 mm linearly along the Z-axis, you may need to move all of the joints by a different amount.

Finally, inverse kinematics algorithms calculate the exact position of each of the robot’s joints required to reach your desired end effector pose.

### solving inverse kinematic model 
![image](https://user-images.githubusercontent.com/36288975/170622829-3fe97ef7-8ef1-44af-afae-b0954871aa0c.png)


![image](https://user-images.githubusercontent.com/36288975/170622902-f48fd9c7-f2ec-4fd5-904b-ea51be8298c3.png)

![image](https://user-images.githubusercontent.com/36288975/170622934-a3fd7f77-7eb2-4408-b66d-d6e3adbd1f99.png)

![image](https://user-images.githubusercontent.com/36288975/170622982-9c4d8b23-1563-4e17-9616-87bcc4f4501d.png)
![image](https://user-images.githubusercontent.com/36288975/170623020-f27efc12-bb58-4f62-840d-af544ac6689e.png)

### PROCEDURE:

open the roboanalyzer software.
select the robot and its degrees of freedom.
change the values of X and Y wherever necessary.
simulate the model for inverse kinematics.
plot the graph between the joints.
update the DH parameters of the link configuration and end effector configuration.

### SIMULATION 
 
 ![170623671-ceac517c-d739-4f6d-9bbd-d655d8324e1d](https://user-images.githubusercontent.com/88670187/205495780-cb3e6a74-8cdf-4f17-9c90-6f592da99ee6.jpg)

 ![170623767-70f827a9-8de9-422e-9003-510f57f3e635](https://user-images.githubusercontent.com/88670187/205495786-65606893-36fe-42eb-87bd-a0772fadee1d.jpg)
![170623818-7cb4dee3-917f-4366-96ed-a9dbcd9865f8](https://user-images.githubusercontent.com/88670187/205495790-b07e3f0b-beac-47af-b73c-860d8ed3a740.png)

 ![170623849-7cb26533-3d12-4ebb-9faa-c8a1b162b0cf](https://user-images.githubusercontent.com/88670187/205495795-8ef4e7e5-831d-4924-bed7-e81d83fc00b2.png)


 ### PLOT  
 
 ![170624053-ab1f4eb0-5579-451e-bd19-dacd4c098629](https://user-images.githubusercontent.com/88670187/205495800-980b77a8-0dc3-4fb0-91a0-a9099a4f22b2.png) 
 ![170624071-a8a118f1-3032-40f4-9014-2faf3055d9ee](https://user-images.githubusercontent.com/88670187/205495807-aab2d5a6-0b11-49a7-9d0b-2ffe174213e3.jpg)

 ![170624191-a7f570a4-91de-4b50-b5ce-70e6441efae6](https://user-images.githubusercontent.com/88![170624205-059291ef-9ff5-4610-af0e-c1cc99181782](https://user-images.githubusercontent.com/88670187/205495815-0538689a-2496-491c-827f-62ab7ceaa039.jpg)
670187/205495814-bc88f22e-918c-43a5-8e43-833c73867aa4.png)


### RESULTS :  
Thus,the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer is analysed and the graph of joint angle for a given input end effector position is plotted.
