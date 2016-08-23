---
layout: default
title: Blog
permalink: /blog/
---

<div class="container">
    <div class="row">
        <div class="col-md-12">
            {% for post in site.paginator.posts %}
                {% include tile.html %}
            {% endfor %}

            {% include pagination.html %}
        </div>
    </div>
</div>
