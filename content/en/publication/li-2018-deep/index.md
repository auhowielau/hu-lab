---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Deep cost-sensitive and order-preserving feature learning for cross-population
  age estimation
subtitle: ''
summary: ''
authors:
- Kai Li
- Junliang Xing
- Chi Su
- Weiming Hu
- Yundong Zhang
- Stephen Maybank
tags: []
categories: []
date: '2018-01-01'
lastmod: 2020-09-14T02:08:11+08:00
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
publishDate: '2020-09-13T18:08:11.002615Z'
publication_types:
- 1
abstract: 'Facial age estimation from a face image is an important yet very challenging task in computer vision, since humans with different races and/or genders, exhibit quite different patterns in their facial aging processes. To deal with the influence of race and gender, previous methods perform age estimation within each population separately. In practice, however, it is often very difficult to collect and label sufficient data for each population. Therefore, it would be helpful to exploit an existing large labeled dataset of one (source) population to improve the age estimation performance on another (target) population with only a small labeled dataset available. In this work, we propose a Deep Cross-Population (DCP) age estimation model to achieve this goal. In particular, our DCP model develops a two-stage training strategy. First, a novel cost-sensitive multi-task loss function is designed to learn transferable aging features by training on the source population. Second, a novel order-preserving pair-wise loss function is designed to align the aging features of the two populations. By doing so, our DCP model can transfer the knowledge encoded in the source population to the target population. Extensive experiments on the two of the largest benchmark datasets show that our DCP model outperforms several strong baseline methods and many state-of-the-art methods.'
publication: '*IEEE Conference on Computer Vision and Pattern Recognition (**CVPR**)*'
url_pdf: http://openaccess.thecvf.com/content_cvpr_2018/papers/Li_Deep_Cost-Sensitive_and_CVPR_2018_paper.pdf
---
