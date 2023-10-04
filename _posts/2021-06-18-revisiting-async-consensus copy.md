---
title: 'Revisiting signature-free asynchronous Byzantine consensus'
date: 2021-06-18
permalink: /posts/2021/06/revisiting-async-consensus/
tags:
  - consensus
---

Among asynchronous, randomized, and signature-free implementations of consensus, the protocols of Mostéfaoui et al. (PODC 2014 and JACM 2015) represent a landmark result, which has been extended later and taken up in practical systems. The protocols achieve optimal resilience and take, in expectation, only a constant expected number of rounds and have quadratic message complexity. Randomization is provided through a common-coin primitive. However, the first version of this simple and appealing protocol suffers from a little-known liveness issue due to asynchrony. The JACM 2015 version avoids the problem, but is considerably more complex.

This work revisits the original protocol of PODC 2014 and points out in detail why it may not progress. A fix for the protocol is presented, which does not affect any of its properties, but lets it regain the original simplicity in asynchronous networks enhanced with a common-coin protocol.

[Blog post](https://cryptobern.github.io/revisiting/)

