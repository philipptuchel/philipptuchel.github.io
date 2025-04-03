---
title: "A Continual and Incremental Learning Approach for TinyML On-device Training Using Dataset Distillation and Model Size Adaption"
collection: publications
category: manuscripts
permalink: /publication/2024-09-11-continual-learning
date: 2024-09-11
venue: 'Proceedings of the 2024 IEEE 7th International Conference on Industrial Cyber-Physical Systems (ICPS)'
authors: 'Jointly with Marcus Rüb, Axel Sikora, and Daniel Mueller-Gritschneder'
paperurl: 'https://doi.org/10.1109/ICPS59941.2024.10639989'
citation: 'M. Rüb, P. Tuchel, A. Sikora, and D. Mueller-Gritschneder (2024). &quot;A Continual and Incremental Learning Approach for TinyML On-device Training Using Dataset Distillation and Model Size Adaption.&quot; <i>Proceedings of the 2024 IEEE 7th International Conference on Industrial Cyber-Physical Systems (ICPS)</i>, pp. 1-8.'
---

<!-- more -->

A new algorithm for incremental learning in the context of Tiny Machine learning (TinyML) is presented, which is optimized for low-performance and energy efficient embedded devices. TinyML is an emerging field that deploys machine learning models on resource-constrained devices such as microcontrollers, enabling intelligent applications like voice recognition, anomaly detection, predictive maintenance, and sensor data processing in environments where traditional machine learning models are not feasible. The algorithm solve the challenge of catastrophic forgetting through the use of knowledge distillation to create a small, distilled dataset. The novelty of the method is that the size of the model can be adjusted dynamically, so that the complexity of the model can be adapted to the requirements of the task. This offers a solution for incremental learning in resource-constrained environments, where both model size and computational efficiency are critical factors. Results show that the proposed algorithm offers a promising approach for TinyML incremental learning on embedded devices. The algorithm was tested on five datasets including: CIFAR10, MNIST, CORE50, HAR, Speech Commands. The findings indicated that, despite using only 43% of Floating Point Operations (FLOPs) compared to a larger fixed model, the algorithm experienced a negligible accuracy loss of just 1%. In addition, the presented method is memory efficient. While state-of-the-art incremental learning is usually very memory intensive, the method requires only 1% of the original data set.
