---
title: 'Quorum systems in permissionless networks'
date: 2022-11-12
permalink: /posts/2022/11/permissionless-quorums/
tags:
  - permissionless quorums
  - asymmetric trust
  - stellar protocol
---

Fail-prone systems, and their quorum systems, are useful tools for the design of distributed algorithms. However, fail-prone systems as studied so far require every process to know the full system membership in order to guarantee safety through globally intersecting quorums. Thus, they are of little help in an open, permissionless setting, where such knowledge may not be available. We propose to generalize the theory of fail-prone systems to make it applicable to permissionless systems. We do so by enabling processes not only to make assumptions about failures, but also to make assumptions about the assumptions of other processes. Thus, by transitivity, processes that do not even know of any common process may nevertheless have intersecting quorums and solve, for example, reliable broadcast. Our model generalizes existing models such as the classic fail-prone system model [Malkhi and Reiter, 1998] and the asymmetric fail-prone system model [Cachin and Tackmann, OPODIS 2019]. Moreover, it gives a characterization with standard formalism of the model used by the Stellar blockchain.

[Blog post](https://cryptobern.github.io/permissionless/)

