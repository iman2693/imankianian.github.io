---
permalink: /
title: "Welcome to my personal academic webpage!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---



I am Iman Kianian, a computer science researcher with a focus on machine learning and artificial intelligence. My primary research interest is in computer vision, a field I have been engaged in since my undergraduate studies, working on computer vision tasks under the supervision of [Dr. Sadegh Eskandari](https://scholar.google.com/citations?user=y-LsrFEAAAAJ&hl=en"). During my Master's at the [University of Tehran](https://ut.ac.ir/en) ,Best University in Iran, I expanded my research under the guidance of [Dr. Hedieh Sajedi](https://scholar.google.com/citations?user=YHjV73oAAAAJ&hl=en), focusing on medical image processing and deep learning.

I have also gained experience in other areas of machine learning and natural language processing, excelling in advanced courses with high grades. I am looking forward to pursuing my studies for a PhD degree and publishing several papers in prestigious conferences and journals like CVPR, ICCV, and NeurIPS. My work continues to explore new challenges and innovations in the AI field.

[[Scholar]](https://scholar.google.com/citations?user=NWBdlBkAAAAJ&hl=en)  [[Projects]](https://Github.com/iman2693)  [[Linkedin]](https://www.linkedin.com/in/imankianian/)  [[Printable CV]](https://drive.google.com/file/d/1EkeR0sNAoisDQz4V8uXbTztuUZUpLX2b/view?usp=drive_link)  [[Transcript]](https://drive.google.com/file/d/1-eUgf3i0W60qKh1bX4kpIFeVcXr-R1kP/view?usp=sharing)


<hr>

# Publications

{% include base_path %}

{% for post in site.publications reversed %}
  {% if post.type == 'journal' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

{% for post in site.publications reversed %}
  {% if post.type == 'conference' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

