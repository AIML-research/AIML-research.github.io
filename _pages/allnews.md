---
title: "News"
layout: textlay
excerpt: "Artificial Intelligence and Machine Learning Group at Freie Universität Berlin."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline | markdownify}}</em></p>
{% endfor %}
