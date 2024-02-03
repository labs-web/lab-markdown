---
layout : default
---

<!-- Ce script affiche tous les pages dans la page index.html -->
{%- assign pages = site.pages | sort: "order"  -%}
{% for page in pages %}
{% if page.url != "/feed.xml" and  page.url != "/"   %}
    {{- page.content -}}
{% endif %}
{% endfor %}  
