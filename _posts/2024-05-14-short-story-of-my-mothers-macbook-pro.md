---
layout: post
title: Short story of my mother's MacBook Pro
date: 2024-05-14 21:00 +0200
categories: [Computers, MacBooks]
tags: [computers, software, hardware, apple, macbook, linux, gaming]
---

### Specs

- **Name:** [Apple MacBook Pro 13" 2013](https://everymac.com/systems/apple/macbook_pro/specs/macbook-pro-core-i5-2.4-13-late-2013-retina-display-specs.html)
- **CPU:** [Intel Core i5-4258U (2 cores, 4 threads) @ 2.90 GHz](https://www.intel.com/content/www/us/en/products/sku/75990/intel-core-i54258u-processor-3m-cache-up-to-2-90-ghz/specifications.html)
- **iGPU:** Intel Iris Graphics 5100
- **Ram:** 8 GB DDR3L
- **Disks:** WD Black SN770 1 TB
- **OS:** macOS Sonoma + [OpenCore](https://github.com/dortania/OpenCore-Legacy-Patcher) & [Ubuntu 24.04 LTS](https://ubuntu.com/desktop)

### Story

There isn't really much to say here really, this MacBook was bought for my mother by my father, but really I was the one who was using it most of the time, Back then I used to dual-boot macOS & Windows 10, but after I started using my father's MacBook, It was returned to my mom, but she didn't really use it much, but after my father's/my main MacBook's battery started bulging, I took this Mac for myself and started using it again.

I upgraded the system to macOS Sonoma and installed Ubuntu 23.10, and it worked like a charm (macOS Sonoma is kinda unoptimized for this old hardware though), I later re-pasted the CPU with Arctic MX-6 and upgraded the original 256 GB SSD to a WD Black SN770 1 TB.

It was my main laptop that I used when I did the 42 Wolfsburg's Piscine program and did a lot of C coding and compiling with this MacBook.

Hardware-wise there aren't many issues, the battery health level is around 84%, I do plan to replace it later on when I can afford it. Software-wise, Linux still lacks the driver for the MacBook's built-in webcam, though I don't really care for it much.

### Gaming stuff on Linux (WIP)

#### **Linux kernel 6.8.0 + Mesa 24.0.5**

- **Minecraft 1.20.4** (+ [Sodium](https://github.com/CaffeineMC/sodium-fabric)) = ~30FPS (kinda playable)
- **Civilization V** = ~ ~20-30FPS (Playable)
- **Civilization: Beyond Earth** = ~10-25FPS (Unplayable)
- **Portal 2** = ~30-60FPS (Too stuttery)
- **Phoenix Wright: Ace Attorney** = ~30-50FPS (Very playable)

> Note: the FPS's are really just estimates from my memory, please take it with a grain of salt (for now).

Because of **Steam's Proton**, I'm able to play some games on this thing, sadly the Haswell iGPU has only incomplete **Vulkan 1.2** support, I was able to start some games with Proton 7, but when entering the game it usual crashes, so whenever I play a game I usually play with the latest Proton (or [Proton-GE](https://github.com/GloriousEggroll/proton-ge-custom)) and forcing Proton to use WineD3D (DirectX to OpenGL) instead of the more efficient DXVK (DirectX to Vulkan).

I imagine that if full Vulkan support for the iGPU would ever be implemented or WineD3D would performance improve, maybe this MacBook could reach even higher potential than native Windows itself.
