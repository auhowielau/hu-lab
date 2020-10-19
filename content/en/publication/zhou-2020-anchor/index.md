---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Anchor-free one-stage online multi-object tracking
subtitle: ''
summary: ''
authors:
- Zongwei Zhou
- Yangxi Li
- Jin Gao
- Junliang Xing
- Liang Li
- Weiming Hu
tags: []
categories: []
date: '2020-01-01'
lastmod: 2020-09-14T02:08:08+08:00
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
publishDate: '2020-09-13T18:08:08.057294Z'
publication_types:
- 1
abstract: 'Current multi-object tracking (MOT) algorithms are dominated by the tracking-by-detection paradigm, which divides MOT into three independent sub-tasks of target detection, appearance embedding, and data association. To improve the efficiency of this tracking paradigm, this paper presents an anchor-free one-stage learning framework to perform target detection and appearance embedding in a unified network, which learns for each point in the feature pyramid of the input image an object detection prediction and a feature representation. Two effective training strategies are proposed to reduce missed detections in dense pedestrian scenes. Moreover, an improved non-maximum suppression procedure is introduced to obtain more accurate box detections and appearance embeddings by taking the box spatial and appearance similarities into account simultaneously. Experiments show that our MOT algorithm achieves real-time tracking speed while obtaining comparable tracking performance to state-of-the-art MOT trackers. Code will be released to facilitate further studies of this problem.'
publication: '*Pattern Recognition and Computer Vision (**PRCV best paper**)*'
---
