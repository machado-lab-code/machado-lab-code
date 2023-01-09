---
title: "Machado Lab - News"
layout: gridlay
excerpt: "Machado Lab: News"
sitemap: false
permalink: /news/
---

# News

{% for article in site.data.news %}
**{{ article.date }}**
{{ article.headline | markdownify}}
{% endfor %}
