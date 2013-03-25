---
layout: page
title: NTalk plugin for Bukkit
category: bukkit
tagline: Chat ! Nicknames ! Colors ! Censor ! Colored Tags !
tags: [bukkit, plugin]
---
{% include JB/setup %}

NTalk is a [Bukkit][] plugin and is part of the [NPlugins][] project.
You can view the source of all plugins in the [NPlugins Github repository][].

### *Status :* Private Alpha

Will allow modification of chat format, colors in chat, bad words check, private messages with 1 player, 1 group or console (channel-like)

_DONE:_
* Plugin structure (Config/Messages/Main class)
* Chat template to decide what to write before the message (Default: `&f<[prefix][name][suffix]&f> [message]`)
* Chat template for Private messages
* Chat formatting for Groups and/or Players (First check if Player has a custom format, then Group)
* Op format is defined in Config as "the same format as this group". Defaul to group 'admin'


_TODO:_
* Command: `/tell <Player> <Message>` - Aliases: `/pm <Player> <Message>`, `/m <Player> <Message>`, `@<Player> <Message>`
* Ability to replace `<Player>` with a group name: `/tell admin Hi staff!`
* Ability to use short names for groups, players: `@ad Hi staff!` (Same result as above)
* Ability to use multiple names of Group/Player/Console: `/pm admin,Console,Ribesg Hi!`
* Handle the "Console" word as a player, send the message to Console.

{% include JB/comments %}

<!--- Under this lines are links defined --->
[Bukkit]: http://bukkit.org "Bukkit Forums"

[NPlugins]: /bukkit/NPlugins "NPlugins project page"
[NPlugins Github repository]: https://github.com/Ribesg/NPlugins "NPlugins Github repository"