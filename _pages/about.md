---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

<!--
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
-->


<!--# 🔥 News-->
# 🔥 _Paper News_
- _2025.04:  RoboOccWorld: Occupancy World Model for Robots_
- _2025.04:  RoboOcc: Enhancing the Geometric and Semantic Scene Understanding for Robots_
- _2025.04:  RoadFormer: Road Surface Classification Using Local-Global Feature Fusion_
- _2025.03:  Q-MambaIR: Accurate Quantized Mamba for Efficient Image Restoration_
- _2025.03:  HumanoidPano: Hybrid Spherical Panoramic-LiDAR Cross-Modal Perception for Humanoid Robots_
- _2025.01:  PillarMamba: Learning Dense Context Information for Roadside Point Cloud 3D Object Detection via State Space Model_
- _2024.12:  HeightFormer: Learning Height Prediction in Voxel Features for Roadside Vision Centric 3D Object Detection via Transformer_
- _2024.11:  PillarID: Rethinking Backbone Network Designs for Pillar-based 3D Object Detection in Infrastructure Point Cloud_
- _2024.10:  Height3D: A Roadside Visual Framework Based on Height Prediction in Real 3D Space_


# 📝 _Publications_
<div class='paper-box'><div class='paper-box-image' style="display: inline-block; vertical-align: top; margin: 0; padding: 0;">
  <div><div class="badge">arxiv 2025</div><img src='images/robooccworld.png' alt="sym" width="400" height="300"></div></div>
<div class='paper-box-text' markdown="1" style="font-size: 16px;">
**[Occupancy World Model for Robots]**
  
<span style="color: #000000;">**Zhang Zhang\***</span>, Qiang Zhang\*, Wei Cui\*, Shuai Shi, Yijie Guo, Gang Han, Wen Zhao, Hengle Ren, Renjing Xu, Jian Tang

- _We restructure the OccWorld-ScanNet benchmark to evaluate the forecasting of scene evolutions._
- _We propose a occupancy world model based on the spatial understanding and temporal modeling of the 3D scene for robots' decision and exploration._
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="display: inline-block; vertical-align: top; margin: 0; padding: 0;">
  <div><div class="badge">arxiv 2025</div><img src='images/roboocc.png' alt="sym" width="400" height="300"></div></div>
<div class='paper-box-text' markdown="1" style="font-size: 16px;">
**[RoboOcc: Enhancing the Geometric and Semantic Scene Understanding for Robots](https://arxiv.org/pdf/2504.14604.pdf)**
  
**Zhang Zhang\***, Qiang Zhang\*, Wei Cui\*, Shuai Shi, Yijie Guo, Gang Han, Wen Zhao, Hengle Ren, Renjing Xu, Jian Tang

- _We introduce a method for enhancing geometric and semantic scene understanding in 3D occupancy prediction task for robots._
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="display: inline-block; vertical-align: top; margin: 0; padding: 0;">
  <div><div class="badge">arxiv 2025</div><img src='images/roadformer.png' alt="sym" width="400" height="300"></div></div>
<div class='paper-box-text' markdown="1" style="font-size: 16px;">
**[RoadFormer: Road Surface Classification Using Local-Global Feature Fusion]**
  
Tianze Wang\*, **Zhang Zhang\***, Chao Sun, Todo

- _We propose a feature stacking method that comprehensively considers both local and global information for road surface classification._
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="display: inline-block; vertical-align: top; margin: 0; padding: 0;">
  <div><div class="badge">arxiv 2025</div><img src='images/qmambair.jpg' alt="sym" width="400" height="300"></div></div>
<div class='paper-box-text' markdown="1" style="font-size: 16px;">
**[Q-MambaIR: Accurate Quantized Mamba for Efficient Image Restoration](https://arxiv.org/pdf/2503.21970.pdf)**
  
Yujie Chen, Haotong Qin, **Zhang Zhang**, Michelo Magno, Luca Benini, Yawei Li

- _We propose an accurate, efficient, and flexible quantized mamaba for image restoration task._
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="display: inline-block; vertical-align: top; margin: 0; padding: 0;">
  <div><div class="badge">arxiv 2025</div><img src='images/h-pano.png' alt="sym" width="400" height="300"></div></div>
<div class='paper-box-text' markdown="1" style="font-size: 16px;">
**[HumanoidPano: Hybrid Spherical Panoramic-LiDAR Cross-Modal Perception for Humanoid Robots](https://arxiv.org/pdf/2503.09010.pdf)**
  
Qiang Zhang\*, **Zhang Zhang\***, Wei Cui\*, Jingkai Sun, Jiahang Cao, Yijie Guo, Gang Han, Wen Zhao, Jiaxu Wang, Chenghao Sun, Lingfeng Zhang, Hao Cheng, Yujie Chen, Lin Wang, Jian Tang, Renjing Xu

- _We propose a novel hybrid cross-modal perception framework that synergistically integrates panoramic vision and LiDAR sensing for humanoid robots._
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="display: inline-block; vertical-align: top; margin: 0; padding: 0;">
  <div><div class="badge">todo</div><img src='images/pillarmamba.png' alt="sym" width="400" height="300"></div></div>
<div class='paper-box-text' markdown="1" style="font-size: 16px;">
**[PillarMamba: Learning Dense Context Information for Roadside Point Cloud 3D Object Detection via State Space Model]**
  
**Zhang Zhang**, Chao Sun, Todo
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="display: inline-block; vertical-align: top; margin: 0; padding: 0;">
  <div><div class="badge">arxiv 2025</div><img src='images/heightformer.png' alt="sym" width="400" height="300"></div></div>
<div class='paper-box-text' markdown="1" style="font-size: 16px;">
**[HeightFormer: Learning Height Prediction in Voxel Features for Roadside Vision Centric 3D Object Detection via Transformer](https://arxiv.org/pdf/2503.10777.pdf)**
  
**Zhang Zhang**, Chao Sun, Chao Yue, Da Wen, Yujie Chen, Tianze Wang, Jianghao Leng

- _We propose an efficient framework learning height prediction in voxel features via transformers for roadside visual perception._
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="display: inline-block; vertical-align: top; margin: 0; padding: 0;">
  <div><div class="badge">under review</div><img src='images/pillarid.png' alt="sym" width="400" height="300"></div></div>
<div class='paper-box-text' markdown="1" style="font-size: 16px;">
**[PillarID: Rethinking Backbone Network Designs for Pillar-based 3D Object Detection in Infrastructure Point Cloud]**
  
**Zhang Zhang**, Chao Sun, Bo Wang, Da Wen

- _We propose a dense backbone-based network for utilizing the rich contextual information of the roadside point cloud effectively._
</div>
</div>

<div class='paper-box'><div class='paper-box-image' style="display: inline-block; vertical-align: top; margin: 0; padding: 0;">
  <div><div class="badge">T-ITS 2025</div><img src='images/height3d.png' alt="sym" width="400" height="300"></div></div>
<div class='paper-box-text' markdown="1" style="font-size: 16px;">
**[Height3D: A Roadside Visual Framework Based on Height Prediction in Real 3D Space]**
  
**Zhang Zhang**, Chao Sun, Bo Wang, Bin Guo, Da Wen, Tianyi Zhu, Qili Ning

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

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
-->
