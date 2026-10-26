---
layout: default
title: Prof. Lijian Xu | AI Research
---

<style>
:root {
  --accent: #2563eb;
  --accent-light: #eff6ff;
  --text-main: #1f2937;
  --text-muted: #64748b;
  --border: #e5e7eb;
  --surface: #ffffff;
  --surface-alt: #f8fafc;
}

#profile-site {
  color: var(--text-main);
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI",
    Helvetica, Arial, sans-serif;
  line-height: 1.75;
  max-width: 1100px;
  margin: 0 auto;
}

#profile-site * {
  box-sizing: border-box;
}

#profile-site a {
  color: var(--accent);
  text-decoration: none;
}

#profile-site a:hover {
  text-decoration: underline;
}

#profile-site .site-nav {
  position: sticky;
  top: 0;
  z-index: 100;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  gap: 12px;
  padding: 14px 20px;
  background: var(--surface);
  border-bottom: 1px solid var(--border);
}

#profile-site .brand {
  color: var(--text-main);
  font-weight: 750;
  font-size: 17px;
  white-space: nowrap;
}

#profile-site .nav-links {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  gap: 18px;
}

#profile-site .nav-links a {
  color: var(--text-main);
  font-size: 14px;
  font-weight: 550;
}

#profile-site .nav-toggle {
  display: none;
  padding: 6px 10px;
  border: 1px solid var(--border);
  border-radius: 7px;
  background: var(--surface);
  color: var(--text-main);
  cursor: pointer;
}

#profile-site .hero {
  display: grid;
  grid-template-columns: minmax(0, 1fr) 250px;
  gap: 42px;
  align-items: center;
  padding: 54px 28px 44px;
  border-bottom: 1px solid var(--border);
}

#profile-site .eyebrow {
  color: var(--accent);
  font-size: 13px;
  font-weight: 750;
  letter-spacing: 1.5px;
  text-transform: uppercase;
}

#profile-site h1 {
  margin: 8px 0 12px;
  color: var(--text-main);
  font-size: clamp(30px, 4vw, 43px);
  line-height: 1.2;
  letter-spacing: -1px;
}

#profile-site .affiliation {
  margin: 0 0 18px;
  color: var(--text-muted);
  font-size: 16px;
  line-height: 1.8;
}

#profile-site .hero-description {
  max-width: 690px;
  font-size: 15px;
}

#profile-site .hero-image {
  width: 100%;
  max-width: 230px;
  aspect-ratio: 4 / 5;
  object-fit: cover;
  border-radius: 14px;
  border: 1px solid var(--border);
  background: var(--surface-alt);
  justify-self: center;
}

#profile-site .hero-links {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 22px;
}

#profile-site .action-link {
  display: inline-block;
  padding: 8px 14px;
  border: 1px solid var(--border);
  border-radius: 8px;
  font-size: 13px;
  font-weight: 600;
}

#profile-site .action-link.primary {
  color: #fff;
  background: var(--accent);
  border-color: var(--accent);
}

#profile-site section {
  padding: 42px 28px;
  border-bottom: 1px solid var(--border);
  scroll-margin-top: 75px;
}

#profile-site .section-heading {
  margin: 0 0 8px;
  font-size: 26px;
  line-height: 1.35;
  letter-spacing: -0.4px;
}

#profile-site .section-subtitle {
  margin: 0 0 25px;
  color: var(--text-muted);
  font-size: 14px;
}

#profile-site .bio {
  max-width: 900px;
  font-size: 15px;
}

#profile-site .stats {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 14px;
  margin-top: 26px;
}

#profile-site .stat {
  padding: 18px;
  text-align: center;
  background: var(--surface-alt);
  border: 1px solid var(--border);
  border-radius: 10px;
}

#profile-site .stat-number {
  display: block;
  color: var(--accent);
  font-size: 25px;
  font-weight: 800;
}

#profile-site .stat-label {
  display: block;
  color: var(--text-muted);
  font-size: 12px;
}

#profile-site .research-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 18px;
}

#profile-site .research-card {
  padding: 23px;
  border: 1px solid var(--border);
  border-radius: 12px;
  background: var(--surface);
  transition: transform 0.2s, box-shadow 0.2s;
}

#profile-site .research-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 24px rgba(15, 23, 42, 0.07);
}

#profile-site .research-icon {
  font-size: 28px;
}

