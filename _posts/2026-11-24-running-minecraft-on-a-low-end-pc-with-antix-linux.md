---
layout: post
title: "Running Minecraft 1.21.11 On A Low-End PC with AntiX Linux"
date: 2026-11-24
author: "evenblad3"
tags: [minecraft, windows, linux]
category: linux
---

This was pretty challenging to make it run at solid 60 FPS but it's playable!

### System Specifications
- AMD PRO A4-4350B
- R4 4GB RAM ddr3
- AMD Radeon R4 Graphics 128MB
- 512GB HDD

As we know Windows is known to consume at least 30% 16GB ram even when it is idle, so we got rid of the shit and tried [AntiX Linux](https://antixlinux.com).

THIS IS **NOT** A TUTORIAL!
I DO **NOT** CONDONE PIRACY!!

## Linux Installation
I did dual boot so the laptop has Windows and Linux. Both operating systems have equal amount of space, ~200GB.
Using GRUB too.


## Setting Up Minecraft
The launcher I used came with its own JRE, saved me tons of installation commands.

Vsync is disabled and Framerate is set to unlimited, no other changes made.

### Mods Installed:
- Fabric API
- Mod Menu
- Sodium (very important lol)
- FerriteCore
- Entity Culling
- Immediately Fast

All of these mods are available on [modrinth.com](https://modrinth.com)!

And for some reason Lithium seems to hurt the FPS, so I removed it.

## Result
Running on my private Aternos server.

When you join, framerate goes from very low to solid 60 and above within 10-15 seconds which is very reasonable on this machine.

Framerate fluctuates from 60 to 120 when you stay within the rendered chunks.
And when you explore it goes to 40 or less, so I don't recommend flying with elytra lol

![Minecraft 1.21.11 on AntiX Linux](https://i.postimg.cc/MG4gQMRB/Screenshot-2026-11-24-18-36-51.jpg)

Have a nice day and I hope you tried it as well :)
