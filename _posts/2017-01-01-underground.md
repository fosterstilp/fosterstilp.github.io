---
layout: project
title:  Underground
category: projects
---
Underground is a game project I have been working on sporadically during my free time.  The game is set in modern London, and follows an unexpected adventure with two "uncool" highschool students.  

It is the largest and most in-depth game project we've done, and is still in its early stages of conception.  Below are some images from progress made on the game so far:

![underground_image01](/img/underground1.jpg)
![underground_image02](/img/underground2.png)
![underground_image03](/img/underground3.jpg)
![underground_image04](/img/underground4.jpeg)
![underground_image05](/img/underground5.png)
![underground_image06](/img/underground6.gif)
![underground_image07](/img/underground7.png)
![underground_image08](/img/underground8.gif)

Below are all of the posts written over the course of the game's progress so far:

{% for post in site.tags['underground'] %}
<a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}