#profile-site .research-card h3 {
  margin: 10px 0 8px;
  font-size: 17px;
  line-height: 1.5;
}

#profile-site .research-card p {
  margin: 0;
  color: var(--text-muted);
  font-size: 14px;
}

#profile-site .tag-list {
  display: flex;
  flex-wrap: wrap;
  gap: 7px;
  margin-top: 14px;
}

#profile-site .tag {
  padding: 3px 9px;
  border-radius: 5px;
  background: var(--accent-light);
  color: var(--accent);
  font-size: 11px;
  font-weight: 600;
}

#profile-site .news-list {
  padding: 0;
  margin: 0;
  list-style: none;
}

#profile-site .news-item {
  display: grid;
  grid-template-columns: 64px minmax(0, 1fr);
  gap: 16px;
  padding: 14px 0;
  border-bottom: 1px solid var(--border);
  font-size: 14px;
}

#profile-site .news-item:last-child {
  border-bottom: none;
}

#profile-site .news-year {
  color: var(--accent);
  font-weight: 750;
}

#profile-site .pub-toolbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 12px;
  margin: 20px 0 25px;
}

#profile-site .pub-filters {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
}

#profile-site .filter-btn {
  padding: 7px 13px;
  border: 1px solid var(--border);
  border-radius: 7px;
  background: var(--surface);
  color: var(--text-main);
  cursor: pointer;
  font-size: 13px;
}

#profile-site .filter-btn.active {
  color: #fff;
  background: var(--accent);
  border-color: var(--accent);
}

#profile-site .pub-count {
  color: var(--text-muted);
  font-size: 12px;
}

#profile-site .pub-list {
  display: grid;
  gap: 18px;
}

#profile-site .pub-card {
  display: grid;
  grid-template-columns: 155px minmax(0, 1fr);
  gap: 22px;
  align-items: start;
  padding: 20px;
  border: 1px solid var(--border);
  border-radius: 12px;
  background: var(--surface);
}

#profile-site .pub-image {
  display: block;
  width: 100%;
  aspect-ratio: 4 / 3;
  object-fit: contain;
  border: 1px solid var(--border);
  border-radius: 7px;
  background: var(--surface-alt);
}

#profile-site .pub-venue {
  display: inline-block;
  margin-bottom: 7px;
  color: var(--accent);
  font-size: 11px;
  font-weight: 750;
  letter-spacing: 0.5px;
  text-transform: uppercase;
}

#profile-site .pub-title {
  margin: 0 0 9px;
  color: var(--text-main);
  font-size: 16px;
  line-height: 1.55;
}

#profile-site .pub-authors {
  margin: 0 0 7px;
  color: var(--text-muted);
  font-size: 13px;
}

#profile-site .pub-authors strong {
  color: var(--text-main);
}

#profile-site .pub-meta {
  margin: 0 0 12px;
  color: var(--text-muted);
  font-size: 12px;
}

#profile-site .pub-links {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
}

#profile-site .pub-links a {
  display: inline-block;
  padding: 4px 9px;
  border: 1px solid var(--border);
  border-radius: 5px;
  font-size: 12px;
  font-weight: 600;
}

#profile-site .pub-links a:hover {
  background: var(--accent-light);
  text-decoration: none;
}

#profile-site .collab-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 12px;
}

#profile-site .collab-item {
  padding: 15px 17px;
  border: 1px solid var(--border);
  border-radius: 9px;
  font-size: 14px;
}

#profile-site .contact-panel {
  padding: 25px;
  border: 1px solid var(--border);
  border-radius: 12px;
  background: var(--surface-alt);
}

#profile-site .contact-panel p {
  font-size: 14px;
}

#profile-site .site-footer {
  padding: 24px 28px;
  color: var(--text-muted);
  text-align: center;
  font-size: 12px;
}

#profile-site .back-top {
  float: right;
}

