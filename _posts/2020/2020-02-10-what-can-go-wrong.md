---
title: What Can Go Wrong?

date: 2020-02-10 01:11 +01:00
series: crystaldown
---
What's the worst thing that can happen to you when you go shopping?
Leaving your wallet at home?
Or running out of gas while driving?

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 32
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
