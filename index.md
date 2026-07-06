---
layout: default
title: Yui Tatsumi / 巽 優衣
---

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  line-height: 1.7;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
  color: #24292f;
  background: #ffffff;
}
.page-content {
  max-width: 1200px;
  margin: 40px auto;
  padding: 0 20px 0 150px;
}

.side-nav {
  position: fixed;
  left: 35px;
  top: 140px;
  width: 150px;
  display: flex;
  flex-direction: column;
  gap: 10px;
  font-size: 0.95rem;
}

.side-nav a {
  color: #57606a;
  text-decoration: none;
  padding: 4px 0 4px 10px;
  border-left: 2px solid transparent;
}

.side-nav a:hover {
  color: #0969da;
  border-left-color: #0969da;
}

.section-heading {
  scroll-margin-top: 32px;
  margin-top: 72px;
  margin-bottom: 28px;
  padding-bottom: 10px;
  border-bottom: 3px solid #d0d7de;
  font-size: 1.8rem;
  letter-spacing: 0.02em;
}

.profile {
  display: flex;
  align-items: flex-start;
  gap: 24px;
  margin: 24px 0 36px;
}

.profile img {
  width: 150px;
  height: 150px;
  object-fit: cover;
  border-radius: 50%;
  flex-shrink: 0;
}

.profile-content {
  flex: 1;
}

.profile-content h1 {
  margin-top: 0;
}

.timeline {
  margin: 20px 0 48px;
}

.timeline-item {
  display: grid;
  grid-template-columns: 180px 90px 1fr;
  column-gap: 28px;
  align-items: start;
  margin: 32px 0 48px;
}

.timeline-date {
  font-size: 1.05rem;
  color: #111;
  white-space: nowrap;
  padding-top: 6px;
}

.timeline-logo {
  display: flex;
  justify-content: center;
  padding-top: 4px;
}

.timeline-logo img {
  width: 58px;
  height: 58px;
  object-fit: contain;
}

.timeline-logo .logo-placeholder {
  width: 58px;
  height: 58px;
  border-radius: 12px;
  background: #f6f8fa;
  border: 1px solid #d0d7de;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: 700;
  color: #57606a;
  font-size: 0.85rem;
}

.timeline-content h3 {
  margin: 0 0 6px;
  font-size: 1.25rem;
}

.timeline-content p {
  margin: 6px 0;
}

.timeline-content ul {
  margin-top: 8px;
}

blockquote {
  border-left: 4px solid #d0d7de;
  background: #f6f8fa;
  padding: 1em 1.2em;
  margin: 1.2em 0;
  border-radius: 8px;
}

blockquote p {
  margin: 0.4em 0;
}

h1, h2, h3 {
  line-height: 1.3;
}

hr {
  border: 0;
  border-top: 1px solid #d0d7de;
  margin: 1.5em 0;
}

@media (max-width: 1000px) {
  .side-nav {
    display: none;
  }

  .page-content {
    max-width: 100%;
    margin: 32px auto;
    padding: 0 20px;
  }
}

@media (max-width: 750px) {
  .timeline-item {
    grid-template-columns: 1fr;
    row-gap: 10px;
  }

  .timeline-date {
    font-weight: 700;
  }

  .timeline-logo {
    justify-content: flex-start;
  }
}

@media (max-width: 700px) {
  .profile {
    flex-direction: column;
  }

  .profile img {
    width: 100px;
    height: 100px;
  }
}
</style>

<nav class="side-nav">
  <a href="#profile">Profile</a>
  <a href="#publications">Publications</a>
  <a href="#education">Education</a>
  <a href="#experience">Research Experience</a>
  <a href="#awards">Awards</a>
  <a href="#funding">Funding</a>
  <a href="#skills">Skills</a>
  <a href="#hobbies">Hobbies</a>
  <a href="#contact">Contact</a>
</nav>

En/[Ja](index_ja.html)

