---
layout: arrangements
sidebar: right
show_meta: false
title: "Arrangements"
subheadline: All arrangements are available for purchase through email!
description: Interactive list of arrangements by Robby Good.
permalink: "/arrangements/"
---

<ul class="side-nav">
    {% for post in site.arrangements reversed %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{% if post.subheadline %}{{ post.subheadline }} &middot; {% endif %}<span class="works-list-titles">{{ post.title }}</span><br><span class="works-list-descriptions">{{ post.year_arranged }} / For {{ post.instrumentation }}</span><span class="works-list-duration">{{ post.duration }}</span></a></li>
{% endfor %}
</ul>