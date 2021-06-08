---
title: "References"

date: 2020-07-17 01:11 +02:00
series: crystaldown
---
Incorporating references is fun and so, but I'm never sure if my readers actually get them.

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 53
  | first %}

[ {{page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
