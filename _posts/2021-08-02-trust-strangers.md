---
title: 'How to Trust Strangers'
date: 2021-06-18
permalink: /posts/2021/08/how-to-trust-strangers/
tags:
  - asymmetric trust
  - composition rules
---

Trust is the basis of any distributed, fault-tolerant, or secure system. A trust assumption specifies the failures that a system, such as a blockchain network, can tolerate and determines the conditions under which it operates correctly. In systems subject to Byzantine faults, the trust assumption is usually specified through sets of processes that may fail together. Trust has traditionally been symmetric, such that all processes in the system adhere to the same, global assumption about potential faults. Recently, asymmetric trust models have also been considered, especially in the context of blockchains, where every participant is free to choose who to trust. In both cases, it is an open question how to compose trust assumptions. Consider two or more systems, run by different and possibly disjoint sets of participants, with different assumptions about faults: how can they work together? This work answers this question for the first time and offers composition rules for symmetric and for asymmetric quorum systems. These rules are static and do not require interaction or agreement on the new trust assumption among the participants. Moreover, they ensure that if the original systems allow for running a particular protocol (guaranteeing consistency and availability), then so will the joint system. At the same time, the composed system tolerates as many faults as possible, subject to the underlying consistency and availability properties. Reaching consensus with asymmetric trust in the model of personal Byzantine quorum systems (Losa et al., DISC 2019) was shown to be impossible, if the trust assumptions of the processes diverge from each other. With asymmetric quorum systems, and by applying our composition rule, we show how consensus is actually possible, even with the combination of disjoint sets of processes.

[Blog post](https://cryptobern.github.io/howtotruststrangers/)

