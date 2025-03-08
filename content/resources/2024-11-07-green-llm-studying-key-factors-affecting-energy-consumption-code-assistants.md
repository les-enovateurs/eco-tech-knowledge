---
title: "Green LLM: Studying Key Factors Affecting Energy Consumption of Code Assistants"
publication_date: 2024-11-07
authors:
  - title: Tristan Coignion
    organization: inria/_index
  - title: Clément Quinton
    organization: inria/_index  
  - title: Romain Rouvoy
    organization: inria/_index
categories:
  - ai/_index
tags:
  - energy consumption
  - code assistants
  - green AI
  - sustainability
  - large language models
resource_type: research
summary: |
  In recent years,Large Language Models (LLMs) have significantly improved in generating high-quality code, enabling their integration into developers' Integrated Development Environments (IDEs) as code assistants. 
  
  These assistants, such as GitHub Copilot, deliver real-time code suggestions and can greatly enhance developers' productivity. However, the environmental impact of these tools, in particular their energy consumption, remains a key concern. 
  
  This paper investigates the energy consumption of LLM-based code assistants by simulating developer interactions with GitHub Copilot and analyzing various configuration factors. We collected a dataset of development traces from 20 developers and conducted extensive software project development simulations to measure energy usage under different scenarios. 
  
  Our findings reveal that the energy consumption and performance of code assistants are influenced by various factors, such as the number of concurrent developers, model size, quantization methods, and the use of streaming. Notably, a substantial portion of generation requests made by GitHub Copilot is either canceled or rejected by developers, indicating a potential area for reducing wasted computations.
  
  Based on these findings, we share actionable insights into optimizing configurations for different use cases, demonstrating that careful adjustments can lead to significant energy savings. 
source_url: https://arxiv.org/abs/2411.11892
source_document: https://arxiv.org/pdf/2411.11892
source_organizations:
  - inria/_index
language: en
---