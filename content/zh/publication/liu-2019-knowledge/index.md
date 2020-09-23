---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Knowledge distillation via instance relationship graph
subtitle: ''
summary: ''
authors:
- Yufan Liu
- Jiajiong Cao
- Bing Li
- Chunfeng Yuan
- Weiming Hu
- Yangxi Li
- Yunqiang Duan
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
publishDate: '2020-09-13T18:08:09.978876Z'
publication_types:
- 1
abstract: 'The key challenge of knowledge distillation is to extract general, moderate and sufficient knowledge from a teacher network to guide a student network. In this paper, a novel Instance Relationship Graph (IRG) is proposed for knowledge distillation. It models three kinds of knowledge, including instance features, instance relationships and feature space transformation, while the latter two kinds of knowledge are neglected by previous methods. Firstly, the IRG is constructed to model the distilled knowledge of one network layer, by considering instance features and instance relationships as vertexes and edges respectively. Secondly, an IRG transformation is proposed to models the feature space transformation across layers. It is more moderate than directly mimicking the features at intermediate layers. Finally, hint loss functions are designed to force a students IRGs to mimic the structures of a teachers IRGs. The proposed method effectively captures the knowledge along the whole network via IRGs, and thus shows stable convergence and strong robustness to different network architectures. In addition, the proposed method shows superior performance over existing methods on datasets of various scales.'
publication: '*IEEE Conference on Computer Vision and Pattern Recognition (CVPR)*'
url_pdf: http://openaccess.thecvf.com/content_CVPR_2019/papers/Liu_Knowledge_Distillation_via_Instance_Relationship_Graph_CVPR_2019_paper.pdf
---
