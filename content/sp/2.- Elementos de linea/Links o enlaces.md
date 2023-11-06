+++
title = 'Links o enlaces'
date = 2023-11-01T19:13:18+01:00
draft = false
+++

Añadir enlaces a una publicación, más que común, hoy en día es algo **casi obligatorio**. Con Markdown tendrás varias formas de hacerlo.

### Links o enlaces en línea
___
Son los enlaces de toda la vida. Como su nombre indica, se encuentran en línea con el texto.

Se crean escribiendo la palabra o texto enlazada entre ```[] ```**corchetes**, y el link en cuestión entre ```()``` **paréntesis**.

| MARKDOWN  | RESULTADO   |   
| ```[enlace en línea](http://www.limni.net)``` |	enlace en línea |  

### Links o enlaces como referencia
____
La desventaja del método anterior, es que si utilizas links demasiado complejos o largos pueden dificultarte la lectura de tu texto.

Para solucionarlo y crear tu contenido de una manera más ordenada puedes generar enlaces de referencia.

Esto quiere decir que en tu texto enlazarás **palabras o códigos concretos** (formados por letras y/o números), que en otro lugar más apartado de tu documento tendrás definidos como determinadas URL.

```
[nombre que quieres darle a tu enlace][nombre de tu referencia]
[nombre de tu referencia]: http:www.tuenlace.com
```
Esto se ve más claro con un ejemplo.
```
Me llamo Javier Cristóbal y tengo un blog sobre [productividad mac][blog].
En dicha [web][blog] recopilo artículos sobre todo lo relacionado con automatización, gestión y eficiencia.
[blog]: http://limni.net/blog
```

La referencia ```[blog]``` puede estar incluida en cualquier parte del documento, así puedes organizarte mejor y de una manera más _limpia_, recopilando todas tus referencias en un mismo lugar.


Además como ves a continuación, esta referencia **no se incluye en el resultado final**, sino que desaparece.

«Me llamo Javier Cristóbal y tengo un blog sobre [productividad mac][blog].
En dicha [web][blog] recopilo artículos sobre todo lo relacionado con automatización, gestión y eficiencia.
[blog]: http://limni.net/blog »

### Links automáticos
____
Verás esta forma dentro de elementos varios: links automáticos
