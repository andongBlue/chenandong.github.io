---
permalink: /
title: "Biography"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am now a graduate student in NLP direction. I graduated from [Hunan University](http://www-en.hnu.edu.cn/) with an undergraduate degree in Electrical Engineering and Automation. My supervisor was Prof. [Zhigang Ling](http://eeit.hnu.edu.cn/info/1307/4568.htm) who start my research journey about Artificial Intelligence. Now I am doing my master's degree in China and National Language Resource and Monitoring Research Center at Minzu University of China and [Queen Mary University of London](https://www.qmul.ac.uk/), supervised by Prof. Xiaobing Zhao, Prof. Yuan Sun and PHD [Rosella Galindo Esparza](https://scholar.google.com/citations?user=oxqjNj8AAAAJ&hl=en). During this period, I spent summer doing intership in industry. Recently I am working on large-scale pre-training model in the AI Lab in Cambricon Technologies Corporation, supervised by Prof. [Xishan Zhang](http://people.ucas.edu.cn/~zhangxishan?language=en). In the process of programming, I like to open source what I think is valuable. Now I am the project leader of an open source project about data analysis([Hands-on data analysis](https://github.com/datawhalechina/hands-on-data-analysis/blob/master/README-English.md)), which now has **398 starts** and **163 forks**.
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
