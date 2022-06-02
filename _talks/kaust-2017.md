---
title: 'ForestClaw/Geo : Modeling dam-break
flooding using scalable, adaptive quad
trees'
collection: talks
type: Workshop lecture
talk_type: Workshop lecture
permalink: /talks/kaust-2017.html
abstract: 'We demonstrate our success in incorporating GeoClaw (LeVeque, George, Berger, Mandli), a widely used code for simulation of tsunamis, debris flow, flooding, storm surges and so on, into ForestClaw, an adaptive quadtree code based on the highly scalable library p4est (C. Burstedde, Univ. Bonn).  This new adaptive mesh framework  uses the patch-based algorithms first developed by Berger, Colella, LeVeque and others and extends them to a non-overlapping hierarchy of grids occupying the leaves of a quadtree mesh.  The ForestClaw framework brings parallel compute power to the GeoClaw code (previously parallelized using OpenMP) and allows us to run GeoClaw simulations on large scale parallel computing environments.  We show results from simulations of the 1976 Teton Dam failure in eastern Idaho, and show that we can achieve excellent agreement with historical data such as arrival times and flooding boundaries.  

If time permits, we will also discuss our experience in incorporating legacy Cartesian single grid/serial codes into modern adaptive frameworks.  In particular, we discuss some of the pitfalls in porting codes which rely heavily on modern Fortran (F90) constructs such as modules.  In this part of the talk, we will discuss our recent work porting Ash3d, a serial, single grid code developed by the USGS Cascade Volcanic Observatory (Vancouver, WA) for simulating volcanic ash dispersion, to ForestClaw.'
slides: 'kaust-2017.pdf'
date: 2017-05-23
date_talk: May 23, 2017
date_conference: 'May 22 - May 24, 2017'
venue: 'KAUST workshop on predictive complex computational fluid dynamics'
organization: 'King Abdullah University of Science and Technology'
conference_url: 'https://pccfd.kaust.edu.sa/home'
location: KAUST, Saudi Arabia
authors: Donna Calhoun
---
