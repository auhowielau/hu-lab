---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Bin ratio-based histogram distances and their application to image classification
subtitle: ''
summary: ''
authors:
- Weiming Hu
- Nianhua Xie
- Ruiguang Hu
- Haibin Ling
- Qiang Chen
- Shuicheng Yan
- Stephen Maybank
tags: []
categories: []
date: '2014-01-01'
lastmod: 2020-09-27T16:54:16+08:00
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
publishDate: '2020-09-27T08:54:16.589009Z'
publication_types:
- 2
abstract: 'Large variations in image background may cause partial matching and normalization problems for histogram-based representations, i.e., the histograms of the same category may have bins which are significantly different, and normalization may produce large changes in the differences between corresponding bins. In this paper, we deal with this problem by using the ratios between bin values of histograms, rather than bin values’ differences which are used in the traditional histogram distances. We propose a bin ratio-based histogram distance (BRD), which is an intra-cross-bin distance, in contrast with previous bin-to-bin distances and cross-bin distances. The BRD is robust to partial matching and histogram normalization, and captures correlations between bins with only a linear computational complexity. We combine the BRD with the ℓ 1 histogram distance and the χ 2 histogram distance to generate the ℓ 1 BRD and the χ 2 BRD, respectively. These combinations exploit and benefit from the robustness of the BRD under partial matching and the robustness of the ℓ 1 and χ 2 distances to small noise. We propose a method for assessing the robustness of histogram distances to partial matching. The BRDs and logistic regression-based histogram fusion are applied to image classification. The experimental results on synthetic data sets show the robustness of the BRDs to partial matching, and the experiments on seven benchmark data sets demonstrate promising results of the BRDs for image classification.'
publication: '*IEEE Transactions on Pattern Analysis and Machine Intelligence (**TPAMI**)*'
year: '~2014'
url_pdf: https://eprints.bbk.ac.uk/13323/1/13323.pdf
---
