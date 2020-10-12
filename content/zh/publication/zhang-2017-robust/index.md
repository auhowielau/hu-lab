---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Robust visual object tracking with top-down reasoning
subtitle: ''
summary: ''
authors:
- Mengdan Zhang
- Jiashi Feng
- Weiming Hu
tags: []
categories: []
date: '2017-01-01'
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
publishDate: '2020-09-13T18:08:13.062141Z'
publication_types:
- 1
abstract: 'In generic visual tracking, traditional appearance based trackers suffer from distracting factors like bad lighting or major target deformation, etc., as well as insufficiency of training data. In this work, we propose to exploit the category-specific semantics to boost visual object tracking, and develop a new visual tracking model that augments the appearance based tracker with a top-down reasoning component. The continuous feedback from this reasoning component guides the tracker to reliably identify candidate regions with consistent semantics across frames and localize the target object instance more robustly and accurately. Specifically, a generic object recognition model and a semantic activation map method are deployed to provide effective top-down reasoning about object locations for the tracker. In addition, we develop a voting based scheme for the reasoning component to infer the object semantics. Therefore, even without sufficient training data, the tracker can still obtain reliable top-down clues about the objects. Together with the appearance clues, the tracker can localize objects accurately even in presence of various major distracting factors. Extensive evaluations on two large-scale benchmark datasets, OTB2013 and OTB2015, clearly demonstrate that the top-down reasoning substantially enhances the robustness of the tracker and provides state-of-the-art performance.'
publication: '*ACM international conference on Multimedia (**ACM MM**)*'
url_pdf: http://ir.ia.ac.cn/bitstream/173211/19733/1/sample-sigconf.pdf
---
