---
title: 'DiabDeep: Pervasive Diabetes Diagnosis based on Wearable Medical Sensors and
  Efficient Neural Networks'
authors:
- Hongxu Yin
- Bilal Mukadam
- Xiaoliang Dai
- N.K. Jha
date: '2019-12-17'
publishDate: '2023-11-24T10:38:57.736353Z'
publication_types:
- article-journal
doi: 10.1109/TETC.2019.2958946
abstract: 'Diabetes impacts the quality of life of millions of people around the globe.
  However, diabetes diagnosis is still an arduous process, given that this disease
  develops and gets treated outside the clinic. The emergence of wearable medical
  sensors (WMSs) and machine learning points to a potential way forward to address
  this challenge. WMSs enable a continuous, yet user-transparent, mechanism to collect
  and analyze physiological signals. However, disease diagnosis based on WMS data
  and its effective deployment on resource-constrained edge devices remain challenging
  due to inefficient feature extraction and vast computation cost. To address these
  problems, we propose a framework called DiabDeep that combines efficient neural
  networks (called DiabNNs) with off-the-shelf WMSs for pervasive diabetes diagnosis.
  DiabDeep bypasses the feature extraction stage and acts directly on WMS data. It
  enables both an (i) accurate inference on the server, e.g., a desktop, and (ii)
  efficient inference on an edge device, e.g., a smartphone, to obtain a balance between
  accuracy and efficiency based on varying resource budgets and design goals. On the
  resource-rich server, we stack sparsely connected layers to deliver high accuracy.
  On the resource-scarce edge device, we use a hidden-layer long short-term memory
  based recurrent layer to substantially cut down on computation and storage costs
  while incurring only a minor accuracy loss. At the core of our system lies a grow-and-prune
  training flow: it leverages gradient-based growth and magnitude-based pruning algorithms
  to enable DiabNNs to learn both weights and connections, while improving accuracy
  and efficiency. We demonstrate the effectiveness of DiabDeep through a detailed
  analysis of data collected from 52 participants. For server (edge) side inference,
  we achieve a 96.3% (95.3%) accuracy in classifying diabetics against healthy individuals,
  and a 95.7% (94.6%) accuracy in distinguishing among type-1 diabetic, type-2 diabetic,
  and healthy individuals. Against conventional baselines, such as support vector
  machines with linear and radial basis function kernels, k-nearest neighbor, random
  forest, and linear ridge classifiers, DiabNNs achieve higher accuracy, while reducing
  the model size (floating-point operations) by up to  $454.5 times (8.9times)$ .
  Therefore, the system can be viewed as pervasive and efficient, yet very accurate.'
tags:
- to-read
---
