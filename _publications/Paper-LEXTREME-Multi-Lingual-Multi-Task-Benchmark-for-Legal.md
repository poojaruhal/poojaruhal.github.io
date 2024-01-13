---
title: "LEXTREME: A Multi-Lingual and Multi-Task Benchmark for the Legal Domain"
collection: publications
permalink: /publications/Paper-LEXTREME-Multi-Lingual-Multi-Task-Benchmark-for-Legal
venue: "Findings of the Association for Computational Linguistics: EMNLP 2023"
date: 2023-01-12
---

[Paper](https://aclanthology.org/2023.findings-emnlp.200/),
[Arxiv](https://arxiv.org/abs/2301.13126)
[GitHub](https://github.com/JoelNiklaus/LEXTREME)
[Dataset](https://huggingface.co/datasets/joelniklaus/lextreme),

## ABSTRACT
Lately, propelled by phenomenal advances around the transformer architecture, the legal NLP field has enjoyed spectacular growth. To measure progress, well-curated and challenging benchmarks are crucial. Previous efforts have produced numerous benchmarks for general NLP models, typically based on news or Wikipedia. However, these may not fit specific domains such as law, with its unique lexicons and intricate sentence structures. Even though there is a rising need to build NLP systems for languages other than English, many benchmarks are available only in English and no multilingual benchmark exists in the legal NLP field. We survey the legal NLP literature and select 11 datasets covering 24 languages, creating LEXTREME. To fairly compare models, we propose two aggregate scores, i.e., dataset aggregate score and language aggregate score. Our results show that even the best baseline only achieves modest results, and also ChatGPT struggles with many tasks. This indicates that LEXTREME remains a challenging task with ample room for improvement. To facilitate easy use for researchers and practitioners, we release LEXTREME on huggingface along with a public leaderboard and the necessary code to evaluate models. We also provide a public Weights and Biases project containing all runs for transparency.