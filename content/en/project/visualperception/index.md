---
title: Visual Perception
authors: []
summary: Object detection, tracking and segmentation.
tags:
- 
date: "2020-08-25T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""
weight: 10

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
<!-- <img src="featured.gif" width=80%> -->
## Introduction
Object detection, segmentation, tracking are all fundamental tasks in computer vision. Object detection aims to detect instances of semantic objects of a certain class (such as humans, buildings, or cars) in digital images, and visual object tracking (VOT) focuses on estimating the location and scale of a target (or multiple targets) in a video sequence. Beyond representing object locations as rectangle bounding boxes, pixel-level masks can provide more specific location information, namely instance segmentation and video object segmentation (VOS). The above-mentioned technologies are widely used in many fields such as robot navigation, intelligent video surveillance, industrial inspection, and video editing. VSLab has been strenuously working on these fields for many years and has achieved rich results in both theoretical research and practical applications.  
Object tracking and segmentation are challenging due to the various factors in realistic seniors, e.g., illumination change, background clutter, distractors. Accuracy, robustness, and realtime are three main foci when designing a strong tracking and segmentation model. To the end, we impose attention mechanism (RASNet) to improve tracking accuracy. Anchor-free regression (Ocean) is introduced to achieve better tracking robustness. Related algorithms have achieved excellent results in many international visual object tracking competitions.  
## Competitions
- Visual Object Tracking competition 2018 (VOT2018) realtime track winner (SiamRPN).
- Visual Object Tracking competition 2019 (VOT2019) RGBT track runner-up (SiamDW-T).
- Visual Object Tracking competition 2020 (VOT2020) realtime and base track runner-ups (OcenaPlus).
- Visual Object Tracking competition 2020 (VOT2020) RGBT track winner (SiamDW-T re-submitted by the committee).
## Talks
- Qiang Wang: [SiamMask](https://www.bilibili.com/video/BV1Kt411u7CT?from=search&seid=14223038225505545546)
- Zhipeng Zhang: [Ocean](https://www.bilibili.com/video/BV1354y1e7wU?from=search&seid=10926703456041213142)
## Publications
- SiamMask: Fast Online Object Tracking and Segmentation: A Unifying Approach [CVPR2019]  
Qiang Wang, Li Zhang, Luca Bertinetto, Weiming Hu, Philip H.S. Torr  
<img src="siammask.png" width=80%>
In this paper we illustrate how to perform both visual object tracking and semi-supervised video object segmentation, in real-time, with a single simple approach. Our method, dubbed SiamMask, improves the offline training procedure of popular fully-convolutional Siamese approaches for object tracking by augmenting their loss with a binary segmentation task. Once trained, SiamMask solely relies on a single bounding box initialization and operates online, producing class-agnostic object segmentation masks and rotated bounding boxes at 55 frames per second. Despite its simplicity, versatility and fast speed, our strategy allows us to establish a new state of the art among real-time trackers on VOT-2018, while at the same time demonstrating competitive performance and the best speed for the semisupervised video object segmentation task on DAVIS-2016 and DAVIS-2017.  
- Ocean: Object-aware Anchor-free Tracking [ECCV2020]  
Zhipeng Zhang, Houwen Peng, Jianlong Fu, Bing Li, Weiming Hu  
<img src="ocean.png" width=80%>
Anchor-based Siamese trackers have achieved remarkable advancements in accuracy, yet the further improvement is restricted by the lagged tracking robustness. We find the underlying reason is that the regression network in anchor-based methods is only trained on the positive anchor boxes. This mechanism makes it difficult to refine the anchors whose overlap with the target objects are small. In this paper, we propose a novel object-aware anchor-free network to address this issue. First, instead of refining the reference anchor boxes, we directly predict the position and scale of target objects in an anchor-free fashion. Since each pixel in groundtruth boxes is well trained, the tracker is capable of rectifying inexact predictions of target objects during inference. Second, we introduce a feature alignment module to learn an object-aware feature from predicted bounding boxes. The object-aware feature can further contribute to the classification of target objects and background. Moreover, we present a novel tracking framework based on the anchor free model. The experiments show that our anchor-free tracker achieves state-of-the-art performance on five benchmarks.  
- TBF: Tracking-by-Fusion via Gaussian Process Regression Extended to Transfer Learning  
Jin Gao, Qiang Wang, Junliang Xing, Weiming Hu, Stephen Maybank
<img src="tbf.png" width=80%>
This paper presents a new Gaussian Processes (GPs)-based particle filter tracking framework. The framework non-trivially extends Gaussian process regression (GPR) to transfer learning, and, following the tracking-by-fusion strategy, integrates closely two tracking components, namely a GPs component and a CFs one. First, the GPs component analyzes and models the probability distribution of the object appearance by exploiting GPs. It categorizes the labeled samples into auxiliary and target ones, and explores unlabeled samples in transfer learning. The GPs component thus captures rich appearance information over object samples across time. On the other hand, to sample an initial particle set in regions of high likelihood through the direct simulation method in particle filtering, the powerful yet efficient correlation filters (CFs) are integrated, leading to the CFs component. In fact, the CFs component not only boosts the sampling quality, but also benefits from the GPs component, which provides re-weighted knowledge as latent variables for determining the impact of each correlation filter template from the auxiliary samples. In this way, the transfer learning based fusion enables effective interactions between the two components.  
- RASNet：Learning Attentions: Residual Attentional Siamese Network for High Performance Online Visual Tracking [CVPR2018]  
Qiang Wang, Zhu Teng , Junliang Xing, Jin Gao, Weiming Hu, Stephen Maybank
<img src="rasnet.png" width=80%>
Offline training for object tracking has recently shown great potentials in balancing tracking accuracy and speed. However, it is still difficult to adapt an offline trained model to a target tracked online. This work presents a Residual Attentional Siamese Network (RASNet) for high performance object tracking. The RASNet model reformulates the correlation filter within a Siamese tracking framework, and introduces different kinds of the attention mechanisms to adapt the model without updating the model online. In particular, by exploiting the offline trained general attention, the target adapted residual attention, and the channel favored feature attention, the RASNet not only mitigates the over-fitting problem in deep network training, but also enhances its discriminative capacity and adaptability due to the separation of representation learning and discriminator learning. The proposed deep architecture is trained from end to end and takes full advantage of the rich spatial temporal information to achieve robust visual tracking.  
- RDSNet: A New Deep Architecture for Reciprocal Object Detection and Instance Segmentation [AAAI2020]  
Shaoru Wang, Yongchao Gong, Junliang Xing, Lichao Huang, Chang Huang, Weiming Hu
<img src="rdsnet.png" width=80%>
Object detection and instance segmentation are two fundamental computer vision tasks. They are closely correlated but their relations have not yet been fully explored in most previous work. This paper presents RDSNet, a novel deep architecture for reciprocal object detection and instance segmentation. To reciprocate these two tasks, we design a two-stream structure to learn features on both the object level (i.e., bounding boxes) and the pixel level (i.e., instance masks) jointly. Within this structure, information from the two streams is fused alternately, namely information on the object level introduces the awareness of instance and translation variance to the pixel level, and information on the pixel level refines the localization accuracy of objects on the object level in return. Specifically, a correlation module and a cropping module are proposed to yield instance masks, as well as a mask based boundary refinement module for more accurate bounding boxes. Extensive experimental analyses and comparisons on the COCO dataset demonstrate the effectiveness and efficiency of RDSNet.  
- Rank1：Rank-1 Tensor Approximation for High-Order Association in Multi-target Tracking  
Xinchu Shi, Haibin Ling, Yu Pang, Weiming Hu, Peng Chu, Junliang Xing
<img src="rank1.png" width=80%>
High-order motion information is important in multi-target tracking (MTT) especially when dealing with large inter-target ambiguities. Such high-order information can be naturallymodeled as amulti dimensional assignment (MDA) problem, whose global solution is however intractable in general. In this paper, we propose a novel framework to the problem by reshaping MTT as a rank-1 tensor approximation problem (R1TA). We first show that MDA and R1TA share the same objective function and similar constraints. This discovery opens a door to use high-order tensor analysis for MTT and suggests the exploration of R1TA. In particular, we develop a tensor power iteration algorithm to effectively capture high-order motion information as well as appearance variation. The proposed algorithm is evaluated on a diverse set of datasets including aerial video sequences containing ariel borne dense highway scenes, top-view pedestrian trajectories, multiple similar objects, normal view pedestrians and vehicles. The effectiveness of the proposed algorithm is clearly demonstrated in these experiments.  
