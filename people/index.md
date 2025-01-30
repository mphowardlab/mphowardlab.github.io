---
title: People
nav:
  order: 2
---

# {% include icon.html icon="fa-solid fa-users" %}People

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: ^pi$" %}
{% include list.html data="members" component="portrait" filters="role: ^postdoc$" %}
{% include list.html data="members" component="portrait" filters="role: phd-candidate" %}
{% include list.html data="members" component="portrait" filters="role: phd-student" %}
{% include list.html data="members" component="portrait" filters="role: masters-student" %}
{% include list.html data="members" component="portrait" filters="role: undergrad-student" %}

{% include section.html dark=true %}

We aim to have strong relationships among our team members. To achieve this,
we take occasional breaks to socialize and unwind, to build a supportive work
environment that enhances our research collaboration and goals. 

{% include section.html %}

{% include slideshow.html data="group_photos" filters="" %}


{% include section.html %}
## Alumni

{% include list.html data="members" component="portrait" filters="role: postdoc-alum" %}
{% include list.html data="members" component="portrait" filters="role: phd-alum" %}
{% include list.html data="members" component="portrait" filters="role: masters-alum" %}
{% include list.html data="members" component="portrait" filters="role: undergrad-alum" %}
