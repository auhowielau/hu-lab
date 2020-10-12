---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Asymmetric 3d convolutional neural networks for action recognition
subtitle: ''
summary: ''
authors:
- Hao Yang
- Chunfeng Yuan
- Bing Li
- Yang Du
- Junliang Xing
- Weiming Hu
- Stephen J Maybank
tags: []
categories: []
date: '2019-01-01'
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
publishDate: '2020-09-13T18:08:09.531917Z'
publication_types:
- 2
abstract: 'Convolutional Neural Network based action recognition methods have achieved significant improvements in recent years. The 3D convolution extends the 2D convolution to the spatial-temporal domain for better analysis of human activities in videos. The 3D convolution, however, involves many more parameters than the 2D convolution. Thus, it is much more expensive on computation, costly on storage, and difficult to learn. This work proposes efficient asymmetric one-directional 3D convolutions to approximate the traditional 3D convolution. To improve the feature learning capacity of asymmetric 3D convolutions, a set of local 3D convolutional networks, called MicroNets, are proposed by incorporating multi-scale 3D convolution branches. Then, an asymmetric 3D-CNN deep model is constructed by MicroNets for the action recognition task. Moreover, to avoid training two networks on the RGB and Flow frames separately as most works do, a simple but effective multi-source enhanced input is proposed, which fuses useful information of the RGB and Flow frame at the pre-processing stage.

The asymmetric 3D-CNN model is evaluated on two of the most challenging action recognition benchmarks, UCF-101 and HMDB-51. The asymmetric 3D-CNN model outperforms all the traditional 3D-CNN models in both effectiveness and efficiency, and its performance is comparable with that of recent state-of-the-art action recognition methods on both benchmarks.'
publication: '*Pattern recognition (**PR**)*'
url_pdf: http://eprints.bbk.ac.uk/23342/1/Asymmetric_3DCNN_PatternRecognition.pdf
---
