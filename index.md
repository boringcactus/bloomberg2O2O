---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
Mike Bloomberg should not be President.

{% for fact in site.facts %}
# {{ fact.title }}
{{ fact.content }}
(<a href="{{ fact.source }}">source</a>)
{% endfor %}
