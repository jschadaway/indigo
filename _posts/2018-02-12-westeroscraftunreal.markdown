---
title: "WesterosCraftUnreal - A Minecraft port to Unreal Engine 4"
layout: post
date: 2018-02-12 19:24
tag: c++
image: https://i.imgur.com/gfkJBnz.png
headerImage: false
projects: true
hidden: true # don't count this post in blog pagination
description: "Pylet is a basic development environment for creating, managing, and tracing Python code. It is intended to be as simple as possible to accomodate students and other learning individuals."
category: project
author: chamathdharmasiri
externalLink: false
---

![Screenshot](http://i.imgur.com/RhqDjz6.png)

WesterosCraftUnreal is a derivation of Andrew Scheidecker's [BrickGrid plugin](https://github.com/AndrewScheidecker/BrickGame/tree/master/Plugins/BrickGrid/Source/BrickGrid), meant to demonstrate the parsing of Minecraft's native NBT format directly to Unreal Engine 4. This project is built for the purposes of the [WesterosCraft](http://www.westeroscraft.com) server, though most of the functionality is derived from UE4 plugins.

[View on BitBucket](https://bitbucket.org/Hal9007/westeroscraftunreal)

---

Using Andrew Scheidecker's wonderful BrickGrid plugin as a framework, I use the libmcmap C library to parse Minecraft world data and stream it into a persistent Unreal Engine 4 world. Data for recently loaded chunks is cached, and the world can be saved or loaded at will within Unreal Engine 4. This project is meant to explore the possibilities of using Minecraft as a world-building tool to construct games that can be further developed in a more feature-rich game engine. In the future, I'd like to allow a dedicated server to manage both chunk streaming to connected users and network replications - as of yet, the project only allows multiplayer as a listen server, and functionality is fairly limited.