---
layout: archive
title: Projects
permalink: /projects/
description: Some interesting projects
nav: true
display_categories: [work, fun]
horizontal: false
---
<div class="projects grid">
    <ul>
        <li>In-course project: Point cloud generation by Variational Auto-encoder. <a
                href='../files/pointer_cloud.pdf'>[report]</a></li>
        <li>In-course project: Music playlist recommendation system. <a
                href='../files/playlist_recommandation.pdf'>[report]</a></li>
        <li>In-course project: Autonomous Driving. <a href='../files/auto_drive.pdf'>[report]</a></li>
        <li>In-course project: Huarong Dao Puzzle Solution(Search). <a href='../files/huarongdao.pdf'>[report]</a></li>
    </ul>
    <!-- 
  {% assign sorted_projects = site.projects | sort: "importance" %}
  {% for project in sorted_projects %}
  <div class="grid-item">
    {% if project.redirect %}
    <a href="{{ project.redirect }}" target="_blank">
    {% else %}
    <a href="{{ project.url | relative_url }}">
    {% endif %}
      <div class="card hoverable">
        {% if project.img %}
        <img src="{{ project.img | relative_url }}" alt="project thumbnail">
        {% endif %}
        <div class="card-body">
          <h2 class="card-title text-lowercase">{{ project.title }}</h2>
          <p class="card-text">{{ project.description }}</p>
          <div class="row ml-1 mr-1 p-0">
            {% if project.github %}
            <div class="github-icon">
              <div class="icon" data-toggle="tooltip" title="Code Repository">
                <a href="{{ project.github }}" target="_blank"><i class="fab fa-github gh-icon"></i></a>
              </div>
              {% if project.github_stars %}
              <span class="stars" data-toggle="tooltip" title="GitHub Stars">
                <i class="fas fa-star"></i>
                <span id="{{ project.github_stars }}-stars"></span>
              </span>
              {% endif %}
            </div>
            {% endif %}
          </div>
        </div>
      </div>
    </a>
  </div>
{% endfor %}
 -->

</div>

<!-- ---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
--- -->

<!-- {% include base_path %}


{% for post in site.projects %}
{% include archive-single.html %}
{% endfor %} -->