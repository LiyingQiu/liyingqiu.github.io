---
layout: page
permalink: /research/
title: Research
nav: true
nav_order: 2
---

# Publications

- **Personalization, consumer search, and algorithmic pricing**  
  Liying Qiu, Yan Huang, Param Vir Singh, Kannan Srinivasan  
  *Marketing Science*, 2025.

  <details markdown="1">
  <summary><strong>Abstract</strong></summary>

  Our study investigates the impact of product ranking systems on artificial intelligence (AI)-powered pricing algorithms. Specifically, we examine the effects of personalized and unpersonalized ranking systems on algorithmic pricing outcomes and consumer welfare. Our analysis reveals that personalized ranking systems, which rank products in decreasing order of consumers' utilities, may encourage higher prices charged by pricing algorithms, especially when consumers search for products sequentially on a third-party platform. This is because personalized ranking significantly reduces the ranking-mediated price elasticity of demand and thus incentives to lower prices. Conversely, unpersonalized ranking systems lead to significantly lower prices and greater consumer welfare. These findings suggest that even in the absence of price discrimination, personalization may not necessarily benefit consumers because pricing algorithms can undermine consumer welfare through higher prices. Thus, our study highlights the crucial role of ranking systems in shaping algorithmic pricing behaviors and consumer welfare.

  </details>

# Working Papers

- **A structural model of consumer search leveraging generative AI**  
  Liying Qiu, Param Vir Singh, Nitin Mehta, Kannan Srinivasan  
  Job Market Paper

  <details markdown="1">
  <summary><strong>Abstract</strong></summary>

  Independent sellers on digital platforms face a fundamental information disadvantage in making marketing decisions: while rich individual-level consumer search journeys, including queries, clicks, comparisons, and purchases, exist in clickstream data, platforms typically provide only aggregated metrics to sellers, such as query-level click shares and purchase shares. These aggregate measures are useful for monitoring performance but are insufficient for directly recovering the consumer preferences and search costs that drive search and purchase behavior. To bridge this information gap, we propose a lightweight and scalable agentic framework that transforms seller-visible aggregates into the specific underlying consumer preferences and search costs governing search and purchase decisions. The framework is designed for seller-side implementation: it relies only on information commonly available from platform dashboards and does not require sellers to observe individual-level search trajectories, estimate complex structural models, or maintain large-scale proprietary consumer databases. The framework first uses a feature-extractor agent based on general-purpose large language models (LLMs) to identify utility-relevant variables. These extracted variables, together with seller-visible aggregate measures, are then passed to a fine-tuned preference-generator agent that outputs consumer preferences and search costs. We fine-tune the preference-generator using detailed consumer search trajectories spanning 696 categories, 27,064 products, and 106,632 consumers. Our results show that the framework can recover consumer preferences and search costs in both future-period market holdouts and new product categories excluded from training, suggesting that the model learns a transferable mapping from aggregate dashboard information to consumer search primitives. Counterfactual experiments further demonstrate that sellers can make better marketing decisions using our framework than using either their own purchase data or dashboard data alone. Overall, this paper shows that generative AI can bridge the gap between rich platform-side consumer data and limited seller-side information, providing independent sellers with lightweight, scalable, interpretable, and decision-relevant insights for marketing decisions.

  </details>

- **Testing theoretical alignment in large language models: Evidence from insurance choices**  
  Liying Qiu, Param Vir Singh, Kannan Srinivasan  
  Major Revision at *Information Systems Research*

  <details markdown="1">
  <summary><strong>Abstract</strong></summary>

  Large Language Models (LLMs) are increasingly proposed as tools for simulating consumer decision-making in business research. While their outputs often resemble human choices, it remains unclear whether these decisions reflect coherent applications of formal decision theories or arise from alternative statistical regularities. This paper introduces the Theory-Based Chain of Verification (TBCV), a diagnostic framework to assess whether LLM-generated decisions are internally consistent with specified theoretical models. TBCV proceeds in two steps: inferring decision-theoretic parameters or heuristics, such as loss aversion, from model choices, and verifying whether those parameters predict consistent behavior under systematically perturbed scenarios. To illustrate, we apply TBCV to GPT-4-turbo using a dataset of real-world home insurance choices that are well explained by Prospect Theory, providing a strong benchmark for theoretical alignment. While GPT-4-turbo's choices approximate aggregate human patterns, 85% of its follow-up decisions violate the Prospect Theory parameters implied by its prior selections. In contrast, its behavior is highly consistent with Extremeness Aversion, systematically favoring compromise options across choice sets. TBCV offers a principled method to distinguish between different forms of alignment, enabling more rigorous use of LLMs in business research and economic modeling.

  </details>
