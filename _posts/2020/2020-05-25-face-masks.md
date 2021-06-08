---
title: "Face Masks"
---
So I've been on the train today.
In Germany, you are required to wear masks while you travel with any public transport.
But some people just wear that damn thing as an accessory.
Or they don't have one at all.
Just wear the damn mask properly!!
Thank you.

Anyway, stay healthy and enjoy the chapter.

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 46
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
