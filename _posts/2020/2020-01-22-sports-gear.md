---
title: Sports Gear

date: 2020-01-22 01:11 +01:00
series: crystaldown
---
Why do the more interesting sports all need expensive gear to do? Good gear is so expensive…

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 24
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
