---
title: "References, the Scientific Kind"

date: 2020-07-20 01:11 +02:00
series: crystaldown
---
Let me quote one of my favourite stand-up mathematicians: “The question is not how much data supports your thesis.
The question is how much data did you ignore.”

Also, there will be no chapter on Friday.
My usual chair broke and I got a replacement one.
It's slightly shorter.
I did not expect to get neck pain from 2cm less height.

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 54
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
