---
layout: post
date: 2025-12-18
title: Checkout jinns v1.7.0
inline: false
related_posts: false
---

**Changelog:** we introduced cool things in this new version, like the `solve_alternate()` function to
do coordinate descent on the loss in inverse problem. It allows fine-grained control over optimisation with respect to each parameters (*e.g.* constrained optimization, regularization, etc.).

---

<tt>jinns</tt> is a Python package for physics-informed neural networks (PINNs) we develop together with [Hugo Gangloff](https://hgangloff.github.io/) as a basis for our research. Using the JAX ecosystem, it provides an intuitive and flexible interface for

 * forward problem: learning a PDE solution.
 * inverse problem: learning the parameters of a PDE.
 * meta-modeling: learning a family of PDE indexed by its parameters.

<tt>Check out the documentation: [https://mia_jinns.gitlab.io/jinns/](https://mia_jinns.gitlab.io/jinns/)</tt>

*Want to use or contribute ?* Development happens on [Gitlab](https://gitlab.com/mia_jinns/jinns)

![image](/assets/img/jinns-diagram.png)
