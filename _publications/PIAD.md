---
title: "Physics-informed Anomaly Detection for Unmanned Aerial Vehicles"
collection: publications
category: manuscripts
permalink: /publications/PIAD/
excerpt: 'Physics-informed deep learning framework for UAV runtime anomaly detection.'
date: 2025-10-01
venue: 'IEEE Robotics and Automation Letters (RA-L)'
paperurl: '/files/PIAD.pdf'
citation: 'Guo, Yifan, Kartik A. Pant, and Inseok Hwang. "Physics-Informed Anomaly Detection for Unmanned Aerial Vehicles." IEEE Robotics and Automation Letters 10, no. 10 (2025): 9948-9955.'
---

The secure operation of Unmanned Aerial Vehicle (UAV) systems requires assurance of safety and reliability. However, their security aspect can be challenged by various unexpected anomalies, which can significantly compromise a UAV's performance or lead to catastrophic failures. The UAV's runtime safety assurance in dynamic environments remains an open problem. To address this challenge, we propose a novel physics-informed anomaly detection framework called Physics-informed Prediction for Detection (PIPD) and instantiate the framework into two specific models, PIPDall and PIPDres. The proposed framework efficiently integrates the knowledge of physical dynamics into a deep anomaly detection model, exhibiting significantly better detection accuracies and a superior generalization ability to unseen anomalies. Unlike typical physics-informed frameworks, which often sharpen the loss landscape, our framework further smoothens it, thereby facilitating an efficient training process. We validate our framework using emulated Global Navigation Satellite System (GNSS) spoofing attacks with linear and sinusoidal profiles, which are covered under different noise levels. The simulation results present a performance improvement of up to 17.77% in the ROC-AUC score of our models compared to the baselines. Through real-world experiments, we confirm the effectiveness of our framework against multi-noise GNSS spoofing attacks and extend our validation to other complex scenarios, including aperiodic GNSS attacks and wind disturbance.
