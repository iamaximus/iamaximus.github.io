---
title: Combinations & Quantifiers - Module 2
date: 2025-01-23 23:47 +0300
categories: [Blogging, Study]
tags: [ personal blog, math]
author: maksat
math: true
---

## Combinations

A ***combination*** of $r$ elements from the $n$ elements of $A$ is an unordered selection of $r$ of the $n$ elements of $A$.

### I

${\displaystyle n} \choose {\displaystyle r}$


### II

$n \cdot (n-1) ... (n-r+1) = \frac{\displaystyle n!}{\displaystyle(n-r)!}$

${\displaystyle n} \choose {\displaystyle r}$ = $\frac{\displaystyle n!}{\displaystyle r!\cdot (n-r)!}$

## Predicates
Basic statements with ***variables*** are called ***predicates***.

Predicates are ***undetermined***.

If we insert values in the free variables, we obtain a ***proposition***.

## Quantifiers
***Universal quantifier*** - "for all $x$" - $\forall x$

We read $\forall x P(x)$ as "$P(x)$ is true for all $x$".

***Existential quantifier*** - "there exists $x$" - $\exists a\in$

We read $\exists x P(x)$ as "there exists an $x$ such that $P(x)$ is true".

---

Suppose we have a proposition $P(x,y)$ where $x$ is the row and $y$ is the column and truth values as per the following grid:

|*P*|*1*|*2*|*3*|*4*|
|-|-|-|-|-|
|*1*|**T**|F|F|T|
|*2*|F|F|F|**T**|
|*3*|F|F|**T**|T|
|*4*|**T**|F|F|T|

The proposition $\forall x \exists y P(x,y)$ - *for all $x$ there exists $y$ such that $P(x,y)$* is true because for each row there is a column that has at least one True value.

