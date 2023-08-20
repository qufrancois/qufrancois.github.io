---
layout: about
title: about
permalink: /
subtitle: Université Paris-Dauphine PSL, CEREMADE

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  address: 


news: false  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---

I am a PhD student in Probability theory under the supervision of [Djalil Chafaï](https://djalil.chafai.net/wiki/) and [Pierre Tarrago](http://tarrago.perso.math.cnrs.fr). I am mostly interested in high dimensional phenomenas arising from random matrix theory and exactly solvable models. 

**Research Interests:** Random Matrices, Free Probability, Integrable Probability and Algebraic Combinatorics.

**Contact:** firstname.lastname@dauphine.psl.eu

**Office(s):** 
- B223, Université Paris-Dauphine, Place du Maréchal de Lattre de Tassigny, 75016 Paris
- V3, École Normale Supérieure, 45 rue d'Ulm, 75005 Paris

---

### Preprints:
---

<!-- _pages/publications.md -->
<div class="Preprints">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>


### Published Papers:
---