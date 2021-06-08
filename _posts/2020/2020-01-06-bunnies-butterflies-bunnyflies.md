---
title: Bunnies, Butterflies, Bunnyflies!

date: 2020-01-06 00:01 +01:00
series: crystaldown
---
Bunnies, Butterflies, Bunnyflies!

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 17
  | first %}

[ {{page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
