---
title: 'Adaptively refined tree-based solver for the Serre-Green-Naghdi equations'
collection: talks
type: Mini-symposium speaker
talk_type: Mini-symposium speaker
permalink: /talks/siam-cse-2021.html
abstract: 'We describe our progress in developing a Serre-Green-Naghdi (SGN) solver for the parallel, adaptive library ForestClaw.  The SGN equations are based on higher order asymptotic expansions of the solutions to surface flow based on potential theory.  The zeroth order terms in the asymptotic solution lead to the familiar depth-averaged flow governed by the shallow water wave equations (SWE). The first order expansions introduce corrections that model the dispersive behavior in the flow.  In our implementation of the SGN, we use an operator split approach in which one step of the SWE  using the wave propagation algorithm (www.clawpack.org), followed by an variable coefficient elliptic solve for the correction terms.  Our parallel, elliptic solver (ThunderEgg, S. Aiton, BSU) is based on BICGStab, with a patch-based multi-grid smoother. We will present performance results for the solver, as well as results for the SGN equations. '
slides: 'siam-cse-2021.pdf'
date: 2021-03-04
date_talk: Mar 04, 2021
date_conference: 'Mar 01 - Mar 05, 2021'
venue: 'SIAM Computational and Engineering Conference'
organization: 'Society for Industrial and Applied Mathematics'
conference_url: 'https://www.siam.org/conferences/cm/conference/cse21'
location: Fort Worth, TX (USA) (virtual)
authors: Donna Calhoun
---