@media (max-width: 700px) {
  #profile-site .site-nav {
    padding: 12px 16px;
  }

  #profile-site .nav-toggle {
    display: block;
  }

  #profile-site .nav-links {
    display: none;
    flex-basis: 100%;
    flex-direction: column;
    align-items: flex-start;
    gap: 0;
    padding-top: 8px;
  }

  #profile-site .nav-links.open {
    display: flex;
  }

  #profile-site .nav-links a {
    width: 100%;
    padding: 9px 0;
  }

  #profile-site .hero {
    grid-template-columns: 1fr;
    padding: 35px 20px;
    gap: 24px;
  }

  #profile-site .hero-image {
    grid-row: 1;
    max-width: 155px;
    aspect-ratio: 1 / 1;
    border-radius: 50%;
  }

  #profile-site section {
    padding: 32px 20px;
  }

  #profile-site .research-grid,
  #profile-site .collab-grid {
    grid-template-columns: 1fr;
  }

  #profile-site .stats {
    gap: 8px;
  }

  #profile-site .stat {
    padding: 12px 6px;
  }

  #profile-site .stat-number {
    font-size: 21px;
  }

  #profile-site .pub-card {
    grid-template-columns: 1fr;
    gap: 14px;
    padding: 15px;
  }

  #profile-site .pub-image {
    max-width: 260px;
  }

  #profile-site .news-item {
    grid-template-columns: 52px minmax(0, 1fr);
    gap: 10px;
  }
}

@media (prefers-color-scheme: dark) {
  #profile-site {
    --text-main: #e5e7eb;
    --text-muted: #9ca3af;
    --border: #374151;
    --surface: #111827;
    --surface-alt: #1f2937;
    --accent-light: #1e3a5f;
    --accent: #60a5fa;
  }

  #profile-site .action-link.primary,
  #profile-site .filter-btn.active {
    color: #111827;
  }
}
</style>

