---
layout: page
permalink: /research/
title: Research
nav: true
nav_order: 1
---

<!-- prettier-ignore-start -->

<style>
  .research-page {
    max-width: 900px;
    margin: 0 auto;
  }

  .research-intro {
    margin-bottom: 2.4rem;
    font-size: 1.02rem;
    line-height: 1.65;
    color: var(--global-text-color);
  }

  .research-section {
    margin-top: 2.4rem;
    margin-bottom: 1.2rem;
  }

  .research-section-title {
    font-size: 1.55rem;
    font-weight: 650;
    margin-bottom: 1rem;
    padding-bottom: 0.45rem;
    border-bottom: 1px solid var(--global-divider-color);
    color: var(--global-theme-color);
  }

  .paper-card {
    margin-bottom: 1.6rem;
    padding: 1.45rem 1.6rem;
    border: 1px solid var(--global-divider-color);
    border-radius: 14px;
    background: var(--global-bg-color);
    box-shadow: 0 4px 14px rgba(0, 0, 0, 0.04);
  }

  .paper-card:hover {
    box-shadow: 0 7px 22px rgba(0, 0, 0, 0.07);
    transform: translateY(-1px);
    transition: box-shadow 0.18s ease, transform 0.18s ease;
  }

  .paper-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    gap: 1rem;
    margin-bottom: 0.45rem;
  }

  .paper-title {
    font-weight: 700;
    font-size: 1.08rem;
    line-height: 1.4;
    margin: 0;
  }

  .paper-badge {
    flex-shrink: 0;
    display: inline-block;
    padding: 0.25rem 0.6rem;
    border: 1px solid var(--global-theme-color);
    border-radius: 999px;
    color: var(--global-theme-color);
    font-size: 0.78rem;
    font-weight: 650;
    line-height: 1.2;
    white-space: nowrap;
  }

  .paper-authors {
    margin-bottom: 0.25rem;
    line-height: 1.55;
  }

  .paper-venue {
    margin-bottom: 0.9rem;
    color: var(--global-text-color-light);
    line-height: 1.5;
  }

  .paper-venue em {
    color: var(--global-text-color);
  }

  .abstract-details {
    margin-top: 0.75rem;
  }

  .abstract-toggle {
    display: inline-flex;
    align-items: center;
    gap: 0.35rem;
    padding: 0.32rem 0.75rem;
    border: 1px solid var(--global-theme-color);
    border-radius: 999px;
    color: var(--global-theme-color);
    font-weight: 650;
    font-size: 0.92rem;
    cursor: pointer;
    width: fit-content;
    user-select: none;
    list-style: none;
    transition: background-color 0.15s ease, color 0.15s ease, box-shadow 0.15s ease;
  }

  .abstract-toggle:hover {
    background-color: rgba(0, 86, 179, 0.08);
    text-decoration: none;
  }

  .abstract-toggle:focus {
    outline: none;
  }

  .abstract-toggle:focus-visible {
    box-shadow: 0 0 0 3px rgba(0, 86, 179, 0.25);
  }

  .abstract-toggle::-webkit-details-marker {
    display: none;
  }

  .abstract-toggle::before {
    content: "▸";
    font-size: 0.85rem;
  }

  .abstract-details[open] .abstract-toggle::before {
    content: "▾";
  }

  .abstract-text {
    margin-top: 1rem;
    padding: 1rem 1.1rem;
    border-left: 3px solid var(--global-theme-color);
    background: rgba(0, 86, 179, 0.04);
    border-radius: 0 10px 10px 0;
    line-height: 1.65;
    font-size: 0.96rem;
  }

  @media (max-width: 700px) {
    .paper-header {
      display: block;
    }

    .paper-badge {
      margin-top: 0.65rem;
    }

    .paper-card {
      padding: 1.25rem;
    }
  }
</style>

<div class="research-page">

<p class="research-intro">
My research examines how artificial intelligence reshapes managerial decision-making, consumer search, and platform markets. I combine structural modeling, machine learning, reinforcement learning, and generative AI to study how firms, platforms, and policymakers can make better decisions in digital environments.
</p>

<div class="research-section">
  <h2 class="research-section-title">Publications</h2>
</div>

