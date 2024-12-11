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

This is Bo Chen, a postdoc at University of Illinois at Urbana-Champaign (UIUC) working with Prof. Klara Nahrstedt. I obtained my Ph.D. in computer science at UIUC in 2022, advised by Prof. Klara Nahrstedt. Before coming to UIUC, I got my B.E. degree from Shanghai Jiao Tong University (SJTU), under the supervision of Prof. Xinbing Wang.

The Metaverse integrates augmented reality (AR), virtual reality (VR), and the internet to create a shared, immersive, and interactive environment, enabling a wide specturm of applications.
Despite the hype about the Metaverse, it has never become a reality. I uncover three main obstacles faced by existing immersive computing systems: (1) the exploding amount of data brought by a large virtual world, (2) the disturbing artifacts produced by existing 3D modeling techniques, and (3) the unreliable real-world environments.
To overcome these obstacles, my research advocates AI-system co-design, an approach with two core principles:

1. **System-for-AI Optimization**: *Identifying and employing advanced Artificial Intelligence (AI) techniques to transcend the limitation of traditional immersive computing systems*.
2. **AI-for-System Customization**: *Customizing traditional system optimization techniques to tackle AI-induced system challenges and improve AI performance*.

Guided by these principles, my research bridges the gap between current immersive computing systems and the Metaverse, advancing Bandwidth Efficiency, Photo-realism, and Reliability.

**Research Interests: Networking, operating systems, virtual reality, immersive/visual/spatial computing, and mobile computing.**

<span style="color: red; font-weight: bold;">I am now actively looking for tenure-track faculty positions (2024-2025). Feel free to ping me if you have any openings.</span>

**Here is my [CV](images/CV.pdf).** Contact: boc2 AT illinois DOT edu


# 🔥 News
- *2024.03*: &nbsp;🎉🎉 Paper Accepted in ACM MobiCom'25, NeVo: Advancing Volumetric Video Streaming with Neural Content Representation.
- *2024.11*: &nbsp;🎉🎉 Invited Talk at UM-SJTU Joint Institute, Advancing Immersive Computing with AI-System Co-design.
- *2024.09*: &nbsp;🎉🎉 Paper Conditionally Accepted in ACM SenSys'24, ImmerScope: Multi-view Video Aggregation at Edge towards Immersive Content Services.
- *2024.04*: &nbsp;🎉🎉 Invited Talk at UIUC Sys-Net Spring 2024 Retreat, NeRFHub: A Context-Aware NeRF Serving Framework for Mobile Immersive Applications
- *2024.03*: &nbsp;🎉🎉 Invited Talk at UT Dallas, Advancing Immersive Computing Systems in Age of Machine Learning.
- *2024.03*: &nbsp;🎉🎉 Paper Accepted in ACM MobiSys'24, NeRFHub: A Context-Aware NeRF Serving Framework for Mobile Immersive Applications.
- *2024.01*: &nbsp;🎉🎉 Paper Accepted in ACM MMSys'24, Learning to Manage Uncertainty in Video Streaming.
- *2023.12*: &nbsp;🎉🎉 Paper Accepted in USENIX NSDI'24, LiFteR: Unleash Learned Codecs in Video Streaming with Loose Frame Referencing.

# 📝 Selected Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

- [NeVo: Advancing Volumetric Video Streaming with Neural Content Representation], Nan Wu, **Bo Chen**, Ruizhi Cheng, Klara Nahrstedt, Bo Han, **MobiCom 2025**
- [ImmerScope: Multi-view Video Aggregation at Edge towards Immersive Content Services](https://dl.acm.org/doi/10.1145/3666025.3699324), **Bo Chen**, Hongpeng Guo, Mingyuan Wu, Zhe Yang, Zhisheng Yan, Klara Nahrstedt, **SenSys 2024**
- [LiFteR: Unleash Learned Codecs in Video Streaming with Loose Frame Referencing](https://www.usenix.org/system/files/nsdi24-chen-bo.pdf), **Bo Chen**, Zhisheng Yan, Yinjie Zhang, Zhe Yang, Klara Nahrstedt, **NSDI 2024**
- [NeRFHub: A Context-Aware NeRF Serving Framework for Mobile Immersive Applications](https://dl.acm.org/doi/pdf/10.1145/3643832.3661879), **Bo Chen**, Zhisheng Yan, Bo Han, Klara Nahrstedt, **MobiSys 2024**
- [Vesper: Learning to Manage Uncertainty in Video Streaming](https://dl.acm.org/doi/10.1145/3625468.3647621), **Bo Chen**, Mingyuan Wu, Hongpeng Guo, Zhisheng Yan, Klara Nahrstedt, **MMSys 2024**
- [[Best Student Paper] Context-aware Image Compression Optimization for Visual Analytics Offloading](https://dl.acm.org/doi/10.1145/3625468.3647621), **Bo Chen**, Zhisheng Yan, Klara Nahrstedt, **MMSys 2022**, Media Coverage: [Siebel School News](https://siebelschool.illinois.edu/news/alumnus-bo-chen-wins-best-student-paper-award-from-acm-multimedia-systems-2022), [George Mason University News](https://www.gmu.edu/news/2022-11/zhisheng-yan-nabs-best-student-paper-award)
- [[Best Paper Award] SEAWARE: Semantic Aware View Prediction System for 360-degree Video Streaming](https://dl.acm.org/doi/10.1145/3625468.3647621), Jounsup Park, Mingyuan Wu, Eric Lee, **Bo Chen**, Klara Nahrstedt, Michael Zink, Ramesh Sitaraman, **ISM 2020**
- Please check the full list at [Google Scholar](https://scholar.google.com/citations?user=E8mxs2UAAAAJ) or [dblp](https://dblp.org/pid/89/5615-25.html).

# 🎖 Honors and Awards
- *2022.06* Best Student Paper Award (ACM MMSys 2022).
- *2020.12* Best Paper Award (IEEE ISM 2022).
- *2019.06* SIGMM Travel Grant (ACM MMSys 2019).
 

# 📖 Educations
- *2022.07 - 2024.04 (now)*, Postdoctoral Research Associate at University of Illinois at Urbana-Champaign, Champaign, IL, USA.
- *2016.09 - 2022.05*, Ph.D. at University of Illinois at Urbana-Champaign, Champaign, IL, USA.
- *2012.09 - 2016.06*, B.S. at Shanghai Jiao Tong University, Shanghai, China.
- *2009.09 - 2012.06*, High school at Fuzhou No.1 High School, Fuzhou, China.


# 💻 Internships
- *2020.05 - 2020.08*, Student intern at Meta.
- *2019.05 - 2019.07*, Research intern at AT&T.


# 📖 Teaching
- *2023*, CS 537 Advanced Topics in IOT, Teaching Assistant, University of Illinois at Urbana-Champaign.
- *2022*, CS 537 Advanced Topics in IOT, Teaching Assistant, University of Illinois at Urbana-Champaign.
- *2020*, CS 438 Communication Network, Teaching Assistant, University of Illinois at Urbana-Champaign.


# 💬 Services
- *Reviewer*, 2025: ACM TOMM, IEEE TMM, 2024: ACM MM, IEEE ICCCN, ACM TOMM, 2023: ACM MM, ACM MMSys, ACM TOMM. 
- *TPC Member*, 2025: ACM MMSys, 2024: ACM MMSys, 2023: SEC, ImmerCOM.
- *Publication Chair*, 2024: [NSF Workshop on Sustainable Computing for Sustainability](https://edas.info/web/nsf-wscs24/index.html), 2023: IEEE SECON. 
