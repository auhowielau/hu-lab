---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'SCNN: Sequential convolutional neural network for human action recognition
  in videos'
subtitle: ''
summary: ''
authors:
- Hao Yang
- Chunfeng Yuan
- Junliang Xing
- Weiming Hu
tags: []
categories: []
date: '2017-01-01'
lastmod: 2020-09-14T02:08:13+08:00
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
publishDate: '2020-09-13T18:08:12.919524Z'
publication_types:
- 1
abstract: 'Convolutional Neural Network (CNN) and Recurrent Neural Network (RNN) are two typical kinds of neural networks. While CNN models have achieved great success on image recognition due to their strong abilities in abstracting spatial information from multiple levels, RNN models have not achieved significant progress in video analyzing tasks (e.g. action recognition), although RNN can inherently model temporal dependencies from videos. In this work, we propose a Sequential Convolutional Neural Network, denoted as SCNN, to extract effective spatial-temporal features from videos, thus incorporating the strengths of both convolutional operation and recurrent operation. Our SCNN model extends RNN to directly process feature maps, rather than vectors flattened from feature maps, to keep spatial structures of the inputs. It replaces the full connections of RNN with convolutional connections to decrease parameter numbers, computational cost, and over-fitting risk. Moreover, we introduce asymmetric convolutional layers into SCNN to reduce parameter numbers and computational cost further. Our final SCNN deep architecture used for action recognition achieves very good performances on two challenging benchmarks, UCF-101 and HMDB-51, outperforming many state-of-the-art methods.'
publication: '*2017 IEEE International Conference on Image Processing (ICIP)*'
url_pdf: http://ir.ia.ac.cn/bitstream/173211/20086/1/0000355-yanghaoICIP2017.pdf
---
