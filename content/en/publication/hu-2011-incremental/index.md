---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Incremental tensor subspace learning and its applications to foreground segmentation
  and tracking
subtitle: ''
summary: ''
authors:
- Weiming Hu
- Xi Li
- Xiaoqin Zhang
- Xinchu Shi
- Stephen Maybank
- Zhongfei Zhang
tags: []
categories: []
date: '2011-01-01'
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
publishDate: '2020-09-27T08:54:17.091693Z'
publication_types:
- 2
abstract: 'Appearance modeling is very important for background modeling and object tracking. Subspace learning-based algorithms have been used to model the appearances of objects or scenes. Current vector subspace-based algorithms cannot effectively represent spatial correlations between pixel values. Current tensor subspace-based algorithms construct an offline representation of image ensembles, and current online tensor subspace learning algorithms cannot be applied to background modeling and object tracking. In this paper, we propose an online tensor subspace learning algorithm which models appearance changes by incrementally learning a tensor subspace representation through adaptively updating the sample mean and an eigenbasis for each unfolding matrix of the tensor. The proposed incremental tensor subspace learning algorithm is applied to foreground segmentation and object tracking for grayscale and color image sequences. The new background models capture the intrinsic spatiotemporal characteristics of scenes. The new tracking algorithm captures the appearance characteristics of an object during tracking and uses a particle filter to estimate the optimal object state. Experimental evaluations against state-of-the-art algorithms demonstrate the promise and effectiveness of the proposed incremental tensor subspace learning algorithm, and its applications to foreground segmentation and object tracking.'
publication: '*International Journal of Computer Vision (**IJCV**)*'
year: '~2014'
url_pdf: https://link.springer.com/content/pdf/10.1007/s11263-010-0399-6.pdf
---
