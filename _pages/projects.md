---
layout: default
title: Aytek's Projects
permalink: /projects
---

<!-- Projects
================================================== -->
<section class="featured-posts">
    <div class="section-title">
        <h2><span>Projects</span></h2>
    </div>
    <div class="row">

    {% for post in site.posts %}

        {% if post.project == true %}

            {% include featuredbox.html %}

        {% endif %}

    {% endfor %}

    </div>
</section>