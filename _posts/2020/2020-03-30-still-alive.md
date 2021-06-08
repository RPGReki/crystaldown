---
title: Still Alive

date: 2020-03-30 01:11 +02:00
series: crystaldown
---
I'm still alive. This isn't a good time to catch the flu. But I'm back under the living, for now.

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 43
  | first %}

[ {{page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
