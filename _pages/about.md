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

I'm interested in uncovering why fire has intensified in the western United States through improving our understanding of plant drought response, using ecohydrological and physical modeling as well as microwave satellite data. Current research efforts include understanding land-atmosphere coupling impacts on fuel moisture and fire, and quantifying plant-water relations at scale.

---

## Recent Posts

{% for post in site.posts limit:10 %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %Y" }}*

{{ post.content }}
{% endfor %}
