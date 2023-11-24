---
title: Deep Learning-Based Stacked Denoising and Autoencoder for ECG Heartbeat Classification
authors:
- Siti Nurmaini
- Annisa Darmawahyuni
- Akhmad Noviar Sakti Mukti
- Muhammad Naufal Rachmatullah
- Firdaus Firdaus
- Bambang Tutuko
date: '2020-01-01'
publishDate: '2023-11-24T10:38:59.069697Z'
publication_types:
- article-journal
doi: 10.3390/electronics9010135
abstract: 'The electrocardiogram (ECG) is a widely used, noninvasive test for analyzing
  arrhythmia. However, the ECG signal is prone to contamination by different kinds
  of noise. Such noise may cause deformation on the ECG heartbeat waveform, leading
  to cardiologists&rsquo; mislabeling or misinterpreting heartbeats due to varying
  types of artifacts and interference. To address this problem, some previous studies
  propose a computerized technique based on machine learning (ML) to distinguish between
  normal and abnormal heartbeats. Unfortunately, ML works on a handcrafted, feature-based
  approach and lacks feature representation. To overcome such drawbacks, deep learning
  (DL) is proposed in the pre-training and fine-tuning phases to produce an automated
  feature representation for multi-class classification of arrhythmia conditions.
  In the pre-training phase, stacked denoising autoencoders (DAEs) and autoencoders
  (AEs) are used for feature learning; in the fine-tuning phase, deep neural networks
  (DNNs) are implemented as a classifier. To the best of our knowledge, this research
  is the first to implement stacked autoencoders by using DAEs and AEs for feature
  learning in DL. Physionet&rsquo;s well-known MIT-BIH Arrhythmia Database, as well
  as the MIT-BIH Noise Stress Test Database (NSTDB). Only four records are used from
  the NSTDB dataset: 118 24 dB, 118 &minus;6 dB, 119 24 dB, and 119 &minus;6 dB, with
  two levels of signal-to-noise ratio (SNRs) at 24 dB and &minus;6 dB. In the validation
  process, six models are compared to select the best DL model. For all fine-tuned
  hyperparameters, the best model of ECG heartbeat classification achieves an accuracy,
  sensitivity, specificity, precision, and F1-score of 99.34%, 93.83%, 99.57%, 89.81%,
  and 91.44%, respectively. As the results demonstrate, the proposed DL model can
  extract high-level features not only from the training data but also from unseen
  data. Such a model has good application prospects in clinical practice.'
tags:
- deep learning
- arrhythmia
- autoencoder
- denoising autoencoder
- heartbeat classification
links:
- name: URL
  url: https://www.mdpi.com/2079-9292/9/1/135
---
