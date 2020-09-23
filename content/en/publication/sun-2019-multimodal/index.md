---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Multimodal Semantic Attention Network for Video Captioning
subtitle: ''
summary: ''
authors:
- Liang Sun
- Bing Li
- Chunfeng Yuan
- Zhengjun Zha
- Weiming Hu
tags: []
categories: []
date: '2019-01-01'
lastmod: 2020-09-14T02:08:10+08:00
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
publishDate: '2020-09-13T18:08:10.126453Z'
publication_types:
- 1
abstract: 'Inspired by the fact that different modalities in videos carry complementary information, we propose a Multimodal Semantic Attention Network(MSAN), which is a new encoder-decoder framework incorporating multimodal semantic attributes for video captioning. In the encoding phase, we detect and generate multimodal semantic attributes by formulating it as a multi-label classification problem. Moreover, we add auxiliary classification loss to our model that can obtain more effective visual features and high-level multimodal semantic attribute distributions for sufficient video encoding. In the decoding phase, we extend each weight matrix of the conventional LSTM to an ensemble of attribute-dependent weight matrices, and employ attention mechanism to pay attention to different attributes at each time of the captioning process. We evaluate algorithm on two popular public benchmarks: MSVD and MSR-VTT, achieving competitive results with current state-of-the-art across six evaluation metrics.'
publication: '*IEEE International Conference on Multimedia and Expo (ICME)*'
url_pdf: https://arxiv.org/pdf/1905.02963
---
