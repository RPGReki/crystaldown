---
title: Childhood Memories about Pepperoni Pizza
---
Being a native German speaker, I had the wrong impression about Americans and their cartoon characters eating pizza spicy.
All due to a single false friend.
It doesn't help when 90% of all “translations” just say „Peperonipizza” for pepperoni pizza.
That German word would correctly translate to “hot pepper pizza”.
I only found out recently when watching some random YouTube video.
What a way to ruin my childhood memories…
Now to ruining Swift's dinner…

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | where: "chapter", 9
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
