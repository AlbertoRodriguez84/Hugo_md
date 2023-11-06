+++
title = 'Codigo'
date = 2023-11-01T19:13:40+01:00
draft = false
+++

En según que tipo de publicaciones (sobre todo las de carácter técnico), necesitarás añadir pequeñas secciones donde mostrar código de otro lenguaje, atajos de teclado, o demás contenido que no debería ser tratado como tal.

Para ello tienes disponible dos alternativas.

#### Código puro ```<code>```
La forma más sencilla de escribir código en Markdown es envolver el texto entre dos comillas sencillas ``` ` ```. Esto se corresponde con la etiqueta HTML ```<code>```
´´´
`Esto es una línea de código`
´´´   
   
Se verá como `Esto es una línea de código`.

Como ves, es muy útil para introducir código dentro de la misma línea o párrafo, algo que no permite el método siguiente.

#### Texto preformateado ```<pre>```   
    
La otra manera de añadir código en Markdown es **comenzar el párrafo con cuatro espacios en blanco**. Esto se corresponde con la etiqueta HTML ```<pre>```

```
 Esto es una línea de código

```
Se convierte en

``` 
Esto es una línea de código
```


Ojo, ¡estos espacios deberás incluirlos **en cada línea que escribas**! Para añadir código en bloque es mejor utilizar la sintaxis que viste anteriormente: códigos de bloque.
