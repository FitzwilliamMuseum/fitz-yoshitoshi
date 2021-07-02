---
title: Thirty-two Aspects of Customs and Manners
permalink: /series/thirty-two-aspects-of-customs-and-manners
layout: default
order: 5
---
This series of 32 prints was published by Tsunashima Kamekichi in 1888. It depicts a chronological survey from the Kansei era (1789-1800) to the Meiji era (1860-1912) of women of different backgrounds and occupations, each associated with a particular mood or character trait.

The word for 'Aspect' or 'Type' or 'Appearance' (sô) had been famously used by earlier artists such as Utamaro and Kunisada. It was a technical term borrowed from physiognomists who analysed character on the basis of physical facial features. It could also mean 'flower', referring to bijin (female beauties).

<div class="row">
{% assign sorted-posts = site.explore | where: "series","customs" %}
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
