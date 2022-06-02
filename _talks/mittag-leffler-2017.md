---
title: 'Multi-rate Runge-Kutta-Chebyschev
time-stepping for parabolic equations
on adaptively refined meshes'
collection: talks
type: Workshop lecture
talk_type: Workshop lecture
permalink: /talks/mittag-leffler-2017.html
abstract: 'Adaptive mesh refinement (AMR) is widely recognized as a way to use computational resources efficiently.  Often used to improve the performance of finite volume or finite difference methods on logically Cartesian meshes, an adaptive mesh strategy dynamically allocates mesh resources in regions in the computational domain where the demands for resolution are the highest.  When using explicit time stepping schemes on adaptive meshes, it is often advantageous to use local time stepping as well, and allow coarser regions of the domain to take larger time steps than finer regions. 

Runge-Kutta-Chebyschev (RKC) methods are a class of stabilized, single step, multi-stage explicit time stepping methods designed to efficiently solve mildly stiff differential equations.   RKC schemes are relatively easy to implement and have low storage requirements, and so are ideal candidates for solving parabolic partial differential equations using  a method-of-lines approach.    While parabolic equations are most commonly solved using implicit methods, explicit methods are generally easier to implement,  especially for non-uniform or adaptive meshes, or for coupled systems of parabolic equations.  Furthermore, they are {\em direct} in the sense that the solution at time $T$ can be obtained after a number of steps that is known a priori.  Finally, when combining diffusion with other operators (e.g. advection), operator splitting errors can be avoided if methods for both schemes are explicit.  

We have developed an algorithm which uses RKC time stepping for adaptive refinement in time and space.  The essential component in the algorithm is a mechanism for interleaving the stage 
progression between levels and interpolating in time between stages when spatial refinement levels are not time synchronized.  We have used this algorithm for solving a one-dimensional heat equation on an adaptively refined mesh, and find that, depending on the refinement strategy, time savings using both adaptivity in time and space can be significant, when compared to solving the equivalent problem on a uniformly refined mesh.  We also present results using ForestClaw, a two-dimensional block-structured quadtree code for solving two dimensional hyperbolic problems on adaptively refined finite volume meshes.   Applications of interest are reaction-diffusion problems, including crystal growth, and biological pattern formation.'
slides: 'mittag-leffler-2017.pdf'
date: 2017-06-02
date_talk: Jun 02, 2017
date_conference: 'May 29 - Jun 02, 2017'
venue: 'Numerical methods for PDEs and their applications'
organization: 'Institut Mittag-Leffler (The Royal Swedish Academy of Sciences)'
conference_url: 'http://www.mittag-leffler.se/workshop/numerical-methods-pdes-and-their-applications'
location: Institue Mittag-Leffter, Djursholm, Sweden
authors: Donna Calhoun, Talin Mirzakhanian, David Ketcheson
---
