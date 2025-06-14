---
layout: default
title: "AI Insights - English"
permalink: /r/AI-Insights/EN/
repo: AI-Insights
---
# AI Insights - English Archives

{% assign posts = site.ai_insights | where:"lang", "EN" | sort: "month" | sort: "year" | reverse %}

{% for post in posts %}
<article id="{{ post.year }}-{{ post.month }}">
  {{ post.content }}
  <hr>
</article>
{% endfor %}