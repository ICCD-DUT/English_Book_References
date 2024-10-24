
# 3D Scene Modeling and Robotics Interaction - Related Resources(Chapter 2)
**************************


## Introduction
**************************
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Autonomous exploration of unknown environments has been a topic of significant interest, as effective scene exploration can provide robust and generalizable planning strategies for various downstream tasks, such as autonomous scene scanning, reconstruction, and visual semantic navigation. However, challenges such as occlusions and limited camera field of view restrict robots to local observations, hindering effective exploration. To address this, rich scene priors are crucial. The robot can leverage functional and spatial priors to guide exploration and path planning. Representation methods for these scene priors include building 3D object model libraries for model matching, constructing scene knowledge graphs and using Graph Convolutional Networks for feature extraction, and employing scene completion algorithms to model prior scene information explicitly. The key challenge lies in seamlessly integrating local observations with prior knowledge to enhance the robot's global understanding for improved path planning and task completion. This chapter reviews the current state of research, explores scene exploration methods, and presents case studies for practical insights.

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



