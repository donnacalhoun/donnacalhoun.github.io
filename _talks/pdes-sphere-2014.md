---
title: 'Parallel, adaptive framework for
mapped, multi-block domains'
collection: talks
type: Workshop lecture
talk_type: Workshop lecture
permalink: /talks/pdes-sphere-2014.html
abstract: 'We describe a parallel, adaptive, multiblock method for solving conservation laws on a finite volume sphere grid. The grid layout we consider consists of a nested hierarchy of fixed size, non-overlapping, logically Cartesian meshes stored as leaves in a quadtree.  Dynamic grid refinement and de-refinement, and parallel partitioning of the grids is done through the use of the highly scalable quadtree/octree based p4est code (C. Burstedde).  Because the code is multi-block, we are able to easily solve on a variety of geometries, including cubed sphere and the two-patch sphere grid proposed by Calhoun, Helzel and LeVeque (SIAM Review, 2008).  We describe the details for coordinating the multi-rate time stepping strategy with parallel ghost patch exchanges and show that that using a multi-rate time stepping does not impact the parallel performance. We will demonstrate results from benchmark problems described in Lauritzen et al. (Geoscientific Model Development, 2014), using the second order, finite volume wave propagation algorithms for
hyperbolic PDEs (ClawPack, R. J. LeVeque).'
slides: 'pdes-sphere-2014.pdf'
date: 2014-04-09
date_talk: Apr 09, 2014
date_conference: 'Apr 07 - Apr 11, 2014'
venue: 'PDEs on the Sphere'
organization: 'National Center for Atmospheric Research (NCAR)'
conference_url: 'https://www.cgd.ucar.edu/events/20140407/'
location: Boulder, CO (USA)
authors: Donna Calhoun, Carsten Burstedde
---
