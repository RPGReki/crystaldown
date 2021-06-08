---
title: Thoughts on Building Your Own House

date: 2019-12-13 23:11 +01:00
series: crystaldown
---
When building your own house you decide what it looks like and what rooms it has.
Do you want a secret room? Yeah, build one.
Not that Swift got that idea…

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 6
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->