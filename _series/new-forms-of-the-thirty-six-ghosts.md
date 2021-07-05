---
title: New Forms of the Thirty-six Ghosts
permalink: /series/new-forms-of-the-thirty-six-ghosts
layout: default
order: 4
image: /images/thumbnails/P_28_2003.jpeg
---

This series of 36 prints was published by Sasaki Toyokichi in 1889-92. The subjects are drawn from various sources of legend from Japanese history and literature, kabuki and noh theatre, linked only by the presence of a supernatural being in each print.

The word used in the title for 'ghost', kai , actually means strange, monstrous or weird, so the subjects include demons and monsters as well as the spirits of dead humans returning from hell to haunt the living. Each print is given the appearance of having a worm-eaten border.

This was the last of Yoshitoshi's major series. He was ill during their making, had help from pupils on the later designs, and died before the last three were published.

<div class="row">
{% assign sorted-posts = site.explore | where: "series","ghosts" %}
{% for author in sorted-posts limit: 5 %}
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
