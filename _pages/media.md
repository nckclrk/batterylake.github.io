---
layout: archive
title: "Media"
permalink: /media/
author_profile: true
---

{% for post in site.media reversed %}
  <article>
    <h2><a href="{{ post.link }}">{{ post.title }}</a></h2>
    <p><strong>{{ post.venue }}</strong>, {{ post.date | date: "%B %d, %Y" }}</p>
  </article>
{% endfor %} 