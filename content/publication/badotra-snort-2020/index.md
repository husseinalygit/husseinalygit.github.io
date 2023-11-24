---
title: SNORT based early DDoS detection system using Opendaylight and open networking
  operating system in software defined networking
authors:
- Sumit Badotra
- Surya Narayan Panda
date: '2020-05-29'
publishDate: '2023-11-24T10:38:58.556002Z'
publication_types:
- article-journal
doi: 10.1007/s10586-020-03133-y
abstract: Software-defined networking (SDN) is an approach in the network that provides
  many advantages with the help of separating the intelligence of the network (controller)
  with the underlying network infrastructure (data plane). But this isolation also
  gives birth to many security concerns; therefore, the need to protect the network
  from various attacks is becoming mandatory. Distributed Denial of Service (DDoS)
  in SDN is one such attack that is becoming a hurdle to its growth. Before the mitigation
  of DDoS attacks, the primary step is to detect them. In this paper, an early DDoS
  detection tool is created by using SNORT IDS (Intrusion Detection System). This
  tool is integrated with popularly used SDN controllers (Opendaylight and Open Networking
  Operating System). For the experimental setup, five different network scenarios
  are considered. In each scenario number of hosts, switches and data packets vary.
  For the creation of different hosts, switches the Mininet emulation tool is used
  whereas for generating the data packets four different penetration tools such as
  Hping3, Nping, Xerxes, Tor Hammer, LOIC are used. The generated data packets are
  ranging from (50,000 per second–2,50,000 per second) and the number of hosts/switches
  are ranging from (50–250) in every scenario respectively. The data traffic is bombarded
  towards the controllers and the evaluation of these packets is achieved by making
  use of Wireshark. The analysis of our DDoS detection system is performed on the
  basis of various parameters such as time to detect the DDoS attack, Round Trip Time
  (RTT), percentage of packet loss and type of DDoS attack. It is found that ODL takes
  minimum time to detect the successful DDoS attack and more time to go down than
  ONOS. Our tool ensures the timely detection of fast DDoS attacks which delivers
  the better performance of the SDN controller and not compromising the overall functionality
  of the entire network.
links:
- name: URL
  url: https://doi.org/10.1007/s10586-020-03133-y
---
