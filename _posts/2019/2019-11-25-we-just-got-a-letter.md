---
title: "♫ We Just Got A Letter ♫"

date: 2019-11-25 11:11 +01:00
series: crystaldown
---

I don't like the show this quote is from, in fact, I was already an adult when I first saw the show,
but it's so damn catchy!

♫ We just got a letter! We just got a letter! We just got a letter! I wonder who it's from. ♫

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 2
  | first %}

[ {{page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
