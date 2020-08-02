---
layout: page
title: Home
id: home
permalink: /
---

# Welcome!✨

Hey there! I'm Sky Lan, welcome to my tiny piece of land.

I will be adding posts and notes here to learn with my garage door open.

My writing will be in English or 中文, whichever felt natural at the moment.

# Posts🧐

{% for post in site.posts %}
  <article>
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
  </article>
{% endfor %}

# Notes✏️
{% for note in site.notes %}
  <article>
    <h3>
      <a href="{{ note.url }}">
        {{ note.title }}
      </a>
    </h3>
  </article>
{% endfor %}


<style>
  .wrapper {
    max-width: 46em;
  }
</style>
