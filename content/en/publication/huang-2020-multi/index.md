---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Multi-Cue Semi-Supervised Color Constancy With Limited Training Samples
subtitle: ''
summary: ''
authors:
- Xinwei Huang
- Bing Li
- Shuai Li
- Wenjuan Li
- Weihua Xiong
- Xuanwu Yin
- Weiming Hu
- Hong Qin
tags: []
categories: []
date: '2020-01-01'
lastmod: 2020-09-14T02:08:08+08:00
featured: false
draft: false

url_pdf: files/multi
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
publishDate: '2020-09-13T18:08:08.794917Z'
publication_types:
- 2
abstract: 'Color constancy is one of the fundamental tasks in computer vision. Many supervised methods, including recently proposed Convolutional Neural Networks (CNN)-based methods, have been proved to work well on this problem, but they often require a sufficient number of labeled data. However, it is expensive and time-consuming to collect a large number of labeled training images with accurately measured illumination. In order to reduce the dependence on labeled images and leverage unlabeled ones without measured illumination, we propose a novel semi-supervised framework with limited training samples for illumination estimation. Our key insight is that the images with similar features from different cues will share similar lighting conditions. Consequently, three graphs based on three visual cues, low-level RGB color distribution, mid-level initial illuminant estimates and high-level scene content, are constructed to represent the relationship among different images. Then a multi-cue semi-supervised color constancy method (MSCC) is proposed after integrating these three graphs into a unified model. Extensive experiments on benchmark datasets demonstrate that our proposed MSCC method outperforms nearly all the existing supervised methods with limited labeled samples. Even with no unlabeled samples, MSCC still obtains better performance and stableness than most supervised methods.'
publication: '*IEEE Transactions on Image Processing*'
---
