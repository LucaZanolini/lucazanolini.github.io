---
title: "From Symmetric to Asymmetric Asynchronous Byzantine Consensus"
collection: publications
permalink: /publication/2019-asymconsensus
excerpt: 'Asymmetric Asynchronous Byzantine Consensus'
date: 
venue: ''
paperurl: 'https://arxiv.org/abs/2005.08795v2'
citation: ''
---
Consensus is arguably one of the most important notions in distributed computing. Among asynchronous, randomized, and signature-free implementations, the protocols of Mostéfaoui et al. (PODC 2014 and JACM 2015) represent a landmark result, which has been extended later and taken up in practical systems. The protocols achieve optimal resilience and takes, in expectation, only a constant expected number of rounds of quadratic message complexity. Randomization is provided through a common-coin primitive. In traditional consensus protocols, all involved processes adhere to a global, symmetric failure model, typically only defined by bounds on the number of faulty processes. Motivated by applications to blockchains, however, more flexible trust assumptions have recently been considered. In particular, with asymmetric trust, a process is free to choose which other processes it trusts and which ones might collude against it. This paper revisits the optimal asynchronous protocol of Mostéfaoui et al. and shows how to realize it with asymmetric trust. The paper starts by pointing out in detail why some versions of this protocol may violate liveness. Then it proposes a fix for the protocol that does not affect its properties, but lets it regain the simplicity of its original version (PODC 2014). At the same time, the paper shows how to realize randomized signature-free asynchronous Byzantine consensus with asymmetric quorums. This results in an optimal consensus protocol with subjective, asymmetric trust and constant expected running time. It is suitable for applications to blockchains, for instance.

[Download paper here](https://arxiv.org/abs/2005.08795v2)