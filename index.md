{% for tab in site.tabs %}
- [{{ tab.title }}]({{ tab.url }})
{% endfor %}