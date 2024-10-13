---
id:             2024-gemrag
title:          "Embodied-RAG: General non-parametric Embodied Memory for Retrieval and Generation"
authors:
    - Quanting
    - So Yeon Min
    - Me
    - Aarav Bajaj
    - Ruslan Salakhutdinov
    - MJR
    - Bisk
venue:          Under Review         
year:           "2024-10"
thumbnail:      assets/moreresearch/gemrag/gem_rag.png
links:
    website:    https://quanting-xie.github.io/Embodied-RAG-web/
    paper:      https://arxiv.org/pdf/2409.18313

layout: project
short_title: General non-parametric Embodied Memory for Retrieval and Generation
abstract: "There is no limit to how much a robot might explore and learn, but all of that knowledge needs to be searchable
and actionable. Within language research, retrieval augmented generation (RAG) has become the workhouse of large-scale
non-parametric knowledge, however existing techniques do not directly transfer to the embodied domain, which is multimodal,
data is highly correlated, and perception requires abstraction. To address these challenges, we introduce Embodied-RAG,
a framework that enhances the foundational model of an embodied agent with a non-parametric memory system capable
of autonomously constructing hierarchical knowledge for both navigation and language generation. Embodied-RAG handles a
full range of spatial and semantic resolutions across diverse environments and query types, whether for a specific object or a
holistic description of ambiance. At its core, Embodied-RAG’s memory is structured as a semantic forest, storing language
descriptions at varying levels of detail. This hierarchical organization allows the system to efficiently generate context-sensitive outputs across different robotic platforms. We demonstrate that Embodied-RAG effectively bridges RAG to the robotics domain, successfully handling over 200 explanation and navigation queries across 19 environments, highlighting its promise for generalpurpose non-parametric system for embodied agents."
---