---
id:             2024-toolcal
title:          "Manipulator-held tool calibration with 3D Foundation Models"
authors:
    - WZhi
    - Haozhan Tang
    - Me
    - MJR
venue:          RA-L 2024, ICRA 2025
year:           "2024-10"
thumbnail:      assets/moreresearch/toolcal_ral/toolcal.png
links:
    paper:      https://arxiv.org/abs/2407.10331

layout: project
short_title: Manipulator-held tool calibration with 3D Foundation Models
abstract: "Humans have the remarkable ability to use held objects as tools to interact with their environment. For this to occur, humans internally estimate how hand movements affect the object's movement. We wish to endow robots with this capability. We contribute methodology to jointly estimate the geometry and pose of objects grasped by a robot, from RGB images captured by an external camera. Notably, our method transforms the estimated geometry into the robot's coordinate frame, while not requiring the extrinsic parameters of the external camera to be calibrated. Our approach leverages 3D foundation models, large models pre-trained on huge datasets for 3D vision tasks, to produce initial estimates of the in-hand object. These initial estimations do not have physically correct scales and are in the camera's frame. Then, we formulate, and efficiently solve, a coordinate-alignment problem to recover accurate scales, along with a transformation of the objects to the coordinate frame of the robot. Forward kinematics mappings can subsequently be defined from the manipulator's joint angles to specified points on the object. These mappings enable the estimation of points on the held object at arbitrary configurations, enabling robot motion to be designed with respect to coordinates on the grasped objects. We empirically evaluate our approach on a robot manipulator holding a diverse set of real-world objects."
---