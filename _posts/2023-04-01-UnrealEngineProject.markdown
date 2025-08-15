---
layout: post
title: Unreal Engine Project
date: 2023-04-01 00:00:00
description: Beginnings of an Action-RPG type game to learn the ropes of the Unreal Engine like level building, actor behaviour and practice Level Design
img: UnrealEngineProject.png # Add image post (optional)
tags: [UE5, Level Design, Actor Behaviour] # add tag
---
<iframe width="896" height="504" src="https://www.youtube.com/embed/Z-aYjYpU0to?si=jHNjp_K7yVWOXfeg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
> Short video playing through the whole level.

## Overview
The goal for this project was to build a small Action-RPG game, like Diablo and Path of Exile, with one attack for the player and enemies, within one level that can be completed. More specifically, I wanted to learn to use the Unreal Engine for building a level, implementing the actor behaviours and animations. All assets, like models, animations and textures are from asset packs or Mixamo. 

![Enemy Behaviour Tree]({{site.baseurl}}/assets/img/UnrealEngineProject/EnemyBehaviourTree.png)
> Behaviour tree of the enemies in the game.

## Enemy Behaviour
Enemies follow the shown behaviour tree (contrary to what I thought at first, those are already very useful even with this simple behaviour of the enemies). It makes them run around randomly and chase the player when seen. Their attacks have an animation trigger that then checks for hitting the player.

Here, another option could have been to have the sword always check for hits, or during the full time of the swing. Similarly, the player has an animation trigger that spawns an explosion at the mouse pointer or, if too far away, at maximum cast range. 

![Annotated Map]({{site.baseurl}}/assets/img/UnrealEngineProject/TopDownOnMap_Annotated.jpg)
> Map of the valley with markings for POI's and the player path.

## The Map
Looking at the combination of view angle, how I built the level as an open space and the dirt paths as guidance, I know now that players easily get lost with it. How much can be seen and used as guidance is not enough without a mini-map or a space that is more constricting. On top of that, leaving the path does not offer much. I never implemented anything that could be found except for small health packs. As a result, what should be rewarding – exploring and going of the path from time to time – is not. I marked on the map areas that I already set up as something to discover, but for now remain empty.