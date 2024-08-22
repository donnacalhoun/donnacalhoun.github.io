---
title: 'ForestClaw : A parallel library for solving PDEs on an adaptive hierarchy of logically Cartesian meshes '
collection: talks
type: Invited
talk_type: Invited
permalink: /talks/uppsala-2023.html
abstract: 'I will describe the software package ForestClaw, a PDE solver for time dependent PDEs based on updating a solution on an adaptive hierarchy of logically Cartesian meshes. The adaptive hierarchy is based the mesh generation library p4est (C. Burstedde, L. Wilcox and T. Isaac) for parallel dynamically adaptive mesh refinement (AMR) on a forest of octrees.   ForestClaw is a PDE layer for p4est that provides time stepping, spatial discretizations, tagging criteria for refinement and all data transfer between neighboring grids and old and new meshes.  I will describe the components of ForestClaw, the basic algorithms used to update the solution on a dynamically evolving quadtree mesh, and related issues of accuracy and stability of the AMR solution.  I&apos;ll describe several projects that are currently using ForestClaw, including solver strategies for elliptic problems.  Recent results from a DARPA funded project to detected natural hazards (tsunamis, earthquakes, storms, volcanic eruptions) will also be discussed. '
slides: 'uppsala-2023.pdf'
date: 2023-02-22
date_talk: Feb 22, 2023
venue: 'Research Seminar, Dept, of Information Technology'
organization: 'Uppsala University'
location: Uppsala, Sweden
authors: Donna Calhoun
---
