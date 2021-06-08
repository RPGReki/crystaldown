---
title: Lots of Visitors

date: 2020-01-08 01:00 +01:00
series: crystaldown
---
Crystal Down has a lot of visitors lately…

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 18
  | first %}

[ {{page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
