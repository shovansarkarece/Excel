---
title: "Statistical Function/LARGE,SMALL"
datePublished: Tue Mar 12 2024 00:11:08 GMT+0000 (Coordinated Universal Time)
cuid: cltnm9vwj00000ajndqon3e9v
slug: statistical-functionlargesmall

---

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1710202238858/6cc5dcfb-e56d-47cb-a9e8-9361c9b9354a.png align="center")

Assume we have a salary sheet where we ant to get the second/third  largest/smallest salary then  we use

large and small function

<mark>Syntax:LARGE(array,k) &nbsp;--&gt;Array means cell range</mark>

IF we pass 1 then we will get highest salary

IF we pass 2 then we will get second highest salary

IF we pass 3 then we will get third highest salary

<mark>Syntax:SMALL(array,k) --&gt;Array means cell range</mark>

IF we pass 1 then we will get lowest salary

IF we pass 2 then we will get second lowest salary

IF we pass 3 then we will get third lowest salary

<mark>=SUM(LARGE(B30:B40;{1;2;3})) --&gt;Sum of 3 largest number</mark>

<mark>=SUM(SMALL(B31:B41;{1;2;3})) --&gt;Sum of 3 lowest number</mark>