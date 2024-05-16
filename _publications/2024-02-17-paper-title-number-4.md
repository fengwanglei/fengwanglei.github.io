---
title: "Pretraining Client Selection Algorithm Based on a Data Distribution Evaluation Model in Federated Learning"
collection: publications
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'This paper propose an FL client subset selection algorithm.'
date: 2024-02-17
venue: 'IEEE Access'
paperurl: 'https://ieeexplore.ieee.org/document/10517589?source=authoralert'
citation: 'Chang Xu, Hong Liu, Kexin Li, <b>Wanglei Feng</b>, Wei Qi. (2024). &quot;Pretraining Client Selection Algorithm Based on a Data Distribution Evaluation Model in Federated Learning.&quot; <i>IEEE Access</i>.'
---

Federated Learning (FL) allows task initiators (servers) to utilize data from task participants (clients) to train machine learning models while protecting data privacy. However, in the FL system, when the client data are non-independently identically distributed (Non-IID), appropriate metrics are chosen to accurately evaluate the quality of the client data, accordingly to select a reasonable subset of clients, and thus ensure the accuracy of the FL aggregation model. In this paper, based on the experimental results, a data distribution evaluation model is proposed, which is based on two metrics: the volume of client data and its increment and the balance of global client data. This data distribution evaluation model enables more accurate evaluation of clients with Non-IID characteristics. Based on this evaluation model, this paper further proposes an FL client subset selection algorithm. This algorithm accurately evaluates the data value of each client, enabling the server to select the most valuable subset of clients before FL training, thus improving the accuracy of the federated learning aggregation model in scenarios with Non-IID client data. When training the FL aggregation model using the proposed method on datasets composed of CIFAR-10, Fashion-MNIST, and DEAP distributions, compared to the optimal baseline, the average precision scores increased by 5.99%, 4.79%, and 4.29% respectively. The improvement in accuracy is more pronounced in scenarios with Non-IID data, such as in the DEAP dataset distribution with the highest Non-IID degree, where the accuracy increased by 5.30% compared to the optimal baseline.
