---
title: "Uncertainty guided online ensemble for non-stationary data streams in fusion science"

authors:
  - Rajput, K.
  - Schram, M.
  - Sammuli, B.
  - Lin, S.

date: '2026-01-01'
doi: 'https://doi.org/10.1016/j.mlwa.2026.100894'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-01-01T00:00:00Z'

# Publication type.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Machine Learning with Applications, Volume 24, Article 100894"
publication_short: ""

abstract: "Machine Learning (ML) is poised to play a pivotal role in the development and operation of next-generation fusion devices. Fusion data shows non-stationary behavior with distribution drifts, resulted by both experimental evolution and machine wear-and-tear. ML models assume stationary distribution and fail to maintain performance when encountered with such non-stationary data streams. Online learning techniques have been leveraged in other domains, however it has been largely unexplored for fusion applications. In this paper, we investigate online learning for continuous adaptation to drifting data streams in the prediction of Toroidal Field (TF) coils deflection at the DIII-D fusion facility. We further address the short-term performance degradation inherent to standard online learning, which arises because ground truth is unavailable at prediction time. To mitigate this issue, we propose an uncertainty-guided online ensemble framework. The method leverages the Deep Gaussian Process Approximation (DGPA) for calibrated uncertainty estimation and uses these uncertainty measures to guide a meta-algorithm that aggregates predictions from learners trained over different historical horizons. Our results show that online learning reduces prediction error by 80% compared to a static model. The online ensemble and the proposed uncertainty-guided ensemble further reduce error by approximately 6%, and 10% respectively, relative to standard single-model online learning, while also providing calibrated uncertainty estimates to support operational decision-making."

tags:
  - Ensemble Learning
  - Uncertainty Quantification
  - Fusion Science
  - Online Learning
  - Non-stationary Data

featured: false

url_pdf: 'https://arxiv.org/abs/2511.02092'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://www.sciencedirect.com/science/article/pii/S2666827026000599'
url_video: ''

# Featured image
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
projects: []

# Slides (optional).
slides: ""
---
