---
mathLink: Differentiable $\Rightarrow$ $\l[Df\l(\v{a}\r)\r]=Jf\l(\v{a}\r)$
---

<div class="topSpace"></div>

Date Created: 02/01/2023 15:25:20
Tags: #Type/Proposition #Topic/Analysis #Courses/MATH358

Proved by: [[Differentiable implies existence of directional derivatives]]
References: <i>Not Applicable</i>
Justifications: <i>Not Applicable</i>

Specializations: <i>Not Applicable</i>
Generalizations: <i>Not Applicable</i>

``` ad-Proposition
title: Proposition.

Fix $m,n\in\N^+$, let $U\subseteq\R^n$ be open, and fix $\v{a}\in U$. For a function $f:U\to\R^m$, if $f$ is differentiable at $\v{a}$, then $\l[Df\l(\v{a}\r)\r]=Jf\l(\v{a}\r)$.

```

<i>Proof.</i> Let $\l\{\v{e}_1,\dots,\v{e}_n\r\}$ and $\l\{\widetilde{\v{e}}_1,\dots,\widetilde{\v{e}}_m\r\}$ be the standard bases for $\R^n$ and $\R^m$, respectively. For all $j\in\l\{1,\dots,n\r\}$, observe that
$$\begin{equation}
    \l[Df\l(\v{a}\r)\r]\v{e}_j=D_jf\l(\v{a}\r)=\lim\limits_{t\to0}\frac{f\l(\v{a}+t\v{e}_j\r)-f\l(\v{a}\r)}{t}=\sum_{i=1}^{m}\lim\limits_{t\to0}\frac{f_i\l(\v{a}+t\v{e}_j\r)-f_i\l(\v{a}\r)}{t}\widetilde{\v{e}}_i=\sum_{i=1}^{m}\l(D_jf_i\r)\l(\v{a}\r)\widetilde{\v{e}}_i.
\end{equation}$$
Thus the $j^\textrm{th}$ column of $\l[Df\l(\v{a}\r)\r]$ is the vector $\sum_{i=1}^{m}\l(D_jf_i\r)\l(\v{a}\r)\widetilde{\v{e}}_i$, so the result follows.<span style="float:right;">$\blacksquare$</span>
