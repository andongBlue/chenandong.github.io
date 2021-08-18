---
permalink: /
title: "Biography"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---



我现在是一名NLP领域的研究生。本科在湖南大学做控制方向。现在是中央民族大学语咨委lab和伦敦玛丽女王大学的研究生。师从赵小兵与孙媛老师。在中央民族大学期间，主要的方向是低资源语言的表示学习。在伦敦玛丽女王大学，I am  supervised by Ph.D. candidate Rosella Paulina Galindo Esparza and Bosque in the CogSci research group.

# Recent progress💡

1. 现在我在中科寒武纪Ai-Lab做实习生，主要从事大规模预训练的工作
2. 正在完成一篇ACL的论文，论文是关于低资源机器阅读理解任务，在伦敦n玛丽女王大学

# Interests

- Artificial Intelligence
- Computational Linguistics
- Natural Language Processing
- Machine Reading Comprehension
- Language Model

# Education

- BSc in Electrical engineering and its automation, 2019

  HUNAN UNIVERSITY

- MS in Computational Linguistics, 2022

  MINZU UNIVERSITY OF CHINA

- MS in Big Data Science, 2022

  QUEEN MARY UNIVERSITY OF LONDON
  

# Publications

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# Talks
{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}


Open Source Contribution
======
## Hands-on data analysis
**Role**: Project sponsor and content builder

**Introduction**: An open-source data analysis project for everyone to learn by themselves

- Use the Titanic data set to divide tasks according to data observation, data manipulation, data visualization, data modeling, and model evaluation. 
-  Result : **Start** 398; **Fork:** 163

[Open source link here](https://github.com/datawhalechina/hands-on-data-analysis)
