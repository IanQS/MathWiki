---
mathLink: auto
---

<div class="topSpace"></div>

Date Created: 27/01/2022 11:56:26
Tags: #Type/Proposition #Topic/Set_Theory

Proved by: [[Left-invertible iff injection]], [[Right-invertible iff surjection (Choice)]]
References: <i>Not Applicable</i>
Justifications: <i>Not Applicable</i>

Specializations: <i>Not Applicable</i>
Generalizations: <i>Not Applicable</i>

``` ad-Proposition
title: Proposition.

Let $f:X\to Y$. Then $f$ is a bijection iff it is invertible.

```

<i>Proof.</i>
* ($\Rightarrow$): Since $f$ is a bijection, it is both an injection and a surjection, so there exist left and right-inverses $g,h:Y\to X$ of $f$, respectively. It follows that $g=h$ and thus $g$ is both a left and a right-inverse of $f$. Therefore, $f$ is invertible.

* ($\Leftarrow$): Since $f$ is invertible, $f$ has both a left and right-inverse so $f$ is both injective and surjective. It follows, by definition, that $f$ is bijective.<span style="float:right;">$\blacksquare$</span>
