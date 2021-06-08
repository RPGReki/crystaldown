---
title: "Final Chapter"

date: 2020-10-05 01:11 +02:00
series: crystaldown
---
Final Chapter… time to move on… from Volume 1.

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 62
  | first %}

[ {{page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
