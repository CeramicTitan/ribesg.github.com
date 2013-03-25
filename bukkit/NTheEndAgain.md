---
layout: page
title: NTheEndAgain plugin for Bukkit
category: bukkit
tagline: Infinite EnderDragons ! End selective regeneration ! 
tags: [bukkit, plugin]
---
{% include JB/setup %}

NTheEndAgain is a [Bukkit][] plugin and is part of the [NPlugins][] project.
You can view the source of all plugins in the [NPlugins Github repository][].

### *Status :* Private Pre-Alpha

A rewrite of my [TheEndAgain][] plugin, with at least the same functions. Just better, faster.

_DONE:_
* Main, empty, plugin structure (Config/Messages/Main class)
* Chunk representation
* Complete Configuration
* Finished Listener
* Coded Commands (Not case sensitive):  
    `/end regen [worldName]`  
    `/end respawnEnderDragon [worldName]` or `/end respawnED [worldName]`  
    `/end nbEnderDragon [worldName]` or `/end nbED [worldName]`  
    `/end chunk info` or `/end chunk i`  
    `/end chunk protect` or `/end chunk p`  
    `/end chunk unprotect` or `/end chunk up`  
* Some tests

_TODO:_
* Configurable messages (60% of them are missing)
* Allow `[x z worldName | x,z,worldName]` argument for `/end chunk *` commands
* A lot of tests, found some bugs in current Private Pre-Alpha stage
* Maybe add something in configuration for EnderCrystals (ability to disable them or change their behaviour)

{% include JB/comments %}

<!--- Under this lines are links defined --->
[Bukkit]: http://bukkit.org "Bukkit Forums"

[NPlugins]: /bukkit/NPlugins.html "NPlugins project page"
[NPlugins Github repository]: https://github.com/Ribesg/NPlugins "NPlugins Github repository"

[NTheEndAgain]: /bukkit/NTheEndAgain.html "NTheEndAgain dedicated page"