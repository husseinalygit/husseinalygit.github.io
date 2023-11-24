---
title: 'PiNcH: An effective, efficient, and robust solution to drone detection via
  network traffic analysis'
authors:
- Savio Sciancalepore
- Omar Adel Ibrahim
- Gabriele Oligeri
- Roberto Di Pietro
date: '2020-02-26'
publishDate: '2023-11-24T10:38:58.253879Z'
publication_types:
- article-journal
doi: 10.1016/j.comnet.2019.107044
abstract: 'We propose Picking a Needle in a Haystack (PiNcH), a methodology to detect
  the presence of a drone, its current status, and its movements by leveraging just
  the communication traffic exchanged between the drone and its Remote Controller
  (RC). PiNcH is built applying standard classification algorithms to the eavesdropped
  traffic, analyzing features such as packets inter-arrival time and size. PiNcH is
  fully passive and it requires just cheap and general-purpose hardware. To evaluate
  the effectiveness of our solution, we collected real communication traces originated
  by a drone running the widespread ArduCopter open-source firmware, currently mounted
  on-board of a wide range (30+) of commercial amateur drones. Then, we tested our
  solution against different publicly available wireless traces. The results prove
  that PiNcH can efficiently and effectively: (i) identify the presence of the drone
  in several heterogeneous scenarios; (ii) identify the current state of a powered-on
  drone, i.e., flying or lying on the ground; (iii) discriminate the movements of
  the drone; and, finally, (iv) enjoy a reduced upper bound on the time required to
  identify a drone with the requested level of assurance. The effectiveness of PiNcH
  has been also evaluated in the presence of both heavy packet loss and evasion attacks.
  In this latter case, the adversary modifies on purpose the profile of the traffic
  of the drone-RC link to avoid the detection. In both the cited cases, PiNcH continues
  enjoying a remarkable performance. Further, the comparison against state of the
  art solution confirms the superior performance of PiNcH in several scenarios. Note
  that all the drone-controller generated data traces have been released as open-source,
  to allow replicability and foster follow-up. Finally, the quality and viability
  of our solution, do prove that network traffic analysis can be successfully adopted
  for drone identification and status discrimination, and pave the way for future
  research in the area.'
tags:
- Drones detection
- Intrusion detection
- RF Passive detection
- Unmanned aerial vehicles
links:
- name: URL
  url: http://www.sciencedirect.com/science/article/pii/S1389128619311764
---
