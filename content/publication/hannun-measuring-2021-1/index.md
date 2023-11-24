---
title: Measuring data leakage in machine-learning models with Fisher information
authors:
- Awni Hannun
- Chuan Guo
- Laurens van der Maaten
date: '2021-12-01'
publishDate: '2023-11-24T10:39:01.244880Z'
publication_types:
- paper-conference
publication: '*Proceedings of the Thirty-Seventh Conference on Uncertainty in Artificial
  Intelligence*'
abstract: Machine-learning models contain information about the data they were trained
  on. This information leaks either through the model itself or through predictions
  made by the model. Consequently, when the training data contains sensitive attributes,
  assessing the amount of information leakage is paramount. We propose a method to
  quantify this leakage using the Fisher information of the model about the data.
  Unlike the worst-case a priori guarantees of differential privacy, Fisher information
  loss measures leakage with respect to specific examples, attributes, or sub-populations
  within the dataset. We motivate Fisher information loss through the Cram’er-Rao
  bound and delineate the implied threat model. We provide efficient methods to compute
  Fisher information loss for output-perturbed generalized linear models. Finally,
  we empirically validate Fisher information loss as a useful measure of information
  leakage.
links:
- name: URL
  url: https://proceedings.mlr.press/v161/hannun21a.html
---
