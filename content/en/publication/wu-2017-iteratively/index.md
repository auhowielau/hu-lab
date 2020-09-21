---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Iteratively divide-and-conquer learning for nonlinear classification and ranking
subtitle: ''
summary: ''
authors:
- Ou Wu
- Xue Mao
- Weiming Hu
tags: []
categories: []
date: '2017-01-01'
lastmod: 2020-09-14T02:08:10+08:00
featured: false
draft: false

url_pdf: files/iteratively
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
publishDate: '2020-09-13T18:08:10.418672Z'
publication_types:
- 2
abstract: 'Nonlinear classifiers (i.e., kernel support vector machines (SVMs)) are effective for nonlinear data classification. However, nonlinear classifiers are usually prohibitively expensive when dealing with large nonlinear data. Ensembles of linear classifiers have been proposed to address this inefficiency, which is called the ensemble linear classifiers for nonlinear data problem. In this article, a new iterative learning approach is introduced that involves two steps at each iteration: partitioning the data into clusters according to Gaussian mixture models with local consistency and then training basic classifiers (i.e., linear SVMs) for each cluster. The two divide-and-conquer steps are combined into a graphical model. Meanwhile, with training, each classifier is regarded as a task; clustered multitask learning is employed to capture the relatedness among different tasks and avoid overfitting in each task. In addition, two novel extensions are introduced based on the proposed approach. First, the approach is extended for quality-aware web data classification. In this problem, the types of web data vary in terms of information quality. The ignorance of the variations of information quality of web data leads to poor classification models. The proposed approach can effectively integrate quality-aware factors into web data classification. Second, the approach is extended for listwise learning to rank to construct an ensemble of linear ranking models, whereas most existing listwise ranking methods construct a solely linear ranking model. Experimental results on benchmark datasets show that our approach outperforms state-of-the-art algorithms. During prediction for nonlinear classification, it also obtains comparable classification performance to kernel SVMs, with much higher efficiency.'
publication: '*ACM Transactions on Intelligent Systems and Technology (TIST)*'
---
