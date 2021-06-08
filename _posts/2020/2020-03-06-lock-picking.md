---
title: Lock Picking
---
I can't pick locks. Not with the level of fine control I have. That is none.

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 41
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
