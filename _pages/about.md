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

Hi, I'm Xuhan, a third-year Master's student at the [Visual-Information Intelligent Learning LAB](https://villa.jianzhang.tech/) at [Peking University (PKU)](https://www.pku.edu.cn/), where I am fortunate to be advised by Prof. [Jian ZHANG](https://jianzhang.tech/). **I am expected to graduate in June 2026.**

Previously, I earned my Bachelor's degree in Artificial Intelligence from the [Dalian University of Technology](https://en.dlut.edu.cn/), under the supervision of Prof. [Xu JIA](https://stephenjia.github.io/). My research interests include Low-level Vision, AIGC, and 3D Vision.

I am always open to academic and industry collaborations. Feel free to reach out for research discussions or potential partnerships! 

**Currently seeking Ph.D. (2026 Fall / 2027 Spring) or job opportunities(2026 June).** Here is my [CV](/docs/Xuhan_SHENG_Resume_EN_26.02.05.pdf). 


<!-- I am always open to academic and industrial collaborations. My specific research interests include: -->

<!-- - **Development of foundational video generation models** (autoregressive models, causal inference, and efficient architectures)
- **Video generation models as world simulators** (generalization, physics-compliance, memory consistency, and causal reasoning)
- **Multi-agent embodied AI** -->

<!-- - **Development of foundational video generation models** (autoregressive models, causal inference, and efficient architectures)
- **Video generation models as world simulators** (generalization, physics-compliance, memory consistency, and causal reasoning)
- **Multi-agent embodied AI** -->


# 🔥 News
- *2025.09*: &nbsp;🎉 **Collaboration**: 1 paper accepted in PRCV 2025.
- *2025.08*: &nbsp;🎉 **Collaboration**: 1 paper accepted in IJCV 2025.
- *2025.06*: &nbsp;🎉 **Collaboration**: 1 paper accepted in ICME 2025 for <font color=Red>oral presentation</font>.
- *2024.09*: &nbsp;🎉 **First-author**: 1 paper ("OmniSSR") accepted in ECCV 2024 for <font color=Red>oral presentation</font>.
- *2023.06*: &nbsp;🏆 **Collaboration**: 1 work won the "NTIRE 2023 Challenge on 360deg Omnidirectional Image Super-Resolution track" championship.


# 📝 Publications 

(*: indicates equal contribution; #: indicates corresponding author)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='/images/RealOSR.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RealOSR: Latent Unfolding Boosting Diffusion-based Real-world Omnidirectional Image Super-Resolution](https://arxiv.org/abs/2412.09646)

**Xuhan Sheng**\*, Runyi Li\*, Bin Chen, Weiqi Li, Xu Jiang, Jian Zhang\#

Preprint 2025, Under Review

- A **one-step** denoising diffusion model with **latent unfolding** in the latent space for real-world 360° image super-resolution, achieving ×200 acceleration.

[**Paper**](https://arxiv.org/abs/2412.09646)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2025</div><img src='/images/Re-Face.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[Label-guided Facial Retouching Reversion](https://arxiv.org/abs/2404.14177)

Guanhua Zhao\*, Yu Gu\*, **Xuhan Sheng**, Yujie Hu, Jian Zhang\#

ICME 2025, <font color=Red>Oral Presentation</font>

- Proposed a facial retouching reversion algorithm capable of removing beautification effects such as "skin smoothing," "eye enlargement," and "face slimming."

[**Paper**](https://arxiv.org/abs/2404.14177)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCV 2025</div><img src='/images/logo/pku_logo.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

**OmniDrag: Enabling Motion Control for Omnidirectional Image-to-Video Generation**

Weiqi Li, Shijie Zhao, Chong Mou, **Xuhan Sheng**, et al.

IJCV 2025

- First diffusion-based framework enabling precise drag-style motion control for omnidirectional image-to-video generation.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PRCV 2025</div><img src='/images/logo/pku_logo.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

**Bridging the Point to Boundary Gap for Point-supervised Temporal Action Localization with Single-stage Inference**

Junshi Yang, Shenglan Liu, **Xuhan Sheng**, et al.

PRCV 2025

- A hierarchical framework that converts sparse point annotations into boundary-accurate pseudo labels via Gaussian-prior boundary enhancement.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='/images/OmniSSR.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[OmniSSR: Zero-shot Omnidirectional Image Super-Resolution using Stable Diffusion Model](https://eccv.ecva.net/virtual/2024/poster/1971)

Runyi Li\*, **Xuhan Sheng**\*, Weiqi Li, Jian Zhang\#

ECCV 2024, <font color=Red>Oral Presentation</font>

-  A **zero-shot** framework that uses existing planar image diffusion super-resolution models (e.g., StableSR) for 360° image SR.

[**Paper**](https://eccv.ecva.net/virtual/2024/poster/1971) **\|** [**Project Page**](https://lirunyi2001.github.io/projects/omnissr/) **\|** [**GitHub**](https://github.com/LiRunyi2001/OmniSSR)

<!-- - <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=F15mLDYAAAAJ&citation_for_view=F15mLDYAAAAJ:u5HHmVD_uO8C">
<img src="https://img.shields.io/badge/Citations-15-blue" alt="引用数"></a> -->
<!-- - <a href="https://github.com/theEricMa/TriplaneTurbo"><img src="https://img.shields.io/github/stars/theEricMa/TriplaneTurbo?style=social" alt="GitHub stars"></a> \| [HuggingFace Demo](https://huggingface.co/spaces/ZhiyuanthePony/TriplaneTurbo) -->

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NTIRE 2023</div><img src='/images/ntire.jpg' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">


[OPDN: Omnidirectional Position-aware Deformable Network for Omnidirectional Image Super-Resolution](https://openaccess.thecvf.com/content/CVPR2023W/NTIRE/html/Sun_OPDN_Omnidirectional_Position-Aware_Deformable_Network_for_Omnidirectional_Image_Super-Resolution_CVPRW_2023_paper.html)

Xiaopeng Sun \*, Weiqi Li\*, Zhenyu Zhang, Qiufang Ma, **Xuhan Sheng**, et al.

CVPR Workshops 2023

- The 🏆 **champion** solution for "NTIRE 2023 Challenge on 360deg Omnidirectional Image Super-Resolution track".

[**Paper**](https://openaccess.thecvf.com/content/CVPR2023W/NTIRE/html/Sun_OPDN_Omnidirectional_Position-Aware_Deformable_Network_for_Omnidirectional_Image_Super-Resolution_CVPRW_2023_paper.html)
</div>
</div>

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<span class='anchor' id='educations'></span>
# 📚 Educations

<div class="experience-box">
    <div class="experience-box-logo">
        <img src="/images/logo/pku_logo.png" alt="Peking University Logo" width="80" height="80">
    </div>
    <div class="experience-box-text">
        <p><strong>2023.09 - Now</strong></p>
        <p>Master Student, <a href="https://english.pku.edu.cn/">Peking University</a>, <a href="https://villa.jianzhang.tech/">VILLA Lab</a></p>
        <p>Advisor: Prof. <a href="https://jianzhang.tech/">Jian ZHANG</a></p>
    </div>
</div>

<div class="experience-box">
    <div class="experience-box-logo">
        <img src="/images/logo/dut_logo.png" alt="DUT Logo" width="80" height="80">
    </div>
    <div class="experience-box-text">
        <p><strong>2019.09 - 2023.09</strong></p>
        <p>Bachelor Student, <a href="https://en.dlut.edu.cn/">Dalian University of Technology</a> </p>
        <p>Advisor: Prof. <a href="https://stephenjia.github.io/">Xu JIA</a></p>
    </div>
</div>


<span class='anchor' id='hobbies'></span>
# 😊 Hobbies

<p style="margin: 0.2rem 0 0.8rem; font-size: 0.9rem; opacity: 0.8;"><em>Click image to zoom.</em></p>

I love playing flutes (Irish flute, Boehm flute, Shakuhachi). I love Hatsune Miku. I am learning Cantonese.
<!-- 插入图片 -->
<div class="hobbies-gallery">
    <figure>
        <a href="/images/hobbies/kyuudou.jpg" aria-label="Open Kyūdō image">
        <img src="/images/hobbies/kyuudou.jpg" alt="Kyūdō" loading="lazy" decoding="async">
        </a>
        <figcaption>Kyūdō beginner certificate</figcaption>
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

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->