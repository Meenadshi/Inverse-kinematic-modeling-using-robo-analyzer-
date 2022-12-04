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
 ![170623671-ceac517c-d739-4f6d-9bbd-d655d8324e1d](https://user-images.githubusercontent.com/88670187/205495378-847b55da-e123-44ee-91e9-a2f6122e0f2a.jpg)
 ![170623767-70f827a9-8de9-422e-9003-510f57f3e635](https://user-images.githubusercontent.com/88670187/205495381-f0b9d4bc-40fd-4530-9171-11bb787961db.jpg)
 ![170623818-7cb4dee3-917f-4366-96ed-a9dbcd9865f8](https://user-images.githubusercontent.com/88670187/205495390-0bb18018-9462-48d4-82ec-b8cedb3f5d78.png)
![170623849-7cb26533-3d12-4ebb-9faa-c8a1b162b0cf](https://user-images.githubusercontent.com/88670187/205495400-68dc5e02-b4db-48a8-939b-7560fadc96bd.png)

 ### PLOT 
 ![170624053-ab1f4eb0-5579-451e-bd19-dacd4c098629](https://user-images.githubusercontent.com/88670187/205495402-288c8e79-c3d5-42ce-9ed9-4b5c0b5a8e78.png)
 ![170624071-a8a118f1-3032-40f4-9014-2faf3055d9ee](https://user-images.githubusercontent.com/88670187/205495408-7fca049a-5c23-4226-8f38-2d8ccf0b6fc1.jpg)
 ![170624191-a7f570a4-91de-4b50-b5ce-70e6441efae6](https://user-images.githubusercontent.com/88670187/205495416-c176732a-1cdd-4f7b-bd8a-85c5b65ca841.png)
 ![170624205-059291ef-9ff5-4610-af0e-c1cc99181782](https://user-images.githubusercontent.com/88670187/205495425-be08d868-e789-4e26-8395-f3b42840bc3d.jpg)

 ### RESULTS :  Thus,the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer is analysed and the graph of joint angle for a given input end effector position is plotted.
 
