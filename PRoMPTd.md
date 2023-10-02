---
layout: page
title: "Instance Needs More Care: Rewriting Prompts for Instances Yields Better Zero-Shot Performance"
---

Enabling large language models (LLMs) to perform tasks in zero-shot has been an appealing goal owing to its labor-saving (i.e., requiring no task-specific annotations); as such, zero-shot prompting approaches also enjoy better task generalizability. To improve LLMs' zero-shot performance, prior work has focused on devising more effective task instructions (e.g., "let's think step by step"). However, we argue that, in order for an LLM to solve them correctly in zero-shot, individual test instances need more carefully designed and customized instructions. To this end, we propose an approach that rewrites the task prompt for each individual test input to be more specific, unambiguous, and complete, so as to provide better guidance to the task LLM. We evaluated our approach on eight datasets covering tasks including arithmetics, logical reasoning, and code generation, using GPT-4 as the task LLM. Notably, our approach achieves an absolute improvement of around 10% on the complex MATH dataset and 5% on the code generation task on HumanEval, outperforming conventional zero-shot methods. In addition, we also showed that the rewritten prompt can provide better interpretability of how the LLM resolves each test instance, which can potentially be leveraged as a defense mechanism against adversarial prompting. [The source code and dataset can be obtained here](https://github.com/salokr/PRoMPTd).

<figure>
  <img src="/images/image1.jpg" alt="Image Description">
  <figcaption>Your caption here</figcaption>
</figure>

| Header 1 | Header 2 |
|----------|----------|
| Data 1A  | Data 1B  |
| Data 2A  | Data 2B  |
