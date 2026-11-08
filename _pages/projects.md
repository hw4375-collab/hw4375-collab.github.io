---
layout: page
title: Projects
permalink: /projects/
description: Public research software and formalization work.
nav: true
nav_order: 4
---

<div class="projects-page">
  <header class="page-intro" aria-labelledby="projects-title">
    <p class="eyebrow">Projects</p>
    <h1 id="projects-title">Public research software and formalization work</h1>
    <p>
      These projects link only to public repositories and documentation. Their descriptions summarize the available
      materials and do not claim completed research results beyond them.
    </p>
  </header>

  <section class="project-section" aria-labelledby="current-research-title">
    <div class="section-heading">
      <p class="eyebrow">Current research</p>
      <h2 id="current-research-title">Formal representations</h2>
    </div>
    <div class="project-grid">
      <article class="project-card">
        <p class="project-kicker">Lean 4 · Formal language</p>
        <h3><a href="https://github.com/hw4375-collab/Iris">LeanArabic <span aria-hidden="true">↗</span></a></h3>
        <p>
          A Lean 4 feasibility project for representing a published fragment of Arabic pregroup grammar and producing
          machine-checkable grammatical derivations. The public repository documents both its proof-producing reducer
          baseline and its current scope limits.
        </p>
        <ul class="topic-list" aria-label="LeanArabic tools and fields">
          <li>Lean 4</li>
          <li>Pregroup grammar</li>
          <li>Proof-producing reduction</li>
        </ul>
      </article>
    </div>
  </section>

  <section class="project-section" aria-labelledby="research-software-title">
    <div class="section-heading">
      <p class="eyebrow">Research software</p>
      <h2 id="research-software-title">Verification-oriented tools</h2>
    </div>
    <div class="project-grid">
      <article class="project-card">
        <p class="project-kicker">Lean 4 · AI reasoning verification</p>
        <h3><a href="https://github.com/hw4375-collab/FalconVerifer">FalconVerifier <span aria-hidden="true">↗</span></a></h3>
        <p>
          A public software project for checking formalized reasoning steps with Lean 4 and recording an assurance
          trace. Its documentation explicitly distinguishes verified, refuted, unknown, and ill-formed outcomes, and
          includes a semantic-faithfulness audit for certain LLM translations.
        </p>
        <ul class="topic-list" aria-label="FalconVerifier tools and fields">
          <li>Lean 4</li>
          <li>Assurance traces</li>
          <li>Semantic-faithfulness audit</li>
        </ul>
      </article>
      <article class="project-card">
        <p class="project-kicker">Kotlin Multiplatform · Lean 4</p>
        <h3><a href="https://github.com/hw4375-collab/prooflens-kmp">ProofLens <span aria-hidden="true">↗</span></a></h3>
        <p>
          A Kotlin Multiplatform application for proposing and checking Lean 4 proofs across Android, desktop, and web
          targets. The public repository documents a client/server design in which the Lean kernel is the proof-checking
          authority.
        </p>
        <ul class="topic-list" aria-label="ProofLens tools and fields">
          <li>Kotlin Multiplatform</li>
          <li>Lean 4</li>
          <li>Proof checking</li>
        </ul>
      </article>
    </div>
  </section>

  <section class="project-section" aria-labelledby="earlier-work-title">
    <div class="section-heading">
      <p class="eyebrow">Selected earlier work</p>
      <h2 id="earlier-work-title">Formal-verification experiments</h2>
    </div>
    <div class="project-grid">
      <article class="project-card">
        <p class="project-kicker">Lean 4 · Algebraic topology</p>
        <h3><a href="https://github.com/chaos-butterfly-tech/CB-Attractor">CB-Attractor <span aria-hidden="true">↗</span></a></h3>
        <p>
          A public Lean 4 project for formal-verification experiments on ReLU neural-network decision regions, alongside
          a formalization component in algebraic topology. The repository identifies Hongwei Wang in its project context;
          this description does not make claims beyond the repository's public documentation.
        </p>
        <ul class="topic-list" aria-label="CB-Attractor tools and fields">
          <li>Lean 4</li>
          <li>Algebraic topology</li>
          <li>Neural-network decision regions</li>
        </ul>
      </article>
    </div>
    <p class="section-note">
      Cubical Agda remains part of my current research interests and tools; no standalone public project is listed until
      its materials have been reviewed and approved.
    </p>
  </section>
</div>
