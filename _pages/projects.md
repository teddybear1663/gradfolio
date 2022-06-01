---
title:
layout: default
permalink: /projects/
published: true
---


<div class="ProjectContainer">

	<div class="gallery">


  {% for project in site.projects %}
  
  <div class="projectTile">
          <a href="{{ project.url | prepend: site.baseurl | prepend: site.url }}">
          <span>
              <h2>{{ project.title }}</h2>
              <br/>
              <p>{{ project.description }}</p>
          </span>
          </a>
  </div>
  
  {% endfor %}

	</div>

</div>
