---
layout: songs
sidebar: right
show_meta: false
title: "Songs and Other Projects"
subheadline: All
description: Interactive list of songs and other miscellaneous projects and collaborations by Robby Good.
permalink: "/songs/"
---

<ul class="side-nav">
    {% for post in site.songs reversed %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{% if post.subheadline %}{{ post.subheadline }} &middot; {% endif %}<span class="works-list-titles">{{ post.title }}</span><br><span class="works-list-descriptions">{{ post.release_date }} / For {{ post.instrumentation }}</span><span class="works-list-duration">{{ post.duration }}</span></a></li>
    {% endfor %}
</ul>