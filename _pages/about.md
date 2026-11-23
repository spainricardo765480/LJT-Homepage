---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am Junteng Liu, a first-year PhD candidate at the HKUST NLP Group, supervised by Professor Junxian He. My research focuses on natural language processing and machine learning. I graduated from Shanghai Jiao Tong University (SJTU) in June 2024, where I was previously advised by Professor Junxian He during my undergraduate studies.

## Education

- **Ph.D. in Computer Science** (2024&ndash;Present)
  
  Hong Kong University of Science and Technology (HKUST)

- **B.Eng.** (2020&ndash;2024)
  
  Shanghai Jiao Tong University (SJTU)

## Research Experience

- **Research Intern**, MINIMAX (February 2025 &ndash; Present)

- **Research Intern**, Tencent WXG (June 2024 &ndash; September 2024)
  
  Advisor: Zifei Shan

- **Research Intern**, Shanghai AI Lab (June 2023 &ndash; December 2023)
  
  Advisor: Prof. Yu Cheng

## Research Interests & Skills

- Natural language processing and machine learning
- LLM Reasoning and Reinforcement Learning
- Hallucination in Vision-Language Models (VLM)
- LLM Truthfulness and Interpretability

## Awards & Honors

- Zhiyuan Honor Scholarship, Shanghai Jiao Tong University

## Publications

{% include base_path %}
<ul>
{% for post in site.publications reversed %}
  <li><strong><a href="{{ base_path }}{{ post.url }}">{{ post.title }}</a></strong><br>
  {{ post.citation }}<br>
  <em>{{ post.authorship }}</em></li>
{% endfor %}
</ul>

You can also find my articles on my [Google Scholar profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate) or on the [Publications page]({{ base_path }}/publications/).

## Contact

- **Email:** [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- **GitHub:** [github.com/Vicent0205](https://github.com/Vicent0205)
- **Google Scholar:** [Profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- **X (Twitter):** [@junteng88716710](https://twitter.com/junteng88716710)
