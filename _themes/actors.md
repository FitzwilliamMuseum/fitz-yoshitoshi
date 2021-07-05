---
title: Actors
permalink: /themes/actors
layout: default
image: /images/thumbnails/P_6_2003.jpeg
---
Kabuki theatre originated at the start of the Edo period and developed into an elaborate stage spectacle with complex plots and spectacular productions. In exploiting the phenomenal public fascination with professional Kabuki actors, print publishers and designers fanned the flames of their popularity.

Together with the most exclusive prostitutes of the Yoshiwara, the actors became cultural icons, and their near-legendary names passed from one generation to another. Leading stars had massive fan clubs and supplemented their huge earnings by endorsing products with their names. Prints were nearly always published to coincide with particular performances, usually to generate advance publicity.

<div class="row">
{% assign sorted-posts = site.explore | where: "themes","actors" %}
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
