---
title: "Moon Phases"

date: 2020-10-19 01:11 +02:00
series: crystaldown
---
Moon phases are a wonderful things, aren't they?
Do you still remember Swift is a Lunar Wanderer Ailuranthrope?
One could ask why that subrace and its traits aren't shown in the UI…

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 2
  | where: "chapter", 66
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
