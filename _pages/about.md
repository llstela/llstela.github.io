---
permalink: /
author_profile: true
stylesheets:
  - /assets/css/home.css
redirect_from:
  - /about/
  - /about.html
---

<h1 class="main-heading">Xuhan SHENG</h1>

Hi, I am Xuhan Sheng, an incoming Ph.D. student in Computer Science at the
[Institute of Science Tokyo](https://www.isct.ac.jp/en), advised by Prof.
[Rio Yokota](https://www.rio.gsic.titech.ac.jp/). I received my master's
degree from [Peking University](https://english.pku.edu.cn/), where I worked
with Prof. [Jian Zhang](https://jianzhang.tech/) at
[VILLA Lab](https://villa.jianzhang.tech/), and my bachelor's degree in
Artificial Intelligence from [Dalian University of Technology](https://en.dlut.edu.cn/),
advised by Prof. [Xu Jia](https://stephenjia.github.io/).

My research focuses on low-level vision, diffusion-based image restoration,
vision-language models for image enhancement, and efficient vision encoders for
real-time visual agents. I am always open to academic and industry
collaboration. Here is my latest [CV](/docs/Xuhan_SHENG_Resume_EN_26.06.01.pdf).

News
---------------
<span id="news"></span>
<div class="news-box">
  <ul class="news-list">
    <li><span class="news-date"><em>2026.10</em></span> Starting my Ph.D. in Computer Science at Institute of Science Tokyo.</li>
    <li><span class="news-date"><em>2026.03</em></span> Joined Tencent IEG, Game AI Engine Department, as an intern on AI image restoration and super-resolution.</li>
    <li><span class="news-date"><em>2025.09</em></span> One collaborative paper accepted by PRCV 2025.</li>
    <li><span class="news-date"><em>2025.08</em></span> One collaborative paper accepted by IJCV 2025.</li>
    <li><span class="news-date"><em>2025.06</em></span> One collaborative paper accepted by ICME 2025 as an oral presentation.</li>
    <li><span class="news-date"><em>2025.05</em></span> Joined OPPO Research Institute as an Imaging Algorithm Engineer Intern.</li>
    <li><span class="news-date"><em>2024.09</em></span> OmniSSR accepted by ECCV 2024 as an oral presentation.</li>
    <li><span class="news-date"><em>2023.06</em></span> OPDN won the NTIRE 2023 360-degree Omnidirectional Image Super-Resolution Challenge.</li>
  </ul>
</div>

Education
--------------
<span id="education"></span>
<div class="experience-container">
  <div class="experience-card">
    <div class="experience-info">
      <strong>Institute of Science Tokyo, Department of Computer Science</strong><br>
      <em>2026.10 - Present</em><br>
      Incoming Ph.D. student advised by <a href="https://www.rio.gsic.titech.ac.jp/"><em>Prof. Rio Yokota</em></a>.<br>
      <span style="color:#888;">Research direction: efficient vision encoders, real-time visual agents, and VLA systems.</span>
    </div>
  </div>

  <div class="experience-card">
    <img src="images/logo/pku_logo.png" alt="Peking University logo" class="experience-logo">
    <div class="experience-info">
      <strong>Peking University, School of Electronic and Computer Engineering</strong><br>
      <em>2023.09 - 2026.06</em><br>
      Master's degree in Computer Application Technology, GPA 3.87/4.00.<br>
      <span style="color:#888;">Advisor: <a href="https://jianzhang.tech/"><em>Prof. Jian Zhang</em></a>, VILLA Lab.</span>
    </div>
  </div>

  <div class="experience-card">
    <img src="images/logo/dut_logo.png" alt="Dalian University of Technology logo" class="experience-logo">
    <div class="experience-info">
      <strong>Dalian University of Technology, School of Artificial Intelligence</strong><br>
      <em>2019.09 - 2023.06</em><br>
      Bachelor's degree in Artificial Intelligence, GPA 4.17/5.00.<br>
      <span style="color:#888;">Advisor: <a href="https://stephenjia.github.io/"><em>Prof. Xu Jia</em></a>, IIAU-LAB.</span>
    </div>
  </div>
</div>

Experience
--------------
<span id="experience"></span>
<div class="experience-container">
  <div class="experience-card">
    <div class="experience-info">
      <strong>Tencent IEG, Game AI Engine Department</strong><br>
      <em>2026.03 - Present</em><br>
      Game AI intern working on image super-resolution based on Qwen-Image for game content enhancement.<br>
      <span style="color:#888;">Developed and optimized AI image restoration techniques for production-level visual assets, with related techniques deployed in real business scenarios.</span>
    </div>
  </div>

  <div class="experience-card">
    <div class="experience-info">
      <strong>OPPO Research Institute</strong><br>
      <em>2025.05 - 2025.09</em><br>
      Imaging Algorithm Engineer Intern, AI Talent Program: Class of 2026 Dream-Seeking Internship.<br>
      <span style="color:#888;">Worked on vision-language models for assisting AI-based image enhancement. Advisor: Prof. Lei Zhang.</span>
    </div>
  </div>
</div>

Publications
--------------
<span id="publications"></span>
<button class="pub-button active" onclick="filterPublications(event, 'all')">Selected Publications</button>
<button class="pub-button" onclick="filterPublications(event, 'list')">Full Publications List</button>

(* denotes equal contribution; # denotes corresponding author)

<div id="core-publications" class="publication-view" data-publication-view="core">
  <div class="publication-card" data-category="all">
    <div style="display: flex; align-items: center;">
      <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;">
        <img src="images/RealOSR.jpg" alt="RealOSR overview" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;">
      </div>
      <div>
        <strong>RealOSR: Latent Unfolding Boosts Diffusion-based Real-world Omnidirectional Image Super-Resolution</strong><br>
        <i style="font-size: 13px;"><strong>Xuhan Sheng</strong>, Runyi Li, Bin Chen, Weiqi Li, Xu Jiang, Jian Zhang.</i><br>
        One-step diffusion-based omnidirectional image super-resolution guided by latent space unfolding, with lightweight domain alignment and degradation-aware modules for real-world restoration.
        <br>
        <b><i style="color:#83a1c7;">Under Review &nbsp;</i></b>
        <a href="https://arxiv.org/abs/2412.09646"><em>[Paper]</em></a>
      </div>
    </div>
  </div>

  <div class="publication-card" data-category="all">
    <div style="display: flex; align-items: center;">
      <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;">
        <img src="images/OmniSSR.jpg" alt="OmniSSR overview" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;">
      </div>
      <div>
        <strong>OmniSSR: Zero-shot Omnidirectional Image Super-Resolution using Stable Diffusion Model</strong><br>
        <i style="font-size: 13px;">Runyi Li*, <strong>Xuhan Sheng*</strong>, Weiqi Li, Jian Zhang#.</i><br>
        First zero-shot omnidirectional image super-resolution method leveraging Stable Diffusion priors, with tangent information interaction and gradient decomposition.
        <br>
        <b><i style="color:#83a1c7;">ECCV 2024 Oral &nbsp;</i></b>
        <a href="https://eccv.ecva.net/virtual/2024/poster/1971"><em>[Paper]</em></a>
        <a href="https://lirunyi2001.github.io/projects/omnissr/"><em>[Project]</em></a>
        <a href="https://github.com/LiRunyi2001/OmniSSR"><em>[Code]</em></a>
      </div>
    </div>
  </div>

  <div class="publication-card" data-category="all">
    <div style="display: flex; align-items: center;">
      <div class="pub-media-rotator" data-interval="4000" style="position: relative; width: 320px; height: 180px; margin-right: 20px; border-radius: 8px; overflow: hidden; flex: 0 0 auto;">
        <img src="images/omnidrag_teaser.png" alt="OmniDrag teaser" style="width: 320px; height: 180px; object-fit: contain; display: block; margin: 0 auto;">
      </div>
      <div>
        <strong>OmniDrag: Enabling Motion Control for Omnidirectional Image-to-Video Generation</strong><br>
        <i style="font-size: 13px;">Weiqi Li, Shijie Zhao, Chong Mou, <strong>Xuhan Sheng</strong>, et al.</i><br>
        A diffusion-based framework enabling precise drag-style motion control for omnidirectional image-to-video generation.
        <br>
        <b><i style="color:#83a1c7;">IJCV 2025 &nbsp;</i></b>
        <a href="https://link.springer.com/article/10.1007/s11263-025-02629-7"><em>[Paper]</em></a>
      </div>
    </div>
  </div>
</div>

<div id="full-publications" class="publication-view" data-publication-view="list" hidden>
  <ul class="full-publication-list">
    <li>
      <span class="pub-list-badge">Under Review</span>
      <span class="pub-list-title">RealOSR: Latent Unfolding Boosts Diffusion-based Real-world Omnidirectional Image Super-Resolution</span><br>
      <span class="pub-list-authors"><strong>Xuhan Sheng</strong>, Runyi Li, Bin Chen, Weiqi Li, Xu Jiang, Jian Zhang.</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2412.09646">[Paper]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">ECCV 2024 Oral</span>
      <span class="pub-list-title">OmniSSR: Zero-shot Omnidirectional Image Super-Resolution using Stable Diffusion Model</span><br>
      <span class="pub-list-authors">Runyi Li*, <strong>Xuhan Sheng*</strong>, Weiqi Li, Jian Zhang#.</span>
      <span class="pub-list-links"><a href="https://eccv.ecva.net/virtual/2024/poster/1971">[Paper]</a><a href="https://lirunyi2001.github.io/projects/omnissr/">[Project]</a><a href="https://github.com/LiRunyi2001/OmniSSR">[Code]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">IJCV 2025</span>
      <span class="pub-list-title">OmniDrag: Enabling Motion Control for Omnidirectional Image-to-Video Generation</span><br>
      <span class="pub-list-authors">Weiqi Li, Shijie Zhao, Chong Mou, <strong>Xuhan Sheng</strong>, et al.</span>
      <span class="pub-list-links"><a href="https://link.springer.com/article/10.1007/s11263-025-02629-7">[Paper]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">PRCV 2025</span>
      <span class="pub-list-title">Bridging the Point to Boundary Gap for Point-supervised Temporal Action Localization with Single-stage Inference</span><br>
      <span class="pub-list-authors">Junshi Yang, Shenglan Liu, <strong>Xuhan Sheng</strong>, et al.</span>
      <span class="pub-list-links"><a href="https://link.springer.com/chapter/10.1007/978-981-95-5676-2_21">[Paper]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">ICME 2025 Oral</span>
      <span class="pub-list-title">Label-guided Facial Retouching Reversion</span><br>
      <span class="pub-list-authors">Guanhua Zhao*, Yu Gu*, <strong>Xuhan Sheng</strong>, Yujie Hu, Jian Zhang#.</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2404.14177">[Paper]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">CVPRW 2023</span>
      <span class="pub-list-title">OPDN: Omnidirectional Position-Aware Deformable Network for Omnidirectional Image Super-Resolution</span><br>
      <span class="pub-list-authors">Xiaopeng Sun*, Weiqi Li*, Zhenyu Zhang, Qiufang Ma, <strong>Xuhan Sheng</strong>, et al.</span>
      <span class="pub-list-note">NTIRE 2023 Challenge Champion.</span>
      <span class="pub-list-links"><a href="https://openaccess.thecvf.com/content/CVPR2023W/NTIRE/html/Sun_OPDN_Omnidirectional_Position-Aware_Deformable_Network_for_Omnidirectional_Image_Super-Resolution_CVPRW_2023_paper.html">[Paper]</a></span>
    </li>
  </ul>
</div>

<script src="assets/js/show_publications.js"></script>
<script src="assets/js/pub_media_rotator.js"></script>

Research Interests
--------
<span id="research"></span>
- Efficient vision encoders with dynamic visual token compression and pruning for real-time VLA models.
- Dual VLA systems that combine high-level reasoning models and low-level execution models for long-horizon and cross-embodiment tasks.
- Diffusion-based super-resolution and restoration for panoramic and omnidirectional images.
- Vision-language models for localizing artifacts and assisting AI-based image enhancement.

Honors and Awards
--------
<span id="awards"></span>
- *2024*, Peking University Academic Excellence Award.
- *2023*, Dalian University of Technology University-level Outstanding Graduate.
- *2022*, Dalian University of Technology First-class Academic Excellence Scholarship.
- *2021*, Dalian University of Technology Second-class Academic Excellence Scholarship.
- *2020*, Dalian University of Technology First-class Academic Excellence Scholarship.

Hobbies
--------
I love playing flutes, including Irish flute, Boehm flute, and Shakuhachi. I also enjoy Hatsune Miku and learning Cantonese.

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
    <figcaption>Hatsune Miku</figcaption>
  </figure>
  <figure>
    <a href="/images/hobbies/piccolo.jpg" aria-label="Open piccolo image">
      <img src="/images/hobbies/piccolo.jpg" alt="Piccolo" loading="lazy" decoding="async">
    </a>
    <figcaption>Piccolo</figcaption>
  </figure>
  <figure>
    <a href="/images/hobbies/YFL-411.jpg" aria-label="Open Yamaha YFL-411 image">
      <img src="/images/hobbies/YFL-411.jpg" alt="Yamaha YFL-411" loading="lazy" decoding="async">
    </a>
    <figcaption>Yamaha YFL-411</figcaption>
  </figure>
</div>
