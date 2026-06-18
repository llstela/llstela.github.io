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

<div class="collaboration-banner">
  <div class="collaboration-banner__badge">Open for Collaboration</div>
  <p class="collaboration-banner__lead">At the Institute of Science Tokyo, access to up to <span class="collaboration-banner__highlight">128 NVIDIA H100 GPUs</span> is available for my independent open-ended research.</p>
  <p class="collaboration-banner__text">I am actively seeking close collaborations with both academia and industry. If this aligns with your interests, please feel free to reach out.</p>
</div>

Hi, I'm Xuhan, an incoming Ph.D. student in Computer Science at the [Institute of Science Tokyo](https://www.isct.ac.jp/en/), advised by Prof. [Rio Yokota](https://www.rio.gsic.titech.ac.jp/). I received my Master's degree from the [Visual-Information Intelligent Learning LAB](https://villa.jianzhang.tech/) at [Peking University (PKU)](https://www.pku.edu.cn/), advised by Prof. [Jian ZHANG](https://jianzhang.tech/), and my Bachelor's degree in Artificial Intelligence from [Dalian University of Technology](https://en.dlut.edu.cn/), advised by Prof. [Xu JIA](https://stephenjia.github.io/).

My current research interest is in world models.

I am always open to academic and industry collaborations. Feel free to reach out, and here is my latest [CV](/docs/Xuhan_SHENG_Resume_EN_26.06.01.pdf).


<span class='anchor' id='news'></span>
# 🔥 News
- *2026.10*: 🚀 I will start my Ph.D. in Computer Science at the Institute of Science Tokyo.
- *2026.03*: 🎮 I joined Tencent IEG, Game AI Engine Department, as an intern working on AI image restoration and super-resolution for game content enhancement.
- *2025.09*: 🎉 **Collaboration**: 1 paper accepted in PRCV 2025.
- *2025.08*: 🎉 **Collaboration**: 1 paper accepted in IJCV 2025.
- *2025.06*: 🎉 **Collaboration**: 1 paper accepted in ICME 2025 for <font color=Red>oral presentation</font>.
- *2025.05*: 🎯 I joined OPPO Research Institute as an Imaging Algorithm Engineer Intern in the AI Talent Program.
- *2024.09*: 🎉 **First-author**: 1 paper ("OmniSSR") accepted in ECCV 2024 for <font color=Red>oral presentation</font>.
- *2023.06*: 🏆 **Collaboration**: 1 work won the "NTIRE 2023 Challenge on 360deg Omnidirectional Image Super-Resolution track" championship.


<span class='anchor' id='experience'></span>
# 💼 Experience

<div class="experience-box">
    <div class="experience-box-logo">
        <div class="experience-logo-card">
            <img src="/images/logo/tencent_logo.png" alt="Tencent Logo">
        </div>
    </div>
    <div class="experience-box-text">
        <p class="experience-title"><strong>Tencent IEG</strong>, Game AI Engine Department</p>
        <p class="experience-meta"><strong>2026.03 - Present</strong> · Intern</p>
        <p>Working on <strong>image super-resolution</strong> based on <strong>Qwen-Image</strong> for game content enhancement, and developing <strong>AI-based image restoration</strong> techniques for production-level visual assets.</p>
    </div>
</div>

<div class="experience-box">
    <div class="experience-box-logo experience-box-logo--wide">
        <div class="experience-logo-card">
            <img src="/images/logo/oppo_logo.png" alt="OPPO Logo">
        </div>
    </div>
    <div class="experience-box-text">
        <p class="experience-title"><strong>OPPO Research Institute</strong></p>
        <p class="experience-meta"><strong>2025.05 - 2025.09</strong> · Imaging Algorithm Engineer Intern</p>
        <p>Worked on <strong>vision-language models</strong> for assisting <strong>AI-based image enhancement</strong>. Advisor: Prof. <a href="https://www4.comp.polyu.edu.hk/~cslzhang/">Lei Zhang</a>.</p>
    </div>
</div>


<span class='anchor' id='research-interests'></span>
# 🔬 Research Interests

- Efficient vision encoders with dynamic visual token compression and pruning for real-time VLA models.
- Dual VLA systems that combine high-level reasoning models and low-level execution models for long-horizon tasks and cross-embodiment.
- Diffusion-based super-resolution and restoration for panoramic and omnidirectional images.
- Vision-language models for artifact localization and AI-based image enhancement.


<span class='anchor' id='publications'></span>
# 📑 Publications

(*: indicates equal contribution; #: indicates corresponding author)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='/images/RealOSR.jpg' alt="RealOSR overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**RealOSR: Latent Unfolding Boosts Diffusion-based Real-world Omnidirectional Image Super-Resolution**](https://arxiv.org/abs/2412.09646)

**Xuhan Sheng**\*, Runyi Li\*, Bin Chen, Weiqi Li, Xu Jiang, Jian Zhang\#

Under Review

- A one-step diffusion-based omnidirectional image super-resolution method guided by latent space unfolding, with lightweight domain alignment and degradation-aware modules for real-world restoration.

[**Paper**](https://arxiv.org/abs/2412.09646)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PRCV 2025</div><img src='/images/PBHL_pipeline.png' alt='PBHL pipeline' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

[**Bridging the Point to Boundary Gap for Point-supervised Temporal Action Localization with Single-stage Inference**](https://link.springer.com/chapter/10.1007/978-981-95-5676-2_21)

Junshi Yang, Shenglan Liu, **Xuhan Sheng**, et al.

PRCV 2025

- A hierarchical framework that converts sparse point annotations into boundary-accurate pseudo labels via Gaussian-prior boundary enhancement.

[**Paper**](https://link.springer.com/chapter/10.1007/978-981-95-5676-2_21)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCV 2025</div><img src='/images/omnidrag_teaser.png' alt='OmniDrag teaser' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

[**OmniDrag: Enabling Motion Control for Omnidirectional Image-to-Video Generation**](https://link.springer.com/article/10.1007/s11263-025-02629-7)

Weiqi Li, Shijie Zhao, Chong Mou, **Xuhan Sheng**, et al.

IJCV 2025

- First diffusion-based framework enabling precise drag-style motion control for omnidirectional image-to-video generation.

[**Paper**](https://link.springer.com/article/10.1007/s11263-025-02629-7)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2025 Oral</div><img src='/images/Re-Face.jpg' alt="Re-Face overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Label-guided Facial Retouching Reversion**](https://arxiv.org/abs/2404.14177)

Guanhua Zhao\*, Yu Gu\*, **Xuhan Sheng**, Yujie Hu, Jian Zhang\#

ICME 2025, <font color=Red>Oral Presentation</font>

- A diffusion-based method for reversing facial retouching effects such as skin smoothing, eye enlargement, and face slimming.

[**Paper**](https://arxiv.org/abs/2404.14177)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024 Oral</div><img src='/images/OmniSSR.jpg' alt="OmniSSR overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**OmniSSR: Zero-shot Omnidirectional Image Super-Resolution using Stable Diffusion Model**](https://eccv.ecva.net/virtual/2024/poster/1971)

Runyi Li\*, **Xuhan Sheng**\*, Weiqi Li, Jian Zhang\#

ECCV 2024, <font color=Red>Oral Presentation</font>

- The first zero-shot omnidirectional image super-resolution method leveraging Stable Diffusion priors, integrating tangent information interaction and gradient decomposition without training.

[**Paper**](https://eccv.ecva.net/virtual/2024/poster/1971) **\|** [**Project Page**](https://lirunyi2001.github.io/projects/omnissr/) **\|** [**GitHub**](https://github.com/LiRunyi2001/OmniSSR)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPRW 2023</div><img src='/images/ntire.jpg' alt="NTIRE overview" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[**OPDN: Omnidirectional Position-Aware Deformable Network for Omnidirectional Image Super-Resolution**](https://openaccess.thecvf.com/content/CVPR2023W/NTIRE/html/Sun_OPDN_Omnidirectional_Position-Aware_Deformable_Network_for_Omnidirectional_Image_Super-Resolution_CVPRW_2023_paper.html)

Xiaopeng Sun\*, Weiqi Li\*, Zhenyu Zhang, Qiufang Ma, **Xuhan Sheng**, et al.

CVPR Workshops 2023, NTIRE 2023 360-degree Panoramic SR Challenge Champion

- The champion solution for the NTIRE 2023 Challenge on 360-degree panoramic image super-resolution.

[**Paper**](https://openaccess.thecvf.com/content/CVPR2023W/NTIRE/html/Sun_OPDN_Omnidirectional_Position-Aware_Deformable_Network_for_Omnidirectional_Image_Super-Resolution_CVPRW_2023_paper.html)

</div>
</div>


<span class='anchor' id='educations'></span>
# 🎓 Educations

<div class="experience-box">
    <div class="experience-box-logo">
        <div class="experience-logo-card">
            <img src="/images/logo/science_tokyo_logo.png" alt="Institute of Science Tokyo Logo">
        </div>
    </div>
    <div class="experience-box-text">
        <p class="experience-title"><strong><a href="https://www.isct.ac.jp/en/">Institute of Science Tokyo</a></strong>, Department of Computer Science</p>
        <p class="experience-meta"><strong>2026.10 - Present</strong> · Incoming Ph.D. Student</p>
        <p>Advisor: Prof. <a href="https://www.rio.gsic.titech.ac.jp/">Rio Yokota</a></p>
    </div>
</div>

<div class="experience-box">
    <div class="experience-box-logo">
        <div class="experience-logo-card">
            <img src="/images/logo/pku_logo.png" alt="Peking University Logo">
        </div>
    </div>
    <div class="experience-box-text">
        <p class="experience-title"><strong><a href="https://english.pku.edu.cn/">Peking University</a></strong>, <a href="https://villa.jianzhang.tech/">VILLA Lab</a></p>
        <p class="experience-meta"><strong>2023.09 - 2026.06</strong> · Master Student</p>
        <p>Advisor: Prof. <a href="https://jianzhang.tech/">Jian ZHANG</a>; GPA: 3.87/4.00</p>
    </div>
</div>

<div class="experience-box">
    <div class="experience-box-logo">
        <div class="experience-logo-card">
            <img src="/images/logo/dut_logo.png" alt="DUT Logo">
        </div>
    </div>
    <div class="experience-box-text">
        <p class="experience-title"><strong><a href="https://en.dlut.edu.cn/">Dalian University of Technology</a></strong></p>
        <p class="experience-meta"><strong>2019.09 - 2023.06</strong> · Bachelor Student</p>
        <p>Advisor: Prof. <a href="https://stephenjia.github.io/">Xu JIA</a>; GPA: 4.17/5.00</p>
    </div>
</div>


<span class='anchor' id='awards'></span>
# 🏅 Honors and Awards

- *2024*, Peking University Academic Excellence Award.
- *2023*, Dalian University of Technology University-level Outstanding Graduate.
- *2022*, Dalian University of Technology First-class Academic Excellence Scholarship.
- *2021*, Dalian University of Technology Second-class Academic Excellence Scholarship.
- *2020*, Dalian University of Technology First-class Academic Excellence Scholarship.


<span class='anchor' id='hobbies'></span>
# 😊 Hobbies

<p style="margin: 0.2rem 0 0.8rem; font-size: 0.9rem; opacity: 0.8;"><em>Click image to zoom.</em></p>

I love playing flutes (Irish flute, Boehm flute, Shakuhachi). I love Hatsune Miku. I am learning Cantonese.

<div class="hobbies-gallery">
    <figure>
        <a href="/images/hobbies/kyuudou.jpg" aria-label="Open Kyudo image">
        <img src="/images/hobbies/kyuudou.jpg" alt="Kyudo beginner certificate" loading="lazy" decoding="async">
        </a>
        <figcaption>Kyudo beginner certificate</figcaption>
    </figure>
    <figure>
        <a href="/images/hobbies/miku.jpg" aria-label="Open Hatsune Miku image">
        <img src="/images/hobbies/miku.jpg" alt="Hatsune Miku" loading="lazy" decoding="async">
        </a>
        <figcaption>39 for supporting Miku!</figcaption>
    </figure>
    <figure>
        <a href="/images/hobbies/piccolo.jpg" aria-label="Open Piccolo image">
        <img src="/images/hobbies/piccolo.jpg" alt="Piccolo" loading="lazy" decoding="async">
        </a>
        <figcaption>Piccolo</figcaption>
    </figure>
    <figure>
        <a href="/images/hobbies/YFL-411.jpg" aria-label="Open Yamaha YFL-411 image">
        <img src="/images/hobbies/YFL-411.jpg" alt="YFL-411" loading="lazy" decoding="async">
        </a>
        <figcaption>Yamaha YFL-411</figcaption>
    </figure>
</div>
