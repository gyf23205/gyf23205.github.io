---
title: "NS-RTW: Neuro-Symbolic Planning for Min–Max Routing With Time Windows"
collection: publications
category: manuscripts
permalink: /publications/NSRTW/
excerpt: 'A self-supervised neuro-symbolic bi-level method for min-max multi-agent routing with time windows.'
date: 2026-09-02
venue: 'IEEE Transactions on Intelligent Transportation Systems (T-ITS)'
paperurl: '/files/NS-RTW.pdf'
citation: 'Li, Jiaxian, Yifan Guo, Chen Wang, and Zhongqiang Ren. "NS-RTW: Neuro-Symbolic Planning for Min–Max Routing With Time Windows." IEEE Transactions on Intelligent Transportation Systems 27, no. 11 (2026): 15115-15130.'
---

This paper investigates a min-max routing problem with time windows (RTW), which seeks paths for multiple agents starting from a single depot to visit a set of target locations, each within a designated time window, while minimizing the maximum completion time among the agents. Most existing research either considers the min-sum objective (minimizing the sum of completion times) or ignores the time window constraints. Recent work explores data-driven approaches, such as reinforcement learning (RL), to address this challenge. However, it still struggles to generalize to unseen scenarios outside the training set. To address these challenges, we propose a neuro-symbolic method called NS-RTW, which combines learning-based and classical search techniques within a bi-level optimization framework, enabling end-to-end self-supervision and offering better generalization than existing methods. On synthetic datasets, our method is able to find feasible solutions for all instances, outperforming the RL baseline, which fails in complex scenarios. Among all baseline methods, ours finds the best-quality solution in 87.1% of commonly solved instances. Experiments on Solomon benchmark and real-world case further demonstrate the generalization capability and practical applicability of our method.
