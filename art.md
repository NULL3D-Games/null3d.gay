---
layout: page
permalink: /posts/art/
title: Art
---

<div class="posts">
  {% for post in site.categories['Art'] %}
    <article class="post">
      <h1>
          <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      </h1>
      <div>
        <p class="post_date">{{ post.date | date: "%B %e, %Y" }}</p>
      </div>
      <div align="center">
      <a href="{{ site.baseurl }}{{ post.url }}">
        <img src="{{post.image}}" title="{{post.title}}" height = 400 width = 400 alt="{{post.title}}">
      </a>
      </div>
      <div class="entry">
        {{ post.excerpt }}
      </div>
      <a href="{{ post.bsky }}">View this art on bsky!!!</a>
    </article>
  {% endfor %}
</div>
<br>
<div align="center">
  <h2>
  You've reached the end! <br> Check back later for more art :3
  </h2>
</div>
