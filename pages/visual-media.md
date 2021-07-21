---
layout: visual-medias
sidebar: right
show_meta: false
title: "Visual Media"
subheadline: All
description: Interactive list of visual media scores by Robby Good.
permalink: "/visual-media/"
---

<ul class="side-nav">
    {% for post in site.visual_media reversed %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{% if post.subheadline %}{{ post.subheadline }} &middot; {% endif %}<span class="visual_media-list-titles">{{ post.title }}</span><br><span class="visual_media-list-descriptions">{{ post.release_date }} / By {{ post.creator }}</span><span class="visual-media_list-duration">{{ post.media_type }}</span></a></li>
{% endfor %}
</ul>