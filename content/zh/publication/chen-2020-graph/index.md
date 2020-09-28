---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Graph convolutional network with structure pooling and joint-wise channel attention
  for action recognition
subtitle: ''
summary: ''
authors:
- Yuxin Chen
- Gaoqun Ma
- Chunfeng Yuan
- Bing Li
- Hui Zhang
- Fangshi Wang
- Weiming Hu
tags: []
categories: []
date: '2020-01-01'
lastmod: 2020-09-14T02:08:08+08:00
featured: false
draft: false


url_pdf: files/graph.pdf
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
publishDate: '2020-09-13T18:08:08.057294Z'
publication_types:
- 2
abstract: 'Recently, graph convolutional networks (GCNs) have achieved state-of-the-art results for skeleton based action recognition by expanding convolutional neural networks (CNNs) to graphs. However, due to the lack of effective feature aggregation method, e.g. max pooling in CNN, existing GCN-based methods only learn local information among adjacent joints and are hard to obtain high-level interaction features, such as interactions between five parts of human body. Moreover, subtle differences of confusing actions often hide in specific channels of key joints’ features, this kind of discriminative information is rarely exploited in previous methods. In this paper, we propose a novel graph convolutional network with structure based graph pooling (SGP) scheme and joint-wise channel attention (JCA) modules. The SGP scheme pools the human skeleton graph according to the prior knowledge of human body’s typology. This pooling scheme not only leads to more global representations but also reduces the amount of parameters and computation cost. The JCA module learns to selectively focus on discriminative joints of skeleton and pays different levels of attention to different channels. This novel attention mechanism enhance the model’s ability to classify confusing actions.  
We evaluate our SGP scheme and JCA module on three most challenging skeleton based action recognition datasets: NTU-RGB+D, Kinetics-M, and SYSU-3D. Our method outperforms the state-of-art methods on three benchmarks.'
publication: '*Pattern Recognition (PR)*'
---
