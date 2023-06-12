---
title: Research
nav:
  order: 1
---

{% include section.html %}
<!--  -->
{% capture text %}

<!-- Add text -->

{%
  include button.html
  link="Non-equilibrium simulations"
  text="More information"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Nonequilibrium self-assembly of nanomaterials "
  text=text
%}
<!--  -->
{% capture text %}

<!-- Add text -->

{%
  include button.html
  link="id_plasmonics"
  text="More information"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/inverse_design_plasmonics_figure.png"
  link="id_plasmonics"
  title="Inverse design of plasmonic nanocrystal superlattices"
  flip=true
  style="bare"
  text=text
%}
<!--  -->
{% capture text %}

<!-- Add text -->

{%
  include button.html
  link="software"
  text="More information"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="software"
  title="Title"
  text=text
%}

<!--  -->
{% capture text %}

<!-- Add text -->

{%
  include button.html
  link="title"
  text="More information"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="people"
  title="Title"
  flip=true
  style="bare"
  text=text
%}
