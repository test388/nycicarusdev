---
layout: home
permalink: /
image:
  feature: protest-blue.jpg
---

<div class="tiles">

<div class="tile">
  <h2 class="post-title">Who We Are</h2>
  <p class="post-excerpt">We are a support network and media project by and for people who experience the world in ways that are often diagnosed as mental illness.</p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title">Events and Workshops</h2>
  <p class="post-excerpt">We envision a new culture that allows the space and freedom for exploring different states of being, and recognizes that breakdown can be the entrance to breakthrough.</p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title">Guides and Publications</h2>
  <p class="post-excerpt">We aim to create a language that is so vast and rich that it expresses the infinite diversity of human experiences.</p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title">Online Community</h2>
  <p class="post-excerpt">The Icarus Project has an extremely active online community on it's Facebook group. Although the group is closed, all who request membership are joined. You can find it <a href="https://www.facebook.com/groups/2394863930/">HERE</a></p>
</div><!-- /.tile -->

</div><!-- /.tiles -->

<div class="tiles">
{% for post in site.categories.events %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

<div class="tiles">
{% for post in site.categories.articles %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

