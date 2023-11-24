---
title: 'SVELTE: Real-time intrusion detection in the Internet of Things'
authors:
- Shahid Raza
- Linus Wallgren
- Thiemo Voigt
date: '2013-11-01'
publishDate: '2023-11-24T10:38:58.832323Z'
publication_types:
- article-journal
doi: 10.1016/j.adhoc.2013.04.014
abstract: In the Internet of Things (IoT), resource-constrained things are connected
  to the unreliable and untrusted Internet via IPv6 and 6LoWPAN networks. Even when
  they are secured with encryption and authentication, these things are exposed both
  to wireless attacks from inside the 6LoWPAN network and from the Internet. Since
  these attacks may succeed, Intrusion Detection Systems (IDS) are necessary. Currently,
  there are no IDSs that meet the requirements of the IPv6-connected IoT since the
  available approaches are either customized for Wireless Sensor Networks (WSN) or
  for the conventional Internet. In this paper we design, implement, and evaluate
  a novel intrusion detection system for the IoT that we call SVELTE. In our implementation
  and evaluation we primarily target routing attacks such as spoofed or altered information,
  sinkhole, and selective-forwarding. However, our approach can be extended to detect
  other attacks. We implement SVELTE in the Contiki OS and thoroughly evaluate it.
  Our evaluation shows that in the simulated scenarios, SVELTE detects all malicious
  nodes that launch our implemented sinkhole and/or selective forwarding attacks.
  However, the true positive rate is not 100%, i.e., we have some false alarms during
  the detection of malicious nodes. Also, SVELTE’s overhead is small enough to deploy
  it on constrained nodes with limited energy and memory capacity.
tags:
- Internet of Things
- Intrusion detection
- Security
- 6LoWPAN
- IPv6
- RPL
- Sensor networks
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S1570870513001005
---
