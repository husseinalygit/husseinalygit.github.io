---
title: 'Anticipate, Ensemble and Prune: Improving Convolutional Neural Networks via
  Aggregated Early Exits'
authors:
- Simone Sarti
- Eugenio Lomurno
- Matteo Matteucci
date: '2023-01-28'
publishDate: '2023-11-24T10:39:01.178688Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2301.12168
abstract: Today, artificial neural networks are the state of the art for solving a
  variety of complex tasks, especially in image classification. Such architectures
  consist of a sequence of stacked layers with the aim of extracting useful information
  and having it processed by a classifier to make accurate predictions. However, intermediate
  information within such models is often left unused. In other cases, such as in
  edge computing contexts, these architectures are divided into multiple partitions
  that are made functional by including early exits, i.e. intermediate classifiers,
  with the goal of reducing the computational and temporal load without extremely
  compromising the accuracy of the classifications. In this paper, we present Anticipate,
  Ensemble and Prune (AEP), a new training technique based on weighted ensembles of
  early exits, which aims at exploiting the information in the structure of networks
  to maximise their performance. Through a comprehensive set of experiments, we show
  how the use of this approach can yield average accuracy improvements of up to 15%
  over traditional training. In its hybrid-weighted configuration, AEP's internal
  pruning operation also allows reducing the number of parameters by up to 41%, lowering
  the number of multiplications and additions by 18% and the latency time to make
  inference by 16%. By using AEP, it is also possible to learn weights that allow
  early exits to achieve better accuracy values than those obtained from single-output
  reference models.
tags:
- Computer Science - Machine Learning
- Computer Science - Computer Vision and Pattern Recognition
- Computer Science - Artificial Intelligence
links:
- name: URL
  url: http://arxiv.org/abs/2301.12168
---
