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
      <span class="white-text">Under construction</span> <p />
      <a class="btn-lrg btn-lrg-dark" href="{{ "http://www.instagram.com/hahahotdogs"}}">Check out our Instagram</a>
    </div>
  </div>
</section>

<!--Where to buy-->
<section class="home-projects">
  <div class="pw-container">
    <h3>Buy Online</h3>
      <div class="home-buy-online-list">
        {% for item in site.data.buy-online.list %}
          <div class="home-project">
            <a href="{{ item.url }}" alt="{{ item.title }}">
              <img class="home-project-thumbnail" src="{{ item.thumbnail }}" />
              <!--<h4 class="home-project-title">{{ item.title }}</h4>-->
              <!--<p class="home-project-description">{{ item.description }}</p>-->
            </a>
          </div>
        {% endfor %}
      </div>
  </div>
</section>

<section class="home-projects">
  <div class="pw-container">
    <h3><a name="projects"></a>Products Gallery</h3>
    <div class="home-projects-list">
      {% for item in site.data.projects.list %}
      <div class="home-project">
        <a href="{{ item.url }}" alt="{{ item.title }}" data-lightbox="postcards">
          <img class="home-project-thumbnail" src="{{ item.thumbnail }}" />
          <!-- <h4 class="home-project-title">{{ item.title }}</h4> -->
          <!--<p class="home-project-description">{{ item.description }}</p>-->
        </a>
      </div>
      {% endfor %}
    </div>
  </div>
</section>
