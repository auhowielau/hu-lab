---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Single and multiple object tracking using log-Euclidean Riemannian subspace
  and block-division appearance model
subtitle: ''
summary: ''
authors:
- Weiming Hu
- Xi Li
- Wenhan Luo
- Xiaoqin Zhang
- Stephen Maybank
- Zhongfei Zhang
tags: []
categories: []
date: '2012-01-01'
lastmod: 2020-09-27T16:54:16+08:00
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
publishDate: '2020-09-27T08:54:16.840337Z'
publication_types:
- 2
abstract: 'Object appearance modeling is crucial for tracking objects, especially in videos captured by nonstationary cameras and for reasoning about occlusions between multiple moving objects. Based on the log-euclidean Riemannian metric on symmetric positive definite matrices, we propose an incremental log-euclidean Riemannian subspace learning algorithm in which covariance matrices of image features are mapped into a vector space with the log-euclidean Riemannian metric. Based on the subspace learning algorithm, we develop a log-euclidean block-division appearance model which captures both the global and local spatial layout information about object appearances. Single object tracking and multi-object tracking with occlusion reasoning are then achieved by particle filtering-based Bayesian state inference. During tracking, incremental updating of the log-euclidean block-division appearance model captures changes in object appearance. For multi-object tracking, the appearance models of the objects can be updated even in the presence of occlusions. Experimental results demonstrate that the proposed tracking algorithm obtains more accurate results than six state-of-the-art tracking algorithms.'
publication: '*IEEE Transactions on Pattern Analysis and Machine Intelligence (**TPAMI**)*'
year: '~2014'
url_pdf: http://eprints.bbk.ac.uk/13325/1/13325.pdf
---
