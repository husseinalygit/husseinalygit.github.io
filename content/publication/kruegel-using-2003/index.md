---
title: Using Decision Trees to Improve Signature-Based Intrusion Detection
authors:
- Christopher Kruegel
- Thomas Toth
date: '2003-01-01'
publishDate: '2023-11-24T10:38:58.269498Z'
publication_types:
- paper-conference
publication: '*Recent Advances in Intrusion Detection*'
doi: 10.1007/978-3-540-45248-5_10
abstract: Most deployed intrusion detection systems (IDSs) follow a signature-based
  approach where attacks are identified by matching each input event against predefined
  signatures that model malicious activity. This matching process accounts for the
  most resource intensive task of an IDS. Many systems perform the matching by comparing
  each input event to all rules sequentially. This is far from being optimal. Although
  sometimes ad-hoc optimizations are utilized, no general solution to this problem
  has been proposed so far.This paper describes an approach where machine learning
  clustering techniques are applied to improve the matching process. Given a set of
  signatures (each dictating a number of constraints the input data must fulfill to
  trigger it) an algorithm generates a decision tree that is used to find malicious
  events using as few redundant comparisons as possible.This general idea has been
  applied to a network-based IDS. In particular, a system has been implemented that
  replaces the detection engine of Snort [14,16]. Experimental evaluation shows that
  the speed of the detection process has been significantly improved, even compared
  to Snort’s recently released, fully revised detection engine.
tags:
- Machine Learning
- Network Security
- Signature-based Intrusion Detection
---
