---
title: "Creativity = Experimentation"

date: 2020-10-23 01:11 +02:00
series: crystaldown
---
Being creative means experimenting!
{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 2
  | where: "chapter", 67
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
