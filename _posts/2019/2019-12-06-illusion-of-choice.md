---
title: Illusion of Choice

date: 2019-12-06 23:11 +01:00
series: crystaldown
---
Many games offer a lot of choices, but usually, I manage to choose one of the few combinations that make the game almost impossible to finish.
In other cases, the choice ceases to be one because it's mathematically provable a certain combination is better than another.
Is it still a choice?

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 4
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
