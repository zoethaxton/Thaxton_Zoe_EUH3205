---
layout: default
title: Supplements
number: 4
---

# Supplements

# Timeline

<iframe class='timeline-iframe' src='https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1ggyFnihALsjnK22MpUlcurmowEgVLBcoK-D8aGK1y2I&font=Default&lang=en&initial_zoom=2&height=650' width='100%' height='650' webkitallowfullscreen mozallowfullscreen allowfullscreen frameborder='0'></iframe> 

# Supplementary Websites

https://study.com/academy/lesson/video/europe-reacts-to-the-french-revolution.html 
https://guides.loc.gov/women-in-the-french-revolution/revolutions-rebellions/1789-1830-1848

# Supplementary Media Files

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'revolutionsof1848'" %}
{% include media.html pages=media %}

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'ReactionstotheFrenchRevolution'" %}
{% include media.html pages=media %}

{% assign media = site.media_metadata | where_exp: "item", "item.name == '19thCenturyIsms'" %}
{% include media.html pages=media %}
