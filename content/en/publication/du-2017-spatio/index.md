---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Spatio-temporal self-organizing map deep network for dynamic object detection
  from videos
subtitle: ''
summary: ''
authors:
- Yang Du
- Chunfeng Yuan
- Bing Li
- Weiming Hu
- Stephen Maybank
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
publishDate: '2020-09-13T18:08:12.596354Z'
publication_types:
- 1
abstract: 'In dynamic object detection, it is challenging to construct an effective model to sufficiently characterize the spatial-temporal properties of the background. This paper proposes a new Spatio-Temporal Self-Organizing Map (STSOM) deep network to detect dynamic objects in complex scenarios. The proposed approach has several contributions: First, a novel STSOM shared by all pixels in a video frame is presented to efficiently model complex background. We exploit the fact that the motions of complex background have the global variation in the space and the local variation in the time, to train STSOM using the whole frames and the sequence of a pixel over time to tackle the variance of complex background. Second, a Bayesian parameter estimation based method is presented to learn thresholds automatically for all pixels to filter out the background. Last, in order to model the complex background more accurately, we extend the single-layer STSOM to the deep network. Then the background is filtered out layer by layer. Experimental results on CDnet 2014 dataset demonstrate that the proposed STSOM deep network outperforms numerous recently proposed methods in the overall performance and in most categories of scenarios.'
publication: '*IEEE Conference on Computer Vision and Pattern Recognition (**CVPR**)*'
url_pdf: http://openaccess.thecvf.com/content_cvpr_2017/papers/Du_Spatio-Temporal_Self-Organizing_Map_CVPR_2017_paper.pdf
---
