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

**Research Interests: Networking, ML systems, virtual reality, immersive/visual/spatial computing, and mobile/edge computing.**

<span style="color: red; font-weight: bold;">I am now on job market (2024-2025). Feel free to ping me if you have any openings.</span>

**Here is my [CV](images/CV.pdf), [Research Statement](images/research-statement.pdf), and [Teaching Statement](images/teaching-statement.pdf).** Contact: boc2 AT illinois DOT edu

A list of useful resources for a tentative course on **"immersive computing with AI-system co-design"** [here](/resources/).

This is Bo Chen, a postdoc at University of Illinois at Urbana-Champaign (UIUC) working with Prof. Klara Nahrstedt. I obtained my Ph.D. in computer science at UIUC in 2022, advised by Prof. Klara Nahrstedt. Before coming to UIUC, I got my B.E. degree from Shanghai Jiao Tong University (SJTU), under the supervision of Prof. Xinbing Wang.

I build immersive computing systems that support advanced Artificial Intelligence (AI) models with AI-system co-design:

1. **AI-for-Immersion Insight**: *Identifying insights from Artificial Intelligence (AI) techniques to overcome the limitation of traditional immersive computing systems*.
2. **AI-System Joint Design**: *Customized system optimization and adapt AI architecture or training to overcome performance degradation of AI systems*.

Guided by AI-system co-design, my research advances immersive computing systems in the following directions:

