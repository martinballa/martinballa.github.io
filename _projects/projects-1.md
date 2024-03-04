---
title: "Tabletop games"
excerpt: "Short description of projects item number 1<br/><img src='/files/tag.png'>"
collection: projects
---

### Research
I worked on applying Deep Reinforcement Learning to evaluate generalisation on various GVGAI games. I am currenlty working with gridworld environments with improving generalisation in mind. I train goal-conditioned policies on randomly generated gridworld levels and then benchmark the policies on unseen levels.


### Tabletop Games Framework (TAG)
The Tabletop Games Framework (TAG) is a Java-based benchmark for developing modern board games for AI research. TAG provides a common skeleton for implementing tabletop games based on a common API for AI agents, a set of components and classes to easily add new games and an import module for defining data in JSON format. At present, this platform includes the implementation of seven different tabletop games that can also be used as an example for further developments. Additionally, TAG also incorporates logging functionality that allows the user to perform a detailed analysis of the game, in terms of action space, branching factor, hidden information, and other measures of interest for Game AI research. You can find the repository [here](https://github.com/GAIGResearch/TabletopGames) and the paper that describes the design [here](https://arxiv.org/pdf/2009.12065.pdf)
<figure>
	<img src="/files/tag.png" alt="TAG screenshot">
	<figcaption>Screenshot of Pandemic, one of the currently implemented games from TAG </figcaption>
</figure>


### Java-pommerman
<img src="/files/java-pommerman.png" alt="java-pommerman" width="200" style="float:right">

I was involved in creating the Java version of the Pommerman framework. The framework is available [here](https://github.com/GAIGResearch/java-pommerman). We also evaluated Statistical Forward Planning methods in the framework, you can read the paper [here](https://github.com/GAIGResearch/java-pommerman/raw/master/AIIDE-19_paper-46.pdf). Screenshot from the game's GUI is on the right.

### Game parameter search using MAP-elites
We used a simple game called CaveSwing to tune the game's hyper-parameters using the MAP-Elites algorithm. Using MAP-elites we could find levels that the agent played with different behaviours. The heatmap below shows the result of a run of MAP-elites when observing the average height the agent takes to solve the level in combination with the average speed the agent takes to finish the level. The code is available on Github [here](https://github.com/martinballa/MAPElitesCaveSwing).
<figure>
	<img src="/files/map_elites_heatmap.png" >
	<figcaption>Heatmap from running MAP-elites on CaveSwing</figcaption>
</figure>

### Grapple Battle
As part of the first year training in IGGI we had to design and develop a game using Unity in a week. We came up with a First-person, split-screen game where the players have to grapple to avoid falling into the lava. The game features multiple weapon types and game modes: Capture the flag and deathmatch. You can check the gameplay in the video below:

<center>
	<iframe width="560" height="315" src="https://www.youtube.com/embed/nDR2EJ_dvOw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>
