---
layout: page
title: Book Me
permalink: /book-me/
description: Johnny Arrow
background: '/img/ice-demon/arrow-acrobatics-ndsm-pale.jpg'
---

## Solo Aerial Rope, Silks or Straps, Modelling
Johnny is a versatile performer who works in dinnershows, burlesque, festivals and theater. He is an experienced hand-to-hand acrobat and
hand balancer while specializing in aerial rope, straps and silks. His solo work is theatrical by nature and seeks to hide
meaning in unexpected layers.

{% for post in site.tags.solo limit : 5 %}
  {% include post_preview.html post=post %}
{% endfor %}
