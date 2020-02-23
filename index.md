---
layout: home
---
# Mike Bloomberg wants to be your President!

{% for fact in site.facts %}
## {{ fact.title }}
{{ fact.content }}
(<a href="{{ fact.source }}">source</a>)
{% endfor %}
