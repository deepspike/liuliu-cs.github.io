---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Building Energy-Efficient Multi-Level Cell STT-RAM Caches with Data Compression [pdf](http://liuliu-cs.github.io/files/ASP-DAC-17.pdf)
**Liu Liu**, Ping Chi, Shuangchen Li, Yuanqing Cheng, Yuan Xie
Published in *the 22nd Asia and South Pacific Design Automation Conference (ASP-DAC)*

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
