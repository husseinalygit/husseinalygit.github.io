---
title: Traceable Ring Signature
authors:
- Eiichiro Fujisaki
- Koutarou Suzuki
date: '2006-01-01'
publishDate: '2023-11-24T10:38:58.597006Z'
publication_types:
- report
abstract: "The ring signature allows a signer to leak secrets anonymously, without
  the risk of identity escrow. At the same time, the ring signature provides great
  flexibility: No group manager, no special setup, and the dynamics of group choice.
  The ring signature is, however, vulnerable to malicious or irresponsible signers
  in some applications, because of its anonymity. In this paper, we propose a traceable
  ring signature scheme. A traceable ring scheme is a ring signature except that it
  can restrict ``excessive'' anonymity. The traceable ring signature has a tag that
  consists of a list of ring members and an issue that refers to, for instance, a
  social affair or an election. A ring member can make any signed but anonymous opinion
  regarding the issue, but only once (per tag). If the member submits another signed
  opinion, possibly pretending to be another person who supports the first opinion,
  the identity of the member is immediately revealed. If the member submits the same
  opinion, for instance, voting ``yes'' regarding the same issue twice, everyone can
  see that these two are linked. The traceable ring signature can suit to many applications,
  such as an anonymous voting on a BBS, a dishonest whistle-blower problem, and unclonable
  group identification. We formalize the security definitions for this primitive and
  show an efficient and simple construction."
tags:
- cryptographic protocols
links:
- name: URL
  url: https://eprint.iacr.org/2006/389
---
