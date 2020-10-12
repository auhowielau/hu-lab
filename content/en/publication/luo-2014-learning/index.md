---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Learning human actions by combining global dynamics and local appearance
subtitle: ''
summary: ''
authors:
- Guan Luo
- Shuang Yang
- Guodong Tian
- Chunfeng Yuan
- Weiming Hu
- Stephen J Maybank
tags: []
categories: []
date: '2014-01-01'
lastmod: 2020-10-12T22:18:03+08:00
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
publishDate: '2020-10-12T14:18:03.525489Z'
publication_types:
- 2
abstract: 'In this paper, we address the problem of human action recognition through combining global temporal dynamics and local visual spatio-temporal appearance features. For this purpose, in the global temporal dimension, we propose to model the motion dynamics with robust linear dynamical systems (LDSs) and use the model parameters as motion descriptors. Since LDSs live in a non-Euclidean space and the descriptors are in non-vector form, we propose a shift invariant subspace angles based distance to measure the similarity between LDSs. In the local visual dimension, we construct curved spatio-temporal cuboids along the trajectories of densely sampled feature points and describe them using histograms of oriented gradients (HOG). The distance between motion sequences is computed with the Chi-Squared histogram distance in the bag-of-words framework. Finally we perform classification using the maximum margin distance learning method by combining the global dynamic distances and the local visual distances. We evaluate our approach for action recognition on five short clips data sets, namely Weizmann, KTH, UCF sports, Hollywood2 and UCF50, as well as three long continuous data sets, namely VIRAT, ADL and CRIM13. We show competitive results as compared with current state-of-the-art methods.'
publication: '*IEEE Transactions on Pattern Analysis and Machine Intelligence (**TPAMI featured paper**)*'
url_pdf: https://eprints.bbk.ac.uk/13354/1/13354.pdf
year: ~2014
---
