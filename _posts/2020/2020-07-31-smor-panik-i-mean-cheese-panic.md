---
title: "Smør-Panik, I mean Cheese Panic!"
---
It's a butter crisis too! smør-panik! But cheese is much more storable!

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 56
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
