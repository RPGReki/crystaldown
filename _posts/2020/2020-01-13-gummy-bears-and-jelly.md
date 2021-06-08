---
title: Gummy Bears and Jelly
---
Gummy bears and jelly have the same ingredients, the only difference is the water content.
Some gummy bear variants have a coating of wax added so they don't stick.

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 20
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
