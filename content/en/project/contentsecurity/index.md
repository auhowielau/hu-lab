---
title: Multimedia Content Security
authors: []
summary: Detect and filter harmful multimedia content.
tags:
- 
date: "2020-08-25T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""
weight: 40

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
With the swift development of communication technologies, multimedia digital content, consisting of image, video, audio, and text, is growing exponentially and is permeating each aspect of our lives. However, there is much harmful information in multimedia content, such as terrorism, narcotics, racism, violence, privacy-invasion, and illegal-deals, which may lead to severe social turmoil. Thus, it is vital for our society to clean the harmful content on the web, so as to create a beautiful and peaceful world.  
It is challenging to automatically recognize the harmful content, as this requires the computer not only to see the images/videos in depth, but also to fully understand the audio and the text. For several years, VSLab has been devoted to the research around multimedia content security, and has developed many advanced technologies, such as harmful image/video detection, anomaly detection, and face forgery detection.

## Featured Topics
<html>
  <div class="row align-items-flex-start">
    <div class="col-12 col-md-4 order-first">
      <img src="demo.png" width=100%>
    </div>
    <div class="col-12 col-md-8">
      <h4 class="mb-0 mt-4">
        <a href="/subpage/face" style="color: black">Face Forgery Detection</a>
      </h4>
        With advances in rendering techniques and deep learning, the manipulation and generation of realistic digital image have been improved much. Computer-generated (CG) images are becoming indistinguishable from photographic (PG) images. In particular, Deepfakes, the face swapping technology mainly based on Generative Adversarial Networks, tries to fit the distribution of real face images and then replaces the faces in a source image with the identity of a specified target while maintaining the attributes such as head poses and facial expressions, which are true to life. It means that fake generated images may be maliciously used to defraud the public. So it is necessary to develop algorithms to identify whether an image is synthetic. CG image forensic task devote to distinguish CG images from PG images. And Face Forgery Detection is specifically aimed at human face scenes.
    </div>
  </div>
</html>

## Publications
- Yufan Liu, Minglang Qiao, Mai Xu, Bing Li, Weiming Hu (2020). Learning to predict salient faces: a novel visual-audio saliency model. European Conference on Computer Vision (ECCV).
- Weiming Hu, Jun Gao, Bing Li, Ou Wu, Junping Du, Stephen J. Maybank (2018). Anomaly Detection Using Local Kernel Density Estimation and Context-Based Regression. IEEE Transactions on Knowledge and Data Engineering.
- <a href="/publication/hu-2018-deep" style="color: black">Weiming Hu, Yabo Fan, Junliang Xing, Liang Sun, Zhaoquan Cai, and Stephen Maybank (2018). Deep constrained siamese hash coding network and load-balanced locality-sensitive hashing for near duplicate image detection. IEEE Transactions on Image Processing.</a>
- <a href="/publication/xing-2017-towards" style="color: black">Junliang Xing, Zhiheng Niu, Junshi Huang, Weiming Hu, Xi Zhou, and Shuicheng Yan (2017). Towards robust and accurate multi-view and partially-occluded face alignment. IEEE Transactions on Pattern Analysis and Machine Intelligence.</a>
- <a href="/publication/wu-2016-multimodal" style="color: black">Ou Wu, Haiqiang Zuo, Weiming Hu, Bing Li (2016). Multimodal web aesthetics assessment based on structural SVM and multitask fusion learning. IEEE Transactions on Multimedia.
- <a href="/publication/hu-2015-multi" style="color: black">Weiming Hu, Xinmiao Ding, Bing Li, Jianchao Wang, Yan Gao, Fangshi Wang, Stephen Maybank (2015). Multi-perspective cost-sensitive context-aware multi-instance sparse coding and its application to sensitive video recognition. IEEE Transactions on Multimedia.</a>
