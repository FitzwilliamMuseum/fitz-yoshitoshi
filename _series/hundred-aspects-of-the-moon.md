---
title: One hundred aspects of the moon
layout: default
permalink: /series/hundred-aspects-of-the-moon
order: 3
---

This series of 100 prints was published in 1885-92 by Akiyama Buemon. The subjects are drawn from various sources in Japanese and Chinese history and literature, Kabuki and Noh theatre, and even contemporary Tokyo, linked only by the presence of the moon in each print. The creation of mood according to the phase of the moon was exploited for its poetic and expressive possibilites. This was the most successful and still the most famous of Yoshitoshi's print series. People would queue before dawn to buy each new design and still find the edition sold out.

<div class="row">
{% assign sorted-posts = site.explore | where: "series","aspects" %}
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
