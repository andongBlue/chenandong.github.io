---
permalink: /
title: "Biography"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am currently a graduate student in the field of NLP in Minzu University of Chia and [Queen Mary University of London](https://www.qmul.ac.uk/) (Double Degress). I 

Previously, I completed my Ph.D. in Computer Science from Yale University, advised by Dragomir Radev. Before coming to Yale, I got my master's at Columbia University advised by Owen Rambow and Kathleen McKeown. I was an undergraduate at the University of Utah. Throughout my graduate studies, I spent several summers doing internships in industry, including Samsung Research America, Salesforce Research, and Microsoft Research. I also introduced and organized multiple popular shared tasks (e.g. Spider, SParC, CoSQL) for building conversational NLIs, which have attracted more than 100 submissions from top research labs.
我现在是一名NLP领域的研究生。本科在湖南大学做控制方向。现在是中央民族大学语咨委lab和伦敦玛丽女王大学的研究生。师从赵小兵与孙媛老师。在中央民族大学期间，主要的方向是低资源语言的表示学习。在伦敦玛丽女王大学，I am  supervised by Ph.D. candidate Rosella Paulina Galindo Esparza and Bosque in the CogSci research group.

# Recent progress💡

1. Recently, I am working as an intern at Cambricon Technologies Corporation Ai-Lab, mainly working on large-scale pre-training
2. In collaboration with Rosella Galindo Esparza in Queen Mary University of London, a paper is being written on low resource machine reading comprehension. The paper will be submitted to ACL.

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
<ul>{% for post in site.talks %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>


Open Source Contribution
======
## Hands-on data analysis
**Role**: Project sponsor and content builder

**Introduction**: An open-source data analysis project for everyone to learn by themselves

- Use the Titanic data set to divide tasks according to data observation, data manipulation, data visualization, data modeling, and model evaluation. 
-  Result : **Start** 398; **Fork:** 163

[Open source link here](https://github.com/datawhalechina/hands-on-data-analysis)
