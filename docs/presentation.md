---
layout: presentation
order: 1
---
<<<<<<< HEAD

=======
>>>>>>> develop

{% assign pages = site.pages | sort: "order" %}
{% for page in pages %}
 {% if page.chapitre and page.chapitre != "Rappele markdown" %}
    {{- page.content | markdownify -}}
  {% endif %}
<<<<<<< HEAD

{% endfor %}
   
 
=======
{% endfor %}
>>>>>>> develop
