---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## About Me

I use remote sensing, process-based modeling, and machine learning to research ecohydrological and hydroclimatological processes, especially wildfire and drought.

My work on wildfire focuses on burn severity, that is, how much biomass is lost to fire, and how climate change is modifying burn severity regimes in the Western United States. I am also interested in plant water stress and its role in wildfire risk. This includes using microwave remote sensing to track plant water potential (Ψ) and live fuel moisture content (LFMC) at landscape scales, with the goal of understanding how vegetation physiology mediates fire behavior under drought.

---

## Recent Posts

{% for post in site.posts limit:3 %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %Y" }}*

{{ post.excerpt }}
{% endfor %}
