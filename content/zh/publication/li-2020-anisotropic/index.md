---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Anisotropic convolution for image classification
subtitle: ''
summary: ''
authors:
- Wenjuan Li
- Bing Li
- Chunfeng Yuan
- Yangxi Li
- Haohao Wu
- Weiming Hu
- Fangshi Wang
tags: []
categories: []
date: '2020-01-01'
lastmod: 2020-09-14T02:08:07+08:00
featured: false
draft: false

url_pdf: files/anisotropic.pdf
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
publishDate: '2020-09-13T18:08:07.619499Z'
publication_types:
- 2
abstract: 'Convolutional neural networks are built upon simple but useful convolution modules. The traditional convolution has a limitation on feature extraction and object localization due to its fixed scale and geometric structure. Besides, the loss of spatial information also restricts the networks performance and depth. To overcome these limitations, this paper proposes a novel anisotropic convolution by adding a scale factor and a shape factor into the traditional convolution. The anisotropic convolution augments the receptive fields flexibly and dynamically depending on the valid sizes of objects. In addition, the anisotropic convolution is a generalized convolution. The traditional convolution, dilated convolution and deformable convolution can be viewed as its special cases. Furthermore, in order to improve the training efficiency and avoid falling into a local optimum, this paper introduces a simplified implementation of the anisotropic convolution. The anisotropic convolution can be applied to arbitrary convolutional networks and the enhanced networks are called ACNs (anisotropic convolutional networks). Experimental results show that ACNs achieve better performance than many state-of-the-art methods and the baseline networks in tasks of image classification and object localization, especially in classification task of tiny images.'
publication: '*IEEE Transactions on Image Processing (**TIP**)*'
---
