---
title: "Linux"
datePublished: Sun Jul 16 2023 05:50:19 GMT+0000 (Coordinated Universal Time)
cuid: clk50pmyr000c09mh1g089opo
slug: linux

---

Day-1

StartFragment**'log' directory তে যাওয়ার ২টা path আছেঃ**

**\[root@peacock var\]# cd /var/log ==&gt; Absolute path; যেখানে আমরা শুরু থেকে শেষ পর্যন্ত সম্পূর্ণ path mention করি। Usually যখন আমরা এক directory থেকে অন্য directory তে ঢুকে কাজ করতে চাই**

**\[root@peacock log\]# pwd**

**/var/log**

**\[root@peacock log\]# cd ..**

**\[root@peacock var\]# cd log ==&gt;Relative path, যেখানে আমরা কোন path mention করি না**

**\[root@peacock log\]# pwd**

**/var/log**

**\[root@peacock log\]#**

**What is auto path completion?**

**\[root@peacock ~\]# cd /etc/yum ==&gt;যেমন আমরা '/etc/yum' path type করতে চাই, e type করার পরে'tab' key press করলে auto fill করে দিবে /etc command**

**\[root@peacock ~\]# ls -a ==&gt; Dot যুক্ত file গুলো hidden**

**প্রতিটি directory তে 1 dot and 2 dot থাকে 1 dot means current directory**

**2 dot means parent directory**

**. .bash\_logout .config Downloads Pictures Templates**

**.. .bash\_profile .cshrc .lesshst Public Videos**

**anaconda-ks.cfg .bashrc Desktop .local .ssh .xauthNOByx3**

**.bash\_history .cache Documents Music .tcshrc .Xauthority**EndFragment