---
title: "Asynchrony-Resilient Sleepy Total-Order Broadcast Protocols"
collection: publications
permalink: /publication/2024-asyncres-tob
excerpt: 'Asynchrony-Resilient Sleepy Total-Order Broadcast Protocols.'
date: 2024
venue: PODC
# paperurl: 
# citation: 
---

Dynamically available total-order broadcast (TOB) protocols tolerate fluctuating participation, e.g., as high as 99% of their participants going offline, which is especially useful in permissionless blockchain environments. However, dynamically available TOB protocols are synchronous protocols, and they lose their safety guarantees during periods of asynchrony. This is a major issue in practice.

In this paper, we propose a simple but effective mechanism for tolerating bounded periods of asynchrony in dynamically available TOB protocols that ensure safety deterministically. We propose to trade off assumptions limiting the online/offline churn rate in exchange for tolerating bounded asynchronous periods through the use of a configurable message-expiration period. 

In practice, this allows picking a small synchrony bound 𝛿, and therefore obtain a fast protocol in the common case, knowing that the protocol tolerates occasional periods of duration at most 𝜋 > 𝛿 during which the bound does not hold. We show how to apply this idea to a state-of-the-art protocol to make it tolerate bounded periods of asynchrony.

_Co-authored by_ Francesco D'Amato and Giuliano Losa

[arXiv paper here](https://arxiv.org/abs/2309.05347) 



