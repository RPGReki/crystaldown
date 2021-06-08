---
published: false
layout: 2020/volume
type: volume
title: "Volume 2: Vampire Aide and Exodus"
excerpt: "Volume 2 of Crystal Down Web Novel: Vampire Aide and Exodus"
date: 2020-10-16
shortlink: /cd/2/e/
robots: noindex
sitemap: false
---
{% assign pages = site.pages
  | where: "lang", "en-CA"
  | where: "type", "chapter"
  | where: "book.series", page.book.series
  | where: "book.number", page.book.number
  | sort: "chapter" %}
<style>
  main {
    counter-reset: chapter;
  }

  h2::before {
    counter-increment: chapter;
    content: "Chapter " counter(chapter) ": ";
  }
</style>


{% for page in pages %}
{% if jekyll.environment != "unpublished" and page.published == "sponsors" %}{% break %}{% endif %}
{% if jekyll.environment != "unpublished" and page.published == "pre-sponsors" %}{% break %}{% endif %}
<article>
<h2>{{ page.title }}</h2>
{{ page.content }}
</article>
{% endfor %}

[Prologue: The Bus Factor](./00-prologue-the-bus-factor/){:id="next" style="display: none"}
