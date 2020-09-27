---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Fusing R Features and Local Features with Context-Aware Kernels for Action ecognition
subtitle: ''
summary: ''
authors:
- Chunfeng Yuan
- Baoxin Wu
- Xi Li
- Weiming Hu
- Stephen Maybank
- Fangshi Wang
tags: []
categories: []
date: '2016-01-01'
lastmod: 2020-09-14T02:08:15+08:00
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
publishDate: '2020-09-13T18:08:15.127726Z'
publication_types:
- 2
abstract: 'The performance of action recognition in video sequences depends significantly on the representation of actions and the similarity measurement between the representations. In this paper, we combine two kinds of features extracted from the spatio-temporal interest points with context-aware kernels for action recognition. For the action representation, local cuboid features extracted around interest points are very popular using a Bag of Visual Words (BOVW) model. Such representations, however, ignore potentially valuable information about the global spatio-temporal distribution of interest points. We propose a new global feature to capture the detailed geometrical distribution of interest points. It is calculated by using the 3D R transform which is defined as an extended 3D discrete Radon transform, followed by the application of a two-directional two-dimensional principal component analysis. For the similarity measurement, we model a video set as an optimized probabilistic hypergraph and propose a context-aware kernel to measure high order relationships among videos. The context-aware kernel is more robust to the noise and outliers in the data than the traditional context-free kernel which just considers the pairwise relationships between videos. The hyperedges of the hypergraph are constructed based on a learnt Mahalanobis distance metric. Any disturbing information from other classes is excluded from each hyperedge. Finally, a multiple kernel learning algorithm is designed by integrating the l2 norm regularization into a linear SVM classifier to fuse the R feature and the BOVW representation for action recognition. Experimental results on several datasets demonstrate the effectiveness of the proposed approach for action recognition.'
publication: '*International Journal of Computer Vision (IJCV)*'
url_pdf: http://ir.ia.ac.cn/bitstream/173211/10838/1/IJCV%202015%20Features%20and%20Local%20Features%20with%20Context-aware%20Kernels%20for%20Action%20Recognition.pdf
---
