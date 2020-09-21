---
title: Video Caption
authors: []
summary: Generating natural language descriptions automatically according to the visual information of given videos.
tags:
- 
date: "2020-08-25T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: 
  preview_only: True

# links:
# - icon: 
#   icon_pack: 
#   name: 
#   url: 
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: 
---
## Introduction
Video captioning aims to generate natural language descriptions automatically according to the visual information of given videos by understanding the action and event in the video. There are many wonderful visions of video captioning such as blind assistance and autopilot assistance. Video captioning needs to consider both spatial appearance and temporal dynamics of video contents, which is a promising and challenging task. The key problems in this task are twofold: how to extract discriminative features to represent the contents of videos, and how to leverage the existing visual features to match the corresponding captioning corpus. The ultimate aim is to cross the gap between vision and language.  
Previous works, such as S2VT, SA-LSTM, h-RNN, always leverage appearance features of keyframes and motion features of segments to represent video contents. These features extract global information and hard to capture the detailed temporal dynamics of objects in the video. In the topic of video captioning using objects information, we show that the object relational graph can assist the system to enrich partial information during the process of relational reasoning. Furthermore, for such a complex system, the support of external knowledge is very important. Our approach transfers linguistic knowledge to the model by introducing an external language model. With the help of these methods above, we achieve outstanding performance on MSVD, MSR-VTT and VATEX benchmarks.  
## Competitions
- VATEX Captioning Challenge 2019 Chinese and English tracks winner
## Demo
<video src="./demo1.mp4" width="360px" height="270px" controls="controls"></video>

English captions:  
People are crossing the street and cars are turning at a busy intersection in a business district.  
Pedestrians attempt to cross a street at a busy intersection where construction is also taking place.  
<video src="./demo2.mp4" width="360px" height="270px" controls="controls"></video>

English Captions:  
A person in a bear costumer stands in a bounce house and falls down as people talk in the background.  
A person wearing a bear costume is inside an inflatable play area as they lose their balance and fall over.  
## Publications
- Object Relational Graph with Teacher-Recommended Learning for Video Captioning [CVPR2020]  
Ziqi Zhang, Yaya Shi, Chunfeng Yuan, Bing Li, Peijin Wang, Weiming Hu, Zhengjun Zha.  
<img src="org.png" width=80%>
We propose an object relational graph (ORG) based encoder, which captures more detailed interaction features to enrich visual representation. Meanwhile, we design a teacher-recommended learning (TRL) method to make full use of the successful external language model (ELM) to integrate the abundant linguistic knowledge into the caption model.
- Multimodal Semantic Attention Network for Video Captioning [ICME2019]  
Liang Sun, Bing Li, Chunfeng Yuan, Zhengjun Zha, Weiming Hu.
- Dual sticky hierarchical Dirichlet process hidden Markov model and its application to natural language description of motions [TPAMI2018]  
Weiming Hu, Guodong Tian, Yongxin Kang, Chunfeng Yuan, and Stephen Maybank.
