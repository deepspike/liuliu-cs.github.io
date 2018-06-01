---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

* [Building Energy-Efficient Multi-Level Cell STT-RAM Caches with Data Compression](http://liuliu-cs.github.io/files/ASP-DAC-17.pdf) <br />
**Liu Liu**, Ping Chi, Shuangchen Li, Yuanqing Cheng, Yuan Xie <br />
in *the 22nd Asia and South Pacific Design Automation Conference (ASP-DAC)*, Jan. 2017

* [NVSim-CAM: A Circuit-Level Simulator for Emerging Nonvolatile Memory based Content-Addressable Memory](http://liuliu-cs.github.io/files/ICCAD-17.pdf) <br />
Shuangchen Li, **Liu Liu**, Peng Gu, Cong Xu, and Yuan Xie. <br />
in *the 35rd International Comference on Computer-Aided Design (ICCAD)*, Nov. 2016

* [Leveraging 3D Technologies for Hardware Security: Opportunities and Challenges](http://liuliu-cs.github.io/files/GLSVLSI-16.pdf) <br />
Peng Gu, Shuangchen Li, Dylan Stow, Russell Barnes, **Liu Liu**, Eren Kursun, Yuan Xie <br />
in *the 26th Great Lakes Symposium on VLSI (GLSVLSI)*, May 2016


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
