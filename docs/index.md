---
layout : default
---
 
{%- assign pages = site.pages | sort: "order"  -%}
{% for page in pages %}
{% if page.url != "/feed.xml" and  page.url != "/"   %}
    {{- page.content -}}
{% endif %}
{% endfor %}  
