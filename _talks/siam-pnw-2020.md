---
title: 'Solving the Serre-Green-Naghdi equations on adaptively refined quadtree meshes'
collection: talks
type: Keynote
talk_type: Keynote
permalink: /talks/siam-pnw-2020.html
abstract: 'The depth-averaged shallow water wave equations are commonly used to model tsunamis, overland flooding, debris flows, storm surges and so on.  Generally, depth averaged flow models show excellent large scale agreement with observations and can thus be reliably used to predict whether tsunamis will reach distant coast lines, and can provide vital information about arrival times.  However, for other types of flows, dispersive effects missing from the SWE model can play an important role in predicting whether waves will overtop seawalls, or whether a landslide entering a lake will trigger tsunami-like behavior on the opposite shore.  To model these dispersive affects, several models include dispersive corrections to the SWE.  One such model is the Serre-Green-Naghdi equations.  
 We will present our work on solving the Serre-Green-Naghdi (SGN) equations on adaptively refined Cartesian meshes.  A common approach to treating the higher order derivatives that appear in the SGN equations is to treat these terms implicitly, resulting in an elliptic-like operator for the dispersive terms. As a result, a key component of an SGN solver is a variable coefficient elliptic solver. We will discuss our current work in developing an elliptic solver for adaptively refined meshes generated by ForestClaw (www.forestclaw.org).  The solver is based on multi-grid preconditioned BiCG-STAB and implemented in the code ThunderEgg (Scott Aiton, Boise State University).  A key feature of the ThunderEgg solver is that it can take advantage of fast solvers, when available, to solve local elliptic problems on the Cartesian patches in the adaptive mesh hierarchy.  We will show results using the solver for challenging benchmark problems, as well as preliminary results on solving the model SGN equations on adaptive meshes.'
slides: 'siam-pnw-2020.pdf'
video: 'https://www.youtube.com/watch?v=MglKXgPHXLo&list=PLAENrdU3Q0mKVGgCDlx0zYG9RhqzOtqG2&index=3'
date: 2020-10-17
date_talk: Oct 17, 2020
venue: 'Pacific Northwest Numerical Analysis Seminar'
organization: 'PNWNAS'
conference_url: 'https://sites.google.com/view/pnwnas2020/'
location: Pacific Northwest Cloud Meeting (virtual)
authors: Donna Calhoun
---