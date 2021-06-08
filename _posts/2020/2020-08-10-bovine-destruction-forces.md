---
title: "Bovine Destruction Forces"

date: 2020-08-10 01:11 +02:00
series: crystaldown
---
There are quite a lot of bovine destruction forces, aren't there?

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 59
  | first %}

[ {{page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->

