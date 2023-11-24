---
title: 'FedDetect: A Novel Privacy-Preserving Federated Learning Framework for Energy
  Theft Detection in Smart Grid'
authors:
- Mi Wen
- Rong Xie
- Kejie Lu
- Liangliang Wang
- Kai Zhang
date: '2022-04-01'
publishDate: '2023-11-24T10:38:59.991725Z'
publication_types:
- article-journal
doi: 10.1109/JIOT.2021.3110784
abstract: In smart grids, a major challenge is how to effectively utilize consumers’
  energy consumption data while preserving security and privacy. In this article,
  we tackle this challenging issue and focus on energy theft detection, which is very
  important for smart grids. Specifically, we note that most existing energy theft
  detection schemes are centralized, which may be unscalable, and more importantly,
  may be very difficult to protect data privacy. To address this issue, we propose
  a novel privacy-preserving federated learning framework for energy theft detection,
  namely, FedDetect. In our framework, we consider a federated learning system that
  consists of a data center (DC), a control center (CC), and multiple detection stations.
  In this system, each detection station (DTS) can only observe data from local consumers,
  which can use a local differential privacy (LDP) scheme to process their data to
  preserve privacy. To facilitate the training of the model, we design a secure protocol
  so that detection stations can send encrypted training parameters to the CC and
  the DC, which then use homomorphic encryption to calculate the aggregated parameters
  and return updated model parameters to detection stations. In our study, we prove
  the security of the proposed protocol with solid security analysis. To detect energy
  theft, we design a deep learning model based on the state-of-the-art temporal convolutional
  network (TCN). Finally, we conduct extensive data-driven experiments using a real-energy
  consumption data set. The experimental results demonstrate that the proposed federated
  learning framework can achieve high accuracy of detection with a smaller computation
  overhead.
tags:
- Data models
- Security
- Energy consumption
- Privacy
- Collaborative work
- Data privacy
- Energy theft detection
- federated learning
- privacy protection
- smart grid
- Smart grids
- temporal convolutional network (TCN)
---
