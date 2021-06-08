---
title: "International Cuisine"
---
Speaking of International Cuisine… what's typical food for a certain country?
How do you define it?
Is it what people there like eating?
Or is it things you can only get in a certain country?
I mean you can almost get everything anywhere!

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 51
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
