---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Open-book video captioning with retrieve-copy-generate network
subtitle: ''
summary: ''
authors:
- Ziqi Zhang
- Zhongang Qi
- Chunfeng Yuan
- Ying Shan
- Bing Li
- Ying Deng
- Weiming Hu
tags: []
categories: []
date: '2021-01-01'
lastmod: 2021-04-16T15:53:36+08:00
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
publishDate: '2021-04-16T07:53:36.488545Z'
publication_types:
- 1
abstract: 'Due to the rapid emergence of short videos and the requirement for content understanding and creation, the video captioning task has received increasing attention in recent years. In this paper, we convert traditional video captioning task into a new paradigm, \ie, Open-book Video Captioning, which generates natural language under the prompts of video-content-relevant sentences, not limited to the video itself. To address the open-book video captioning problem, we propose a novel Retrieve-Copy-Generate network, where a pluggable video-to-text retriever is constructed to retrieve sentences as hints from the training corpus effectively, and a copy-mechanism generator is introduced to extract expressions from multi-retrieved sentences dynamically. The two modules can be trained end-to-end or separately, which is flexible and extensible. Our framework coordinates the conventional retrieval-based methods with orthodox encoder-decoder methods, which can not only draw on the diverse expressions in the retrieved sentences but also generate natural and accurate content of the video. Extensive experiments on several benchmark datasets show that our proposed approach surpasses the state-of-the-art performance, indicating the effectiveness and promising of the proposed paradigm in the task of video captioning.'
publication: '*IEEE Conference on Computer Vision and Pattern Recognition (**CVPR**)*'
url_pdf: https://arxiv.org/pdf/2103.05284.pdf
---
