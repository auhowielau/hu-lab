---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'DPFPS: Dynamic and progressive filter pruning for compressing convolutional
  neural networks from scratch'
subtitle: ''
summary: ''
authors:
- Xiaofeng Ruan
- Yufan Liu
- Bing Li
- Chunfeng Yuan
- Weiming Hu
tags: []
categories: []
date: '2021-01-01'
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
publishDate: '2021-04-16T07:53:36.366868Z'
publication_types:
- 1
abstract: 'Filter pruning is a commonly used method for compressing Convolutional Neural Networks (ConvNets), due to its friendly hardware supporting and flexibility. However, existing methods mostly need a cumbersome procedure, which brings many extra hyper-parameters and training epochs. This is because only using sparsity and pruning stages cannot obtain a satisfying performance. Besides, many works do not consider the difference of pruning ratio across different layers. To overcome these limitations, we propose a novel dynamic and progressive filter pruning (DPFPS) scheme that directly learns a structured sparsity network from Scratch. In particular, DPFPS imposes a new structured sparsityinducing regularization specifically upon the expected pruning parameters in a dynamic sparsity manner. The dynamic sparsity scheme determines sparsity allocation ratios of different layers and a Taylor series based channel sensitivity criteria is presented to identify the expected pruning parameters. Moreover, we increase the structured sparsity-inducing penalty in a progressive manner. This helps the model to be sparse gradually instead of forcing the model to be sparse at the beginning. Our method solves the pruning ratio based optimization problem by an iterative soft-thresholding algorithm (ISTA) with dynamic sparsity. At the end of the training, we only need to remove the redundant parameters without other stages, such as fine-tuning. Extensive experimental results show that the proposed method is competitive with 11 state-of-the-art methods on both small-scale and largescale datasets (i.e., CIFAR and ImageNet). Specifically, on ImageNet, we achieve a 44.97% pruning ratio of FLOPs by compressing ResNet-101, even with an increase of 0.12% Top-5 accuracy.'
publication: '*AAAI Conference on Artificial Intelligence (**AAAI**)*'
url_code: https://github.com/taoxvzi/DPFPS
---
