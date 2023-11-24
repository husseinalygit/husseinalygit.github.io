---
title: 'CryptGPU: Fast Privacy-Preserving Machine Learning on the GPU'
authors:
- Sijun Tan
- Brian Knott
- Yuan Tian
- David J. Wu
date: '2021-05-01'
publishDate: '2023-11-24T10:39:00.044572Z'
publication_types:
- paper-conference
publication: '*2021 IEEE Symposium on Security and Privacy (SP)*'
doi: 10.1109/SP40001.2021.00098
abstract: We introduce CryptGPU, a system for privacy-preserving machine learning
  that implements all operations on the GPU (graphics processing unit). Just as GPUs
  played a pivotal role in the success of modern deep learning, they are also essential
  for realizing scalable privacy-preserving deep learning. In this work, we start
  by introducing a new interface to losslessly embed cryptographic operations over
  secret-shared values (in a discrete domain) into floating-point operations that
  can be processed by highly-optimized CUDA kernels for linear algebra. We then identify
  a sequence of \"GPU-friendly\" cryptographic protocols to enable privacy-preserving
  evaluation of both linear and non-linear operations on the GPU. Our microbenchmarks
  indicate that our private GPU-based convolution protocol is over 150× faster than
  the analogous CPU-based protocol; for non-linear operations like the ReLU activation
  function, our GPU-based protocol is around 10× faster than its CPU analog. With
  CryptGPU, we support private inference and training on convolutional neural networks
  with over 60 million parameters as well as handle large datasets like ImageNet.
  Compared to the previous state-of-the-art, our protocols achieve a 2× to 8× improvement
  in private inference for large networks and datasets. For private training, we achieve
  a 6× to 36× improvement over prior state-of-the-art. Our work not only showcases
  the viability of performing secure multiparty computation (MPC) entirely on the
  GPU to newly enable fast privacy-preserving machine learning, but also highlights
  the importance of designing new MPC primitives that can take full advantage of the
  GPU’s computing capabilities.
tags:
- Training
- Deep learning
- Cryptography
- Privacy
- machine-learning
- GPU
- Graphics processing units
- Linear algebra
- multi-party-computation
- privacy
- Systematics
---
