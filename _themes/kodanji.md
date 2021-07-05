---
title: Kodanji
permalink: /themes/kodanji
layout: default
image: /images/thumbnails/P_6_2003.jpeg

---
Ichikawa Kodanji IV (1812-66) was a disciple of the great Ichikawa Danjûrô VII in Osaka and succeeded his teacher as Edo's leading actor after Danjûrô's death in 1859. He overcame his slight stature and limited vocal gifts by developing the art of 'special effects' (keren), such as flying (chûnori) and quick-change technique (hayagawari), but he also won acclaim for his realism in playing well-intentioned men whose circumstances drove them into crime. Kodanji featured in numerous prints by artists of the previous generation, such as Kunisada and Yoshitoshi's teacher, Kuniyoshi.

<div class="row">
{% assign sorted-posts = site.explore | where: "themes","kodanji" %}
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
