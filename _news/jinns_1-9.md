---
layout: post
date: 2026-4-10
title: Checkout jinns v1.9
inline: false
related_posts: false
---

**Changelog:**  new in 1.9 - [Natural Gradient Descent](https://arxiv.org/pdf/2302.13163) is now available and custom optimizers for second order methods. More incoming soon (e.g. [Anagram](https://arxiv.org/abs/2412.10782) or self-scaled Broyden) 

Many thanks to Hugo Gangloff for his dedication on this, and to the [ScimBa](https://www.scimba.org/) team for stimulating discussions. You should go check out their work as well!

---

<tt>jinns</tt> is a Python package for physics-informed neural networks (PINNs) we develop together with [Hugo Gangloff](https://hgangloff.github.io/) as a basis for our research. Using the JAX ecosystem, it provides an intuitive and flexible interface for

 * forward problem: learning a PDE solution.
 * inverse problem: learning the parameters of a PDE.
 * meta-modeling: learning a family of PDE indexed by its parameters.

<tt>Check out the documentation: [https://mia_jinns.gitlab.io/jinns/](https://mia_jinns.gitlab.io/jinns/)</tt>

*Want to use or contribute ?* Development happens on [Gitlab](https://gitlab.com/mia_jinns/jinns)

![image](/assets/img/jinns-diagram.png)
