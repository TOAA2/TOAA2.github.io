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


# Quantum Field Theory

## Effective Field Theory

- [Course on EFT by Iain Stewart](https://www.youtube.com/playlist?list=PLUl4u3cNGP60TvpbO5toEWC8y8w51dtvm) Lecture notes can be downloaded on [Stewart's personal webpage](http://www2.lns.mit.edu/~iains/Home/Homepage.html)
- [A concise introduction to EFT](https://arxiv.org/abs/2006.16285)

## Gauge Theory

- [Weinberg-Witten Theorem](https://www.researchgate.net/publication/227727891_The_Weinberg-Wirten_theorem_on_massless_particles_An_essay) I found [The Wikipedia page on the WW theorem](https://en.wikipedia.org/wiki/Weinberg%E2%80%93Witten_theorem) is also helpful. Some discussions are presented in *Quantum Field Theory and the Standard Model by Matthew D. Schwartz*.

## Textbooks

- ***Lectures of Sidney Coleman on Quantum Field Theory*** Truly the first textbook on quantum field theory! Coleman provides an in-depth explanation of the basics of quantum field theory. But the second half of the book is a little stale, especially when it focuses on current algebra, which may be only historically interesting. Many fundamental topics are not covered, such as EFT.
- ***Quantum Field Theory and the Standard Model by Matthew D. Schwartz*** "A wonderful tour of quantum field theory from the modern perspective, filled with insights on both the conceptual underpinnings and the concrete, elegant calculational tools of the subject." Nima Arkani-Hamed, Institute for Advanced Study, Princeton
- ***Quantum Field Theory by Mark Srednicki*** A nice decoupling of the basic topics on quantum field theory! There are no barriers to starting on any section of interest.
- ***The Quantum Theory of Fields by Steven Weinberg*** Deserves its reputation.
- ***[Notes on QFT by Yuchen Wang](https://zhuanlan.zhihu.com/p/391450897)*** Basics of QFT in the view of an excellent student. In Chinese!
- ***[Lecture notes on Gauge Theory by David Tong](http://www.damtp.cam.ac.uk/user/tong/gaugetheory.html)*** Textbook-level topics on gauge theory in a relatively modern view.



---
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.articles reversed %}
  {% include archive-single.html %}
{% endfor %}
