---
title: "RANK() and RANK() function with COUNTIF()"
datePublished: Wed Mar 13 2024 13:13:54 GMT+0000 (Coordinated Universal Time)
cuid: cltptodc2000008l8g09ebvgn
slug: rank-and-rank-function-with-countif

---

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1710335502382/eb79c00e-fd81-4f5e-81e5-81001cb9b7e8.png align="center")

RANK function is depricated that's why we use RANK.EQ()

Synatx:RANK(number,range;order)--&gt;By-default order is

always in descending order so don't touch in order

k45 is basically RANK 5 and K46 is RANK 6 because there

are no rank is in decimal number but in average for cell K45,RANK value is 5 and for cell K46 RANK value is 6.IF we add 5+6=11--&gt;RANK&gt;AVG(11/2)--&gt;5,5(That is the main point)

IN K column we are geting rank average 5,5 and rank  5 ,two times which is bit conflicted that's why we use this New RANK formula with COUNTIF

**<mark>=RANK(G45;G45:G55)+COUNTIF($G$45:G45;G45)-1</mark>**