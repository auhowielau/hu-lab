---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Discriminant tracking using tensor representation with semi-supervised improvement
subtitle: ''
summary: ''
authors:
- Jin Gao
- Junliang Xing
- Weiming Hu
- Steve Maybank
tags: []
categories: []
date: '2013-01-01'
lastmod: 2020-10-11T15:36:48+08:00
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
publishDate: '2020-10-11T07:36:48.692416Z'
publication_types:
- 1
abstract: 'Visual tracking has witnessed growing methods in object representation, which is crucial to robust tracking. The dominant mechanism in object representation is using image features encoded in a vector as observations to perform tracking, without considering that an image is intrinsically a matrix, or a 2 nd -order tensor. Thus approaches following this mechanism inevitably lose a lot of useful information, and therefore cannot fully exploit the spatial correlations within the 2D image ensembles. In this paper, we address an image as a 2 nd -order tensor in its original form, and find a discriminative linear embedding space approximation to the original nonlinear submanifold embedded in the tensor space based on the graph embedding framework. We specially design two graphs for characterizing the intrinsic local geometrical structure of the tensor space, so as to retain more discriminant information when reducing the dimension along certain tensor dimensions. However, spatial correlations within a tensor are not limited to the elements along these dimensions. This means that some part of the discriminant information may not be encoded in the embedding space. We introduce a novel technique called semi-supervised improvement to iteratively adjust the embedding space to compensate for the loss of discriminant information, hence improving the performance of our tracker. Experimental results on challenging videos demonstrate the effectiveness and robustness of the proposed tracker.'
publication: '*IEEE International Conference on Computer Vision (**ICCV**)*'
url_pdf: https://www.cv-foundation.org/openaccess/content_iccv_2013/papers/Gao_Discriminant_Tracking_Using_2013_ICCV_paper.pdf
year: ~2014
---
