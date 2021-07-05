---
title: Ghosts
permalink: /themes/ghosts
layout: default
image: /images/thumbnails/P_28_2003.jpeg
---
Given that the traditional Shinto religion of Japan taught that the world was full of animistic spirits, it is no wonder that 'ghosts' played such a large part in Japanese folklore, literature, Noh and Kabuki theatre, and in woodcut prints.

Encounters with the supernatural were felt as a real experience, and many, like Yoshitoshi, had affecting sightings of ghosts. The word for ghost, kai, actually means strange, monstrous or weird, so the supernatural beings included a variety of demons and monsters as well as the spirits of dead humans returning from hell to haunt the living.


<div class="row">
{% assign sorted-posts = site.explore | where: "themes","ghosts" %}
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
