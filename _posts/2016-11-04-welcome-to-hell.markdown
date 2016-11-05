---
layout: post
title:  "Welcome to HELLo Jekyll!"
date:   2016-11-04 22:12:00 -0500
categories: jekyll hate
author: jeremy
---
Jekyll. It's like MovableType for GitHub. Right? Am I Right?

{% assign author = site.data.people[page.author] %}
<a rel="author"
  href="{{ author.linkedin }}"
  title="{{ author.name }}">
    {{ author.name }}
</a>