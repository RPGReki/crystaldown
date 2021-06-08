---
title: Some people…

date: 2020-02-12 01:11 +01:00
series: crystaldown
---
Some people just don't know when to quit…

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 33
  | first %}

[ {{page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
