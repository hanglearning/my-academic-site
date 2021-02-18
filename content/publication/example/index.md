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
url_pdf: ""
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
url_video: ""
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
date: 2021-01-09T18:23:57.215Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: ""
---
**[Paper](https://arxiv.org/abs/2101.03300)**

**[Code](https://github.com/hanglearning/VBFL)[](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbl81dUdoV3h0NlJfSk5CbXZiMk5rWFFscEhNQXxBQ3Jtc0ttTjNyeG1PTWcwdWVSZjd5ZUctTVgyRS1lRzRQcU9ObUYwLTdFTmFoUmNhbmk0dGVjX0hjUzdON0piN1Q1clNZckpObnFoRUk4UnBFT0V3RE5lTUNWLXhRek9pRlVxM1cyZVJzb2tsMnJQTEw3d2ZYNA&q=https%3A%2F%2Fgithub.com%2Fhanglearning%2FVBFL)**

<iframe width="560" height="315" src="https://www.youtube.com/embed/LMseEXEITvw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>