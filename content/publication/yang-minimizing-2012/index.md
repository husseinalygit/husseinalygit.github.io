---
title: Minimizing private data disclosures in the smart grid
authors:
- Weining Yang
- Ninghui Li
- Yuan Qi
- Wahbeh Qardaji
- Stephen McLaughlin
- Patrick McDaniel
date: '2012-10-16'
publishDate: '2023-11-24T10:39:01.783767Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 2012 ACM conference on Computer and communications
  security*'
doi: 10.1145/2382196.2382242
abstract: Smart electric meters pose a substantial threat to the privacy of individuals
  in their own homes. Combined with non-intrusive load monitors, smart meter data
  can reveal precise home appliance usage information. An emerging solution to behavior
  leakage in smart meter measurement data is the use of battery-based load hiding.
  In this approach, a battery is used to store and supply power to home devices at
  strategic times to hide appliance loads from smart meters. A few such battery control
  algorithms have already been studied in the literature, but none have been evaluated
  from an adversarial point of view. In this paper, we first consider two well known
  battery privacy algorithms, Best Effort (BE) and Non-Intrusive Load Leveling (NILL),
  and demonstrate attacks that recover precise load change information, which can
  be used to recover appliance behavior information, under both algorithms. We then
  introduce a stepping approach to battery privacy algorithms that fundamentally differs
  from previous approaches by maximizing the error between the load demanded by a
  home and the external load seen by a smart meter. By design, precise load change
  recovery attacks are impossible. We also propose mutual-information based measurements
  to evaluate the privacy of different algorithms. We implement and evaluate four
  novel algorithms using the stepping approach, and show that under the mutual-information
  metrics they outperform BE and NILL.
tags:
- privacy
- smart meter
- load monitor
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/2382196.2382242
---
