---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'D2C: Deep cumulatively and comparatively learning for human age estimation'
subtitle: ''
summary: ''
authors:
- Kai Li
- Junliang Xing
- Weiming Hu
- Stephen J Maybank
tags: []
categories: []
date: '2017-01-01'
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
publishDate: '2020-09-13T18:08:12.161517Z'
publication_types:
- 2
abstract: 'Age estimation from face images is an important yet difficult task in computer vision. Its main difficulty lies in how to design aging features that remain discriminative in spite of large facial appearance variations. Meanwhile, due to the difficulty of collecting and labeling datasets that contain sufficient samples for all possible ages, the age distributions of most benchmark datasets are often imbalanced, which makes this problem more challenge. In this work, we try to solve these difficulties by means of the mainstream deep learning techniques. Specifically, we use a convolutional neural network which can learn discriminative aging features from raw face images without any handcrafting. To combat the sample imbalance problem, we propose a novel cumulative hidden layer which is supervised by a point-wise cumulative signal. With this cumulative hidden layer, our model is learnt indirectly using faces with neighbouring ages and thus alleviate the sample imbalance problem. In order to learn more effective aging features, we further propose a comparative ranking layer which is supervised by a pair-wise comparative signal. This comparative ranking layer facilitates aging feature learning and improves the performance of the main age estimation task. In addition, since one face can be included in many different training pairs, we can make full use of the limited training data. It is noted that both of these two novel layers are differentiable, so our model is end-to-end trainable. Extensive experiments on the two of the largest benchmark datasets show that our deep age estimation model gains notable advantage on accuracy when compared against existing methods.'
publication: '*Pattern Recognition (**PR**)*'
url_pdf: http://ir.ia.ac.cn/bitstream/173211/15080/1/PR17D2C.pdf
---
