---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Listwise learning to rank from crowds
subtitle: ''
summary: ''
authors:
- Ou Wu
- Qiang You
- Fen Xia
- Lei Ma
- Weiming Hu
tags: []
categories: []
date: '2016-01-01'
lastmod: 2020-09-14T02:08:15+08:00
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
publishDate: '2020-09-13T18:08:15.562575Z'
publication_types:
- 2
abstract: 'Learning to rank has received great attention in recent years as it plays a crucial role in many applications such as information retrieval and data mining. The existing concept of learning to rank assumes that each training instance is associated with a reliable label. However, in practice, this assumption does not necessarily hold true as it may be infeasible or remarkably expensive to obtain reliable labels for many learning to rank applications. Therefore, a feasible approach is to collect labels from crowds and then learn a ranking function from crowdsourcing labels. This study explores the listwise learning to rank with crowdsourcing labels obtained from multiple annotators, who may be unreliable. A new probabilistic ranking model is first proposed by combining two existing models. Subsequently, a ranking function is trained by proposing a maximum likelihood learning approach, which estimates ground-truth labels and annotator expertise, and trains the ranking function iteratively. In practical crowdsourcing machine learning, valuable side information (e.g., professional grades) about involved annotators is normally attainable. Therefore, this study also investigates learning to rank from crowd labels when side information on the expertise of involved annotators is available. In particular, three basic types of side information are investigated, and corresponding learning algorithms are consequently introduced. Further, the top-k learning to rank from crowdsourcing labels are explored to deal with long training ranking lists. The proposed algorithms are tested on both synthetic and real-world data. Results reveal that the maximum likelihood estimation approach significantly outperforms the average approach and existing crowdsourcing regression methods. The performances of the proposed algorithms are comparable to those of the learning model in consideration reliable labels. The results of the investigation further indicate that side information is helpful in inferring both ranking functions and expertise degrees of annotators.'
publication: '*ACM Transactions on Knowledge Discovery from Data (**TKDD**)*'
url_pdf: http://ir.ia.ac.cn/bitstream/173211/12019/1/tkdd.pdf
---
