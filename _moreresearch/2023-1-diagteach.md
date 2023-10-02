---
id:             2023-diagteach
title:          "Learning from Demonstration via Probabilistic Diagrammatic Teaching"
authors:
    - WZhi
    - Me
    - MJR
venue:          Under Review | [Spotlight] 2023 IROS DiffPropRob Workshop 
year:           "2023-09"
thumbnail:      assets/moreresearch/dia_teach.png
links:
    paper:      https://arxiv.org/abs/2309.03835

layout: project
short_title: Diagrammatic Teaching
abstract: "Learning for Demonstration (LfD) enables robots to acquire new skills by imitating expert demonstrations, allowing users to communicate their instructions in an intuitive manner. Recent progress in LfD often relies on kinesthetic teaching or teleoperation as the medium for users to specify the demonstrations. Kinesthetic teaching requires physical handling of the robot, while teleoperation demands proficiency with additional hardware. This paper introduces an alternative paradigm for LfD called Diagrammatic Teaching. Diagrammatic Teaching aims to teach robots novel skills by prompting the user to sketch out demonstration trajectories on 2D images of the scene, these are then synthesised as a generative model of motion trajectories in 3D task space. Additionally, we present the Ray-tracing Probabilistic Trajectory Learning (RPTL) framework for Diagrammatic Teaching. RPTL extracts time-varying probability densities from the 2D sketches, applies ray-tracing to find corresponding regions in 3D Cartesian space, and fits a probabilistic model of motion trajectories to these regions. New motion trajectories, which mimic those sketched by the user, can then be generated from the probabilistic model. We empirically validate our framework both in simulation and on real robots, which include a fixed-base manipulator and a quadruped-mounted manipulator."
---