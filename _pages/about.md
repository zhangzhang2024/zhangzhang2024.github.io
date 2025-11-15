---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  
  /* 链接文本（新增） */
  a {
    color: #8B0000; /* 链接默认颜色 */
    text-decoration: none; /* 可选：去掉除下划线 */
  }

  /* 全局字体设置 */
  body {
    font-family: "Arial";
  }
  
  /* 鼠标悬停时的链接颜色（可选） */
  a:hover {
    color: #CD5C5C; /* 稍浅的红色，增强交互感 */
  }
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 👋 _About Me_ <!-- ![visitors](https://visitor-badge.laobi.icu/badge?page_id=zhangzhang2024.github.io) -->

🎓 Hi, there.  I am a Ph.D student at School of Mechanical Engineering, Beijing Institute of Technology, advised by **<a href="https://scholar.google.com/citations?user=aUnzdwIAAAAJ&hl=zh-CN&oi=ao" style="text-decoration: none;">Prof. Chao Sun</a>**. 

<!-- 🤗 I have been fortunate to collaborate with **<a href="https://x-humanoid.com/" style="text-decoration: none;">Beijing Innovation Center of Humanoid Robotics</a>**. -->

🔥 My previous research focused on Roadside / Vehicle-side / Collaborative / Embodied 3D Perception, aiming to enhance agents' spatial understanding of surrounding environment. 

✨ My currently research interests are in the <span style="color: #000000;">**Spatial Intelligence**</span> and <span style="color: #000000;">**Autonomous Driving**</span>. 

🤗 More specifically, my research interests include:

- End-to-End Autonomous Driving with Vision-Language-Action-World Models

- Spatial Reasoning with Vision-Language Models in Autonomous Driving

📫 If you are interested in academic collaboration, feel free to reach me via **<a href="mailto:zhangzhang00@bit.edu.cn" style="text-decoration: none;">zhangzhang00@bit.edu.cn</a>** — I'd love to connect 🤗!

<!-- # 📖 Educations
- *2022 - Present*, PhD student, School of Machanical Engineering, Beijing Institute of Technology. **<a href="zhangzhang00@bit.edu.cn" style="text-decoration: none;">zhangzhang00@bit.edu.cn</a>**
- *2018 - 2022*, Undergrad student, School of Machanical Engineering, Beijing Institute of Technology. -->

<br>

# 🔥 _Publications_

<div class='paper-box' style="display: flex; align-items: flex-start; gap: 10px; /* 控制图文间距，可按需调整 */">
  <div class='paper-box-image' style="margin: 0; padding: 0;">
    <div><img src='images/heatv2x.png' alt="sym" width="300" height="200" style="display: block; margin: 0;"></div>
  </div>
  <div class='paper-box-text' markdown="1" style="font-size: 14px; margin: 0; padding: 0;">
    **<a href="https://arxiv.org/pdf/2511.10211" style="text-decoration: none;">HeatV2X: Scalable Heterogeneous Collaborative Perception via Efficient Alignment and Interaction</a>**

    _<span style="color: #777777;">Yueran Zhao</span>, <span style="color: #000000;">Zhang Zhang</span>, <span style="color: #777777;">Chao Sun</span>, <span style="color: #777777;">et al</span>._ 

    _arXiv, 2025_

    - _We propose Heterogeneous Adaptation, a scalable collaborative framework via efficient alignment and interaction._
  </div>
</div>

<!-- <div class='paper-box'><div class='paper-box-image' style="display: inline-block; vertical-align: top; margin: 0; padding: 0;">
  <div><img src='images/roadmamba.png' alt="sym" width="500" height="400"></div></div>
<div class='paper-box-text' markdown="1" style="font-size: 14px;">
  
**<a href="https://arxiv.org/pdf/2508.01210" style="text-decoration: none;">RoadMamba: A Dual-Branch Visual State Space Model for Road Surface Classification</a>**

_<span style="color: #777777;">Tianze Wang</span>, <span style="color: #000000;">Zhang Zhang</span>, <span style="color: #777777;">Chao Yue</span>, <span style="color: #777777;">et al</span>._ 

_arXiv, 2025_

- _We explore for the first time the potential of visual Mamba architectures for road surface classification task and propose a framework that effectively combines local-global perception._
</div>
</div>  -->

<!--
<div class='paper-box'><div class='paper-box-image' style="display: inline-block; vertical-align: top; margin: 0; padding: 0;">
  <div><img src='images/robooccworld.png' alt="sym" width="400" height="300"></div></div>
<div class='paper-box-text' markdown="1" style="font-size: 14px;">
**<a href="https://arxiv.org/pdf/2505.05512v1.pdf" style="text-decoration: none;">Occupancy World Model for Robots</a>**

_<span style="color: #000000;">**Zhang Zhang\***</span>, Qiang Zhang\*, Wei Cui\*, Shuai Shi, Yijie Guo, Gang Han, Wen Zhao, Jingkai Sun, Jiahang Cao, Jiaxu Wang, Hao Cheng, Xiaozhu Ju, Zhengping Che, Renjing Xu, Jian Tang†_ 

_arXiv, 2025_

- _We restructure the OccWorld-ScanNet benchmark to evaluate the forecasting of scene evolutions._
- _We propose a occupancy world model for robots' decision and exploration._
</div>
</div> 
-->

<div class='paper-box'><div class='paper-box-image' style="display: inline-block; vertical-align: top; margin: 0; padding: 0;">
  <div><img src='images/humanoidocc.png' alt="sym" width="500" height="400"></div></div>
<div class='paper-box-text' markdown="1" style="font-size: 14px;">
  
**<a href="https://arxiv.org/pdf/2507.20217" style="text-decoration: none;">Humanoid Occupancy: Enabling A Generalized Multimodal Occupancy Perception System on Humanoid Robots</a>**
  
_X-Humanoid Team_

_**<a href="https://autonomousrobots.nl/workshops/2025-iros" style="text-decoration: none;">IROS Workshop on PM2CE, 2025</a>** \| **<a href="https://humanoid-occupancy.github.io/" style="text-decoration: none;">Project</a>**_ 

- _We release a generalized multimodal occupancy perception system for humanoid robots._
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="display: inline-block; vertical-align: top; margin: 0; padding: 0;">
  <div><img src='images/pillarmamba.png' alt="sym" width="500" height="400"></div></div>
<div class='paper-box-text' markdown="1" style="font-size: 14px;">
  
**<a href="https://arxiv.org/pdf/2505.05397.pdf" style="text-decoration: none;">PillarMamba: Learning Local-Global Context for Roadside Point Cloud via Hybrid State Space Model</a>**
  
_<span style="color: #000000;">Zhang Zhang</span>, <span style="color: #777777;">Chao Sun</span>, <span style="color: #777777;">Chao Yue</span>, <span style="color: #777777;">et al</span>._

_arXiv, 2025_ _\|_  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="vertical-align: middle; margin-right: 4px;"> <path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path> </svg>_**<a href="https://github.com/zhangzhang2024/PillarMamba" style="text-decoration: none;">Code</a>**_

- _We propose a local-global method to boost the power of the standard state space model and address the local connection disrupted and historical relationship forgotten._
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="display: inline-block; vertical-align: top; margin: 0; padding: 0;">
  <div><img src='images/roboocc.png' alt="sym" width="500" height="400"></div></div>
<div class='paper-box-text' markdown="1" style="font-size: 14px;">
  
**<a href="https://arxiv.org/pdf/2504.14604.pdf" style="text-decoration: none;">RoboOcc: Enhancing the Geometric and Semantic Scene Understanding for Robots</a>**
  
_<span style="color: #000000;">Zhang Zhang</span>, <span style="color: #777777;">Qiang Zhang</span>, <span style="color: #777777;">Wei Cui</span>, <span style="color: #777777;">et al</span>._

_arXiv, 2025_

- _We present a method to enhance geometric and semantic scene understanding in 3D occupancy prediction for robots._
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="display: inline-block; vertical-align: top; margin: 0; padding: 0;">
  <div><img src='images/heightformer_fig2.png' alt="sym" width="500" height="400"></div></div>
<div class='paper-box-text' markdown="1" style="font-size: 14px;">
  
**<a href="https://arxiv.org/pdf/2503.10777.pdf" style="text-decoration: none;">HeightFormer: Learning Height Prediction in Voxel Features for Roadside Vision Centric 3D Object Detection via Transformer</a>**
  
_<span style="color: #000000;">Zhang Zhang</span>, <span style="color: #777777;">Chao Sun</span>, <span style="color: #777777;">Chao Yue</span>, <span style="color: #777777;">et al</span>._

_arXiv, 2025_ _\|_  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="vertical-align: middle; margin-right: 4px;"> <path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path> </svg>_**<a href="https://github.com/zhangzhang2024/HeightFormer" style="text-decoration: none;">Code</a>**_

- _We propose an efficient framework learning height prediction in voxel features via transformer for roadside visual perception._
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="display: inline-block; vertical-align: top; margin: 0; padding: 0;">
  <div><img src='images/h-pano.png' alt="sym" width="500" height="400"></div></div>
<div class='paper-box-text' markdown="1" style="font-size: 14px;">
  
**<a href="https://arxiv.org/pdf/2503.09010.pdf" style="text-decoration: none;">HumanoidPano: Hybrid Spherical Panoramic-LiDAR Cross-Modal Perception for Humanoid Robots</a>**
  
_<span style="color: #777777;">Qiang Zhang</span>, <span style="color: #000000;">Zhang Zhang</span>, <span style="color: #777777;">Wei Cui</span>, <span style="color: #777777;">et al</span>._

_arXiv, 2025_

- _We propose a novel hybrid cross-modal perception framework that synergistically integrates panoramic vision and LiDAR sensing for humanoid robots._
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="display: inline-block; vertical-align: top; margin: 0; padding: 0;">
  <div><img src='images/pillarid.png' alt="sym" width="500" height="400"></div></div>
<div class='paper-box-text' markdown="1" style="font-size: 14px;">
  
**PillarID: Rethinking Backbone Network Designs for Pillar-based 3D Object Detection in Infrastructure Point Cloud**
  
_<span style="color: #000000;">Zhang Zhang</span>, <span style="color: #777777;">Chao Sun</span>, <span style="color: #777777;">Bo Wang</span>, <span style="color: #777777;">et al</span>._

_**<a href="https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6979" style="text-decoration: none;">IEEE Transactions on Intelligent Transportation Systems (T-ITS), 2025</a>**_ _\|_  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="vertical-align: middle; margin-right: 4px;"> <path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path> </svg>_**<a href="https://github.com/zhangzhang2024/PillarID" style="text-decoration: none;">Code</a>**_ 

- _We propose a dense backbone-based network for utilizing the rich contextual information of the roadside point cloud effectively._
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="display: inline-block; vertical-align: top; margin: 0; padding: 0;">
  <div><img src='images/height3d.png' alt="sym" width="500" height="400"></div></div>
<div class='paper-box-text' markdown="1" style="font-size: 14px;">
  
**<a href="https://ieeexplore.ieee.org/document/11005676" style="text-decoration: none;">Height3D: A Roadside Visual Framework Based on Height Prediction in Real 3D Space</a>** 
  
_<span style="color: #000000;">Zhang Zhang</span>, <span style="color: #777777;">Chao Sun</span>, <span style="color: #777777;">Bo Wang</span>, <span style="color: #777777;">et al</span>._

_**<a href="https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6979" style="text-decoration: none;">IEEE Transactions on Intelligent Transportation Systems (T-ITS), 2025</a>**_ _\|_  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="vertical-align: middle; margin-right: 4px;"> <path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path> </svg>_**<a href="https://github.com/zhangzhang2024/Height3D" style="text-decoration: none;">Code</a>**_ 

- _We propose a novel roadside visual perception framework based on the heightnet in real 3D space instead of image 2D space._
</div>
</div>

<!--
[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
-->
