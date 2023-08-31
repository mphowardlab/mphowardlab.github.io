---
title: Non-equilibrium simulations

---

{% include section.html %}
<!--  -->
{% capture text %}

<!-- Add text -->
Nanoparticles or colloidal dispersions play a vital role in our daily lives. From paints to catalysts, they can be produced using colloidal dispersions. If a dispersion has different types of particles, various aspects can be controlled to make it self-assemble into desired structures. One such aspect we are controlling in this study is solvent evaporation. Solvent evaporation allows us to create self-assembled coatings and supraparticles cheaply and efficiently. However, it is hard to know what combination of parameters, such as evaporation rate, particle sizes, initial film or droplet length, etc., would result in the desired structure when using the solvent evaporation method. We can conduct physical experiments in the laboratory; however, it would be time consuming to go through the different permutations of parameters that would result in the desired structure. This is where computer simulations and modeling comes into the picture! It allows us to go through the various parameters that affect the process and gives us an insight into the physics governing it. 

Currently, this study involves two kinds of simulation techniques. For one of them, we use particle-based simulation technique based on multi-particle collision dynamics (MPCD) to study transport properties of various novel particle shapes. To compute the various transport properties, sedimentation simulations are conducted for the different particle shapes considered using the MPCD method.

For the other one, we use a continuum simulation technique based on dynamic density functional theory (DDFT). We are trying to understand the thermodynamic and transport parameters required to achieve desired structures using evaporation-induced self-assembly in multi-component drying colloidal suspension. In addition to this, we use established particle-based simulation software such as HOOMD to see the overall structure evolution of the drying nano-particle system.

{% endcapture %}

{%
  include feature.html
  image="images/software.png"
  link="research"
  title="Nonequilibrium self-assembly of nanomaterials "
  text=text
%}
<!--  -->
