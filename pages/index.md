---
layout: 2020/base
type: base
title: "Crystal Down Web Novel Overview"
date: 2019-11-11
shortlink: /cd/
excerpt: "Meet Swift who just got reincarnated as a 10-year-old catling after a traffic accident. Having just woken up in a new world with no real explanation, our kitten shows he lacks any common sense whatsoever…"

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
# Crystal Down Web Novel Overview

<!-- markdownlint-disable MD033 -->
<p class="social icons">
  {% if page.feed %}
  <link rel="alternate" type="application/atom+xml" href="{{ page.feed | absolute_url }}" title="{{ page.book.title }} Chapters Atom Feed">
  <a rel="alternate" type="application/atom+xml"
   href="{{ page.feed | absolute_url }}"
   title="{{ page.book.title }} Chapters Atom Feed">
    <img src="{{ '/assets/images/feed.png' | prepend: site.staticUrl | absolute_url }}" alt="Atom Feed">
  </a>
  {% endif %}
  {% if page.scribblehub %}
  <a href="{{ page.scribblehub }}" rel="alternate"
    target="_blank" rel="noopener nofollow" title="{{ page.book.title }} on Scribble Hub">
    <img src="{{ '/assets/images/scribblehub.png' | prepend: site.staticUrl | absolute_url }}" alt="Scribble Hub">
  </a>
  {% endif %}
  {% if page.wattpad %}
  <a href="{{ page.wattpad }}" rel="alternate"
    target="_blank" rel="noopener nofollow" title="{{ page.book.title }} on Wattpad">
    <img src="{{ '/assets/images/wattpad.png' | prepend: site.staticUrl | absolute_url }}" alt="Wattpad">
  </a>
  {% endif %}
</p>
<!-- markdownlint-enable MD033 -->

## Disclaimer

This is a work of fiction.
Names, characters, places, and incidents are the product of the author's imagination or are used fictitiously.
Any resemblance to actual events, locales, or persons, living or dead, is coincidental.

## Volume&nbsp;01: Life&nbsp;in&nbsp;Avan&nbsp;Forest

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Book",
  "url": "{{ page.url | absolute_url }}#volume01-lifeinavanforest",
  "name": "{{ site.title }} 1: Life in Avan Forest",
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
<img src="{{ page.path | replace: 'index.md', '/thumbnail.jpg' | prepend: '/' | prepend: site.staticUrl }}" alt="Crystal Down Cover: boy with cat ears sleeps on the lap of another boy">
</div>
<div class="col-12 col-md-9">
Meet Swift Mittens who just got reincarnated as a 10-year-old catling after a traffic accident.
Having just woken up in a new world with no real explanation, our kitten shows he lacks any common sense whatsoever while he tries to cope with his situation as good as he can: being alone in the middle of nowhere, with no fixed shelter, no stable source of food — but with a kind of gaming interface and his not so helpful knowledge from playing MMOs in his past life.
A good start to an adventure… or it would be an adventure if he didn't hole himself up in the middle of the forest in the first place!

<h3 class="mt-3"> Life in Avan Forest Chapters </h3>

{% assign pages = site.pages
  | where: "lang", "en-CA"
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 1
  | sort: "chapter" %}

<ul style="list-style: none">{% for page in pages %}
{% if jekyll.environment != "unpublished" and page.published == "sponsors" %}{% break %}{% endif %}
{% if jekyll.environment != "unpublished" and page.published == "pre-sponsors" %}{% break %}{% endif %}
  <li><span class="count w-3">{% if page.current_chapters %}{{ page.current_chapters }}{% else %}{{ page.chapter }}{% endif %}.</span> <a href="{{ page.url }}">{{ page.title }}</a></li>{% endfor %}
</ul>
<!-- markdownlint-enable MD033 -->
</div>
</div>

[Prologue: The Bus Factor](./01-life-in-avan-forest/00-prologue-the-bus-factor/){:id="next" style="display: none"}

## Volume&nbsp;02: Vampire&nbsp;Aide&nbsp;and&nbsp;Exodus

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Book",
  "url": "{{ page.url | absolute_url }}#volume02-vampireaideandexodus",
  "name": "{{ site.title }} 2: Vampire Aide and Exodus",
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
After returning from the way too eventful trip Matthew's aide Patrick gets badly poisoned!

{% assign pages = site.pages
  | where: "lang", "en-CA"
  | where: "type", "chapter"
  | where: "book.series", "Crystal Down"
  | where: "book.number", 2
  | sort: "chapter" %}

### Vampire Aide and Exodus Chapters

<!-- markdownlint-disable MD033 -->
<ul style="list-style: none">{% for page in pages %}
{% if jekyll.environment != "unpublished" and page.published == "sponsors" %}{% break %}{% endif %}
{% if jekyll.environment != "unpublished" and page.published == "pre-sponsors" %}{% break %}{% endif %}
  <li><span class="count w-3">{% if page.current_chapters %}{{ page.current_chapters }}{% else %}{{ page.chapter }}{% endif %}.</span> <a href="{{ page.url }}">{{ page.title }}</a></li>{% endfor %}
</ul>
<!-- markdownlint-enable MD033 -->

### Glossary

See the [Crystal Down Glossary](/crystaldown/glossary/){:.btn .btn-large .btn-primary}.
