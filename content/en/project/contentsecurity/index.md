---
title: Multimedia Content Security
authors: []
summary: Detect and filter harmful multimedia content.
tags:
- 
date: "2020-08-25T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""
weight: 15

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

## Face Forgery Detection
With advances in rendering techniques and deep learning, the manipulation and generation of realistic digital image have been improved much. Computer-generated (CG) images are becoming indistinguishable from photographic (PG) images. In particular, Deepfakes, the face swapping technology mainly based on Generative Adversarial Networks, tries to fit the distribution of real face images and then replaces the faces in a source image with the identity of a specified target while maintaining the attributes such as head poses and facial expressions, which are true to life. It means that fake generated images may be maliciously used to defraud the public. So it is necessary to develop algorithms to identify whether an image is synthetic. CG image forensic task devote to distinguish CG images from PG images. And Face Forgery Detection is specifically aimed at human face scenes.  
<img src="demo.png" width=80%>
Existing CG image forensic works still have difficulty in distinguishing high-quality CG images from PG images. The main reasons are that existing benchmarks are out of fashion and methods ignore the underlying texture differences, which are important in this task. To solve this problem, we first construct a large-scale dataset with high diversity and low bias between CG and PG images. Then, a texture-aware CG and PG images classification is also proposed which considers the correlations between filters in the output feature map of a backbone. A mass of experiments demonstrate the effectiveness and superiority of our method.  
Similarly, there are three problems in face forgery detection to solve: 1) the forensic methods cannot always maintain a high accuracy rate for unknown synthesis methods, which means their generalization needs to be improved; 2) their detection performance is easily influenced by conventional image processing methods and lacks enough robustness in practical applications; 3) there is no sufficient understanding of the essence of artificial clues used by the forensic methods, so it is difficult to design heuristic strategies. We believe that the commonality such as module structure and post-processing methods should be summarized from the synthesis methods, so that the forensic methods can be designed specifically to make it maintain high accuracy for more types of fake images. Rather than simply treating face forgery detection as an image binary classification problem, we are exploring the relationship between more use of high-level semantics of a face itself and the detection performance, to have a better understanding about the nature of Deepfakes.  

## Publications
- Weiming Hu, Jun Gao, Bing Li, Ou Wu. Junping Du, Stephen J. Maybank. Anomaly Detection Using Local Kernel Density Estimation and Context-Based Regression. IEEE Trans. on Knowledge and Data Engineering (IEEE TKDE), vol. 32, no. 2, pp. 218-233, 2020.
- Yufan Liu, Minglang Qiao, Mai Xu, Bing Li, Weiming Hu, “Learning to predict salient faces: a novel visual-audio saliency model”, Proceedings of the IEEE Conference on European Conference on Computer Vision（ECCV）. 2020.
- Junliang Xing, Zhiheng Niu, Junshi Huang, Weiming Hu( ), Xi Zhou, and Shuicheng Yan, “Towards robust and accurate multi-view and partially-occluded face alignment,” IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), vol. 40, no. 4, pp. 987-1001, 2018.
- Weiming Hu, Yabo Fan, Junliang Xing, Liang Sun, Zhaoquan Cai, and Stephen Maybank, “Deep constrained siamese hash coding network and load-balanced locality-sensitive hashing for near duplicate image detection,” IEEE Transactions on Image Processing (TIP), vol. 27, no. 9, pp. 4452-4464, September 2018.
- Hu Weiming, Ding Xinmiao, Li Bing, Wang Jianchao, Gao Yan, Wang Fangshi, Maybank Stephen，Multi-Perspective Cost-Sensitive Context-Aware Multi-Instance Sparse Coding and Its Application to Sensitive Video Recognition, IEEE Trans. On Multimedia (IEEE TMM), 18(1): 76~89, 2016.
- Wu Ou, Zuo Haiqiang, Hu, Weiming, Li Bing, Multimodal Web Aesthetics Assessment Based on Structural SVM and Multitask Fusion Learning. IEEE Trans. On Multimedia (IEEE TMM), 18(6): 1062-1076, 2016.
