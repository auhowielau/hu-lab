---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Deeper and wider siamese networks for real-time visual tracking
subtitle: ''
summary: ''
authors:
- Zhipeng Zhang
- Houwen Peng
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
publishDate: '2020-09-13T18:08:10.273061Z'
publication_types:
- 1
abstract: 'Siamese networks have drawn great attention in visual tracking because of their balanced accuracy and speed. However, the backbone networks used in Siamese trackers are relatively shallow, such as AlexNet, which does not fully take advantage of the capability of modern deep neural networks. In this paper, we investigate how to leverage deeper and wider convolutional neural networks to enhance tracking robustness and accuracy. We observe that direct replacement of backbones with existing powerful architectures, such as ResNet and Inception, does not bring improvements. The main reasons are that 1) large increases in the receptive field of neurons lead to reduced feature discriminability and localization precision; and 2) the network padding for convolutions induces a positional bias in learning. To address these issues, we propose new residual modules to eliminate the negative impact of padding, and further design new architectures using these modules with controlled receptive field size and network stride. The designed architectures are lightweight and guarantee real-time tracking speed when applied to SiamFC and SiamRPN. Experiments show that solely due to the proposed network architectures, our SiamFC+ and SiamRPN+ obtain up to 9.8%/6.3% (AUC), 23.3%/8.8% (EAO) and 24.4%/25.0% (EAO) relative improvements over the original versions on the OTB-15, VOT-16 and VOT-17 datasets, respectively.'
publication: '*IEEE Conference on Computer Vision and Pattern Recognition (CVPR)*'
url_pdf: http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Deeper_and_Wider_Siamese_Networks_for_Real-Time_Visual_Tracking_CVPR_2019_paper.pdf
url_code: https://github.com/researchmm/SiamDW
---
