---
layout: page
title: Home
id: home
permalink: /
---

# Hello!✨

I'm Sky.

I put my articles and notes here to learn with my garage door open.

My writing will be in English or 中文, whatever felt natural at the moment.

# My Writings🧐

{% for post in site.posts %}
<article>
  <a href="{{ post.url }}">
    {{ post.title }}
  </a>
</article>
{% endfor %}

# Book Notes📚

{% for book in site.books %}
<article>
  <a href="{{ book.url }}">
    {{ book.title }}
  </a>
</article>
{% endfor %}

# Idea Notes✏️

{% for note in site.notes %}
<article>
  <a href="{{ note.url }}">
    {{ note.title }}
  </a>
</article>
{% endfor %}

<style>
  .wrapper {
    max-width: 46em;
  }
</style>