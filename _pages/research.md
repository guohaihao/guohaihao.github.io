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
    <strong>Haihao Guo</strong>, Yingkang Xie, P. B. (Seethu) Seetharaman. "Data-Driven Product Design Guided by Past Successes: An Application to Music with GenAI."
    <div style="margin-top: 0.5rem;">Submitted to <strong>Journal of Marketing Research</strong>.</div>
    <details>
      <summary>Abstract</summary>
      New product design requires balancing aspects of past successes versus innovating beyond them, especially for creative products (e.g., music). However, conventional product-design approaches, such as conjoint analysis, are difficult to implement in the music context. This research proposes an interpretable data-driven framework for successful music design, which locates an optimal position for a new song in relation to past commercial hits. This framework applies deep learning with music-theory to translate song audio into interpretable features in three dimensions (melody, harmony, and rhythm) and trace the evolution of historically successful musical styles. Contemporary songs are then positioned relative to these styles using distance and concentration measures. Using only six such measures, the proposed model outperforms benchmark models which use more than 4,000 audio-embedding variables in predicting commercial success. Results show that contemporary songs are more successful when they stay close to historical styles while also blending across them. A retrieval-augmented generation pipeline translates these insights into design guidance. A laboratory experiment using five pairs of original versus model-guided GenAI-edited songs shows positive marginal effects of guided edits on listeners’ responses. This study provides musicians and firms with a systematic way to draw on past hits to augment new music design.
    </details>
  </li>
</ol>
</section>

<section class="research-section">
<h3>Working Papers</h3>

<ol class="research-list" start="2">
  <li>
    <strong>Haihao Guo</strong>, P. B. (Seethu) Seetharaman. <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5492026" target="_blank" rel="noopener">"Instant versus Sustained Diffusion of YouTube Videos: A Multimodal Analysis of Content Characteristics."</a>
    <div style="margin-top: 0.5rem;">Reject and Resubmit at <strong>Journal of Marketing Research</strong>.</div>
    <details>
      <summary>Abstract</summary>
      Despite an emerging body of research on online content diffusion, there has been little to no investigation of how content characteristics drive distinct temporal diffusion patterns. This study addresses this gap by investigating two primary questions: (1) What are the main diffusion patterns of online videos? (2) Which specific content characteristics influence these patterns? We estimate the Bass diffusion model on a random sample of one million YouTube videos and identify 42,046 videos with highly predictable temporal diffusion patterns. Using K-means clustering, we find that these videos fall under two broad types: (1) instant diffusion (rapid spike followed by quick decline), (2) sustained diffusion (steady growth over time). Guided by Dual Process Theory, we apply state-of-the-art machine learning methods—(1) Spotify audio analysis, (2) Whisper transcription, (3) Sentence-BERT embeddings, and (4) Topic modeling—to extract audio, visual, and textual features corresponding to System 1 (fast, emotional) versus System 2 (slow, analytical) cognitive processes. Logistic regression analyses reveal that instant diffusion is associated with high-energy, emotionally engaging content (System 1), whereas sustained diffusion is associated with informational density and complexity (System 2). Viewer engagement metrics (comment complexity, delayed sharing, longer watch times) further validate these cognitive distinctions. Our findings can be used by YouTube content creators to design video content that is tailored to achieve specific temporal viewership objectives.
    </details>
  </li>
  <li>
    <strong>Haihao Guo</strong>, Baojun Jiang, P. B. (Seethu) Seetharaman. <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7124478" target="_blank" rel="noopener">"Self-Publishing versus Publisher-Backed Publishing in Digital Game Distribution."</a>
    <div style="margin-top: 0.5rem;">Submitted to <strong>Marketing Science</strong>.</div>
    <details>
      <summary>Abstract</summary>
      Independent game developers must choose whether to self-publish or work with a publisher that can amplify demand. We build an analytical model in which the developer's effort is unobservable and the publishing mode (self-publishing versus publisher-backed publishing) is endogenous. Publisher commercialization capability raises the marginal return to quality, but standard revenue sharing weakens the developer's incentive to invest in quality-enhancing effort. We show that equilibrium price, developer effort, and publishing mode are characterized by two cutoffs: one for the publisher's capability and another for the game's baseline quality relative to development cost. The developer self-publishes only when both publisher capability and baseline quality relative to development cost are below their corresponding cutoffs; otherwise, publisher-backed publishing is sustained. Using profit sharing as a diagnostic benchmark, we show that some publisher-backed releases fail to arise under revenue sharing because of incentive misalignment rather than insufficient surplus creation. We further show that publisher commercialization capability is more effective when it complements game quality rather than merely expands exposure, and that revenue sharing can distort not only developer effort but also game selection. We provide suggestive descriptive evidence from the Steam PC games market during 2015--2025. The patterns are directionally consistent with the theory: publisher-backed games are associated with higher launch prices and sales, and these associations appear more pronounced for higher-capability publishers. The paper offers implications for developers' publishing-mode choices and publishers' contract design in digital creative markets.
    </details>
  </li>
  <li>
    <strong>Haihao Guo</strong>, Jino Lu, Yingkang Xie, Nick Argyres, and Seethu Seetharaman. “The Science We Miss: AI for Connecting Ideas and Researchers across Communities.”
    <div style="margin-top: 0.5rem;">Submitted to <strong>Organization Science</strong>.</div>
  </li>
</ol>
</section>

{% if page.show_selected_wip %}

<section class="research-section">
<h3>Selected Work in Progress</h3>

<ol class="research-list" start="5">
  <li><strong>Haihao Guo</strong>, P. B. (Seethu) Seetharaman, Baojun Jiang. "Dynamic Reference Point in Price: Evidence from Video Games Market."</li>
  <li><strong>Haihao Guo</strong>, P. B. (Seethu) Seetharaman, Yingkang Xie. "Generative AI Disclosure and Belief Updating in Music Evaluation."</li>
  <li><strong>Haihao Guo</strong>, P. B. (Seethu) Seetharaman, Yingkang Xie. "Recombination and Innovation in Popular Music: The Creative Potential of Generative AI."</li>
</ol>
</section>
{% endif %}
