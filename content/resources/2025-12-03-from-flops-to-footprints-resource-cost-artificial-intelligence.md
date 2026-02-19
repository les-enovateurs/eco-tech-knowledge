---
title: "From FLOPs to Footprints: The Resource Cost of Artificial Intelligence"
publication_date: 2025-12-03
authors:
  - title: Sophia Falk
    organization: bonn-university/_index
  - title: Nicholas Kluge Corrêa
    organization: bonn-university/_index
  - title: Sasha Luccioni
    organization: hugging-face/_index
  - title: Lisa Biber-Freudenberger
    organization: bonn-university/_index
  - title: Aimee van Wynsberghe
    organization: bonn-university/_index
categories:
  - resource-depletion/_index
  - sustainable/_index
tags:
  - sustainable AI
  - resource cost
  - AI computation
  - AI model training
  - FLOPs
  - GPU
  - material footprint
  - hardware
resource_type: article
summary: |
  As computational demands continue to rise, assessing the environmental footprint of AI requires moving beyond energy and water consumption to include the material demands of specialized hardware. This study quantifies the material footprint of AI training by linking computational workloads to physical hardware needs.

  The elemental composition of the Nvidia A100 SXM 40 GB GPU was analyzed using inductively coupled plasma optical emission spectroscopy, identifying 32 elements. Results show that AI hardware consists of about 90% heavy metals and only trace amounts of precious metals — copper, iron, tin, silicon, and nickel dominate by mass.

  Using a multi-step methodology integrating these measurements with computational throughput per GPU across varying lifespans, the study finds that training GPT-4 requires between 1,174 and 8,800 A100 GPUs depending on Model FLOPs Utilization (MFU) and hardware lifespan — corresponding to the extraction and eventual disposal of up to 7 tons of toxic elements.

  Combined software and hardware optimization strategies can significantly reduce material demands: increasing MFU from 20% to 60% lowers GPU requirements by 67%, extending lifespan from 1 to 3 years yields comparable savings, and implementing both measures together reduces GPU needs by up to 93%.

  The study highlights that incremental performance gains — such as those between GPT-3.5 and GPT-4 — come at disproportionately high material costs, and underscores the necessity of incorporating material resource considerations into discussions of AI scalability.
source_url: https://arxiv.org/abs/2512.04142
source_document: https://arxiv.org/pdf/2512.04142
source_organizations:
  - bonn-university/_index
  - hugging-face/_index
language: en
doi: https://doi.org/10.48550/arXiv.2512.04142
---

