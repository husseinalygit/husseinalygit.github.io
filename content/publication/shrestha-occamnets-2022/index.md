---
title: 'OccamNets: Mitigating Dataset Bias by Favoring Simpler Hypotheses'
authors:
- Robik Shrestha
- Kushal Kafle
- Christopher Kanan
date: '2022-07-12'
publishDate: '2023-11-24T10:39:01.200285Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2204.02426
abstract: 'Dataset bias and spurious correlations can significantly impair generalization
  in deep neural networks. Many prior efforts have addressed this problem using either
  alternative loss functions or sampling strategies that focus on rare patterns. We
  propose a new direction: modifying the network architecture to impose inductive
  biases that make the network robust to dataset bias. Specifically, we propose OccamNets,
  which are biased to favor simpler solutions by design. OccamNets have two inductive
  biases. First, they are biased to use as little network depth as needed for an individual
  example. Second, they are biased toward using fewer image locations for prediction.
  While OccamNets are biased toward simpler hypotheses, they can learn more complex
  hypotheses if necessary. In experiments, OccamNets outperform or rival state-of-the-art
  methods run on architectures that do not incorporate these inductive biases. Furthermore,
  we demonstrate that when the state-of-the-art debiasing methods are combined with
  OccamNets results further improve.'
tags:
- Computer Science - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2204.02426
---
