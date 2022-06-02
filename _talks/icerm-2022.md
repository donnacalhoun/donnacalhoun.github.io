---
title: 'Challenges in coupling codes in large scale PDE solvers'
collection: talks
type: Invited
talk_type: Invited
permalink: /talks/icerm-2022.html
abstract: 'We discuss time stepping challenges in large scale PDE solvers built within an adaptive meshing framework.  Adaptive meshing is a software strategy for dynamically managing mesh resolution so that spatial and temporal solution features of interest (typically defined by the user) are computed at the highest levels of resolution. By dynamically managing computational resources, solver performance can be dramatically increased.  Most commonly, only the spatial resolution is dynamically managed.  In this case, a standard &quot;method of lines&quot; approach can be used to advance the solution, with possible time step restrictions based on the highest spatial resolution.  Less common is the use of &quot;local time stepping&quot;, a strategy in which the time step size is locally adjusted to maintain, for example, a constant CFL number across the domain. Local time stepping works well for purely hyperbolic problems, and in fact is implemented in many Cartesian grid codes.  What is not entirely clearly is how to manage local time stepping with multi-stage time stepping schemes or operator split approaches for systems of PDEs, especially if the system involves elliptic terms. 

I will discuss these issues in the context of ForestClaw software (www.forestclaw.org), a Cartesian grid based software platform for solving PDEs on a hierarchy of adaptively refined Cartesian meshes.  We will show progress on several projects, including a DARPA funded project involving remote sensing in the atmosphere.  This project will couple several complex codes through the ForestClaw platform. The coupling will occur through interpolation between different ForestClaw mesh hierarchies, as well as through operator splitting involving elliptic, parabolic and hyperbolic terms.  Time stepping must be commensurate with the accuracy of each individual code, while balancing communication costs.  
'
slides: 'icerm-2022.pdf'
date: 2022-01-12
date_talk: Jan 12, 2022
date_conference: 'Jan 10 - Jan 14, 2022'
venue: 'Holistic Design of Time Dependent PDE Discretization'
organization: 'Institute for Computational and Experimental Research in Mathematics (ICERM)'
conference_url: 'https://icerm.brown.edu/topical_workshops/tw-22-hdtd/'
location: Providence, RI (USA)
authors: Donna Calhoun, Jonathan Snively
---
