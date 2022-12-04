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
 ![170623671-ceac517c-d739-4f6d-9bbd-d655d8324e1d](https://user-images.githubusercontent.com/88670187/205495657-ca625e88-cd01-49c0-aed2-dc27736c9ed1.jpg)

 ![170623767-70f827a9-8de9-422e-9003-510f57f3e635](https://user-images.githubusercontent.com/88670187/205495663-890be768-2e5b-46a6-81b3-59256c3149d7.jpg)
![170623818-7cb4dee3-917f-4366-96ed-a9dbcd9865f8](https://user-images.githubusercontent.com/88670187/205495666-07c27161-ea05-498e-b1cc-50fec286adab.png)
 ![170623849-7cb26533-3d12-4ebb-9faa-c8a1b162b0cf](https://user-images.githubusercontent.com/88670187/205495669-2dc72277-bca5-42d3-8ede-77dfb3bac88e.png)

 
 ### PLOT 
 
 ![170624053-ab1f4eb0-5579-451e-bd19-dacd4c098629](https://user-images.githubusercontent.com/88670187/205495674-3d80d6c2-ed53-4ffb-a534-afb57ad3f23d.png)
 ![170624071-a8a118f1-3032-40f4-9014-2faf3055d9ee](https://user-images.githubusercontent.com/88670187/205495677-649e31c8-58d3-47d2-9eb3-5d5cc8b63cc1.jpg)
 ![170624191-a7f570a4-91de-4b50-b5ce-70e6441efae6](https://user-images.githubusercontent.com/88670187/205495683-ef3537ea-5960-43e4-98aa-a26b4b83259b.png)
![170624205-059291ef-9ff5-4610-af0e-c1cc99181782](https://user-images.githubusercontent.com/88670187/205495686-62a03a37-1d0a-4a51-a0d6-32b0314334a5.jpg)


### RESULTS :  
Thus,the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer is analysed and the graph of joint angle for a given input end effector position is plotted.
