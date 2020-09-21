---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Recursive Least-Squares Estimator-Aided Online Learning for Visual Tracking
subtitle: ''
summary: ''
authors:
- Jin Gao
- Weiming Hu
- Yan Lu
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
publishDate: '2020-09-13T18:08:08.356099Z'
publication_types:
- 1
abstract: 'Online learning is crucial to robust visual object tracking as it can provide high discrimination power in the presence of background distractors. However, there are two contradictory factors affecting its successful deployment on the real visual tracking platform: the discrimination issue due to the challenges in vanilla gradient descent, which does not guarantee good convergence; the robustness issue due to over-fitting resulting from excessive update with limited memory size (the oldest samples are discarded). Despite many dedicated techniques proposed to somehow treat those issues, in this paper we take a new way to strike a compromise between them based on the recursive least-squares estimation (LSE) algorithm. After connecting each fully-connected layer with LSE separately via normal equations, we further propose an improved mini-batch stochastic gradient descent algorithm for fully-connected network learning with memory retention in a recursive fashion. This characteristic can spontaneously reduce the risk of over-fitting resulting from catastrophic forgetting in excessive online learning. Meanwhile, it can effectively improve convergence though the cost function is computed over all the training samples that the algorithm has ever seen. We realize this recursive LSE-aided online learning technique in the state-of-the-art RT-MDNet tracker, and the consistent improvements on four challenging benchmarks prove its efficiency without additional offline training and too much tedious work on parameter adjusting.'
publication: '*Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern
  Recognition*'
url_pdf: http://openaccess.thecvf.com/content_CVPR_2020/papers/Gao_Recursive_Least-Squares_Estimator-Aided_Online_Learning_for_Visual_Tracking_CVPR_2020_paper.pdf
---
