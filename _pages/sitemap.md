---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

<h2>Pages</h2>

{% assign allowed_urls = "/publications/|/talks/|/teaching/|/cv/|/marathon/" %}
{% for post in site.pages %}
  {% if allowed_urls contains post.url %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

