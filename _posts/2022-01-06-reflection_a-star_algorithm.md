---
title: Reflection A-Star Algorithms from Scratch
tags: [Reflection, Algorithms]
style: 
color: 
description: A reflection of my implementation and application of the A-star algorighm.
---

{% include elements/figure.html image="https://github.com/SimonLuder/SimonLuder.github.io/blob/main/pictures/A-Star-Path_small.png?raw=true" caption="" %}

During my studies I had the task to implement the A-Star algorithm to find the shortest path between two points on a pixel based map. The A-Star algorithm is a graph-based algorithm, which follows the most promising path to solve a problem, based on the already covered distance as well as on a guess of the remaining distance to the target.

For me, this task was particularly interesting, because the problem of the shortest path can not only be used on maps, but offers a variety of applications. For example, the A-Star algorithm can also be used to study information networks, to optimize logistics tasks, or even for Natural Language Processing.

Since the maps used for pathfinding were not available in vectorized format, the algorithm had to iterate over the individual pixels. This created a bit of a performance problem, especially at higher resolutions and larger maps, as this meant that each pixel represented a separate node to the algorithm. Accordingly, if I were to revise it, I would first implement a more efficient method for creating a vectorized road network. Other than that, however, the implementation worked smoothly.

Most instructive for me was the impact of the chosen heuristic, which estimates the remaining path to the target. For example, choosing a heuristic that estimated the remaining distance more generously tended to result in a wider spreading behavior compared to one which underestimated the remaining path.

Overall, the implementation has been a very educational exercise that has shown me how a path-finding algorithm can work in general, and what problems it can solve in particular. Thereby i was able to add another tool into my data science arsenal, which will surely help me with my future challenges.
