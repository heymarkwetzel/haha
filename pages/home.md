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

<section class="pw-container-full">
  <section class="home-buy-online">
    <div class="pw-container-1-2">
      <h3>Buy Wholesale</h3>
      <div class="need-to-insert-image-control">
      </div>
    </div>
  </section>

  <section class="home-buy-online">
    <div class="pw-container-1-2">
      <h3>Buy on Etsy</h3>
      <div class="need-to-insert-image-control">
      </div>
    </div>
  </section>
</section>

<section class="home-projects">
  <div class="pw-container">
    <h3><a name="projects"></a>Haha Hot Dogs</h3>
    <div class="home-projects-list">
      {% for item in site.data.projects.list %}
      <div class="home-project">
        <a href="{{ item.url }}" alt="{{ item.title }}" data-lightbox="postcards">
          <img class="home-project-thumbnail" src="{{ item.thumbnail }}" />
          <!-- <h4 class="home-project-title">{{ item.title }}</h4> -->
          <p class="home-project-description">{{ item.description }}</p>
        </a>
      </div>
      {% endfor %}
    </div>
  </div>
</section>
