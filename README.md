# Le traducteur patoisant

Un simple programme front-end qui traduit du français au normand

## Améliorations possibles

### Améliorations informatiques

- Présentation visuelle peu agréable à l'oeil actuellement.
- Quand un paragraphe commence par un terme traduisible (tout premier mot), il n'est pas traduit.
- Envisager la possibilité d'activier/désactiver le gras sur les mots.
- Rendre aléatoire la sélection d'une traduction quand plusieurs existent. Par exemple, **abeille** peut se traduire par **avette** ou par **mâoque à mié**

### Améliorations possibles par des patoisants

- Ajouter la forme plurielle des noms, qui manque actuellement: **2 âbres**, etc.
- Ajouter les formes conjuquées des verbes. Les verbes ne sont présents qu'à l'infinitif actuellement.

### Autres améliorations possibles

- Faire du ménage dans le lexique.
    - Il y a des traduction vides ("")
    - La présence de virgules indique souvent plusieurs mots possibles pour la traduction ou la source. À restructurer: une nouvelle ligne pour chaque mot à traduit, et une virgule avec des guillemets anglais pour chaque traduction possible.

## Ce qui ne peut pas se régler

- Les différences de genre. **Un pantalon** devient **une brague** en normand. Le traducteur ne peut pas tenir compte de l'accord des adjectifs, etc., sans analyseur grammatical. Le plus simple est de (1) tolérer la traduction avec le mauvais genre ou (2) de revoir le lexique manuellement pour ne proposer que des traduction de même genre.
- Le sens des mots n'est pas pris en compte par le traducteur. Les termes polysémiques comme **fort** (adverbe et adjectif) peuvent donc être difficiles à traduire. Est-ce qu'on peut dire à la fois **néru bougui** (fort embarrassé), **souliers forts** (souolyis nérus) et **néru dépourvue** (fort dépourvue) en normand? Je ne sais pas. Ce n'est qu'un exemple parmi sans doute plusieurs autres.
