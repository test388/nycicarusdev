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
  <p class="post-excerpt">We are a support network, advocacy organization and media project by and for people who experience the world in ways that are often diagnosed as mental illness.</p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title">Reclaiming History</h2>
  <p class="post-excerpt">What do Martin Luther King, Nina Simone, Issac Newton, Virgina Woolf, Pablo Picasso, Sigmund Freud, and Abraham Lincoln have in common? They are all one of us. The history of brilliance in madness is our history.</p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title">Reappropriating Language</h2>
  <p class="post-excerpt">We are not a diagnosis or a social affliction. We embrace the term “madness” because it connects us to our art, our history and each other.</p>
</div><!-- /.tile -->

<div class="tile">
  <h2 class="post-title">Community</h2>
  <p class="post-excerpt">We hold <a href="/events">regular events, workshops and celebrations</a>. We have an active online community at Facebook.
    <br/><a href="https://www.facebook.com/theicarusproject" class="btn">Facebook Page</a><br/>
    <a href="https://www.facebook.com/groups/2394863930/" class="btn">Facebook Group</a></p>
</div><!-- /.tile -->

</div><!-- /.tiles -->

<p style="color:red;">*under construction*</p>
#Events 

<div class="tiles">
{% for post in site.categories.events %}
  {% include post-grid-events.html %}
{% endfor %}
</div><!-- /.tiles -->

#Articles 

<div class="tiles">
{% for post in site.categories.articles %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

