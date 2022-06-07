---
layout: post
title:  "Conjinctive coding in the parahippocampal networks"
date:   2021-11-03 
categories: updates
excerpt_separator: <!--end_excerpt-->
---
In our latest preprint with Alessandro Treves and Charlotte Boccara we looked at how cells in the Medial Enthorinal Cortex, Presubiculum and Parasubiculum of rats respond to the movement of the head of the animal (you can find paper [here](2021-09-14-Continuous-attractors-for-dynamic-memories.markdown)).

We found a population of cells that modulate their firing in response to the angular velocity with which the head is rotating. This population is distributed with similar proportion in all three regions, and in all the layers we looked into (with the notable exception of MEC LII).

An interesting fact came up when we looked at how this population relates to cells coding for other properties such as the running speed, the animal position, the direction of the head and the intensity of [Theta rythm oscilaltions](https://en.wikipedia.org/wiki/Theta_wave) of the local field potential (LFP): many of these properties are coded conjunctively by the cells, without any evident structure in how these conjunctions are distributed.

In particular, we did not find any correlation between the score quantifying the effect sizes of the different modulation, and the intersection between the different populations were compatible with the hypothesis that each feature was assigned randomly to a subset of cells in these regions.

To vizualize this unruly conjunctiveness, I have built an interactive dashboard, check it out [here](https://mixsel.herokuapp.com/)!  
No clear clusters can be seen in any of the subspace of coding scores; rather, coding strength organizes on a multivariate continuous distribution, in which different subclasses can be identified more for convenience than anything else.

What are the computational implications of this lack of strucutre?  
This is an intriguing direction we are pursuing at the moment. Stay tuned for more!




