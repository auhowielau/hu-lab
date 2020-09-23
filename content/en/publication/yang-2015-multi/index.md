---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Multi-feature max-margin hierarchical Bayesian model for action recognition
subtitle: ''
summary: ''
authors:
- Shuang Yang
- Chunfeng Yuan
- Baoxin Wu
- Weiming Hu
- Fangshi Wang
tags: []
categories: []
date: '2015-01-01'
lastmod: 2020-09-14T02:08:17+08:00
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
publishDate: '2020-09-13T18:08:17.022681Z'
publication_types:
- 1
abstract: 'In this paper, a multi-feature max-margin hierarchical Bayesian model (M3HBM) is proposed for action recognition. Different from existing methods which separate representation and classification into two steps, M3HBM jointly learns a high-level representation by combining a hierarchical generative model (HGM) and discriminative max-margin classifiers in a unified Bayesian framework. Specifically, HGM is proposed to represent actions by distributions over latent spatial temporal patterns (STPs) which are learned from multiple feature modalities and shared among different classes. For recognition, we employ Gibbs classifiers to minimize the expected loss function based on the max-margin principle and use the classifiers as regularization terms of M3HBM to perform Bayeisan estimation for classifier parameters together with the learning of STPs. In addition, multi-task learning is applied to learn the model from multiple feature modalities for different classes. For test videos, we obtain the representations by the inference process and perform action recognition by the learned Gibbs classifiers. For the learning and inference process, we derive an efficient Gibbs sampling algorithm to solve the proposed M3HBM. Extensive experiments on several datasets demonstrate both the representation power and the classification capability of our approach for action recognition.'
publication: '*IEEE Conference on Computer Vision and Pattern Recognition (CVPR)*'
url_pdf: http://openaccess.thecvf.com/content_cvpr_2015/papers/Yang_Multi-Feature_Max-Margin_Hierarchical_2015_CVPR_paper.pdf
---
