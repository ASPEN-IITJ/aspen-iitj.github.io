---
title: "News"
layout: textlay
excerpt: "ASPEN Lab at IIT Jodhpur"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}