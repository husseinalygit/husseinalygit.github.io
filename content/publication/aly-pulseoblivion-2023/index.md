---
title: 'PulseOblivion: An Effective Session-Based Continuous Authentication Scheme
  Using PPG Signals'
authors:
- Hussein A Aly
- Roberto Di Pietro
date: '2023-01-01'
publishDate: '2023-11-24T11:33:23.957529Z'
publication_types:
- article-journal
abstract: In this paper, we propose a novel session-based continuous authentication model using photoplethysmography (PPG). Unlike previous PPG-based authentication techniques that generate user signatures only during the initial interaction, our session-based approach tackles inter session PPG drifting by generating a user signature at the start of each session. Our model is composed by two modules. Firstly, heavy deep autoencoders (AE) are utilized for feature extraction and, secondly, a lightweight Local Outlier Factor (LOF) is employed for user authentication.Additionally, we introduce a continuous updating system for the LOF model, which automatically recovers from security breaches and can enhance authentication accuracy by more than 9%. Our experiments show that in a single-session scenario, our model achieves authentication accuracies of 93.5% and 91.8% on the CapnoBase and BIMDC benchmarking datasets, respectively, outperforming the state-of-the-art baseline model by 3.2% and 1.6% on both datasets, respectively. In multiple-session scenarios, our scheme attains an authentication accuracy of 95% when tested on the BioSec2 dataset, effectively mitigating inter-session PPG drifting and achieving an advantage of more than 8.5% in authentication accuracy over the state-of-the-art method. In terms of execution speed, our solution is seven times faster at runtime compared to competing state-of-the-art solutions.
doi: https://doi.org/10.1109/ACCESS.2023.3329993
---
