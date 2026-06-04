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

I'm Yucheng Xing (邢宇程), a PhD student at the National University of Singapore (NUS), advised by [Prof. Mengling Feng](https://www.mornin-feng.com/). My research focuses on information fusion, uncertainty quantification, survival analysis, and computational pathology.

I am always open to collaborations. If you share similar interests, please feel free to reach out.

<a href='https://scholar.google.com/citations?user=uC7NT-IAAAAJ'>My Google Scholar citations <strong><span id='total_cit'>0+</span></strong></a> (<a href='https://scholar.google.com/citations?user=uC7NT-IAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).

<!-- 提示：引用数徽章要在你把 _config.yml 的 repository 改成自己的仓库、且 GitHub Actions 跑过一次后才显示真实数字。 -->

# 📝 Publications 

‡: Co-First Authors

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/dpsurv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DPsurv: Dual-Prototype Evidential Fusion for Uncertainty-Aware and Interpretable Whole-Slide Image Survival Prediction](https://arxiv.org/abs/2510.00053)

**Yucheng Xing**, Ling Huang, Jingying Ma, Ruping Hong, Jiangdong Qiu, Pei Liu, Kai He, Huazhu Fu, Mengling Feng

[**arXiv**](https://arxiv.org/abs/2510.00053)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/codebrain.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CodeBrain: Bridging Decoupled Tokenizer and Multi-Scale Architecture for EEG Foundation Model](https://arxiv.org/abs/2506.09110)

Jingying Ma‡, Feng Wu‡, Qika Lin, **Yucheng Xing**, Chenyu Liu, Ziyu Jia, Mengling Feng

[**arXiv**](https://arxiv.org/abs/2506.09110) [![](https://img.shields.io/badge/CodeBrain-blue?logo=github)](https://github.com/jingyingma01/CodeBrain)
</div>
</div>

- Preprint [SCOPE: Structured Prototype-Guided Adaptation for EEG Foundation Models with Limited Labels](https://arxiv.org/abs/2602.17251)  
Jingying Ma‡, Feng Wu‡, **Yucheng Xing**, Qika Lin, Tianyu Liu, Chenyu Liu, Ziyu Jia, Mengling Feng

<!-- TODO: 后续论文照上面格式加。带缩略图的用 paper-box 块；纯列表的用 "- 会议/期刊 [标题](链接)" 一行。作者列表里把自己加粗 **Yucheng Xing**。 -->

# 🎖 Honors and Awards
*To be added.*
<!-- TODO 示例:
- *2024.08* President's Graduate Fellowship, National University of Singapore
-->

# 📖 Educations
*To be added.*
<!-- TODO 示例:
- *2024.08 - now*, Ph.D., <学院/专业>, National University of Singapore, Singapore
- *2020.09 - 2024.06*, B.E., <专业>, <本科学校>, China
-->

# 💻 Experience
*To be added.*
<!-- TODO 示例:
- *2023.xx - 2024.xx*, Research Assistant, <单位>, supervised by [Prof. xxx](链接).
-->

# 💬 Academic Services
*To be added.*
<!-- TODO 示例:
- Conference Reviewer: ICML, NeurIPS
- Journal Reviewer: xxx
-->

# 🎓 Teaching
*To be added.*
<!-- TODO 示例:
- *2026.01 - 2026.05*, Teaching Assistant, <课程代码 课程名>, National University of Singapore
-->
