---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Multi-cue illumination estimation via a tree-structured group joint sparse
  representation
subtitle: ''
summary: ''
authors:
- Bing Li
- Weihua Xiong
- Weiming Hu
- Brian Funt
- Junliang Xing
tags: []
categories: []
date: '2016-01-01'
lastmod: 2020-09-14T02:08:16+08:00
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
publishDate: '2020-09-13T18:08:15.998437Z'
publication_types:
- 2
abstract: 'A multi-cue illumination estimation method based on tree-structured group joint sparse representation is proposed. Tests show that the proposed method works better than existing methods, most of which are based on using only a single cue type, for example, a binarized color histogram or simple image statistic such as the mean RGB. Most existing illumination estimation methods make their estimates using only one of three kinds of cues. They differ in which cue type they use, but the chosen cue is either based on (1) properties of the low-level RGB color distribution, (2) mid-level initial illuminant estimates provided by subordinate methods, or (3) high-level knowledge of scene content (e.g., indoor versus outdoor scene). The proposed multi-cue method combines the information provided by cues of all three of these types within the framework of a tree-structured group joint sparse representation (TGJSR). In TGJSR, the training data is grouped into a tree of subgroups. A test image under an unknown illuminant has its features reconstructed in terms of a joint sparse representation model derived from the grouped training data. The test image’s illumination is then estimated based on the weights involved in the joint sparse representation model. As a general framework, the proposed TGJSR framework can also easily be extended to incorporate any new features or cues that might be discovered in the future for illumination estimation.'
publication: '*International Journal of Computer Vision (IJCV)*'
url_pdf: http://ir.ia.ac.cn/bitstream/173211/11101/1/IJCV16ColorConstancyMC.pdf
---
