---
permalink: /
author_profile: true
stylesheets:
  - /assets/css/home.css
redirect_from:
  - /about/
  - /about.html
---
<h1 class="main-heading">Hi there <img src="images/Hi.gif" width="40px"> Welcome to my Homepage!</h1>

I am **Zixuan Weng**, a Ph.D. student in Computer Science and Engineering at the **Georgia Institute of Technology**, advised by [Prof. Ling Liu](https://faculty.cc.gatech.edu/~lingliu/). I received my B.Eng. in Computer Science and Technology from **Beijing Jiaotong University** in 2024.

My research interests include large language model safety, agent safety, and agentic reinforcement learning. Feel free to [contact me](mailto:zxweng0701@gmail.com) about research collaboration and academic opportunities.

News
---------------
<div class="news-box">
  <ul class="news-list">
    <li><span class="news-date"><em>2026.04</em></span> FineSteer was accepted to ACL 2026 as an oral paper (Top 4%).</li>
    <li><span class="news-date"><em>2025.08</em></span> Foot-In-The-Door was accepted to EMNLP 2025 as an oral paper (Top 4%).</li>
    <li><span class="news-date"><em>2025.08</em></span> Recognized as a KDD Outstanding Reviewer (Top 10%).</li>
    <li><span class="news-date"><em>2025.06</em></span> JailbreakDiffBench was accepted to ICCV 2025.</li>
    <li><span class="news-date"><em>2025.05</em></span> SDE was accepted to KDD 2025.</li>
    <li><span class="news-date"><em>2024.02</em></span> Our work on PPR-based embeddings was accepted to WWW 2024 as an oral paper (Top 9%).</li>
  </ul>
</div>

Education
--------------

<div class="experience-container">
  <div class="experience-card">
      <img src="images/georgia-tech-logo.png" alt="Georgia Institute of Technology logo" class="experience-logo">
      <div class="experience-info">
          <strong><a href="https://www.gatech.edu/">Georgia Institute of Technology</a></strong><br>
          <em>Aug. 2026 - Present</em><br>
          Ph.D. in Computer Science and Engineering<br>
          <span style="color:#888;">Advisor: <a href="https://faculty.cc.gatech.edu/~lingliu/">Prof. Ling Liu</a></span>
      </div>
  </div>

  <div class="experience-card">
      <img src="images/beijing-jiaotong-logo.png" alt="Beijing Jiaotong University logo" class="experience-logo">
      <div class="experience-info">
          <strong><a href="https://www.bjtu.edu.cn/">Beijing Jiaotong University</a></strong><br>
          <em>Sept. 2020 - Jun. 2024</em><br>
          B.Eng. in Computer Science and Technology
      </div>
  </div>
</div>

Publications
--------------
<button class="pub-button active" onclick="filterPublications(event, 'all')">Core Publications</button>
<button class="pub-button" onclick="filterPublications(event, 'list')">Full Publications List</button>

(* equal contribution)

<div id="core-publications" class="publication-view" data-publication-view="core">
<div class="publication-card" data-category="all">
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;">
      <img src="images/sleep.png" alt="FineSteer" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;">
    </div>
    <div>
      <strong>FineSteer: A Unified Framework for Fine-grained Inference-time Steering in Large Language Models</strong><br>
      <i style="font-size: 13px;"><strong>Zixuan Weng</strong>, Jinghuai Zhang, Kunlin Cai, Ying Li, Peiran Wang, Yuan Tian.</i><br>
      A unified framework for constructing fine-grained, query-specific steering vectors for large language models.<br>
      <b><i style="color:#83a1c7;">ACL 2026 Oral (Top 4%) &nbsp;</i></b>
      <a href="https://arxiv.org/abs/2604.15488"><em>[paper]</em></a>
    </div>
  </div>
</div>

<div class="publication-card" data-category="all">
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;">
      <img src="images/gpu.png" alt="Foot-In-The-Door" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;">
    </div>
    <div>
      <strong>Foot-In-The-Door: A Multi-turn Jailbreak for LLMs</strong><br>
      <i style="font-size: 13px;"><strong>Zixuan Weng</strong>, Xiaolong Jin, Jinyuan Jia, Xiangyu Zhang.</i><br>
      A multi-turn jailbreak strategy motivated by the Foot-In-The-Door phenomenon.<br>
      <b><i style="color:#83a1c7;">EMNLP 2025 Oral (Top 4%) &nbsp;</i></b>
      <a href="https://aclanthology.org/2025.emnlp-main.100.pdf"><em>[paper]</em></a>
    </div>
  </div>
</div>

<div class="publication-card" data-category="all">
  <div style="display: flex; align-items: center;">
    <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;">
      <img src="images/noodle.png" alt="SDE" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;">
    </div>
    <div>
      <strong>SDE: A Simplified and Disentangled Dependency Encoding Framework for State Space Models in Time Series Forecasting</strong><br>
      <i style="font-size: 13px;"><strong>Zixuan Weng</strong>, Jindong Han, Wenzhao Jiang, Hao Liu.</i><br>
      A simplified state space model with disentangled dependency encoding for time series forecasting.<br>
      <b><i style="color:#83a1c7;">KDD 2025 &nbsp;</i></b>
      <a href="https://arxiv.org/abs/2408.12068"><em>[paper]</em></a>
    </div>
  </div>
</div>
</div>

<div id="full-publications" class="publication-view" data-publication-view="list" hidden>
  <ol class="full-publication-list">
    <li><span class="pub-list-badge">ACL 2026</span> <span class="pub-list-title">FineSteer: A Unified Framework for Fine-grained Inference-time Steering in Large Language Models.</span><br><span class="pub-list-authors"><strong>Zixuan Weng</strong>, Jinghuai Zhang, Kunlin Cai, Ying Li, Peiran Wang, Yuan Tian.</span> <span class="pub-list-note">Oral, Top 4%.</span> <span class="pub-list-links"><a href="https://arxiv.org/abs/2604.15488">[paper]</a></span></li>
    <li><span class="pub-list-badge">EMNLP 2025</span> <span class="pub-list-title">Foot-In-The-Door: A Multi-turn Jailbreak for LLMs.</span><br><span class="pub-list-authors"><strong>Zixuan Weng</strong>, Xiaolong Jin, Jinyuan Jia, Xiangyu Zhang.</span> <span class="pub-list-note">Oral, Top 4%.</span> <span class="pub-list-links"><a href="https://aclanthology.org/2025.emnlp-main.100.pdf">[paper]</a></span></li>
    <li><span class="pub-list-badge">KDD 2025</span> <span class="pub-list-title">SDE: A Simplified and Disentangled Dependency Encoding Framework for State Space Models in Time Series Forecasting.</span><br><span class="pub-list-authors"><strong>Zixuan Weng</strong>, Jindong Han, Wenzhao Jiang, Hao Liu.</span> <span class="pub-list-links"><a href="https://arxiv.org/abs/2408.12068">[paper]</a></span></li>
    <li><span class="pub-list-badge">ICCV 2025</span> <span class="pub-list-title">JailbreakDiffBench: A Comprehensive Benchmark for Jailbreaking Diffusion Models.</span><br><span class="pub-list-authors">Xiaolong Jin, <strong>Zixuan Weng</strong>, Hanxi Guo, Siyuan Cheng, Guangyu Shen, Chenlong Yin, Xiangyu Zhang.</span> <span class="pub-list-links"><a href="https://openaccess.thecvf.com/content/ICCV2025/papers/Jin_JailbreakDiffBench_A_Comprehensive_Benchmark_for_Jailbreaking_Diffusion_Models_ICCV_2025_paper.pdf">[paper]</a></span></li>
    <li><span class="pub-list-badge">WWW 2024</span> <span class="pub-list-title">Towards Deeper Understanding of PPR-based Embedding Approaches: A Topological Perspective.</span><br><span class="pub-list-authors">Xingyi Zhang, <strong>Zixuan Weng</strong>, Sibo Wang.</span> <span class="pub-list-note">Oral, Top 9%.</span> <span class="pub-list-links"><a href="https://dl.acm.org/doi/abs/10.1145/3589334.3645663">[paper]</a></span></li>
    <li><span class="pub-list-badge">UbiComp 2023</span> <span class="pub-list-title">I Know Your Intent: Graph-Enhanced Intent-Aware User Device Interaction Prediction via Contrastive Learning.</span><br><span class="pub-list-authors">Jingyu Xiao, Qingsong Zou, Qing Li, Dan Zhao, Kang Li, <strong>Zixuan Weng</strong>, Ruoyu Li, Yong Jiang.</span> <span class="pub-list-links"><a href="https://dl.acm.org/doi/10.1145/3610906">[paper]</a></span></li>
    <li><span class="pub-list-badge">Preprint</span> <span class="pub-list-title">DAMBench: A Multi-Modal Benchmark for Deep Learning-based Atmospheric Data Assimilation.</span><br><span class="pub-list-authors">Hao Wang*, <strong>Zixuan Weng*</strong>, Hao Liu.</span> <span class="pub-list-note">In submission.</span></li>
  </ol>
</div>

<script src="assets/js/show_publications.js"></script>
<script src="assets/js/pub_media_rotator.js"></script>

Experience
--------------

### VLM Red-Teaming (Talent Program), ByteDance
*Talent Program (Jindouyun) Intern, advised by [Bai Yang](https://bymavis.github.io/) | Sep. 2025 - May 2026*

- Conducted red-teaming for Doubao and Volcano Ark.
- Built a security assessment platform for the technology middle platform.
- Addressed real-world security problems using production data and requirements.

### LLM Steering
*Research Assistant, advised by [Prof. Yuan Tian](https://www.ytian.info/) (UCLA) | Jun. 2025 - Jan. 2026*

- Developed an efficient method for constructing query-specific steering vectors.
- Achieved state-of-the-art performance in jailbreak defense and hallucination reduction with little to no impact on general model performance.
- Led the resulting ACL submission as first author.

### LLM Jailbreak
*Research Assistant, advised by [Prof. Jinyuan Jia](https://jinyuan-jia.github.io/) (Penn State) and [Prof. Xiangyu Zhang](https://www.cs.purdue.edu/homes/xyzhang/) (Purdue) | Dec. 2024 - May 2025*

- Introduced a novel multi-turn jailbreak strategy motivated by the Foot-In-The-Door phenomenon.
- Achieved a jailbreak success rate above 94% on mainstream LLMs.
- Led the resulting EMNLP paper as first author.

### Time Series Forecasting
*Research Assistant, advised by [Prof. Hao Liu](https://raymondhliu.github.io/) (HKUST) | Feb. 2024 - May 2024*

- Identified and formally defined three dependencies in time series.
- Analyzed Mamba's strengths and adaptation challenges for time series forecasting.
- Proposed a simplified Mamba with a theoretically grounded disentangled encoding strategy.

### Understanding PPR-Based Graph Embeddings
*Research Assistant, advised by [Prof. Sibo Wang](https://www1.se.cuhk.edu.hk/~swang/) (CUHK) | Jul. 2023 - Oct. 2023*

- Studied random-walk-based graph embedding methods and developed a method to analyze information encoded by PPR embeddings.
- Improved performance recovery by 10% for average path length and 5% for community connectivity over the baseline.

### User Behavior Prediction with Graph Contrastive Learning
*Research Assistant, advised by [Prof. Yong Jiang](https://www.sigs.tsinghua.edu.cn/jy/main.htm) (Tsinghua University) | Oct. 2022 - Jun. 2023*

- Developed a cluster-based historical attention mechanism for capturing multi-level periodicity in user behavior.
- Improved performance by an average of 7% over state-of-the-art baselines while providing better interpretability.
- Contributed to a paper published at UbiComp/ISWC 2023.

Awards
--------
- **2025**, KDD Outstanding Reviewer (Top 10%).
- **2023**, National College Students' Innovative Entrepreneurial Training Plan Program (Top 5%).
- **2023**, National Scholarship (Top 1%).
- **2023**, First Class Scholarship for Academic Performance (Top 2%).
- **2023**, Second Class Scholarship for Social Work Performance (Top 5%).

Academic Services
--------
- **Session Chair:** KDD 2025.
- **Reviewer:** NeurIPS 2026; CVPR 2026; ARR May 2025; WWW 2026; KDD 2024, 2025, and 2026.
- **Volunteer:** KDD 2025; EMNLP 2025.
