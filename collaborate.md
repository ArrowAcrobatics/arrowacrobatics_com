---
layout: page
title: Collaborate
permalink: /collaborate/
background: "/img/collaborate/arrowacrobatics-dancevalley-rainbowedition-cropped.jpg"
description: Art is Conversation
---

## Let's work together!
Over the years it has been my privilege to work together and befriend many beautiful artists in many different
subcultures. If you have an idea that you think would be awesome to make happen together, just shoot me a message
and see where it leads us! Modeling, opera, cabaret, dance, costumes, acrobatics, drag, fire, burlesque... what about it?


{% for post in site.tags.collaborate limit : 5 %}
  {% include post_preview.html post=post %}
{% endfor %}
