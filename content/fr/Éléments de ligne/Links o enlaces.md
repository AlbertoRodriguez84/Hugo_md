+++
title = 'Liens'
date = 2023-11-01T19:13:18+01:00
draft = false
+++

Ajouter des liens vers une publication, plus que courant, est aujourd'hui quelque chose de **presque obligatoire**. Avec Markdown, vous aurez plusieurs façons de le faire.

### Liens ou liens en ligne
___
Ce sont les liens d’une vie. Comme leur nom l’indique, ils sont conformes au texte.

Ils sont créés en écrivant le mot ou le texte lié entre ```[] ```**crochets**, et le lien en question entre ```()``` **parenthèses**.

| MARQUAGE | RÉSULTAT |
| ```[lien en ligne](http://www.limni.net)``` | lien en ligne |

### Liens ou liens de référence
____
L’inconvénient de la méthode précédente est que si vous utilisez des liens trop complexes ou trop longs, ils peuvent rendre difficile la lecture de votre texte.

Pour résoudre ce problème et créer votre contenu de manière plus organisée, vous pouvez générer des liens de référence.

Cela signifie que dans votre texte, vous relierez des **mots ou codes spécifiques** (constitués de lettres et/ou de chiffres), que vous aurez définis à un autre endroit plus éloigné de votre document comme certaines URL.

```
[nom que vous souhaitez donner à votre lien][nom de votre référence]
[nom de votre référence] : http:www.tuenlace.com
```
C'est plus clair avec un exemple.
```
Je m'appelle Javier Cristóbal et j'ai un blog sur [la productivité Mac][blog].
Dans ce [site Web] [blog], je compile des articles sur tout ce qui concerne l'automatisation, la gestion et l'efficacité.
[blog] : http://limni.net/blog
```

La référence ```[blog]``` peut être incluse n'importe où dans le document, afin que vous puissiez mieux vous organiser et de manière plus propre, en rassemblant toutes vos références en un seul endroit.


De plus, comme vous le voyez ci-dessous, cette référence n'est **pas incluse dans le résultat final**, mais disparaît.

«Je m'appelle Javier Cristóbal et j'ai un blog sur [la productivité Mac][blog].
Dans ce [site Web] [blog], je compile des articles sur tout ce qui concerne l'automatisation, la gestion et l'efficacité.
[blog] : http://limni.net/blog »

### Liens automatiques
____
Vous verrez ce formulaire au sein de différents éléments : liens automatiques