---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

**Jing Tang** (唐晶) was born in 2001, and now she is studying as a fifth-year Ph.D. candidate at the State Key Laboratory of Intelligent Manufacturing Equipment and Technology (SKL-IMET) at Huazhong University of Science and Technology (HUST) under the supervision of [Prof. Bo Tao](https://mse.hust.edu.cn/info/1142/1328.htm). She also holds a bachelor’s degree from HUST. Her Google Scholar profile is [here](https://scholar.google.com/citations?hl=en&user=UIH3wxMAAAAJ).

2026 Publications
======
<p class="pub-intro">&#42; Equal contribution; &dagger; Corresponding author.</p>

<ol class="pub-2026">
{% assign pubs_2026 = site.publications | sort: "date" | reverse %}
{% for post in pubs_2026 %}{% assign y = post.date | date: "%Y" %}{% if y == "2026" %}
  <li><strong>{{ post.title }}</strong><br>{{ post.excerpt | markdownify | remove: "<p>" | remove: "</p>" | strip }}<br><i>{{ post.venue }}</i></li>
{% endif %}{% endfor %}
</ol>

Contact Information
======
Jing Tang, Ph.D. Candidate  
School of Mechanical Science & Engineering  
State Key Laboratory of Intelligent Manufacturing Equipment and Technology  
Huazhong University of Science & Technology  
Wuhan, Hubei, P. R. China (430074)  
Email: [j_tang@hust.edu.cn](mailto:j_tang@hust.edu.cn) / [focusers@163.com](mailto:focusers@163.com)

Have a nice day!
