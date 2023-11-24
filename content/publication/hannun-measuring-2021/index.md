---
title: Measuring Data Leakage in Machine-Learning Models with Fisher Information
authors:
- Awni Hannun
- Chuan Guo
- Laurens van der Maaten
date: '2021-08-23'
publishDate: '2023-11-24T10:39:01.229912Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2102.11673
abstract: Machine-learning models contain information about the data they were trained
  on. This information leaks either through the model itself or through predictions
  made by the model. Consequently, when the training data contains sensitive attributes,
  assessing the amount of information leakage is paramount. We propose a method to
  quantify this leakage using the Fisher information of the model about the data.
  Unlike the worst-case a priori guarantees of differential privacy, Fisher information
  loss measures leakage with respect to specific examples, attributes, or sub-populations
  within the dataset. We motivate Fisher information loss through the Craḿer-Rao
  bound and delineate the implied threat model. We provide efficient methods to compute
  Fisher information loss for output-perturbed generalized linear models. Finally,
  we empirically validate Fisher information loss as a useful measure of information
  leakage.
tags:
- Computer Science - Machine Learning
- Computer Science - Cryptography and Security
links:
- name: URL
  url: http://arxiv.org/abs/2102.11673
---
