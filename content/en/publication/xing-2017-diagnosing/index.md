---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Diagnosing deep learning models for high accuracy age estimation from a single
  image
subtitle: ''
summary: ''
authors:
- Junliang Xing
- Kai Li
- Weiming Hu
- Chunfeng Yuan
- Haibin Ling
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
publishDate: '2020-09-13T18:08:12.309151Z'
publication_types:
- 2
abstract: 'Given a face image, the problem of age estimation is to predict the actual age from the visual appearance of the face. In this work, we investigate this problem by means of the deep learning techniques. We comprehensively diagnose the training and evaluating procedures of the deep learning models for age estimation on two of the largest datasets. Our diagnosis includes three different kinds of formulations for the age estimation problem using five most representative loss functions, as well as three different architectures to incorporate multi-task learning with race and gender classification. We start our diagnoses process from a simple baseline architecture from previous work. With appropriate problem formulation and loss function, we obtain state-of-the-art performance with the simple baseline architecture. By further incorporating our newly proposed deep multi-task learning architecture, the age estimation performance is further improved with high-accuracy race and gender classification results obtained simultaneously. With all the insights gained from the diagnosing process, we finally build a deep multi-task age estimation model which obtains a MAE of 2.96 on the Morph II dataset and 5.75 on the WebFace dataset, both of which improve previous best results by a large margin.'
publication: '*Pattern Recognition (**PR**)*'
url_pdf: http://159.226.21.68/bitstream/173211/15074/1/xing_Diagnosing%20deep%20learning%20models%20for%20high%20accuracy%20age%20estimation%20from%20a%20single%20image.pdf
---
