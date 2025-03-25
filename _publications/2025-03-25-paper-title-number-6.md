---
title: "EMO: Edge Model Overlays to Scale Model Size in Federated Learning"
collection: publications
permalink: /publication/2025-03-25-paper-title-number-6
excerpt: 'This paper propose Edge Model Overlay to address the challenges in SFL.'
date: 2025-04-03
venue: 'ICDCS'
paperurl: ' '
citation: 'Di Wu, Weibo He, <b>Wanglei Feng</b>, Zhenyu Wen, Bin Qian, and Blesson Varghese. (Accept). &quot;EMO: Edge Model Overlays to Scale Model Size in Federated Learning.&quot; <i>ICDCS2025</i>. (CCF B)'
---

 Federated Learning (FL) trains machine learning models on edge devices with distributed data. However, the computational and memory limitations of these devices restrict the training of large models using FL. Split Federated Learning (SFL) addresses this challenge by distributing the model across the device and server, but it introduces a tightly coupled data flow, leading to computational bottlenecks and high communication costs. We propose EMO as a solution to enable the training of large models in FL while mitigating the challenges of SFL. EMO introduces Edge Model Overlay(s) between the device and server, enabling the creation of a larger ensemble model without modifying the FL workflow. The key innovation in EMO is Augmented Federated Learning (AFL), which builds an ensemble model by connecting the original (smaller) FL model with model(s) trained in the overlay(s) to facilitate horizontal or vertical scaling. This is accomplished through three key modules: a hierarchical activation replay cache to decouple AFL from FL, a convergence-aware communication controller to optimize communication overhead, and an ensemble inference module. Evaluations on a real-world prototype show that EMO improves accuracy by up to 17.77% compared to FL, and reduces communication costs by up to 7.17× and decreases training time by up to 6.9× compared to SFL.
