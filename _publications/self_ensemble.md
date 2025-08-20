---
title: "Self-ensemble: Mitigating Confidence Distortion for Large Language Models"
collection: publications
category: conferences
permalink: /publication/self_ensemble
excerpt: 'Although Large Language Models (LLMs) perform well in general fields, they exhibit a confidence distortion problem on multi-choice question-answering (MCQA), particularly as the number of answer choices increases. Specifically, on MCQA with many choices, LLMs suffer from under-confidence in correct predictions and over-confidence in incorrect ones, leading to a substantially degraded performance. To solve this problem, we propose Self-ensemble in this work. Our method splits the choices into several groups and ensembles LLM predictions across these groups to reach a final decision. The advantage of Self-ensemble is its plug-and-play nature, where it can be integrated into existing LLM architecture based on a designed attention mask and positional encoding, without requiring labeled datasets for parameter tuning. Experimental results on three LLMs and datasets demonstrate that Self-ensemble comprehensively addresses the confidence distortion problem of LLMs, outperforming standard inference as well as baseline methods.'
date: 2025-06-02
venue: 'EMNLP 2025 Findings'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/pdf/2506.01951'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Although Large Language Models (LLMs) perform well in general fields, they exhibit a confidence distortion problem on multi-choice question-answering (MCQA), particularly as the number of answer choices increases. Specifically, on MCQA with many choices, LLMs suffer from under-confidence in correct predictions and over-confidence in incorrect ones, leading to a substantially degraded performance. To solve this problem, we propose Self-ensemble in this work. Our method splits the choices into several groups and ensembles LLM predictions across these groups to reach a final decision. The advantage of Self-ensemble is its plug-and-play nature, where it can be integrated into existing LLM architecture based on a designed attention mask and positional encoding, without requiring labeled datasets for parameter tuning. Experimental results on three LLMs and datasets demonstrate that Self-ensemble comprehensively addresses the confidence distortion problem of LLMs, outperforming standard inference as well as baseline methods.
