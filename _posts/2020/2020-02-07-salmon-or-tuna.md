---
title: Salmon or Tuna?

date: 2020-02-07 01:11 +01:00
series: crystaldown
---
Salmon or Tuna? Salmon or Tuna? Salmon!

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 31
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
