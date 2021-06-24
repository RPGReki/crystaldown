---
layout: 2020/base
type: base
title: "Crystal Down Web Novel Overview"
date: 2019-11-11
shortlink: /cd/
excerpt: "Meet Swift who just got reincarnated as a 10-year-old catling after a traffic accident. Having just woken up in a new world with no real explanation, our kitten shows he lacks any common sense whatsoever…"

book:
  series: Crystal Down

intermediate_breadcrumbs:
  -
    title: Archived Projects
    url: /archive/

feed: /crystaldown/chapters.xml
scribblehub: https://www.scribblehub.com/series/75079/crystal-down/

---
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "BreadcrumbList",
  "itemListElement": [{
    "@type": "ListItem",
    "position": 0,
    "name": "{{ site.title }}",
    "item": "{{ "/" | absolute_url }}"
  }, {
    "@type": "ListItem",
    "position": 1,
    "name": "Crystal Down",
    "item": "{{ "/crystaldown/" | absolute_url }}"
  }]
}
</script>

<!-- markdownlint-disable MD025 -->
# {{ page.title }}

{% include series-overview/urls.html %}

## Disclaimer

{% include series-overview/disclaimer.md %}

## Volume&nbsp;01: Life&nbsp;in&nbsp;Avan&nbsp;Forest

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Book",
  "url": "{{ page.url | absolute_url }}#volume01-lifeinavanforest",
  "name": "{{ site.book.series }} 1: Life in Avan Forest",
  "position": "1",
  "copyrightYear": "2019-2020",
  "inLanguage": "en-CA",
  "author": {
    "@type": "Person", {% assign author = site.data.staff | where: "id", page.author | last %}
    "name": "{{ author.name }}",
    "url": "{{ author.url }}"
  },
  "publisher": {
    "@type": "Person",
    "name": "{{ author.name }}",
    "url": "{{ author.url }}"
  }
}
</script>

<!-- markdownlint-disable MD033 -->
<div class="row">
<div class="col-12 col-md-3">
{% if page.canonical_domain %}
<img src="thumbnail.webp" alt="Crystal Down Cover: boy with cat ears sleeps on the lap of another boy">
{% else %}
<img src="{{ page.path | replace: 'index.md', '/thumbnail.webp' | prepend: '/' | prepend: site.static_url | absolute_url }}" alt="Crystal Down Cover: boy with cat ears sleeps on the lap of another boy">
{% endif %}
</div>
<div class="col-12 col-md-9">
Meet Swift Mittens who just got reincarnated as a 10-year-old catling after a traffic accident.
Having just woken up in a new world with no real explanation, our kitten shows he lacks any common sense whatsoever while he tries to cope with his situation as good as he can: being alone in the middle of nowhere, with no fixed shelter, no stable source of food — but with a kind of gaming interface and his not so helpful knowledge from playing MMOs in his past life.
A good start to an adventure… or it would be an adventure if he didn't hole himself up in the middle of the forest in the first place!

<h3 class="mt-3"> Life in Avan Forest Chapters</h3>

{% assign pages = site.pages
  | where: "lang", "en-CA"
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | sort: "chapter" %}

{% include series-overview/chapter-list.html %}
</div>
</div>
<!-- markdownlint-enable MD033 -->

[Prologue: The Bus Factor](./01-life-in-avan-forest/00-prologue-the-bus-factor/){:id="next" style="display: none"}

## Volume&nbsp;02: Vampire&nbsp;Aide&nbsp;and&nbsp;Exodus

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Book",
  "url": "{{ page.url | absolute_url }}#volume02-vampireaideandexodus",
  "name": "{{ site.book.series }} 2: Vampire Aide and Exodus",
  "position": "1",
  "copyrightYear": "2020",
  "inLanguage": "en-CA",
  "author": {
    "@type": "Person", {% assign author = site.data.staff | where: "id", page.author | last %}
    "name": "{{ author.name }}",
    "url": "{{ author.url }}"
  },
  "publisher": {
    "@type": "Person",
    "name": "{{ author.name }}",
    "url": "{{ author.url }}"
  }
}
</script>

Swift Mittens has been reincarnated in another world as a ten-year-old catling after a traffic accident.
After setting up his base in Avan Forest he was named to be the keeper of the hill he happened to dug his cave into.
He befriends Matthew, the second price of Sitnalta and ends up joining Matthew and his group for a simple errand to a dairy farm village.
After returning from the way too eventful trip, Matthew's aide Patrick gets badly poisoned!

### Vampire Aide and Exodus Chapters

{% assign pages = site.pages
  | where: "lang", "en-CA"
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 2
  | sort: "chapter" %}

{% include series-overview/chapter-list.html %}

### Glossary

See the [Crystal Down Glossary](./glossary/){:.btn .btn-large .btn-primary}.
