---
title: After the Rain

date: 2020-03-09 01:11 +01:00
series: crystaldown
---
What's best after a trip in the cold rain? A hot bath!

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 42
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
