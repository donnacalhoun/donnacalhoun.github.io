---
title: 'Dispersive terms in the shallow water
wave equations'
collection: talks
type: Workshop lecture
talk_type: Workshop lecture
permalink: /talks/banff-2019.html
abstract: 'The depth-averaged shallow water wave equations are commonly used to model flows arising from natural hazards.  The GeoClaw code, developed by D. George,  R. J. LeVeque, M. J. Berger, K. Mandli and others is one example of a depth-averaged flow solver  now widely used for modeling tsunamis, overland flooding, debris flows, storm surges and so on.  Generally, depth averaged flow models show excellent large scale agreement with observations and can thus be reliably used to predict whether tsunamis will reach distant coast lines, and if, so can give vital information about arrival times.  However, for other types of flows, dispersive effects missing from the SWE model can play an important role in determining localized effects such as whether waves will overtop seawalls, or whether a landslide entering a lake will trigger tsunami-like behavior on the opposite shore.  Because of the importance of these dispersive effects, several depth averaged codes include dispersive corrections to the SWE.  One set of equations commonly used to model these dispersive effects are the Serre-Green-Naghdi (SGN)equations.  

We will present our work to include dispersive correction terms into the GeoClaw extension of ForestClaw, a parallel adaptive library for Cartesian grid methods.  One formulation of the SGN equations stabilizes higher order derivatives by treating them implicitly.  As a result, a key component of an SGN solver is a variable coefficient Poisson solver. We will discuss our current work in deveoping both an iterative solver, based on multi-grid preconditioned BiCG-STAB solver (Scott Aiton, Boise State), and a direct solver based on the Hierarchical-Poincaré-Steklov (HPS) method developed by  Gillman and Martinsson (2014).  We will describe the SGN equations and provide an overview of their derivation, and then show preliminary results on uniform Cartesian meshes.  Comparisons with the SGN solver in Basilisk (S. Popinet) and BoussClaw (J. Kim et al) will also be shown to verify our model. '
slides: 'banff-2019.pdf'
video: 'https://www.birs.ca/events/2019/5-day-workshops/19w5189/videos/watch/201905150939-Calhoun.html'
date: 2019-05-15
date_talk: May 15, 2019
date_conference: 'May 12 - May 17, 2019'
venue: 'Women in Numerical PDEs and their Applications'
organization: 'Banff International Research Station'
conference_url: 'https://www.birs.ca/events/2019/5-day-workshops/19w5189'
location: Banff, Canada
authors: Donna Calhoun
---
