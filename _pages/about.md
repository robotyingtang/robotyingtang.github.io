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

I am a Ph.D. student in Computer Science and Technology at Huazhong University of Science and Technology. My research focuses on efficient and adaptive visual representation learning, including multi-task representation learning, vision foundation model distillation, Mixture-of-Experts / dynamic routing, feature compression, and long-term visual correspondence.

My current work studies how to analyze, compress, specialize, and recombine visual knowledge. I am particularly interested in building deployable vision systems that transfer complementary knowledge from large vision foundation models into efficient student models, while preserving semantic consistency and reducing negative transfer across tasks and teachers.

I have published papers in ICML, ACM MM, ICME, AAAI, and related multimedia / computer vision venues. Please see my <a href='https://scholar.google.com/citations?user=_MNsF6gAAAAJ'>Google Scholar</a> for the latest publication list and citations <strong><span id='total_cit'>[TODO: citation count]</span></strong>. You can also enable a Google Scholar badge here:
<a href='https://scholar.google.com/citations?user=_MNsF6gAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>


# 🔥 News
- *2026.[TODO]*: &nbsp;🎉 PRISM was accepted to ICML 2026.
- *2025.04*: &nbsp;Temporal Coherent Object Flow for Multi-Object Tracking was published at AAAI 2025.
- *2024.10*: &nbsp;Autogenic Language Embedding for Coherent Point Tracking was published at ACM MM 2024.
- *2024.07*: &nbsp;Agnostic Feature Compression with Semantic Guided Channel Importance Analysis was published at ICME 2024.


# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/prism.png' alt="PRISM" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PRISM: Synergizing Vision Foundation Models via Self-organized Expert Specialization](https://openreview.net/forum?id=3v5l5TepEe)

**Ying Tang**, Dong Li, Youjia Zhang, Zikai Song, Junqing Yu, Wei Yang

[**Project**](https://github.com/robotyingtang/PRISM-VFM) / [**Paper**](https://openreview.net/forum?id=3v5l5TepEe) <strong><span class='show_paper_citations' data='_MNsF6gAAAAJ:[TODO_PRISM_CITATION_ID]'></span></strong>

- We introduce PRISM, a dual-stream Mixture-of-Experts framework for multi-teacher vision foundation model distillation. PRISM decomposes heterogeneous VFM knowledge into specialized expert subspaces and dynamically recomposes them for downstream dense prediction tasks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2024</div><img src='images/icme2024_feature_compression.png' alt="Agnostic Feature Compression" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Agnostic Feature Compression with Semantic Guided Channel Importance Analysis](https://doi.org/10.1109/ICME57554.2024.10687920)

**Ying Tang**, Wei Yang, Junqing Yu, Zikai Song

[**Paper**](https://doi.org/10.1109/ICME57554.2024.10687920) <strong><span class='show_paper_citations' data='_MNsF6gAAAAJ:[TODO_ICME2024_CITATION_ID]'></span></strong>

- We propose a task-agnostic intermediate feature compression framework. It uses Grad-CAM and semantic segmentation to separate essential and peripheral feature channels, then applies different compression strengths to reduce transmission cost with minimal accuracy loss and no retraining.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/altrack.png' alt="ALTrack" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Autogenic Language Embedding for Coherent Point Tracking](https://arxiv.org/abs/2407.20730)

Zikai Song, **Ying Tang**, Run Luo, Lintao Ma, Junqing Yu, Yi-Ping Phoebe Chen, Wei Yang

[**Paper**](https://arxiv.org/abs/2407.20730) / [**Project**](https://github.com/SkyeSong38/ALTrack) <strong><span class='show_paper_citations' data='_MNsF6gAAAAJ:[TODO_ACMMM2024_CITATION_ID]'></span></strong>

- We introduce an autogenic language-assisted tracking framework that learns text embeddings from visual features and integrates them into visual representations, improving semantic consistency for long-term point tracking without explicit text annotations.
</div>
</div>

## Selected Collaborative Publications

- [Temporal Coherent Object Flow for Multi-Object Tracking](https://doi.org/10.1609/aaai.v39i7.32749), Zikai Song, Run Luo, Lintao Ma, **Ying Tang**, Yi-Ping Phoebe Chen, Junqing Yu, Wei Yang, **AAAI 2025**.
- [Exploiting Appearance Re-Emergence for Robust Visual Tracking](https://doi.org/10.1145/3769748.3773347), Zikai Song, Yunyao Zhang, **Ying Tang**, Junqing Yu, Wei Yang, **MMAsia 2025**.
- [MA-VLAD: a fine-grained local feature aggregation scheme for action recognition](https://doi.org/10.1007/s00530-024-01341-9), Na Feng, **Ying Tang**, Zikai Song, Junqing Yu, Yi-Ping Phoebe Chen, Wei Yang, **Multimedia Systems 2024**.
- [Distractor-Aware Tracker with a Domain-Special Optimized Benchmark for Soccer Player Tracking](https://doi.org/10.1145/3460426.3463629), Zikai Song, Zhiwen Wan, Wei Yuan, **Ying Tang**, Junqing Yu, Yi-Ping Phoebe Chen, **ICMR 2021**.


# 🎖 Honors and Awards
- *2024*: Huawei Scholarship.
- *[TODO]*: Ph.D. Graduate Scholarship.
- *[TODO]*: First-Class Graduate Scholarship.
- *[TODO]*: Graduate Freshman Scholarship.


# 📖 Education
- *2022.09 - 2027.06 (expected)*, Ph.D. student in Computer Science and Technology, Huazhong University of Science and Technology.
- *2020.09 - 2022.06*, M.S. in Computer Science and Technology, Huazhong University of Science and Technology.
- *2016.09 - 2020.07*, B.S. in Computer Science and Technology, Jilin University.


# 💻 Skills
- Deep learning frameworks: PyTorch, Python, Linux, Git.
- Research topics: vision foundation models, knowledge distillation, multi-task learning, Mixture-of-Experts, feature compression, semantic correspondence, visual tracking.
- Experimental practice: large-scale training / fine-tuning, ablation study, SOTA comparison, paper writing, and reproducible experiment organization.



# 📌 Misc
- Email: [t_ying@hust.edu.cn](mailto:t_ying@hust.edu.cn)
- Google Scholar: [Ying Tang](https://scholar.google.com/citations?user=_MNsF6gAAAAJ)
- GitHub: [robotyingtang](https://github.com/robotyingtang)
