---
title: "🆕 Communication-Efficient Multimodal Federated Learning: Joint Modality and Client Selection"
url: "mmFedMC"
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
abstract: "Multimodal federated learning (FL) aims to enrich model training in FL settings where clients are collecting measurements across multiple modalities. However, key challenges to multimodal FL remain unaddressed, particularly in heterogeneous network settings where: (i) the set of modalities collected by each client will be diverse, and (ii) communication limitations prevent clients from uploading all their locally trained modality models to the server. In this paper, we propose multimodal Federated learning with joint Modality and Client selection (mmFedMC), a new FL methodology that can tackle the above-mentioned challenges in multimodal settings. The joint selection algorithm incorporates two main components: (a) A modality selection methodology for each client, which weighs (i) the impact of the modality, gauged by Shapley value analysis, (ii) the modality model size as a gauge of communication overhead, against (iii) the frequency of modality model updates, denoted recency, to enhance generalizability. (b) A client selection strategy for the server based on the local loss of modality model at each client. Experiments on five real-world datasets demonstrate the ability of mmFedMC to achieve comparable accuracy to several baselines while reducing the communication overhead by over 20x. A demo video of our methodology is available at [https://liangqiy.com/mmfedmc/](https://liangqiy.com/mmfedmc/)."
projects:
  - federated-learning
image:
  filename: JMCS.png
date: 2024-01-18T14:31:11.488Z
url_Video: "mmFedMC_Demo.mp4"
links:
  - name: DOI
    url: https://arxiv.org/abs/2401.16685
---


{{< video library="true" src="mmFedMC_Demo.mp4" controls="yes" >}}

