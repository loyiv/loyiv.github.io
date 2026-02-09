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

I am **Youwei Liu**, an undergraduate at **Central South University**. I am currently a Research Assistant at **The Hong Kong Polytechnic University (PolyU NLP Lab)**, focusing on long-horizon agent planning by integrating LLM agents, embodied agents, reinforcement learning, and world models. I collaborate with **[Jian Wang](https://iwangjian.github.io/)** on agent. Thanks to him for his generous guidance and support.

# 📖 Education

- <img src="images/csu-logo .png" alt="CSU" style="height:36px; vertical-align:middle; margin-right:8px;">
  **Sep 2023 – 2027 (expected)** &nbsp; **[Central South University](https://en.csu.edu.cn/)** — Changsha, China
  - *Undergraduate Student*
  - Major: Data Science Excellence Talent Program

# 💻 Research Experience

- <img src="images/polyunlp.png" alt="PolyU NLP" style="height:36px; vertical-align:middle; margin-right:8px;">
  **Apr 2025 – Present** &nbsp; **[PolyU NLP Lab](https://polyunlp.github.io/)** — Hong Kong, China
  - *Research Assistant*
  - Working on long-horizon agent planning by integrating LLM agents, embodied agents, reinforcement learning, and world models.

- <img src="images/cuhk.png" alt="CUHK(SZ)" style="height:36px; vertical-align:middle; margin-right:8px;">
  <img src="images/KAUST.png" alt="KAUST" style="height:36px; vertical-align:middle; margin-right:8px;">
  **Jul 2024** &nbsp; **[CUHK (Shenzhen)](https://www.cuhk.edu.cn/en) & [KAUST](https://www.kaust.edu.sa/en/)** — Shenzhen, China
  - *Visiting Student*
  - Supervised by Jinchao Xu; research on multi-scale feature transmission across token, embedding, and contextual layers in LLMs.

# 🔥 News
- *2026.01*: &nbsp; **Imagine-then-Plan (ITP)** released as an **arXiv preprint**. 
  [[arXiv]](https://arxiv.org/abs/2601.08955) · [[PDF]](https://arxiv.org/pdf/2601.08955.pdf) · [[GitHub]](YOUR_ITP_GITHUB_URL) · 🤗 [[Hugging Face]](https://huggingface.co/papers/2601.08955)

# 📝 Publications 

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">arXiv 2026</div>
      <img src='images/itp_workflow.png' alt="ITP workflow" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[**Imagine-then-Plan: Agent Learning from Adaptive Lookahead with World Models**](https://arxiv.org/abs/2601.08955)

**Youwei Liu**, Jian Wang, Hanlin Wang, Beichen Guo, Wenjie Li

[arXiv](https://arxiv.org/abs/2601.08955) &nbsp;|&nbsp; [PDF](https://arxiv.org/pdf/2601.08955.pdf) &nbsp;|&nbsp; [GitHub](YOUR_ITP_GITHUB_URL) &nbsp;|&nbsp; 🤗 [Hugging Face](https://huggingface.co/papers/2601.08955)

- Unified framework for agent learning via **lookahead imagination** with a learned world model.
- **Adaptive lookahead** trades off ultimate goal and task progress to choose imagination horizon dynamically.
- Training-free and RL-trained variants; strong results on representative agent benchmarks.

</div>
</div>

# 🎖 Honors and Awards
- **Outstanding Paper (Oral)** — “Shenzhen Cup” Math Modeling Challenge <span style="float:right;">Aug 2024</span>
- **First Prize**, National Undergraduate Math Modeling Competition <span style="float:right;">Sep 2024</span>
- **First Prize**, National Undergraduate Market Research Analysis (CP Cup) <span style="float:right;">May 2024</span>
- **Second Prize**, CSU Mathematical Modeling Competition <span style="float:right;">Jun 2024</span>
- **National-Level**, Innovation and Entrepreneurship Training Award <span style="float:right;">Apr 2024</span>
- **National Second Prize**, Service Outsourcing Innovation and Entrepreneurship Competition <span style="float:right;">May 2025</span>
- **Honorable Mention**, Mathematical Contest in Modeling (MCM), COMAP-USA <span style="float:right;">Jan 2025</span>



