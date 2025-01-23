---
title: Math - Module 2
date: 2025-01-21 22:14 +0300
categories: [Blogging, Study]
tags: [ personal blog, math]
author: maksat
math: true
---

## Counting subsets

If set $A$ has $n\geq1$ elements:

$A = \{ x_1, x_2, ... , x_n \}$

We can say that there are $n$ steps with 2 options each. The options are: include that element or not into the subset

- Step 1: $~$ $x_1$ has 2 options, so can be counted in 2 ways
- Step 2: $~$ $x_2$ has 2 options, so can be counted in 2 ways
- . . .
- Step $n$: $~$ $x_n$ has 2 options, so can be counted in 2 ways

So by the MR total number of subsets of a set can be counted as follows:

$2_1\cdot 2_2 \cdot ... \cdot 2_n = 2^n$

---


|$steps$|$$x_1$$             |$$x_2$$        |$$x_3$$      |$$x_n$$      |
|-------|-----------         |-------------  |-----------  |-----------  |
|$$1$$  |$\emptyset$ or $x_1$|$$\emptyset$$    |$$\emptyset$$|$$\emptyset$$|
|$$2$$  |$$\emptyset$$         |$\emptyset$ or $x_2$  |$$\emptyset$$|$$\emptyset$$|
|$$3$$  |$$\emptyset$$         |$$\emptyset$$    |$\emptyset$ or $x_2$ |$$\emptyset$$|
|$$n$$  |$$\emptyset$$         |$$\emptyset$$    |$$\emptyset$$ |$\emptyset$ or $x_n$|
|$$options$$| $$2$$ | $$2$$  | $$2$$ | $$2$$ |

For each  2 options of $x_1$ there are 2 options of $x_2$ and $x_3$ up to $x_n$

---
<br>
<br>

## Permutation
A permutation is an arrangement of objects in a definite order. The members or elements of sets are arranged here in a sequence or linear order. For example, the permutation of set A={1,6} is 2, such as {1,6}, {6,1}. As you can see, there are no other ways to arrange the elements of set A.

In permutation, the elements should be arranged in a particular order whereas in combination the order of elements does not matter. 