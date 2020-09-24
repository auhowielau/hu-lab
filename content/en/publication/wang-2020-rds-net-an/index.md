---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'RDSNet: A New Deep Architecture for Reciprocal Object Detection and Instance Segmentation'
subtitle: ''
summary: ''
authors:
- Shaoru Wang
- Yongchao Gong
- Junliang Xing
- Lichao Huang
- Chang Huang
- Weiming Hu
tags: []
categories: []
date: '2020-01-01'
lastmod: 2020-08-23T16:10:10+08:00
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
publishDate: '2020-08-23T08:10:10.648576Z'
publication_types: ["1"]

abstract: 'Object detection and instance segmentation are two fundamental computer vision tasks. They are closely correlated but their relations have not yet been fully explored in most previous work. This paper presents RDSNet, a novel deep architecture for reciprocal object detection and instance segmentation. To reciprocate these two tasks, we design a two-stream structure to learn features on both the object level (i.e., bounding boxes) and the pixel level (i.e., instance masks) jointly. Within this structure, information from the two streams is fused alternately, namely information on the object level introduces the awareness of instance and translation variance to the pixel level, and information on the pixel level refines the localization accuracy of objects on the object level in return. Specifically, a correlation module and a cropping module are proposed to yield instance masks, as well as a mask based boundary refinement module for more accurate bounding boxes. Extensive experimental analyses and comparisons on the COCO dataset demonstrate the effectiveness and efficiency of RDSNet. The source code is available at https://github.com/wangsr126/RDSNet.'
publication: '*AAAI Conference on Artificial Intelligence (AAAI)*'

links:
# - name: Custom Link
#   url: https://baidu.com
url_pdf: https://arxiv.org/pdf/1912.05070.pdf
url_code: 'https://github.com/wangsr126/RDSNet'
---
