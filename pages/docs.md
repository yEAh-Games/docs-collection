---
layout: page
title: Documentation
permalink: /docs/
---

{% include alert.html type="info" title="yEAh Docs 2.0" content="The yEAh Docs are currently undergoing extensive reconstruction and renovation. We are transitioning to yEAh Docs 2.0, which involves migrating files, implementing new styling and formatting, and introducing updated documentation content. Kindly note that the process is still ongoing, and not all sections may function as expected. If you require information from the previous version, you can switch to '1.0' using the version selector at the top. We apologize for any inconvenience and appreciate your patience during this transition. For assistance or inquiries, please contact the docs team at docs@yeahgames.net." %}

Welcome to the yEAh Docs! Discover comprehensive documentation covering every site, service, and feature on the yEAh Network. Our detailed guides provide valuable insights, instructions, and troubleshooting tips. Engage with our community through built-in comment integration to discuss topics, share insights, and collaborate with other members. Empower yourself with knowledge and unlock the full potential of the yEAh Network.

<hr style="border-color:white">
# <span title="Recently updated documentation pages">Updates</span>

<div class="section-index">
    <hr class="panel-line">
    {% assign recent_docs = site.docs | sort: 'date' | reverse | limit: 20 %}
    {% for post in recent_docs %}
        {% if post.url contains '/docs/v/' %}
            {% continue %}
        {% endif %}
        <div class="entry">
            <h5><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h5>
            <p>{{ post.description }}</p>
        </div>
    {% endfor %}
</div>