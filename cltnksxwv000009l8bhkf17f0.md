---
title: "Statistical Function/Running Count"
datePublished: Mon Mar 11 2024 23:29:58 GMT+0000 (Coordinated Universal Time)
cuid: cltnksxwv000009l8bhkf17f0
slug: statistical-functionrunning-count

---

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1710199159523/941c6167-0ab4-4c44-9661-831a5de8cf5c.png align="center")

<mark>=IF(B5="";"";COUNTA($B$4:B5))</mark>

Explnation OF This Logic: IF B5 cell is empty then keep it empty neither just COUNTA the selected column,But here the hack is we must have to lock the first cell address like <mark>$B$4</mark> not the last range <mark>B5</mark>

**COUNTA()--&gt;Counts how many values are in the list of**

**arguments and it ignores only blank text**