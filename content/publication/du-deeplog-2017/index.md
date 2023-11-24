---
title: 'DeepLog: Anomaly Detection and Diagnosis from System Logs through Deep Learning'
authors:
- Min Du
- Feifei Li
- Guineng Zheng
- Vivek Srikumar
date: '2017-10-01'
publishDate: '2023-11-24T10:38:59.083818Z'
publication_types:
- article-journal
doi: https://doi.org/10.1145/3133956.3134015
abstract: Anomaly detection is a critical step towards building a secure and trustworthy
  system. The primary purpose of a system log is to record system states and significant
  events at various critical points to help debug system failures and perform root
  cause analysis. Such log data is universally available in nearly all computer systems.
  Log data is an important and valuable resource for understanding system status and
  performance issues; therefore, the various system logs are naturally excellent source
  of information for online monitoring and anomaly detection. We propose DeepLog,
  a deep neural network model utilizing Long Short-Term Memory (LSTM), to model a
  system log as a natural language sequence. This allows DeepLog to automatically
  learn log patterns from normal execution, and detect anomalies when log patterns
  deviate from the model trained from log data under normal execution. In addition,
  we demonstrate how to incrementally update the DeepLog model in an online fashion
  so that it can adapt to new log patterns over time. Furthermore, DeepLog constructs
  workflows from the underlying system log so that once an anomaly is detected, users
  can diagnose the detected anomaly and perform root cause analysis effectively. Extensive
  experimental evaluations over large log data have shown that DeepLog has outperformed
  other existing log-based anomaly detection methods based on traditional data mining
  methodologies.
links:
- name: URL
  url: https://dl.acm.org/doi/abs/10.1145/3133956.3134015
---
