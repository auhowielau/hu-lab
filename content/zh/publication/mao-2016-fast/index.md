---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Fast kernel SVM training via support vector identification
subtitle: ''
summary: ''
authors:
- Xue Mao
- Zhouyu Fu
- Ou Wu
- Weiming Hu
tags: []
categories: []
date: '2016-01-01'
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
publishDate: '2020-09-13T18:08:13.960717Z'
publication_types:
- 1
abstract: 'Training kernel SVM on large datasets suffers from high computational complexity and requires a large amount of memory. However, a desirable property of SVM is that its decision function is solely determined by the support vectors, a subset of training examples with non-vanishing weights. This motivates a novel efficient algorithm for training kernel SVM via support vector identification. The efficient training algorithm involves two steps. In the first step, we randomly sample the training data without replacement several times, each time a small subset of training data is sampled. Then a kernel SVM is trained on each subset, and the resulting kernel SVM models are used to identify the support vectors on the margin. In the second step, an optimization problem is solved to estimate the Lagrange multipliers corresponding to these support vectors. After obtaining the support vectors and Lagrange multipliers, we can approximate the decision function of kernel SVM. Due to the cubic complexity of standard kernel SVM training algorithm, training many kernel SVMs on small subsets of training data is much more efficient than training a single kernel SVM on the whole training data especially for large datasets. Therefore, our algorithm has better scalability than kernel SVM. Besides, training SVMs on each subset can be done independently, and hence our algorithm can be easily parallelized for further speedup. Since our algorithm only identifies the support vectors on the margin, it produces less number of support vectors as compared to that produced by standard kernel SVM. This makes our algorithm more efficient in prediction too. Experimental results show that our method outperforms state-of-the-art methods and achieves performance on par with the kernel SVM albeit with much improved efficiency.'
publication: '*2016 23rd International Conference on Pattern Recognition (ICPR)*'
url_pdf: https://projet.liris.cnrs.fr/imagine/pub/proceedings/ICPR-2016/media/files/0649.pdf
---
