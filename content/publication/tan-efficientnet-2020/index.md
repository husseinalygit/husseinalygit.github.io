---
title: 'EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks'
authors:
- Mingxing Tan
- Quoc V. Le
date: '2020-09-11'
publishDate: '2023-11-24T10:38:59.793658Z'
publication_types:
- article-journal
abstract: Convolutional Neural Networks (ConvNets) are commonly developed at a fixed
  resource budget, and then scaled up for better accuracy if more resources are available.
  In this paper, we systematically study model scaling and identify that carefully
  balancing network depth, width, and resolution can lead to better performance. Based
  on this observation, we propose a new scaling method that uniformly scales all dimensions
  of depth/width/resolution using a simple yet highly effective compound coefficient.
  We demonstrate the effectiveness of this method on scaling up MobileNets and ResNet.
  To go even further, we use neural architecture search to design a new baseline network
  and scale it up to obtain a family of models, called EfficientNets, which achieve
  much better accuracy and efficiency than previous ConvNets. In particular, our EfficientNet-B7
  achieves state-of-the-art 84.3% top-1 accuracy on ImageNet, while being 8.4x smaller
  and 6.1x faster on inference than the best existing ConvNet. Our EfficientNets also
  transfer well and achieve state-of-the-art accuracy on CIFAR-100 (91.7%), Flowers
  (98.8%), and 3 other transfer learning datasets, with an order of magnitude fewer
  parameters. Source code is at https://github.com/tensorflow/tpu/tree/master/models/official/efficientnet.
tags:
- Computer Science - Machine Learning
- Computer Science - Computer Vision and Pattern Recognition
- Statistics - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/1905.11946
---
