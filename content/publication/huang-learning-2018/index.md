---
title: Learning Deep ResNet Blocks Sequentially using Boosting Theory
authors:
- Furong Huang
- Jordan Ash
- John Langford
- Robert Schapire
date: '2018-07-03'
publishDate: '2023-11-24T10:39:01.104883Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 35th International Conference on Machine Learning*'
abstract: We prove a multi-channel telescoping sum boosting theory for the ResNet
  architectures which simultaneously creates a new technique for boosting over features
  (in contrast with labels) and provides a new algorithm for ResNet-style architectures.
  Our proposed training algorithm, BoostResNet, is particularly suitable in non-differentiable
  architectures. Our method only requires the relatively inexpensive sequential training
  of TTT “shallow ResNets”. We prove that the training error decays exponentially
  with the depth TTT if the weak module classifiers that we train perform slightly
  better than some weak baseline. In other words, we propose a weak learning condition
  and prove a boosting theory for ResNet under the weak learning condition. A generalization
  error bound based on margin theory is proved and suggests that ResNet could be resistant
  to overfitting using a network with l1l1l_1 norm bounded weights.
links:
- name: URL
  url: https://proceedings.mlr.press/v80/huang18b.html
---
