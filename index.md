{% for item in site.pages | where: 'title' | sort: 'title' %}
- [{{item.title}}]({{item.url}})
{% endfor %}
