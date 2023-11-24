---
title: 'Sphinx: Enabling Privacy-Preserving Online Learning over the Cloud'
authors:
- Han Tian
- Chaoliang Zeng
- Zhenghang Ren
- Di Chai
- Junxue Zhang
- Kai Chen
- Qiang Yang
date: '2022-05-01'
publishDate: '2023-11-24T10:39:00.013724Z'
publication_types:
- paper-conference
publication: '*2022 IEEE Symposium on Security and Privacy (SP)*'
doi: 10.1109/SP46214.2022.9833648
abstract: With the growing complexity of deep learning applications, users have started
  to delegate their data and models to the cloud. Among these applications, online
  learning services, which involve both training and inference procedures, are widely
  deployed. To ensure privacy guarantee on the public cloud, researchers have proposed
  a plethora of privacy-preserving deep learning algorithms with different techniques,
  ranging from obfuscation mechanisms to cryptographic tools. However, none of them
  is applicable to online learning services. They either focus only on inference or
  training procedure while ignoring the other, or require non-colluding or trusted
  third parties. In this paper, we present Sphinx, an efficient and privacy-preserving
  online deep learning system without any trusted third parties. Sphinx strikes a
  balance between model performance, computational efficiency, and privacy preservation
  with systematical optimizations on both private inference and training protocols.
  At its core, Sphinx synthesizes homomorphic encryption and differential privacy
  reciprocally to maintain the model by keeping most of its parameters as plaintexts,
  enabling fast training and inference protocol designs. Meanwhile, by refining the
  homomorphic operation behaviors, Sphinx avoids most of the heavyweight homomorphic
  operations and minimizes the communication cost. As a result, Sphinx is able to
  reduce the training time significantly while achieving real-time inference without
  exposing user privacy. In our experiments, we find that compared to the pure homomorphic
  encryption solution, Sphinx is $^textrm-5$$ for MNIST) without a trusted data aggregator,
  and is more robust against practical reconstruction attacks.
tags:
- Training
- Computational modeling
- Cloud computing
- Deep learning
- Protocols
- Privacy
- Refining
---
