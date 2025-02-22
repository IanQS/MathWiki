<div class="topSpace"></div>

Date Created: 09/01/2023 15:58:47
Tags: #Type/Proposition #Topic/Ring_Theory

Proved by: <i>Not Applicable</i>
References: <i>Not Applicable</i>
Justifications: <i>Not Applicable</i>

Specializations: <i>Not Applicable</i>
Generalizations: <i>Not Applicable</i>

``` ad-Proposition
title: Proposition.

Let $R$ be a commutative ring and take $a,a_1,a_2,b\in R$ with $b\neq0$. Then the following properties hold.
* $b\divides a_1$ and $b\divides a_2$ implies $b\divides\!\l(a_1r\pm a_2\r)$ for any $r\in R$.
* $1\divides a$ and $b\divides0$.
* $u\divides a$ for all $u\in R^\times$.
* $b\divides a$ iff $a\in\gen{b}$ iff $\gen{a}\subseteq\gen{b}$.
* $a\sim b$ iff $\gen{a}=\gen{b}$.
* If $a=bu$ for some $u\in R^\times$, then $a\sim b$. The converse holds if $R$ is an integral domain.

```

<i>Proof.</i> The first three are easy: write $a_1=bk_1$ and $a_2=bk_2$ for some $k_1,k_2\in R$ and observe that $a_1r\pm a_2=bk_1r\pm bk_2=b\l(k_1r\pm k_2\r)$. Also, we have $a=1a$, $0=0b$, and $a=u\l(u^{-1}a\r)$ for all $u\in R^\times$.
* Observe that $b\divides a$ iff $a=kb$ for some $k\in R$, which occurs iff $a\in\gen{b}$. Now, for all $x\in\gen{a}$, $x=ar$ for some $r\in R$ and hence $b\divides a$ implies $b\divides x$. Thus $x=bk$ for some $k\in R$ and hence $x\in\gen{b}$. The converse is easy.
* This follows directly from the above.
* If $a=bu$, then $b=au^{-1}$ and hence $a\sim b$. Conversely, write $a=bk$ and $b=al$ for some $k,l\in R$. Then $a=\l(al\r)k=a\l(lk\r)$, so, since $R$ is an integral domain, we see that $lk=1$. In particular, $u\coloneqq k\in R^\times$.<span style="float:right;">$\blacksquare$</span>
