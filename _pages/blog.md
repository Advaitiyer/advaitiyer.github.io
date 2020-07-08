---
title: "Blog"
layout: archive
permalink: /blog/
author_profile: true
---

{% for post in site.posts.blog %}
  {% include archive-single.html %}
{% endfor %}
