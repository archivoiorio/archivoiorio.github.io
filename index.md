---
layout: null
---
{% for file in site.static_files %}
    {{ file.path }}
{% endfor %}
