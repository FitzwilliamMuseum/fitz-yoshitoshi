---
title: Combat
permalink: /themes/combat
layout: default
image: /images/thumbnails/P_27_2003.jpg
---
Violence and combat had long been major themes in Ukiyo-e prints, and formed a major part of the subject matter of Yoshitoshi's teacher Kuniyoshi, whose warrior prints vied for popularity with Kunisada's prints of actors.

The ban on depicting real historical events within the Edo period meant that the warriors were those of the distant and often legendary past, but as the Edo period gave way to the Meiji period in 1868, circumstances changed.

Yoshitoshi's violent prints of the 1860s reflect the sometimes violent change taking place in Japan, and in the following decade he went on to make prints of contemporary battles for newspapers. In later life his subjects were dominated once more by the legendary heroes that had been depicted in prints of the Edo period.


<div class="row">
{% assign sorted-posts = site.explore | where: "themes","combat" %}
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
