---
title: Visual Tracking With Convolutional Random Vector Functional Link Network
authors:
- Le Zhang
- Ponnuthurai Nagaratnam Suganthan
date: '2017-10-01'
publishDate: '2023-11-24T10:39:00.230099Z'
publication_types:
- article-journal
doi: 10.1109/TCYB.2016.2588526
abstract: Deep neural network-based methods have recently achieved excellent performance
  in visual tracking task. As very few training samples are available in visual tracking
  task, those approaches rely heavily on extremely large auxiliary dataset such as
  ImageNet to pretrain the model. In order to address the discrepancy between the
  source domain (the auxiliary data) and the target domain (the object being tracked),
  they need to be finetuned during the tracking process. However, those methods suffer
  from sensitivity to the hyper-parameters such as learning rate, maximum number of
  epochs, size of mini-batch, and so on. Thus, it is worthy to investigate whether
  pretraining and fine tuning through conventional back-prop is essential for visual
  tracking. In this paper, we shed light on this line of research by proposing convolutional
  random vector functional link (CRVFL) neural network, which can be regarded as a
  marriage of the convolutional neural network and random vector functional link network,
  to simplify the visual tracking system. The parameters in the convolutional layer
  are randomly initialized and kept fixed. Only the parameters in the fully connected
  layer need to be learned. We further propose an elegant approach to update the tracker.
  In the widely used visual tracking benchmark, without any auxiliary data, a single
  CRVFL model achieves 79.0% with a threshold of 20 pixels for the precision plot.
  Moreover, an ensemble of CRVFL yields comparatively the best result of 86.3%.
tags:
- deep learning
- Data models
- Biological neural networks
- Training
- Convolutional neural network (CNN)
- convolutional random vector functional link (CRVFL)
- random vector functional link (RVFL)
- Target tracking
- visual tracking
- Visualization
---
