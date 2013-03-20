---
layout: page
title: NCuboid plugin for Bukkit
category: bukkit
tagline: Also compatible with MCPC
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
  + cuboid: cubo, c
  + reload: rld, r
  + create: c

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
    +Many others

* Aliases:
  + delete: d, remove, rm
  + info: i
  + help: h, ?
  + flag: f
  + flag values:
    - true, enable, enabled, on, 1
    - false, disabled, disable, off, 0
  + welcomeMessage: wm
  + farewellMessage: fm
* A lot of tests

{% include JB/comments %}

<!--- Under this lines are links defined --->
[Bukkit]: http://bukkit.org "Bukkit Forums"

[NPlugins]: /bukkit/NPlugins.html "NPlugins project page"
[NPlugins Github repository]: https://github.com/Ribesg/NPlugins "NPlugins Github repository"