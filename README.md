# 2023-m03-projet-JO

Projet réaliser avec [Visual Paradigm](https://www.visual-paradigm.com/) (je suis plus habitué à cet outils plutot que StartUML).

Pour le rendu, j'ai fait une release GitHub avec une archive zip avec le contenu du dossier rendu. Si vous voulez voir le travail plus en détail, tout est dans le dépot. (cf. [Contenu du dépot
](#contenu-du-d%C3%A9pot) pour plus d'info)

## Contenu du dépot

1. Le projet Visual Paradigm : JO.vpp (A la racine du dépot)
2. Les fichiers de rendu dans le dossier `rendu` :
    - Une présentation compilant les diagrammes au format pptx et pdf.
    - Les 3 diagrammes au format jpg

## Organisation du projet Visual Paradigm

- Un dossier `Conception` contenant les diagrammes et les éléments composant les diagrammes.
- Un package `fr.diginamic.jo` contenant mes représentation UML d'entité metier et de class métier.   
Hormis la classe éxecutable InsertionAthletes qui est à la racine du package, les representations UML sont séparés dans des sous-packages `entites`, `services` et `dao`.
- Un dossier `Modèle physique` qui contient mes représentation d'entité pour le modèle physique de données ERD.
