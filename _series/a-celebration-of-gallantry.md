---
title: A Celebration of Gallantry
permalink: /series/a-celebration-of-gallantry
layout: default
order: 1
image: /images/thumbnails/P_22_2003.jpeg

---
This series of 7 prints was published in 1865 by Daikin. Each print shows a leading actor as a tattooed fireman. Firemen were popular figures, and their heroics and appearance lent themselves to depiction in prints. They wore tattoos partly to demonstrate their indifference to pain; they wore patterned quilted robes, which they reversed to the plain side when fighting fires; and they carried huge geometric standards (matoi) to identify their brigade and to signal above the flames. This set is a variation on the popular genre of actor portraits, with the patterns on the robes deriving from the actor's personal identifying crest (mon).

<div class="row">
{% assign sorted-posts = site.explore | where: "series","gallantry" %}
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
