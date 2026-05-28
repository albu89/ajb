---
permalink: /
title: Alexander John Büsser
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I build clinically deployable AI systems for diagnostics, disease modeling, and real-world evidence generation.

<p class="now-line"><span class="now-dot" aria-hidden="true"></span><strong>Currently:</strong> building <a href="https://www.cardioexplorer.ai/">Cardio Explorer</a> at Exploris Health. Open to advisory engagements, speaking, and select pro bono work.</p>

Over the past decade I have led AI, product, and engineering initiatives across [IBM](https://www.ibm.com), Roche, [Idorsia](https://www.idorsia.com), and [Exploris Health](https://www.explorishealth.com/) — contributing to launched medical products, regulatory-grade diagnostics, and large-scale real-world evidence platforms.

My current focus areas:

- clinically grounded foundation models
- multimodal disease representation learning
- regulatory-grade AI for diagnostics
- translational evidence generation across pharma and devices

My background combines machine learning training at [EPFL](https://www.epfl.ch/en/), [SNU](https://en.snu.ac.kr/), and [IBM](https://www.ibm.com) with a strong clinical track record — having shaped or led evidence programs at [GSK](https://www.gsk.com), [Sanofi](https://www.sanofi.com), and [Idorsia](https://www.idorsia.com). I have used this combination to launch two diagnostic products in endocrinology and cardiology, including the [Accu-Chek SmartGuide CGM](https://www.accu-chek.ch/fachkraefte/smartguide), which scaled to eight-figure (€) revenue in under three years.

My current focus is developing foundation models for the early detection of coronary artery disease — to help prevent avoidable myocardial infarctions.

<style>
  .product-section { margin-top: 1rem; }
  .section-subtitle { max-width: 70ch; opacity: 0.9; margin-bottom: 1.25rem; }
  .product-row {
    display: grid;
    grid-template-columns: 220px minmax(0, 1fr);
    gap: 20px;
    padding: 18px 0;
    border-top: 1px solid rgba(127, 127, 127, 0.25);
  }
  .product-row:first-of-type { border-top: none; }
  .product-media {
    border-radius: 12px;
    display: block;
    overflow: hidden;
    text-decoration: none;
  }
  .product-media img {
    width: 100%;
    aspect-ratio: 16 / 10;
    object-fit: cover;
    object-position: center;
    display: block;
    border: 1px solid rgba(127, 127, 127, 0.35);
    border-radius: 12px;
  }
  .product-media img.toujeo-image {
    object-position: top center;
  }
  .product-body {
    display: flex;
    flex-direction: column;
    justify-content: center;
    min-width: 0;
  }
  .product-body h3 { margin: 0 0 0.3rem 0; line-height: 1.2; }
  .product-one-liner {
    margin: 0 0 0.6rem 0;
    opacity: 0.92;
    line-height: 1.4;
    max-width: 62ch;
  }
  .product-links {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-top: 0.15rem;
  }
  .product-link {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    padding: 6px 10px;
    border-radius: 8px;
    border: 1px solid rgba(127, 127, 127, 0.3);
    text-decoration: none;
    line-height: 1.1;
    font-size: 0.95rem;
  }
  .product-link svg {
    width: 16px;
    height: 16px;
    flex: 0 0 16px;
  }
  .product-row:nth-of-type(even) { grid-template-columns: minmax(0, 1fr) 220px; }
  .product-row:nth-of-type(even) .product-media { order: 2; }
  .product-row:nth-of-type(even) .product-body { order: 1; }
  .work-buttons {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin-top: 0.5rem;
  }
  .work-button {
    display: inline-flex;
    align-items: center;
    padding: 8px 14px;
    border-radius: 8px;
    border: 1px solid rgba(127, 127, 127, 0.35);
    text-decoration: none;
    font-weight: 500;
    background: transparent;
    line-height: 1.1;
  }
  .work-button:hover {
    border-color: rgba(48, 158, 215, 0.55);
  }

  .impact-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 14px;
    margin: 1rem 0 1.5rem 0;
  }
  .impact-card {
    border: 1px solid rgba(127, 127, 127, 0.25);
    border-radius: 12px;
    padding: 14px 16px;
    background: transparent;
    transition: border-color 0.15s ease;
  }
  .impact-card:hover { border-color: rgba(48, 158, 215, 0.45); }
  .impact-card h4 {
    margin: 0 0 0.35rem 0;
    font-size: 0.78rem;
    text-transform: uppercase;
    letter-spacing: 0.06em;
    opacity: 0.7;
  }
  .impact-card p {
    margin: 0;
    line-height: 1.45;
    font-size: 0.95rem;
  }

  .theme-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 14px;
    margin: 1rem 0 1.5rem 0;
  }
  .theme-card {
    border: 1px solid rgba(127, 127, 127, 0.25);
    border-radius: 12px;
    padding: 16px 18px;
    background: transparent;
    transition: border-color 0.15s ease;
  }
  .theme-card:hover { border-color: rgba(48, 158, 215, 0.45); }
  .theme-card h3 {
    margin: 0 0 0.4rem 0;
    font-size: 1rem;
    line-height: 1.25;
  }
  .theme-card p {
    margin: 0;
    font-size: 0.93rem;
    line-height: 1.45;
    opacity: 0.92;
  }

  .now-line {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    padding: 6px 12px;
    margin: 0.25rem 0 1rem 0;
    border-radius: 999px;
    border: 1px solid rgba(48, 158, 215, 0.35);
    background: rgba(48, 158, 215, 0.06);
    font-size: 0.92rem;
    line-height: 1.4;
  }
  .now-dot {
    display: inline-block;
    width: 8px;
    height: 8px;
    border-radius: 50%;
    background: rgb(48, 158, 215);
    box-shadow: 0 0 0 4px rgba(48, 158, 215, 0.18);
    flex: 0 0 8px;
  }

  .work-cta {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-top: 1rem;
  }
  .work-button.primary {
    background: rgb(48, 158, 215);
    border-color: rgb(48, 158, 215);
    color: #fff;
  }
  .work-button.primary:hover {
    background: rgb(34, 138, 195);
    border-color: rgb(34, 138, 195);
    color: #fff;
  }
  .work-button svg {
    width: 16px;
    height: 16px;
    margin-right: 6px;
    flex: 0 0 16px;
  }

  @media (max-width: 900px) {
    .product-row { grid-template-columns: 1fr; }
    .product-row:nth-of-type(even) { grid-template-columns: 1fr; }
    .product-row .product-media,
    .product-row .product-body { order: initial; }
    .product-row:nth-of-type(even) .product-media,
    .product-row:nth-of-type(even) .product-body { order: initial; }
    .product-media {
      max-width: 320px;
      margin: 0 auto 0.5rem auto;
    }
    .product-links { margin-top: 0.35rem; }
  }
