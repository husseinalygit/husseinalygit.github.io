---
title: Over-sampling algorithm for imbalanced data classification
authors:
- Xu Xiaolong
- Chen Wen
- Sun Yanfei
date: '2019-12-01'
publishDate: '2023-11-24T10:38:59.295747Z'
publication_types:
- article-journal
doi: 10.21629/JSEE.2019.06.12
abstract: For imbalanced datasets, the focus of classification is to identify samples
  of the minority class. The performance of current data mining algorithms is not
  good enough for processing imbalanced datasets. The synthetic minority over-sampling
  technique (SMOTE) is specifically designed for learning from imbalanced datasets,
  generating synthetic minority class examples by interpolating between minority class
  examples nearby. However, the SMOTE encounters the overgeneralization problem. The
  densitybased spatial clustering of applications with noise (DBSCAN) is not rigorous
  when dealing with the samples near the borderline. We optimize the DBSCAN algorithm
  for this problem to make clustering more reasonable. This paper integrates the optimized
  DBSCAN and SMOTE, and proposes a density-based synthetic minority over-sampling
  technique (DSMOTE). First, the optimized DBSCAN is used to divide the samples of
  the minority class into three groups, including core samples, borderline samples
  and noise samples, and then the noise samples of minority class is removed to synthesize
  more effective samples. In order to make full use of the information of core samples
  and borderline samples, different strategies are used to over-sample core samples
  and borderline samples. Experiments show that DSMOTE can achieve better results
  compared with SMOTE and Borderline-SMOTE in terms of precision, recall and F-value.
tags:
- Intrusion detection
- Clustering algorithms
- Data mining
- Boosting
- density-based spatial clustering of applications with noise (DBSCAN)
- imbalanced data
- over-sampling
- Sun
- synthetic minority over-sampling technique (SMOTE)
- Systems engineering and theory
- Telecommunications
---
