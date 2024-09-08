---
title: "MGCN: Enhanced Spatial-Temporal Dynamics in Pose Forecasting"
collection: article
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'Recently, there has been a growing interest in predicting human motion, which involves forecasting future body poses based on observed pose sequences. This task is complex due to modeling spatial and temporal relationships. Autoregressive models, including recurrent neural networks (RNNs) and their variants, as well as transformer networks, are commonly used for addressing this challenge. However, autoregressive models have several serious drawbacks, such as vanishing or exploding gradients. Other researchers have attempted to solve the communication problem in the spatial dimension by integrating graph convolutional networks (GCNs) and long short-term memory (LSTM) or convolutional neural network (CNN) models. These approaches process temporal and spatial information separately and fuse them to extract features, whereas this sequential processing hampers the model’s ability to capture spatiotemporal information and perform feature extraction simultaneously. To address this in human pose forecasting, we propose a novel approach called the multi-graph convolution network (MGCN). By introducing an augmented graph for pose sequences, our model captures spatial and temporal information in one step only using GCN. Multiple frames provide multiple parts, which are joined together in a unified graph instance. Furthermore, our model investigates the impact of natural structure and sequence-aware attention. In the experimental evaluation of the large-scale benchmark datasets (Human3.6M, AMSS, and 3DPW), MGCN outperforms the state-of-the-art methods in human pose prediction.'
date: 2024-06-25
venue: 'International Journal of Machine Learning and Cybernetics'
paperurl: 'https://link.springer.com/article/10.1007/s13042-024-02254-9'
---



**任务与贡献**：提出的 MGCN 模型将多个帧的时间序列与不同跳数的连接结合构建图，实现了时间和空间特征的一步集成来预测人体姿态。并融入了两种注意力机制：anchor 和 pseudo-regressive策略来提高各种姿态预测任务中的性能。

**效果**：超过了当前的最优模型在Human3.6M姿态预测数据集上基本各种运动类型的的预测准确率。发表在期刊International Journal of Machine Learning and Cybernetics
