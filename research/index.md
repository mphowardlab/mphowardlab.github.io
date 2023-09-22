---
title: Research
nav:
  order: 1
---

# {% include icon.html icon="fas fa-sitemap"%}Research

We are working on some exciting projects! 

{% include list.html component="card" data="research" filters="" style="small" %}

{% include section.html %}
## Drying-induced nanoparticle self-assembly
{% capture content %}
{%
  include figure.html
  image="images/stratified.jpeg"
  caption="Self-stratified coating of small and big nanoparticles."
  width="300px"
%}
{% endcapture %}

{%
   include float.html
   content=content
%}

Nanoparticle-based materials are important for numerous technologies, ranging
from consumer products such as paints to advanced materials used for catalysis
or photonics. Often these materials are made by dispersing nanoparticles in a
solvent at low concentrations, then removing the solvent by evaporation or
drying to concentrate them. As the solvent is being removed, the nanoparticles
*self-assemble* into their final solid structure due to their physical
interactions and the changing concentration. The self-assembled structure, and
its corresponding material properties, can depend sensitively on how the
nanoparticle dispersion is processed. This is especially true when the
dispersion contains multiple types of nanoparticles.

We are interested in using solvent drying to cheaply and efficiently create
nanoparticle coatings or bigger "supraparticles" that have controlled
composition gradients. However, it is currently hard to know what combination of
parameters, such as drying rate or nanoparticle chemistry, will produced
the desired structure after the solvent is removed. We are using different
simulation methods, including both particle-based and continuum-level modeling,
to understand how thermodynamic and transport considerations influence
drying-induced self-assembly. Our ultimate goal is to computationally design
conditions that produce a targeted self-assembled structure.

This material is based upon work supported by the National Science Foundation
under Award No. 2223084. Any opinions, findings and conclusions or
recommendations expressed in this material are those of the authors and do not
necessarily reflect the views of the National Science Foundation.

[Read more in our publications on drying-induced assembly.](../../publications/?search=Colloidal+suspensions)
