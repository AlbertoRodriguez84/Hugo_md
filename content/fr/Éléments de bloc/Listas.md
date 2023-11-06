+++
title = 'Listes'
date = 2023-11-01T19:12:24+01:00
draft = false
+++

Contrairement à ce qui se passe en HTML, générer des listes dans Markdown est extrêmement simple. Vous pouvez rencontrer deux types.

### Listes non ordonnées
____
Pour créer des **listes non ordonnées**, utilisez ```*``` **astérisques**, ```` -``` **traits d'union** ou ```+``` **symbole plus** .
```
- Élément de liste 1
- Élément de liste 2
* Élément de liste 3
* Élément de liste 4
+ Élément de liste 5
+ Élément de liste 6
```
Peu importe l'élément que vous choisissez, vous pouvez même les échanger. Ils auront tous la même apparence une fois traités.

- Élément de liste 1
- Élément de liste 2
* Élément de liste 3
* Élément de liste 4
+ Élément de liste 5
+ Élément de liste 6
  
Pour générer des **listes imbriquées** dans d'autres, vous devrez simplement ajouter **quatre espaces avant le prochain ```*```, ```` -``` ou ```+```.
```
- Élément de liste 1
- Élément de liste 2
    - Élément de liste 3
    - Élément de liste 4
        - Élément de liste 5
        - Élément de liste 6
```
- Élément de liste 1
- Élément de liste 2
    - Élément de liste 3
    - Élément de liste 4
        - Élément de liste 5
        - Élément de liste 6
### Listes ordonnées
___
Pour créer des listes ordonnées, vous devez utiliser la syntaxe de type : « numéro ». 1. Comme pour les listes non ordonnées, vous pouvez également les imbriquer ou les combiner.
```
1. Élément de liste 1
2. Élément de liste 2
    - Élément de liste 3
    - Élément de liste 4
        1. Élément de liste 5
        2. Élément de liste 6
```

1. Élément de liste 1
2. Élément de liste 2
    - Élément de liste 3
    - Élément de liste 4
        1. Élément de liste 5
        2. Élément de liste 6