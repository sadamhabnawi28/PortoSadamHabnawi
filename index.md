---
layout: default
title: Home
---

<link rel="stylesheet" href="{{ '/assets/css/style.css' | relative_url }}">

<div class="wrapper">

  {% include hero.html %}

  <div class="layout">

    {% include sidebar.html %}

    <main class="content">
      {% include about.html %}
      {% include projects.html %}
      {% include skills.html %}
      {% include contact.html %}
    </main>

  </div>
</div>
