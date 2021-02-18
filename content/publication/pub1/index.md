---
abstract: Federated learning (FL) is a promising distributed learning solution
  that only exchanges model parameters without revealing raw data. However, the
  centralized architecture of FL is vulnerable to the single point of failure.
  In addition, FL does not examine the legitimacy of local models, so even a
  small fraction of malicious devices can disrupt global training. To resolve
  these robustness issues of FL, in this paper, we propose a blockchain-based
  decentralized FL framework, termed VBFL, by exploiting two mechanisms in a
  blockchained architecture. First, we introduced a novel decentralized
  validation mechanism such that the legitimacy of local model updates is
  examined by individual validators. Second, we designed a dedicated
  proof-of-stake consensus mechanism where stake is more frequently rewarded to
  honest devices, which protects the legitimate local model updates by
  increasing their chances of dictating the blocks appended to the blockchain.
  Together, these solutions promote more federation within legitimate devices,
  enabling robust FL. Our emulation results of the MNIST classification
  corroborate that with 15% of malicious devices, VBFL achieves 87% accuracy,
  which is 7.4x higher than Vanilla FL.
slides: ""
url_pdf: "https://arxiv.org/pdf/2101.03300.pdf"
publication_types:
  - "1"
authors:
  - Hang Chen
  - Syed Ali Asif
  - Jihong Park
  - Chien-Chung Shen
  - Mehdi Bennis
author_notes: []
publication: In *AAAI 2021 Workshop - Towards Robust, Secure and Efficient Machine Learning*
summary: ""
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: "https://www.youtube.com/embed/LMseEXEITvw"
title: Robust Blockchained Federated Learning with Model Validation and
  Proof-of-Stake Inspired Consensus
doi: ""
featured: true
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: https://img.youtube.com/vi/LMseEXEITvw/0.jpg
date: 2021-02-18T21:42:22.802Z
url_slides: "https://docs.google.com/presentation/d/1E6arGCspzfSQMzWcmR7qqDXIeE9DWbbV-xC-hXAeEhU/edit?usp=sharing"
publishDate: 2021-01-09T00:00:00.000Z
url_poster: "https://drive.google.com/file/d/1tmO6bFUWXzIhcGD0yLo1V0HHKk2u6gGk/view?usp=sharing"
url_code: "https://github.com/hanglearning/VBFL"
---

<iframe width="560" height="315" src="https://www.youtube.com/embed/LMseEXEITvw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>