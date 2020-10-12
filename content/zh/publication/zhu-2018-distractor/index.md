---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Distractor-aware siamese networks for visual object tracking
subtitle: ''
summary: ''
authors:
- Zheng Zhu
- Qiang Wang
- Bo Li
- Wei Wu
- Junjie Yan
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
publishDate: '2020-09-13T18:08:11.435487Z'
publication_types:
- 1
abstract: 'Recently, Siamese networks have drawn great attention in visual tracking community because of their balanced accuracy and speed. However, features used in most Siamese tracking approaches can only discriminate foreground from the non-semantic backgrounds. The semantic backgrounds are always considered as distractors, which hinders the robustness of Siamese trackers. In this paper, we focus on learning distractor-aware Siamese networks for accurate and long-term tracking. To this end, features used in traditional Siamese trackers are analyzed at first. We observe that the imbalanced distribution of training data makes the learned features less discriminative. During the off-line training phase, an effective sampling strategy is introduced to control this distribution and make the model focus on the semantic distractors. During inference, a novel distractor-aware module is designed to perform incremental learning, which can effectively transfer the general embedding to the current video domain. In addition, we extend the proposed approach for long-term tracking by introducing a simple yet effective local-to-global search region strategy. Extensive experiments on benchmarks show that our approach significantly outperforms the state-of-the-arts, yielding 9.6% relative gain in VOT2016 dataset and 35.9% relative gain in UAV20L dataset. The proposed tracker can perform at 160 FPS on short-term benchmarks and 110 FPS on long-term benchmarks.'
publication: '*European Conference on Computer Vision (**ECCV**)*'
url_pdf: http://openaccess.thecvf.com/content_ECCV_2018/papers/Zheng_Zhu_Distractor-aware_Siamese_Networks_ECCV_2018_paper.pdf
url_code: https://github.com/foolwood/DaSiamRPN
---
