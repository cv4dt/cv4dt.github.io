---
title: Computer Vision
date: 2025-01-01
#links:
#  - type: site
#    url: https://github.com/pandas-dev/pandas
tags:
  #- Hugo
  #- HugoBlox
  #- Markdown
authors:
  - dr-olaf-wysocki
  - haibing-wu
  - qilin-zhang
  - daniel-lehmberg
---

We are the Computer Vision Working Group of CV4DT. Click for more!

<!--more-->

We are a computer vision & 3D reconstruction working group ([Olaf Wysocki](/author/dr-olaf-wysocki/), [Haibing Wu](/author/haibing-wu/), [Qilin Zhang](/author/qilin-zhang/), [Daniel Lehmberg](/author/daniel-lehmberg/)) focusing on:
- 3D semantic object reconstruction 
- Uncertainty-aware novel view synthesis   
- Geometric prior-guided reconstruction  

# Research Projects

Our projects are primarily **research-oriented**, aiming for publication in top-tier computer vision and graphics venues such as **CVPR**, **NeurIPS**, and **ICCV**.  
Below is an overview of our ongoing and upcoming research directions.

---

### 🏠 Structured 3D Object Reconstruction

We aim to reconstruct **structured 3D models** aligned with interpretable geometric and semantic representations.  
This direction builds upon our prior work:  
- [*Texture2LoD3: Enabling LoD3 Building Reconstruction With Panoramic Images* (CVPR 2025)](https://openaccess.thecvf.com/content/CVPR2025W/USM3D/papers/Tang_Texture2LoD3_Enabling_LoD3_Building_Reconstruction_With_Panoramic_Images_CVPRW_2025_paper.pdf)  
- [*Scan2LoD3: Reconstructing semantic 3D building models at LoD3 using ray casting and Bayesian networks* (CVPR23)](https://openaccess.thecvf.com/content/CVPR2023W/PCV/papers/Wysocki_Scan2LoD3_Reconstructing_Semantic_3D_Building_Models_at_LoD3_Using_Ray_CVPRW_2023_paper.pdf)  

Several project proposals are currently under review to expand this line of research.

---

### 🧩 Revisiting Geometric Features for 3D Scene Understanding

We revisit **geometric descriptors** for large-scale **3D semantic segmentation**, **SSL**, **3D instance segmentation**, **3D object pose estimation**, **3D shape completion**,  studying how handcrafted and learned geometric features can be combined to achieve better generalization across domains. Preliminary findings are available in [*arXiv:2402.06506*](https://arxiv.org/pdf/2402.06506) 

Papers are in the making to expand this line of research.

---

### 🧭 6DoF Estimation Using Structured 3D Models

We explore **structured 3D model representations** for **6-degree-of-freedom (6DoF) pose estimation**, targeting improved robustness and interpretability compared to implicit or point-based methods.  
This direction builds on related work of [*3D Structured Priors for Pose Estimation* (NeurIPS 2024)](https://proceedings.neurips.cc/paper_files/paper/2024/file/d78ece6613953f46501b958b7bb4582f-Paper-Conference.pdf).
  
A new iteration of this work is in preparation for upcoming major conference deadlines.

---

### 🌌 Geometry-Prior-Guided 3D Gaussian Splatting

This project investigates the integration of **geometry-aware priors** into **3D Gaussian Splatting** to enhance reconstruction quality and geometric fidelity.  
Preliminary findings are available in [*arXiv:2508.07355*](https://arxiv.org/pdf/2508.07355), and ongoing work extends the framework beyond building-specific scenarios toward **general-purpose 3D environments**.

---

### 🗂️ Dataset Development

We also curate and release datasets supporting our main research directions, including:  
- **Facade Segmentation Dataset** – for large-scale semantic façade parsing; This building upon our worldwide-largest facade dataset [*ZAHA* (WACV25)](https://openaccess.thecvf.com/content/WACV2025/html/Wysocki_ZAHA_Introducing_the_Level_of_Facade_Generalization_and_the_Large-Scale_WACV_2025_paper.html) 
- **Point Cloud Completion Dataset** – for partial-to-complete reconstruction learning  
- **3D Object Reconstruction Dataset** – for structured geometry prediction and analysis  

These datasets promote **reproducible, data-rich 3D research** across geometry, perception, and robotics.



We are always looking for fantastic persons to join us for the following project collaboration!