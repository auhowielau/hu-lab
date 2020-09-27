---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Dual sticky hierarchical Dirichlet process hidden Markov model and its application
  to natural language description of motions
subtitle: ''
summary: ''
authors:
- Weiming Hu
- Guodong Tian
- Yongxin Kang
- Chunfeng Yuan
- Stephen Maybank
tags: []
categories: []
date: '2018-01-01'
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
publishDate: '2020-09-13T18:08:13.204727Z'
publication_types:
- 2
abstract: 'In this paper, a new nonparametric Bayesian model called the dual sticky hierarchical Dirichlet process hidden Markov model (HDP-HMM) is proposed for mining activities from a collection of time series data such as trajectories. All the time series data are clustered. Each cluster of time series data, corresponding to a motion pattern, is modeled by an HMM. Our model postulates a set of HMMs that share a common set of states (topics in an analogy with topic models for document processing), but have unique transition distributions. The number of HMMs and the number of topics are both automatically determined. The sticky prior avoids redundant states and makes our HDP-HMM more effective to model multimodal observations. For the application to motion trajectory modeling, topics correspond to motion activities. The learnt topics are clustered into atomic activities which are assigned predicates. We propose a Bayesian inference method to decompose a given trajectory into a sequence of atomic activities. The sources and sinks in the scene are learnt by clustering endpoints (origins and destinations) of trajectories. The semantic motion regions are learnt using the points in trajectories. On combining the learnt sources and sinks, the learnt semantic motion regions, and the learnt sequence of atomic activities, the action represented by a trajectory can be described in natural language in as automatic a way as possible. The effectiveness of our dual sticky HDP-HMM is validated on several trajectory datasets. The effectiveness of the natural language descriptions for motions is demonstrated on the vehicle trajectories extracted from a traffic scene.'
publication: '*IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)*'
url_pdf: http://eprints.bbk.ac.uk/19747/2/DualSticky.pdf
---
