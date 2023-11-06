+++
title = 'Code'
date = 2023-11-01T19:13:40+01:00
draft = false
+++

Selon le type de publications (notamment celles de nature technique), vous devrez ajouter de petites sections où vous pourrez afficher du code d'une autre langue, des raccourcis clavier ou d'autres contenus qui ne doivent pas être traités comme tels.

Pour cela, vous disposez de deux alternatives.

#### Code pur ```<code>```
Le moyen le plus simple d'écrire du code dans Markdown est de placer le texte entre deux guillemets simples ``` ` ```. Cela correspond à la balise HTML ```<code>```
'''
`C'est une ligne de code`
'''
   
Cela ressemblera à « Ceci est une ligne de code ».

Comme vous pouvez le constater, c'est très utile pour saisir du code dans la même ligne ou paragraphe, ce que la méthode suivante ne permet pas.

#### Texte préformaté ```<pre>```
    
L'autre façon d'ajouter du code dans Markdown est de **commencer le paragraphe avec quatre espaces vides**. Cela correspond à la balise HTML ```<pre>```

```
 Ceci est une ligne de code

```
Devient

```
Ceci est une ligne de code
```


Attention, vous devez inclure ces espaces **dans chaque ligne que vous écrivez** ! Pour ajouter du code par blocs, il est préférable d'utiliser la syntaxe que vous avez vue précédemment : les codes de bloc.