<div class="paper-card">

  <div class="paper-header">
    <h3 class="paper-title">Personalization, Consumer Search, and Algorithmic Pricing</h3>
    <span class="paper-badge">Published</span>
  </div>

  <div class="paper-authors">
    Liying Qiu, Yan Huang, Param Vir Singh, Kannan Srinivasan
  </div>

  <div class="paper-venue">
    <em>Marketing Science</em>, 2025.
  </div>

  <details class="abstract-details">
    <summary class="abstract-toggle">Abstract</summary>

    <div class="abstract-text">
      Our study investigates the impact of product ranking systems on artificial intelligence (AI)-powered pricing algorithms. Specifically, we examine the effects of personalized and unpersonalized ranking systems on algorithmic pricing outcomes and consumer welfare. Our analysis reveals that personalized ranking systems, which rank products in decreasing order of consumers' utilities, may encourage higher prices charged by pricing algorithms, especially when consumers search for products sequentially on a third-party platform. This is because personalized ranking significantly reduces the ranking-mediated price elasticity of demand and thus incentives to lower prices. Conversely, unpersonalized ranking systems lead to significantly lower prices and greater consumer welfare. These findings suggest that even in the absence of price discrimination, personalization may not necessarily benefit consumers because pricing algorithms can undermine consumer welfare through higher prices. Thus, our study highlights the crucial role of ranking systems in shaping algorithmic pricing behaviors and consumer welfare.
    </div>
  </details>

</div>

<div class="research-section">
  <h2 class="research-section-title">Working Papers</h2>
</div>

<div class="paper-card">

  <div class="paper-header">
    <h3 class="paper-title">A Structural Model of Consumer Search Leveraging Generative AI</h3>
    <span class="paper-badge">Job Market Paper</span>
  </div>

  <div class="paper-authors">
    Liying Qiu, Param Vir Singh, Nitin Mehta, Kannan Srinivasan
  </div>

  <div class="paper-venue">
    Job Market Paper
  </div>

  <details class="abstract-details">
    <summary class="abstract-toggle">Abstract</summary>

    <div class="abstract-text">
      Independent sellers on digital platforms face a fundamental information disadvantage in making marketing decisions: while rich individual-level consumer search journeys, including queries, clicks, comparisons, and purchases, exist in clickstream data, platforms typically provide only aggregated metrics to sellers, such as query-level click shares and purchase shares. These aggregate measures are useful for monitoring performance but are insufficient for directly recovering the consumer preferences and search costs that drive search and purchase behavior. To bridge this information gap, we propose a lightweight and scalable agentic framework that transforms seller-visible aggregates into the specific underlying consumer preferences and search costs governing search and purchase decisions. The framework is designed for seller-side implementation: it relies only on information commonly available from platform dashboards and does not require sellers to observe individual-level search trajectories, estimate complex structural models, or maintain large-scale proprietary consumer databases. The framework first uses a feature-extractor agent based on general-purpose large language models (LLMs) to identify utility-relevant variables. These extracted variables, together with seller-visible aggregate measures, are then passed to a fine-tuned preference-generator agent that outputs consumer preferences and search costs. We fine-tune the preference-generator using detailed consumer search trajectories spanning 696 categories, 27,064 products, and 106,632 consumers. Our results show that the framework can recover consumer preferences and search costs in both future-period market holdouts and new product categories excluded from training, suggesting that the model learns a transferable mapping from aggregate dashboard information to consumer search primitives. Counterfactual experiments further demonstrate that sellers can make better marketing decisions using our framework than using either their own purchase data or dashboard data alone. Overall, this paper shows that generative AI can bridge the gap between rich platform-side consumer data and limited seller-side information, providing independent sellers with lightweight, scalable, interpretable, and decision-relevant insights for marketing decisions.
    </div>
  </details>

</div>

<div class="paper-card">

  <div class="paper-header">
    <h3 class="paper-title">Testing Theoretical Alignment in Large Language Models: Evidence from Insurance Choices</h3>
    <span class="paper-badge">Major Revision</span>
  </div>

  <div class="paper-authors">
    Liying Qiu, Param Vir Singh, Kannan Srinivasan
  </div>

  <div class="paper-venue">
    Major Revision at <em>Information Systems Research</em>
  </div>

  <details class="abstract-details">
    <summary class="abstract-toggle">Abstract</summary>

    <div class="abstract-text">
      Large Language Models (LLMs) are increasingly proposed as tools for simulating consumer decision-making in business research. While their outputs often resemble human choices, it remains unclear whether these decisions reflect coherent applications of formal decision theories or arise from alternative statistical regularities. This paper introduces the Theory-Based Chain of Verification (TBCV), a diagnostic framework to assess whether LLM-generated decisions are internally consistent with specified theoretical models. TBCV proceeds in two steps: inferring decision-theoretic parameters or heuristics, such as loss aversion, from model choices, and verifying whether those parameters predict consistent behavior under systematically perturbed scenarios. To illustrate, we apply TBCV to GPT-4-turbo using a dataset of real-world home insurance choices that are well explained by Prospect Theory, providing a strong benchmark for theoretical alignment. While GPT-4-turbo's choices approximate aggregate human patterns, 85% of its follow-up decisions violate the Prospect Theory parameters implied by its prior selections. In contrast, its behavior is highly consistent with Extremeness Aversion, systematically favoring compromise options across choice sets. TBCV offers a principled method to distinguish between different forms of alignment, enabling more rigorous use of LLMs in business research and economic modeling.
    </div>
  </details>

</div>

</div>

<!-- prettier-ignore-end -->
