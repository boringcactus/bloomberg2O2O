---
layout: home
---
# Mike Bloomberg should not be President.

{% for fact in site.facts %}
## {{ fact.title }}
{{ fact.content }}
(<a href="{{ fact.source }}">source</a>)
{% endfor %}
