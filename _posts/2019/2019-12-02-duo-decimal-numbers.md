---
title: "Duodecimal Numbers"
---
This novel includes duodecimal numbers.
Until Swift learns how the numbers a read all numbers are converted to decimal in the ruby annotations.
Like this: {%include ruby base="10" text="twelve" %}

After that, it will be how the numbers are read, though I will be changing how some numbers are read.
Like this: {%include ruby base="20" text="two dozen" %}

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 3
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->

If you want to learn more right now, why don't you watch a video of Numberphile about it?

{% include youtube.htmlvideotitle="Base 12 - Numberphile" videoid="U6xJfP7-HCc" %}
