{% for tab in site.tabs %}
- [{{ tab.title }}](/{{ site.github.repository_name }}{{ tab.url }})
{% endfor %}