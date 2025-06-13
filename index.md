---
layout: default
---

{% capture readme %}{% include_relative README.md %}{% endcapture %}
{{ readme | markdownify }}

## Repositories
<ul>
{% for repo in site.data.repos %}
  <li><a href="/{{ repo[0] }}/">{{ repo[0] }}</a></li>
{% endfor %}
</ul>
