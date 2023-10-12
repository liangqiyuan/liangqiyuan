---
title: "🆕 Digital Ethics in Federated Learning"
publication_types:
  - "3"
authors:
  - admin
  - Dong-Jun Han
  - Vishnu Pandi Chellapandi
  - Stanislaw H. Żak
  - Christopher G. Brinton
doi: ""
publication: _arXiv_
publication_short: ""
abstract: Federated learning (FL) is a distributed machine learning (ML) paradigm that enables clients to collaborate without accessing, infringing upon, or leaking original user data by sharing only model parameters. In the Internet of Things (IoT), edge devices are increasingly leveraging multimodal data compositions and fusion paradigms to enhance model performance. However, in FL applications, two main challenges remain open: (i) addressing the issues caused by heterogeneous clients lacking specific modalities and (ii) devising an optimal modality upload strategy to minimize communication overhead while maximizing learning performance. In this paper, we propose Federated Multimodal Fusion learning with Selective modality communication (FedMFS), a new multimodal fusion FL methodology that can tackle the above mentioned challenges. The key idea is to utilize Shapley values to quantify each modality's impact and modality model size to gauge communication overhead, so that each client can selectively upload the modality models to the server for aggregation. This enables FedMFS to flexibly balance performance against communication costs, depending on resource constraints and applications. Experiments on real-world multimodal datasets demonstrate the effectiveness of FedMFS, achieving comparable accuracy while reducing communication overhead by one twentieth compared to baselines.
projects:
  - federated-learning
image:
  filename: FedMFS.png
date: 2023-10-10T14:31:11.488Z
links:
  - name: DOI
    url: https://arxiv.org/abs/2310.07048
---