</style>

## At a glance

<section class="impact-grid">
  <div class="impact-card">
    <h4>Diagnostics</h4>
    <p>Two launched products in endocrinology and cardiology, deployed in real clinical practice.</p>
  </div>
  <div class="impact-card">
    <h4>Pharma evidence</h4>
    <p>Real-world evidence work supporting launches of blockbuster therapeutics including <a href="https://www.idorsia.com/our-innovation/portfolio/daridorexant.html">Daridorexant</a> and <a href="https://www.toujeo.com/">Toujeo</a>.</p>
  </div>
  <div class="impact-card">
    <h4>Publications</h4>
    <p><a href="https://www.nature.com/nm/">Nature Medicine</a>, <a href="https://www.nature.com/articles/s43856-024-00698-2">Communications Medicine</a>, and issued <a href="https://patents.google.com/patent/US20230092186A1/en">patents</a>.</p>
  </div>
  <div class="impact-card">
    <h4>Industry</h4>
    <p>IBM, Roche, Idorsia, Exploris Health. Global IBM Innovation Award recipient.</p>
  </div>
  <div class="impact-card">
    <h4>AI focus</h4>
    <p>Clinical foundation models and multimodal disease representation learning.</p>
  </div>
  <div class="impact-card">
    <h4>Regulatory</h4>
    <p>Hands-on experience shipping Software-as-a-Medical-Device (SaMD) under regulated quality systems.</p>
  </div>
</section>

## Selected Products & Translational Impact

