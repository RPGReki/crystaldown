---
title: "Why am I very merry?"

date: 2020-07-06 01:11 +02:00
series: crystaldown
---
Why am I very merry? So very, very merry?! So very, very merry?

Oh yeah, it's the fiftieth chapter! BTW, childhood memories with Alfred J. Kwak are back.

What's Alfred Jodocus Kwak? This clip might juggle your memory: https://www.youtube.com/watch?v=lFqRTo5yJBk

Oh right, it's Alfred Jonathan Kwak in English.

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 50
  | first %}

[ {{page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
