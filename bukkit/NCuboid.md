---
layout: page
title: NCuboid plugin for Bukkit
category: bukkit
tagline: Protection plugin for all your needs. Will be highly configurable.
tags: [bukkit, plugin]
---
{% include JB/setup %}

NCuboid is a [Bukkit][] plugin and is part of the [NPlugins][] project.
You can view the source of all plugins in the [NPlugins Github repository][].

### *Status :* Private Pre-Alpha

Important plugin, basically like Worldguard, but with every functionnality I need. It's also something much more difficult to do.

_DONE:_
* Plugin Structure
* Cuboid, CuboidDB representations. Almost completely done.
* Almost every Events are handled, linked to config etc.
* Commands:  
    `/cuboid reload <configName>`  
    `/cuboid create <cuboidName>`  
* Aliases:  
  + `cuboid`: `cubo`, `c`
  + `reload`: `rld`, `r`
  + `create`: `c`

_TODO:_
* Investigate non-Cuboid regions (Cylinders). Will be done after some releases.
* Commands:  
    `/cuboid` (Gives informations on player's cuboids)  
    `/cuboid delete <cuboidName>`  
    `/cuboid info <cuboidName>`  
    `/cuboid help [pageNumber]`  
    `/cuboid flag <cuboidName> <flagName> <value>`  
    `/cuboid welcomeMessage [message]`  
    `/cuboid farewellMessage [message]`  
    `/cuboid setJailPoint <cuboidName> <jailName>`  
    `/cuboid delJailPoint <jailName>`  
    `/cuboid rename <cuboidName> <newName>`  
    `/cuboid setOwner <cuboidName> <newOwnerName>`  
    `/cuboid addCoOwner <cuboidName> <newCoOwnerName>`  
    `/cuboid delCoOwner <cuboidName> <coOwnerName>`  
    `/cuboid redefine <cuboidName>`  
    `/cuboid allow <cuboidName> <playerName>`  
    `/cuboid deny <cuboidName> <playerName>`  
    `/cuboid allowCommand <cuboidName> <commandName>`  
    `/cuboid denyCommand <cuboidName> <commandName>`  
    `/cuboid list <playerName>`  
    Following commands may be change to a unique `/cuboid set <cuboidName> <attributeName> <value>`  
    `/cuboid setExternalPoint <cuboidName> [ worldName,x,y,z | worldName x y z ]`  
    `/cuboid setInternalPoint <cuboidName> [ worldName,x,y,z | worldName x y z ]`  
    `/cuboid setBoosterVector <cuboidName> < x,y,z | x y z >`  
    `/cuboid setHealAmount <cuboidName> <amount>` Temporary usage, may change  
    `/cuboid setHealTimer <cuboidName> <timer>` Temporary usage, may change  
    `/cuboid setHealMin <cuboidName> <min>` Temporary usage, may change  
    `/cuboid setHealMax <cuboidName> <max>` Temporary usage, may change  
    `/cuboid setFeedAmount <cuboidName> <amount>` Temporary usage, may change  
    `/cuboid setFeedTimer <cuboidName> <timer>` Temporary usage, may change  
    `/cuboid setFeedMin <cuboidName> <min>` Temporary usage, may change  
    `/cuboid setFeedMax <cuboidName> <max>` Temporary usage, may change  
    +Many others not yet listed  
* Aliases:  
  + `delete`: `d`, `remove`, `rm`
  + `info`: `i`
  + `help`: `h`, `?`
  + `flag`: `f`
  + flag `<values>`:
    - `true`, `enable`, `enabled`, `on`, `1`
    - `false`, `disable`, `disabled`, `off`, `0`
  + `welcomeMessage`: `wm`
  + `farewellMessage`: `fm`
* A lot of tests

{% include JB/comments %}

<!--- Under this lines are links defined --->
[Bukkit]: http://bukkit.org "Bukkit Forums"

[NPlugins]: /bukkit/NPlugins.html "NPlugins project page"
[NPlugins Github repository]: https://github.com/Ribesg/NPlugins "NPlugins Github repository"