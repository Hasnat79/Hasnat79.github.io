---
permalink: /publications/
title: "Publications"
excerpt: "Research publications by Hasnat Md. Abdullah"
layout: null
---
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Publications · Hasnat Md. Abdullah</title>
  <style>
    :root {
      --cream: #faf8f4;
      --white: #fff;
      --ink: #1a1816;
      --muted: #7a746c;
      --faint: #b8b0a5;
      --accent: #b85c2c;
      --border: #e8e2da;
      --serif: Georgia, serif;
      --sans: "DM Sans", system-ui, sans-serif;
    }
    * { box-sizing: border-box; }
    body {
      margin: 0;
      background: var(--cream);
      color: var(--ink);
      font: 15px/1.7 var(--sans);
    }
    a { color: var(--accent); text-decoration: none; }
    a:hover { text-decoration: underline; }
    .site-wrap { max-width: 900px; margin: 0 auto; padding: 0 2rem; }
    nav {
      position: sticky;
      top: 0;
      z-index: 1;
      padding: .75rem 0;
      background: rgba(250,248,244,.94);
      border-bottom: 1px solid var(--border);
      backdrop-filter: blur(8px);
    }
    nav .site-wrap { display: flex; justify-content: space-between; align-items: center; }
    .nav-name { color: var(--ink); font: 500 1.05rem var(--serif); }
    .nav-links { display: flex; gap: 1.5rem; list-style: none; margin: 0; padding: 0; }
    .nav-links a {
      color: var(--muted);
      font-size: .78rem;
      font-weight: 500;
      letter-spacing: .04em;
      text-transform: uppercase;
    }
    .nav-links a:hover { color: var(--accent); text-decoration: none; }
    main { padding: 4rem 0 5rem; }
    .eyebrow {
      margin: 0 0 .5rem;
      color: var(--accent);
      font-size: .72rem;
      font-weight: 600;
      letter-spacing: .1em;
      text-transform: uppercase;
    }
    h1 { margin: 0 0 .75rem; font: 500 2.8rem/1.15 var(--serif); letter-spacing: -.03em; }
    .intro { max-width: 650px; margin: 0 0 2.5rem; color: var(--muted); }
    .section-label {
      margin: 2rem 0 .75rem;
      color: var(--faint);
      font-size: .72rem;
      font-weight: 600;
      letter-spacing: .1em;
      text-transform: uppercase;
    }
    .paper {
      margin: 0 0 .75rem;
      padding: 1rem 1.15rem;
      background: var(--white);
      border: 1px solid var(--border);
      border-radius: 8px;
    }
    .paper-title { margin: 0 0 .35rem; font-size: .95rem; line-height: 1.45; }
    .paper-title a { color: var(--ink); font-weight: 500; }
    .paper-title a:hover { color: var(--accent); }
    .paper-meta { margin: 0; color: var(--muted); font-size: .8rem; }
    .paper-note { margin: .25rem 0 0; color: var(--faint); font-size: .75rem; }
    footer { border-top: 1px solid var(--border); padding: 1.5rem 0; color: var(--faint); font-size: .78rem; text-align: center; }
    @media (max-width: 600px) {
      .site-wrap { padding: 0 1.25rem; }
      .nav-links { gap: .75rem; }
      .nav-links a { font-size: .68rem; }
      h1 { font-size: 2.2rem; }
      main { padding-top: 3rem; }
    }
  </style>
