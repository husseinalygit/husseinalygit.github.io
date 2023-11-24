---
title: 'Network traffic analysis through node behaviour classification: a graph-based
  approach with temporal dissection and data-level preprocessing'
authors:
- F. Zola
- L. Segurola-Gil
- J. L. Bruse
- M. Galar
- R. Orduna-Urrutia
date: '2022-04-01'
publishDate: '2023-11-24T10:39:00.803995Z'
publication_types:
- article-journal
doi: 10.1016/j.cose.2022.102632
abstract: 'Network traffic analysis is an important cybersecurity task, which helps
  to classify anomalous, potentially dangerous connections. In many cases, it is critical
  not only to detect individual malicious connections, but to detect which node in
  a network has generated malicious traffic so that appropriate actions can be taken
  to reduce the threat and increase the system’s cybersecurity. Instead of analysing
  connections only, node behavioural analysis can be performed by exploiting the graph
  information encoded in a connection network. Network traffic, however, is temporal
  data and extracting graph information without a fixed time scope may only unveil
  macro-dynamics that are less related to cybersecurity threats. To address these
  issues, a threefold approach is proposed here: firstly, temporal dissection for
  extracting graph-based information is applied. As the resulting graphs are typically
  affected by class imbalance (i.e. malicious nodes are under-represented), two novel
  graph data-level preprocessing techniques - R-hybrid and SM-hybrid - are introduced,
  which focus on exploiting the most relevant graph substructures. Finally, a Neural
  Network (NN) and two Graph Convolutional Network (GCN) approaches are compared when
  performing node behaviour classification. Furthermore, we compare the node classification
  performance of these supervised models with traditional unsupervised anomaly detection
  techniques. Results show that temporal dissection parameters affected classification
  performance, while the data-level preprocessing strategies reduced class imbalance
  and led to improved supervised node behaviour classification, outperforming anomaly
  detection models. In particular, Neural Network (NN) outperformed Graph Convolutional
  Network (GCN) approaches for two attack families and was less affected by class
  imbalance, yet one GCN performed best overall. The presented study successfully
  applies a temporal graph-based approach for malicious actor detection in network
  traffic data.'
tags:
- Deep Learning
- Graph Convolutional Networks
- Graph imbalance problem
- Network analysis
- Temporal dissection
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0167404822000311
---
