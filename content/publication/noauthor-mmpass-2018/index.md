---
title: 'mmPass: Human Body-based User Authentication Leveraging mmWave Signals in
  Open-World Scenarios'
date: '2018-01-01'
publishDate: '2023-11-24T10:39:01.363929Z'
publication_types:
- article-journal
abstract: User authentication is undergoing an expansion of application scenarios
  and innovation of technical methods nowadays. Existing user authentication approaches
  generally rely on biometrics, such as fingerprint, face recognition, iris recognition,
  etc., which may face the threat of replay attacks and the decline of user experience
  in extensive Internet of Things (IoT) environments. New approaches exploit radio
  frequency (RF) signals, e.g., mmWave signals, to sense human characteristics and
  extract individual uniqueness for user authentication, providing a contactless and
  nonintrusive manner that naturally defends against replay attacks. However, current
  RF signal-based approaches are confronted with constraint usage scenarios and have
  difficulties implementing user authentication in open-world scenarios. The open-world
  scenarios refer to dynamic background environments, various human poses and the
  presence of unauthorized users, which are reflections of practical and real usage
  cases of user authentication. In this paper, we present an open-world user authentication
  system, mmPass, which leverages a commercial off-the-shelf (COTS) mmWave radar to
  sense human bodies for identifying individuals. In mmPass, we first utilize a MUSIC-based
  neural network imaging model to eliminate environmental clutter and generate environment-independent
  human silhouette images for fine-grained feature extraction. Then, human bodies
  are modeled as topological structures to perform posture normalization, ensuring
  robustness against diverse human postures. Next, mmPass extracts body features through
  a metric learning model, and synthesizes data placeholders for a better generalization
  to unauthorized users. Finally, a k-NN-based authentication model is constructed
  based on the extracted body features to authenticate users’ identities. Experiments
  in real environments show that the proposed mmPass achieves an average authentication
  accuracy of 93.4% and FAR of 2.3% in open-world scenarios.
---
