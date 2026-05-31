# Pu Pang

**Ph.D. Student in Artificial Intelligence**
**Xi'an Jiaotong University & Zhongguancun Academy**

[![Email](https://img.shields.io/badge/Email-s--pp24%40bza.edu.cn-blue?style=flat-square\&logo=gmail)](mailto:s-pp24@bza.edu.cn)
[![GitHub](https://img.shields.io/badge/GitHub-fankewen-black?style=flat-square\&logo=github)](https://github.com/fankewen)

---

### About Me

I am a Ph.D. student in Artificial Intelligence at **Xi'an Jiaotong University** and **Zhongguancun Academy**.

My research focuses on **computer vision**, **multimodal fusion**, and **embodied perception**, with a particular interest in building structured scene representations for reconstruction, simulation-to-reality transfer, and robotic manipulation.

I am currently working on **Gaussian Splatting-based representations**, including transparent surface reconstruction, semantic 2D Gaussian fields, and dynamic 3D Gaussian fields for robot action prediction.

---

### Research & Projects

#### TSGS: Improving Gaussian Splatting for Transparent Surface Reconstruction via Normal and De-lighting Priors

**ACM Multimedia · Second Author**

Transparent objects are difficult for 3D Gaussian Splatting because low-opacity Gaussian particles often make depth rendering incorrectly capture the background.

In this work, we improve the depth rasterization process by introducing a sliding-window strategy in the CUDA rendering pipeline. The method searches for local regions with maximum opacity and uses them to recover more reliable transparent surface depth.

---

#### Bridging Simulation and Reality: Cross-Domain Transfer with Semantic 2D Gaussian Splatting

**Under Submission**

Simulation and real-world environments often contain a significant domain gap, which limits the direct deployment of robot policies trained in simulation.

We use **semantic 2D Gaussian Splatting** as a bridge between the robot and the environment. The constructed semantic 2DGS field provides cross-scene geometric and semantic representations for robot models. During manipulation, the field can be dynamically updated through real-time environmental inputs, enabling more effective sim-to-real transfer while reducing the dependence on real-world robot data.

---

#### GaussAct: Robot Manipulation via Dynamic 3D Gaussian Splatting

**Ongoing Work**

Accurate future scene prediction is important for safe and reliable robotic manipulation.

In this project, we explore a feed-forward dynamic 3D Gaussian field for predicting next-frame scene changes. By incorporating optical-flow priors and rigid-body constraints of robotic arms, we aim to make Gaussian particle motion physically meaningful and directly infer robot actions from particle dynamics.

---

### What I Build

* **Gaussian Splatting for scene representation**

  * Transparent surface reconstruction
  * Depth rendering and CUDA rasterization
  * 2D/3D Gaussian scene fields

* **Embodied perception for robotics**

  * Dynamic scene prediction
  * Robot manipulation from visual-geometric representations
  * Action inference from Gaussian particle motion

* **Sim-to-real transfer**

  * Semantic 2D Gaussian fields
  * Cross-domain geometric representations
  * Real-time environment-aware field updates

* **Multimodal and geometric perception**

  * Computer vision
  * Multimodal fusion
  * High-level scene understanding for embodied agents

---

### Experience & Education

| Period         | Role / Degree | Institution                                      | Focus                                                              |
| -------------- | ------------- | ------------------------------------------------ | ------------------------------------------------------------------ |
| 2024 — Present | Ph.D. Student | Xi'an Jiaotong University & Zhongguancun Academy | Artificial Intelligence · Embodied Perception · Gaussian Splatting |
| 2022 — 2024    | M.S.          | Xi'an Jiaotong University                        | Artificial Intelligence                                            |
| 2018 — 2022    | B.S.          | Xi'an Jiaotong University                        | Automation                                                         |

---

### Honors

* **First Prize**, Brain-Controlled Robotics Track, Brain-Computer Interface Competition, 2025

---

### Research Keywords

![Computer Vision](https://img.shields.io/badge/Computer%20Vision-Research-blue?style=flat-square)
![Multimodal Fusion](https://img.shields.io/badge/Multimodal%20Fusion-Research-blueviolet?style=flat-square)
![Embodied Perception](https://img.shields.io/badge/Embodied%20Perception-Robotics-green?style=flat-square)
![Gaussian Splatting](https://img.shields.io/badge/Gaussian%20Splatting-3D%20Representation-orange?style=flat-square)
![Robotic Manipulation](https://img.shields.io/badge/Robotic%20Manipulation-Action%20Prediction-red?style=flat-square)
![CUDA Rasterization](https://img.shields.io/badge/CUDA-Rasterization-black?style=flat-square)

---

### Current Focus

I am currently focusing on a compact but connected research direction:

> **Gaussian-based scene representations for embodied perception and robotic manipulation.**

In practice, this means building dynamic, semantic, and physically meaningful representations that can support reconstruction, prediction, sim-to-real transfer, and robot action generation.

---

### GitHub Notes

Some research repositories are being organized before public release.

I prefer to release projects with clear documentation, reproducible instructions, and concrete demos rather than raw experiment code.
