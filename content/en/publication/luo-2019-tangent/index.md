---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Tangent Fisher vector on matrix manifolds for action recognition
subtitle: ''
summary: ''
authors:
- Guan Luo
- Jiutong Wei
- Weiming Hu
- Stephen J Maybank
tags: []
categories: []
date: '2019-01-01'
lastmod: 2020-09-14T02:08:07+08:00
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
publishDate: '2020-09-13T18:08:07.317300Z'
publication_types:
- 2
abstract: 'In this paper, we address the problem of representing and recognizing human actions from videos on matrix manifolds. For this purpose, we propose a new vector representation method, named tangent Fisher vector, to describe video sequences in the Fisher kernel framework. We first extract dense curved spatio-temporal cuboids from each video sequence. Compared with the traditional straight cuboids, the dense curved spatio-temporal cuboids contain much more local motion information. Each cuboid is then described using a linear dynamical system (LDS) to simultaneously capture the local appearance and dynamics. Furthermore, a simple yet efficient algorithm is proposed to learn the LDS parameters and approximate the observability matrix at the same time. Each video sequence is thus represented by a set of LDSs. Considering that each LDS can be viewed as a point in a Grassmann manifold, we propose to learn an intrinsic GMM on the manifold to cluster the LDS points. Finally a tangent Fisher vector is computed by first accumulating all the tangent vectors in each Gaussian component, and then concatenating the normalized results across all the Gaussian components. A kernel is defined to measure the similarity between tangent Fisher vectors for classification and recognition of a video sequence. This approach is evaluated on the state-of-the-art human action benchmark datasets. The recognition performance is competitive when compared with current state-of-the-art results.'
publication: '*IEEE Transactions on Image Processing (**TIP**)*'
url_pdf: https://eprints.bbk.ac.uk/30050/1/TangentFisherVector.pdf
---
