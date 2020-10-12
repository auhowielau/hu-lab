---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Learning to Predict Salient Faces: A Novel Visual-Audio Saliency Model'
subtitle: ''
summary: ''
authors:
- Yufan Liu
- Minglang Qiao
- Mai Xu
- Bing Li
- Weiming Hu
- Ali Borji
tags: []
categories: []
date: '2020-01-01'
lastmod: 2020-09-14T02:08:08+08:00
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
publishDate: '2020-09-13T18:08:08.647282Z'
publication_types:
- 1
abstract: 'Recently, video streams have occupied a large proportion of Internet traffic, most of which contain human faces. Hence, it is necessary to predict saliency on multiple-face videos, which can provide attention cues for many content based applications. However, most of multiple-face saliency prediction works only consider visual information and ignore audio, which is not consistent with the naturalistic scenarios. Several behavioral studies have established that sound influences human attention, especially during the speech turn-taking in multipleface videos. In this paper, we thoroughly investigate such influences by establishing a large-scale eye-tracking database of Multiple-face Video in Visual-Audio condition (MVVA). Inspired by the findings of our investigation, we propose a novel multi-modal video saliency model consisting of three branches: visual, audio and face. The visual branch takes the RGB frames as the input and encodes them into visual feature maps. The audio and face branches encode the audio signal and multiple cropped faces, respectively. A fusion module is introduced to integrate the information from three modalities, and to generate the final saliency map. Experimental results show that the proposed method outperforms 11 state-of-the-art saliency prediction works. It performs closer to human multi-modal attention.'
publication: '*European Conference on Computer Vision (**ECCV**)*'
url_pdf: https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123650409.pdf
---