<div id="profile-site">

  <!-- Navigation -->
  <nav class="site-nav">
    <a class="brand" href="#home">Lijian Xu</a>

    <button
      class="nav-toggle"
      type="button"
      aria-label="Toggle navigation"
      aria-expanded="false"
      onclick="(function(b){var n=document.querySelector('#profile-site .nav-links');var o=n.classList.toggle('open');b.setAttribute('aria-expanded',String(o));})(this)"
    >☰ Menu</button>

    <div class="nav-links">
      <a href="#home">Home</a>
      <a href="#research">Research</a>
      <a href="#news">News</a>
      <a href="#publications">Publications</a>
      <a href="#collaboration">Collaboration</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <!-- Home -->
  <header class="hero" id="home">
    <div>
      <div class="eyebrow">Artificial Intelligence · Research</div>

      <h1>Prof. Lijian Xu <span style="font-weight:400;">(徐利建)</span></h1>

      <p class="affiliation">
        Associate Professor<br>
        Institute of Artificial Intelligence<br>
        Shenzhen University of Advanced Technology (SUAT)
      </p>

      <div class="hero-description">
        <p>
          I work on multimodal artificial intelligence, efficient visual
          computing, medical foundation models, and bio-inspired embodied
          intelligence. My research aims to develop AI systems that are
          computationally efficient, generalizable, and trustworthy.
        </p>
      </div>

      <div class="hero-links">
        <a class="action-link primary"
           href="https://scholar.google.com/citations?hl=en&user=K-PZJhkAAAAJ"
           target="_blank" rel="noopener noreferrer">Google Scholar ↗</a>

        <a class="action-link"
           href="mailto:xulijian@suat-sz.edu.cn">Email</a>

        <a class="action-link" href="#publications">Selected Publications ↓</a>
      </div>
    </div>

    <!-- Replace with your own portrait if available -->
    <img
      class="hero-image"
      src="images/profile.jpg"
      alt="Lijian Xu"
      onerror="this.style.display='none'"
    >
  </header>

  <!-- Biography -->
  <section id="about">
    <h2 class="section-heading">About Me</h2>
    <p class="section-subtitle">Biography and research background</p>

    <div class="bio">
      <p>
        Dr. Lijian Xu is an Associate Professor at the Institute of Artificial
        Intelligence, Shenzhen University of Advanced Technology (SUAT).
        He received his Ph.D. through the joint academic program of Shanghai
        Jiao Tong University and Chiba University, following his M.S. from
        Shanghai Jiao Tong University and B.S. from Zhejiang University.
      </p>

      <p>
        He has held research positions at The Chinese University of Hong Kong,
        Shanghai Artificial Intelligence Laboratory, and SenseTime, gaining
        experience across academic research and industrial AI development.
      </p>

      <p>
        His research focuses on efficient multimodal intelligence, medical AI,
        computer vision, multimodal world models, and bio-inspired embodied
        intelligence. He is particularly interested in the interplay between
        data-driven learning, structured knowledge, computational efficiency,
        and trustworthy reasoning.
      </p>

      <p>
        He has published over <strong>60 research papers</strong>, with work
        appearing in venues including <em>Med</em> (Cell Press), ICML,
        <em>Pattern Recognition</em>, IEEE Transactions on Medical Imaging,
        and MICCAI.
      </p>

      <p>
        His applied research includes contributions to the Puyi medical
        multimodal foundation model developed in collaboration with Shanghai
        AI Laboratory, medical AI infrastructure, and the deployment of AI
        systems on domestic computing platforms. He has also collaborated
        with Huawei on migration to Ascend computing platforms and contributed
        to clinical AI translation through SenseCare.
      </p>
    </div>

    <div class="stats">
      <div class="stat">
        <span class="stat-number">60+</span>
        <span class="stat-label">Research Publications</span>
      </div>

      <div class="stat">
        <span class="stat-number">AI + Healthcare</span>
        <span class="stat-label">Research Translation</span>
      </div>

      <div class="stat">
        <span class="stat-number">SUAT</span>
        <span class="stat-label">Current Affiliation</span>
      </div>
    </div>
  </section>

  <!-- Research -->
  <section id="research">
    <h2 class="section-heading">Research Interests</h2>
    <p class="section-subtitle">
      From efficient multimodal models to intelligent embodied systems
    </p>

    <div class="research-grid">

      <article class="research-card">
        <div class="research-icon">⚡</div>
        <h3>Efficient Multimodal Intelligence</h3>
        <p>
          Reducing visual redundancy and computational cost in large
          multimodal models through token compression, dynamic inference,
          model distillation, quantization, and efficient architectures.
        </p>
        <div class="tag-list">
          <span class="tag">Token Compression</span>
          <span class="tag">Efficient Inference</span>
          <span class="tag">Model Optimization</span>
        </div>
      </article>

      <article class="research-card">
        <div class="research-icon">🩺</div>
        <h3>Medical Foundation Models</h3>
        <p>
          Developing multimodal medical AI systems for clinical image
          understanding, computational pathology, medical report generation,
          and reliable diagnostic reasoning.
        </p>
        <div class="tag-list">
          <span class="tag">Medical AI</span>
          <span class="tag">Computational Pathology</span>
          <span class="tag">Vision-Language Models</span>
        </div>
      </article>

      <article class="research-card">
        <div class="research-icon">🤖</div>
        <h3>Embodied Intelligence &amp; World Models</h3>
        <p>
          Exploring multimodal world models, intelligent agents, physical
          priors, and bio-inspired approaches for efficient perception,
          decision-making, and interaction with the physical world.
        </p>
        <div class="tag-list">
          <span class="tag">World Models</span>
          <span class="tag">Embodied AI</span>
          <span class="tag">Bio-inspired Intelligence</span>
        </div>
      </article>

      <article class="research-card">
        <div class="research-icon">🌐</div>
        <h3>Generalizable &amp; Trustworthy AI</h3>
        <p>
          Improving model robustness and transparency through structured
          knowledge, open-world recognition, uncertainty estimation,
          out-of-distribution adaptation, and interpretable reasoning.
        </p>
        <div class="tag-list">
          <span class="tag">Generalization</span>
          <span class="tag">Open-World Recognition</span>
          <span class="tag">Trustworthy AI</span>
        </div>
      </article>

    </div>
  </section>

  <!-- News -->
  <section id="news">
    <h2 class="section-heading">Recent News</h2>
    <p class="section-subtitle">Selected research updates</p>

    <ul class="news-list">
      <li class="news-item">
        <span class="news-year">2026</span>
        <span>
          Our work on interpretable multi-task chest radiograph analysis
          was published in <em>Med</em> (Cell Press).
        </span>
      </li>

      <li class="news-item">
        <span class="news-year">2026</span>
        <span>
          Our work on semantic slot aggregation for gigapixel pathology
          reasoning was accepted by MICCAI 2026.
        </span>
      </li>

      <li class="news-item">
        <span class="news-year">2026</span>
        <span>
          Our work on spatial-concept alignment for robust open-world vision
          appeared in <em>Pattern Recognition</em>.
        </span>
      </li>

      <li class="news-item">
        <span class="news-year">2026</span>
        <span>
          Research published in <em>Journal of Crystal Growth</em>.
        </span>
      </li>

      <li class="news-item">
        <span class="news-year">2025</span>
        <span>
          Research accepted by ICML 2025 and published in
          IEEE Transactions on Medical Imaging.
        </span>
      </li>
    </ul>
  </section>

  <!-- Publications -->
  <section id="publications">
    <h2 class="section-heading">Selected Publications</h2>
    <p class="section-subtitle">
      A selection of recent work. For the full publication list, please visit
      <a href="https://scholar.google.com/citations?hl=en&user=K-PZJhkAAAAJ"
         target="_blank" rel="noopener noreferrer">Google Scholar ↗</a>.
    </p>

    <div class="pub-toolbar">
      <div class="pub-filters" aria-label="Filter publications by year">
        <button class="filter-btn active" data-year="all" type="button">All</button>
        <button class="filter-btn" data-year="2026" type="button">2026</button>
        <button class="filter-btn" data-year="2025" type="button">2025</button>
      </div>
      <span class="pub-count" id="pub-count" aria-live="polite">
        4 selected publications
      </span>
    </div>

    <div class="pub-list" id="pub-list">

      <!-- Med 2026 -->
      <article class="pub-card" data-year="2026">
        <div>
          <img
            class="pub-image"
            src="images/med2026.JPG"
            alt="Med 2026 paper illustration"
            loading="lazy"
            onerror="this.style.display='none'"
          >
        </div>

        <div>
          <span class="pub-venue">Med · Cell Press · 2026</span>
          <h3 class="pub-title">
            A unified multi-task framework enables interpretable chest
            radiograph analysis
          </h3>
          <p class="pub-authors">
            <strong>Lijian Xu</strong>, Ziyu Ni, Xinglong Liu, Xiaosong Wang,
            Hongsheng Li, Shaoting Zhang
          </p>
          <p class="pub-meta">
            Medical AI · Multi-task Learning · Interpretable Diagnosis
          </p>
          <div class="pub-links">
            <a href="https://arxiv.org/abs/2606.03417"
               target="_blank" rel="noopener noreferrer">Paper ↗</a>
          </div>
        </div>
      </article>

      <!-- Pattern Recognition 2026 -->
      <article class="pub-card" data-year="2026">
        <div>
          <img
            class="pub-image"
            src="images/pr2026.png"
            alt="SCALAR paper illustration"
            loading="lazy"
            onerror="this.style.display='none'"
          >
        </div>

        <div>
          <span class="pub-venue">Pattern Recognition · 2026</span>
          <h3 class="pub-title">
            SCALAR: Spatial-Concept Alignment for Robust Vision in Harsh
            Open World
          </h3>
          <p class="pub-authors">
            Xiaoyu Yang, <strong>Lijian Xu</strong>, Xingyu Zeng, Xiaosong Wang,
            Hongsheng Li, Shaoting Zhang
          </p>
          <p class="pub-meta">
            Computer Vision · Spatial-Concept Alignment · Open-World Recognition
          </p>
          <div class="pub-links">
            <a href="https://www.sciencedirect.com/science/article/pii/S0031320326001688"
               target="_blank" rel="noopener noreferrer">Paper ↗</a>
          </div>
        </div>
      </article>

      <!-- MICCAI 2026 -->
      <article class="pub-card" data-year="2026">
        <div>
          <img
            class="pub-image"
            src="images/miccai2026.png"
            alt="TC-SSA paper illustration"
            loading="lazy"
            onerror="this.style.display='none'"
          >
        </div>

        <div>
          <span class="pub-venue">MICCAI · 2026</span>
          <h3 class="pub-title">
            TC-SSA: Token Compression via Semantic Slot Aggregation for
            Gigapixel Pathology Reasoning
          </h3>
          <p class="pub-authors">
            Zhuo Chen, Xiaoyu Yang, <strong>Lijian Xu</strong>
          </p>
          <p class="pub-meta">
            Computational Pathology · Token Compression · Efficient Reasoning
          </p>
          <div class="pub-links">
            <a href="https://arxiv.org/pdf/2603.01143"
               target="_blank" rel="noopener noreferrer">Paper ↗</a>
          </div>
        </div>
      </article>

      <!-- IEEE TMI 2025 -->
      <article class="pub-card" data-year="2025">
        <div>
          <img
            class="pub-image"
            src="images/tmi2025.png"
            alt="IEEE TMI paper illustration"
            loading="lazy"
            onerror="this.style.display='none'"
          >
        </div>

        <div>
          <span class="pub-venue">IEEE Transactions on Medical Imaging · 2025</span>
          <h3 class="pub-title">
            Segmentation and Vascular Vectorization for Coronary Artery by
            Geometry-Based Cascaded Neural Network
          </h3>
          <p class="pub-authors">
            Xiaoyu Yang, <strong>Lijian Xu</strong>, Qing Xia, Simon C. H. Yu,
            Hongsheng Li, Shaoting Zhang
          </p>
          <p class="pub-meta">
            Medical Image Analysis · Coronary Artery Segmentation · Vectorization
          </p>
          <div class="pub-links">
            <a href="https://arxiv.org/pdf/2305.04208"
               target="_blank" rel="noopener noreferrer">Paper ↗</a>
          </div>
        </div>
      </article>

    </div>

    <p style="margin-top:24px; text-align:center;">
      <a class="action-link"
         href="https://scholar.google.com/citations?hl=en&user=K-PZJhkAAAAJ"
         target="_blank" rel="noopener noreferrer">
        View Full Publication List on Google Scholar ↗
      </a>
    </p>
  </section>

  <!-- Collaboration -->
  <section id="collaboration">
    <h2 class="section-heading">Collaboration</h2>
    <p class="section-subtitle">
      Research collaboration across AI, medicine, and intelligent systems
    </p>

    <div class="collab-grid">
      <div class="collab-item">
        <strong>Medical Foundation Models</strong><br>
        <span style="color:var(--text-muted);">
          Multimodal learning and clinical reasoning
        </span>
      </div>

      <div class="collab-item">
        <strong>Computational Pathology</strong><br>
        <span style="color:var(--text-muted);">
          Whole-slide image understanding and efficient inference
        </span>
      </div>

      <div class="collab-item">
        <strong>Vision-Language Intelligence</strong><br>
        <span style="color:var(--text-muted);">
          Multimodal reasoning and generalizable visual models
        </span>
      </div>

      <div class="collab-item">
        <strong>Embodied Intelligence</strong><br>
        <span style="color:var(--text-muted);">
          World models and bio-inspired intelligent systems
        </span>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact">
    <h2 class="section-heading">Contact</h2>
    <p class="section-subtitle">
      Academic collaboration, student opportunities, and research inquiries
    </p>

    <div class="contact-panel">
      <p>
        I welcome opportunities for academic and industry collaboration
        in multimodal AI, medical AI, efficient visual computing, and
        embodied intelligence.
      </p>

      <p>
        <strong>Email:</strong>
        <a href="mailto:xulijian@suat-sz.edu.cn">
          xulijian@suat-sz.edu.cn
        </a>
      </p>

      <p>
        <strong>Affiliation:</strong><br>
        Institute of Artificial Intelligence,<br>
        Shenzhen University of Advanced Technology (SUAT)
      </p>

      <p>
        <a href="https://scholar.google.com/citations?hl=en&user=K-PZJhkAAAAJ"
           target="_blank" rel="noopener noreferrer">
          Google Scholar ↗
        </a>
      </p>
    </div>
  </section>

  <footer class="site-footer">
    <a class="back-top" href="#home">Back to top ↑</a>
    © 2026 Lijian Xu · Shenzhen University of Advanced Technology
  </footer>

