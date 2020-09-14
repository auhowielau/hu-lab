---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'SPCNet: scale position correlation network for end-to-end visual tracking'
subtitle: ''
summary: ''
authors:
- Qiang Wang
- Jin Gao
- Mengdan Zhang
- Junliang Xing
- Weiming Hut
tags: []
categories: []
date: '2018-01-01'
lastmod: 2020-09-14T02:08:09+08:00
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
publishDate: '2020-09-13T18:08:08.941531Z'
publication_types:
- 1
abstract: 'We present a novel Scale Position Correlation Network (SPCNet) for learning to track objects robustly and efficiently. Different from most previous Correlation Filter (CF) based tracking models, SPCNet unifies the feature representation learning and CF based appearance modeling within one end-to-end learnable framework. In particular, SPCNet learns to track objects within a joint scale-position space, and is very effective in learning features for the accurate prediction of object scale and position. To learn our model from end to end, the SPCNet introduces a differentiable correlation filter layer into a Siamese architecture. Therefore, the localization error can be effectively back-propagated through the whole network, enabling fast adaptation of feature learning and appearance modeling for the objects to be tracked. Such task driven feature learning admits a very lightweight design that can be efficiently pre-trained. In addition, the dense appearance modeling in the joint scale-position space is also efficient. It benefits from the computation of gradients within the Fourier frequency domain. Such careful architecture design ensures that SPCNet is effective and efficient with a small model size. Extensive experimental analyses and evaluations on three largest benchmarks, OTB-2013, OTB-2015, and VOT2015, demonstrate its superiority over many state-of-the-art algorithms.'
publication: '*2018 24th International Conference on Pattern Recognition (ICPR)*'
url_pdf: http://ir.ia.ac.cn/bitstream/173211/21613/1/SPCNet.pdf
---
