---
title: Genji
permalink: /themes/genji
layout: default
image: /images/thumbnails/P_2_2004.jpg
---
Many prints were inspired directly or indirectly by The Tale of Genji (Genji monogatari), the classic Japanese novel written in the 11th century by Murasaki Shikibu (c.975-1025), a lady of the Heian court. It tells of the romantic adventures of Prince Genji.

Numerous episodes had been popularly depicted throughout the Edo Period, but the theme received a boost by the publication in 1829-42 of Ryutei Tanehiko's serial novel Nise murasaki inaka genji (False Murasaki and a Rural Genji), which reset the romance in the 15th century, with a cynical hero, and narrative conventions borrowed from popular novels, Kabuki and puppet theatre, replacing the melancholy poetic tone of the original.

The popularity of this new version resulted in a Genji craze, with all sorts of Genji-themed products appearing for sale, Genji hairstyles, and a distinct genre of prints based on the story known as Genji-e (Genji pictures).

<div class="row">
{% assign sorted-posts = site.explore | where: "themes","genji" %}
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
