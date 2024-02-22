---
title: "Communication-Efficient Federated Learning for Multimodal Automatic Target Recognition"

event: The 8th Annual Workshop on Naval Applications of Machine Learning (NAML 2024)
event_url: https://sites.google.com/go.spawar.navy.mil/naml/

location: California, USA
address:
  street: San Diego Mission Bay Resort
  city: San Diego
  region: California
  postcode: '92109'
  country: United States

summary: The 8th Annual Workshop on Naval Applications of Machine Learning (NAML 2024)
abstract: 'Federated learning (FL) is a distributed machine learning paradigm that enables clients to collaborate without accessing, infringing upon, or leaking user raw data by sharing only model parameters. Multimodal automatic target recognition (ATR) in FL aims to enrich model training in FL settings where clients are collecting measurements across multiple modalities (e.g., sensors measuring pressure, motion, and other types of data). However, key challenges to multimodal FL remain unaddressed, particularly in heterogeneous network settings: (i) the set of modalities collected by each client will be diverse, and (ii) communication limitations prevent clients from uploading all their locally trained modality models to the server. In this study, we propose multimodal fusion Federated learning with joint Modality and Client selection (mmFedMC), a new FL framework for multimodal ATR that can tackle the above-mentioned challenges. The joint selection algorithm incorporates two main components: (a) A modality selection criterion for each client, which weighs (i) the impact of the modality, gauged by Shapley value analysis, (ii) the modality model size as a gauge of communication overhead, against (iii) the frequency of modality model updates, denoted recency, to enhance generalizability. This allows mmFedMC to flexibly balance performance against communication costs, depending on resource constraints and application requirements. (b) A client selection for the server is performed on the basis of the cross-entropy of prediction as a metric. This involves selecting a subset of clients for uploading and aggregating models, which further reduces communication overhead and optimizes the overall process. Experiments on a real-world dataset with six modalities demonstrate that mmFedMC achieves 98.19% accuracy with a communication overhead of only 5MB per client. This represents an approximate 10% increase in accuracy compared to random modality or client selection. Moreover, in comparison to other state-of-the-art methods that do not utilize a selection mechanism, mmFedMC enhances accuracy by a factor of 2x to 4x. Alternatively, to achieve comparable levels of accuracy, other methods require approximately 20x more communication overhead, i.e., about 100MB per client. Beyond the trade-off between performance and communication overhead, mmFedMC also offers an interpretable representation of the modality impact during the FL process. In the initial stages of FL, most modalities exhibit similar impacts. However, as the communication rounds progress, modalities with larger feature sets and complex models play a subordinate role in modality selection due to their higher communication costs. With the advancement of FL, more straightforward modalities that continue to convey substantial information emerge as primary contributors.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-03-11T17:40:00Z'
# date_end: '2023-06-04T20:40:00Z'
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: '2024-01-27T00:00:00Z'

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: true

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

url_code: ''
url_pdf: ''
# url_slides: IV2023 Presentation.pdf
url_video: ''
url_poster: NAML2024 Poster.pdf

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - federated-learning
---
