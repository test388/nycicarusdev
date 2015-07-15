---
layout: home
permalink: /
image:
  feature: protest-blue.jpg
---

<style>
  .btn{
    margin-bottom: 0px;
    margin-top: 10px;
  }
</style>

<div class="tiles">

<div class="tile">
  <h2 class="post-title">Who We Are</h2>
  <p class="post-excerpt">We are a support network and media project by and for people who experience the world in ways that are often diagnosed as mental illness.</p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title">Events and Workshops</h2>
  <p class="post-excerpt">The NYC Icarus Project hosts a regular event at the Blue Stockings Feminist Community Center every month. In addition to regular events we host numerouse special events and classes.</p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title">Guides and Publications</h2>
  <p class="post-excerpt">We aim to create a language that is so vast and rich that it expresses the infinite diversity of human experiences.</p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title">Online Community</h2>
  <p class="post-excerpt">The Icarus Project has an extremely active online community at Facebook.
    <br/><a href="https://www.facebook.com/theicarusproject" class="btn">Facebook Page</a><br/>
    <a href="https://www.facebook.com/groups/2394863930/" class="btn">Facebook Group</a></p>
</div><!-- /.tile -->

</div><!-- /.tiles -->



<div class="tiles">

#Events

{% for post in site.categories.events %}
  {% include post-grid-events.html %}
{% endfor %}
</div><!-- /.tiles -->


<div class="tiles">

#Articles

{% for post in site.categories.articles %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

