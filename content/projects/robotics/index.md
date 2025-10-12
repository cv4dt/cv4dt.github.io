---
title: Robotics
date: 2025-01-01
#links:
#  - type: site
#    url: https://github.com/pandas-dev/pandas
tags:
  #- Hugo
  #- HugoBlox
  #- Markdown
authors:
  - dr-guangming-wang
  - dr-yixiong-jing
  - qizhen-ying
---

We are the Robotics Working Group of CV4DT. Click for more!

<!--more-->

# Robotics
We are a computer vision & robotics working group ([Guangming Wang](/author/dr-guangming-wang/), [Yixiong Jing](/author/dr-yixiong-jing/), [Qizhen Ying](/author/qizhen-ying/)), focusing on:
- Robotic manipulation and control  
- 3D vision for robotic perception  
- Generative models for planning and world understanding  

We are always looking for fantastic persons to join us for the following project collaboration!

---

## Ongoing Research Projects

### Project 1: **ActionReasoning: Robot Action Reasoning in 3D Space with LLM for Robotic Brick Stacking**


<img src="/uploads/research_video_robotics/brick_stacking.gif" alt="brick demo" width="550">

Classical robotic systems typically rely on custom planners designed for constrained environments. While effective in restricted settings, these systems lack generalization capabilities, limiting the scalability of embodied AI and general‑purpose robots. To address this gap, we propose ActionReasoning, an LLM-driven framework that performs explicit action reasoning to produce physics-consistent, prior-guided decisions for robotic manipulation. The experiments demonstrate that the proposed multi-agent LLM framework enables stable brick placement without task-specific programming, highlighting its potential to generalize beyond narrowly defined tasks (Paper is submitted to a top robotic conference). 

### Project 2: **Robotic Perception: Physics-Aware 3D Gaussian Modeling**

Our goal is to develop a unified 3D Gaussian modeling framework that integrates geometric, semantic, and physical attributes, enabling robots to achieve dynamic and adaptive understanding of their environments, thereby acquiring human-like adaptability and generalization capabilities.


### Project 3: **Robotic Manipulation: Generalizable Manipulation of Different Types of Objects**

Our goal is to build a general reasoning framework for the manipulation of deformable objects, hinged objects, and rigid objects, progressing from universal representations of different types of objects, to general reasoning, and ultimately to general manipulation. This will enable robots to attain human-like perception and manipulation skills for different types of objects.

---

## Past Research Projects

### **RL-GSBridge: 3D Gaussian Splatting Based Real2Sim2Real Method for Robotic Manipulation Learning**

<img src="/uploads/research_video_robotics/Sim2real.gif" alt="RL-GSBridge demo" width="350">

Sim-to-Real refers to the process of transferring policies learned in simulation to the real world, which is crucial for achieving practical robotics applications. However, recent Sim2real methods either rely on a large amount of augmented data or large learning models, which is inefficient for specific tasks. To this end, we propose RL-GSBridge, a novel real-to-sim-to-real framework which incorporates 3D Gaussian Splatting into the conventional RL simulation pipeline, enabling zero-shot sim-to-real transfer for vision-based deep reinforcement learning. 

Through a series of sim-to-real experiments, including grasping and pick-and-place tasks, we demonstrate that RL-GSBridge maintains a satisfactory success rate in real-world task completion during sim-to-real transfer. Furthermore, a series of rendering metrics and visualization results indicate that our proposed mesh-based 3D GS reduces artifacts in unstructured objects, demonstrating more realistic rendering performance. The related work was published at top robotics conference [ICRA](https://ieeexplore.ieee.org/abstract/document/11128103).

### **SNI-SLAM: Semantic Neural Implicit SLAM**

<img src="/uploads/research_video_robotics/SNI_SLAM.gif" alt="SLAM demo" width="550">

We propose SNI-SLAM, a first semantic SLAM system utilizing neural implicit representation that simultaneously performs accurate semantic mapping high-quality surface reconstruction and robust camera tracking. In this system we introduce hierarchical semantic representation to allow multi-level semantic comprehension for top-down structured semantic mapping of the scene. In addition to fully utilize the correlation between multiple attributes of the environment we integrate appearance geometry and semantic features through cross-attention for feature collaboration. Our SNI-SLAM method demonstrates superior performance over all recent NeRF-based SLAM methods in terms of mapping and tracking accuracy on multiple datasets while also showing excellent capabilities in accurate semantic segmentation and real-time semantic mapping. Related work was publihsed at top computer vision conference [CVPR](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhu_SNI-SLAM_Semantic_Neural_Implicit_SLAM_CVPR_2024_paper.pdf).

### **Learning of Long-Horizon Sparse-Reward Robotic Manipulator Tasks With Base Controllers**

<img src="/uploads/research_video_robotics/20_arxiv_DDPGwB.gif" alt="RL robot arm demo" width="350">

Deep reinforcement learning (DRL) enables robots to perform some intelligent tasks end-to-end. However, there are still many challenges for long-horizon sparse-reward robotic manipulator tasks. We propose a method of learning long-horizon sparse-reward tasks utilizing one or more existing traditional controllers named base controllers. The experiments demonstrated that the learned  policies steadily outperform base controllers. Compared to previous works of learning from demonstrations, our method improves sample efficiency by orders of magnitude and improves performance. Overall, our method bears the potential of leveraging existing industrial robot manipulation systems to build more flexible and intelligent controllers. The related work was published at top AI journal [IEEE T-NNLS](https://ieeexplore.ieee.org/abstract/document/9882014)