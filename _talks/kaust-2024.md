---
title: 'Tree-based Adaptive Mesh Refinement, GPUs (and Turbulence)'
collection: talks
type: Invited
talk_type: Invited
permalink: /talks/kaust-2024.html
abstract: 'We describe an approach to adaptive mesh refinement that is well-suited for implementations on GPUs.   We fill the leaves of a quadtree or octree mesh with logically Cartesian grids of a fixed, uniform size. These grids are easily distributed to the GPU in large batches of O(1000) patches per kernel call.  The GPU then updates the solution on each patch independently.  The resulting speed-up for a second order Godunov solver is about 5-7x speedup over a single CPU core.  We will demonstrate our algorithm on several nonlinear hyperbolic problems illustrating the benefits of parallel performance and dynamic mesh adaptivity coupled with GPUs.  Our GPU code is implemented in the code ForestClaw (D. Calhoun and C. Burstedde), a PDE layer built on top of the mesh management library p4est (C. Burstedde, Univ. of Bonn). '
slides: 'kaust-2024.pdf'
date: 2024-02-27
date_talk: Feb 27, 2024
date_conference: 'Feb 26 - Feb 28, 2024'
venue: 'KAUST Turbulence Workshop'
organization: 'KAUST'
conference_url: 'https://turbulenceworkshop.kaust.edu.sa/'
location: Thuwal, Saudi Arabia
authors: Donna Calhoun
---
