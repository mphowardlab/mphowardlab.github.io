---
---

{% include section.html %}

{% capture text %}

We use multiscale modeling, computer simulations, and fundamental chemical
engineering concepts to develop new scientific understanding and solutions
to engineering challenges in soft materials.

{%
  include button.html
  link="research"
  text="Learn about our work"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

We are an active group of graduate and undergraduate researchers working together 
to make an impact. We strive to become technically outstanding engineers and to 
develop the future workforce in computational material sciences.

{%
  include button.html
  link="people"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/2025-02-group.jpg"
  link="people"
  title="Our Team"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

We develop new scientific software to enable our own work and to support other
researchers in our community. We aim to create more open, accessible, and
reproducible science.

{%
  include button.html
  link="software"
  text="Explore our software"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/software-feature.png"
  link="software"
  title="Our Software"
  text=text
%}
