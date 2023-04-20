---
title: People
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our research team is made up of 

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: candidate" %}
{% include list.html data="members" component="portrait" filters="role: phd" %}
{% include list.html data="members" component="portrait" filters="role: undergrad" %}

{% include section.html background="images/background.jpg" dark=true %}

We strive to have strong relationships among our team members. To achieve this, we take occasional breaks to socialize and unwind, to build a supportive work environment that enhances our research collaboration and goals. 

{% include section.html %}

{% capture content %}

  {% include figure.html image="images/2022-07-BBQ.jpg" %}
  {% include figure.html image="images/cookie_dec_2.jpg" %}
  {% include figure.html image="images/cookie_dec.jpg" %}
  
{% endcapture %}

{% include grid.html style="square" content=content %}

{% include section.html background="images/background.jpg" dark=true %}

Soon to come our alumni.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: alumni" %}