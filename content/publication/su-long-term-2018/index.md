---
title: Long-term Blood Pressure Prediction with Deep Recurrent Neural Networks
authors:
- Peng Su
- Xiao-Rong Ding
- Yuan-Ting Zhang
- Jing Liu
- Fen Miao
- Ni Zhao
date: '2018-01-14'
publishDate: '2023-11-24T10:38:57.935832Z'
publication_types:
- article-journal
abstract: Existing methods for arterial blood pressure (BP) estimation directly map
  the input physiological signals to output BP values without explicitly modeling
  the underlying temporal dependencies in BP dynamics. As a result, these models suffer
  from accuracy decay over a long time and thus require frequent calibration. In this
  work, we address this issue by formulating BP estimation as a sequence prediction
  problem in which both the input and target are temporal sequences. We propose a
  novel deep recurrent neural network (RNN) consisting of multilayered Long Short-Term
  Memory (LSTM) networks, which are incorporated with (1) a bidirectional structure
  to access larger-scale context information of input sequence, and (2) residual connections
  to allow gradients in deep RNN to propagate more effectively. The proposed deep
  RNN model was tested on a static BP dataset, and it achieved root mean square error
  (RMSE) of 3.90 and 2.66 mmHg for systolic BP (SBP) and diastolic BP (DBP) prediction
  respectively, surpassing the accuracy of traditional BP prediction models. On a
  multi-day BP dataset, the deep RNN achieved RMSE of 3.84, 5.25, 5.80 and 5.81 mmHg
  for the 1st day, 2nd day, 4th day and 6th month after the 1st day SBP prediction,
  and 1.80, 4.78, 5.0, 5.21 mmHg for corresponding DBP prediction, respectively, which
  outperforms all previous models with notable improvement. The experimental results
  suggest that modeling the temporal dependencies in BP dynamics significantly improves
  the long-term BP prediction accuracy.
tags:
- Computer Science - Machine Learning
- Computer Science - Artificial Intelligence
- Mathematics - Dynamical Systems
- Statistics - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/1705.04524
---
