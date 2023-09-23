---
id:             2023-orbistab
title:          "Learning Orbitally Stable Systems for Diagrammatically Teaching"
authors:
    - WZhi
    - Kangni
    - Me
    - MJR
# venue:          
year:           "2019-05"
thumbnail:      assets/moreresearch/orbi_stab.png
links:
    paper:      https://arxiv.org/abs/2309.10298

layout: project
short_title: Orbitally Stable Systems for Diagrammatically Teaching
abstract: "Diagrammatic Teaching is a paradigm for robots to acquire novel skills, whereby the user provides 2D sketches over images of the scene to shape the robot's motion. In this work, we tackle the problem of teaching a robot to approach a surface and then follow cyclic motion on it, where the cycle of the motion can be arbitrarily specified by a single user-provided sketch over an image from the robot's camera. Accordingly, we introduce the \emph{Stable Diffeomorphic Diagrammatic Teaching} (SDDT) framework. SDDT models the robot's motion as an \emph{Orbitally Asymptotically Stable} (O.A.S.) dynamical system that learns to follow the user-specified sketch. This is achieved by applying a \emph{diffeomorphism}, i.e. a differentiable and invertible function, to morph a known O.A.S. system. The parameterised diffeomorphism is then optimised with respect to the Hausdorff distance between the limit cycle of our modelled system and the sketch, to produce the desired robot motion. We provide theoretical insight into the behaviour of the optimised system and also empirically evaluate SDDT, both in simulation and on a quadruped with a mounted 6-DOF manipulator. Results show that we can diagrammatically teach complex cyclic motion patterns with a high degree of accuracy."
---