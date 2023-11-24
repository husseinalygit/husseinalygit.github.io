---
title: 'No Need to Teach New Tricks to Old Malware: Winning an Evasion Challenge with
  XOR-based Adversarial Samples'
authors:
- Fabricio Ceschin
- Marcus Botacin
- Gabriel Lüders
- Heitor Murilo Gomes
- Luiz Oliveira
- Andre Gregio
date: '2021-04-27'
publishDate: '2023-11-24T10:39:00.386271Z'
publication_types:
- paper-conference
publication: '*Reversing and Offensive-oriented Trends Symposium*'
doi: 10.1145/3433667.3433669
abstract: 'Adversarial attacks to Machine Learning (ML) models became such a concern
  that tech companies (Microsoft and CUJO AI’s Vulnerability Research Lab) decided
  to launch contests to better understand their impact on practice. During the contest’s
  first edition (2019), participating teams were challenged to bypass three ML models
  in a white box manner. Our team bypassed all the three of them and reported interesting
  insights about models’ weaknesses. In the second edition (2020), the challenge evolved
  to an attack-and-defense model: the teams should either propose defensive models
  and attack other teams’ models in a black box manner. Despite the difficulty increase,
  our team was able to bypass all models again. In this paper, we describe our insights
  for this year’s contest regarding on attacking models, as well defending them from
  adversarial attacks. In particular, we show how frequency-based models (e.g., TF-IDF)
  are vulnerable to the addition of dead function imports, and how models based on
  raw bytes are vulnerable to payload-embedding obfuscation (e.g., XOR and base64
  encoding).'
tags:
- machine learning
- adversarial malware
- malware detection
links:
- name: URL
  url: https://doi.org/10.1145/3433667.3433669
---
