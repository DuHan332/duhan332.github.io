---
title: "Comparison of different Machine Learning Algorithm on Super Mario Bros."
collection: projects
type: "python project"
permalink: /projects/project8
---

A project that compares DQN and double DQN with dueling architecture on Super Mario Bros.

![DQN](/images/DQN.gif)

Description
------
This project compared the effectiveness of DQN and Double DQN with dueling architecture, specifically on a Super Mario Bros dataset, using the OpenAI Gym. As an intersection of my interests in video games and machine learning, this study aims to explore the DQN algorithm.

Features
------
In this project, I compare Deep Q-Network (DQN) and Double Deep Q-Network (Double DQN), both augmented with Dueling Network architectures. DQN uses a target network to estimate maximum Q-values, which can lead to optimistic bias. Double DQN addresses this by using the online network to select actions and the target network to estimate their Q-values, reducing overestimation. The Dueling Network architecture, incorporated into both models, splits the network into streams for estimating A and V. Both of them are tested on the Super Mario Bros environment from the OpenAI Gym library. The results demonstrated that with dueling architecture, the difference between DQN and double DQN is not significant, implying that the dueling architecture minimizes the performance differences between DQN and Double DQN.

[Github](https://github.com/DuHan332/DQN_mario)
[Download Report](https://github.com/DuHan332/DQN_mario/blob/main/comparison_of_dqn_and_double_dqn_with_dueling_architecture.pdf)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1iATU6YkKwPCN-pLQxu53LjiMb1-rKvsZ)
