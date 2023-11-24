---
title: 'Forward Thinking: Building and Training Neural Networks One Layer at a Time'
authors:
- Chris Hettinger
- Tanner Christensen
- Ben Ehlert
- Jeffrey Humpherys
- Tyler Jarvis
- Sean Wade
date: '2017-06-08'
publishDate: '2023-11-24T10:39:01.061378Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.1706.02480
abstract: We present a general framework for training deep neural networks without
  backpropagation. This substantially decreases training time and also allows for
  construction of deep networks with many sorts of learners, including networks whose
  layers are defined by functions that are not easily differentiated, like decision
  trees. The main idea is that layers can be trained one at a time, and once they
  are trained, the input data are mapped forward through the layer to create a new
  learning problem. The process is repeated, transforming the data through multiple
  layers, one at a time, rendering a new data set, which is expected to be better
  behaved, and on which a final output layer can achieve good performance. We call
  this forward thinking and demonstrate a proof of concept by achieving state-of-the-art
  accuracy on the MNIST dataset for convolutional neural networks. We also provide
  a general mathematical formulation of forward thinking that allows for other types
  of deep learning problems to be considered.
tags:
- Computer Science - Machine Learning
- Statistics - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/1706.02480
---
