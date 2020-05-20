---
layout: default
title: Haha Hot Dogs
permalink: /
nav: light
---

<section class="home-hero">
  <div class="pw-container">
    <div class="home-hero-content">
      <p>Postcards and other garbage I love you</p>
      <a class="btn-lrg btn-lrg-dark" href="{{ "/postcards/" | relative_url }}">Check them out</a>
    </div>
  </div>
</section>

<section class="home-projects">
  <div class="pw-container">
    <h3><a name="products"></a>Products</h3>
    <div class="home-projects-list">
      {% for item in site.data.projects.list %}
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
