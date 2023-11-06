+++
title = 'Others'
date = 2023-11-01T19:13:40+01:00
draft = false
+++

### Embedded videos

We can display an embedded video with the following code:

```
{{ < youtube 6H0jLIKe0uw > }}
```
Here we can see a small introduction to Hugo.

{{< youtube 6H0jLIKe0uw >}}



### Buttons

Continuing with the example of the previous video, instead of showing it we can put a button that links to the video and takes up less space on our website.

To put the button you have to put the following syntax:

```
{{ % button href="https://youtu.be/6H0jLIKe0uw" icon="fas fa-download" icon-position="right" % }}To watch the video click here{{ % /button % }}
```

{{% button href="https://youtu.be/6H0jLIKe0uw" icon="fas fa-download" icon-position="right" %}}To watch the video click here{{% /button %}}