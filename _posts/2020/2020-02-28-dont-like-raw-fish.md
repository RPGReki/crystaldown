---
title: Don't Like Raw Fish?

date: 2020-02-28 01:11 +01:00
series: crystaldown
---
I've seen people doing this wrong:
If you're uncomfortable with eating raw fish, just get Sushi without raw fish!
Don't be a jerk towards the chef and open the Sushi to remove the fish…

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 39
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
