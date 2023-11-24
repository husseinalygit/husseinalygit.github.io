---
title: A Closer Look at Branch Classifiers of Multi-exit Architectures
authors:
- Shaohui Lin
- Bo Ji
- Rongrong Ji
- Angela Yao
date: '2022-07-13'
publishDate: '2023-11-24T10:39:01.215547Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2204.13347
abstract: Multi-exit architectures consist of a backbone and branch classifiers that
  offer shortened inference pathways to reduce the run-time of deep neural networks.
  In this paper, we analyze different branching patterns that vary in their allocation
  of computational complexity for the branch classifiers. Constant-complexity branching
  keeps all branches the same, while complexity-increasing and complexity-decreasing
  branching place more complex branches later or earlier in the backbone respectively.
  Through extensive experimentation on multiple backbones and datasets, we find that
  complexity-decreasing branches are more effective than constant-complexity or complexity-increasing
  branches, which achieve the best accuracy-cost trade-off. We investigate a cause
  by using knowledge consistency to probe the effect of adding branches onto a backbone.
  Our findings show that complexity-decreasing branching yields the least disruption
  to the feature abstraction hierarchy of the backbone, which explains the effectiveness
  of the branching patterns.
tags:
- Computer Science - Computer Vision and Pattern Recognition
links:
- name: URL
  url: http://arxiv.org/abs/2204.13347
---
