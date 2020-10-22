---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Anomaly detection using local kernel density estimation and context-based regression
subtitle: ''
summary: ''
authors:
- Weiming Hu
- Jun Gao
- Bing Li
- Ou Wu
- Junping Du
- Stephen John Maybank
tags: []
categories: []
date: '2018-01-01'
lastmod: 2020-10-22T11:02:25+08:00
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
publishDate: '2020-10-22T03:02:25.539599Z'
publication_types:
- 2
abstract: 'Current local density-based anomaly detection methods are limited in that the local density estimation and the neighborhood density estimation are not accurate enough for complex and large databases, and the detection performance depends on the size parameter of the neighborhood. In this paper, we propose a new kernel function to estimate samples’ local densities and propose a weighted neighborhood density estimation to increase the robustness to changes in the neighborhood size. We further propose a local kernel regression estimator and a hierarchical strategy for combining information from the multiple scale neighborhoods to refine anomaly factors of samples. We apply our general anomaly detection method to image saliency detection by regarding salient pixels in objects as anomalies to the background regions. Local density estimation in the visual feature space and kernel-based saliency score propagation in the image enable the assignment of similar saliency values to homogenous object regions. Experimental results on several benchmark datasets demonstrate that our anomaly detection methods overall outperform several state-of-art anomaly detection methods. The effectiveness of our image saliency detection method is validated by comparison with several state-of-art saliency detection methods.'
publication: '*IEEE Transactions on Knowledge and Data Engineering (**TKDE**)*'
url_pdf: http://eprints.bbk.ac.uk/25154/1/OutlierDetection.pdf
---
