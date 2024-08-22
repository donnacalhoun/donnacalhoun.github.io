---
title: 'Implementation of coupled simulations in the ForestClaw Library'
collection: talks
type: Mini-symposium speaker
talk_type: Mini-symposium speaker
permalink: /talks/siam-cse-2023.html
abstract: 'We present an implementation of the coupling of two distinct adaptive simulations, run on a separate hierarchy of adaptive Cartesian meshes within the ForestClaw library. Both simulations have their own set of options, and own meshes derived from p4est quadtree/octree meshes, and solver characteristics. Through coupling, however, both can be run in the same executable. This work goes beyond the typical coupling of hyperbolic solvers with elliptic and/or parabolic solvers in that each simulation may involve its own operator split approach and runs on its own mesh. The target codes are solvers MAGICForest (Model for Acoustic Gravity wave Interactions and Coupling, J. Snively Embry-Riddle Aeronautic Univ. (ERAU)) with the ionosphere code TreesGEMINI (Geospace Environment Model of Ion-Neutral Interactions, M. Zettergren, ERAU). MAGICForest currently runs within the ForestClaw environment, and progress is being made to extend ForestClaw with the GEMINI solvers. We will report on the progress towards full coupling of these two solvers, and underlying challenges that must be overcome to allow multiple simulations to run and communicate through a single executable.'
slides: 'cse-2023.pdf'
date: 2023-03-02
date_talk: Mar 02, 2023
date_conference: 'Feb 27 - Mar 03, 2023'
venue: 'SIAM Computational Science and Engineering Conference'
organization: 'Society for Industrial and Applied Mathematics'
conference_url: 'https://www.siam.org/conferences-events/past-event-archive/cse23/'
location: Amsterdam, Netherlands
authors: Donna Calhoun, Scott Aiton, Carsten Burstedde
---
