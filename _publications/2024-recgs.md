---
id:             2024-1-recgs
title:          "RecGS: Removing Water Caustic with Recurrent Gaussian Splatting"
authors:
    - Me
    - WZhi
    - Braden Meyers
    - Nelson Durrant
    - Kaining
    - Josh
    - Corina
    - MJR
venue:          RA-L 2024, ICRA 2025
year:           "2024-07"
thumbnail:      assets/publications/2024-recgs/recgs.png
links:
    paper:      https://arxiv.org/abs/2407.10318
    code:       https://github.com/tyz1030/recgs
    bibtex:     assets/publications/2024-recgs/ref.txt
    website:    https://tyz1030.github.io/proj/recgs.html

layout: project
short_title: Removing Water Caustic with Recurrent Gaussian Splatting
abstract: "Water caustics are commonly observed in seafloor imaging data from shallow-water areas. Traditional methods that remove caustic patterns from images often rely on 2D filtering or pre-training on an annotated dataset, hindering the performance when generalizing to real-world seafloor data with 3D structures. In this paper, we present a novel method Recurrent Gaussian Splatting, which takes advantage of today's photorealistic 3D reconstruction technology, 3D Guassian Splatting (3DGS), to separate caustics from seafloor imagery. With a sequence of images taken by an underwater robot, we build 3DGS recursively and decompose the caustic with low-pass filtering in each iteration. In the experiments, we analyze and compare with different methods, including joint optimization, 2D filtering, and deep learning approaches. The results show that our method can effectively separate the caustic from the seafloor, improving the visual appearance."
---
