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
  - wanru-yang
  - haibing-wu
  - qilin-zhang
  - daniel-lehmberg
---

We are the Computer Vision Working Group of CV4DT. Click for more!

<!--more-->

We are the Computer Vision Working Group of CV4DT: ([Olaf Wysocki](/author/dr-olaf-wysocki/), [Haibing Wu](/author/haibing-wu/), [Qilin Zhang](/author/qilin-zhang/), [Daniel Lehmberg](/author/daniel-lehmberg/), [Wanru Yang](/author/wanru-yang/)).

# Research Projects

Our projects are primarily **research-oriented**, aiming for publication in top-tier computer vision venues such as **CVPR**, **ECCV** **NeurIPS**, and similar.  
Below is an overview of our ongoing and upcoming research directions.

---

### 🏠 Structured 3D Object Reconstruction

We aim to reconstruct **structured 3D models** aligned with interpretable geometric and semantic representations.  
This direction builds upon our prior work:  
- [*Texture2LoD3: Enabling LoD3 Building Reconstruction With Panoramic Images* (CVPR25)](https://openaccess.thecvf.com/content/CVPR2025W/USM3D/papers/Tang_Texture2LoD3_Enabling_LoD3_Building_Reconstruction_With_Panoramic_Images_CVPRW_2025_paper.pdf)  
- [*Scan2LoD3: Reconstructing semantic 3D building models at LoD3 using ray casting and Bayesian networks* (CVPR23)](https://openaccess.thecvf.com/content/CVPR2023W/PCV/papers/Wysocki_Scan2LoD3_Reconstructing_Semantic_3D_Building_Models_at_LoD3_Using_Ray_CVPRW_2023_paper.pdf)  

Several project proposals are currently under review to expand this line of research.

---

### 🧩 Revisiting Geometric Features for 3D Scene Understanding

We revisit **geometric descriptors** for large-scale **3D semantic segmentation**, **SSL**, **3D instance segmentation**, **3D object pose estimation**, **3D shape completion**,  studying how handcrafted and learned geometric features can be combined to achieve better generalization across domains. Preliminary findings are available in [*arXiv:2402.06506*](https://arxiv.org/pdf/2402.06506) 

Papers are in the making to expand this line of research.

---

### 🏁 Sim2Real 3D Domain Gap

We still observe large domain gaps between simulated and real-world data, hampering application of simulated data into real-world challenges and many downstream tasks. We believe in the power of *diffusion models* to cater for this gap. Preliminary results, building a framework for running simulations within the unique real-world city twin are here: [*arXiv:2505.17959*](https://arxiv.org/abs/2505.17959)

One paper is under review, while another draft is in preparation. 

---


### 🧭 6DoF Estimation Using Structured 3D Models

We explore **structured 3D model representations** for **6-degree-of-freedom (6DoF) pose estimation**, targeting improved robustness and interpretability compared to implicit or point-based methods.  
This direction builds on related work of [*LoD-Loc: Aerial Visual Localization using LoD 3D
Map with Neural Wireframe Alignment* (NeurIPS24)](https://proceedings.neurips.cc/paper_files/paper/2024/file/d78ece6613953f46501b958b7bb4582f-Paper-Conference.pdf).
  
A new iteration of this work is in preparation for upcoming major conference deadlines.

---

### 🌌 Geometry-Prior-Guided 3D Gaussian Splatting

This project investigates the integration of **geometry-aware priors** into **3D Gaussian Splatting** to enhance reconstruction quality and geometric fidelity.  
Preliminary findings are available in [*arXiv:2508.07355*](https://arxiv.org/pdf/2508.07355), and ongoing work extends the framework beyond building-specific scenarios toward **general-purpose 3D environments**.

---

### 📈 Quantifying Uncertainty of X

In this research direction, we explore quantification of uncertainty in various modalities and downstream tasks: From data acqusition, through segmentation to inference. Our rationale is often grounded in Bayesian modeling of uncertainty (but not limited to!). Previously published papers, e.g., on reconstruction uncertainty
[*Scan2LoD3: Reconstructing semantic 3D building models at LoD3 using ray casting and Bayesian networks* (CVPR23)](https://openaccess.thecvf.com/content/CVPR2023W/PCV/papers/Wysocki_Scan2LoD3_Reconstructing_Semantic_3D_Building_Models_at_LoD3_Using_Ray_CVPRW_2023_paper.pdf). 
Currently, we are involved in the funded project, [NeRF2BIM](https://www.asg.ed.tum.de/en/gds/forschung-research/projects/nerf2bim/), together with Profs Petzold, Holst and Niessner, where we analyze laser scanning uncertainty and its influence on final 3D object reconstruction.


---

### 🗂️ Dataset Development

We also curate and release datasets supporting our main research directions, including:  
- **Facade Segmentation Dataset** – for large-scale semantic façade parsing; This building upon our worldwide-largest facade dataset [*ZAHA* (WACV25)](https://openaccess.thecvf.com/content/WACV2025/html/Wysocki_ZAHA_Introducing_the_Level_of_Facade_Generalization_and_the_Large-Scale_WACV_2025_paper.html) 
- **Point Cloud Completion Dataset** – for partial-to-complete reconstruction learning  
- **3D Object Reconstruction Dataset** – for structured geometry prediction and analysis  

These datasets promote **reproducible, data-rich 3D research** across geometry, perception, and robotics.



We are always looking for fantastic persons to join us for the following project collaboration!
