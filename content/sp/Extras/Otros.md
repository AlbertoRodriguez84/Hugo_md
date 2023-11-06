+++
title = 'Otros'
date = 2023-11-01T19:13:40+01:00
draft = false
+++

### Videos incrustados

Podemos mostrar un video incrustado con el siguiente codigo:

```
{{ < youtube 6H0jLIKe0uw > }}
```
Aquí podemos ver una pequeña introducción a Hugo.

{{< youtube 6H0jLIKe0uw >}}



### Botones

Siguiendo con el ejemplo del video anterior, en vez de mostrarlo podemos poner un boton que nos enlace al video y ocupe menos en nuestra web.

Para poner el boton tener que poner la siguiente sintaxis:

```
{{ % button href="https://youtu.be/6H0jLIKe0uw" icon="fas fa-download" icon-position="right" % }}Para ver el video pulsa aqui{{ % /button % }}
```

{{% button href="https://youtu.be/6H0jLIKe0uw" icon="fas fa-download" icon-position="right" %}}Para ver el video pulsa aqui{{% /button %}}