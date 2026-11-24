---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

Hi! I'm **Jing Tang** (唐晶). I was born in 2001 and am now a fifth-year Ph.D. student at the State Key Laboratory of Intelligent Manufacturing Equipment and Technology (SKL-IMET), Huazhong University of Science and Technology (HUST), where I'm advised by [Prof. Bo Tao](https://mse.hust.edu.cn/info/1142/1328.htm). I did my undergrad at HUST as well.

I work on **visual-tactile dexterous manipulation** for robots, including **VLA**, **VTLA** and **VTAM** models, as well as **embodied understanding** and **model acceleration**. See my papers on [Google Scholar](https://scholar.google.com/citations?hl=en&user=UIH3wxMAAAAJ).

Recent Publications
======
<p class="pub-intro">&#42; Equal contribution; &dagger; Corresponding author.</p>

<div class="pub-2026">
{% assign pubs_2026 = site.publications | sort: "date" | reverse %}
{% for post in pubs_2026 %}{% assign y = post.date | date: "%Y" %}{% if y == "2026" %}
{% assign venue_parts = post.venue | split: " (" %}
  <div class="pub-card">
    <div class="pub-card__tags">
      <span class="pub-card__type">{% if post.category == "journals" %}Journal{% else %}Conference{% endif %}</span>
      {% if venue_parts[1] %}<span class="pub-card__badge">{{ venue_parts[1] | remove: ")" }}</span>{% endif %}
    </div>
    <div class="pub-card__title">{{ post.title }}</div>
    <div class="pub-card__authors">{{ post.excerpt | markdownify | remove: "<p>" | remove: "</p>" | strip }}</div>
    <div class="pub-card__venue">{{ venue_parts[0] }}</div>
  </div>
{% endif %}{% endfor %}
</div>
<p class="pub-note"><a href="{{ base_path }}/publications/">All publications →</a></p>

Contact Information
======
Jing Tang, Ph.D. Candidate  
School of Mechanical Science & Engineering  
State Key Laboratory of Intelligent Manufacturing Equipment and Technology  
Huazhong University of Science & Technology  
Wuhan, Hubei, P. R. China (430074)  
Email: [j_tang@hust.edu.cn](mailto:j_tang@hust.edu.cn) / [focusers@163.com](mailto:focusers@163.com)

Have a nice day!
