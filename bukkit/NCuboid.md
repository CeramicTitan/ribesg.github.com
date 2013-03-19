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
  + **/cuboid reload \<configName>** with alias **rld** for **reload**
  + **/cuboid create \<cuboidName>** with alias **c** for **create**
  + **/cuboid delete \<cuboidName>** with aliases **d**, **r** and **remove** for **delete**

_TODO:_
* Investigate non-Cuboid regions (Cylinders)
* Commands:
  + New alias **r** for **reload** in command **/cuboid reload \<configName>**
  + **/cuboid delete \<cuboidName>** with aliases **d**, **r** and **remove** for **delete**
  + **/cuboid** with aliases **c** and **cubo** for **cuboid** (Gives informations on player's cuboids)
  + **/cuboid info \<cuboidName>** with alias **i** for **info**
  + **/cuboid help [pageNumber]** with alias **h** for **help**
  + **/cuboid flag \<cuboidName> \<flagName> \<value>** with alias **f** for **flag**. Allowed values:
    - **true**, **enabled**, **t**, **1**
    - **false**, **disabled**, **f**, **0**
  + **/cuboid welcomeMessage \[message\]** with alias **wm** for **welcomeMessage**
  + **/cuboid farewellMessage \[message\]** with alias **fm** for **farewellMessage**
  + Many others

{% include JB/comments %}

<!--- Under this lines are links defined --->
[Bukkit]: http://bukkit.org "Bukkit Forums"

[NPlugins]: /bukkit/NPlugins.html "NPlugins project page"
[NPlugins Github repository]: https://github.com/Ribesg/NPlugins "NPlugins Github repository"