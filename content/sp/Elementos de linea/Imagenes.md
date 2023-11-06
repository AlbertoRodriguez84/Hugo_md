+++
title = 'Imagenes'
date = 2023-11-01T19:13:47+01:00
draft = false
+++

Insertar una imagen con Markdown se realiza de una manera prácticamente idéntica a insertar links.

Solo que en este caso, deberás añadir un símbolo de ```!```** exclamación** al principio y el **enlace** no será otro que la **ubicación de la imagen**.


```
![Texto alternativo](/ruta/a/la/imagen.jpg)
```
El texto alternativo es lo que se mostraría si la carga de la imagen fallase.

También podrás añadir un **título alternativo** entrecomillándolo al final de la ruta. Esto sería el título mostrado al dejar el cursor del ratón sobre la imagen.
```
![Texto alternativo](/ruta/a/la/imagen.jpg "Título alternativo")   
```
Ya que al añadir imágenes también estás tratando con URLs, puedes utilizar el método que viste anteriormente para **incluir links mediante referencias**, solo que en este caso **los enlaces de referencia serán aquellos donde se encuentre tu imagen**.

```
De esta forma podrías insertar una imagen
![nombre de la imagen][img1]
O dos, sin ensuciar tu espacio de escritura.
![nombre de la imagen2][img2] 
[img1]: /ruta/a/la/imagen.jpg "Título alternativo"
[img2]: /ruta/a/la/imagen2.jpg "Título alternativo"
```