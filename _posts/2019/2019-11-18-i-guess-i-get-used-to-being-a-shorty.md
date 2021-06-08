---
title: "I guess I need to get used to being a shorty…"

date: 2019-11-18 11:11 +01:00
series: crystaldown
---

I guess I need to get used to being a shorty… 😭

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 1
  | first %}

[ {{page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->