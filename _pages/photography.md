---
layout: page
title: Photography
description: 
permalink: /photography/
nav: true
nav_order: 4
---

<!-- Lightbox CSS & JS should be included globally, e.g. in _includes/head_custom.html -->

<style>
  .photo-container {
    margin: 40px auto;
    max-width: 600px;
    text-align: center;
  }

  .photo-container img {
    width: 100%;
    border-radius: 8px;
    transition: box-shadow 0.3s ease;
    cursor: zoom-in;
  }

  .photo-container img:hover {
    box-shadow: 0 8px 24px rgba(0, 0, 0, 0.2);
  }

  .photo-caption {
    margin-top: 10px;
    font-size: 0.9em;
    color: #555;
    font-family: 'Lora', serif;
  }
</style>

<div class="photo-container">
  <a href="{{ site.baseurl }}/assets/img/Photos/Photo1.jpg" data-lightbox="gallery" title="Arosa, October 2024, 35mm B/W film">
    <img src="{{ site.baseurl }}/assets/img/Photos/Photo1.jpg" alt="Photo 1">
  </a>
  <div class="photo-caption">Arosa, October 2024, 35mm B/W film</div>
</div>

<div class="photo-container">
  <a href="{{ site.baseurl }}/assets/img/Photos/Photo2.jpg" data-lightbox="gallery" title="Konstanz, September 2024, 35mm B/W film">
    <img src="{{ site.baseurl }}/assets/img/Photos/Photo2.jpg" alt="Photo 2">
  </a>
  <div class="photo-caption">Konstanz, September 2024, 35mm B/W film</div>
</div>

<div class="photo-container">
  <a href="{{ site.baseurl }}/assets/img/Photos/Photo3.jpg" data-lightbox="gallery" title="Konstanz, September 2024, 35mm B/W film">
    <img src="{{ site.baseurl }}/assets/img/Photos/Photo3.jpg" alt="Photo 3">
  </a>
  <div class="photo-caption">Konstanz, September 2024, 35mm B/W film</div>
</div>
