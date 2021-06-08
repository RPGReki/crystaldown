---
title: "More Options"

date: 2020-07-10 16:05 +02:00
series: crystaldown
---
I was motivated to revamp my code. While I was at it, I also added 2 more options to the page:
Toggle Line Height and Toggle Dyslexic Font.

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 51
  | first %}

[ {{page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
