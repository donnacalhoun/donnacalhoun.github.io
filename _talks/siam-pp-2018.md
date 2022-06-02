---
title: 'Volcanic ash transport using
parallel, adaptive Ash3d'
collection: talks
type: Mini-symposium speaker
talk_type: Mini-symposium speaker
permalink: /talks/siam-pp-2018.html
abstract: 'As the eruption of Eyjafjallajokull in Iceland in 2010 demonstrated, &quot;zero ash tolerance&quot; policies imposed on civil aviation can lead to significant disruption for travelers and loss of revenue for airlines.  To mitigate the hazards associated with  volcanic eruptions, numerical volcanic ash transport and dispersal models are routinely used to forecast ash concentration loads in the atmosphere.   However, delivering  high fidelity predictions within operational time frames, especially for long-lasting eruptions that spread ash over  wide areas with dense air traffic,  places severe demands on computational resources.

Ash3d, developed by the USGS, is one of several volcanic ash transport models in operational use.  Available through a web-based portal, Ash3d solves a set of advection-diffusion-deposition equations to transport one or more classes of ash particles on a regional latitude/longitude grid.  Current meteorological data is used to define wind fields for the transport equations and second order finite volume schemes are used to update the evolving ash plume.

To improve the efficiency of the single grid, serial Ash3d code, we have ported Ash3d to our parallel, adaptive software library ForestClaw.  We present results showing the scalability of the Ash3d extension of ForestClaw and discuss issues related to porting legacy codes to modern parallel, adaptive frameworks. Results will include tests to simulate the eruption of Mt. St. Helen&apos;s and the Icelandic volcano Eyja.'
slides: 'siam-pp-2018.pdf'
date: 2018-03-10
date_talk: Mar 10, 2018
date_conference: 'Mar 07 - Mar 10, 2018'
venue: 'SIAM Parallel Processing Conference'
organization: 'Society for Industrial and Applied Mathematics'
conference_url: 'https://archive.siam.org/meetings/pp18/?_ga=2.127230925.1322043160.1506199199-2012472258.1506199199'
location: Tokyo, Japan
authors: Donna Calhoun, Melody Shih
---
