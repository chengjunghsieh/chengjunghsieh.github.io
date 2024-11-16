---
layout: archive
title: ""
permalink: /research/
author_profile: true
redirect_from:
  - /publications
---
{% include base_path %}

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

# Research

### Systems Software and Security Lab
**Georgia Institute of Technology**
Graduate Research Assistant, 2023 - 2025
Advisor: Professor Taesoo Kim

- Developed a Smart Contract CVE database to collect and verify exploits for smart contracts, facilitating systematic vulnerability management
- Designed and implemented a fuzzing tool for Android native libraries using JNI, leveraging reverse engineering with Jadx and automating harness generation using Generative AI with few-shot learning and prompt engineering

### Machine Discovery and Social Network Mining Lab
**National Taiwan University**
Undergraduate Research Assistant, 2016 - 2017
Advisor: Professor Shou-De Lin

- Conducted research on privacy-preserving and security aspects in Machine Learning, focusing on Recommender Systems
- Employed distributed training methodologies to enhance the scalability and robustness of the models while preserving user privacy

### Network Security Lab
**National Taiwan University**
Undergraduate Research Assistant, 2015 - 2016
Advisor: Professor Hsu-Chun Hsiao

- Studied and presented research papers related to network security, focusing on emerging threats and defensive techniques
- Investigated potential attacks and defenses on Software-Defined Networking (SDN) data planes, contributing to the development of secure SDN architectures

# Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
