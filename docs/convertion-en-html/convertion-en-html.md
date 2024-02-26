---
layout: default
chapitre: outil de convertion md en html
order: 8
---
# Outil de convertion md en html
![Pandoc](/lab-markdown/convertion-en-html/images/pandoc.png)
*figure: Pandoc*

<!-- note -->
Pandoc est un outil polyvalent en ligne de commande permettant de convertir entre différents formats de document. Il prend en charge une large gamme de formats d'entrée et de sortie, notamment Markdown, HTML, LaTeX, PDF, DOCX, et bien d'autres..
## Command

```bash
pandoc presentation.md -f markdown -t html -s -o convertion-en-html.html
```
## Outil 
[Pandoc](https://github.com/jgm/pandoc/releases/tag/3.1.12)

## Livrables
- [Rapport](/lab-markdown/convertion-en-html/rapport.html)
- [Presentation](/lab-markdown/convertion-en-html/presentation.html)
