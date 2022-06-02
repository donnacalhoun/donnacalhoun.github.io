---
title: 'A logically Cartesian, adaptively refined two-patch sphere grid for modeling transport in the atmosphere'
collection: talks
type: Workshop lecture
talk_type: Workshop lecture
permalink: /talks/pdes-sphere-2012.html
abstract: 'A logically Cartesian, adaptively refined two-patch sphere grid for
modeling transport in the atmosphere

Recently, we demonstrated results using a second order finite volume scheme on a novel, logically Cartesian, two-patch 2d sphere grid. The numerical scheme, based on the wave-propagation algorithms in Clawpack ( R. J. LeVeque, Univ. of Washington), was easily adapted to the single grid Cartesian layout of our two-patch sphere grid mapping.  Furthermore, we were able to use an existing adaptive mesh refinement patch-based (AMR) code (Berger, Oliger et al.) to run computational efficient simulations.

In our current work, we are developing a new AMR code which uses wave propagation algorithms on non-overlapping AMR grids stored as leaves in a forest of quad- or oct-trees.  The underlying tree-based code, p4est (Carsten Burstedde, Univ. of Bonn) manages the multi-block connectivity in a multi-processor environment and has been shown to be highly scalable in applications of interest to geophysicists.  This new AMR code, which we call ForestClaw, will easily handle the adaptivity for our two-patch sphere grid, as well as the cubed-sphere, and more generally, any multi-block geometry.

We will present preliminary results from our efforts to use ForestClaw for modeling volcanic ash dispersal in the atmosphere.  This is joint work with Carsten Burstedde (Univ. of Bonn) and researchers at the Cascade Volcanic Observatory (Vancouver, Washington).'
slides: 'pdes-sphere-2012.pdf'
date: 2012-09-25
date_talk: Sep 25, 2012
date_conference: 'Sep 24 - Sep 28, 2013'
venue: 'PDEs on the Sphere'
organization: 'Isaac Newton Institute, Cambridge University, England'
conference_url: 'https://www.newton.ac.uk/event/ammw02/'
location: Cambridge, England
authors: Donna Calhoun, Carsten Burstedde
---
