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
promising components of advanced sensors. The
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
  caption="Methodology for ultra coarse-graining [[source]](https://pdb101.rcsb.org/motm/109)."
  width="300px"
%}
{% endcapture %}

{%
   include float.html
   content=content
%}
Capsids are container-like structures made from proteins that form a protective
shell around a virus's genetic material. Self-assembly of the capsid plays a
critical role in the virus life cycle, and understanding the dynamics of this
process may provide an avenue for designing therapeutics. However,
characterizing the dynamic pathway of capsid self-assembly is challenging to for
experiments, but the length and time scales of this process exceed current
capabilities of atomistic molecular dynamics.

To address this challenge, we are working with Dr. Chris Kieslich to develop a
computationally efficient ultra-coarse-grained model, representing each capsid
protein as a single coarse-grained particle, so that we can simulate capsid
assembly from protein solutions at unprecedented scales. Our approach
systematically integrates surrogate modeling, sparse sampling, and statistical
mechanics for coarse graining to efficiently compute an accurate approximation
of the pairwise potential of mean force and torque.

This work is supported by Auburn University's Research Support Program.

[Read more in our publications on surrogate modeling.](../../publications/?search=surrogate+modeling)

{% include section.html %}
## Elastic turbulence in branched and associating polymer solutions
{% capture content %}
{%
  include figure.html
  image="images/research-elastic-turbulence.jpg"
  caption="Flow through an expansion."
  width="300px"
%}
{% endcapture %}

{%
   include float.html
   content=content
%}
Polymer flooding is an enhanced oil recovery method that uses solutions of 
high-molecular-weight polymers to displace oil trapped in reservoirs. This 
method has a surprisingly high recovery efficiency that is believed to be caused 
by a flow instability called elastic turbulence and is known to depend on the 
architecture and chemistry of the polymers. We are using dissipative particle 
dynamics and multiparticle collision dynamics simulations to study the molecular 
mechanisms that underly elastic turbulence. Our long-term goal is to 
rationally engineer better polymers for flooding processes.

This work is supported by the donors of ACS Petroleum Research Fund under Grant 66616-DNI9.

[Read more in our publications on elastic turbulence.](../../publications/?search=elastic+turbulence)
## Materials optimization for advanced bus technologies
{% capture content %}
{%
  include figure.html
  image="images/photo.jpg"
  caption="Placeholder figure."
  width="300px"
%}
{% endcapture %}

{%
   include float.html
   content=content
%}
There is an opportunity to improve the performance and economics of advanced bus 
technologies by engineering their components. For example, the HVAC system can 
be the second-largest energy consumer in electric buses¬, and a significant portion 
of the energy consumed by the HVAC system is lost through windows and structural 
panels. Minimizing such losses may be an opportunity to decrease operating costs 
and downtime. We are using computational heat-transfer models to understand heat
 losses through components of advanced transit-bus technologies. The model will 
 incorporate material properties of bus components that are being systematically 
 measured by Dr. Bryan Beckingham and Dr. Cassandra Porter. We are also conducting 
 a sensitivity analysis for the different climates found throughout the United 
 States. This work will enable optimization of and improved decision-making about 
 materials used in advanced bus technologies.

[Read more in our publications on materials for advanced bus technologies.](../../publications/?search=bus)
## Molecular simulations of multicomponent transport in polymer membranes
{% capture content %}
{%
  include figure.html
  image="images/photo.jpg"
  caption="Placeholder figure."
  width="300px"
%}
{% endcapture %}

{%
   include float.html
   content=content
%}
Polymer membranes are an important separations technology for the chemical 
industry. A key engineering goal is to increase membrane selectivity to desired 
solutes while maximizing permeability. However, selectivity and permeability are 
controlled by transport phenomena that are poorly understood for industrially 
relevant multicomponent mixtures, in which molecular-scale interactions can 
nontrivially enhance or inhibit transport compared to binary mixtures. Traditional 
experimental approaches for characterizing multicomponent membrane-based 
separations yield limited information about these interactions, so we are using 
atomistic molecular dynamics simulations to better understanding them using binary 
and ternary alcohol–water mixtures as a platform fluid.

[Read more in our publications on multicomponent transport in polymer membranes.](../../publications/?search=polymer+membranes)
## Multiparticle Collision Dynamics
{% capture content %}
{%
  include figure.html
  image="images/photo.jpg"
  caption="Placeholder figure."
  width="300px"
%}
{% endcapture %}

{%
   include float.html
   content=content
%}
Simulating the behavior of soft materials, such as nanoparticles or polymers, suspended in a solvent is critical for addressing numerous challenges, including improving the efficiency of wastewater treatment technologies, processing advanced materials for energy applications, and effectively delivering drugs to the body. Solvent-mediated hydrodynamic interactions typically play an important role, but the solvent is difficult to model at relevant scales because of its significantly smaller size than the suspended materials. Multiparticle collision dynamics (MPCD) is a mesoscopic, particle-based simulation method that can flexibly address this challenge. We previously developed open-source MPCD software in HOOMD-blue with parallelization for both CPUs and GPUs, and we are currently working on key features needed to support new science and engineering, including:
* A more convenient and faster approach for modeling nanoparticle suspensions using rigid body dynamics
* Expanded capabilities for modeling complex boundaries as triangulated surfaces
* Methods for simulating rheology, including Lees–Edwards boundary conditions, reverse nonequilibrium simulations, and wall-driven flows.
This material is based upon work support by the National Science Foundation under Award No. 2310724.


[Read more in our publications on multiparticle collision dynamics.](../../publications/?search=multiparticle+collision+dynamics)
