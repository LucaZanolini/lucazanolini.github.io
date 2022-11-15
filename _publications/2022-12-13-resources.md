---
title: "Modeling Resources in Permissionless Longest-chain Total-order Broadcast"
collection: publications
permalink: /publication/2022-resources
excerpt: 'Modeling Resources in Permissionless Longest-chain Total-order Broadcast.'
# date: 2021-04-30
venue: OPODIS
# paperurl: https://drops.dagstuhl.de/opus/volltexte/2021/14853/
# citation: 
---
Leader-based protocols for consensus, i.e., atomic broadcast, allow some processes to unilaterally affect the final order of transactions. This has become a problem for blockchain networks and decentralized finance because it facilitates front-running and other attacks. To address this, order fairness for payload messages has been introduced recently as a new safety property for atomic broadcast complementing traditional agreement and liveness. We relate order fairness to the standard validity notions for consensus protocols and highlight some limitations with the existing formalization. Based on this, we introduce a new differential order fairness property that fixes these issues. We also present the quick order-fair atomic broadcast protocol that guarantees payload message delivery in a differentially fair order and is much more efficient than existing order-fair consensus protocols. It works for asynchronous and for eventually synchronous networks with optimal resilience, tolerating corruptions of up to one third of the processes. Previous solutions required there to be less than one fourth of faults. Furthermore, our protocol incurs only quadratic cost, in terms of amortized message complexity per delivered payload.

_Co-authored by_ Sarah Azouvi, Christian Cachin, Duc V. Le, and Marko Vukolić

[arXiv paper here]() 



