---
title: "MS-ZeroWall: Detecting Zero-Day Multi-Step Attack in Smart Home using VAE and HMM"
collection: publications
permalink: /publication/2024-04-17-paper-title-number-3
excerpt: 'This paper propose a multi-step attack prediction architecture applied in the smart home.'
date: 2024-04-17
venue: 'IEEE Transactions on Vehicular Technology'
paperurl: 'https://ieeexplore.ieee.org/document/10507036'
citation: 'Taotao Li, Zhen Hong, <b>Wanglei Feng</b>, Li Yu, Zhenyu Wen. (2024). &quot;MS-ZeroWall: Detecting Zero-Day Multi-Step Attack in Smart Home using VAE and HMM.&quot; <i>IEEE Transactions on Vehicular Technology</i>. (SCI-2,IF:6.8)'
---

The development of technologies in the smart home provides convenience to our living life, however, the resource-constrained characteristics lead to its frequent exposure to various attacks. 
Previous techniques for attack detection in the Internet of Things (IoT) are primarily fitted to simple attacks (i.e., single-step attack) but are insufficient analysis for dynamic detection of so-called complicated attacks (i.e., multi-step attacks).  Usually, there are three challenges for deploying a multi-step attack prediction system under IoT: 1) resource-constrained, 2) frequently unknown multi-step threats, and 3) high demand for real-time. To address these challenges, in this paper, we propose a multi-step attack prediction architecture (namely, MS-ZeroWall) applied in the smart home.
Firstly, the MS-ZeroWall does not need expensive software, which can be easily deployed on resource-constrained IoT.Then, it captures the characteristics of known threats through the variational auto-encoder (VAE) and uses a VAE-based dual-domain defense strategy (DVAE) to achieve unknown multi-step threat identification. In addition, MS-ZeroWall automatically model any multi-step attack by combining the hidden Markov model (HMM) and VAE, and it uses an aggregated HMM (AHMM) approach to improve the multi-step attacks prediction under low time-delay windows so as to satisfy real-time. We evaluate the MS-ZeroWall on a publicly available multi-step attack dataset, with an $F1$-score of over 0.96 on unknown multi-step threat identification, and an average accuracy improvement of 12.3\% on low-latency multi-step attack prediction.
