---
title: 'Quick Fair Order'
date: 2022-04-13
permalink: /posts/2022/04/quick-fair-order/
tags:
  - mev
  - fairness
  - atomic broadcast
---

Leader-based protocols for consensus, i.e., atomic broadcast, allow some processes to unilaterally affect the final order of transactions. This has become a problem for blockchain networks and decentralized finance because it facilitates front-running and other attacks. To address this, order fairness for payload messages has be en introduced recently as a new safety property for atomic broadcast complementing traditional agreement and liveness. We relate order fairness to the standard validity notions for consensus protocols and highlight some limitations with the existing formalization. Based on this, we introduce a new differential order fairness property that fixes these issues. We also present the quick order-fair atomic broadcast protocol that guarantees payload message delivery in a differentially fair order and is much more efficient than existing order-fair consensus protocols. It works for asynchronous and for eventually synchronous networks with optimal resilience, tolerating corruptions of up to one third of the processes. Previous solutions required there to be less than one fourth of faults. Furthermore, our protocol incurs only quadratic cost, in terms of amortized message complexity per delivered payload.

[Blog post](https://cryptobern.github.io/quickfairorder//)

