---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Ocean: Object-aware Anchor-free Tracking'
subtitle: ''
summary: ''
authors:
- Zhipeng Zhang
- Houwen Peng
tags: []
categories: []
date: '2020-01-01'
lastmod: 2020-09-14T02:08:08+08:00
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
publishDate: '2020-09-13T18:08:08.647282Z'
publication_types:
- 2
abstract: 'Anchor-based Siamese trackers have achieved remarkable advancements in accuracy, yet the further improvement is restricted by the lagged tracking robustness. We find the underlying reason is that the regression network in anchor-based methods is only trained on the positive anchor boxes (i.e., IoU≥0.6). This mechanism makes it difficult to refine the anchors whose overlap with the target objects are small. In this paper, we propose a novel object-aware anchor-free network to address this issue. First, instead of refining the reference anchor boxes, we directly predict the position and scale of target objects in an anchor-free fashion. Since each pixel in groundtruth boxes is well trained, the tracker is capable of rectifying inexact predictions of target objects during inference. Second, we introduce a feature alignment module to learn an object-aware feature from predicted bounding boxes. The object-aware feature can further contribute to the classification of target objects and background. Moreover, we present a novel tracking framework based on the anchor-free model. The experiments show that our anchor-free tracker achieves state-of-the-art performance on five benchmarks, including VOT-2018, VOT-2019, OTB-100, GOT-10k and LaSOT.'
publication: '*arXiv preprint arXiv:2006.10721*'
url_pdf: https://arxiv.org/pdf/2006.10721
url_code: https://github.com/researchmm/TracKit
---
