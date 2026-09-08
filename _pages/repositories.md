---
layout: page
permalink: /repositories/
title: Repositories
description: Open-source work and research code by Muhammad Ayaz.
nav: true
nav_order: 4
---

## GitHub

Research code and public projects are available on [Muhammad Ayaz's GitHub profile](https://github.com/ayazkhan789).

{% if site.data.repositories.github_users %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    {% include repository/repo_user.html username=user %}
  {% endfor %}
</div>

{% endif %}

Individual repositories are intentionally not listed here until their names and public status have been verified.