### **1. Efficiency**
- 2D Video Streaming [(NSDI'24)](https://www.usenix.org/system/files/nsdi24-chen-bo.pdf)  
- Multi-view Video Streaming [(SenSys'24)](https://dl.acm.org/doi/10.1145/3666025.3699324)  
- Visual Analytics Offloading [(MMSys'22, Best Student Paper)](https://dl.acm.org/doi/10.1145/3524273.3528178)  
- 360 Video Streaming [(ISM'20, Best Paper Award)](https://ieeexplore.ieee.org/document/9327920)  
- Efficient LLM Serving with Cache [(Arxiv'25)](https://arxiv.org/pdf/2502.20587)  

### **2. Photo-realism**
- NeRF-based Video Streaming with Viewport Optimization [(MobiCom'25)](https://www.sigmobile.org/mobicom/2025/cfp.html)  
- NeRF-based Video Streaming with Rate Adaptation [(MobiSys'25)](https://www.sigmobile.org/mobisys/2025/)  
- 3D Gaussian Splatting-based Video Streaming [(HotMobile'25)](https://hotmobile.org/2025/)  
- NeRF-based 3D Content Serving [(MobiSys'24)](https://dl.acm.org/doi/pdf/10.1145/3643832.3661879)  

### **3. Reliability**
- Uncertainty in 2D Video Streaming [(MMSys'24)](https://dl.acm.org/doi/10.1145/3625468.3647621)  
- Reliable Gauge Reading [(MIPR'24)](https://ieeexplore.ieee.org/document/10707806)  
- Quantization Rectification in Image Compression [(ICML'23 NCW)](https://arxiv.org/pdf/2403.17236)  
- Reliable Underwater Image Transmission [(Arxiv'25)](https://arxiv.org/pdf/2502.10891)  


# 🔥 News
- *2025.3*: &nbsp;🎉🎉 Paper Conditionally Accepted in **ACM MobiSys'25**, NeRFlow: Towards Adaptive Streaming for NeRF Videos.
- *2025.1*: &nbsp;🎉🎉 Paper Accepted in **ACM HotMobile'25**, Advancing Immersive Content Delivery with Dynamic 3D Gaussian Splatting.
- *2024.12*: &nbsp;🎉🎉 Paper Accepted in **ACM MobiCom'25**, NeVo: Advancing Volumetric Video Streaming with Neural Content Representation.
- *2024.12*: &nbsp;🎉🎉 Invited Talk at Shanghai Jiao Tong University, Advancing Immersive Computing with AI-System Co-design.
- *2024.11*: &nbsp;🎉🎉 Invited Talk at UM-SJTU Joint Institute, Advancing Immersive Computing with AI-System Co-design.
- *2024.09*: &nbsp;🎉🎉 Paper Accepted in **ACM SenSys'24**, ImmerScope: Multi-view Video Aggregation at Edge towards Immersive Content Services.
- *2024.04*: &nbsp;🎉🎉 Invited Talk at UIUC Sys-Net Spring 2024 Retreat, NeRFHub: A Context-Aware NeRF Serving Framework for Mobile Immersive Applications.
- *2024.03*: &nbsp;🎉🎉 Invited Talk at UT Dallas, Advancing Immersive Computing Systems in Age of Machine Learning.
- *2024.03*: &nbsp;🎉🎉 Paper Accepted in **ACM MobiSys'24**, NeRFHub: A Context-Aware NeRF Serving Framework for Mobile Immersive Applications.
- *2024.01*: &nbsp;🎉🎉 Paper Accepted in **ACM MMSys'24**, Learning to Manage Uncertainty in Video Streaming.
- *2023.12*: &nbsp;🎉🎉 Paper Accepted in **USENIX NSDI'24**, LiFteR: Unleash Learned Codecs in Video Streaming with Loose Frame Referencing.

# 📝 Selected Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

- [**MobiSys 2025**] Rui-xiao Zhang, Tianchi Huang, **Bo Chen**, Klara Nahrstedt, "NeRFlow: Towards Adaptive Streaming for NeRF Videos"
- [**MobiCom 2025**] Nan Wu, **Bo Chen**, Ruizhi Cheng, Klara Nahrstedt, Bo Han, "NeVo: Advancing Volumetric Video Streaming with Neural Content Representation"
- [**SenSys 2024**] **Bo Chen**, Hongpeng Guo, Mingyuan Wu, Zhe Yang, Zhisheng Yan, Klara Nahrstedt, [ImmerScope: Multi-view Video Aggregation at Edge towards Immersive Content Services](https://dl.acm.org/doi/10.1145/3666025.3699324)
- [**NSDI 2024**] **Bo Chen**, Zhisheng Yan, Yinjie Zhang, Zhe Yang, Klara Nahrstedt, [LiFteR: Unleash Learned Codecs in Video Streaming with Loose Frame Referencing](https://www.usenix.org/system/files/nsdi24-chen-bo.pdf)
- [**MobiSys 2024**] **Bo Chen**, Zhisheng Yan, Bo Han, Klara Nahrstedt, [NeRFHub: A Context-Aware NeRF Serving Framework for Mobile Immersive Applications](https://dl.acm.org/doi/pdf/10.1145/3643832.3661879)
- [**MMSys 2024**] **Bo Chen**, Mingyuan Wu, Hongpeng Guo, Zhisheng Yan, Klara Nahrstedt, [Vesper: Learning to Manage Uncertainty in Video Streaming](https://dl.acm.org/doi/10.1145/3625468.3647621)
- [**MMSys 2022 (Best Student Paper)**] **Bo Chen**, Zhisheng Yan, Klara Nahrstedt, [Context-aware Image Compression Optimization for Visual Analytics Offloading](https://dl.acm.org/doi/10.1145/3524273.3528178), Media Coverage: [Siebel School News](https://siebelschool.illinois.edu/news/alumnus-bo-chen-wins-best-student-paper-award-from-acm-multimedia-systems-2022), [George Mason University News](https://www.gmu.edu/news/2022-11/zhisheng-yan-nabs-best-student-paper-award)
- [**ISM 2020 (Best Paper Award)**]Jounsup Park, Mingyuan Wu, Eric Lee, **Bo Chen**, Klara Nahrstedt, Michael Zink, Ramesh Sitaraman, [SEAWARE: Semantic Aware View Prediction System for 360-degree Video Streaming](https://ieeexplore.ieee.org/document/9327920)
- Please check the full list at [Google Scholar](https://scholar.google.com/citations?user=E8mxs2UAAAAJ) or [dblp](https://dblp.org/pid/89/5615-25.html).


# 🎖 Honors and Awards
- *2022.06* Best Student Paper Award (ACM MMSys 2022).
- *2020.12* Best Paper Award (IEEE ISM 2022).
- *2019.06* SIGMM Travel Grant (ACM MMSys 2019).
 

# 📖 Educations
- *2022.07 - 2025.03 (now)*, Postdoctoral Research Associate at University of Illinois at Urbana-Champaign, Champaign, IL, USA.
- *2016.09 - 2022.05*, Ph.D. at University of Illinois at Urbana-Champaign, Champaign, IL, USA.
- *2012.09 - 2016.06*, B.S. at Shanghai Jiao Tong University, Shanghai, China.
- *2009.09 - 2012.06*, High school at Fuzhou No.1 High School, Fuzhou, China.


# 💻 Internships
- *2020.05 - 2020.08*, Student intern at Meta.
- *2019.05 - 2019.07*, Research intern at AT&T.


# 📖 Teaching
- *2024*, CS 537 Advanced Topics in IOT, Teaching Assistant, University of Illinois at Urbana-Champaign.
- *2023*, CS 537 Advanced Topics in IOT, Teaching Assistant, University of Illinois at Urbana-Champaign.
- *2022*, CS 537 Advanced Topics in IOT, Teaching Assistant, University of Illinois at Urbana-Champaign.
- *2020*, CS 438 Communication Network, Teaching Assistant, University of Illinois at Urbana-Champaign.


# 💬 Services
- *Reviewer*, 2025: ACM MM, ACM TOMM, IEEE TMM, 2024: ACM MM, IEEE ICCCN, ACM TOMM, 2023: ACM MM, ACM MMSys, ACM TOMM. 
- *TPC Member*, 2025: ACM MMSys, 2024: ACM MMSys, 2023: SEC, ImmerCOM.
- *Publication Chair*, 2024: [NSF Workshop on Sustainable Computing for Sustainability](https://edas.info/web/nsf-wscs24/index.html), 2023: IEEE SECON. 
