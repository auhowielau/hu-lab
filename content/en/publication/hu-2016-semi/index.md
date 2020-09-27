---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Semi-supervised tensor-based graph embedding learning and its application to
  visual discriminant tracking
subtitle: ''
summary: ''
authors:
- Weiming Hu
- Jin Gao
- Junliang Xing
- Chao Zhang
- Stephen Maybank
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
publishDate: '2020-09-13T18:08:11.871292Z'
publication_types:
- 2
abstract: 'An appearance model adaptable to changes in object appearance is critical in visual object tracking. In this paper, we treat an image patch as a two-order tensor which preserves the original image structure. We design two graphs for characterizing the intrinsic local geometrical structure of the tensor samples of the object and the background. Graph embedding is used to reduce the dimensions of the tensors while preserving the structure of the graphs. Then, a discriminant embedding space is constructed. We prove two propositions forfinding the transformation matrices which are used to map the original tensor samples to the tensor-based graph embedding space. In order to encode more discriminant information in the embedding space, we propose a transfer-learningbased semi-supervised strategy to iteratively adjust the embedding space into which discriminative information obtained from earlier times is transferred. We apply the proposed semi-supervised tensor-based graph embedding learning algorithm to visual tracking. The new tracking algorithm captures an object s appearance characteristics during tracking and uses a particle filter to estimate the optimal object state. Experimental results on the CVPR 2013 benchmark dataset demonstrate the effectiveness of the proposed tracking algorithm.'
publication: '*IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)*'
url_pdf: http://ir.ia.ac.cn/bitstream/173211/11102/1/PAMI16SSTrack.pdf
---
