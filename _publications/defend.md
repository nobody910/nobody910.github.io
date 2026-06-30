---
title: "DEFEND: Poisoned Model Detection and Malicious Client Exclusion Mechanism for Secure Federated Learning-based Road Condition Classification"
collection: publications
permalink: /publication/defend
excerpt: ''
date: 2026-03-23
venue: 'The 41st ACM/SIGAPP Symposium on Applied Computing (SAC 2026)'
paperurl: 'https://dl.acm.org/doi/10.1145/3748522.3779807'

citation: 'S Liu and Panos Papadimitratos, "DEFEND: Poisoned Model Detection and Malicious Client Exclusion Mechanism for Secure Federated Learning-based Road Condition Classification", ACM/SIGAPP Symposium on Applied Computing (SAC), pp. 1486–1495, Mar 2026, doi: 10.1145/3748522.3779807.'

---

[Download paper here](http://nobody910.github.io/files/DEFEND.pdf)

**Abstract:** Federated Learning (FL) has drawn the attention of the Intelligent Transportation Systems (ITS) community. FL can train various models for ITS tasks, notably camera-based Road Condition Classification (RCC), in a privacy-preserving collaborative way. However, opening up to collaboration also opens FL-based RCC systems to adversaries, i.e., misbehaving participants that can launch Targeted Label-Flipping Attacks (TLFAs) and threaten transportation safety. Adversaries mounting TLFAs poison training data to misguide model predictions, from an actual source class (e.g., wet road) to a wrongly perceived target class (e.g., dry road). Existing countermeasures against poisoning attacks cannot maintain model performance under TLFAs close to the performance level in attack-free scenarios, because they lack specific model misbehavior detection for TLFAs and neglect client exclusion after the detection. To close this research gap, we propose DEFEND, which includes a poisoned model detection strategy that leverages neuron-wise magnitude analysis for attack goal identification and Gaussian Mixture Model (GMM)-based clustering. DEFEND discards poisoned model contributions in each round and adapts accordingly client ratings, eventually excluding malicious clients. Extensive evaluation involving various FL-RCC models and tasks shows that DEFEND can thwart TLFAs and outperform seven baseline countermeasures, with at least 15.78\% improvement, with DEFEND remarkably achieving under attack the same performance as in attack-free scenarios.

**Keywords:** federated learning, road condition classification, data poisoning attacks, transportation safety

<br/><img src='/images/papers/DEFEND.png' width = "700">