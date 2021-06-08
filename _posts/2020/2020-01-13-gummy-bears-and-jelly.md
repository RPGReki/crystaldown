---
title: Gummy Bears and Jelly

date: 2020-01-13 01:11 +01:00
series: crystaldown
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
