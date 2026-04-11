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

I am a 2rd-year Ph.D. student at the School of Artificial Intelligence, Xidian University, supervised by <a href="https://web.xidian.edu.cn/ldli/index.html">Prof. Leida Li</a>. Prior to this, I received the B.Sc. degree from China University of Mining and Technology and M.Sc. degree from Xidian University. My research interests include Visual Quality Assessment and T2I Generation Evaluation.


# 🔥 News
- *2026.04*: &nbsp;🎉🎉 FG-IAA accepted as an **Oral presentation** at CVPR 2026.
- *2026.03*: &nbsp;🎉🎉 One paper (AesBench) accepted by **ICME 2026**.
- *2026.02*: &nbsp;🎉🎉 One paper (FG-IAA) accepted by **CVPR 2026**.
- *2025.11*: &nbsp;🎉🎉 Three papers (LongT2IBench, FGResQ, TuningIQA) accepted by **AAAI 2026**, with LongT2IBench as an **Oral presentation**.
- *2024.07*: &nbsp;🎉🎉 Two papers (TMCR, AesExpert) accepted by **ACM Multimedia 2024**. 
- *2024.01*: &nbsp;🎉🎉 One paper (MTCL) accepted by **IEEE Transactions on Multimedia**.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026 Oral</div><img src='images/FGAesthetics+Q.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fine-grained Image Aesthetic Assessment: Learning Discriminative Scores from Relative Ranks](https://arxiv.org/abs/2603.03907)

 **Zhichao Yang**†, Jianjie Wang†, Zhixianhe Zhang, Pangu Xie, Xiangfei Sheng, Pengfei Chen, Leida Li

\[[Paper](https://arxiv.org/abs/2603.03907)\] \[[Project](https://yzc-ippl.github.io/FG-IAA/)\] \[[Code](https://github.com/yzc-ippl/FG-IAA)\] 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026 Oral</div><img src='images/LongT2IBench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LongT2IBench: A Benchmark for Evaluating Long Text-to-Image Generation with Graph-structured Annotations](https://arxiv.org/abs/2512.09271)

 **Zhichao Yang**, Tianjiao Gu, Jianjie Wang, Feiyu Lin, Xiangfei Sheng, Pengfei Chen, Leida Li

\[[Paper](https://arxiv.org/abs/2512.09271)\] \[[Project](https://welldky.github.io/LongT2IBench-Homepage/)\] \[[Code](https://github.com/yzc-ippl/LongT2IBench)\] 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/TMCR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Semantics-Aware Image Aesthetics Assessment using Tag Matching and Contrastive Ranking](https://dl.acm.org/doi/abs/10.1145/3664647.3680972)

 **Zhichao Yang**, Leida Li, Pengfei Chen, Jinjian Wu, Weisheng Dong

\[[Paper](https://dl.acm.org/doi/abs/10.1145/3664647.3680972)\] \[[Code](https://github.com/yzc-ippl/TMCR)\] 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMM 2024</div><img src='images/MTCL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multi-Level Transitional Contrast Learning for Personalized Image Aesthetics Assessment](https://ieeexplore.ieee.org/abstract/document/10168279)

 **Zhichao Yang**, Leida Li, Yuzhe Yang, Yaqian Li, Weisi Lin

\[[Paper](https://ieeexplore.ieee.org/abstract/document/10168279)\] \[[Code](https://github.com/yzc-ippl/MTCL)\] 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/FGResQ.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fine-grained Image Quality Assessment for Perceptual Image Restoration](https://arxiv.org/pdf/2508.14475)

Xiangfei Sheng†, Xiaofeng Pan†, **Zhichao Yang**, Pengfei Chen, Leida Li

\[[Paper](https://arxiv.org/pdf/2508.14475)\] \[[Project](https://sxfly99.github.io/FGResQ-Homepage/)\] \[[Code](https://github.com/sxfly99/FGResQ)\]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/TuningIQA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TuningIQA: Fine-Grained Blind Image Quality Assessment for Livestreaming Camera Tuning](https://arxiv.org/pdf/2508.17965)

Xiangfei Sheng†, Zhichao Duan†, Xiaofeng Pan, Yipo Huang, **Zhichao Yang**, Pengfei Chen, Leida Li

\[[Paper](https://arxiv.org/pdf/2508.17965)\]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/AesExpert.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AesExpert: Towards Multi-Modality Foundation Model for Image Aesthetics Perception](https://arxiv.org/pdf/2404.09624)

Yipo Huang, Xiangfei Sheng, **Zhichao Yang**, Quan Yuan, Zhichao Duan, Pengfei Chen, Leida Li, Weisi Lin, Guangming Shi

\[[Paper](https://arxiv.org/pdf/2404.09624)\] \[[Project](https://yipoh.github.io/aes-expert/)\] \[[Code](https://github.com/yipoh/AesExpert)\]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2026</div><img src='images/AesBench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AesBench: An Expert Benchmark for Multimodal Large Language Models on Image Aesthetics Perception](https://arxiv.org/abs/2401.08276)

Yipo Huang†, Quan Yuan†, Xiangfei Sheng, **Zhichao Yang**, Haoning Wu, Pengfei Chen, Yuzhe Yang, Leida Li, Weisi Lin

\[[Paper](https://arxiv.org/abs/2401.08276)\] \[[Project](https://aesbench.github.io/)\] \[[Code](https://github.com/yipoh/AesBench)\]

</div>
</div>


# 🎖 Honors and Awards
- *2025.12* 🏅 入选2025年度中国科协青年科技人才培育工程博士生专项计划 !
- *2024.06* 🏆 **Winner Award**, CVPR NTIRE 2024 DXOMARK Portrait Quality Assessment Challenge.
- *2023.12* 🏅 National Scholarship for Master Students, Xidian University.
- *2023.09* 🏆 **Runner-up**, CGI-AIAA 2023: Artistic Image Aesthetics Assessment Challenge.

# 📖 Educations
- *2024.09 - present*, Ph.D. Candidate in Computer Science and Technology, Xidian University.
- *2021.09 - 2024.06*, Master, Computer Science and Technology, Xidian University
- *2017.09 - 2021.06*, Bachelor, Electronic Information Engineering, China University of Mining and Technology.

# 💬 Invited Talks
- *2026.03*, Invited Speaker at the CSIG 21st Student Member Sharing Forum, talk title: "Fine-Grained Image Quality Assessment".

# 💻 Internships
- *2022.10 - 2023.03*, Computer Vision Intern, OPPO Research Institute, Shanghai, China.
