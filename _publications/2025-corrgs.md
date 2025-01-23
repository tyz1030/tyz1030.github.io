---
id:             2024-1-recgs
title:          "Scalable Benchmarking and Robust Learning for Noise-Free Ego-Motion and 3D Reconstruction from Noisy Video"
authors:
    - Xiaohao
    - Me
    - Shibo Zhao
    - Xiang li
    - Sibo Wang
    - Yongqi Chen
    - Ye
    - Bhiksha Raj
    - MJR
    - Sebastian Scherer
    - Xiaonan
venue:          ICLR 2025
year:           "2025-01"
thumbnail:      assets/publications/2025-corrgs/corrgs.png
links:
    paper:      https://openreview.net/forum?id=Pz9zFea4MQ&noteId=emrO4yq0eR
    # code:       https://github.com/tyz1030/recgs
    # bibtex:     assets/publications/2024-recgs/ref.txt
    # website:    https://tyz1030.github.io/proj/recgs.html

layout: project
short_title: Scalable Benchmarking and Robust Learning for Noise-Free Ego-Motion and 3D Reconstruction from Noisy Video
abstract: "We aim to redefine robust ego-motion estimation and photorealistic 3D reconstruction by addressing a critical limitation: the reliance on noise-free data in existing models. While such sanitized conditions simplify evaluation, they fail to capture the unpredictable, noisy complexities of real-world environments. Dynamic motion, sensor imperfections, and synchronization perturbations lead to sharp performance declines when these models are deployed in practice, revealing an urgent need for frameworks that embrace and excel under real-world noise. To bridge this gap, we tackle three core challenges: scalable data generation, comprehensive benchmarking, and model robustness enhancement. First, we introduce a scalable noisy data synthesis pipeline that generates diverse datasets simulating complex motion, sensor imperfections, and synchronization errors. Second, we leverage this pipeline to create Robust-Ego3D, a benchmark rigorously designed to expose noise-induced performance degradation, highlighting the limitations of current learning-based methods in ego-motion accuracy and 3D reconstruction quality. Third, we propose Correspondence-guided Gaussian Splatting (CorrGS), a novel method that progressively refines an internal clean 3D representation by aligning noisy observations with rendered RGB-D frames from clean 3D map, enhancing geometric alignment and appearance restoration through visual correspondence. Extensive experiments on synthetic and real-world data demonstrate that CorrGS consistently outperforms prior state-of-the-art methods, particularly in scenarios involving rapid motion and dynamic illumination. We will release our code and benchmark to advance robust 3D vision, setting a new standard for ego-motion estimation and high-fidelity reconstruction in noisy environments."
---
