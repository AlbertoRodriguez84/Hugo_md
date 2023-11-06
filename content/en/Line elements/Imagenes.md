+++
title = 'Images'
date = 2023-11-01T19:13:47+01:00
draft = false
+++

Inserting an image with Markdown is done in a practically identical way to inserting links.

Only in this case, you will have to add an !** exclamation** symbol at the beginning and the link will be none other than the location of the image.

![Alternative text](/path/to/the/image.jpg)
The alt text is what would be displayed if the image load failed.

You can also add an alternative title in quotes at the end of the route. This would be the title displayed when you leave the mouse cursor over the image.

![Alternative text](/path/to/the/image.jpg "Alternative title")
Since when adding images you are also dealing with URLs, you can use the method you saw previously to include links through references, only in this case the reference links will be those where your image is located.

This way you could insert an image
![image name][img1]
Or two, without messing up your writing space.
![image name2][img2]
[img1]: /ruta/a/la/imagen.jpg "Alternative title"
[img2]: /ruta/a/la/imagen2.jpg "Alternative title"