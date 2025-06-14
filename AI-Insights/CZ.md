---
layout: default
title: "AI Insights - Czech"
permalink: /r/AI-Insights/CZ/
repo: AI-Insights
---
# AI Insights - Český archiv

{% assign posts = site.ai_insights | where:"lang", "CZ" | sort: "month" | sort: "year" | reverse %}

{% for post in posts %}
<article id="{{ post.year }}-{{ post.month }}">
  {{ post.content }}
  <hr>
</article>
{% endfor %}