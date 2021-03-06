---
layout: math
title: "Assignment 10: String Algorithms"
---

# Assignment 10: String Algorithms

## 1936 All in All (1)

(Same as [Leetcode 392: Is Subsequence](https://leetcode.com/problems/is-subsequence/))

Let $dp(i)$ be the maximum length of prefix of $s$ that is a substring of $t$'s $i$-character prefix.

$$
dp(i)=
\begin{cases}
dp(i-1) &t_i \neq s_{dp(i-1)+1}\\
dp(i-1)+1 &t_i = s_{dp(i-1)+1}\\
\end{cases}
$$

## 2408 Anagram Groups (2)

(Solved)

## 2359 Questions (3)

Trivial [Josephus Problem](https://en.wikipedia.org/wiki/Josephus_problem#The_general_case). See the Wikipedia page if you don't know how to solve it quickly.

## 1750 Dictionary (3)

(Solved)

## 2752 Seek the Name, Seek the Fame (4)

(Solved)

## 1961 Period (5)

(Solved)

## 1147 Binary codes (6) 

## 3261 Milk Patterns (6)

(Solved)

## 2185 Milking Grid (7)

## 3349 Snowflake Snow Snowflakes (7)

(Solved)

## 3167 Cow Patterns (8, challenge problem)

## 2774 Long Long Message (9, challenge problem)

Simple $O(n^2)$ DP solution is not fast enough for this problem. However, if you meet this problem in an interview (it is indeed a common interview question), DO USE the DP solution because most interviewers don't know suffix array. :)

(TBC)