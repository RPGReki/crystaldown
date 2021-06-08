---
title: Keeping Pets

date: 2020-01-27 01:11 +01:00
series: crystaldown
---
Cats are pets that do have their own character.
If you want a pet that obediently listens to orders get a dog instead.

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 26
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
