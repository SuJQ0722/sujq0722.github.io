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


# 😎 About Me
I'm an undergraduate at Shanghai Jiao Tong University (SJTU), pursuing a B.Eng. in Electrical Engineering and Automation (expected Jun 2026). I'm now a research intern with the UIUC Ulab & OpenManus Team, advised by Prof. Jiaxuan You. My work focuses on multi-agent protocols, GUI agent, and agentic reinforcement learning.

## Research interests
My current research centers around the following domains:
- Multimodal Agentic Reinforcement Learning
- World Foundation Models
- Multi-Agent System Design


# 🔥 News
- 2025.06 — Paper on synthetic data for autonomous driving accepted by ICCV 2025.
- 2025.05 — Joined UIUC Ulab & OpenManus Team as a Research Intern (Urbana, IL).
- 2024.05 — Joined SJTU CMIC as a Research Intern (Shanghai), advised by Prof. Siheng Chen.

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026 Submission</div><img src='images/500x300.png' alt="paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Which LLM Multi-Agent Protocol to Choose?](#)

- Designed four scenarios to fairly compare A2A, ACP, ANP, and Agora and proposed a meta-protocol with an intelligent router for dynamic selection per scenario. [![](https://img.shields.io/github/stars/MultiagentBench/Multiagent-Protocol?style=social&label=Code+Stars)](https://github.com/MultiagentBench/Multiagent-Protocol)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026 Submission</div><img src='images/500x300.png' alt="paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MASLab: A Unified and Comprehensive Codebase for LLM-based Multi-Agent Systems](https://arxiv.org/abs/2505.16988), Rui Ye, Keduan Huang, Qimin Wu, Yuzhu Cai, Tian Jin, Xianghe Pang, Xiangrui Liu, **Jiaqi Su**, Chen Qian, Bohan Tang, Kaiqu Liang, Jiaao Chen, Yue Hu, Zhenfei Yin, Rongye Shi, Bo An, Yang Gao, Wenjun Wu, Lei Bai, Siheng Chen

- Integrated 20+ methods with standardized benchmarks and evaluation protocols for reproducible research and fair comparison. [![](https://img.shields.io/github/stars/MASWorks/MASLab?style=social&label=Code+Stars)](https://github.com/MASWorks/MASLab)
</div>
</div>

- ``arXiv`` [Unraveling the effects of synthetic data on end-to-end autonomous driving](https://www.arxiv.org/abs/2503.18108), Junhao Ge, Zuhong Liu, Longteng Fan, Yifan Jiang, **Jiaqi Su**, Yiming Li, Zhejun Zhang, Siheng Chen. [![](https://img.shields.io/github/stars/cancaries/SceneCrafter?style=social&label=Code+Stars)](https://github.com/cancaries/SceneCrafter)

# 🎖 Honors and Awards
- 2025 — Challenge Cup (Training Optimization and Inference Acceleration for Reasoning LLMs): Second place nationwide. Collaborated with Prof. Erhu Feng and Prof. Muning Wen; developed GRPO/PPO training and deployment pipelines based on veRL; led inference optimization including speculative decoding and heterogeneous deployment across CPU and NPU.

# 📖 Educations
- 2022.09 — 2026.06 (expected), B.Eng. in Electric Power Engineering and Automation, Shanghai Jiao Tong University (SJTU), Shanghai, China.

# 💻 Internships
- 2025.05 — Present, UIUC Ulab & OpenManus Team, Research Intern, Urbana, IL. Advisor: Prof. Jiaxuan You. Focus: multi-agent protocols, GUI agent and embodied navigation.
- 2024.05 — 2025.05, SJTU CMIC, Research Intern, Shanghai. Advisor: Prof. Siheng Chen. Focus: multi-agent system evaluation and coordination strategies.

# 📝 Blogs
<ul class="blog-cards">
  <li class="blog-card">
    <a class="blog-card__link" href="/blogs/2025-10-3-gui/">
      <div class="blog-card__content">
        <div class="blog-card__meta">Oct 3, 2025</div>
        <div class="blog-card__title">The Evolving Face of GUI: Lessons from Recent Work</div>
        <div class="blog-card__excerpt">Summary of recent GUI agent works and insights on training, evaluation, and design patterns.</div>
        <div class="blog-card__tags"><span class="tag-chip">gui</span><span class="tag-chip">agents</span><span class="tag-chip">training paradigm</span></div>
      </div>
      <div class="blog-card__arrow">›</div>
    </a>
  </li>
</ul>

<p><a href="/blogs/">View all blogs →</a></p>