---
layout: default
order: 1
---

{% assign pages = site.pages | sort: "order" %}
{% for page in pages %}
 {% if page.chapitre %}
    {{- page.content | markdownify -}}
  {% endif %}
{% endfor %}



<<<<<<< HEAD
## Présentation 
[Présentation](https://labs-web.github.io/lab-markdown/presentation.html)
=======
>>>>>>> develop

