+++
title = 'Code'
date = 2023-11-01T19:13:40+01:00
draft = false
+++

Depending on the type of publications (especially those of a technical nature), you will need to add small sections where you can show code from another language, keyboard shortcuts, or other content that should not be treated as such.

For this you have two alternatives available.

#### Pure code ```<code>```
The easiest way to write code in Markdown is to wrap the text in two single quotes ``` ` ```. This corresponds to the HTML tag ```<code>```
´´´
`This is a line of code`
´´´
   
It will look like `This is one line of code`.

As you can see, it is very useful for entering code within the same line or paragraph, something that the following method does not allow.

#### Preformatted text ```<pre>```
    
The other way to add code in Markdown is to **start the paragraph with four blank spaces**. This corresponds to the HTML tag ```<pre>```

```
 This is a line of code

```
Becomes

```
This is a line of code
```


Be careful, you must include these spaces **in each line you write**! To add code in blocks it is better to use the syntax you saw previously: block codes.