---
title: 'ForestClaw: Hybrid forest-of-octrees AMR for hyperbolic conservation laws'
collection: publications
publish_type: journal-article
permalink: /publication/journal-article/bu-ca-ma-te-2014.html
abstract: 'We present a new hybrid paradigm for parallel adaptive mesh refinement (AMR) that combines the scalability and lightweight architecture of tree-based AMR with the computational efficiency of patch-based solvers for hyperbolic conservation laws. The key idea is to interpret each leaf of the AMR hierarchy as one uniform compute patch in {R^d} with {m^d} degrees of freedom, where m is customarily between 8 and 32. Thus, computation on each patch can be optimized for speed, while we inherit the flexibility of adaptive meshes. In our work we choose to integrate with the p4est AMR library since it allows us to compose the mesh from multiple mapped octrees and enables the cubed sphere and other nontrivial multi- block geometries. We describe aspects of the parallel implementation and close with scalings for both MPI-only and OpenMP/MPI hybrid runs, where the largest MPI run executes on 16,384 CPU cores.'
date: 01/01/2014
venue: 'Parallel Computing : Accelerating Computational Science and Engineering (CSE)'
paperurl: 'https://arxiv.org/abs/1308.1472'
citation: 'Carsten Burstedde, Donna Calhoun, Kyle Mandli, Andy Terrel, "ForestClaw: Hybrid forest-of-octrees AMR for hyperbolic conservation laws", <i>Parallel Computing : Accelerating Computational Science and Engineering (CSE)</i>, 2014.'
download: bu-ca-ma-te-2014.pdf
---
