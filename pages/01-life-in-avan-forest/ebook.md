---
published: private
layout: epub
type: volume
title: "Volume 1: Life in Avan Forest"
excerpt: "Volume 1 of Crystal Down Web Novel: Life in Avan Forest"
date: 2020-07-24
shortlink: /cd/1/e/
robots: noindex
sitemap: false
chapter: 101
---
<section epub:type="notice">
{% include_relative frontmatter/notice.html.inc %}
</section>

<section epub:type="imprint">
{% include_relative frontmatter/imprint.html.inc %}
</section>

<section epub:type="acknowledgments">
{% include_relative frontmatter/acknowledgments.html.inc %}
</section>

<section epub:type="copyright-page">
{% include_relative frontmatter/copyright.html.inc %}
</section>

<section epub:type="preface">
{% include_relative frontmatter/preface.html.inc %}
</section>

{% assign pages = site.pages  
  | where: "lang", "en-CA"
  | where: "type", "chapter"
  | where: "book.series", page.book.series
  | where: "book.number", page.book.number
  | sort: "chapter" %}

{% for page in pages %}
{% if jekyll.environment != "unpublished" and page.published == "sponsors" %}{% break %}{% endif %}
{% if jekyll.environment != "unpublished" and page.published == "pre-sponsors" %}{% break %}{% endif %}
<section epub:type="{% unless page.chapter == 0 %}chapter{% else %}prologue{% endunless %}">
<h1>{{ page.title }}</h1>
{{ page.content }}
</section>
{% endfor %}

<section epub:type="afterword">
{% include_relative afterword.html.inc %}
</section>

<section epub:type="epilogue">
{% include_relative epilogue.html.inc %}
</section>
