---
id:             2024-stable
title:          "Teaching Periodic Stable Robot Motion Generation via Sketch
"
authors:
    - WZhi
    - Haozhan
    - Me
    - MJR
venue:          RA-L 2024, ICRA 2025
year:           "2024-12"
thumbnail:      assets/moreresearch/stable/stable.png
links:
    paper:      https://ieeexplore.ieee.org/abstract/document/10804075

layout: project
short_title: Teaching Periodic Stable Robot Motion Generation via Sketch
abstract: "Contemporary robots are complex systems. Teaching novel motion patterns to robots requires specialised expertise, often entailing the careful specification of robot motion or the cumbersome design of optimisation problems. In this letter, we seek to simplify the process of generating periodic motions, by teaching robots with user sketches. In particular, we tackle the problem of teaching a robot to approach a surface and then follow cyclic motion on the surface. The limit cycle of the motion can be arbitrarily specified by a single user-provided sketch over an image from the robot's camera, and the sketched limit cycle is then projected into the scene. To generate motion that converges to the limit cycle, we contribute the Stable Periodic Diagrammatic Teaching (SPDT) framework. SPDT models the robot's motion as an Orbitally Asymptotically Stable (O.A.S.) dynamical system that learns to stabilise based on the diagrammatic sketch provided by the user. This is achieved by applying a differentiable and invertible function, known as a diffeomorphism, to shape a known O.A.S. system. The parameterised diffeomorphism is then optimised with respect to the Hausdorff distance between the limit cycle of our modelled system and the sketch, to produce the desired robot motion. We provide insight into the behaviour of the optimised system and empirically evaluate SPDT. Results show that we can diagrammatically teach complex cyclic motion patterns with accuracy."
---