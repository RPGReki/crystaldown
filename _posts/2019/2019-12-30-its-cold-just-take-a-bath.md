---
title: It's cold? Just take a hot bath!

date: 2019-12-30 11:11 +01:00
series: crystaldown
---
The best thing when it's cold is taking a nice hot bath. Only a hot spring could make it better!

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 14
  | first %}

[ {{page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
