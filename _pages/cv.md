---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Electrical and Computer Engineering, Purdue University, 2028 (expected)
* M.S. in Electrical and Computer Engineering, University of Pittsburgh, 2022
* B.S. in Computer Science, Jiangsu University, China, 2020


Research Experience
======
### Workload-aware Human-autonomy Teaming  
**May 2025 – Aug. 2025**  
[Video](https://youtu.be/tOOq3-FIZnY)
- Led the design and implementation for both the host and user GUIs for our human-autonomy teaming system for a rescue scenario. The system uses eye trackers and ECG sensors to estimate users’ concentration status and uses a learning-based temporal logic to adaptively allocate the coordination tasks.  
- Built up the communication channel and synchronized the data flows between devices.  
- Tested our workload-aware human autonomy teaming framework on human subjects and supported the final presentation to the sponsors.

### Physics-informed Deep Learning for Anomaly Detection  
**Jan. 2023 – Present**  
[Code](https://github.com/gyf23205/FIAD)
- Led the development of a physics-informed deep learning anomaly detection framework, focusing on the runtime assurance of UAVs. Results are published in IEEE Robotics and Automation Letters (RA-L).  
- Combined the prior knowledge of system dynamics with a deep anomaly detector, significantly improving the detector’s robustness, accuracy, and loss landscape sensitivity.  
- Extended the algorithm for anomaly identification and relief. Applied the proposed method to both simulated (Gazebo) and real-world (Crazyflie) scenarios. Improved up to 12% detection AUC score over the advanced baseline. The magnitude of the condition number of the parameter Hessians drops from 208.9 to 31.5.

### Imperative Learning Solution for Robots Route Planning  
**Sept. 2022 – Feb. 2023**  
[Code](https://github.com/sair-lab/iMTSP)
- Led the development of a self-supervised deep learning model for the NP-hard multiple traveling salesmen problem. Results are published in the International Conference on Intelligent Robots and Systems (IROS).  
- Achieved near-optimal routes for multiple traveling salesman problems with up to thousands of cities, which is computationally prohibitive for any classic method.  
- Outperformed state-of-the-art reinforcement learning-based and heuristic baselines with the proposed algorithm. With 5% computing time, our method achieved 80% better results than Google’s meta-heuristic approach on large-scale problems with 500 or more cities.

### VLM-Neural-Symbolic Framework for Multi-robot Coverage  
**Aug. 2024 – Present**  
[Code](https://github.com/gyf23205/NS_PC)
- Combined VLM, CNN, and MPC and proposed a VLM-Neural-Symbolic framework for multi-robot systems to accomplish the persistent coverage task in unseen environments with obstacles.  
- Overcame two major difficulties of reinforcement-learning-based coverage policy: (1) zero-shot generalization to unseen environments, (2) guaranteed connectivity and collision avoidance.  
- Built up high-fidelity simulation environments in Isaac Sim to validate the proposed method.

### Imperative Learning: A Self-supervised Robotics Learning Framework  
**Sept. 2022 – Feb. 2023**  
[Paper link](https://journals.sagepub.com/doi/full/10.1177/02783649251353181?casa_token=MIka0_oKH-IAAAAA%3A1Pe2QXXwPRUwDhy5QVOJom8vDjDN1xERrb7kpJlBHn5YcmBpWXDnCOkHtE7E3fFBHGyLflqSHFxb)
- Built the self-supervised neural-symbolic robotics learning framework: Imperative learning, in discrete optimization scenarios. Results are published in the International Journal of Robotics Research (IJRR).  
- Enhanced learning-based methods with symbolic methods. Overcame the label-intensive obstacles by taking advantage of symbolic reasoning concerning logical reasoning, physical principles, geometric analysis, etc.

### EEG-based Human Sleeping Stage Estimation  
**May 2021 – Aug. 2022**  
[Paper link](https://link.springer.com/article/10.1186/s40537-023-00758-9)
- Proposed a semi-supervised cluster-then-label algorithm to tackle the EEG distribution drifting challenge between human users. The accuracy and F1 scores were improved by 7.17 ± 6.15% and 9.17 ± 4.98%, respectively, compared with the state-of-the-art baseline. The results are published in the Journal of Big Data.  
- Coordinated the cooperation between the AI team, hardware team, and the biology team. Supervised junior researchers during the study. Significantly contributed to the commercialization process of the research.  
- Collected and processed real sleeping data from human subjects.

Work Experience
======
* Summer 2019:  Research Intern
  * HanWang Technology, Beijing, China
  * Supervisor: Shuwei Shao
  * Duties includes:
    * Developed a prototype system with the Connectionist Temporal Classification algorithm to solve the problem of labelling unsegmented. sequence data.
    * Implementedandtrainedahandwritingalgorithmrecognition model(Bi-LSTM+CTC).
    * Delivered a presentation on the internal working principle of the CTC layer for the team.
  
Skills
======
* Deep learning programming
  *  Python,PyTorch
  *  TorchRL
  *  PyTorchGeometric
* Simulation
  *  Gymnasium
  *  Gazebo
  *  IsaacSim
  *  IsaacLab
* Hardware
  * ROS2
  * Crazyflie
