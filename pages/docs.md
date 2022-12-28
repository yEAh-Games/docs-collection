---
layout: page
title: Documentation
permalink: /docs/
---

# Documentation

Welcome to the yEAh Games Documentation pages! Here you can quickly jump to a 
particular page. This list is based on when docs were published (newest first); please use the sidebar to view the docs in their proper folders.

<div class="section-index">
    <hr class="panel-line">
    {% for post in site.docs  %}        
    <div class="entry">
    <h5><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h5>
    <p>{{ post.description }}</p>
    </div>{% endfor %}
</div>
