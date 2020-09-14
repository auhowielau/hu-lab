---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Online multi-target tracking with tensor-based high-order graph matching
subtitle: ''
summary: ''
authors:
- Zongwei Zhou
- Junliang Xing
- Mengdan Zhang
- Weiming Hu
tags: []
categories: []
date: '2018-01-01'
lastmod: 2020-09-14T02:08:09+08:00
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
publishDate: '2020-09-13T18:08:09.086109Z'
publication_types:
- 1
abstract: 'In this paper we formulate multi-target tracking (MTT) as a high-order graph matching problem and propose a l 1 -norm tensor power iteration solution. Concretely, the search for trajectory-observation correspondences in MTT task is cast as a hypergraph matching problem to maximize a multi-linear objective function over all permutations of the associations. This function is defined by a tensor representing the affinity between association tuples where pair-wise similarities, motion consistency and spatial structural information can be embedded expediently. To solve the matching problem, a dual-direction unit l 1 -norm constrained tensor power iteration algorithm is proposed. Additionally, as measuring the appearance affinity with features extracted from the rectangle patch, which is adopted in most methods, has a weak discrimination when bounding boxes overlap each other heavily, we present a deep pair-wise appearance similarity metric based on object mask in this paper where just the features from true target region are utilized. Experimental evaluation shows that our approach achieves an accuracy comparable to state-of-the-art online trackers. The source code of the proposed approach will be released to facilitate further studies on the MTT problem.'
publication: '*2018 24th International Conference on Pattern Recognition (ICPR)*'
---
