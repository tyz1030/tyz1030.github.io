---
id:             2025-3-dreamsea
title:          "Infinite Leagues Under the Sea: Photorealistic 3D Underwater Terrain Generation by Latent Fractal Diffusion Models"
authors:
    - Me
    - WZhi
    - Josh
    - MJR
highlight:      Oral Presentation
venue:          FM-Wild@ICLR 2025; Full paper under review
year:           "2025-03"
thumbnail:      assets/publications/2025-dreamsea/dreamsea.png
links:
    paper:      https://arxiv.org/abs/2503.06784
    # code:       https://github.com/tyz1030/darkgs
    # bibtex:     assets/publications/2024-darkgs/ref.txt
    # website:    https://tyz1030.github.io/proj/darkgs.html

layout: project
short_title: Photorealistic 3D Underwater Terrain Generation by Latent Fractal Diffusion Models
abstract: "This paper tackles the problem of generating representations of underwater 3D terrain. Off-the-shelf generative models, trained on Internet-scale data but not on specialized underwater images, exhibit downgraded realism, as images of the seafloor are relatively uncommon. To this end, we introduce DreamSea, a generative model to generate hyper-realistic underwater scenes. DreamSea is trained on real-world image databases collected from underwater robot surveys. Images from these surveys contain massive real seafloor observations and covering large areas, but are prone to noise and artifacts from the real world. We extract 3D geometry and semantics from the data with visual foundation models, and train a diffusion model that generates realistic seafloor images in RGBD channels, conditioned on novel fractal distribution-based latent embeddings. We then fuse the generated images into a 3D map, building a 3DGS model supervised by 2D diffusion priors which allows photorealistic novel view rendering. DreamSea is rigorously evaluated, demonstrating the ability to robustly generate large-scale underwater scenes that are consistent, diverse, and photorealistic. Our work drives impact in multiple domains, spanning filming, gaming, and robot simulation."
---