---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a second year Computer Science Ph.D. student at Johns Hopkins University advised by Dr. [Vladimir Braverman](https://engineering.jhu.edu/faculty/vladimir-braverman/) and Dr. [Alex Szalay](https://engineering.jhu.edu/faculty/alexander-szalay/). Previously, I earned my B.S. in Computer Science and B.A. in Mathematical Economic Analysis from Rice University. At Hopkins, I am affiliated with the Center for Language and Speech Processing (CLSP).

My research focuses on large language model (LLM) reasoning, post-training, and inference-time scaling. If you are interested in these topics and would like to talk with me, feel free to send me an email and I'm happy to chat!

## News

- Apr. 2026: Our paper on [Enhancing Large Reasoning Models via Decoding Tree Sketching](https://arxiv.org/pdf/2511.00640) is accepted to ICML! 
- Aug. 2025: Our paper on [Mitigating Confidence Distortion for Large Language Models](https://aclanthology.org/anthology-files/anthology-files/pdf/findings/2025.findings-emnlp.902.pdf) is accepted to EMNLP Findings!

## Publications

{% include base_path %}
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
