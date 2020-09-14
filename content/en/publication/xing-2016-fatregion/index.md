---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'FatRegion: A Fast Adaptive Tree-Structured Region Extraction Approach'
subtitle: ''
summary: ''
authors:
- Junliang Xing
- Weiming Hu
- Haizhou Ai
- Shuicheng Yan
tags: []
categories: []
date: '2016-01-01'
lastmod: 2020-09-14T02:08:13+08:00
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
publishDate: '2020-09-13T18:08:13.524871Z'
publication_types:
- 2
abstract: 'Coherent image regions can be used as good features for many computer vision tasks, such as object tracking, segmentation, and recognition. Most of previous region extraction methods, however, are not suitable for online applications because of their either heavy computations or unsatisfactory results. We propose a seed-based region growing and merging approach to generate simultaneously coherent and discriminative image regions. We present a quadtree-based seed initialization algorithm to adaptively place seeds into different image areas and then grow them into regions by a color- and edge-guided growing procedure. To merge these regions in different levels, we propose to use the generalized boundary strength to measure the quality of region merging result. In addition, we present a region merging algorithm of linear time complexity to perform efficient and effective region merging. Overall, our new approach simultaneously holds these advantages: 1) it is extremely fast with linear complexity in both time and space, which takes less than 50 ms to process an HVGA image; 2) it can give a direct control of the region number and well adapt to image regions with various sizes and shapes; and 3) it provides a tree-structured representation of the regions and thus can model the image from multiple scales. We evaluate the proposed approach on the standard benchmarks with extensive comparisons with the state-of-the-art methods. The experimental results demonstrate its good comprehensive performances. Example applications using the extracted regions as features for online object tracking and multiclass object segmentation also exhibit its potential for many computer vision tasks.'
publication: '*IEEE Transactions on Circuits and Systems for Video Technology*'
url_pdf: http://ir.ia.ac.cn/bitstream/173211/13723/1/TCSVT17FatRegion.pdf
---
