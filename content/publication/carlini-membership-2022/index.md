---
title: Membership Inference Attacks From First Principles
authors:
- Nicholas Carlini
- Steve Chien
- Milad Nasr
- Shuang Song
- Andreas Terzis
- Florian Tramer
date: '2022-04-12'
publishDate: '2023-11-24T10:39:01.908130Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2112.03570
abstract: A membership inference attack allows an adversary to query a trained machine
  learning model to predict whether or not a particular example was contained in the
  model's training dataset. These attacks are currently evaluated using average-case
  \"accuracy\" metrics that fail to characterize whether the attack can confidently
  identify any members of the training set. We argue that attacks should instead be
  evaluated by computing their true-positive rate at low (e.g., textless0.1%) false-positive
  rates, and find most prior attacks perform poorly when evaluated in this way. To
  address this we develop a Likelihood Ratio Attack (LiRA) that carefully combines
  multiple ideas from the literature. Our attack is 10x more powerful at low false-positive
  rates, and also strictly dominates prior attacks on existing metrics.
tags:
- Computer Science - Machine Learning
- Computer Science - Cryptography and Security
links:
- name: URL
  url: http://arxiv.org/abs/2112.03570
---
