---
title: 'Multirate RKC time stepping on
adaptively refined meshes'
collection: talks
type: Workshop lecture
talk_type: Workshop lecture
permalink: /talks/banff-2018.html
abstract: 'Adaptive mesh refinement (AMR) has been widely used for solving a variety of 
PDEs in which solution features of interest are spatially localized.  In the past three decades, much attention has been devoted to spatial discretization in the AMR setting, while relatively little attention has been paid to time stepping on a multi-resolution hierarchy of grids.  Adaptive time stepping, aimed at preserving a constant CFL number across the mesh hierarchy, was built into the original Berger-Oliger and Berger-Collela approaches to adaptive mesh refinement, but in its original form, this adaptive time stepping was only well suited to single-step, single-stage time stepping schemes.  While more sophisticated schemes can be easily implemented if the same size time step is used on all grids (global time stepping), little attention has been given to combining adaptive time stepping with multi-step or multi-stage schemes.

In this talk, we present our current efforts to combine the multi-stage, explicit Runge-Kutta-Chebyshev (RKC) integration scheme with adaptive time stepping.  Using the RKC scheme, we can solve parabolic equations using explicit time stepping in a manner that is competitive, if not superior to alternative implicit approaches.  The multi-stage nature of the scheme requires special algorithmic structures be built into the core AMR time stepping strategy.  In particular, for finite volume schemes, extra effort may be required to ensure that the resulting scheme is conservative. We have developed a algorithmic approach to implementing the RKC scheme on an one-dimensional adaptively refined mesh using adaptive time stepping, and are currently working on a two dimensional approach in our block-structured adaptive code ForestClaw. We will present results from typical reaction diffusion problems. '
slides: 'banff-2018.pdf'
video: 'https://www.birs.ca/events/2018/5-day-workshops/18w5152/videos/watch/201812051104-Calhoun.html'
date: 2018-12-05
date_talk: Dec 05, 2018
date_conference: 'Dec 02 - Dec 07, 2018'
venue: 'Integrating the Integrators for Nonlinear Evolution Equations &#58; from Analysis to Numerical Methods, High-Performance-Computing and Applications'
organization: 'Banff International Research Station'
conference_url: 'https://www.birs.ca/events/2018/5-day-workshops/18w5152'
location: Banff, Canada
authors: Donna Calhoun, Talin Mirzakhanian
---
