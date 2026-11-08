---
layout: page
title: Research
permalink: /research/
description: Research interests at the intersection of mathematical foundations, formal methods, and AI reasoning.
nav: true
nav_order: 2
---

<div class="research-page">
  <header class="research-intro" aria-labelledby="research-overview-title">
    <p class="eyebrow">Research</p>
    <h1 id="research-overview-title">Mathematical foundations for reliable reasoning</h1>
    <p>
      My research interests concern the representation, transformation, and verification of mathematical meaning within
      formal reasoning systems. The directions below describe research interests and ongoing exploration, not completed
      results or established claims.
    </p>
    <div class="research-question">
      <span>Guiding question</span>
      <p>How can mathematical meaning be represented, transformed, and verified within formal reasoning systems?</p>
    </div>
  </header>

  <div class="research-layout">
    <aside class="research-index" aria-label="Research section index">
      <p>On this page</p>
      <nav>
        <a href="#mathematical-foundations"><span>01</span> Mathematical Foundations</a>
        <a href="#ai-for-formal-mathematics"><span>02</span> AI for Formal Mathematics</a>
        <a href="#formal-methods-for-trustworthy-ai"><span>03</span> Formal Methods for Trustworthy AI</a>
        <a href="#research-philosophy"><span>∴</span> Research Philosophy</a>
      </nav>
    </aside>

    <div class="research-sections">
      <section id="mathematical-foundations" class="research-direction" aria-labelledby="foundations-title">
        <p class="direction-number">01</p>
        <h2 id="foundations-title">Mathematical Foundations</h2>
        <p class="direction-subtitle">Type Theory, Homotopy Theory, and Higher Category Theory</p>
        <p>
          I am interested in the structural foundations of mathematics, particularly dependent type theory, homotopy type
          theory, and higher category theory. These subjects provide mathematical languages for studying objects,
          constructions, proofs, and equivalences.
        </p>
        <p>
          An important aspect of my current work is understanding how such structures can be represented within proof
          assistants, including Lean 4 and Cubical Agda. I am particularly interested in the role of paths, equivalences,
          and higher-dimensional structures in formal mathematical reasoning.
        </p>
        <ul class="topic-list topic-list--large" aria-label="Mathematical Foundations topics">
          <li>Dependent Type Theory</li>
          <li>Homotopy Type Theory</li>
          <li>Cubical Type Theory</li>
          <li>Higher Category Theory</li>
          <li>Formalized Homotopy Theory</li>
        </ul>
      </section>

      <section id="ai-for-formal-mathematics" class="research-direction" aria-labelledby="formal-mathematics-title">
        <p class="direction-number">02</p>
        <h2 id="formal-mathematics-title">AI for Formal Mathematics</h2>
        <p class="direction-subtitle">Autoformalization and Semantic Faithfulness</p>
        <p>
          Modern proof assistants can verify formal mathematical proofs with a high degree of logical precision. However,
          the correctness of a formal proof does not, by itself, establish that the formalized statement expresses the
          intended mathematical meaning. This distinction becomes especially important when artificial intelligence is
          used to translate mathematical language into formal representations.
        </p>
        <div class="mathematical-process" aria-label="Natural language through machine verification">
          $$
          \text{Natural Language}
          \longrightarrow
          \text{Mathematical Language}
          \longrightarrow
          \text{Formal Code}
          \longrightarrow
          \text{Machine Verification}.
          $$
        </div>
        <p>
          I am interested in how to evaluate and improve the faithfulness of these transformations. Formal correctness
          asks whether a generated proof satisfies the rules of a formal system; semantic faithfulness asks whether the
          generated formal statement accurately represents the intended mathematical problem.
        </p>
        <p>
          I am exploring how mathematical structure, type systems, and formal verification can contribute to more
          reliable AI-assisted mathematical reasoning.
        </p>
        <ul class="topic-list topic-list--large" aria-label="AI for Formal Mathematics topics">
          <li>Mathematical Autoformalization</li>
          <li>Semantic Faithfulness</li>
          <li>Formal Verification of AI-Generated Proofs</li>
          <li>Mathematical Language Representation</li>
          <li>Human–AI Collaboration in Mathematics</li>
        </ul>
      </section>

      <section id="formal-methods-for-trustworthy-ai" class="research-direction" aria-labelledby="trustworthy-ai-title">
        <p class="direction-number">03</p>
        <h2 id="trustworthy-ai-title">Formal Methods for Trustworthy AI</h2>
        <p class="direction-subtitle">Reliable Reasoning and Verified AI Systems</p>
        <p>
          Beyond mathematical theorem proving, I am interested in how formal methods can support the development of
          trustworthy artificial intelligence. Formal specifications can describe properties that an AI system is expected
          to satisfy, while verification techniques can provide evidence that specific implementations or behaviors
          satisfy those properties.
        </p>
        <p>
          I am interested in exploring these methods in the context of AI reasoning systems and autonomous agents.
          Potential applications include the verification of decision-making procedures, constraints on AI-agent behavior,
          and the formal specification of safety-critical workflows.
        </p>
        <p>
          This direction aims to connect mathematical foundations with practical challenges in reliable AI.
        </p>
        <ul class="topic-list topic-list--large" aria-label="Formal Methods for Trustworthy AI topics">
          <li>Formal Specification</li>
          <li>AI Reasoning Verification</li>
          <li>Verified AI Agents</li>
          <li>Type-Theoretic Approaches to Reliability</li>
          <li>Formal Methods for Decision-Making Systems</li>
        </ul>
      </section>

      <section id="research-philosophy" class="research-philosophy" aria-labelledby="philosophy-title">
        <p class="eyebrow">Research philosophy</p>
        <h2 id="philosophy-title">Verification in relation to meaning</h2>
        <p>
          I view formal verification not only as a technique for establishing logical correctness, but also as part of a
          broader effort to understand the relationship between mathematical structures, their representations, and their
          intended meaning. My long-term interest is in mathematical frameworks that make machine reasoning more
          transparent, interpretable, and verifiable.
        </p>
      </section>
    </div>

  </div>
</div>
