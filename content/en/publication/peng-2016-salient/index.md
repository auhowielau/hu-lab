---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Salient object detection via structured matrix decomposition
subtitle: ''
summary: ''
authors:
- Houwen Peng
- Bing Li
- Haibin Ling
- Weiming Hu
- Weihua Xiong
- Stephen J Maybank
tags: []
categories: []
date: '2016-01-01'
lastmod: 2020-09-14T02:08:12+08:00
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
publishDate: '2020-09-13T18:08:12.016937Z'
publication_types:
- 2
abstract: 'Low-rank recovery models have shown potential for salient object detection, where a matrix is decomposed into a low-rank matrix representing image background and a sparse matrix identifying salient objects. Two deficiencies, however, still exist. First, previous work typically assumes the elements in the sparse matrix are mutually independent, ignoring the spatial and pattern relations of image regions. Second, when the low-rank and sparse matrices are relatively coherent, e.g., when there are similarities between the salient objects and background or when the background is complicated, it is difficult for previous models to disentangle them. To address these problems, we propose a novel structured matrix decomposition model with two structural regularizations: (1) a tree-structured sparsity-inducing regularization that captures the image structure and enforces patches from the same object to have similar saliency values, and (2) a Laplacian regularization that enlarges the gaps between salient objects and the background in feature space. Furthermore, high-level priors are integrated to guide the matrix decomposition and boost the detection. We evaluate our model for salient object detection on five challenging datasets including single object, multiple objects and complex scene images, and show competitive results as compared with 24 state-of-the-art methods in terms of seven performance metrics.'
publication: '*IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)*'
url_pdf: https://eprints.bbk.ac.uk/14986/1/14986.pdf
---
