---
title: "A Fast Confirmation Rule for the Ethereum Consensus Protocol"
collection: publications
permalink: /publication/2024-confirmationrule
excerpt: 'A Fast Confirmation Rule for the Ethereum Consensus Protocol.'
#date: 2024
# venue: PODC
# paperurl: 
# citation: 
---

A Confirmation Rule, within blockchain networks, refers to an algorithm implemented by network nodes that determines (either probabilistically or deterministically) the permanence of certain blocks on the blockchain. An example of Confirmation Ruble is the Bitcoin's longest chain Confirmation Rule where a block b is confirmed (with high probability) when it has a sufficiently long chain of successors, its siblings have notably shorter successor chains, the majority of the network's total computation power (hashing) is controlled by honest nodes, and network synchrony holds.
The only Confirmation Rule currently available in the Ethereum protocol, Gasper, is the FFG Finalization Rule. While this Confirmation Rule works under asynchronous network conditions, it is quite slow for many use cases. Specifically, best-case scenario, it takes around 13 to 19 min to confirm a transaction, where the actual figure depends on when the transaction is submitted to the network.
In this work, we devise a Fast Confirmation Rule for Ethereum's consensus protocol. Our Confirmation Rule relies on synchrony conditions, but provides a best-case confirmation time of 12 seconds only, greatly improving on the latency of the FFG Finalization Rule.
Users can then rely on the Confirmation Rule that best suits their needs depending on their belief about the network conditions and the need for a quick response.

_Co-authored by_ Aditya Asgaonkar, Francesco D'Amato, Roberto Saltini, and Chenyi Zhang

[arXiv paper here](https://arxiv.org/abs/2405.00549) 



