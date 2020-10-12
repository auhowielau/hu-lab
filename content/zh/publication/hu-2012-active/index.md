---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Active contour-based visual tracking by integrating colors, shapes, and motions
subtitle: ''
summary: ''
authors:
- Weiming Hu
- Xue Zhou
- Wei Li
- Wenhan Luo
- Xiaoqin Zhang
- Stephen Maybank
tags: []
categories: []
date: '2012-01-01'
lastmod: 2020-09-27T16:54:17+08:00
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
publishDate: '2020-09-27T08:54:17.342993Z'
publication_types:
- 2
abstract: 'In this paper, we present a framework for active contour-based visual tracking using level sets. The main components of our framework include contour-based tracking initialization, color-based contour evolution, adaptive shape-based contour evolution for non-periodic motions, dynamic shape-based contour evolution for periodic motions, and the handling of abrupt motions. For the initialization of contour-based tracking, we develop an optical flow-based algorithm for automatically initializing contours at the first frame. For the color-based contour evolution, Markov random field theory is used to measure correlations between values of neighboring pixels for posterior probability estimation. For adaptive shape-based contour evolution, the global shape information and the local color information are combined to hierarchically evolve the contour, and a flexible shape updating model is constructed. For the dynamic shape-based contour evolution, a shape mode transition matrix is learnt to characterize the temporal correlations of object shapes. For the handling of abrupt motions, particle swarm optimization is adopted to capture the global motion which is applied to the contour in the current frame to produce an initial contour in the next frame.'
publication: '*IEEE Transactions on Image Processing (**TIP**)*'
year: '~2014'
url_pdf: http://www.nlpr.ia.ac.cn/2013papers/gjkw/gk6.pdf
---
