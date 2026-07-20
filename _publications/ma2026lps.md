---
title: "The Dentate Gyrus of Large Language Models: A Parameterized Knowledge Pattern Separation Framework for Scenario Cognition Diagnosis and Enhancement"
collection: publications
category: journal
permalink: /publication/ma2026lps
date: 2025-07-20
venue: 'Journal of Computer Research and Development'
paperurl: 'https://crad.ict.ac.cn/cn/article/pdf/preview/10.7544/issn1000-1239.202660437.pdf'
citation: 'Ma Boxiang, Li Ru, Guo Shaoru, Li Yinghao, Víctor Gutiérrez-Basulto. The Dentate Gyrus of Large Language Models: A Parameterized Knowledge Pattern Separation Framework for Scenario Cognition Diagnosis and Enhancement[J]. Journal of Computer Research and Development. DOI: 10.7544/issn1000-1239.202660437'
selected: true
---

Large language models (LLMs) exhibit systematic generalization limitations in scenario cognition tasks, revealing potential functional deficiencies in their knowledge memorization processes. Inspired by the pattern separation mechanism of the dentate gyrus in the human hippocampus, this paper hypothesizes that failures in scenario cognition are associated with limitations in the internal pattern separation capability of LLMs. Based on this hypothesis, we first design a cross-entity representation diagnosis (CERD) method, which quantitatively measures entity representation confusion across different layers without additional training. Our analysis reveals that standard autoregressive training fails to induce sufficiently effective pattern separation capabilities, leaving substantial cross-entity correlation confusion within LLM representations. Building upon this observation, we further propose latent-space pattern separation (LPS), which explicitly incorporates pattern separation constraints into the training process by introducing a triplet-based contrastive regularization at target layers with severe entity confusion, thereby reducing correlations among easily confused knowledge representations. Extensive experiments across LLMs ranging from 0.8B to 9B parameters demonstrate that LPS consistently improves scenario cognition capabilities. Compared with standard autoregressive training, our method achieves up to 101.5% relative improvement in exact match (EM), providing a new perspective for understanding and enhancing scenario cognition and knowledge memorization mechanisms in LLMs.