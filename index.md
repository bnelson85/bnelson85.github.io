{% for item in site.pages | sort: 'title' %}
- [{{item.title}}]({{item.url}})
{% endfor %}
