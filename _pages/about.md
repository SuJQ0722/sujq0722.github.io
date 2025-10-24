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


# 🎓 About Me
I'm an undergraduate at Shanghai Jiao Tong University (SJTU), pursuing a B.Eng. in Electrical Engineering and Automation (expected Jun 2026). Currently, I serve as a research intern with the [UIUC Ulab](https://ulab-uiuc.github.io/) & OpenManus Team under the guidance of Prof. [Jiaxuan You](https://cs.stanford.edu/~jiaxuan/), where my research focuses on multi-agent systems, GUI agents, and agentic reinforcement learning. Prior to this, I completed a research internship at [SJTU CMIC](https://cmic.sjtu.edu.cn/CN/Default.aspx), advised by Prof. [Siheng Chen](https://siheng-chen.github.io/).

<span style="color: red;">I am actively seeking PhD/Research Assistant positions or collaboration opportunities in multimodal agents and world models. I would be truly honored and excited to connect with anyone interested in these areas—please don't hesitate to reach out!</span>

## Research interests
My current research centers around the following domains:
- Multimodal Agentic Learning and Reasoning
- World Models For Multimodal Agents
- Multi-Agent System Design

and many other topics like tool-integrated reasoning, spatial reasoning...

# 🔥 News
- 2025.06 — One paper is accepted by ICCV 2025.
- 2025.05 — Joined UIUC Ulab & OpenManus Team as a Research Intern (Urbana, IL).
- 2024.05 — Joined SJTU CMIC as a Research Intern (Shanghai), advised by Prof. Siheng Chen.

# 📝 Publications

<div class="pub-list" markdown="1">

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026 Submission</div><img src='images/protocolbench_figure.png' alt="paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Which LLM Multi-Agent Protocol to Choose?](https://arxiv.org/abs/2510.17149), Hongyi Du\*, **Jiaqi Su\***, Jisen Li\*, Lijie Ding, Yingxuan Yang, Peixuan Han, Xiangru Tang, Kunlun Zhu, Jiaxuan You

- Designed four scenarios to fairly compare A2A, ACP, ANP, and Agora and proposed a meta-protocol with an intelligent router for dynamic selection per scenario. [![](https://img.shields.io/github/stars/MultiagentBench/Multiagent-Protocol?style=social&label=Code+Stars)](https://github.com/MultiagentBench/Multiagent-Protocol)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026 Submission</div><img src='images/maslab_figure.png' alt="paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MASLab: A Unified and Comprehensive Codebase for LLM-based Multi-Agent Systems](https://arxiv.org/abs/2505.16988), Rui Ye, Keduan Huang, Qimin Wu, Yuzhu Cai, Tian Jin, Xianghe Pang, Xiangrui Liu, **Jiaqi Su**, Chen Qian, Bohan Tang, Kaiqu Liang, Jiaao Chen, Yue Hu, Zhenfei Yin, Rongye Shi, Bo An, Yang Gao, Wenjun Wu, Lei Bai, Siheng Chen

- Integrated 20+ MAS workflows with standardized benchmarks and evaluation protocols for reproducible research and fair comparison. [![](https://img.shields.io/github/stars/MASWorks/MASLab?style=social&label=Code+Stars)](https://github.com/MASWorks/MASLab)
</div>
</div>

- ``ICCV 2025`` [Unraveling the effects of synthetic data on end-to-end autonomous driving](https://www.arxiv.org/abs/2503.18108), Junhao Ge\*, Zuhong Liu\*, Longteng Fan, Yifan Jiang, **Jiaqi Su**, Yiming Li, Zhejun Zhang, Siheng Chen. [![](https://img.shields.io/github/stars/cancaries/SceneCrafter?style=social&label=Code+Stars)](https://github.com/cancaries/SceneCrafter)

</div>

# 🎖 Honors and Awards
- **First Place Nationwide (1/35) — Challenge Cup 2025** (Training Optimization and Inference Acceleration for Reasoning LLMs). Led inference optimization (speculative decoding, CPU/NPU deployment) and GRPO/PPO pipeline development.

# 📖 Educations
- 2022.09 — 2026.06 (expected), B.Eng. in Electric Power Engineering and Automation, Shanghai Jiao Tong University (SJTU), Shanghai, China.

# 💻 Internships
- 2025.05 — Present, UIUC Ulab & OpenManus Team, Research Intern, Urbana, IL. Advisor: Prof. [Jiaxuan You](https://cs.stanford.edu/~jiaxuan/). Focus: multi-agent protocols, GUI agent and embodied navigation.
- 2024.05 — 2025.05, SJTU CMIC, Research Intern, Shanghai. Advisor: Prof. [Siheng Chen](https://siheng-chen.github.io/). Focus: multi-agent system evaluation and coordination strategies.

# 📝 Blogs
*Just so you know, my posts are pretty much just my study notes. I'd love to hear your thoughts and discuss!*
{% include blog_section.html show_heading=false cta=true align='left' %}

<!-- # 🌍 Visitors
<div style="text-align:center; margin: 12px 0;">
<script type="text/javascript" id="mapmyvisitors" src="//mapmyvisitors.com/map.js?d=gsZjV6vDBjLTzyjFrFBYsx6n0kEPCQHS6l7NG-dkOB8&cl=ffffff&w=a"></script>
</div> -->