---
title: Moon
permalink: /themes/moon
layout: default
image: /images/thumbnails/P_23_2003.jpg

---
The moon (tsuki) had special poetic and aesthetic significance in Japanese life. As well as being accociated with numerous legends, many of them deriving from China, the moon was part of the annual calendar, which was itself regulated by the phases of the moon.

Parties and festivals marked the particular appearance of the moon, and special places were set aside for the contemplation of the moon (and often its reflection), such as moon-viewing pavilions.

On the full moon of the 8th and 9th months, poems were composed to the accompaniment of sake drinking. In a work of art the full moon was often associated with autumn. The moon obviously held a significance for Yoshitoshi; it provided the theme of his greatest series of prints, and it was the central metaphor of his memorial poem.


<div class="row">
{% assign sorted-posts = site.explore | where: "themes","moon" %}
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
