---
title: Research
nav:
  order: 1
---

# {% include icon.html icon="fas fa-sitemap"%}Research

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

[Read more in our publications on drying-induced assembly.](../../publications/?search=colloidal+suspensions)


{% include section.html %}
## Multiscale inverse design of nanocrystal superlattices
{% capture content %}
{%
  include figure.html
  image="images/inverse_design_figure.png"
  caption="Multiscale inverse design strategy."
  width="300px"
%}
{% endcapture %}

{%
   include float.html
   content=content
   flip=true
%}
Due to their small sizes, nanocrystals have remarkable properties that make them
promising components of advanced sensors and photocatalytic devices. The
properties of individual nanocrystals can be enhanced and controlled by
assembling them into larger ordered superlattices; however, there are limited
scalable strategies for fabricating superlattices with low defect rates.

We are computationally exploring a new solvent-based strategy to address this
problem. Our computational approach couples particle-based simulations with
optimization methods in an *inverse design* strategy that aims to determine
physicochemical properties of the solvent and nanocrystals that cause the
nanocrystals to self-assemble into a target superlattice. We aim to make
computational predictions that can be directly tested in the laboratory, so we
are actively developing inverse-design strategies to enable this connection,
including:

- Integrating atomistic and coarse-grained simulations in a single inverse design loop
- Using data-driven (surrogate) models to accelerate optimization

We have also developed a new software package,
[relentless](https://relentless.readthedocs.io), to carry out our inverse design
calculations. We anticipate relentless will be broadly useful beyond our own
application!

[Read more in our publications on inverse design.](../../publications/?search=inverse+design)


{% include section.html %}
## Ultra-coarse-grained simulations of protein self-assembly
{% capture content %}
{%
  include figure.html
  image="images/research-ultra-cg.jpg"
  caption="Surrogate model for ultra coarse-graining [source](https://pdb101.rcsb.org/motm/109)."
  width="300px"
%}
{% endcapture %}

{%
   include float.html
   content=content
%}
Viral capsids are spontaneously self-assembling structures, forming a protective
shell that surrounds the virus's genetic material. Self-assembly plays a
critical role in the virus life cycle and understanding the dynamics of the
process can create an avenue for designing therapeutics; however, capturing the
dynamics of self-assembly through conventional computer simulations, like
atomistic simulations, is challenging due to the problem's inherent
multidimensionality.

To address this challenge, our research, in collaboration with Dr. Chris Kieslich,
introduces an ultra-coarse-grained model for more efficient simulation of the
self-assembly process. This approach systematically integrates surrogate
modeling methodology, sparse sampling techniques, and established coarse-grained
theory. The result can be a precise and efficient approximation of the protein's
energy landscape, ideal for simulating viral capsid self-assembly.

More broadly, this research provides a foundational tool for simulating other
mesoscale phenomena, including the self-assembly of synthetic materials. 

[Read more in our publications on surrogate modeling.](../../publications/?search=surrogate+modeling)
