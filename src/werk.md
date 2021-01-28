---
title: 'Werk'
layout: 'layouts/page.html'
custom_css: 'footer {visibility: visible; font-size:0.5rem;} p {font-size: 2rem; font-family: Roboto;}'
---

Gedreven freelance webdesigner & WordPress developer met meer dan 5 jaar ervaring. Ik hamer op <span class="highlight">kwaliteit</span> en zweer bij <span class="highlight">maatwerk</span>. Samen met u ga ik op zoek naar de beste oplossing voor uw project.

<div id="table">
  <ul>
  </ul>
  <ul>
    <li><span class="highlight">DESIGN</span></li>
    <li>Webdesign</li>
    <li>Logo design</li>
    <li>Branding</li>
    <li>Grafisch ontwerp</li>
  </ul>

  <ul>
    <li><span class="highlight">WEBDEVELOPMENT</span></li>
    <li>Front-end development</li>
    <li>WordPress development</li>
    <li>WordPress onderhoud</li>
    <li>SEO optimalisatie</li>
  </ul>
</div>

<br>

### Enkele van mijn werkjes

<div id="work">
{% for item in collections.featuredWork %}
  <a class="effect" href="{{ item.url }}">
    <img src="{{ item.data.image }}" alt="{{ item.data.summary }}"/>
  </a>
{% endfor %}
</div>
