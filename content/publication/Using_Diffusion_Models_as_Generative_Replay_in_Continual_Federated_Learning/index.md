---
title: "🔥 Using Diffusion Models as Generative Replay in Continual Federated Learning -- What will Happen?"
publication_types:
  - "3"
featured: true
authors:
  - Yongsheng Mei
  - admin
  - Dong-Jun Han
  - Kevin S. Chan
  - Christopher G. Brinton
  - Tian Lan
author_notes:
- "Equal contribution"
- "Equal contribution"
doi: ""
publication: _arXiv_
publication_short: ""
abstract: "Federated learning (FL) has become a cornerstone in decentralized learning, where, in many scenarios, the incoming data distribution will change dynamically over time, introducing continuous learning (CL) problems. This continual federated learning (CFL) task presents unique challenges, particularly regarding catastrophic forgetting and non-IID input data. Existing solutions include using a replay buffer to store historical data or leveraging generative adversarial networks. Nevertheless, motivated by recent advancements in the diffusion model for generative tasks, this paper introduces DCFL, a novel framework tailored to address the challenges of CFL in dynamic distributed learning environments. Our approach harnesses the power of the conditional diffusion model to generate synthetic historical data at each local device during communication, effectively mitigating latent shifts in dynamic data distribution inputs. We provide the convergence bound for the proposed CFL framework and demonstrate its promising performance across multiple datasets, showcasing its effectiveness in tackling the complexities of CFL tasks."
projects:
  - federated-learning
image:
  filename: DFCL.png
date: 2024-11-10T14:31:11.488Z
links:
  - name: DOI
    url: https://arxiv.org/abs/2411.06618
  - name: Code
    url: https://github.com/ysmei97/DCFL
---
