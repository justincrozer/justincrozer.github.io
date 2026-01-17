---
title: Justin Crozer
header: "echo ${core_dump} > /www/blog"
description: "Linux, tech,  notes, thoughts, and things I found worth jotting down when I should have been doing something more productive (actually working). I'm Justin, this is my blog. Hi."
permalink: /
layout: default
---

{% for post in site.posts %}
  <p class="blog-item"><b><a href="{{ post.url }}">{{ post.title }}</a></b><br>
  <span class="post-description">{{ post.description }}</span><br>
  <span class="post-meta">📅 {{ post.date | date_to_string }}</span></p>
{% endfor %}

<!-- **THESE LINKS ARE HIDDEN ON THE FRONT END** - they're only used for Mastodon verification purposes -->
<div class="verification-links">
  <a rel="me" href="https://fosstodon.org/@justincrozer">Mastodon</a>
</div>
