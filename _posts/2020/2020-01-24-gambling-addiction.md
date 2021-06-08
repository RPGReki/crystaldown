---
title: Gambling Addiction

date: 2020-01-24 01:11 +01:00
series: crystaldown
---
Gambling is addicting.
But with the right people, it sure is fun.
Don't gamble for real money!

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 25
  | first %}

[ {{page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
