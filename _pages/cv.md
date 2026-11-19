---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download my resume (PDF)](/files/Yifan_Guo_Resume.pdf)

Education
======
* Ph.D. in Electrical and Computer Engineering, Purdue University, Sept. 2023 – May 2028 (expected)
* M.S. in Electrical and Computer Engineering, University of Pittsburgh, Sept. 2021 – Jan. 2023
* B.S. in Computer Science, Jiangsu University, China, Sept. 2016 – Jan. 2020

Research Experience
======
### Latent World Models for Lunar Rover Fault Detection, Isolation, and Recovery (FDIR)
**May 2026 – Present**  
[Code](https://github.com/gyf23205/Rover_FDIR)
- Developed a unified framework for anomaly detection, classification, and root cause analysis in dynamic systems (IEEE Transactions on Neural Networks and Learning Systems (TNNLS), under review).
- Developed a Joint-Embedding Predictive Architecture (JEPA) world model that learns robot dynamics in a latent space, improving prediction accuracy and interpretability.
- Built a high-fidelity NVIDIA Isaac Sim environment and dataset of extreme lunar terrain, rover operating conditions, and rover fault models.
- Deployed the framework for runtime monitoring in Hyundai–Kia's lunar rover project, achieving over 93% area under the receiver operating characteristic curve (AUC-ROC) and over 90% F1 score.
- Earlier work: modeled unmanned aerial vehicle (UAV) dynamics with physics-informed deep learning for anomaly detection; validated in simulation (Gazebo) and on Crazyflie hardware. Published in IEEE Robotics and Automation Letters (RA-L), 2025.

### Koopman-Based Policy Transfer and LLM Decomposition
**Apr. 2025 – Present**  
[Code](https://github.com/gyf23205/Koopman_decompose_ext)
- Proposed a Koopman-theory-based method to decompose neural network controllers into reusable modules with theoretical guarantees.
- Enabled rapid policy transfer across tasks, environments, and embodiments on quadruped robots and UAVs, in simulation and real-world experiments.
- Achieved up to 56% better convergence and 81% better jump-start than baselines ("Padded Koopman Continual Reinforcement Learning: Unified Policy Preservation and Decomposition," IEEE Transactions on Robotics (T-RO), under review).
- Extended the method to the functional decomposition of large language models (LLMs) (IEEE TNNLS, under review).

### Workload-Aware Human-Autonomy Teaming
**May 2025 – Aug. 2025**  
[Video](https://youtu.be/tOOq3-FIZnY)
- Built a human-autonomy teaming system for a rescue scenario that estimates operator workload from eye-tracking and electrocardiogram (ECG) data and adaptively allocates coordination tasks with learning-based temporal logic.
- Led development of the host and user graphical user interfaces (GUIs) and the multi-device data pipeline, and ran human-subject tests for the sponsor demonstration.

### Imperative Learning for Multi-Agent Autonomy (iMTSP)
**Sept. 2022 – Feb. 2023**  
[Code](https://github.com/sair-lab/iMTSP)
- Co-developed imperative learning, a self-supervised neuro-symbolic framework that uses symbolic reasoning (logic, physics, geometry) to remove the need for labels. Published in the International Journal of Robotics Research (IJRR), 2025.
- Led iMTSP, applying it to the NP-hard min-max multiple traveling salesman problem. Published in the IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2024.
- Produced near-optimal routes for thousands of cities, a scale prohibitive for classical solvers.
- Outperformed state-of-the-art reinforcement learning (RL) and heuristic baselines; with 500 or more cities, achieved 80% better solutions than Google OR-Tools' metaheuristic in 5% of its computation time.
- Follow-up work, NS-RTW, extends the approach to routing with time windows. Published in IEEE Transactions on Intelligent Transportation Systems (T-ITS), 2026.

### EEG-Based Human Sleep Stage Estimation
**May 2021 – Aug. 2022**  
[Paper](https://doi.org/10.1186/s40537-023-00758-9)
- Proposed a semi-supervised cluster-then-label algorithm to handle the distribution shift of electroencephalogram (EEG) data between human subjects, improving accuracy and F1 score by 7.17 ± 6.15% and 9.17 ± 4.98% over the state-of-the-art baseline. Published in the Journal of Big Data, 2023.
- Coordinated the AI, hardware, and biology teams, and supervised junior researchers.
- Collected and processed sleep data from human subjects.

Industry Experience
======
### Research Intern, Hanwang Technology, Beijing, China
**June 2019 – Aug. 2019**
- Developed a prototype system using Connectionist Temporal Classification (CTC) to label unsegmented sequence data.
- Implemented and trained a handwriting recognition model (bidirectional long short-term memory network (Bi-LSTM) + CTC).
- Gave a technical presentation to the team on the internal mechanics of the CTC layer.

Teaching
======
<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Skills
======
* **Machine learning:** reinforcement learning, self-supervised and semi-supervised learning, world models, time-series anomaly detection, transfer learning, neuro-symbolic learning
* **Robotics and autonomy:** UAVs, quadruped robots, planetary rovers, FDIR, multi-agent control and route planning, runtime safety monitoring, Koopman theory
* **Tools:** Python, C++, PyTorch, ROS 2, NVIDIA Isaac Sim, Isaac Lab, Gazebo, Crazyflie, Ubuntu, Docker

Publications
======
Full list on [Google Scholar](https://scholar.google.com/citations?user=oYBlfUUAAAAJ&hl=en).

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
