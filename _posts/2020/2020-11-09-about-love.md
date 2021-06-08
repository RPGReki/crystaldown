---
title: "About Love"

date: 2020-11-09 01:11 +01:00
series: crystaldown
---
Let's talk real here…
Just because there's love doesn't mean this story is going to include sex.
And I'm not planning on ripping of High School DxD.
At least, not yet.

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 2
  | where: "chapter", 71
  | first %}

[ {{page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
