---
title: 'Patch-based AMR algorithms'
collection: talks
type: Workshop lecture
talk_type: Workshop lecture
permalink: /talks/kaust-2012.html
abstract: 'When solving elliptic problems using a finite volume scheme on a patch-based grid hierarchy of adaptively refined meshes, the question of how to preserve numerical conservation naturally arises. One way that researchers have used to maintain conservation at coarse/fine boundaries is to introduce a conservative &quot;fix-up&quot; at these boundaries between coarse and fine refinement patches.  For explicit time stepping schemes, these fix-ups can be applied once, after the time step.  But for implicit schemes, the quantity needed to ensure conservation comes out of a coupled solution process, and cannot be computed explicitly. But for at least two decades, researchers actively in involved in AMR development have done the &quot;fix-up&quot;, even for elliptic equations, as a sort of post-processing step, or have taken at most one step of what can be viewed as an iterative scheme. This approach has always worked extremely well, but there has never been any formal justification as to why it works. In this talk, I will present this conservation issue and explain why a one-step approach works as well as it does.  The scheme I will discuss is a second order, finite-volume discretization of constant coefficient elliptic problem on uniform Cartesian meshes.  I will also mention briefly other methods which rely on a full iterative procedure for accuracy and conservation.'
slides: 'kaust-2012.pdf'
poster: 'amr-wg-2012.pdf'
date: 2012-02-05
date_talk: Feb 05, 2012
date_conference: 'Feb 04 - Feb 08, 2012'
venue: '[HPC]^3 Workshop 2012'
organization: 'King Abdullah University of Science and Technology'
conference_url: 'https://numerics.kaust.edu.sa/hpc3/hpc3-2012.html'
location: Kaust, Saudi Arabia
authors: Donna Calhoun
---
