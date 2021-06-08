---
title: "The Secret Cow Level?!"

date: 2020-08-03 01:11 +02:00
series: crystaldown
---
The Secret Cow Level or Not The Cow Level?

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 57
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
