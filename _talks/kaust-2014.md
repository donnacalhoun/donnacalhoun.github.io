---
title: 'ForestClaw : AMR for a mapped, quadtree hierarchy'
collection: talks
type: Workshop lecture
talk_type: Workshop lecture
permalink: /talks/kaust-2014.html
abstract: 'I will describe our progress on developing ForestClaw, a adaptive mesh refinement framework for solving PDEs on an quadtree hierarchy of fixed size grids.  The underlying algorithms are essentially those first described by Berger and Oliger, over 30 years ago, and now used in Chombo, Boxlib, AMRClaw and other popular AMR software projects. The main difference between ForestClaw and these other projects is the use of a fixed quadtree hierarchy, managed by a separate grid management library. This hierarchy in ForestClaw is managed by p4est (Carsten Burstedde, Univ. of Bonn), a highly scalable, dynamic grid management library for managing a forest-of-octrees.  Current focus of ForestClaw development has been on mapped, multiblock domains, including the cubed sphere, and a five-patch disk.  I will talk about several ideas that have allowed for flexible use of grid mappings, including &apos;mapping contexts&apos;, and index transformations needed for multiblock domains. Solvers for ForestClaw include the wave propagation algorithms in Clawpack.'
slides: 'kaust-2014.pdf'
date: 2014-11-09
date_talk: Nov 09, 2014
date_conference: 'Nov 08 - Nov 13, 2014'
venue: '[HPC]^3 Workshop 2014'
organization: 'King Abdullah University of Science and Technology'
conference_url: 'https://numerics.kaust.edu.sa/hpc3-2014/'
location: KAUST, Saudi Arabia
authors: Donna Calhoun, Carsten Burstedde
---
