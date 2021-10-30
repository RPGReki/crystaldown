---
title: Just a snack, I mean a chat
category:
  - crystaldown
  - personal

link:
  series: Crystal Down
  volume_number: 2
  chapter: 74

image: /blog/images/2021-07-02-blood-bag.png
image_alt: Blood Bag (Symbolic Picture)

image_license: CC-BY-SA 3.0 ICSident at German Wikipedia
image_license_url: https://commons.wikimedia.org/wiki/File:Ics-codablock-blood-bag_sample.jpg

---
No, I'm not picking up this story again.
I was just doing some digital housekeeping and discovered I still had a chapter lying around.

Anyway, enjoy.

{% assign page = site.pages
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 2
  | where: "chapter", 74
  | first %}

[{{ page.title }}]({{ page.url | absolute_url }}){:.btn .btn-block .btn-primary .btn-lg}
<!--more-->
