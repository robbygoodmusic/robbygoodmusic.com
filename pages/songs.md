---
layout: works
sidebar: right
show_meta: false
title: "Songs and Other Projects"
subheadline: All
description: Interactive list of songs and other miscellaneous projects and collaborations by Robby Good.
permalink: "/songs/"
---

<ul class="side-nav">
    {% for post in site.songs reversed %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{% if post.subheadline %}{{ post.subheadline }} &middot; {% endif %}<span class="songs-list-titles">{{ post.title }}</span><br><span class="songs-list-descriptions">{{ post.release_date }} / For {{ post.instrumentation }}</span><span class="songs-list-duration">{{ post.duration }}</span></a></li>
    {% endfor %}
</ul>