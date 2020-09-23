---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Tensor power iteration for multi-graph matching
subtitle: ''
summary: ''
authors:
- Xinchu Shi
- Haibin Ling
- Weiming Hu
- Junliang Xing
- Yanning Zhang
tags: []
categories: []
date: '2016-01-01'
lastmod: 2020-09-14T02:08:13+08:00
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
publishDate: '2020-09-13T18:08:13.668488Z'
publication_types:
- 1
abstract: 'Due to its wide range of applications, matching between two graphs has been extensively studied and remains an active topic. By contrast, it is still under-exploited on how to jointly match multiple graphs, partly due to its intrinsic computational intractability. In this work, we address this challenging problem in a principled way under the rank-1 tensor approximation framework. In particular, we formulate multi-graph matching as a combinational optimization problem with two main ingredients: unary matching over graph vertices and structure matching over graph edges, both of which across multiple graphs. Then we propose an efficient power iteration solution for the resulted NP-hard optimization problem. The proposed algorithm has several advantages: 1) the intrinsic matching consistency across multiple graphs based on the high-order tensor optimization; 2) the free employment of powerful high-order node affinity; 3) the flexible integration between various types of node affinities and edge/hyper-edge affinities. Experiments on diverse and challenging datasets validate the effectiveness of the proposed approach in comparison with state-of-the-arts.'
publication: '*IEEE Conference on Computer Vision and Pattern Recognition (CVPR)*'
url_pdf: http://openaccess.thecvf.com/content_cvpr_2016/papers/Shi_Tensor_Power_Iteration_CVPR_2016_paper.pdf
---
