---
title: Drawing
permalink: /themes/drawing
layout: default
image: /images/thumbnails/P_6_2003.jpeg
---
The Fitzwilliam Museum has a large group of drawings by Yoshitoshi and his school, which came to the Museum with the Reitlinger Bequest in 1991. They include preparatory sketches (gakô) and final line-block drawings (hanshita-e) connected to printmaking, seven of which are illustrated here. The methods were descended from those of Yoshitoshi's teacher, Kuniyoshi.

The preparatory sketches in black over a red underdrawing can easily be attributed to Yoshitoshi by their handling and quality, but there is more difficulty with the line-block drawings. The final line-block drawing would have been pasted to the block and destroyed during the carving, so those that survive were either made in connection with uncompleted prints, or they were copies made in the studio from the drawing that was used for the print.



<div class="row">
{% assign sorted-posts = site.explore | where: "themes","drawing" %}
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
