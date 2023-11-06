+++
title = 'Autres'
date = 2023-11-01T19:13:40+01:00
draft = false
+++

### Vidéos intégrées

Nous pouvons afficher une vidéo embarquée avec le code suivant :

```
{{ <youtube 6H0jLIKEe0uw > }}
```
Ici, nous pouvons voir une petite introduction à Hugo.

{{<youtube 6H0jLIKEe0uw >}}



### Boutons

En reprenant l'exemple de la vidéo précédente, au lieu de la montrer, nous pouvons mettre un bouton qui renvoie à la vidéo et prend moins de place sur notre site Web.

Pour mettre le bouton il faut mettre la syntaxe suivante :

```
{{ % button href="https://youtu.be/6H0jLIKE0uw" icon="fas fa-download" icon-position="right" % }}Pour regarder la vidéo, cliquez ici{{ % /button % }}
```

{{% button href="https://youtu.be/6H0jLIKE0uw" icon="fas fa-download" icon-position="right" %}}Pour regarder la vidéo, cliquez ici{{% /button %}}