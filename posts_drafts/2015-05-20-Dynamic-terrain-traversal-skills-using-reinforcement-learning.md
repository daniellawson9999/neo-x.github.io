---
title: Dynamic terrain traversal skills using reinforcement learning
date: 2016-5-14 10:20
modified: Sunday, 21. May 2016 02:06PM 
category: Publication
Tags: News, RL, CharacterAnimation
author: Glen Berseth
authors: Xue Bin Peng, Glen Berseth, Michiel van de Panne
cover: <div> <img width="100%" src="/assets/projects/dynamicTerrainTraversal/teaser.png"/> </div>
summary: The locomotion skills developed for physics-based characters most often target flat terrain. However, much of their potential lies with the creation of dynamic, momentum-based motions across more complex terrains. In this paper, we learn controllers that allow simulated characters to traverse terrains with gaps, steps, and walls using highly dynamic gaits. This is achieved using reinforcement learning, with careful attention given to the action representation, non-parametric approximation of both the value function and the policy; epsilon-greedy exploration; and the learning of a good state distance metric. The methods enable a 21-link planar dog and a 7-link planar biped to navigate challenging sequences of terrain using bounding and running gaits. We evaluate the impact of the key features of our skill learning pipeline on the resulting performance. 
Type: Planning
TitleShort: Physical navigation using RL
---

<div> <img width="100%" src="/assets/projects/dynamicTerrainTraversal/teaser.png"/> </div>

# Abstract

The locomotion skills developed for physics-based characters most often target flat terrain. However, much of their potential lies with the creation of dynamic, momentum-based motions across more complex terrains. In this paper, we learn controllers that allow simulated characters to traverse terrains with gaps, steps, and walls using highly dynamic gaits. This is achieved using reinforcement learning, with careful attention given to the action representation, non-parametric approximation of both the value function and the policy; epsilon-greedy exploration; and the learning of a good state distance metric. The methods enable a 21-link planar dog and a 7-link planar biped to navigate challenging sequences of terrain using bounding and running gaits. We evaluate the impact of the key features of our skill learning pipeline on the resulting performance. 

## Files

[Paper](/assets/projects/dynamicTerrainTraversal/2015-TOG-deepRL.pdf)

### Bibtex

```
@article{2015-TOG-terrainRL,
 author = {Peng, Xue Bin and Berseth, Glen and van de Panne, Michiel},
 title = {Dynamic Terrain Traversal Skills Using Reinforcement Learning},
 journal = {ACM Trans. Graph.},
 issue_date = {August 2015},
 volume = {34},
 number = {4},
 month = jul,
 year = {2015},
 issn = {0730-0301},
 pages = {80:1--80:11},
 articleno = {80},
 numpages = {11},
 url = {http://doi.acm.org/10.1145/2766910},
 doi = {10.1145/2766910},
 acmid = {2766910},
 publisher = {ACM}
} 
```

## Videos!

<br/>
								<iframe width="560" height="315" src="https://www.youtube.com/embed/mazfn4dHPRM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
								<br><br>
								<iframe width="560" height="315" src="https://www.youtube.com/embed/RTuSHI5FNzg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

