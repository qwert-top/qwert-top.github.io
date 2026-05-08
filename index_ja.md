---
layout: null
title: Yui Tatsumi / 巽 優衣
---

<style>
body {
  max-width: 1200px;
  margin: 40px auto;
  padding: 0 20px;
  line-height: 1.7;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
}
.side-nav {
  position: fixed;
  left: 24px;
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
}
.profile {
  display: flex;
  align-items: flex-start;
  gap: 24px;
  margin: 24px 0 36px;
}
.profile img {
  width: 120px;
  height: 120px;
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
  <a href="#profile">プロフィール</a>
  <a href="#publications">業績</a>
  <a href="#education">学歴</a>
  <a href="#experience">研究経験</a>
  <a href="#awards">受賞</a>
  <a href="#funding">研究費</a>
  <a href="#skills">スキル</a>
  <a href="#hobbies">趣味</a>
  <a href="#contact">連絡先</a>
</nav>

[En](index.html)/Ja

<div id="profile" class="profile">
  <img src="my_image.png" alt="巽 優衣">

  <div class="profile-content">
    <h1>巽 優衣 / Yui Tatsumi</h1>

    <p>
      <a href="https://github.com/qwert-top"><strong>Github</strong></a>　/　
      <a href="http://linkedin.com/in/qwert-top"><strong>Linkedin</strong></a>　/　
      <a href="https://scholar.google.com/citations?user=u1nK1wgAAAAJ"><strong>Google Scholar</strong></a>
    </p>

    <p><strong>早稲田大学 大学院 基幹理工学研究科 情報理工・情報通信専攻 修士2年</strong></p>

    <p>
      人工知能、コンピュータービジョン、信号処理などに興味があります。
      渡辺裕教授の指導のもと、主にニューラルネットワークを用いた視聴や認識のための画像圧縮技術について研究しています。
    </p>

    <p>
      学部時の成績および研究業績が学科内の上位5%であり、卒業時には学科賞をいただきました。
    </p>

    <p>
      修士課程修了（2027年3月見込み）後の就職先として企業での研究職を検討しています。
      興味をもっていただいた方はご連絡いただけますと幸いです。
    </p>
  </div>
</div>

<h2 id="publications" class="section-heading">📚研究業績</h2>

### **査読付き学術論文**

1. Takahiro Shindo, Taiju Watanabe, **Yui Tatsumi**, Hiroshi Watanabe, “Image Coding for Object Recognition Tasks Based on Contour Feature Learning with Flexible Object Selection,” **IEEE Access**, 2025.

### 国際会議

1. Ziyue Zeng, **Yui Tatsumi**, Hiroshi Watanabe, “Flow Residual Segmentation and Generative Reconstruction for Motion-Aware Video Coding,” The 9th IIEEJ International Conference on Image Electronics and Visual Computing (**IEVC**), 2026.
2. **Yui Tatsumi**, Ziyue Zeng, Hiroshi Watanabe, “Training-Free Adaptive Quantization for Variable Rate Image Coding for Machines,” IEEE 44th International Conference on Consumer Electronics (**ICCE**), 2026.
3. Taiju Watanabe, Takahiro Shindo, **Yui Tatsumi**, Hiroshi Watanabe, “VFI-LoRA: Leveraging Video Diffusion Models for Video Interpolation Through LoRA Finetuning,” IEEE International Conference on Internet of Things and Intelligence System (**IoTaIS**), 2025.
4. **Yui Tatsumi**, Ziyue Zeng, Hiroshi Watanabe, “Seed Selection for Human-Oriented Image Reconstruction via Guided Diffusion,” IEEE 14th Global Conference on Consumer Electronics (**GCCE**), 2025.
5. Ziyue Zeng, **Yui Tatsumi**, Hiroshi Watanabe, “Bidirectional Attention-Gated Motion Injection for Frame Interpolation,” IEEE 14th Global Conference on Consumer Electronics (**GCCE**), 2025.
6. **Yui Tatsumi**, Ziyue Zeng, Hiroshi Watanabe, “Explicit Residual-Based Scalable Image Coding for Humans and Machines,” IEEE 27th International Workshop on Multimedia Signal Processing (**MMSP**), 2025.
7. Takahiro Shindo, **Yui Tatsumi**, Taiju Watanabe, Hiroshi Watanabe, “Guided Diffusion for the Extension of Machine Vision to Human Visual Perception,” IEEE 27th International Workshop on Multimedia Signal Processing (**MMSP**), 2025.
8. Takahiro Shindo, Taiju Watanabe, **Yui Tatsumi**, Hiroshi Watanabe, “Delta-ICM: Entropy Modeling with Delta Function for Learned Image Compression,” IEEE 43rd International Conference on Consumer Electronics (**ICCE**), 2025.
9. **Yui Tatsumi**, Shoko Tanaka, Shunsuke Akamatsu, Takahiro Shindo, Hiroshi Watanabe, “Classification in Japanese Sign Language Based on Dynamic Facial Expressions,” IEEE 13th Global Conference on Consumer Electronics (**GCCE**), 2024. 
10. Shoko Tanaka, **Yui Tatsumi**, Takahiro Shindo, Hiroshi Watanabe, “Integrating QR Code Characteristics Into Super-Resolution Method,” IEEE 13th Global Conference on Consumer Electronics (**GCCE**), 2024. 
11. Takahiro Shindo, **Yui Tatsumi**, Taiju Watanabe, Hiroshi Watanabe, “Refining Coded Image in Human Vision Layer Using CNN-Based Post-Processing,” IEEE 13th Global Conference on Consumer Electronics (**GCCE**), 2024.
12. Takahiro Shindo, Taiju Watanabe, **Yui Tatsumi**, Hiroshi Watanabe, “Scalable Image Coding for Humans and Machines Using Feature Fusion Network,” IEEE 26th International Workshop on Multimedia Signal Processing (**MMSP**), 2024.

### 国内会議

1. **Yui Tatsumi**, Ziyue Zeng, Hiroshi Watanabe, “Assessing the Effectiveness of Residual Information in Scalable Image Coding for Humans and Machines （日本語）,” The 28th Meeting on Image Recognition and Understanding (MIRU), 2025.
2. Takahiro Shindo, Taiju Watanabe, **Yui Tatsumi**, Hiroshi Watanabe, “Evaluation of Face Recognition Accuracy in Decoded Images for Machine Vision （日本語）,” The 87th National Convention of IPSJ, 2025.
3. Taiju Watanabe, Takahiro Shindo, **Yui Tatsumi**, Hiroshi Watanabe, “Video Frame Interpolation Using Pretrained Diffusion Model （日本語）,” The 87th National Convention of IPSJ, 2025.
4. **Yui Tatsumi**, Takahiro Shindo, Taiju Watanabe, Hiroshi Watanabe, “Scalable Image Coding for Humans and Machines Using Feature Differences （日本語）,” Picture Coding Symposium of Japan (PCSJ), 2024.
5. Takahiro Shindo, Taiju Watanabe, **Yui Tatsumi**, Hiroshi Watanabe, “Assessing the Effectiveness of ICM Method for Privacy Protection （日本語）,” Picture Coding Symposium of Japan (PCSJ), 2024.
6. Taiju Watanabe, Takahiro Shindo, **Yui Tatsumi**, Hiroshi Watanabe, “Evaluation of Face Recognition Accuracy in Decoded Images for Machine Vision （日本語）,” ITE Annual Convention, 2024.

<h2 id="education" class="section-heading">🏫学歴</h2>

<div class="timeline">

  <div class="timeline-item">
    <div class="timeline-date">2025年4月 - 現在</div>
    <div class="timeline-logo">
      <img src="assets/waseda_logo.jpg" alt="早稲田大学">
    </div>
    <div class="timeline-content">
      <h3>修士（工学）</h3>
      <p><strong><a href="https://www.waseda.jp/top/">早稲田大学</a> 基幹理工学研究科 情報理工・情報通信専攻</strong></p>
      <p>指導教員：<a href="https://www.ams.giti.waseda.ac.jp/">渡辺 裕 教授</a></p>
      <p>研究テーマ：人間と機械のための画像圧縮</p>
      <ul><li>リサーチアシスタントとしてNICT委託研究に従事。</li></ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2021年4月 - 2025年3月</div>
    <div class="timeline-logo">
      <img src="assets/waseda_logo.jpg" alt="早稲田大学">
    </div>
    <div class="timeline-content">
      <h3>学士（工学）</h3>
      <p><strong><a href="https://www.waseda.jp/top/">早稲田大学</a> 基幹理工学部 情報通信学科</strong></p>
      <p>GPA：3.6/4.0 <strong>（上位5%）</strong></p>
      <p>指導教員：<a href="https://www.ams.giti.waseda.ac.jp/">渡辺 裕 教授</a></p>
      <p>研究テーマ：人間と機械のための画像圧縮, Sign Language Recognition</p>
      <ul>
        <li>研究補助者としてNICT委託研究に従事。</li>
        <li>主な履修科目：コンピュータプログラミング、マルチメディアシステム、ソフトウェア工学、コンピュータアーキテクチャ、情報理論、オペレーティングシステム、信号処理など。</li>
        <li><em>IEEE GCCE 2024</em> や <em>PCSJ/IMPS 2024</em> などの国際・国内会議で論文を発表。</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2018年9月 - 2021年3月</div>
    <div class="timeline-logo">
      <img src="assets/icu_logo.jpg" alt="ICU High School">
    </div>
    <div class="timeline-content">
      <h3>国際基督教大学高等学校</h3>
      <p>GPA: 4.8/5.0</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2015年10月 - 2018年6月</div>
    <div class="timeline-logo"><div class="logo-placeholder">HI</div></div>
    <div class="timeline-content">
      <h3>米国ハワイ州の現地校に在籍</h3>
    </div>
  </div>

</div>


<h2 id="experience" class="section-heading">👔研究経験</h2>

<div class="timeline">

  <div class="timeline-item">
    <div class="timeline-date">2025年4月 - 2026年3月</div>
    <div class="timeline-logo">
      <img src="assets/waseda_logo.jpg" alt="早稲田大学">
    </div>
    <div class="timeline-content">
      <h3>Research Assistant at 早稲田大学</h3>
      <p>NICT委託研究 課題番号 05101</p>
      <ul>
        <li>Leading a research project commissioned by the National Institute of Information and Communications Technology (NICT), as a Research Assistant at 早稲田大学.</li>
        <li>人間と機械のための画像圧縮に関する研究に従事。</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2026年1月</div>
    <div class="timeline-logo">
      <img src="assets/hitachi_logo.jpg" alt="Hitachi">
    </div>
    <div class="timeline-content">
      <h3>日立製作所 中央研究所 研究インターンシップ</h3>
      <p>研究開発グループ</p>
      <ul><li>AIエージェントの信頼性向上および自己進化技術に関する研究に従事。</li></ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2025年8月 - 2025年11月</div>
    <div class="timeline-logo"><div class="logo-placeholder">IBM</div></div>
    <div class="timeline-content">
      <h3>IBM Research - Tokyo Research Scientist Internship</h3>
      <p><strong>AI Automation</strong></p>
      <ul><li>コンプライアンス自動化に向けたAIエージェントに関する研究・調査に従事。</li></ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2025年8月 - 2025年9月</div>
    <div class="timeline-logo"><div class="logo-placeholder">S</div></div>
    <div class="timeline-content">
      <h3>Sansan R&amp;D インターンシップ</h3>
      <p>R&amp;D Automation Group</p>
      <ul><li>Sansan社内VLMであるViolaの性能および自動化率向上を目的として、名刺デジタル化に関する研究開発に従事。</li></ul>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2024年4月 - 2025年3月</div>
    <div class="timeline-logo">
      <img src="assets/waseda_logo.jpg" alt="早稲田大学">
    </div>
    <div class="timeline-content">
      <h3>Research Support Staff at 早稲田大学</h3>
      <p>NICT委託研究 課題番号 05101</p>
      <ul>
        <li>Led a research project commissioned by NICT, as a Research Support Staff at 早稲田大学.</li>
        <li>人間と機械のためのスケーラブル画像圧縮に関する研究に従事。</li>
        <li>Published 8 papers at conferences such as IEEE MMSP 2024 as a commissioned research team from 早稲田大学.</li>
      </ul>
    </div>
  </div>

</div>

<h2 id="awards" class="section-heading">🏆受賞</h2>

1. Oral Presentation Award, IEEE GCCE 2025 (2025)
2. 情報通信学科賞, 学部在学中の研究活動において優れた成果を収め、学科内で**上位5**％に入る学生に授与 (2025)
3. Oral Presentation Award, IEEE GCCE 2024 (2024)  

<h2 id="funding" class="section-heading">💰研究費</h2>

- NICT（国立研究開発法人 情報通信研究機構）
「情報通信技術に関する委託研究」課題番号 05101

<h2 id="skills" class="section-heading">✨スキル</h2>

- プログラミング言語：Python / C / Java / JavaScript
- フレームワーク・ツール：PyTorch, OpenCV
- その他：GitHub / Docker / Kubernetes
- 自然言語：日本語（母語）, 英語, 日本手話

<h2 id="hobbies" class="section-heading">💚趣味</h2>

旅行 / 日本手話 / 映画

<h2 id="contact" class="section-heading">✉️連絡先</h2>

Email： **yui.t@fuji.waseda.jp**