<div id="profile" class="profile">
  <img src="assets/profile.png" alt="Yui Tatsumi">

  <div class="profile-content">
    <h1>Yui Tatsumi</h1>

    <p>
      <a href="https://github.com/qwert-top"><strong>Github</strong></a>　/　
      <a href="http://linkedin.com/in/qwert-top"><strong>Linkedin</strong></a>　/　
      <a href="https://scholar.google.com/citations?user=u1nK1wgAAAAJ"><strong>Google Scholar</strong></a>
    </p>

    <p><strong>Hi! I’m Yui Tatsumi, a Master’s student in Computer Science at Waseda University, Japan.</strong></p>

    <p>
      My research interests include Artificial Intelligence, Computer Vision, and Signal Processing.
      Under the supervision of Professor Hiroshi Watanabe, my reseach primarily focuses on
      Neural Network-based Image Compression for Humans and Machines.
    </p>

    <p>
      Upon graduating from my undergraduate program, I received a departmental award for ranking in the top 5% of my department based on academic performance and research achievements.
    </p>

    <p>
      After completing my master’s program in Spring 2027, I plan to pursue a research position in industry.
    </p>
  </div>
</div>

<h2 id="publications" class="section-heading">📚PUBLICATIONS</h2>

## Preprints

1. Ziyue Zeng, Xun Su, Haoyuan Liu, Bingyu Lu, <u>Yui Tatsumi</u>, Hiroshi Watanabe, “**GVCC: Zero-Shot Video Compression via Codebook-Driven Stochastic Rectified Flow,**” 2026.
[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.26571)
2. <u>Yui Tatsumi</u>, Hiroshi Watanabe, “**Training-Free Continuous Bitrate Control for Scalable Image Coding for Humans and Machines,**” 2026.
[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.00158)

## Peer-Reviewed Journal Papers

