---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Towards robust and accurate multi-view and partially-occluded face alignment
subtitle: ''
summary: ''
authors:
- Junliang Xing
- Zhiheng Niu
- Junshi Huang
- Weiming Hu
- Xi Zhou
- Shuicheng Yan
tags: []
categories: []
date: '2017-01-01'
lastmod: 2020-09-14T02:08:14+08:00
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
publishDate: '2020-09-13T18:08:14.540201Z'
publication_types:
- 2
abstract: 'Face alignment acts as an important task in computer vision. Regression-based methods currently dominate the approach to solving this problem, which generally employ a series of mapping functions from the face appearance to iteratively update the face shape hypothesis. One keypoint here is thus how to perform the regression procedure. In this work, we formulate this regression procedure as a sparse coding problem. We learn two relational dictionaries, one for the face appearance and the other one for the face shape, with coupled reconstruction coefficient to capture their underlying relationships. To deploy this model for face alignment, we derive the relational dictionaries in a stage-wised manner to perform close-loop refinement of themselves, i.e., the face appearance dictionary is first learned from the face shape dictionary and then used to update the face shape hypothesis, and the updated face shape dictionary from the shape hypothesis is in return used to refine the face appearance dictionary. To improve the model accuracy, we extend this model hierarchically from the whole face shape to face part shapes, thus both the global and local view variations of a face are captured. To locate facial landmarks under occlusions, we further introduce an occlusion dictionary into the face appearance dictionary to recover face shape from partially occluded face appearance. The occlusion dictionary is learned in a data driven manner from background images to represent a set of elemental occlusion patterns, a sparse combination of which models various practical partial face occlusions. By integrating all these technical innovations, we obtain a robust and accurate approach to locate facial landmarks under different face views and possibly severe occlusions for face images in the wild. Extensive experimental analyses and evaluations on different benchmark datasets, as well as two new datasets built by ourselves, have demonstrated the robustness and accuracy of our proposed model, especially for face images with large view variations and/or severe occlusions.'
publication: '*IEEE Transactions on Pattern Analysis and Machine Intelligence (**TPAMI**)*'
url_pdf: http://ir.ia.ac.cn/bitstream/173211/19746/1/TPAMI17HSRD.pdf
---
