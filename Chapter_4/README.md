
# 3D Scene Modeling and Robotics Interaction - Related Resources(Chapter 4)
**************************


## Introduce
**************************
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The task of visual localization [1-3] is to estimate the translation and rotation of the visual device through the acquired visual data. The essence of the task is to solve the transformation matrix of the data transformed between different coordinate systems. The visual localization task is actually a general task description, and the camera localization task is a sub-task of it, aiming to solve the transformation matrix from the camera coordinate system to the world coordinate system. In actual operating environments, such as the situation where robots perceive scenes, camera localization tasks are usually classified according to actual application situations. When a robot enters a new scene, the primary task is to explore the environment extensively. During the entire exploration process, the robot operates without any prior knowledge of the environment. but the robot still needs to constantly perceive its own translation and rotation. In this situation, the camera localization task needs to be carried out while simultaneously exploring certain scene information. Such a camera localization task is called a visual odometry task. Visual odometry tasks usually need to temporarily save some information during the localization process. However, in real application environments, it is not necessary to constantly establish a large amount of temporary information during the localization process, but to locate with the help of known scene data. Such localization tasks are called re-localization tasks.


## Technical Case Source Code
**************************

### 4.3.1 Case One: Camera Relocalization Based Feature Database Matching
Related code: https://github.com/linharrrrrt/Feature-Based-Relocal

### 4.3.2 Case Two: Deep Learning Based Camera Relocalization
Related code: https://github.com/linharrrrrt/DL-Relocal

