---
title: "The Mad Cow Disease in the Media"

date: 2020-07-13 01:11 +02:00
series: crystaldown
---
The Mad Cow Disease was big in the news in 90s.
 ut news these days don't care much about it anymore.
 But it's still around and breaks out from time to time.

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 52
  | first %}

[ {{page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
