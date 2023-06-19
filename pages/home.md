---
layout: default
title: Haha Hot Dogs | Hello
permalink: /
nav: light
---

<section class="home-hero">
  <div class="pw-container">
    <div class="home-hero-content">
      <p>Haha Hot Dogs</p>
      <p></p>
      <p></p>
      <span class="white-text">Postcards, stickers, good times, and more!</span>
      <p></p>
      <span class="white-text">Website under construction</span>
      <a class="btn-lrg btn-lrg-dark" href="{{ "http://www.instagram.com/hahahotdogs"}}">Check out our Instagram</a>
    </div>
  </div>
</section>

<!--Dude. Just re-do the Projects section. Who cares if it's not centered? -->
<section class="projects">
  <div class="pw-container">
    <h3>Buy Online</h3>
      <div class="home-buy-online-list">
        {% for item in site.data.buy-online.list %}
          <div class="home-project">
            <a href="{{ item.url }}" alt="{{ item.title }}">
              <img class="home-project-thumbnail" src="{{ item.thumbnail }}" />
              <h4 class="home-project-title">{{ item.title }}</h4>
              <p class="home-project-description">{{ item.description }}</p>
            </a>
          </div>
        {% endfor %}
      </div>
  </div>
</section>

<section class="projects">
  <div class="pw-container">
    <h3>Buy Online</h3>
      <div class="home-buy-online-list">
        {% for item in site.data.buy-online.list %}
          <div class="home-project">
            <a href="{{ item.url }}" alt="{{ item.title }}">
              <img class="home-project-thumbnail" src="{{ item.thumbnail }}" />
              <h4 class="home-project-title">{{ item.title }}</h4>
              <p class="home-project-description">{{ item.description }}</p>
            </a>
          </div>
        {% endfor %}
      </div>
  </div>
</section>
