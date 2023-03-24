---
layout: archive
title: "Links"
permalink: /links/
author_profile: true
---

I present several interesting links and sources here. Some of them are advanced scientific popularization articles, some are serious introductions. Enjoy!



# 动力系统与非线性科学

- [KAM定理高级科普和证明概要](https://chaoli.club/index.php/7127)
- [利用Logistic Map做到单参数拟合任意散点图（一个参数画大象）](https://aip.scitation.org/doi/10.1063/1.5031956)



---
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.articles reversed %}
  {% include archive-single.html %}
{% endfor %}