</head>
<body>
  <nav aria-label="Main navigation">
    <div class="site-wrap">
      <a class="nav-name" href="/">Hasnat Md. Abdullah</a>
      <ul class="nav-links">
        <li><a href="/">Home</a></li>
        <li><a href="/#research">Research</a></li>
        <li><a href="/#teaching">Service</a></li>
        <li><a href="#under-review">Under review</a></li>
      </ul>
    </div>
  </nav>

  <main class="site-wrap">
    <p class="eyebrow">Research record</p>
    <h1>Publications</h1>
    <p class="intro">
      Selected published work and manuscripts under review across AI, computer vision,
      multimodal learning, alignment, and applied animal-science research.
    </p>

    <p class="section-label">Published</p>

    <article class="paper">
      <h2 class="paper-title"><a href="https://doi.org/10.1609/aaai.v40i44.41106">DETONATE: A Benchmark for Text-to-Image Alignment and Kernelized Direct Preference Optimization</a></h2>
      <p class="paper-meta"><em>AAAI 2026 Special Track on AI Alignment</em> · First author · Oral presentation</p>
    </article>
    <article class="paper">
      <h2 class="paper-title"><a href="https://aclanthology.org/2026.findings-eacl.123/">Ask Me Again Differently: GRAS for Measuring Bias in VLMs on Gender, Race, Age, and Skin Tone</a></h2>
      <p class="paper-meta"><em>EACL 2026 Findings</em> · Co-author</p>
    </article>
    <article class="paper">
      <h2 class="paper-title"><a href="https://aclanthology.org/2025.nlp4pi-1.4/">CliME: Evaluating Multimodal Climate Discourse on Social Media and the Climate Alignment Quotient</a></h2>
      <p class="paper-meta"><em>ACL 2025 NLP for Positive Impact Workshop</em> · First author · Outstanding Paper Award</p>
    </article>
    <article class="paper">
      <h2 class="paper-title"><a href="https://github.com/Hasnat79/InstaLearn">InstaLearn: Continual Knowledge Updates for Domain Adaptation</a></h2>
      <p class="paper-meta"><em>KDD 2025 RelKD Workshop</em> · First author · Spotlight presentation</p>
      <p class="paper-note">Project repository; official proceedings or DOI record not identified.</p>
    </article>
    <article class="paper">
      <h2 class="paper-title"><a href="https://aclanthology.org/2025.emnlp-main.145/">Alignment Quality Index (AQI)</a></h2>
      <p class="paper-meta"><em>EMNLP 2025 Main Conference</em> · Co-author</p>
    </article>
    <article class="paper">
      <h2 class="paper-title"><a href="https://aclanthology.org/2025.findings-emnlp.364/">Mitigating Gender Bias via Fostering Exploratory Thinking in LLMs</a></h2>
      <p class="paper-meta"><em>EMNLP 2025 Findings</em> · Co-author</p>
    </article>
    <article class="paper">
      <h2 class="paper-title"><a href="https://doi.org/10.1109/WACV61041.2025.00566">UALBench: The First Comprehensive Unusual Activity Localization Benchmark</a></h2>
      <p class="paper-meta"><em>WACV 2025</em> · First author</p>
    </article>
    <article class="paper">
      <h2 class="paper-title"><a href="https://doi.org/10.1109/RO-MAN63969.2025.11217735">Non-Uniform Spatial Alignment Errors in sUAS Imagery From Wide-Area Disasters</a></h2>
      <p class="paper-meta"><em>IEEE RO-MAN 2025</em> · Co-author</p>
    </article>
    <article class="paper">
      <h2 class="paper-title"><a href="https://aclanthology.org/2025.ijcnlp-long.100/">Visual Counter Turing Test (VCT²)</a></h2>
      <p class="paper-meta"><em>IJCNLP-AACL 2025</em> · Co-author</p>
    </article>
    <article class="paper">
      <h2 class="paper-title"><a href="https://doi.org/10.1007/s11042-023-14597-6">Affective Social Anthropomorphic Intelligent System</a></h2>
      <p class="paper-meta"><em>Multimedia Tools &amp; Applications</em> · 2023 · Co-author</p>
    </article>
    <article class="paper">
      <h2 class="paper-title"><a href="https://doi.org/10.1109/ICCIT60459.2023.10441433">SynthEnsemble: A Fusion of CNN, Vision Transformer, and Hybrid Models for Chest X-Ray Classification</a></h2>
      <p class="paper-meta"><em>IEEE ICCIT 2023</em> · Co-author</p>
    </article>
    <article class="paper">
      <h2 class="paper-title"><a href="https://doi.org/10.1109/IICAIET55139.2022.9936742">A Comparative Analysis of Lumpy Skin Disease Prediction through ML Approaches</a></h2>
      <p class="paper-meta"><em>IEEE IICAIET 2022</em> · Co-author</p>
    </article>

    <p class="section-label" id="under-review">Under review</p>
    <article class="paper">
      <h2 class="paper-title">A spatiotemporal GNN for predicting New World Screwworm outbreak risk and informing sterile fly release</h2>
      <p class="paper-meta"><em>Journal of Animal Science</em> · First-author manuscript</p>
    </article>
    <article class="paper">
      <h2 class="paper-title">Evaluating the Impact of Depth Image Encoding and Temporal Domain Shift on Cattle Body Segmentation</h2>
      <p class="paper-meta"><em>Computers and Electronics in Agriculture</em> · First-author manuscript</p>
    </article>
  </main>

  <footer>
    <div class="site-wrap">Hasnat Md. Abdullah · <a href="mailto:hasnatabdullah79@gmail.com">Contact</a></div>
  </footer>
</body>
</html>
