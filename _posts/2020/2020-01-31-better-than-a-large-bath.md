---
title: Better Than A Large Bath?!

date: 2020-01-31 01:11 +01:00
series: crystaldown
---
What's better than having a large bath? Being able to use it whenever you like!

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 28
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
