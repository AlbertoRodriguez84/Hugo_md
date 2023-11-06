+++
title = 'Images'
date = 2023-11-01T19:13:47+01:00
draft = false
+++

L'insertion d'une image avec Markdown se fait de manière pratiquement identique à l'insertion de liens.

Seulement dans ce cas, vous devrez ajouter un point d'exclamation ```!```** au début et le **lien** ne sera autre que l'**emplacement de l'image**.


```
![Texte alternatif](/path/to/the/image.jpg)
```
Le texte alternatif est ce qui serait affiché si le chargement de l'image échouait.

Vous pouvez également ajouter un **titre alternatif** entre guillemets à la fin du chemin. Ce serait le titre affiché lorsque vous laisserez le curseur de la souris sur l'image.
```
![Texte alternatif](/path/to/the/image.jpg "Titre alternatif")
```
Étant donné que lors de l'ajout d'images, vous traitez également des URL, vous pouvez utiliser la méthode que vous avez vue précédemment pour **inclure des liens via des références**, seulement dans ce cas **les liens de référence seront ceux où se trouve votre image**.

```
De cette façon, vous pourriez insérer une image
![nom de l'image][img1]
Ou deux, sans gâcher votre espace d'écriture.
![nom de l'image2][img2]
[img1] : /ruta/a/la/imagen.jpg "Titre alternatif"
[img2] : /ruta/a/la/imagen2.jpg "Titre alternatif"
```