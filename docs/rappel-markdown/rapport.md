---
layout: default
order: 3
---

# Rappel Markdown

## Introduction

![Logo Markdown](/lab-markdown/rappel-markdown/images/Markdown-mark.png){: width="400px" }_figure 1: Introduction_

<!-- note -->

Nous passerons en revue les balises Markdown, un langage léger utilisé pour formater du texte de manière simple et lisible. Nous fournirons un rappel des différentes balises disponibles ainsi qu'un exemple pour chacune d'elles. Que vous soyez débutant ou que vous souhaitiez simplement rafraîchir vos connaissances, ce laboratoire vous aidera à maîtriser Markdown pour améliorer la présentation de vos documents .

## Titres

- Exemple :

```
# Titre de niveau 1
## Titre de niveau 2
### Titre de niveau 3
#### Titre de niveau 4
##### Titre de niveau 5
###### Titre de niveau 6
```

## Texte en gras

- Exemple :

**Texte en gras**

## Texte en italique

- Exemple :

_Texte en italique_

## Texte barré

- Exemple :

~~Texte barré~~

## Liens

- Exemple :

```bash

[Texte](https://www.link.org/)

```

[https://www.markdownguide.org/](https://www.markdownguide.org/)

## Images

- Exemple :

```bash
![alt](/lab-markdown/rappel-markdown/images/markdownlogo.png)

```

![Logo Markdown](/lab-markdown/rappel-markdown/images/markdownlogo.png)_figure 2: exemple de image en markdown_

Les images peuvent avoir des attributs de style en ligne tels que la largeur et la hauteur:

```bash

![Alt](/lab-markdown/rappel-markdown/images/markdownlogo.png){: width="100" height="100"}

```

![Logo Markdown](/lab-markdown/rappel-markdown/images/markdownlogo.png){: width="100" height="100"}_figure 3: exemple de resize image en markdown_

## Listes non ordonnées

- Exemple :

- Élément 1
- Élément 2
- Élément 3

## Listes ordonnées

- Exemple :

1. Premier élément
2. Deuxième élément
3. Troisième élément

## Citations

- Exemple :

```bash

> Ceci est une citation

```

## Code en ligne

- Exemple :

Utilisez la balise `<code>` pour afficher du code en ligne.

## Blocs de code

- Exemple :

```markdown
gh pr create
```

## Tables

- Exemple :

```table
| Nom   | Âge | Ville    |
|-------|-----|----------|
| Alice | 30  | New York |
| Bob   | 25  | Paris    |
| Eve   | 35  | London   |

```

## Checkbox

- Exemple :

```checkbox

- [x] Tâche terminée
- [ ] Tâche à faire

```

<!-- note -->