---
title: Firemen
permalink: /themes/firemen
layout: default
image: /images/thumbnails/P_22_2003.jpeg

---
Firemen were popular figures in Edo: the timber construction of the city made fires a regular hazard. Their heroics and colourful appearance lent themselves to depiction in prints. They wore tattoos partly to demonstrate their indifference to pain; they wore elaborately patterned padded robes, which they reversed to the plain side when fighting fires; and they carried huge geometric standards (matoi) so that they could be easily identified and so that they could signal above the flames.



<div class="row">
{% assign sorted-posts = site.explore | where: "themes","firemen" %}
{% for author in sorted-posts  %}
<div class="col-md-4 mb-3">
  <div class="card h-100" >
    <a href="{{site.url}}{{site.baseurl}}{{ author.permalink }}" class="stretched-link">
      <img class="card-img-top" src="{{site.url}}{{site.baseurl}}{{author.image}}" alt="Card image cap" width="300" height="300"/>
    </a>
    <div class="card-body">
      <h3 class="lead mt-2">
        <a href="{{site.url}}{{site.baseurl}}{{ author.permalink }}" class="stretched-link">{{author.title}}</a>
      </h3>
    </div>
  </div>
</div>
{% endfor %}
</div>
