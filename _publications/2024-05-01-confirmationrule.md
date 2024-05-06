---
title: "A Confirmation Rule for the Ethereum Consensus Protocol"
collection: publications
permalink: /publication/2024-confirmationrule
excerpt: 'A Confirmation Rule for the Ethereum Consensus Protocol.'
#date: 2024
# venue: PODC
# paperurl: 
# citation: 
---

A Confirmation Rule, within blockchain networks, refers to an algorithm implemented by network nodes that determines (either probabilistically or deterministically) the permanence of certain blocks on the blockchain. An example of Confirmation Rule is the Bitcoin's longest chain Confirmation Rule where a block is confirmed (with high probability) when it has a sufficiently long chain of successors, its siblings have notably shorter successor chains, and network synchrony holds. In this work, we devise a Confirmation Rule for Ethereum's consensus protocol, Gasper. Initially, our focus is on developing a rule specifically for LMD-GHOST, the component of Gasper responsible for ensuring dynamic availability. This is done independently of the influence of FFG-Casper, which is designed to finalize the blocks produced by LMD-GHOST. Subsequently, we build upon this rule to consider FFG-Casper's impact, aiming to achieve fast block confirmations through a heuristic that balances confirmation speed with a trade-off in safety guarantees. This refined Confirmation Rule could potentially standardize fast block confirmation within Gasper.

_Co-authored by_ Aditya Asgaonkar, Francesco D'Amato, Roberto Saltini, and Chenyi Zhang

[arXiv paper here](https://arxiv.org/abs/2405.00549) 



