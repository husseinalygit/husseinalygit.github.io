---
title: You Can Backdoor Personalized Federated Learning
authors:
- Tiandi Ye
- Cen Chen
- Yinggui Wang
- Xiang Li
- Ming Gao
date: '2023-07-29'
publishDate: '2023-11-24T10:39:01.615423Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2307.15971
abstract: 'Backdoor attacks pose a significant threat to the security of federated
  learning systems. However, existing research primarily focuses on backdoor attacks
  and defenses within the generic FL scenario, where all clients collaborate to train
  a single global model. i̧tetqin2023revisiting conduct the first study of backdoor
  attacks in the personalized federated learning (pFL) scenario, where each client
  constructs a personalized model based on its local data. Notably, the study demonstrates
  that pFL methods with partial model-sharing can significantly boost robustness against
  backdoor attacks. In this paper, we whistleblow that pFL methods with partial model-sharing
  are still vulnerable to backdoor attacks in the absence of any defense. We propose
  three backdoor attack methods: BapFL, BapFL+, and Gen-BapFL, and we empirically
  demonstrate that they can effectively attack the pFL methods. Specifically, the
  key principle of BapFL lies in maintaining clean local parameters while implanting
  the backdoor into the global parameters. BapFL+ generalizes the attack success to
  benign clients by introducing Gaussian noise to the local parameters. Furthermore,
  we assume the collaboration of malicious clients and propose Gen-BapFL, which leverages
  meta-learning techniques to further enhances attack generalization. We evaluate
  our proposed attack methods against two classic pFL methods with partial model-sharing,
  FedPer and LG-FedAvg. Extensive experiments on four FL benchmark datasets demonstrate
  the effectiveness of our proposed attack methods. Additionally, we assess the defense
  efficacy of various defense strategies against our proposed attacks and find that
  Gradient Norm-Clipping is particularly effective. It is crucial to note that pFL
  method is not always secure in the presence of backdoor attacks, and we hope to
  inspire further research on attack and defense in pFL scenarios.'
tags:
- Computer Science - Artificial Intelligence
- Computer Science - Cryptography and Security
links:
- name: URL
  url: http://arxiv.org/abs/2307.15971
---
