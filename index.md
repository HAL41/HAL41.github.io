---
layout: default
---
{% capture readme_content %}{% include_relative README.md %}{% endcapture %}
{{ readme_content | markdownify }}

## Repositories
<!-- Repositories list -->
{% for repo_name in site.data.repos %}
  <ul>
    <li><strong><a href="/r/{{ repo_name }}/">{{ repo_name }}</a></strong></li>
  </ul>
{% endfor %}