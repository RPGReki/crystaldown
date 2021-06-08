---
title: Dissolving with Slimes
---
“I will try not to mention the dissolving of the convict…”

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 37
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
