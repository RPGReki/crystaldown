---
title: My Inspriration Is Back!
---
My inspiration is back. For now.
I hope it stays that way.

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 44
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
