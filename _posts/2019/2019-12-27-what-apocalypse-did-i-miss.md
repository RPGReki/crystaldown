---
title: What Apocalypse did I miss?

date: 2019-12-27 01:11 +01:00
series: crystaldown
---
The shops are open again today.
That just means one things — all the shops are overcrowded.
As if there's an apocalypse happening soon…

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 13
  | first %}

[ {{page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
