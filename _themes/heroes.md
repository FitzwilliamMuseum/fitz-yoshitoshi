---
title: Heroes
permalink: /themes/heroes
layout: default
image: /images/thumbnails/P_26_2003.jpg
---
The Chinese novel Shuihu zhuan (The Water Margin), known in Japanese as Suikoden, tells of the legendary exploits of a group of Chinese brigands during the Northern Song dynasty (1101-26).

It was retold in a popular Japanese novel illustrated by Hokusai in 1805, and was the subject of Kuniyoshi's first set of warrior prints in 1827. A Suikoden craze ensued and manifested itself in tattoos, kites, kiseru pipes for smoking, and curtains of barbershops.

Yoshitoshi made prints based on Suikoden at various points in his career, and was evidently attracted by the anti-establishment theme.

<div class="row">
{% assign sorted-posts = site.explore | where: "themes","heroes" %}
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
