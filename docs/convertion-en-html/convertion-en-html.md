---
layout: default
chapitre: Outil de conversion de Markdown en HTML
order: 8
---
# Outil de conversion de Markdown en HTML
  
![Pandoc](/lab-markdown\8.convertion-en-html\images\pandoc.png){: width="500px"}
*Figure: Pandoc*

<!-- note -->
Pandoc est un outil polyvalent en ligne de commande permettant de convertir entre différents formats de document. Il prend en charge une large gamme de formats d'entrée et de sortie, notamment Markdown, HTML, LaTeX, PDF, DOCX, et bien d'autres..
## Command

```bash
pandoc presentation.md -f markdown -t html -s -o présentation.html
```
## Outil 
[Pandoc](https://github.com/jgm/pandoc/releases/tag/3.1.12)

## Livrables

- [Rapport](/lab-markdown/8.convertion-en-html/rapport.html)
- [Presentation](/lab-markdown/8.convertion-en-html/presentation.html)
