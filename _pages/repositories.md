---
layout: page
permalink: /repositories/
title: Repositories
description: Here you will find data analysis and modeling code from my papers. They are all easy to apply to your own data in a few lines of code.
nav: true
nav_order: 4
---


## GitHub

{% if site.data.repositories.github_repos %}

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}
