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

Hi, I'm Xuhan, a second-year master degree student in the [Visual-Information Intelligent Learning LAB](https://villa.jianzhang.tech/) at [Peking University (PKU)](https://www.pku.edu.cn/), supervised by Prof. [Jian ZHANG](https://jianzhang.tech/). 

Prior to this, I received my Bachelor's degree in Artificial Intelligence (AI) at [Dalian University of Technology](https://en.dlut.edu.cn/), supervised by Prof. [Xu JIA](https://stephenjia.github.io/) My research interests cover Low-level Vision, AIGC, 3D Vision.

<!-- I am always open to academic and industrial collaborations. My specific research interests include: -->

<!-- - **Development of foundational video generation models** (autoregressive models, causal inference, and efficient architectures)
- **Video generation models as world simulators** (generalization, physics-compliance, memory consistency, and causal reasoning)
- **Multi-agent embodied AI** -->

<!-- - **Development of foundational video generation models** (autoregressive models, causal inference, and efficient architectures)
- **Video generation models as world simulators** (generalization, physics-compliance, memory consistency, and causal reasoning)
- **Multi-agent embodied AI** -->

I am always open to academic and industrial collaborations. Feel free to reach out for research discussions and potential collaborations!

**Looking for a PhD or job position.**

# 🔥 News
- *2024.08*: &nbsp;🎉 One paper is accepted in ICME 2025. 🎉
- *2024.08*: &nbsp;🎉 Our "OmniSSR" is accepted in ECCV 2024 for <font color=Red>oral presentation</font>. 🎉
- *2022.02*: &nbsp;🏆 We won the "NTIRE 2023 Challenge on 360deg Omnidirectional Image Super-Resolution track" championship. 🏆


# 📝 Publications 

(*: indicates equal contribution; #: indicates corresponding author)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='/images/RealOSR.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RealOSR: Latent Unfolding Boosting Diffusion-based Real-world Omnidirectional Image Super-Resolution](https://arxiv.org/abs/2412.09646)

**Xuhan Sheng**\*, Runyi Li\*, Bin Chen, Weiqi Li, Xu Jiang, Jian Zhang\#

Preprint 2025

- A **one-step** denoising diffusion model with **latent unfolding** in the latent space for real-world 360° image super-resolution, achieving ×200 acceleration.

[**Paper**](https://arxiv.org/abs/2412.09646)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2025</div><img src='/images/Re-Face.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[Label-guided Facial Retouching Reversion](https://arxiv.org/abs/2404.14177)

Guanhua Zhao\*, Yu Gu\*, **Xuhan Sheng**, Yujie Hu, Jian Zhang\#

ICME 2025

- Proposed a facial retouching reversion algorithm capable of removing beautification effects such as "skin smoothing," "eye enlargement," and "face slimming."

[**Paper**](https://arxiv.org/abs/2404.14177)
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

- The **champion** solution for "NTIRE 2023 Challenge on 360deg Omnidirectional Image Super-Resolution track".

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

<!-- # 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2019.09 - 2023.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->