<section class="product-section">
  <article class="product-row">
    <a class="product-media" href="https://www.cardioexplorer.ai/" target="_blank" rel="noopener">
      <img src="/images/products/cardio-explorer.png" alt="Cardio Explorer" loading="lazy" />
    </a>
    <div class="product-body">
      <h3><a href="https://www.cardioexplorer.ai/" target="_blank" rel="noopener">Cardio Explorer</a></h3>
      <p class="product-one-liner">Built and led the science, regulatory, and product/engineering function end-to-end; hired and managed a 5-person team, secured key regulatory approvals, and drove early adoption with leading hospitals.</p>
      <div class="product-links">
        <a class="product-link" href="https://www.youtube.com/watch?v=wA3W-pthrIM" target="_blank" rel="noopener">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
            <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
            <path d="M2 8a4 4 0 0 1 4 -4h12a4 4 0 0 1 4 4v8a4 4 0 0 1 -4 4h-12a4 4 0 0 1 -4 -4v-8" />
            <path d="M10 9l5 3l-5 3l0 -6" />
          </svg>
          <span>YouTube</span>
        </a>
        <a class="product-link" href="https://drive.google.com/file/d/1tmrWQ8N9T1YAzYA-BiYiD0_NIEcPqHSG/view" target="_blank" rel="noopener">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
            <path d="M12 7v14"/>
            <path d="M3 18a2 2 0 0 1 2 -2h7"/>
            <path d="M3 6a2 2 0 0 1 2 -2h7v20H5a2 2 0 0 1 -2 -2z"/>
            <path d="M12 4h7a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-7"/>
          </svg>
          <span>Poster</span>
        </a>
      </div>
    </div>
  </article>

  <article class="product-row">
    <a class="product-media" href="https://www.accu-chek.ch/fachkraefte/smartguide" target="_blank" rel="noopener">
      <img src="/images/products/smart-life.png" alt="Accu-Check SmartGuide CGM" loading="lazy" />
    </a>
    <div class="product-body">
      <h3><a href="https://www.accu-chek.ch/fachkraefte/smartguide" target="_blank" rel="noopener">Accu-Check SmartGuide CGM</a></h3>
      <p class="product-one-liner">Responsible for the full product lifecycle for an AI-driven Software-as-a-Medical-Device (SaMD), managing a seven-figure (€) budget. Scaled the engineering and product team from early-stage R&amp;D (2 FTE) to 30+ FTE and substantially improved diagnostic algorithms using early transformer architectures, earning a global IBM Innovation Award.</p>
    </div>
  </article>

  <article class="product-row">
    <a class="product-media" href="https://www.idorsia.com/our-innovation/portfolio/daridorexant.html" target="_blank" rel="noopener">
      <img src="/images/products/daridorexant.png" alt="Daridorexant" loading="lazy" />
    </a>
    <div class="product-body">
      <h3><a href="https://www.idorsia.com/our-innovation/portfolio/daridorexant.html" target="_blank" rel="noopener">Daridorexant</a></h3>
      <p class="product-one-liner">Orexin receptor antagonist program supported by evidence strategy and RWE.</p>
    </div>
  </article>

  <article class="product-row">
    <a class="product-media" href="https://www.toujeo.com/" target="_blank" rel="noopener">
      <img class="toujeo-image" src="/images/products/toujeo.png" alt="Toujeo" loading="lazy" />
    </a>
    <div class="product-body">
      <h3><a href="https://www.toujeo.com/" target="_blank" rel="noopener">Toujeo</a></h3>
      <p class="product-one-liner">Long-acting insulin supported by real-world evidence and launch enablement work.</p>
    </div>
  </article>
</section>

## Current Research Themes

My research centers on representation learning for clinical and physiological data, with an emphasis on safety, grounding, and translational utility.

<section class="theme-grid">
  <article class="theme-card">
    <h3>Physiologically grounded foundation models</h3>
    <p>Guiding transformers toward <a href="https://patents.google.com/patent/US20230092186A1/en">physiologically meaningful behavior</a> rather than purely statistical pattern matching.</p>
  </article>
  <article class="theme-card">
    <h3>Clinical representation learning</h3>
    <p>Compact, transferable representations of patients, encounters, and trajectories learned from noisy real-world data.</p>
  </article>
  <article class="theme-card">
    <h3>Disease ontology learning</h3>
    <p>Using language models to learn new <a href="https://www.nature.com/articles/s43856-024-00698-2">disease representations</a> directly from clinical text and codes.</p>
  </article>
  <article class="theme-card">
    <h3>Multimodal cardiovascular diagnostics</h3>
    <p>Combining laboratory, imaging, and signal modalities for the earliest possible detection of coronary artery disease.</p>
  </article>
  <article class="theme-card">
    <h3>Real-world evidence modeling</h3>
    <p>Methods for treatment-effect estimation and biomarker discovery on biased, incomplete observational data.</p>
  </article>
  <article class="theme-card">
    <h3>Translational ML safety</h3>
    <p>Safety, calibration, and uncertainty quantification for models intended for regulated clinical deployment.</p>
  </article>
</section>

## Work with me

I'm currently open to **advisory engagements, speaking, and select pro bono work**. Not actively job-searching, but happy to have the conversation for the right team or mission.

Areas where I'm most useful:

- AI diagnostics and foundation-model strategy
- Real-world evidence design for product launches
- Product and engineering leadership for regulated AI / SaMD
- Scientific advisory for HealthTech startups and pharma teams
- Invited talks and workshops on AI in healthcare

<div class="work-cta">
  <a class="work-button primary" href="mailto:aj.buesser@gmail.com">
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
      <path d="M3 7l9 6l9 -6"/>
      <path d="M3 6m0 2a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2h-14a2 2 0 0 1 -2 -2z"/>
    </svg>
    <span>Email me</span>
  </a>
  <a class="work-button" href="https://www.linkedin.com/in/abu89/" target="_blank" rel="noopener">
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true">
      <path d="M19 3a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2h-14a2 2 0 0 1 -2 -2v-14a2 2 0 0 1 2 -2zM8 11a1 1 0 0 0 -1 1v5a1 1 0 0 0 2 0v-5a1 1 0 0 0 -1 -1zM8 7.5a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0 -3zM13 11a1 1 0 0 0 -1 1v5a1 1 0 0 0 2 0v-2.5c0 -.83 .67 -1.5 1.5 -1.5s1.5 .67 1.5 1.5v2.5a1 1 0 0 0 2 0v-2.5a3.5 3.5 0 0 0 -6 -2.46v-.04a1 1 0 0 0 -1 -1z"/>
    </svg>
    <span>Message on LinkedIn</span>
  </a>
</div>
