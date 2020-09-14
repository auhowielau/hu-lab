---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Human activity prediction using temporally-weighted generalized time warping
subtitle: ''
summary: ''
authors:
- Haoran Wang
- Wankou Yang
- Chunfeng Yuan
- Haibin Ling
- Weiming Hu
tags: []
categories: []
date: '2017-01-01'
lastmod: 2020-09-14T02:08:12+08:00
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
publishDate: '2020-09-13T18:08:12.452738Z'
publication_types:
- 2
abstract: 'Different from traditional human activity recognition, human activity prediction aims to recognize an unfinished activity, typically in absence of explicit temporal progress status. In this paper, we propose a new human activity prediction approach by extending the recently proposed generalized time warping (GTW) [20], which allows an efficient and flexible alignment of two or more multi-dimensional time series. More specifically, for each activity video, either complete or incomplete, we first decompose it into a sequence of short video segments. Then, we represent each segment by the local spatial-temporal statistics using the classical bag-of-visual-words model. In this way, the comparison between a query sequence (i.e., containing an incomplete activity) and a reference sequence (i.e., containing a full activity) boils down to the problem of aligning their corresponding segment sequences. While GTW treats different portions of a sequence as equally important, our task is in favor of early portions since an incomplete activity video always aligns from the beginning of a complete one. Thus motivated, we develop a temporally-weighted GTW (TGTW) algorithm for the activity prediction problem by encouraging alignment in the early portion of an activity sequence. Finally, the similarity derived from TGTW is combined with the k-nearest neighbors algorithm for predicting the activity class of an input sequence. The proposed approach is evaluated on several publicly available datasets in comparison with state-of-the-art approaches. The experimental results and analysis clearly demonstrate the effectiveness of the proposed approach.'
publication: '*Neurocomputing*'
url_pdf: http://ir.ia.ac.cn/bitstream/173211/14360/1/wanghaoran-Human%20activity%20prediction%20using%20temporally-weighted%20generalized%20time%20warping.pdf
---
