---
title: "News"
layout: textlay
excerpt: "Artificial Intelligence and Machine Learning Group at Freie Universität Berlin."
sitemap: false
permalink: /allnews.html
---

## News

{% for article in site.data.news %}
<b> {{ article.date }} </b> <br>
{{ article.headline | markdownify}}
{% endfor %}
