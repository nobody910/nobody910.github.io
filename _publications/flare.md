---
title: "Safeguarding Federated Learning-Based Road Condition Classification"
collection: publications
permalink: /publication/flare
excerpt: ''
date: 2025-07-07
venue: '2025 IEEE Conference on Communications and Network Security (CNS)'
paperurl: 'https://ieeexplore.ieee.org/document/11194922'

citation: 'S Liu and Panos Papadimitratos, "Safeguarding Federated Learning-Based Road Condition Classification", IEEE Conference on Communications and Network Security (CNS), pp. 1-9, Sep 2025, doi: 10.1109/CNS66487.2025.11194922.'

---

[Download paper here](http://nobody910.github.io/files/FLARE.pdf)

**Abstract:** Federated Learning (FL) has emerged as a promising solution for privacy-preserving autonomous driving, specifically camera-based Road Condition Classification (RCC) systems, harnessing distributed sensing, computing, and communication resources on board vehicles without sharing sensitive image data. However, the collaborative nature of FL-RCC frameworks introduces new vulnerabilities: Targeted Label Flipping Attacks (TLFAs), in which malicious clients (vehicles) deliberately alter their training data labels to compromise the learned model inference performance. Such attacks can, e.g., cause a vehicle to mis-classify slippery, dangerous road conditions as pristine and exceed recommended speed. However, TLFAs for FL-based RCC systems are largely missing. We address this challenge with a threefold contribution: 1) we disclose the vulnerability of existing FL-RCC systems to TLFAs; 2) we introduce a novel label-distance-based metric to precisely quantify the safety risks posed by TLFAs; and 3) we propose FLARE, a defensive mechanism leveraging neuron-wise analysis of the output layer to mitigate TLFA effects. Extensive experiments across three RCC tasks, four evaluation metrics, six baselines, and three deep learning models demonstrate both the severity of TLFAs on FL-RCC systems and the effectiveness of FLARE in mitigating the attack impact.

**Keywords:** federated learning, road condition classification, data poisoning attacks, transportation safety

<br/><img src='/images/papers/FLARE.png' width = "700">