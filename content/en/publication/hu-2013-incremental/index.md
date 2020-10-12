---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: An incremental DPMM-based method for trajectory clustering, modeling, and retrieval
subtitle: ''
summary: ''
authors:
- Weiming Hu
- Xi Li
- Guodong Tian
- Stephen Maybank
- Zhongfei Zhang
tags: []
categories: []
date: '2013-01-01'
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
publishDate: '2020-09-27T08:54:16.714701Z'
publication_types:
- 2
abstract: 'Trajectory analysis is the basis for many applications, such as indexing of motion events in videos, activity recognition, and surveillance. In this paper, the Dirichlet process mixture model (DPMM) is applied to trajectory clustering, modeling, and retrieval. We propose an incremental version of a DPMM-based clustering algorithm and apply it to cluster trajectories. An appropriate number of trajectory clusters is determined automatically. When trajectories belonging to new clusters arrive, the new clusters can be identified online and added to the model without any retraining using the previous data. A time-sensitive Dirichlet process mixture model (tDPMM) is applied to each trajectory cluster for learning the trajectory pattern which represents the time-series characteristics of the trajectories in the cluster. Then, a parameterized index is constructed for each cluster. A novel likelihood estimation algorithm for the tDPMM is proposed, and a trajectory-based video retrieval model is developed. The tDPMM-based probabilistic matching method and the DPMM-based model growing method are combined to make the retrieval model scalable and adaptable. Experimental comparisons with state-of-the-art algorithms demonstrate the effectiveness of our algorithm.'
publication: '*IEEE Transactions on Pattern Analysis and Machine Intelligence (**TPAMI**)*'
year: '~2014'
url_pdf: http://www.nlpr.ia.ac.cn/2013papers/gjkw/gk4.pdf
---
