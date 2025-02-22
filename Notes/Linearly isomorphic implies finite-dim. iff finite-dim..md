---
mathLink: $V\iso W$ $\Rightarrow$ ($\dim V<\infty\Leftrightarrow\dim W<\infty$)
---

<div class="topSpace"></div>

Date Created: 28/05/2022 16:37:33
Tags: #Type/Proposition #Topic/Linear_Algebra

Proved by: [[Image of linear map is spanned by image of spanning set]], [[Basic properties of linear maps]]
References: <i>Not Applicable</i>
Justifications: <i>Not Applicable</i>

Specializations: <i>Not Applicable</i>
Generalizations: <i>Not Applicable</i>

``` ad-Proposition
title: Proposition.

Let $V$ and $W$ be isomorphic $K$-vector spaces. Then $V$ is finite-dimensional iff $W$ is finite-dimensional.

```

<i>Proof.</i> Since $V\iso W$, there exists an invertible linear map $T:V\to W$. If $V$ is finite-dimensional, let $\mc{B}\coloneqq\l\{e_1,\dots,e_n\r\}$ be a basis thereof. Then $W$ has a finite spanning set, since
$$\begin{equation}
    W=\im T=\span\l(\im_T\mc{B}\r)=\span\l\{T\l(e_1\r),\dots,T\l(e_n\r)\r\}.
\end{equation}$$
Note that $T^{-1}$ is also linear, so the converse follows similarly.<span style="float:right;">$\blacksquare$</span>
