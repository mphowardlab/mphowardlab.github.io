---
title: People
nav:
  order: 2
---

# {% include icon.html icon="fa-solid fa-users" %}People

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: candidate" %}
{% include list.html data="members" component="portrait" filters="role: phd" %}
{% include list.html data="members" component="portrait" filters="role: undergrad" %}

{% include section.html dark=true %}

We aim to have strong relationships among our team members. To achieve this,
we take occasional breaks to socialize and unwind, to build a supportive work
environment that enhances our research collaboration and goals. 

{% include section.html %}

{% include slideshow.html data="group_photos" filters="" %}
