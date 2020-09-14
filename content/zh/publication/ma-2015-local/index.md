---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Local subspace collaborative tracking
subtitle: ''
summary: ''
authors:
- Lin Ma
- Xiaoqin Zhang
- Weiming Hu
- Junliang Xing
- Jiwen Lu
- Jie Zhou
tags: []
categories: []
date: '2015-01-01'
lastmod: 2020-09-14T02:08:17+08:00
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
publishDate: '2020-09-13T18:08:17.168300Z'
publication_types:
- 1
abstract: 'Subspace models have been widely used for appearance based object tracking. Most existing subspace based trackers employ a linear subspace to represent object appearances, which are not accurate enough to model large variations of objects. To address this, this paper presents a local subspace collaborative tracking method for robust visual tracking, where multiple linear and nonlinear subspaces are learned to better model the nonlinear relationship of object appearances. First, we retain a set of key samples and compute a set of local subspaces for each key sample. Then, we construct a hyper sphere to represent the local nonlinear subspace for each key sample. The hyper sphere of one key sample passes the local key samples and also is tangent to the local linear subspace of the specific key sample. In this way, we are able to represent the nonlinear distribution of the key samples and also approximate the local linear subspace near the specific key sample, so that local distributions of the samples can be represented more accurately. Experimental results on challenging video sequences demonstrate the effectiveness of our method.'
publication: '*Proceedings of the IEEE International Conference on Computer Vision*'
url_pdf: http://openaccess.thecvf.com/content_iccv_2015/papers/Ma_Local_Subspace_Collaborative_ICCV_2015_paper.pdf
---
