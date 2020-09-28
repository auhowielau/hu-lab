---
title: 行为识别
authors: []
summary: "    "
tags:
- 
date: "2020-08-25T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""
weight: 20

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
## 简介
<html>
  <div class="row align-items-flex-start">
    <div class="col-12 col-md-4">
      <img src="featured.gif" width=100%>
    </div>
    <div class="col-12 col-md-8 order-first">
      <p class="mb-0 mt-3">
        行为识别是指根据从包含行为的视频序列中提取特征进行分类，该技术可以应用到很多领域，比如视频分析，智能监控和人机交互等等。</p>
      <p class="mb-0 mt-0">
        当前使用的模型主要分为2D CNN 和3D CNN 两大类，但是他们各有优缺点。3D CNN可以实现高的准确率，却是要以巨大的计算成本为代价。2D CNN 虽然计算成本小，但是却损失了准确率。因此，当前的主要挑战是找到一种高效且有效的算法，可以从视频中提取出有代表性的特征。</p>
      <p class="mb-0 mt-0">
        针对面临的问题，我们团队在这个领域探索了多年，提出了很多模型和方法，包括CNN，线性动态系统，树模型图匹配，图卷积网络等等。</p>
    </div>
  </div>
</html>

## 项目
<html>
  <div class="row align-items-flex-start">
    <div class="col-12 col-md-4">
      <video src="demo.mp4" width="" height="" controls="controls"></video>
    </div>
    <div class="col-12 col-md-8 order-first">
      <h4 class="mb-3 mt-4">
        <a href="/zh/subpage/p2-1" style="color: black">实验室动物行为分析</a>
      </h4>
      <ul>
        <li>实验室动物行为的观察和分析广泛用于神经科学和药理学研究。大鼠和小鼠是常见的动物模型，可用于研究遗传变异，药物治疗，光遗传学刺激和其他干预措施的行为影响。</li>
        <li>人工观察记录的成本高昂：实验人员能够同时关注的目标有限，难以长时间连续工作，在动作记录的精确性上也很难保证。</li>
        <li>自动化检测、定位与分类评估系统可以有效突破上述限制：任意数量目标同时观察，7*24小时连续记录，精确到分秒捕捉全时段动物行为的变化。</li>
        <li>适配不同的实验环境和动物类型，从小动物（鼠）到大动物（猴），从单目标到群体目标，实时捕捉并输出分析结果。</li>
      </ul>
    </div>
  </div>
</html>

## 相关论文
- <a href="/publication/chen-2020-graph" style="color: black">Yuxin Chen, Gaoqun Ma, Chunfeng Yuan, Bing Li, Hui Zhang, Fangshi Wang, Weiming Hu (2020). Graph convolutional network with structure pooling and joint-wise channel attention for action recognition. Pattern Recognition.</a>
- <a href="/publication/luo-2019-tangent" style="color: black">Guan Luo, Jiutong Wei, Weiming Hu, Stephen J Maybank (2019). Tangent Fisher vector on matrix manifolds for action recognition. IEEE Transactions on Image Processing.</a>
- <a href="/publication/yang-2019-asymmetric" style="color: black">Hao Yang, Chunfeng Yuan, Bing Li, Yang Du, Junliang Xing, Weiming Hu, Stephen J Maybank (2019). Asymmetric 3d convolutional neural networks for action recognition. Pattern recognition.</a>
- <a href="/publication/hu-2018-context" style="color: black">Weiming Hu, Baoxin Wu, Pei Wang, Chunfeng Yuan, Yangxi Li, Stephen Maybank (2018). Context-dependent random walk graph kernels and tree pattern graph matching kernels with applications to action recognition. IEEE Transactions on Image Processing.</a>
- <a href="/publication/du-2018-interaction" style="color: black">Yang Du, Chunfeng Yuan, Bing Li, Lili Zhao, Yangxi Li, Weiming Hu (2018). Interaction-aware spatio-temporal pyramid attention networks for action classification. European Conference on Computer Vision (ECCV).</a>
- <a href="/publication/yuan-2016-fusing" style="color: black">Chunfeng Yuan, Baoxin Wu, Xi Li, Weiming Hu, Stephen Maybank, Fangshi Wang (2016). Fusing R Features and Local Features with Context-Aware Kernels for Action ecognition. International Journal of Computer Vision.</a>
