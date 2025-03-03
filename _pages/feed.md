---
layout: archive
title: "Feed"
permalink: /feed/
author_profile: true
---

<div class="archive">
{% for post in site.posts %}
  <p>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <small>{{ post.date | date: "%B %d, %Y" }}</small>
  </p>
{% endfor %}
</div> 