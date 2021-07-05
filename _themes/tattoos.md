---
title: Tattoos
permalink: /themes/tattoos
layout: default
image: /images/thumbnails/P.8-2003.jpg
---

Tattoos were popular among certain sections of Japanese society, particularly the classes of gangsters, labourers and prostitutes. Even today tattooing from neck to ankle is popular among Japanese gangsters.

Firemen were often tattooed, partly as a mark of their ability to resist pain. Prostitutes were sometimes tattooed with their lover's name. Japanese print designers also often wore tattoos, which is an indication that their status was one of lowly craftsman rather than that of a fine artist of the traditional painting schools. Yoshitoshi's teacher Kuniyoshi and some of his pupils were tattooed.

<div class="row">
{% assign sorted-posts = site.explore | where: "themes","tattoos" %}
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
