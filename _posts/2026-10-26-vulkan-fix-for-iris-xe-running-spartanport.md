---
layout: post
title: "Vulkan 1.3 fix For Iris Xe Running SpartanPort"
date: 2026-10-26
author: "evenblad3"
tags: [driver, windows, graphics, rendering]
category: windows
---

## The Problem
SpartanPort needed Vulkan 1.3 to run the game, the device I tried to run had 1.2 and old driver software. It waas `28.x` something...

[Download the latest SpartanPort build](https://github.com/FelipePrado0/SpartanPort/releases/latest)

## The Fix
So I had to update the driver software to version `32.0.101.7092` (As of writing this post, this is the latest version).
First time, I tried installed wrong software and almost ended up losing hope of not being able to play God of War III Remastered. I gave another try and hopefully last to try updating the driver. I made sure the device CPU was actually in the `This download is valid for the product(s) listed below.` list, and finally found the CPU model the laptop had.

[Download Intel® 11th – 14th Gen Processor Graphics for Windows](https://www.intel.com/content/www/us/en/download/864990/intel-11th-14th-gen-processor-graphics-windows.html)

And as usual updating driver software worked and the laptop was able to run the game at 30-60 FPS. Due to large assets being rendered and heavy shader translation, the framerate was fluctuating but it was playable.

Specs:
- Intel i7-1165G7
- Intel Iris Xe Graphics
- 16GB DDR4

Truly grateful to SpartanPort contributors for making GOW III possible to run on lower end devices.
