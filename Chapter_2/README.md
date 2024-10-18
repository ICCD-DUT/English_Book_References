
# 3D Scene Modeling and Robotics Interaction - Related Resources(Chapter 2)
**************************


## Introduce
**************************
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Autonomous exploration of unknown environments has been a topic of significant interest, as effective scene exploration can provide robust and generalizable versatile planning strategies for various downstream tasks, such as autonomous scene scanning, reconstruction, and visual semantic navigation. However, due to challenges like occlusion and the limited field of view of cameras, the robot's observation of the environment usually only involves a local area of ​​the entire environment(e.g., a corner of a room). This limitation makes it difficult for the robot to plan its actions effectively based solely on such partial observations. Therefore, in addition to the robot's local observations, scene exploration also necessitates rich contextual knowledge about indoor environments. Specifically, the robot can utilize functional priors of the indoor environment to guide high-level search strategies (e.g., beds are usually found in bedrooms) and spatial layout priors to assist with low-level path planning (e.g., planning the shortest collision-free path to reach a target point). Representation methods for these scene priors include building 3D object model libraries for model matching, constructing scene knowledge graphs and using Graph Convolutional Networks (GCNs) for feature extraction, and employing scene completion algorithms to explicitly model prior scene information. The core challenge is how to effectively integrate the scene's local observation data with contextual prior knowledge to progressively improve the robot's understanding of the global scene, thus guiding more informed path planning and completing tasks like autonomous scene reconstruction and navigation. Consequently, the main challenges in scene exploration involve how to construct an effective representation method for scene prior knowledge, how to intelligently analyze local observation data in combination with contextual information, and how to find a balance between global scene exploration and local scanning, all with the goal of incrementally


## Technical Case Source Code
**************************
### 2.3.1 Case One: Object-aware guidance for autonomous scene reconstruction
Related paper: [Object-Aware Guidance for Autonomous Scene Reconstruction](https://vcc.tech/research/2018/ObjNBV)  <br>
Related code: https://github.com/againxx/OASC-Benchmark

### 2.3.2 Case Two: Design and Implementation of a System for Unknown 3D Scene Reconstruction
Related paper: [Autonomous Reconstruction of Unknown Indoor Scenes Guided by Time-varying Tensor Fields](https://vcc.tech/research/2017/Fetch1)  <br>
Related code on ROS: http://wiki.ros.org/tensor_field_nav

### 2.3.3 Case Three: Semantic Scene Completion based Scene Exploration in Visual Semantic Navigation
Related paper: [SSCNav: Confidence-Aware Semantic Scene Completion for Visual Semantic Navigation](https://sscnav.cs.columbia.edu/)
Related code: https://github.com/columbia-ai-robotics/SSCNav



