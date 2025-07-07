---
layout: splash
title: Projects
permalink: /projects/
author_profile: true
---
<br>
Main Project

<div class="github-cards-grid">
  {% for project in site.data.projects %}
    {% include github-card.html 
       name=project.name
       description=project.description
       github=project.github
       stars=project.stars
       forks=project.forks
       language=project.language
       language_color=project.language_color
       url=project.url
    %}
  {% endfor %}
</div>


---
Smaller Project

<div class="github-cards-grid">
  {% for project in site.data.miniprojects %}
    {% include github-card.html 
       name=project.name
       description=project.description
       github=project.github
       stars=project.stars
       forks=project.forks
       language=project.language
       language_color=project.language_color
       url=project.url
    %}
  {% endfor %}
</div>