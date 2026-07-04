---
layout: page
permalink: /posts/gamedev/
title: Gamedev
---
I'm a self taught game developer, I started in 2020 with a decade old pc running windows 7 and a dream!<br>
Below is a list of my projects, past and present

<h1>
<a href="https://null3d.itch.io/tacti-cat">Tacti-Cat</a>
</h1>
<h4>-Main project-</h4><br> 
A fast paced, momentum based 2.5D platformer where you fight wizards using fish guns!


<h1>
<a href="https://null3d.itch.io/cheddars-cheese-mafia">Cheddar's Cheese Mafia</a>
</h1>
<h4>-ON HOLD-</h4><br> 
A topdown shooter set in the Tacti-Cat universe about a young Mayor Cheddar in the mob!

<h1>
<a href="https://null3d.itch.io/super-freaks-the-freak-ages">Super Freaks: The Freak Ages</a>
</h1>
<h4>-Game jam-</h4><br> 
An FPS fangame made for Fr3akjam (Freakjam 3) that may or may not be inspired by a recent doom game

<h1>
<a href="https://null3d.itch.io/freakeste">Freakeste</a>
</h1>
<h4>-Game jam-</h4><br> 
A fangame clone of Celeste made for Freakjam 2 where you play as Geyzer on a quest to eat at the most mediocre burger place ever!

<h1>
<a href="https://null3d.itch.io/gaming2">The Abandoned Projects Pack</a>
</h1>
<h4>-CANCELLED-</h4><br> 
A collection of random games that didn't make it too far. Included is: Hookshock, Full Auto Racing, Bowsas Angy, Bad RPGMaker Platformer, and my very first project: Attracted to testing. Don't get too excited, none of these have even a full level of content!

<br>
<hr>
<br>
<h1>
Gamedev news
</h1>
<br>

<div class="posts">
  {% for post in site.categories['Gamedev'] %}
    <article class="post">
      <h1>
          <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      </h1>
      <div>
        <p class="post_date">{{ post.date | date: "%B %e, %Y" }}</p>
      </div>
      <div class="entry">
        {{ post.excerpt }}
      </div>
      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">
          Read More
      </a>
    </article>
  {% endfor %}
</div>

<br>
<div align="center">
  <h2>
  You've reached the end! <br> Check back later for more news :3
  </h2>
</div>
