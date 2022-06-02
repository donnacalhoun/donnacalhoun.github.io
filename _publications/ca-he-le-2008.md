---
title: 'Logically rectangular grids and finite volume methods for PDEs in circular and spherical domains'
collection: publications
publish_type: journal-article
permalink: /publication/journal-article/ca-he-le-2008.html
abstract: 'We describe a class of logically rectangular quadrilateral and hexahedral grids for solving PDEs in circular and spherical domains, including grid mappings for the circle, the sur- face of the sphere, and the three-dimensional ball. The grids are logically rectangular and the computational domain is a single Cartesian grid. Compared to alternative approaches based on a multiblock data structure o runstructured triangulations, this approach simplifies the implementation of numerical methods and the use of adaptive refinement. A more general domain with a smooth boundary can be gridded by composing one of the mappings from this paper with another smooth mapping from the circle or sphere to the desired domain. Although these grids are highly nonorthogonal, we show that the high- resolution wave-propagation algorithm implemented in clawpack can be used effectively to approximate hyperbolic problems on these grids. Since the ratio between the largest and smallest grids is below 2 for most of our grid mappings, explicit finite volume methods such as the wave-propagation algorithm do not suffer from the center or pole singularities that arise with polar or latitude-longitude grids. Numerical test calculations illustrate the potential use of these grids for a variety of applications including Euler equations, shal- low water equations, and acoustics in a heterogeneous medium. Pattern formation from a reaction-diffusion equation on the sphere is also considered. All examples are implemented in the clawpack software package and full source code is available on the web, along with MATLAB routines for the various mappings.'
date: 01/01/2008
venue: 'SIAM Review'
paperurl: 'http://dx.doi.org/10.1137/060664094'
citation: 'Donna Calhoun, Christiane Helzel, Randall LeVeque, "Logically rectangular grids and finite volume methods for PDEs in circular and spherical domains", <i>SIAM Review</i>, 2008.'
download: ca-he-le-2008.pdf
---
