---
---



An engaging 1-3 sentence description of your lab.

{% include section.html %}

## Highlights

{% capture text %}

We use multiscale modeling, computer simulations, and fundamental chemical
engineering concepts to develop new scientific understanding and engineering
solutions to difficult problems in soft matter.

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

We are a team of individuals working together toward our common research goals. We
value the unique experiences and perspectives that everyone brings to their work.
As a team, we strive to train technically outstanding chemical engineers and to
build a more inclusive workforce in computational molecular science.

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
  image="images/2022-10-group.jpg"
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
  image="images/photo.jpg"
  link="software"
  title="Our Software"
  text=text
%}
