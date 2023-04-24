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


## Lattice Gauge Theory

- [Tom DeGrand's TASI lectures on lattice method](https://sites.google.com/a/colorado.edu/tasi-2019-wiki/lecture-topics/introduction-to-lattice-methods) provides a concise introduction to lattice theory. [Lectures on Gauge Theory by David Tong](https://www.damtp.cam.ac.uk/user/tong/gaugetheory.html) are helpful as well. Especially, Tong paid particular attention to fermions on the lattice and the Nielson-Ninomiya Theorem.
- [The references part of the wikipedia page for Nielson-Ninomiya Theorem](https://en.wikipedia.org/wiki/Nielsen%E2%80%93Ninomiya_theorem#References) lists almost all the useful discussions about the NN no-go theorem I found.

## Textbooks

- ***Lectures of Sidney Coleman on Quantum Field Theory*** Truly the first textbook on quantum field theory! Coleman provides an in-depth explanation of the basics of quantum field theory. But the second half of the book is a little stale, especially when it focuses on current algebra, which may be only historically interesting. Many fundamental topics are not covered, such as EFT.
- ***Quantum Field Theory and the Standard Model by Matthew D. Schwartz*** "A wonderful tour of quantum field theory from the modern perspective, filled with insights on both the conceptual underpinnings and the concrete, elegant calculational tools of the subject." Nima Arkani-Hamed, Institute for Advanced Study, Princeton
- ***Quantum Field Theory by Mark Srednicki*** A nice decoupling of the basic topics on quantum field theory! There are no barriers to starting on any section of interest.
- ***The Quantum Theory of Fields by Steven Weinberg*** Deserves its reputation.
- ***[Notes on QFT by Yuchen Wang](https://zhuanlan.zhihu.com/p/391450897)*** Basics of QFT in the view of an excellent student. In Chinese!
- ***[Lecture notes on Gauge Theory by David Tong](http://www.damtp.cam.ac.uk/user/tong/gaugetheory.html)*** Textbook-level topics on gauge theory in a relatively modern view.


# About Machine Learning

## Diffusion Model

- [This blog post](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/) provides a clear introduction to the diffusion model (DDPM). As a student with Physics background, I enjoy a lot. [A Chinese version](https://zhuanlan.zhihu.com/p/530602852) [Another introduction in Chinese](https://zhuanlan.zhihu.com/p/571366616)
- [Yang Song's paper](https://arxiv.org/abs/2011.13456) relates DDPM to the Langevin dynamics. That's interesting and inspiring if you are wondering the origin of human mind. In fact, such a relation in physics has been noted from Einstein. In Einstein's paper about the Brownian motion, he provided a random-walk perspective to understand diffusion phenomena and the Brownian motion. Later, the Brownian motion is understood by the Langevin equation. Combining these two perspectives, we can establish the relation between diffusion and the Langevin equation -- they produce the same random distribution. (In the Brownian motion case, diffusion and the Langevin dynamics are two approaches to the same $\langle x \rangle$, $\langle x^2 \rangle$, namely, the same random distribution of $x$.) Nothing special in physics, but the success of DDPM and Yang Song's *Score-Based Generative Modeling through Stochastic Differential Equations* provides a lot of enlightenment for thinking about human intelligence. [An introduction about the Brownian motion](http://toaa2.github.io/files/Lecture_note_on_Brown_motion.pdf)


---
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.articles reversed %}
  {% include archive-single.html %}
{% endfor %}
