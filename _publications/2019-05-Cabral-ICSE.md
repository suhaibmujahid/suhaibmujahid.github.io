---
title: "Class imbalance evolution and verification latency in just-in-time software defect prediction"
paper_id: Cabral_ICSE2019
collection: publications
authors: 'George Cabral,  Leandro Minku,  Emad Shihab,  Suhaib Mujahid'
permalink: /publication/2019-05-Cabral-ICSE
date: 2019-05-01
venue: 'Proceedings of the 41st IEEE/ACM International Conference on Software Engineering (ICSE)'
series: 'ICSE&apos;19'
preprint: '/papers/Cabral_ICSE2019.pdf'
---
 **Abstract:**  Just-in-Time Software Defect Prediction (JIT-SDP) is an SDP approach that makes defect predictions at the software change level. Most existing JIT-SDP work assumes that the characteristics of the problem remain the same over time. However, JIT-SDP may suffer from class imbalance evolution. Specifically, the imbalance status of the problem (i.e., how much underrepresented the defect-inducing changes are) may be intensified or reduced over time. If occurring, this could render existing JIT-SDP approaches unsuitable, including those that re-build classifiers over time using only recent data. This work thus provides the first investigation of whether class imbalance evolution poses a threat to JIT-SDP. This investigation is performed in a realistic scenario by taking into account verification latency -- the often overlooked fact that labeled training examples arrive with a delay. Based on 10 GitHub projects, we show that JIT-SDP suffers from class imbalance evolution, significantly hindering the predictive performance of existing JIT-SDP approaches. Compared to state-of-the-art class imbalance evolution learning approaches, the predictive performance of JIT-SDP approaches was up to 97.2% lower in terms of g-mean. Hence, it is essential to tackle class imbalance evolution in JIT-SDP. We then propose a novel class imbalance evolution approach for the specific context of JIT-SDP. While maintaining top ranked g-means, this approach managed to produce up to 63.59% more balanced recalls on the defect-inducing and clean classes than state-of-the-art class imbalance evolution approaches. We thus recommend it to avoid overemphasizing one class over the other in JIT-SDP.

DOI: [10.1109/ICSE.2019.00076](https://doi.org/10.1109/ICSE.2019.00076){:target="_blank"}
