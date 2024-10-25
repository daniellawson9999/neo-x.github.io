---
title: Terrain Adaptive Locomotion Skills using Deep Reinforcement Learning
date: 2016-5-14 10:20
modified: Sunday, 21. May 2016 02:06PM 
category: Publication
Tags: News, RL, CharacterAnimation
author: Glen Berseth
authors: Xue Bin Peng, Glen Berseth, Michiel van de Panne
cover: <div> <img width="60%" src="/assets/projects/deeprl/dog_teaser.png"/> <img width="30%" src="/assets/projects/deeprl/goat_teaser.png"/> </div>
summary: Reinforcement learning offers a promising methodology for developing skills for simulated characters, but typically requires working with sparse hand-crafted features. Building on recent progress in deep reinforcement learning (DeepRL), we introduce a mixture of actor-critic experts (MACE) approach that learns terrain-adaptive dynamic locomotion skills using high-dimensional state and terrain descriptions as input, and parameterized leaps or steps as output actions. MACE learns more quickly than a single actor-critic approach and results in actor-critic experts that exhibit specialization. Additional elements of our solution that contribute towards efficient learning include Boltzmann exploration and the use of initial actor biases to encourage specialization. Results are demonstrated for multiple planar characters and terrain classes.
Type: Hierarchical Reinforcement Learning
TitleShort: Terrain navigation using DeepRL
---

<table width="100%">
	<tr width="100%">
		<td width="55%" align="center">
		<img width="100%" src="/assets/projects/deeprl/dog_teaser.png"/>
		</td>
		
		<td width="35%" align="center">
		<img width="230" src="/assets/projects/deeprl/goat_teaser.png"/>
		</td>
	</tr>
</table>	

# Abstract

Reinforcement learning offers a promising methodology for developing skills for simulated characters, but typically requires working with sparse hand-crafted features. Building on recent progress in deep reinforcement learning (DeepRL), we introduce a mixture of actor-critic experts (MACE) approach that learns terrain-adaptive dynamic locomotion skills using high-dimensional state and terrain descriptions as input, and parameterized leaps or steps as output actions. MACE learns more quickly than a single actor-critic approach and results in actor-critic experts that exhibit specialization. Additional elements of our solution that contribute towards efficient learning include Boltzmann exploration and the use of initial actor biases to encourage specialization. Results are demonstrated for multiple planar characters and terrain classes.

## Files

[Paper](/assets/projects/deeprl/2016-TOG-deepRL.pdf)

### Bibtex

```
@article{2016-TOG-deepRL,
  title={Terrain-Adaptive Locomotion Skills Using Deep Reinforcement Learning},
  author={Xue Bin Peng and Glen Berseth and Michiel van de Panne},
  journal = {ACM Transactions on Graphics (Proc. SIGGRAPH 2016)},
  volume = 35,
  number = 5,
  note = {to appear},
  year={2016}
}
```

## Videos!

<br/>
								<iframe width="560" height="315" src="https://www.youtube.com/embed/KPfzRSBzNX4" frameborder="0" allowfullscreen></iframe>
								<br><br>
								<iframe width="560" height="315" src="https://www.youtube.com/embed/A0BmHoujP9k" frameborder="0" allowfullscreen></iframe>

