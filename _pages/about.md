---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a Ph.D. student in Computer Science and Technology at the School of Computer and Information Technology, Shanxi University, under the supervision of [Prof. Ru Li](https://www.researchgate.net/scientific-contributions/Ru-Li-14829601) and [Prof. Víctor Gutiérrez Basulto](https://scholar.google.com/citations?user=L2eFo5IAAAAJ).

My primary research interests include Natural Language Processing and Frame Semantics. I am currently focused on the knowledge memorization capabilities of Large Language Models, with particular emphasis on their ability to understand and model semantic scenarios.

## 📖 Educations
- *2024.09 - Present*, School of Computer and Information Technology, **Shanxi University**. Ph.D. Student.
- *2022.09 - 2024.06*, School of Computer and Information Technology, **Shanxi University**. Master Student.
- *2018.09 - 2022.06*, School of Information Science and Technology, **Taiyuan University of Science and Technology**. Undergraduate.

## 📝 Selected Publications
{% assign selected_pubs = site.publications | where: "selected", true | sort: 'date' | reverse %}

{% for post in selected_pubs %}
  {% include archive-single.html %}
{% endfor %}