</div>

<script>
(function () {
  const root = document.getElementById("profile-site");
  if (!root) return;

  // Close the mobile navigation after selecting a section.
  root.querySelectorAll(".nav-links a").forEach(function (link) {
    link.addEventListener("click", function () {
      const nav = root.querySelector(".nav-links");
      const toggle = root.querySelector(".nav-toggle");

      nav.classList.remove("open");
      toggle.setAttribute("aria-expanded", "false");
    });
  });

  // Filter selected publications by year.
  const buttons = root.querySelectorAll(".filter-btn");
  const papers = root.querySelectorAll(".pub-card");
  const count = root.querySelector("#pub-count");

  function applyFilter(year) {
    let visible = 0;

    papers.forEach(function (paper) {
      const matches = year === "all" || paper.dataset.year === year;
      paper.hidden = !matches;

      if (matches) visible++;
    });

    count.textContent = visible + " selected publication" +
      (visible === 1 ? "" : "s");

    buttons.forEach(function (button) {
      const active = button.dataset.year === year;
      button.classList.toggle("active", active);
      button.setAttribute("aria-pressed", String(active));
    });
  }

  buttons.forEach(function (button) {
    button.addEventListener("click", function () {
      applyFilter(button.dataset.year);
    });
  });

  applyFilter("all");
})();
</script>