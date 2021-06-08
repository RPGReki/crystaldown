---
title: Schnitzel

date: 2020-01-20 01:11 +01:00
series: crystaldown
---
Schnitzel — I could eat that every day — don't tell the Austrians I like eating it with different kinds of sauces.

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 23
  | first %}

[ {{page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
