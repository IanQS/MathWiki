<div class="topSpace"></div>

Date Created: 05/05/2023 14:32:11
Tags: #Type/Theorem #Topic/Group_Theory

Proved by: [[Transitive action iff left-multiplication on quotient by stabilizer]]
References: [[Lagrange's Theorem]]
Justifications: <i>Not Applicable</i>

Specializations: <i>Not Applicable</i>
Generalizations: <i>Not Applicable</i>

``` ad-Theorem
title: Theorem (Orbit-Stabilizer).

Let $G$ be a group acting on a set $X$ and fix $x\in X$. Then there is a bijection between the orbit $Gx$ and cosets $G/G_x$ of the stabilizer $G_x$, so $\l|Gx\r|=\l[G:G_x\r]$.

```

<b>Remark.</b> If $G$ is finite, then $\l|Gx\r|=\l[G:G_x\r]=\l|G\r|/\l|G_x\r|$ by Lagrange’s Theorem. Thus $\l|Gx\r|$ divides $\l|G\r|$, which is a strong constraint.<span style="float:right;">$\blacklozenge$</span>

---

<i>Proof.</i> Restricting the action on $X$ to transitively act on the orbit $Gx$, we see that $Gx$ is equivariant to $G/G_x$ with the left-multiplication action. In particular, we have $\l|Gx\r|=\l|G/G_x\r|$ and the result follows.<span style="float:right;">$\blacksquare$</span>
