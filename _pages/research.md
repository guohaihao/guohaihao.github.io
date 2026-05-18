---
layout: page
title: "Research"
permalink: /research/
description:
nav: true
nav_order: 1
show_selected_wip: false
_styles: |
  .post-header {
    display: none;
  }
  .research-section {
    margin-top: 2rem;
  }
  .research-section:first-child {
    margin-top: 0;
  }
  .research-section h1 {
    text-align: center;
    margin-bottom: 1rem;
  }
  .research-list li {
    margin-bottom: 1.25rem;
  }
  .research-list details {
    margin-top: 0.5rem;
  }
---

<section class="research-section">
<h3>Research Focus</h3>

I study why creative products succeed and how creators can use innovation, borrowing, and generative AI to design content that resonates rather than disappears.

My work combines economics, statistics, and multi-modal machine learning to understand diffusion and performance outcomes in music, online video, and video games.

<details>
  <summary><strong>Details</strong></summary>
  Entertainment markets differ fundamentally from traditional product markets because creative goods are high-dimensional and audience preferences are largely implicit—people know they like a song or a video but cannot easily explain why. My research develops interpretable, theory-guided representations of creative content and embeds them into a historical style space to measure innovation and borrowing relative to past successful works. On the supply side, I study how creators strategically position themselves in style space based on goals (entry, ranking, persistence) and identity (incumbent vs. entrant). I use counterfactual experiments and generative AI pipelines to evaluate how creative decisions affect real outcomes, offering guidance at a moment when AI enables large-scale creation but amplifies noise and uncertainty.
</details>
</section>

<section class="research-section">
<h3>Job Market Paper</h3>

<ol class="research-list">
  <li>
    <strong>Haihao Guo</strong>, P. B. (Seethu) Seetharaman, Yingkang Xie. "Echoes from the Past: Music Design Inspired by Past Hits and Its GenAI Application."
    <details>
      <summary>Abstract</summary>
      A central challenge in music design is determining when and how a song should remain rooted in past musical styles or innovate beyond them to achieve commercial success. This paper proposes a novel data-driven framework, grounded in canonical music theory, to guide the design of commercially successful music by locating a song's optimal position relative to past musical styles and translating it into concrete songwriting choices. We implement the framework in three steps. First, we use deep learning models integrated with music-theoretic analysis to translate audio into theory-grounded features of melody, harmony, and rhythm that can guide songwriting decisions. Second, we use 24,618 Billboard Hot 100 songs from 1958--2017 to recover persistent historical styles. Third, we position 29,331 songs from 2019--2025 relative to these styles by constructing measures of distance and concentration across melody, harmony, and rhythm. We then train an XGBoost model to predict Billboard entry and show that, using only these six interpretable historical-positioning variables, the model outperforms high-dimensional audio-embedding benchmarks with more than 4,000 variables in out-of-sample prediction, while also providing actionable guidance for song redesign. We find that contemporary songs are more likely to enter the Billboard Hot 100 when they follow a close-fusion strategy: staying close to historically successful styles while blending across multiple historical styles rather than closely mirroring any single one. To translate these insights into design, we build a retrieval-augmented generation pipeline that converts model-implied optimal positions relative to historical styles into musician-ready design briefs and GenAI prompts. Finally, we validate this pipeline through a generative AI redesign application using five contemporary unpopular songs across five genres. A lab experiment shows that model-guided edits can improve listener responses, especially in production-driven genres, although AI aversion and vocal familiarity dampen acceptance of these changes. Together, the results show that historical-style positioning can make music design more measurable and actionable by providing concrete guidance for human musicians and implementable instructions for generative AI systems.
    </details>
  </li>
</ol>
</section>

<section class="research-section">
<h3>Working Papers</h3>

<ol class="research-list" start="2">
  <li>
    <strong>Haihao Guo</strong>, P. B. (Seethu) Seetharaman. <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5492026" target="_blank" rel="noopener">"Instant versus Sustained Diffusion of YouTube Videos: A Multimodal Analysis of Content Characteristics."</a>
    <!-- <div style="margin-top: 0.5rem;">• Reject and Resubmit, <strong>Journal of Marketing Research</strong>.</div> -->
    <details>
      <summary>Abstract</summary>
      Despite an emerging body of research on online content diffusion, there has been little to no investigation of how content characteristics drive distinct temporal diffusion patterns. This study addresses this gap by investigating two primary questions: (1) What are the main diffusion patterns of online videos? (2) Which specific content characteristics influence these patterns? We estimate the Bass diffusion model on a random sample of one million YouTube videos and identify 42,046 videos with highly predictable temporal diffusion patterns. Using K-means clustering, we find that these videos fall under two broad types: (1) instant diffusion (rapid spike followed by quick decline), (2) sustained diffusion (steady growth over time). Guided by Dual Process Theory, we apply state-of-the-art machine learning methods—(1) Spotify audio analysis, (2) Whisper transcription, (3) Sentence-BERT embeddings, and (4) Topic modeling—to extract audio, visual, and textual features corresponding to System 1 (fast, emotional) versus System 2 (slow, analytical) cognitive processes. Logistic regression analyses reveal that instant diffusion is associated with high-energy, emotionally engaging content (System 1), whereas sustained diffusion is associated with informational density and complexity (System 2). Viewer engagement metrics (comment complexity, delayed sharing, longer watch times) further validate these cognitive distinctions. Our findings can be used by YouTube content creators to design video content that is tailored to achieve specific temporal viewership objectives.
    </details>
  </li>
  <li>
    <strong>Haihao Guo</strong>, Baojun Jiang, P. B. (Seethu) Seetharaman. "When Should Developers Partner with a Publisher? Theory and Evidence from Steam."
    <details>
      <summary>Abstract</summary>
      Independent game developers must choose whether to self-publish or partner with a publisher that can amplify demand through marketing. We build an analytical model in which the developer's effort is unobservable and the integration choice (partnering vs. self-publishing) is endogenous. Publisher marketing raises the marginal return to quality but weakens effort incentives under standard revenue sharing. We show that equilibrium price, effort, and mode are characterized by two cutoff values—one in the publisher's marketing capability and one in the developer's quality-to-cost ratio. The developer will self-publish only when both its quality-to-cost ratio and the publisher's marketing capability are below some threshold levels; otherwise it will partner with the publisher. We show that profit-sharing contracts expand the region where partnerships are feasible and efficient by better aligning incentives. We test the model's implications using the Steam PC games market (2015--2025), combining mode choice with price and performance outcomes and correcting for selection. The evidence is consistent with the theory: publisher-backed titles—especially when publisher capability is high—exhibit higher launch prices and stronger first-year performance, with patterns that map to the predicted thresholds. This paper offers actionable guidance on when developers should partner, how publishers should set terms, and how platforms should design policies that balance discovery with incentives.
    </details>
  </li>
</ol>
</section>

{% if page.show_selected_wip %}
<section class="research-section">
<h3>Selected Work in Progress</h3>

<ol class="research-list" start="4">
  <li><strong>Haihao Guo</strong>, P. B. (Seethu) Seetharaman, Baojun Jiang. "Dynamic Reference Point in Price: Evidence from Video Games Market."</li>
  <li><strong>Haihao Guo</strong>, P. B. (Seethu) Seetharaman. "Accelerating Social Science Research with DeepWalk Algorithm."</li>
  <li><strong>Haihao Guo</strong>, P. B. (Seethu) Seetharaman. "Impact of Audio vs. Visual on Diffusion of Music Videos."</li>
</ol>
</section>
{% endif %}
