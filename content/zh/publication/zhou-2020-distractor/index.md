---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Distractor-aware discrimination learning for online multiple object tracking
subtitle: ''
summary: ''
authors:
- Zongwei Zhou
- Wenhan Luo
- Qiang Wang
- Junliang Xing
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
publishDate: '2020-09-13T18:08:08.203930Z'
publication_types:
- 2
abstract: 'Online multi-object tracking needs to overcome the intrinsic detector deficiencies, e.g., missing detections, false alarms, and inaccurate detection responses, to grow multiple object trajectories without using future information. Various distractions exist during this growing process like background clutters, similar targets, and occlusions, which present a great challenge. We in this work propose a method for learning a distractor-aware discriminative model that can handle continuous missed and inaccurate detection problems due to the occlusion or the motion blur. To deal with target appearance variations, a relational attention learning mechanism is proposed to capture the distinctive target appearances by selectively aggregating features from history states with weights extracted from their appearance topological relationship. Based on the discrimination model, a multi-stage tracking pipeline is designed for automatic trajectory initialization,propagation, and termination. Extensive experimental analyses and comparisons demonstrate its state-of-the-art performance on widely used challenging MOT16 and MOT17 benchmarks. The source code of this work is released to facilitate further studies on the multi-object tracking problem.'
publication: '*Pattern Recognition*'
---
