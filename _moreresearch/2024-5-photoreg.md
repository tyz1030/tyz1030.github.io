---
id:             2024-photoreg
title:          "PhotoReg: Photometrically Registering 3D Gaussian Splatting Models"
authors:
    - Ziwen Yuan
    - Me
    - MJR
    - WZhi
venue:          Under Review         
year:           "2024-10"
thumbnail:      assets/moreresearch/photoreg/photoreg.png
links:
    website:    https://ziweny11.github.io/photoreg/
    paper:      https://arxiv.org/abs/2410.05044

layout: project
short_title: Photometrically Registering 3D Gaussian Splatting Models
abstract: "Building accurate representations of the environment is critical for intelligent robots to make decisions during deployment. Advances in photorealistic environment models have enabled robots to develop hyper-realistic reconstructions, which can be used to generate images that are intuitive for human inspection. In particular, the recently introduced 3D Gaussian Splatting (3DGS), which describes the scene with up to millions of primitive ellipsoids, can be rendered in real time. 3DGS has rapidly gained prominence. However, a critical unsolved problem persists: how can we fuse multiple 3DGS into a single coherent model? Solving this problem will enable robot teams to jointly build 3DGS models of their surroundings. A key insight of this work is to leverage the duality between photorealistic reconstructions, which render realistic 2D images from 3D structure, and 3D foundation models, which predict 3D structure from image pairs. To this end, we develop PhotoReg, a framework to register multiple photorealistic 3DGS models with 3D foundation models. As 3DGS models are generally built from monocular camera images, they have arbitrary scale. To resolve this, PhotoReg actively enforces scale consistency among the different 3DGS models by considering depth estimates within these models. Then, the alignment is iteratively refined with fine-grained photometric losses to produce high-quality fused 3DGS models. We rigorously evaluate PhotoReg on both standard benchmark datasets and our custom-collected datasets, including with two quadruped robots."
---