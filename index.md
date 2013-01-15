---
layout: page
title: My Computer, Me and Myself
tagline: Welcome to Ribesg's lair
---
{% include JB/setup %}

## Hi ! 
My name is Gael Ribes, I'm french. I'm an apprentice working for HP in Grenoble while studying at the Ensimag.

_If you're not french or not used to french educational system, you may not be able to understand what follows._

I 

## Bukkit !
I started developping _[Bukkit][]_ plugins during the second semester of 2010. This work learnt me the `Java` language, how to use Eclipse, how to use an API dans how to read JavaDocs.

I'm currently working on a new project, between a complete rewrite of _almost_ everything I made during the last 2 years and a new organisation of my plugins : **the N plugins suite**.

I may add more informations on this project somewhere on this website. Here's a list of related projects : 
* **[NCore][]** : Core plugin, it's like a platform for every nodes to connect, for each one to be able to use each other, without cycle dependencies.
* **[NGeneral][]** : General plugin, with everything like **`/time`**, **`/weather`**, **`/rocket`**, **`/god`**...
* **[NCuboid][]** : Important plugin, basically like Worldguard, but with every functionnality I need. It's also something much more difficult to do, learning learning learning !
* **[NPunisher][]** : _(Will be renamed to **NPlayer**)_ It was supposed to be a **`/ban`**, **`/mute`**, **`/kick`**, **`/jail`** plugin, it will be a little more than that. For example there will be an **`/info`** command which would give you informations about the player (first/last seen, punishment status (ex: is he banned ?), and his IP for moderators / admins).
* **[NDodgeball][]** : It will need [NCuboid][] to work. Nothing else to say, self-explanatory ! Basically, it would use the Cuboids for the game itself, and you would define a "game zone" with one selection, automagically subdivised in 4 cuboids with every needed flags etc. You would be able to start a game with a command, players would use a command to join, teams would have colored leather armors, and why not fireworks of the winning team color at the end ?


{% include JB/comments %}

<!--- Under this lines are links defined --->
[Bukkit]: http://bukkit.org "Bukkit Forums"
[NCore]: https://github.com/Ribesg/NCore "NCore plugin repository"
[NGeneral]: https://github.com/Ribesg/NGeneral "NGeneral plugin repository"
[NCuboid]: https://github.com/Ribesg/NCuboid "NCuboid plugin repository"
[NPunisher]: https://github.com/Ribesg/NPunisher "NPunisher plugin repository"
[NDodgeball]: https://github.com/Ribesg/NDodgeball "NDodgeball plugin repository"
