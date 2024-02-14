---
layout: default
chapitre: Rappel markdown
order: 5
---

# Rappel Markdown

<!-- note -->
## Introduction

Nous passerons en revue les balises Markdown, un langage léger utilisé pour formater du texte de manière simple et lisible. Nous fournirons un rappel des différentes balises disponibles ainsi qu'un exemple pour chacune d'elles. Que vous soyez débutant ou que vous souhaitiez simplement rafraîchir vos connaissances, ce laboratoire vous aidera à maîtriser Markdown pour améliorer la présentation de vos documents .

![Logo Markdown](/lab-markdown/5.Rappel-markdown/images/Markdown-mark.png){: width="400px" }*Figure 4: Logo de markdown*



##  Titres
  - Exemple :
  ```bash
    # Titre de niveau 1
    ## Titre de niveau 2
    ### Titre de niveau 3
    #### Titre de niveau 4
    ##### Titre de niveau 5
    ###### Titre de niveau 6
  ```

## Texte en gras
  - Exemple :
  ```bash
    **Texte en gras**
  ```

## Texte en italique
 - Exemple :
  ```bash
    *Texte en italique*
  ```

## Texte barré

 - Exemple :
  ```bash
    ~~Texte barré~~
  ```

## Liens

 - Exemple :

```bash

[Texte](https://www.link.org/)

```


[Markdown Guide](https://www.markdownguide.org/)


## Images

 - Exemple :
  
  ```bash
![alt](/lab-markdown/5.Rappel-markdown/images/markdownlogo.png)

  ```

![Logo Markdown](/lab-markdown/5.Rappel-markdown/images/markdownlogo.png)*Figure 5: Exemple de image en markdown*


Les images peuvent avoir des attributs de style en ligne tels que la largeur et la hauteur:

  ```bash

  ![Alt](/lab-markdown/5.Rappel-markdown/images/markdownlogo.png){: width="100" height="100"}

  ```

  ![Logo Markdown](/lab-markdown/5.Rappel-markdown/images/markdownlogo.png){: width="100" height="100"}*Figure 6: Exemple de resize image en markdown*


## Listes non ordonnées 

 -  Exemple :

  ```bash
    - Élément 1
    - Élément 2
    - Élément 3
  ```



## Listes ordonnées 

  - Exemple :

  ```bash
    1. Premier élément
    2. Deuxième élément
    3. Troisième élément
  ```

## Citations

  - Exemple :
  
  ```bash
    > Ceci est une citation
  ```

## Code en ligne

  - Exemple :
    ```bash
      Utilisez la balise `<code>` pour afficher du code en ligne.
    ```


## Blocs de code

  - Exemple :
  ```bash
    gh pr create 
  ```

## Tables

  - Exemple :

  ```bash
    | Nom   | Âge | Ville    |
    |-------|-----|----------|
    | Alice | 30  | New York |
    | Bob   | 25  | Paris    |
    | Eve   | 35  | London   |
  ```


## Checkbox

 -  Exemple :
   
  ```bash
    - [x] Tâche terminée
    - [ ] Tâche à faire 
  ```
<!-- new slide -->




