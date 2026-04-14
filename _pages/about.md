---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
header:
  overlay_image: /banner.jpeg
  hide_title: true
---

## About Me

I research interactions between the climate, vegetation, and the water cycle using remote sensing, process-based modeling, and machine learning. I am currently pursuing my PhD as a member of the [Konings Lab](https://koningslab.stanford.edu/) at Stanford.

In recent work, I've investigated satellite-based measurements of fire effects, particularly to understand how climate change is altering how forests respond to fire. I am also interested in improving our measurements of plant water stress, and understanding how drought mortality and wildfire risk might change under varying water availabliity.

---

## Recent Posts

{% for post in site.posts limit:10 %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %Y" }}*

{{ post.content }}
{% endfor %}
