---
title: "Accountable Liveness"
collection: publications
permalink: /publication/2025-accountable-liveness
excerpt: 'Accountable Liveness.'
#date: 2024
# venue: PODC
# paperurl: 
# citation: 
---

Safety and liveness are the two classical security properties of consensus protocols. Recent works have strengthened safety with accountability: should any safety violation occur, a sizable fraction of adversary nodes can be proven to be protocol violators. This paper studies to what extent analogous accountability guarantees are achievable for liveness. To reveal the full complexity of this question, we introduce an interpolation between the classical synchronous and partially-synchronous models that we call the x-partially-synchronous network model in which, intuitively, at most an x fraction of the time steps in any sufficiently long interval are asynchronous (and, as with a partially-synchronous network, all time steps are synchronous following the passage of an unknown "global stablization time"). We prove a precise characterization of the parameter regime in which accountable liveness is achievable: if and only if x<1/2 and f < n/2, where n denotes the number of nodes and f the number of nodes controlled by an adversary. We further refine the problem statement and our analysis by parameterizing by the number of violating nodes identified following a liveness violation, and provide evidence that the guarantees achieved by our protocol are near-optimal (as a function of x and f). Our results provide rigorous foundations for liveness-accountability heuristics such as the "inactivity leaks" employed in Ethereum.

_Co-authored by_ Andrew Lewis-Pye, Joachim Neu, and Tim Roughgarden

[arXiv paper here](https://arxiv.org/abs/2504.12218) 



