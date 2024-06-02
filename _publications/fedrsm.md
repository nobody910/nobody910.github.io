---
title: "FedRSM: Representational-Similarity-Based Secured Model Uploading for Federated Learning"
collection: publications
permalink: /publication/fedrsm
excerpt: ''
date: 2023-09-08
venue: 'IEEE International Conference on Trust, Security and Privacy in Computing and Communications'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10538768'

---

[Download paper here](http://nobody910.github.io/files/FedRSM.pdf)


**Abstract:** As a novel learning paradigm, Federated learning (FL) aims at protecting privacy by avoiding raw data shifting between distributed clients and central servers. However, recent researches demonstrate the vulnerability of FL against gradient-based privacy attacks, in which, gradients intercepted by malicious adversaries may result in data leakage. Current defense methods suffer from performance drops, low privacy guarantees, and high communication costs. Motivated by this, we propose FedRSM, a Representational-Similarity-Based Secured Model Uploading for Federated Learning. FedRSM splits Deep Neural Networks (DNNs) into layers, calculates Representational Dissimilarity Vector (RDV), measures the similarity between local RDV and glocal RDV of each model layer, and constructs secured local model to be uploaded based on Representational Consistency Alteration (RCA). According to the evaluation result, FedRSM can improve testing accuracy by up to 2%, significantly reduce communication costs, and avoid data leakage under different model complexities.

**Keywords:** Federated Learning, Privacy Protection, Secured Model Uploading