1. Takahiro Shindo, Taiju Watanabe, <u>Yui Tatsumi</u>, Hiroshi Watanabe, “**Image Coding for Object Recognition Tasks Based on Contour Feature Learning with Flexible Object Selection,**” **IEEE Access**, 2025.
[![Generic badge](https://img.shields.io/badge/IEEE_Xplore-00629B.svg)](https://ieeexplore.ieee.org/abstract/document/11029205)

## International Conference

1. Ziyue Zeng, <u>Yui Tatsumi</u>, Hiroshi Watanabe, “**Flow Residual Segmentation and Generative Reconstruction for Motion-Aware Video Coding,**” The 9th IIEEJ International Conference on Image Electronics and Visual Computing (**IEVC**), 2026.
[![Generic badge](https://img.shields.io/badge/IEEE_Xplore-00629B.svg)](https://ieeexplore.ieee.org/document/11508206)
2. <u>Yui Tatsumi</u>, Ziyue Zeng, Hiroshi Watanabe, “**Training-Free Adaptive Quantization for Variable Rate Image Coding for Machines,**” IEEE 44th International Conference on Consumer Electronics (**ICCE**), 2026.
[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2511.05836)
  [![Generic badge](https://img.shields.io/badge/Code-grey)](https://github.com/qwert-top/AQVR-ICM)
3. Taiju Watanabe, Takahiro Shindo, <u>Yui Tatsumi</u>, Hiroshi Watanabe, “**VFI-LoRA: Leveraging Video Diffusion Models for Video Interpolation Through LoRA Finetuning,**” IEEE International Conference on Internet of Things and Intelligence System (**IoTaIS**), 2025.
[![Generic badge](https://img.shields.io/badge/IEEE_Xplore-00629B.svg)](https://ieeexplore.ieee.org/document/11282119)
4. <u>Yui Tatsumi</u>, Ziyue Zeng, Hiroshi Watanabe, “**Seed Selection for Human-Oriented Image Reconstruction via Guided Diffusion,**” IEEE 14th Global Conference on Consumer Electronics (**GCCE**), 2025.
 [![Generic badge](https://img.shields.io/badge/IEEE_Xplore-00629B.svg)](https://ieeexplore.ieee.org/document/11274920)
[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.05363)
5. Ziyue Zeng, <u>Yui Tatsumi</u>, Hiroshi Watanabe, “**Bidirectional Attention-Gated Motion Injection for Frame Interpolation,**” IEEE 14th Global Conference on Consumer Electronics (**GCCE**), 2025.
[![Generic badge](https://img.shields.io/badge/IEEE_Xplore-00629B.svg)](https://ieeexplore.ieee.org/document/11275014)
6. <u>Yui Tatsumi</u>, Ziyue Zeng, Hiroshi Watanabe, “**Explicit Residual-Based Scalable Image Coding for Humans and Machines,**” IEEE 27th International Workshop on Multimedia Signal Processing (**MMSP**), 2025.
[![Generic badge](https://img.shields.io/badge/IEEE_Xplore-00629B.svg)](https://ieeexplore.ieee.org/document/11324339)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.19297)
7. Takahiro Shindo, <u>Yui Tatsumi</u>, Taiju Watanabe, Hiroshi Watanabe, “**Guided Diffusion for the Extension of Machine Vision to Human Visual Perception,**” IEEE 27th International Workshop on Multimedia Signal Processing (**MMSP**), 2025.
[![Generic badge](https://img.shields.io/badge/IEEE_Xplore-00629B.svg)](https://ieeexplore.ieee.org/document/11324163)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.17907)
8. Takahiro Shindo, Taiju Watanabe, <u>Yui Tatsumi</u>, Hiroshi Watanabe, “**Delta-ICM: Entropy Modeling with Delta Function for Learned Image Compression,**” IEEE 43rd International Conference on Consumer Electronics (**ICCE**), 2025.
[![Generic badge](https://img.shields.io/badge/IEEE_Xplore-00629B.svg)](https://ieeexplore.ieee.org/document/10929842)
[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.07669)
9. <u>Yui Tatsumi</u>, Shoko Tanaka, Shunsuke Akamatsu, Takahiro Shindo, Hiroshi Watanabe, “**Classification in Japanese Sign Language Based on Dynamic Facial Expressions,**” IEEE 13th Global Conference on Consumer Electronics (**GCCE**), 2024.
[![Generic badge](https://img.shields.io/badge/IEEE_Xplore-00629B.svg)](https://ieeexplore.ieee.org/document/10760997)
[![Generic badge](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.06347)
10. Shoko Tanaka, <u>Yui Tatsumi</u>, Takahiro Shindo, Hiroshi Watanabe, “**Integrating QR Code Characteristics Into Super-Resolution Method,**” IEEE 13th Global Conference on Consumer Electronics (**GCCE**), 2024.
[![Generic badge](https://img.shields.io/badge/IEEE_Xplore-00629B.svg)](https://ieeexplore.ieee.org/document/10760486)
11. Takahiro Shindo, <u>Yui Tatsumi</u>, Taiju Watanabe, Hiroshi Watanabe, “**Refining Coded Image in Human Vision Layer Using CNN-Based Post-Processing,**” IEEE 13th Global Conference on Consumer Electronics (**GCCE**), 2024.
[![Generic badge](https://img.shields.io/badge/IEEE_Xplore-00629B.svg)](https://ieeexplore.ieee.org/document/10760327)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.11894)
12. Takahiro Shindo, Taiju Watanabe, <u>Yui Tatsumi</u>, Hiroshi Watanabe, “**Scalable Image Coding for Humans and Machines Using Feature Fusion Network,**” IEEE 26th International Workshop on Multimedia Signal Processing (**MMSP**), 2024.
[![Generic badge](https://img.shields.io/badge/IEEE_Xplore-00629B.svg)](https://ieeexplore.ieee.org/document/10743782)
[![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.09152)
 [![Generic badge](https://img.shields.io/badge/Code-grey)](https://github.com/final-0/ICM-v1)

## Domestic Conference, Japan

1. <u>Yui Tatsumi</u>, Ziyue Zeng, Hiroshi Watanabe, “**Scalable Variable-Rate Video Compression for Humans and Machines via Keyframe Interpolation (in Japanese),**” The 29th Meeting on Image Recognition and Understanding (MIRU), 2026.
2. <u>Yui Tatsumi</u>, Ziyue Zeng, Hiroshi Watanabe, “**Assessing the Effectiveness of Residual Information in Scalable Image Coding for Humans and Machines (in Japanese),**” The 28th Meeting on Image Recognition and Understanding (MIRU), 2025.
3. Takahiro Shindo, Taiju Watanabe, <u>Yui Tatsumi</u>, Hiroshi Watanabe, “**Evaluation of Face Recognition Accuracy in Decoded Images for Machine Vision (in Japanese),**” The 87th National Convention of IPSJ, 2025.
4. Taiju Watanabe, Takahiro Shindo, <u>Yui Tatsumi</u>, Hiroshi Watanabe, “**Video Frame Interpolation Using Pretrained Diffusion Model (in Japanese),**” The 87th National Convention of IPSJ, 2025.
5. <u>Yui Tatsumi</u>, Takahiro Shindo, Taiju Watanabe, Hiroshi Watanabe, “**Scalable Image Coding for Humans and Machines Using Feature Differences (in Japanese),**” Picture Coding Symposium of Japan (PCSJ), 2024.
6. Takahiro Shindo, Taiju Watanabe, <u>Yui Tatsumi</u>, Hiroshi Watanabe, “**Assessing the Effectiveness of ICM Method for Privacy Protection (in Japanese),**” Picture Coding Symposium of Japan (PCSJ), 2024.
7. Taiju Watanabe, Takahiro Shindo, <u>Yui Tatsumi</u>, Hiroshi Watanabe, “**Evaluation of Face Recognition Accuracy in Decoded Images for Machine Vision (in Japanese),**” ITE Annual Convention, 2024.

<h2 id="education" class="section-heading">🏫EDUCATION</h2>

<div class="timeline">

  <div class="timeline-item">
    <div class="timeline-date">Apr. 2025 - Present</div>
    <div class="timeline-logo">
      <img src="assets/waseda_logo.jpg" alt="Waseda University">
    </div>
    <div class="timeline-content">
      <h3>Master of Engineering</h3>
      <p><strong>Department of Computer Science and Communications Engineering, <a href="https://www.waseda.jp/top/en/">Waseda University</a></strong></p>
      <p>Supervisor: Prof. <a href="https://www.ams.giti.waseda.ac.jp/">Hiroshi Watanabe</a></p>
      <p>Topics: Image Compression for Humans/Machines</p>
      <ul>
        <li>Conducted NICT commissioned research as a Research Assistant.</li>
        <li>Relevant Coursework: Advanced Image Information, Natural Language Processing, Information Security, and more. </li>
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Apr. 2021 - Mar. 2025</div>
    <div class="timeline-logo">
      <img src="assets/waseda_logo.jpg" alt="Waseda University">
    </div>
    <div class="timeline-content">
      <h3>Bachelor of Engineering</h3>
      <p><strong>Department of Communications and Computer Engineering, <a href="https://www.waseda.jp/top/en/">Waseda University</a></strong></p>
      <p>GPA: 3.6/4.0 <strong>(top 5%)</strong></p>
      <p>Supervisor: Prof. <a href="https://www.ams.giti.waseda.ac.jp/">Hiroshi Watanabe</a></p>
      <p>Topics: Image Compression for Humans/Machines, Sign Language Recognition</p>
      <ul>
        <li>Conducted NICT commissioned research as a Research Support Staff.</li>
        <li>Relevant Coursework: Computer Programming, Multimedia Systems, Software Engineering, Computer Architecture, Information Theory, Operating System, Signal Processing, and more.</li>
        <li>Published papers at international and domestic conferences such as <em>IEEE GCCE 2024</em> and <em>PCSJ/IMPS 2024</em>.</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Sep. 2018 - Mar. 2021</div>
    <div class="timeline-logo">
      <img src="assets/icu_logo.jpg" alt="ICU High School">
    </div>
    <div class="timeline-content">
      <h3>International Christian University High School</h3>
      <p>GPA: 4.8/5.0</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Oct. 2015 - Jun. 2018</div>
    <div class="timeline-logo">
      <div class="logo-placeholder">HI</div>
    </div>
    <div class="timeline-content">
      <h3>Public School in Hawaii, U.S.</h3>
    </div>
  </div>

</div>

<h2 id="experience" class="section-heading">👔EXPERIENCE</h2>

<div class="timeline">

  <div class="timeline-item">
    <div class="timeline-date">Apr. 2025 - Mar. 2026</div>
    <div class="timeline-logo">
      <img src="assets/waseda_logo.jpg" alt="Waseda University">
    </div>
    <div class="timeline-content">
      <h3>Research Assistant at Waseda University</h3>
      <p>Research project commissioned by NICT, Grant No. 05101</p>
      <ul>
        <li>Led a research project commissioned by the National Institute of Information and Communications Technology (NICT), as a Research Assistant at Waseda University.</li>
        <li>Conducted research on Image Compression for Humans/Machines.</li>
        <li>Published 9 papers in domestic/international conferences and journals as a commissioned research team at Waseda University, including IEEE MMSP 2024 and IEEE Access.</Li>
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Jan. 2026 - Jan. 2026</div>
    <div class="timeline-logo">
      <img src="assets/hitachi_logo.jpg" alt="Hitachi">
    </div>
    <div class="timeline-content">
      <h3>Research Intern at Hitachi, Central Research Laboratory</h3>
      <p>R&amp;D Group</p>
      <ul>
        <li>Conducted research on reliability enhancement and self-evolution technologies for AI agents.</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Aug. 2025 - Nov. 2025</div>
    <div class="timeline-logo">
      <img src="assets/ibm_logo.png" alt="IBM">
    </div>
    <div class="timeline-content">
      <h3>Research Intern at IBM Research - Tokyo</h3>
      <p>AI Automation</p>
      <ul>
        <li>Conducted research and investigation on AI agents for compliance automation.</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Aug. 2025 - Sep. 2025</div>
    <div class="timeline-logo">
      <img src="assets/sansan_logo.png" alt="Sansan">
    </div>
    <div class="timeline-content">
      <h3>Research Intern at Sansan</h3>
      <p>R&amp;D Automation Group</p>
      <ul>
        <li>Conducted R&amp;D on business card digitization, focusing on improving the performance and automation rate of Viola, an in-house VLM developed at Sansan.</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Apr. 2024 - Mar. 2025</div>
    <div class="timeline-logo">
      <img src="assets/waseda_logo.jpg" alt="Waseda University">
    </div>
    <div class="timeline-content">
      <h3>Research Support Staff at Waseda University</h3>
      <p>Research project commissioned by NICT, Grant No. 05101</p>
      <ul>
        <li>Led a research project commissioned by NICT, as a Research Support Staff at Waseda University.</li>
        <li>Conducted research on Scalable Image Compression for Humans and Machines.</li>
        <li>Published 8 papers in domestic/international conferences as a commissioned research team at Waseda University, including IEEE MMSP 2024. </li>
      </ul>
    </div>
  </div>

</div>

<h2 id="awards" class="section-heading">🏆ACADEMIC AWARDS</h2>

1. <a href="https://www.ieee-gcce.org/2025/awards.html">Oral Presentation Award</a>, IEEE GCCE 2025 (2025)
2. Dean's award for students who have achieved excellence in research activities during their undergraduate years, **TOP 5%** in the Department of Communications and Computer Engineering, Waseda University (2025)
3. <a href="https://www.ieee-gcce.org/2024/presentationawards.html">Oral Presentation Award</a>, IEEE GCCE 2024 (2024)

<h2 id="funding" class="section-heading">💰RESEARCH FUNDING</h2>

- NICT (National Institute of Information and Communications Technology) - No.05101 "R&D on ultra-coverage Beyond 5G wireless communication and video coding standardization technologies through international collaboration (Japan-US-Australia)"


<h2 id="skills" class="section-heading">✨SKILLS</h2>

- Programming Language: Python / C / Java / JavaScript
- Frameworks and Application Tools: PyTorch, OpenCV
- Others: GitHub / Docker / Kubernetes
- Natural Language: Japanese (Native), English, Japanese Sign Language

<h2 id="hobbies" class="section-heading">💚HOBBIES</h2>

Traveling / Japanese Sign Language / Movies

<h2 id="contact" class="section-heading">✉️CONTACT</h2>

Email: **yui.t@fuji.waseda.jp**