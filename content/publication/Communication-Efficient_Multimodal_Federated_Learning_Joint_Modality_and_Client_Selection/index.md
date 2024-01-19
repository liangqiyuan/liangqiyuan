---
title: "🆕 Communication-Efficient Multimodal Federated Learning: Joint Modality and Client Selection"
publication_types:
  - "3"
authors:
  - admin
  - Dong-Jun Han
  - Su Wang
  - Devesh Upadhyay
  - Christopher G. Brinton
doi: ""
publication: _arXiv_
publication_short: ""
abstract: Multimodal federated learning (FL) aims to enrich model training in FL settings where clients are collecting measurements across multiple modalities (e.g., sensors measuring pressure, motion, and other types of data). However, key challenges to multimodal FL remain unaddressed, particularly in heterogeneous network settings: (i) the set of modalities collected by each client will be diverse, and (ii) communication limitations prevent clients from uploading all their locally trained modality models to the server. In this paper, we propose multimodal Federated learning with joint Modality and Client selection (mmFedMC), a new multimodal FL methodology that can tackle the above-mentioned challenges. The joint selection algorithm incorporates two main components: (a) A modality selection criterion for each client, which weighs (i) the impact of the modality, gauged by Shapley value analysis, (ii) the modality model size as a gauge of communication overhead, against (iii) the frequency of modality model updates, denoted recency, to enhance generalizability. This allows mmFedMC to flexibly balance performance against communication costs, depending on resource constraints and application requirements. (b) A client selection strategy for the server is performed on the basis of the local loss of modality model as a metric. This involves selecting a subset of clients for uploading and aggregating models, which further reduces communication overhead and optimizes the overall process. Experiments on five real-world datasets demonstrate the ability of mmFedMC to achieve comparable accuracy to several baselines while reducing the communication overhead by over 20x. A demo video of our methodology is available at this http URL.
projects:
  - federated-learning
image:
  filename: JMCS.png
date: 2023-01-18T14:31:11.488Z
links:
  - name: DOI
    url: ""
---
