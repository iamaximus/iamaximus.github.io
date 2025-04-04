---
title: Math - Module 2
date: 2025-01-21 22:14 +0300
categories: [Study, Math]
tags: [ personal blog, math]
author: maksat
math: true
---

## Counting subsets

If set $A$ has $n\geq1$ elements:

$A = \\{ x_1, x_2, ... , x_n \\}$

We can say that there are $n$ steps with 2 options each. The options are: include that element or not into the subset

- Step 1: $~$ $x_1$ has 2 options, so can be counted in 2 ways
- Step 2: $~$ $x_2$ has 2 options, so can be counted in 2 ways
- . . .
- Step $n$: $~$ $x_n$ has 2 options, so can be counted in 2 ways

So by the MR total number of subsets of a set can be counted as follows:

$$2_1\cdot 2_2 \cdot ... \cdot 2_n = 2^n$$

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

## Counting sequences

Sequences allow repetition.

Count number of sequences that form 3 letter word from vowel letters. It could be $aui, aua, aau$ and etc.

We take a sequence with lenght of 3 elements. Each element can have 5 options from vowel letters, so:

- step 1: $~$ $1\cdot 5$
- step 2: $~$ $1\cdot 5$
- step 3: $~$ $1\cdot 5$

By the MR the number of words is: $~$ $5\cdot 5 \cdot 5 = 5^3 = 125$

In other words, for each option in step 1 there are 5 options in each subsequent steps.

The general formula of counting sequences of length $l$ for a set with $n$ elements is: 

$$n^l$$ 

## Cardinality of powerset

A Powerset of a set is the collection of all possible subsets of that set, including the empty set and the set itself.

A powerset of set $A$ is $2^A$ 

$|2^A|$ = $2^{|A|}$

## Permutation
A ***permutation*** is an arrangement of objects in a definite order. The members or elements of sets are arranged here in a sequence or linear order. For example, the permutation of set A={1,6} is 2, such as {1,6}, {6,1}. As you can see, there are no other ways to arrange the elements of set A.

$$nPr=n!$$

In permutation, the elements should be arranged in a particular order whereas in combination the order of elements does not matter. 



## Partial permutation

A ___partial permuatation___ of $r$ out of the $n$ elements of $A$ consists of picking $r$ elements and ordering them in a row.

$$nPr=\frac{n!}{(n-r)!}$$