---
title: Thoughts about Cities

date: 2020-02-03 01:11 +01:00
series: crystaldown
---
Cities can be busy places.
Smaller cities are quieter.
But public transport in small cities can be really bad!

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 29
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
