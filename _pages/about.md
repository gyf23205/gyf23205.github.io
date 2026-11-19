---
permalink: /
title: "Yifan Guo"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I am Yifan Guo, a fourth-year Ph.D. student at the [FD&C/HS Lab](https://sites.google.com/view/fdchsl/home) of Purdue University. I am affiliated with the Elmore Family School of Electrical and Computer Engineering and the School of Aeronautics and Astronautics, and I am co-advised by [Prof. Inseok Hwang](https://engineering.purdue.edu/~ihwang/) and [Prof. Jianghai Hu](https://engineering.purdue.edu/~jianghai/). I also collaborate with [Prof. Chen Wang](https://engineering.buffalo.edu/computer-science-engineering/people/faculty-directory/full-time.host.html/content/shared/engineering/computer-science-engineering/profiles/faculty/ladder/wang-chen.detail.html) at [SAIR Lab](https://sairlab.org/).

My research is on learning-based autonomy for unmanned aerial vehicles (UAVs), quadruped robots, and planetary rovers, in simulation and on hardware. I work on world models, learning-based control, and multi-agent planning. Besides developing algorithms, I build high-fidelity simulation environments (NVIDIA Isaac Sim, Isaac Lab) and run hardware experiments (Crazyflie quadrotors, quadruped robots), because an algorithm only matters if it runs reliably on the vehicle.

**I am looking for a research internship for Summer 2027 in robotics and physical AI.** Please feel free to [contact me](mailto:guo781@purdue.edu).

Research Interests
======
The central question of my research is how to learn models of robot dynamics that are accurate and reliable enough to act on, using prior knowledge (system dynamics, symbolic solvers, operator theory) to reduce the data burden and improve generalization and safety.

- **World models and runtime monitoring.** I learn system dynamics in a latent space with a Joint-Embedding Predictive Architecture (JEPA) world model, and use its prediction error for fault detection, isolation, and recovery (FDIR). Trained on a high-fidelity Isaac Sim dataset of extreme lunar terrain, the model serves as the runtime monitor in Hyundai–Kia's lunar rover project, reaching over 93% area under the receiver operating characteristic curve (AUC-ROC) and over 90% F1 score ([IEEE Transactions on Neural Networks and Learning Systems (TNNLS), under review](/publications/UnifiedAD/)). Earlier, I combined physics priors with deep networks to detect UAV anomalies, validated on Crazyflie quadrotors ([IEEE Robotics and Automation Letters (RA-L), 2025](/publications/PIAD/)).
- **Modular and transferable control.** Using Koopman operator theory, I decompose neural network controllers into reusable modules with theoretical guarantees. This enables rapid policy transfer across tasks, environments, and embodiments on quadrupeds and UAVs, with up to 56% better convergence and 81% better jump-start than baselines ([IEEE Transactions on Robotics (T-RO), under review](/publications/PaddedKoopman/)). The same idea extends to the functional decomposition of large language models (LLMs) (IEEE TNNLS, under review).
- **Self-supervised multi-agent planning.** With imperative learning ([International Journal of Robotics Research (IJRR), 2025](/publications/IL/)), a symbolic solver supervises a neural network without labels. I applied it to the NP-hard min-max multiple traveling salesman problem ([iMTSP, IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2024](/publications/iMTSP/)), outperforming Google OR-Tools by 80% on instances with 500 or more cities in 5% of its computation time, and to routing with time windows ([NS-RTW, IEEE Transactions on Intelligent Transportation Systems (T-ITS) 2026](/publications/NSRTW/)).

News
======
[2026/09] Our paper "NS-RTW: Neuro-Symbolic Planning for Min–Max Routing With Time Windows" is published in IEEE T-ITS!

[2026] My papers "[Padded Koopman Continual Reinforcement Learning: Unified Policy Preservation and Decomposition](/publications/PaddedKoopman/)" (IEEE T-RO) and "[A Unified Framework for Anomaly Detection, Classification, and Root Cause Analysis of Dynamic Systems](/publications/UnifiedAD/)" (IEEE TNNLS) are under review.

[2026/05] Started the latent world model project for runtime monitoring of Hyundai–Kia's lunar rover.

[2025/04/20] My paper "Physics-Informed Anomaly Detection for Unmanned Aerial Vehicles" is published in IEEE RA-L!

[2025/04/10] My paper "Imperative Learning: A Self-Supervised Neuro-Symbolic Learning Framework for Robot Autonomy" is published in IJRR!
