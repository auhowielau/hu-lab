---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Visual tracking via spatially aligned correlation filters network
subtitle: ''
summary: ''
authors:
- Mengdan Zhang
- Qiang Wang
- Junliang Xing
- Jin Gao
- Peixi Peng
- Weiming Hu
- Steve Maybank
tags: []
categories: []
date: '2018-01-01'
lastmod: 2020-09-14T02:08:11+08:00
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
publishDate: '2020-09-13T18:08:11.291843Z'
publication_types:
- 1
abstract: 'Correlation filters based trackers rely on a periodic assumption of the search sample to efficiently distinguish the target from the background. This assumption however yields undesired boundary effects and restricts aspect ratios of search samples. To handle these issues, an end-to-end deep architecture is proposed to incorporate geometric transformations into a correlation filters based network. This architecture introduces a novel spatial alignment module, which provides continuous feedback for transforming the target from the border to the center with a normalized aspect ratio. It enables correlation filters to work on well-aligned samples for better tracking. The whole architecture not only learns a generic relationship between object geometric transformations and object appearances, but also learns robust representations coupled to correlation filters in case of various geometric transformations. This lightweight architecture permits real-time speed. Experiments show our tracker effectively handles boundary effects and aspect ratio variations, achieving state-of-the-art tracking results on three benchmarks.'
publication: '*European Conference on Computer Vision (**ECCV**)*'
url_pdf: http://openaccess.thecvf.com/content_ECCV_2018/papers/mengdan_zhang_Visual_Tracking_via_ECCV_2018_paper.pdf
---
