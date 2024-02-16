---
layout: presentation
order: 1
---

{% assign pages = site.pages | sort: "order" %}
{% for page in pages %}
 {% if page.chapitre and page.chapitre != "table de matière" and page.chapitre != "table des Figures" %}
    {{- page.content | markdownify -}}
  {% endif %}
{% endfor %}