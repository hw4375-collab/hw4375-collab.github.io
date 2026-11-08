---
layout: about
title: Home
permalink: /
subtitle:

selected_papers: false
social: false

announcements:
  enabled: false
  scrollable: true
  limit: 3

latest_posts:
  enabled: false
---

<div class="academic-home">
  <section class="academic-hero" aria-labelledby="home-title">
    <div class="academic-hero__copy">
      <p class="eyebrow">New York University Abu Dhabi · Mathematics + AI</p>
      <h1 id="home-title">Hongwei <span>(Alex)</span> Wang</h1>
      <p class="hero-role">MSc Student in Interdisciplinary Data Science and Artificial Intelligence</p>
      <p class="hero-theme">Mathematical Foundations of Trustworthy Artificial Intelligence</p>
      <p class="hero-introduction">
        I work at the intersection of type theory, higher category theory, formalized mathematics, and artificial
        intelligence, with particular interest in reliable machine reasoning and semantic faithfulness.
      </p>
      <div class="action-row" aria-label="Academic navigation">
        <a class="academic-button academic-button--primary" href="{{ '/research/' | relative_url }}">Explore Research</a>
        <a class="academic-button academic-button--secondary" href="{{ '/projects/' | relative_url }}">View Projects</a>
        <a class="academic-button academic-button--quiet" href="{{ '/assets/pdf/Hongwei_Wang_Academic_CV.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer">Download Academic CV</a>
      </div>
    </div>

    <figure class="meaning-diagram" aria-labelledby="meaning-diagram-title">
      <figcaption id="meaning-diagram-title">A research question in formal reasoning</figcaption>
      <ol>
        <li>
          <span class="diagram-step">01</span>
          <strong>Meaning</strong>
          <span>Mathematical intent</span>
        </li>
        <li>
          <span class="diagram-step">02</span>
          <strong>Formalization</strong>
          <span>Type-theoretic representation</span>
        </li>
        <li>
          <span class="diagram-step">03</span>
          <strong>Verification</strong>
          <span>Machine-checked reasoning</span>
        </li>
      </ol>
      <p>Formal correctness is essential; semantic faithfulness remains the central question.</p>
    </figure>

  </section>

  <section class="academic-section" aria-labelledby="about-heading">
    <div class="section-heading">
      <p class="eyebrow">About</p>
      <h2 id="about-heading">A mathematical approach to reliable reasoning</h2>
    </div>
    <div class="reading-copy reading-copy--wide">
      <p>
        I am a master's student at <strong>New York University Abu Dhabi</strong>, with an academic background in pure
        mathematics. I am particularly interested in how mathematical structures can provide foundations for reliable
        machine reasoning, and how the meaning of mathematical statements can be preserved when translated between
        natural language and formal systems.
      </p>
      <p>
        Proof assistants can mechanically verify formal derivations, but a further question remains: does a formally
        verified statement faithfully represent the mathematical statement originally intended? This distinction between
        formal correctness and semantic faithfulness motivates much of my current work.
      </p>
    </div>
  </section>

  <section class="academic-section" aria-labelledby="interests-heading">
    <div class="section-heading section-heading--split">
      <div>
        <p class="eyebrow">Research interests</p>
        <h2 id="interests-heading">Three connected directions</h2>
      </div>
      <a class="text-link" href="{{ '/research/' | relative_url }}">Research overview <span aria-hidden="true">→</span></a>
    </div>

    <div class="research-card-grid">
      <a class="research-interest-card" href="{{ '/research/#mathematical-foundations' | relative_url }}">
        <span class="card-index">01</span>
        <h3>Mathematical Foundations</h3>
        <p>Structural languages for objects, proofs, equivalences, and higher-dimensional reasoning.</p>
        <ul class="topic-list" aria-label="Mathematical Foundations topics">
          <li>Dependent Type Theory</li>
          <li>Homotopy Type Theory</li>
          <li>Higher Category Theory</li>
        </ul>
        <span class="card-link">Explore direction <span aria-hidden="true">→</span></span>
      </a>

      <a class="research-interest-card" href="{{ '/research/#ai-for-formal-mathematics' | relative_url }}">
        <span class="card-index">02</span>
        <h3>AI for Formal Mathematics</h3>
        <p>Examining how mathematical language can become formal code without losing intended meaning.</p>
        <ul class="topic-list" aria-label="AI for Formal Mathematics topics">
          <li>Autoformalization</li>
          <li>Semantic Faithfulness</li>
          <li>Machine-Checked Proofs</li>
        </ul>
        <span class="card-link">Explore direction <span aria-hidden="true">→</span></span>
      </a>

      <a class="research-interest-card" href="{{ '/research/#formal-methods-for-trustworthy-ai' | relative_url }}">
        <span class="card-index">03</span>
        <h3>Trustworthy Artificial Intelligence</h3>
        <p>Using formal methods to make reasoning systems and AI agents more reliable and verifiable.</p>
        <ul class="topic-list" aria-label="Trustworthy Artificial Intelligence topics">
          <li>Formal Verification</li>
          <li>Reliable Reasoning</li>
          <li>AI Agent Verification</li>
        </ul>
        <span class="card-link">Explore direction <span aria-hidden="true">→</span></span>
      </a>
    </div>

  </section>

  <section class="academic-section academic-section--current" aria-labelledby="current-research-heading">
    <div class="section-heading section-heading--split">
      <div>
        <p class="eyebrow">Current research</p>
        <h2 id="current-research-heading">Meaning, representation, and machine-verifiable reasoning</h2>
      </div>
      <a class="text-link" href="{{ '/research/' | relative_url }}">Research directions <span aria-hidden="true">→</span></a>
    </div>
    <p class="current-research-intro">
      I am currently exploring the relationship between mathematical meaning, formal representation, and machine-verifiable reasoning.
    </p>
    <ul class="current-research-list">
      <li>Developing and studying formal representations of mathematical reasoning.</li>
      <li>Investigating semantic faithfulness in AI-assisted mathematical formalization.</li>
      <li>Exploring type-theoretic and homotopy-theoretic approaches to formalized mathematics.</li>
      <li>Applying formal verification techniques to the reliability of AI reasoning systems.</li>
    </ul>
  </section>

  <section class="academic-section academic-section--surface" aria-labelledby="featured-heading">
    <div class="section-heading section-heading--split">
      <div>
        <p class="eyebrow">Featured research</p>
        <h2 id="featured-heading">Public work and software</h2>
      </div>
      <a class="text-link" href="{{ '/projects/' | relative_url }}">All projects <span aria-hidden="true">→</span></a>
    </div>

    <div class="featured-work-grid">
      <article class="featured-work">
        <p class="project-kicker">Lean 4 · Formalized mathematics</p>
        <h3><a href="https://github.com/hw4375-collab/Iris">LeanArabic</a></h3>
        <p>
          A feasibility project for representing a published fragment of Arabic pregroup grammar and producing
          machine-checkable grammatical derivations.
        </p>
      </article>
      <article class="featured-work">
        <p class="project-kicker">Lean 4 · AI reasoning verification</p>
        <h3><a href="https://github.com/hw4375-collab/FalconVerifer">FalconVerifier</a></h3>
        <p>
          A public verification prototype that separates model-generated interpretation from deterministic formal
          verification and records machine-checkable assurance artifacts.
        </p>
      </article>
    </div>

  </section>

  <section class="academic-section" aria-labelledby="news-heading">
    <div class="section-heading">
      <p class="eyebrow">Recent news</p>
      <h2 id="news-heading">Academic activity</h2>
    </div>
    <ol class="news-timeline">
      <li>
        <time datetime="2026-11">November 2026</time>
        <p>Delivered the talk <em>When Proof No Longer Means Understanding</em> at New York University Abu Dhabi.</p>
      </li>
      <li>
        <time datetime="2026">2026</time>
        <p>Began MSc studies in Interdisciplinary Data Science and Artificial Intelligence at New York University Abu Dhabi.</p>
      </li>
    </ol>
  </section>

  <section class="academic-contact" aria-labelledby="contact-heading">
    <div>
      <p class="eyebrow">Contact</p>
      <h2 id="contact-heading">Academic links</h2>
    </div>
    <div class="academic-link-grid">
      <a class="academic-link-card" href="https://github.com/hw4375-collab" rel="noopener noreferrer">
        <span>GitHub</span>
        <strong>hw4375-collab <span aria-hidden="true">↗</span></strong>
        <small>Public code and research software</small>
      </a>
      <a class="academic-link-card" href="{{ '/assets/pdf/Hongwei_Wang_Academic_CV.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer">
        <span>Academic CV</span>
        <strong>Download PDF <span aria-hidden="true">↗</span></strong>
        <small>Academic curriculum vitae</small>
      </a>
      <a class="academic-link-card" href="mailto:hw4375@nyu.edu">
        <span>NYU academic email</span>
        <strong>hw4375@nyu.edu <span aria-hidden="true">↗</span></strong>
        <small>For academic correspondence</small>
      </a>
    </div>
  </section>
</div>
