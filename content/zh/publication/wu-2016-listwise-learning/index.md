---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Listwise learning to rank by exploring structure of objects
subtitle: ''
summary: ''
authors:
- Ou Wu
- Qiang You
- Xue Mao
- Fen Xia
- Fei Yuan
- Weiming Hu
tags: []
categories: []
date: '2016-01-01'
lastmod: 2020-09-14T23:21:11+08:00
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
publishDate: '2020-09-14T15:21:10.991790Z'
publication_types:
- 2
abstract: 'Listwise learning to rank (LTR) is aimed at constructing a ranking model from listwise training data to order objects. In most existing studies, each training instance consists of a set of objects described by preference features. In a preference feature space for the objects in training, the structure of the objects is associated with the absolute preference degrees for the objects. The degrees significantly influence the ordering of the objects. Nevertheless, the structure of the training objects in their preference feature space has rarely been studied. In addition, most listwise LTR algorithms yield a single linear ranking model for all objects, but this ranking model may be insufficient to capture the underlying nonlinear ranking mechanism among all objects. This study proposes a divide-and-train method to learn a nonlinear ranking model from listwise training data. First, a rank-preserving clustering approach is used to infer the structure of objects in their preference feature space and all the objects in training data are divided into several clusters. Each cluster is assumed to correspond to a preference degree and an ordinal regression function is then learned. Second, considering that relations exist among the clusters, a multi-task listwise ranking approach is then employed to train linear ranking functions for all the clusters (or preference degrees) simultaneously. Our proposed method utilizes both the (relative) preferences among objects and the intrinsic structure of objects. Experimental results on benchmark data sets suggest that the proposed method outperforms state-oft-the-art listwise LTR algorithms.'
publication: '*IEEE Transactions on Knowledge and Data Engineering (TKDD)*'
url_pdf: http://ir.ia.ac.cn/bitstream/173211/12021/1/tkde1.pdf
---
