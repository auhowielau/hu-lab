---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Optimizing locally linear classifiers with supervised anchor point learning
subtitle: ''
summary: ''
authors:
- Xue Mao
- Zhouyu Fu
- Ou Wu
- Weiming Hu
tags: []
categories: []
date: '2015-01-01'
lastmod: 2020-09-14T02:08:16+08:00
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
publishDate: '2020-09-13T18:08:16.435241Z'
publication_types:
- 1
abstract: 'Kernel SVM suffers from high computational complexity when dealing with large-scale nonlinear datasets. To address this issue, locally linear classifiers have been proposed for approximating nonlinear decision boundaries with locally linear functions using a local coding scheme. The effectiveness of such coding scheme depends heavily on the quality of anchor points chosen to produce the local codes. Existing methods usually involve a phase of unsupervised anchor point learning followed by supervised classifier learning. Thus, the anchor points and classifiers are obtained separately whereas the learned anchor points may not be optimal for the discriminative task. In this paper, we present a novel fully supervised approach for anchor point learning. A single optimization problem is formulated over both anchor point and classifier variables, optimizing the initial anchor points jointly with the classifiers to minimize the classification risk. Experimental results show that our method outperforms other competitive methods which employ unsupervised anchor point learning and achieves performance on par with the kernel SVM albeit with much improved efficiency.'
publication: '*International Joint Conference on Artificial Intelligence (IJCAI)*'
url_pdf: http://ir.ia.ac.cn/bitstream/173211/12023/1/11326-50079-1-PB.pdf
---
