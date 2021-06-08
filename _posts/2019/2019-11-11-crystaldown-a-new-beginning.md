---
title: "Crystal Down — A New Beginning"

date: 2019-11-11 11:11 +01:00
series: crystaldown
---

I did it again. I nuked a project to start a new one like it. But that's how it is: try, try and try
again until you succeed. Anyway, let's start from the beginning again:

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 0
  | first %}

[ {{page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
