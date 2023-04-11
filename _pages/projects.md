---
layout: default
title: Aytek's Projects
permalink: /projects
---

<!-- Projects
================================================== -->
<section class="recent-posts">

    <div class="row listrecent">

    {% for post in site.posts %}

        {% if post.project == true %}

            {% include postbox.html %}

        {% endif %}

    {% endfor %}

    </div>
</section>