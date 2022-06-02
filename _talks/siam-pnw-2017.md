---
title: 'Volcanic ash transport using
parallel, adaptive Ash3d'
collection: talks
type: Mini-symposium speaker
talk_type: Mini-symposium speaker
permalink: /talks/siam-pnw-2017.html
abstract: 'As the eruption of Eyjafjallajokull in Iceland in 2010 demonstrated, &quot;zero ash tolerance&quot; policies imposed on civil aviation can lead to significant disruption for travelers and loss of revenue for airlines.  To mitigate the hazards associated with  volcanic eruptions, numerical volcanic ash transport and dispersal models are routinely used to forecast ash concentration loads in the atmosphere.   However, delivering  high fidelity predictions within operational time frames, especially for long-lasting eruptions that spread ash over  wide areas with dense air traffic,  places severe demands on 
computational resources.

Ash3d [1], developed at the Cascade Volcanic Observatory (Vancouver, WA) is one of  several volcanic ash transport models in operational use.  Available through a web-based  portal, Ash3d solves a set of advection-diffusion-deposition equations to transport one  or more classes of ash particles on a regional latitude/longitude grid.  Current  meteorological data is used to define wind fields for the transport equations and second  order finite  volume schemes are used to update the evolving ash plume.   

To improve the efficiency of the single grid, serial Ash3d code, we have ported Ash3d to our parallel, adaptive software library ForestClaw [2].   In this approach,  fine level grids  in a quadtree hierarchy are placed in areas with the highest ash concentration. The solution on each patch is updated using the single grid routines from Ash3d, and the grid hierarchy is updated every few time steps to track the evolving ash cloud.  

We present results showing the scalability of the Ash3d extension of ForestClaw and discuss issues related to porting legacy codes to modern parallel, adaptive frameworks. Results will include tests to simulate the eruption of Mt. St. Helen&apos;s and the Icelandic volcano Eyja.  We will also discuss our approach to ensuring conservation on  the adaptive grids and our on-going efforts to extend the Ash3d code to ForestClaw&apos;s   cubed sphere grid.'
slides: 'siam-pnw-2017.pdf'
date: 2017-10-28
date_talk: Oct 28, 2017
date_conference: 'Oct 27 - Oct 29, 2017'
venue: '1st Biennial Meeting of the SIAM Pacific Northwest Section'
organization: 'Society for Industrial and Applied Mathematics'
conference_url: 'https://sites.google.com/view/siampnw17/home'
location: Corvallis, OR (USA)
authors: Donna Calhoun, Yu-Hsuan Shih, Roger Denlinger, Larry Mastin, Hans Schwaiger
---
