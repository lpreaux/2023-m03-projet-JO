# 2023-m03-projet-JO

> Projet pédagogique réalisé pendant la formation Diginamic en 2023. Ce dépôt conserve les livrables de conception ; ce n'est pas une application maintenue.

Projet réalisé avec [Visual Paradigm](https://www.visual-paradigm.com/).

Pour le rendu, une Release GitHub contient une archive du dossier `rendu`. Le détail reste consultable dans le dépôt (cf. [Contenu du dépôt
](#contenu-du-d%C3%A9pot) pour plus d'info)

## Contenu du dépot

1. Le projet Visual Paradigm : `JO.vpp` (à la racine du dépôt).
2. Les fichiers de rendu dans le dossier `rendu` :
    - Une présentation compilant les diagrammes au format pptx et pdf.
    - Les 3 diagrammes au format jpg

## Organisation du projet Visual Paradigm

- Un dossier `Conception` contenant les diagrammes et les éléments composant les diagrammes.
- Un package `fr.diginamic.jo` contenant les représentations UML des entités et classes métier. Hormis la classe exécutable `InsertionAthletes`, les représentations sont séparées dans les sous-packages `entites`, `services` et `dao`.
- Un dossier `Modèle physique` qui contient les représentations d'entités du modèle physique de données ERD.
