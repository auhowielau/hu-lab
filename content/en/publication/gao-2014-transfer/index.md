---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Transfer learning based visual tracking with gaussian processes regression
subtitle: ''
summary: ''
authors:
- Jin Gao
- Haibin Ling
- Weiming Hu
- Junliang Xing
tags: []
categories: []
date: '2014-01-01'
lastmod: 2020-10-11T15:36:48+08:00
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
publishDate: '2020-10-11T07:36:48.832066Z'
publication_types:
- 1
abstract: 'Modeling the target appearance is critical in many modern visual tracking algorithms. Many tracking-by-detection algorithms formulate the probability of target appearance as exponentially related to the confidence of a classifier output. By contrast, in this paper we directly analyze this probability using Gaussian Processes Regression (GPR), and introduce a latent variable to assist the tracking decision. Our observation model for regression is learnt in a semi-supervised fashion by using both labeled samples from previous frames and the unlabeled samples that are tracking candidates extracted from the current frame. We further divide the labeled samples into two categories: auxiliary samples collected from the very early frames and target samples from most recent frames. The auxiliary samples are dynamically re-weighted by the regression, and the final tracking result is determined by fusing decisions from two individual trackers, one derived from the auxiliary samples and the other from the target samples. All these ingredients together enable our tracker, denoted as TGPR, to alleviate the drifting issue from various aspects. The effectiveness of TGPR is clearly demonstrated by its excellent performances on three recently proposed public benchmarks, involving 161 sequences in total, in comparison with state-of-the-arts.'
publication: '*European Conference on Computer Vision (**ECCV**)*'
url_pdf: https://link.springer.com/content/pdf/10.1007/978-3-319-10578-9_13.pdf
year: ~2014
---
