---
title: 'A locally adaptive Cartesian, finitevolume
framework for solving PDEs
on surfaces'
collection: talks
type: Invited
talk_type: Invited
permalink: /talks/oxford-2012.html
abstract: 'We describe our current efforts to develop finite volume schemes for solving PDEs on logically Cartesian locally adapted surfaces meshes.  Our methods require an underlying smooth or
piecewise smooth grid transformation from a Cartesian computational space to 3d surface meshes, but does not rely on analytic metric terms to obtain second order accuracy.  Our hyperbolic solvers are based on Clawpack (R. J. LeVeque) and the parabolic solvers are based on a diamond-cell approach (Y. Coudi\`ere, T. Gallou\&quot;et, R.  Herbin et al).  If time permits, I will also discuss Discrete Duality Finite Volume methods for solving elliptic PDEs on surfaces.

To do local adaption and time subcycling in regions requiring high spatial resolution, we are developing ForestClaw, a hybrid adaptive mesh refinement (AMR) code in which non-overlapping fixed-size Cartesian grids are stored as leaves in a forest of quad- or oct-trees.  The tree-based code p4est (C. Burstedde) manages the multi-block connectivity and is highly scalable in realistic
applications.

I will present results from reaction-diffusion systems on surface meshes, and test problems from the atmospheric sciences community.'
slides: 'oxford-2012.pdf'
date: 2012-11-29
date_talk: Nov 29, 2012
venue: 'Mathematical Institute'
organization: 'University of Oxford'
location: Oxford, England
authors: Donna Calhoun, Carsten Burstedde
---
