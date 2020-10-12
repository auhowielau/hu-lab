---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Tracking-by-fusion via Gaussian process regression extended to transfer learning
subtitle: ''
summary: ''
authors:
- Jin Gao
- Qiang Wang
- Junliang Xing
- Haibin Ling
- Weiming Hu
- Stephen John Maybank
tags: []
categories: []
date: '2018-01-01'
lastmod: 2020-09-14T02:08:09+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-09-13T18:08:09.231719Z'
publication_types:
- 2
abstract: 'This paper presents a new Gaussian Processes (GPs)-based particle filter tracking framework. The framework non-trivially extends Gaussian process regression (GPR) to transfer learning, and, following the tracking-by-fusion strategy, integrates closely two tracking components, namely a GPs component and a CFs one. First, the GPs component analyzes and models the probability distribution of the object appearance by exploiting GPs. It categorizes the labeled samples into auxiliary and target ones, and explores unlabeled samples in transfer learning. The GPs component thus captures rich appearance information over object samples across time. On the other hand, to sample an initial particle set in regions of high likelihood through the direct simulation method in particle filtering, the powerful yet efficient correlation filters (CFs) are integrated, leading to the CFs component. In fact, the CFs component not only boosts the sampling quality, but also benefits from the GPs component, which provides re-weighted knowledge as latent variables for determining the impact of each correlation filter template from the auxiliary samples. In this way, the transfer learning based fusion enables effective interactions between the two components. Superior performance on four object tracking benchmarks (OTB-2015, Temple-Color, and VOT2015/2016), and in comparison with baselines and recent state-of-the-art trackers, has demonstrated clearly the effectiveness of the proposed framework.'
publication: '*IEEE Transactions on Pattern Analysis and Machine Intelligence (**TPAMI**)*'
url_pdf: https://eprints.bbk.ac.uk/25711/1/TrackingByFusion.pdf
---
