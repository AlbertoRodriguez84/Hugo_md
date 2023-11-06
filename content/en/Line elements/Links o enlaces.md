+++
title = 'Links'
date = 2023-11-01T19:13:18+01:00
draft = false
+++

Adding links to a publication, more than common, today is something **almost mandatory**. With Markdown you will have several ways to do it.

### Links or online links
___
They are the links of a lifetime. As their name suggests, they are in line with the text.

They are created by writing the linked word or text between ```[] ```**brackets**, and the link in question between ```()``` **parentheses**.

| MARKDOWN | RESULT |
| ```[online link](http://www.limni.net)``` | online link |

### Links or links for reference
____
The disadvantage of the previous method is that if you use links that are too complex or long, they can make it difficult for you to read your text.

To solve this and create your content in a more organized way, you can generate reference links.

This means that in your text you will link **specific words or codes** (made up of letters and/or numbers), which in another, more remote place in your document you will have defined as certain URLs.

```
[name you want to give your link][name of your reference]
[name of your reference]: http:www.tuenlace.com
```
This is clearer with an example.
```
My name is Javier Cristóbal and I have a blog about [mac productivity][blog].
In this [website][blog] I compile articles about everything related to automation, management and efficiency.
[blog]: http://limni.net/blog
```

The ```[blog]``` reference can be included anywhere in the document, so you can organize yourself better and in a cleaner way, collecting all your references in one place.


Also, as you see below, this reference is **not included in the final result**, but rather disappears.

«My name is Javier Cristóbal and I have a blog about [mac productivity][blog].
In this [website][blog] I compile articles about everything related to automation, management and efficiency.
[blog]: http://limni.net/blog »

### Automatic links
____
You will see this form within various elements: automatic links