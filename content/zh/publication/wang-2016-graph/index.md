---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Graph based skeleton motion representation and similarity measurement for action
  recognition
subtitle: ''
summary: ''
authors:
- Pei Wang
- Chunfeng Yuan
- Weiming Hu
- Bing Li
- Yanning Zhang
tags: []
categories: []
date: '2016-01-01'
lastmod: 2020-09-14T02:08:14+08:00
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
publishDate: '2020-09-13T18:08:14.252935Z'
publication_types:
- 1
abstract: 'Most of existing skeleton-based representations for action recognition can not effectively capture the spatio-temporal motion characteristics of joints and are not robust enough to noise from depth sensors and estimation errors of joints. In this paper, we propose a novel low-level representation for the motion of each joint through tracking its trajectory and segmenting it into several semantic parts called motionlets. During this process, the disturbance of noise is reduced by trajectory fitting, sampling and segmentation. Then we construct an undirected complete labeled graph to represent a video by combining these motionlets and their spatio-temporal correlations. Furthermore, a new graph kernel called subgraph-pattern graph kernel (SPGK) is proposed to measure the similarity between graphs. Finally, the SPGK is directly used as the kernel of SVM to classify videos. In order to evaluate our method, we perform a series of experiments on several public datasets and our approach achieves a comparable performance to the state-of-the-art approaches.'
publication: '*European Conference on Computer Vision (ECCV)*'
url_pdf: http://159.226.21.68/bitstream/173211/13480/1/chp%253A10.1007%252F978-3-319-46478-7_23.pdf
---
