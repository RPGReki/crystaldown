---
title: "Good Ideas…"

date: 2020-05-18 01:11 +02:00
series: crystaldown
---
Is it just me, or do the good ideas only come when you're about to take a dump?

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 45
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
