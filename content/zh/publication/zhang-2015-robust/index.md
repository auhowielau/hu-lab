---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: A robust tracking system for low frame rate video
subtitle: ''
summary: ''
authors:
- Xiaoqin Zhang
- Weiming Hu
- Nianhua Xie
- Hujun Bao
- Stephen Maybank
tags: []
categories: []
date: '2015-01-01'
lastmod: 2020-09-14T02:08:16+08:00
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
publishDate: '2020-09-13T18:08:16.290628Z'
publication_types:
- 2
abstract: 'Tracking in low frame rate (LFR) videos is one of the most important problems in the tracking literature. Most existing approaches treat LFR video tracking as an abrupt motion tracking problem. However, in LFR video tracking applications, LFR not only causes abrupt motions, but also large appearance changes of objects because the objects poses and the illumination may undergo large changes from one frame to the next. This adds extra difficulties to LFR video tracking. In this paper, we propose a robust and general tracking system for LFR videos. The tracking system consists of four major parts: dominant color-spatial based object representation, bin-ratio based similarity measure, annealed particle swarm optimization (PSO) based searching, and an integral image based parameter calculation. The first two parts are combined to provide a good solution to the appearance changes, and the abrupt motion is effectively captured by the annealed PSO based searching. Moreover, an integral image of model parameters is constructed, which provides a look-up table for parameters calculation. This greatly reduces the computational load. Experimental results demonstrate that the proposed tracking system can effectively tackle the difficulties caused by LFR.'
publication: '*International Journal of Computer Vision*'
url_pdf: https://eprints.bbk.ac.uk/13597/1/13597.pdf
---
