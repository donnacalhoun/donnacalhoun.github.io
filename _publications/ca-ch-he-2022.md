---
title: 'The Cartesian Grid Active Flux Method with Adaptive Mesh Refinement'
collection: publications
publish_type: journal-article
permalink: /publication/journal-article/ca-ch-he-2022.html
abstract: 'We present the first implementation of the Active Flux method on adaptively refined Cartesian grids. The Active Flux method is a third order accurate finite volume method for hyperbolic conservation laws, which is based on the use of point values as well as cell average values of the conserved quantities. The resulting method has a compact stencil in space and time and good stability properties. The method is implemented as a new solver in ForestClaw, a software for parallel adaptive mesh refinement of patch-based solvers. On each Cartesian grid patch the single grid Active Flux method can be applied. The exchange of data between grid patches is organised via ghost cells. The local stencil in space and time and the availability of the point values that are used for the reconstruction, leads to an efficient implementation. The resulting method is third order accurate, conservative and allows the use of subcycling in time.'
date: 01/01/2022
venue: 'https://arxiv.org/abs/2205.07572'
paperurl: 'https://arxiv.org/abs/2205.07572'
citation: 'Donna Calhoun, Erik Chudzik, Christiane Helzel, "The Cartesian Grid Active Flux Method with Adaptive Mesh Refinement", <i>https://arxiv.org/abs/2205.07572</i>, 2022.'
images: 'BurgersLimSmooth_tikz0010.pdf'
caption: 'Solution to Burgers equation using third order Active Flux method'
download: ca-ch-he-2022.pdf
---
