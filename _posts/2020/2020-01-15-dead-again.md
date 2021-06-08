---
title: Dead again?!

date: 2020-01-15 01:11 +01:00
series: crystaldown
---
Didn't Swift just die 21 chapters ago?!

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 21
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
