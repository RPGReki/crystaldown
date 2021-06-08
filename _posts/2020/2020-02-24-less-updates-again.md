---
title: Less Updates Again

date: 2020-02-24 01:11 +01:00
series: crystaldown
---
Things have been hasty the last few weeks. I think I need to reduce the number of chapters per week
for a while…

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 38
  | first %}

[ {{page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
