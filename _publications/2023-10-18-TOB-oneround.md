---
title: "TOB-SVD: Total-Order Broadcast with Single-Vote Decisions in the Sleepy Model"
collection: publications
permalink: /publication/2023-oneround-TOB
excerpt: 'TOB-SVD: Total-Order Broadcast with Single-Vote Decisions in the Sleepy Model.'
# date: 
 venue: ICDCS
# paperurl: 
# citation: 
---

Over the past years, distributed consensus research has extended its focus towards addressing challenges in large-scale, permissionless systems, such as blockchains. This shift is characterized by the need to accommodate dynamic participation, contrasting the traditional approach of a static set of continuously online participants. Works like Bitcoin and the sleepy model have set the stage for this evolving framework.
Notable contributions from Momose and Ren (CCS 2022) and subsequent works have introduced Total-Order Broadcast protocols leveraging Graded Agreement primitives and supporting dynamic participation. However, these approaches often require multiple phases of voting per decision, creating a potential bottleneck for real-world large-scale systems.
Addressing this, our paper introduces TOB-SVD, a novel Total-Order Broadcast protocol in the sleepy model, which is resilient to up to 1/2 of adversarial participants. TOB-SVD requires only a single phase of voting per decision in the best case and achieves lower expected latency compared to existing approaches offering the same optimal adversarial resilience. This work paves the way to more practical Total-Order Broadcast protocols to be implemented in real-world systems where a large number of participants are involved simultaneously and their participation level might fluctuate over time.

_Co-authored by_ Roberto Saltini, Thanh-Hai Tran, and Francesco D'Amato

[arXiv paper here](https://arxiv.org/abs/2310.11331) 



