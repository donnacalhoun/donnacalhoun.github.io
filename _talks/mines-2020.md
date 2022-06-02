---
title: 'A fully unsplit wave propagation algorithm for shallow water flows on GPUs'
collection: talks
type: Invited
talk_type: Invited
permalink: /talks/mines-2020.html
abstract: 'The focus of this talk is on a GPU implementation of the fully multi-dimensional patch solver based on the wave propagation algorithm (R. J. LeVeque, Clawpack).  Our CUDA implementation is designed for use on small, fixed size patches (32x32) used in a larger the block-based adaptive code ForestClaw (D. Calhoun and C. Burstedde).  To update patches on the GPU, we batch-process O(1000) patches per kernel call.  Each patch is assigned a single CUDA thread block, eliminating the need for syncing between blocks.  By redesigning the WPA, we are able to completely update the solution on each patch in a single batch kernel call. To avoid branch divergence, special attention is given to the implementation of wave limiters.  Resulting time using the GPU is about 5-7x speedup over a single CPU.  We will demonstrate our algorithm using examples from the shallow water wave equations implemented in ForestClaw.'
slides: 'mines-2020.pdf'
date: 2020-02-21
date_talk: Feb 21, 2020
venue: 'Dept. of Mathematics'
organization: 'Colorado School of Mines'
location: Golden, CO (USA)
authors: Donna Calhoun
---
