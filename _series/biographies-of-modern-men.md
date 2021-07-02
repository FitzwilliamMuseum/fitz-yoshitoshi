---
title: Biographies of Modern Men
layout: default
permalink: /series/biographies-of-modern-men
order: 2
---
This series shows leading figures in a violent feud between two gambling rings in Shimôsa province (now part of Chiba prefecture) in 1849, led by Iioka Sukegorô and Hanzô. These anti-establishment figures were heroic figures in the popular culture of the time. As with many of Yoshitoshi's prints in the violent and unsettled times of the mid to late 1860s, the series is full of blood and gore.

<div class="row">
{% assign sorted-posts = site.explore | where: "series","biographies" %}
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
