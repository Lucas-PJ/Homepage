---
title: "TGB-Seq Benchmark: Challenging Temporal GNNs with Complex Sequential Dynamics"
collection: publications
permalink: /publication/TGB-Seq
date: 2025-1-23
venue: 'The 13th International Conference on Learning Representations'
---

**Abstract:**
Future link prediction is a fundamental challenge in various real-world dynamic systems. To address this, numerous temporal graph neural networks (temporal GNNs) and benchmark datasets have been developed. However, these datasets often feature excessive repeated edges and lack complex sequential dynamics, a key characteristic inherent in many real-world applications such as recommender systems and Who-To-Follow on social networks. This oversight has led existing methods to inadvertently downplay the importance of learning sequential dynamics, focusing primarily on predicting repeated edges.
In this study, we demonstrate that existing methods, such as GraphMixer and DyGFormer, are inherently incapable of learning simple sequential dynamics, such as a user who has followed OpenAI and Anthropic is more likely to follow AI at Meta next. Motivated by this issue, we introduce the **T**emporal **G**raph **B**enchmark with **Seq**uential Dynamics (TGB-Seq), a new benchmark carefully curated to minimize repeated edges, challenging models to learn sequential dynamics and generalize to unseen edges. TGB-Seq comprises large real-world datasets spanning diverse domains, including e-commerce interactions, movie ratings, business reviews, social networks, citation networks and web link networks. Benchmarking experiments reveal that current methods usually suffer significant performance degradation and incur substantial training costs on TGB-Seq, posing new challenges and opportunities for future research. The datasets and benchmarking code are available at https://anonymous.4open.science/r/TGB-Seq-3F23.

Download [link]([https://arxiv.org/pdf/2408.03669](https://openreview.net/forum?id=8e2LirwiJT))
