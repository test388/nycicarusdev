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
    display: inline-block;
  }
  h1{
    display:inline-block;
  }
  .title-tile{
    width: 100%;
    margin-bottom: 0px;
    margin-top: 30px;
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

<h1>Events</h1> 

<div class="tiles">
  {% for post in site.categories.events limit: 4 %}
    {% include post-grid-events.html %}
  {% endfor %}
  <div class="tile"><a href="{{ site.url }}/events/" class="btn">More Events</a></div>
</div><!-- /.tiles -->

<div class="tiles">
  <div class="tile title-tile">
    <h1>Publications and Media</h1>
  </div>
</div>
 
<div class="tiles">
  {% for post in site.categories.articles limit: 4 %}
    {% include post-grid.html %}
  {% endfor %}
  <div class="tile"><a href="{{ site.url }}/publications-media/" class="btn">More Publications and Media</a></div>
</div><!-- /.tiles -->

<div class="tiles">
  <div class="tile title-tile">
    <h1>Resources</h1>
  </div>
</div>

<div class="tiles">
  {% for post in site.categories.resources limit: 4 %}
    {% include post-grid-resources.html %}
  {% endfor %}
  <div class="tile"><a href="{{ site.url }}/resources/" class="btn">More Resources</a></div>
</div><!-- /.tiles -->

