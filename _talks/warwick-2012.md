---
title: 'A logically Cartesian, adaptively refined two-patch sphere grid for modeling transport in the atmosphere'
collection: talks
type: Invited
talk_type: Invited
permalink: /talks/warwick-2012.html
abstract: 'Recently, we developed a novel, logically Cartesian sphere grid particularly well suited for explicit finite volume schemes.  We demonstrated that schemes such as the wave propagation algorithm (R. J. LeVeque, Univ. of Washington) for solving hyperbolic PDEs and a diamond-cell type method (Calhoun, C. Helzel, Univ. of Bochum) for parabolic equations leads to numerically accurate results on our sphere grid.

In our current work, we are developing a new adaptive mesh refinement (AMR) code which uses wave propagation algorithms on non-overlapping AMR grids stored as leaves in a forest of quad- or oct-trees.  The underlying tree-based code, p4est (Carsten Burstedde, Univ. of Bonn) manages the multi-block connectivity in a multi-processor environment and has been shown to be highly scalable in realistic applications. This hybrid AMR code, which we call ForestClaw, will easily handle the adaptivity for our two-patch sphere grid, as well as the cubed-sphere, and more generally, any multi-block geometry.

I will discuss features of our finite volumes schemes that make them work well on general surface meshes, as well as present a few of the drawbacks.  Currently, our target application is volcanic ash dispersion in the atmosphere.  We will present work in progress on our joint efforts with researchers at the Cascade Volcanic Observatory (Vancouver, Washington, USA).'
slides: 'warwick-2012.pdf'
date: 2012-11-16
date_talk: Nov 16, 2012
venue: 'Applied Math Seminar'
organization: 'University of Warwick'
location: Conventry, UK
authors: Donna Calhoun, Carsten Burstedde
---
