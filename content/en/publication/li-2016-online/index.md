---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Online human action detection using joint classification-regression recurrent
  neural networks
subtitle: ''
summary: ''
authors:
- Yanghao Li
- Cuiling Lan
- Junliang Xing
- Wenjun Zeng
- Chunfeng Yuan
- Jiaying Liu
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
publishDate: '2020-09-13T18:08:14.397583Z'
publication_types:
- 1
abstract: 'Human action recognition from well-segmented 3D skeleton data has been intensively studied and has been attracting an increasing attention. Online action detection goes one step further and is more challenging, which identifies the action type and localizes the action positions on the fly from the untrimmed stream data. In this paper, we study the problem of online action detection from streaming skeleton data. We propose a multi-task end-to-end Joint Classification-Regression Recurrent Neural Network to better explore the action type and temporal localization information. By employing a joint classification and regression optimization objective, this network is capable of automatically localizing the start and end points of actions more accurately. Specifically, by leveraging the merits of the deep Long Short-Term Memory (LSTM) subnetwork, the proposed model automatically captures the complex long-range temporal dynamics, which naturally avoids the typical sliding window design and thus ensures high computational efficiency. Furthermore, the subtask of regression optimization provides the ability to forecast the action prior to its occurrence. To evaluate our proposed model, we build a large streaming video dataset with annotations. Experimental results on our dataset and the public G3D dataset both demonstrate very promising performance of our scheme.'
publication: '*European Conference on Computer Vision (**ECCV**)*'
url_pdf: https://arxiv.org/pdf/1604.05633
---
