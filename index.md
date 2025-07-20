---
layout: base.njk
title: Home
---

## Stories

<div class="card-grid">
{% for story in collections.story %}
    <a href="{{ story.url }}" class="card">
        <h3>{{ story.data.title }}</h3>
    </a>
{% endfor %}
</div>