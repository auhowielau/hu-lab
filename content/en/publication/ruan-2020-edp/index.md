---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'EDP: An efficient decomposition and pruning scheme for convolutional neural
  network compression'
subtitle: ''
summary: ''
authors:
- Xiaofeng Ruan
- Yufan Liu
- Chunfeng Yuan
- Bing Li
- Weiming Hu
- Yangxi Li
- Stephen Maybank
tags: []
categories: []
date: '2020-01-01'
lastmod: 2021-04-16T15:53:36+08:00
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
publishDate: '2021-04-16T07:53:36.236217Z'
publication_types:
- 2
abstract: 'Model compression methods have become popular in recent years, which aim to alleviate the heavy load of deep neural networks (DNNs) in real-world applications. However, most of the existing compression methods have two limitations: 1) they usually adopt a cumbersome process, including pretraining, training with a sparsity constraint, pruning/decomposition, and fine-tuning. Moreover, the last three stages are usually iterated multiple times. 2) The models are pretrained under explicit sparsity or low-rank assumptions, which are difficult to guarantee wide appropriateness. In this article, we propose an efficient decomposition and pruning (EDP) scheme via constructing a compressed-aware block that can automatically minimize the rank of the weight matrix and identify the redundant channels. Specifically, we embed the compressed-aware block by decomposing one network layer into two layers: a new weight matrix layer and a coefficient matrix layer. By imposing regularizers on the coefficient matrix, the new weight matrix learns to become a low-rank basis weight, and its corresponding channels become sparse. In this way, the proposed compressed-aware block simultaneously achieves low-rank decomposition and channel pruning by only one single data-driven training stage. Moreover, the network of architecture is further compressed and optimized by a novel Pruning & Merging (PM) module which prunes redundant channels and merges redundant decomposed layers. Experimental results (17 competitors) on different data sets and networks demonstrate that the proposed EDP achieves a high compression ratio with acceptable accuracy degradation and outperforms state-of-the-arts on compression rate, accuracy, inference time, and run-time memory.'
publication: '*IEEE Transactions on Neural Networks and Learning Systems (**TNNLS**)*'
url_pdf: https://www.dcs.bbk.ac.uk/~SJMAYBANK/EDP%20An%20Efficient%20Decomposition%20and%20Pruning%20Scheme.pdf
---
