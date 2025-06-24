---
title: "DAG-based Consensus with Asymmetric Trust"
collection: publications
permalink: /publication/2025-asymmetric-dag
excerpt: 'DAG-based Consensus with Asymmetric Trust.'
#date: 2024
 venue: PODC
# paperurl: 
# citation: 
---

In protocols with asymmetric trust, each participant is free to make its own individual trust assumptions about others, captured by an asymmetric quorum system. This contrasts with ordinary, symmetric quorum systems and with threshold models, where all participants share the same trust assumption. It is already known how to realize reliable broadcasts, shared-memory emulations, and binary consensus with asymmetric quorums. In this work, we introduce Directed Acyclic Graph (DAG)-based consensus protocols with asymmetric trust. To achieve this, we extend the key building-blocks of the well-known DAG-Rider protocol to the asymmetric model. Counter to expectation, we find that replacing threshold quorums with their asymmetric counterparts in the existing constant-round gather protocol does not result in a sound asymmetric gather primitive. This implies that asymmetric DAG-based consensus protocols, specifically those based on the existence of common-core primitives, need new ideas in an asymmetric-trust model. Consequently, we introduce the first asymmetric protocol for computing a common core, equivalent to that in the threshold model. This leads to the first randomized asynchronous DAG-based consensus protocol with asymmetric quorums. It decides within an expected constant number of rounds after an input has been submitted, where the constant depends on the quorum system.

_Co-authored by_ Ignacio Amores-Sesar, Christian Cachin, and Juan Villacis

[arXiv paper here](https://arxiv.org/abs/2505.17891) 



