---
title: 'Asymmetric Asynchronous Byzantine Consensus'
date: 2021-06-08
permalink: /posts/2021/06/asym-consensus/
tags:
  - asymmetric trust
  - consensus
---

An important element of every blockchain network is its protocol for reaching consensus. In traditional, permissioned consensus protocols, all involved processes adhere to a global, symmetric failure model, typically only defined by bounds on the number of faulty processes. More flexible trust assumptions have recently been considered, especially in connection with blockchains. With asymmetric trust, in particular, a process is free to choose which other processes it trusts and which ones might collude against it.

Cachin and Tackmann (OPODIS 2019) introduced asymmetric quorum systems as a generalization of Byzantine quorum systems, which are the key abstraction for realizing consensus in a system with symmetric trust. This paper shows how to realize randomized signature-free asynchronous Byzantine consensus with asymmetric quorums. This results in an optimal consensus protocol with subjective, asymmetric trust and constant expected running time, which is suitable for applications in blockchain networks.

[Blog post](https://cryptobern.github.io/asymconsensus/)

