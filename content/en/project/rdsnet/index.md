---
title: RDSNet
authors: ["srwang"]
summary: A New Deep Architecture for Reciprocal Object Detection and Instance Segmentation.
tags:
- Object Detection
date: "2020-08-25T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: 

# links:
# - icon: 
#   icon_pack: 
#   name: 
#   url: 
url_code: "https://github.com/wangsr126/RDSNet"
url_pdf: "https://arxiv.org/pdf/1912.05070.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: 
---

Object detection and instance segmentation are two fundamental computer vision tasks. They are closely correlated but their relations have not yet been fully explored in most previous work. This paper presents RDSNet, a novel deep architecture for reciprocal object detection and instance segmentation. To reciprocate these two tasks, we design a two-stream structure to learn features on both the object level (i.e., bounding boxes) and the pixel level (i.e., instance masks) jointly. Within this structure, information from the two streams is fused alternately, namely information on the object level introduces the awareness of instance and translation variance to the pixel level, and information on the pixel level refines the localization accuracy of objects on the object level in return. Specifically, a correlation module and a cropping module are proposed to yield instance masks, as well as a mask based boundary refinement module for more accurate bounding boxes. Extensive experimental analyses and comparisons on the COCO dataset demonstrate the effectiveness and efficiency of RDSNet. The source code is available at https://github.com/wangsr126/RDSNet.
