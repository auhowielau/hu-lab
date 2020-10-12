---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Interaction-aware spatio-temporal pyramid attention networks for action classification
subtitle: ''
summary: ''
authors:
- Yang Du
- Chunfeng Yuan
- Bing Li
- Lili Zhao
- Yangxi Li
- Weiming Hu
tags: []
categories: []
date: '2018-01-01'
lastmod: 2020-09-14T02:08:11+08:00
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
publishDate: '2020-09-13T18:08:11.147262Z'
publication_types:
- 1
abstract: 'Local features at neighboring spatial positions in feature maps have high correlation since their receptive fields are often overlapped. Self-attention usually uses the weighted sum (or other functions) with internal elements of each local feature to obtain its weight score, which ignores interactions among local features. To address this, we propose an effective interaction-aware self-attention model inspired by PCA to learn attention maps. Furthermore, since different layers in a deep network capture feature maps of different scales, we use these feature maps to construct a spatial pyramid and then utilize multi-scale information to obtain more accurate attention scores, which are used to weight the local features in all spatial positions of feature maps to calculate attention maps. Moreover, our spatial pyramid attention is unrestricted to the number of its input feature maps so it is easily extended to a spatio-temporal version. Finally, our model is embedded in general CNNs to form end-to-end attention networks for action classification. Experimental results show that our method achieves the state-of-the-art results on the UCF101, HMDB51 and untrimmed Charades.'
publication: '*European Conference on Computer Vision (**ECCV**)*'
url_pdf: http://openaccess.thecvf.com/content_ECCV_2018/papers/Yang_Du_Interaction-aware_Spatio-temporal_Pyramid_ECCV_2018_paper.pdf
---
