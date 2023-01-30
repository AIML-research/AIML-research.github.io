---
title: "News"
layout: textlay
excerpt: "Artificial Intelligence and Machine Learning Group at  Bundeswehr University Munich."
sitemap: false
permalink: /allnews.html
---

## News

{% for article in site.data.news %}
<b> {{ article.date }} </b> <br>
{{ article.headline | markdownify}}
{% endfor %}
