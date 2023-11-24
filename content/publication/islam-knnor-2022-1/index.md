---
title: 'KNNOR: An oversampling technique for imbalanced datasets'
authors:
- Ashhadul Islam
- Samir Brahim Belhaouari
- Atiq Ur Rehman
- Halima Bensmail
date: '2022-01-01'
publishDate: '2023-11-24T10:38:59.352138Z'
publication_types:
- article-journal
doi: 10.1016/j.asoc.2021.108288
abstract: Predictive performance of Machine Learning (ML) models rely on the quality
  of data used for training the models. However, if the training data is not balanced
  among different classes, the performance of ML models deteriorate heavily. Several
  techniques have been proposed in the literature to add some semblance of balance
  to the data sets by adding artificial data points. Synthetic Minority Oversampling
  Technique(SMOTE) and Adaptive Synthetic Sampling(ADASYN) are some of the commonly
  used techniques to deal with class imbalance. However, these approaches are prone
  to ‘within class imbalance’ and ‘small disjunct problem’. To overcome these problems,
  this article proposes an advanced algorithm by studying the compactness and location
  of the minority class relative to other classes. The proposed technique called K-Nearest
  Neighbor OveRsampling approach (KNNOR) performs a three step process to identify
  the critical and safe areas for augmentation and generate synthetic data points
  of the minority class. The relative density of the entire population is considered
  while generating artificial points. This enables the proposed KNNOR approach to
  oversample the minority class more reliably and at the same time stay resilient
  against noise. The proposed method is compared with the ten top performing contemporary
  oversamplers by testing the accuracy of classifiers trained on augmented data provided
  by each oversampler. The experimental results on several common imbalanced datasets
  show that our method ranks first more consistently than the other state-of-art oversamplers.
  The proposed method is easy to use and has been made open source as a python library.
tags:
- Machine learning
- Data augmentation
- Imbalanced data
- Nearest neighbor
- Support Vector Machines
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S1568494621010942
---
