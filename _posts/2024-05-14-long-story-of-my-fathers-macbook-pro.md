---
layout: post
title: Long story of my father's MacBook Pro
date: 2024-05-14 05:47 +0200
categories: [Computers, MacBooks]
tags: [Computers, Software, Hardware, Apple, MacBook, Linux]
---

In this post, I actually wanted to list all my Computers and equipment, but after writing some stuff, I'd ended up with too long of a text to keep everything, so I'm going to seperate them out to different posts.

Anyways, this is my father's last main MacBook Pro which I'm currently using as my main "desktop".

### Specs

- **Name:** [Apple MacBook Pro 15" 2013](https://everymac.com/systems/apple/macbook_pro/specs/macbook-pro-core-i7-2.3-15-dual-graphics-late-2013-retina-display-specs.html)
- **CPU:** [Intel Core i7-4850HQ (4 cores, 8 threads) @ 3.50 GHz](https://www.intel.com/content/www/us/en/products/sku/76086/intel-core-i74850hq-processor-6m-cache-up-to-3-50-ghz/specifications.html)
- **iGPU:** Intel Iris Pro Graphics 5200
- **dGPU:** NVIDIA GeForce GT 750M (2GB VRAM)
- **Ram:** 16GB DDR3L
- **Disks:** Apple (Samsung) SSD - 512GB
- **OS:** MacOS Sonoma + [OpenCore](https://github.com/dortania/OpenCore-Legacy-Patcher) & [EndeavourOS](https://endeavouros.com) + [KDE Plasma 6](https://kde.org/plasma-desktop)

### Story

#### Inheriting this thing

I inherited this MacBook Pro from my dad, and despite its age, it served me well. It had some battle scars; the screen coating suffered from staingate (failing of the coating), and the speakers blew out. But I pushed through, using it until the battery began to bulge alarmingly. In January 2024, I invested in a new iFixit battery, pair of speakers, and Arctic MX-6 thermal paste to keep it going.

#### Wolfsburg Woes

Taking it with me to Wolfsburg for the 42 Wolfsburg's Piscine program was exciting, but the journey wasn't smooth sailing. The LVDS cable, responsible for connecting the display, started to fail, causing the screen to get fuzzy. I replaced the cable myself, but unfortunately, the display went completely poof.

#### A Frustrating Diagnosis

Seeking a professional solution, I paid 50 euros for a diagnosis. To my disappointment, the repair shop declared the motherboard connector damaged and refused to fix it, deeming the laptop too old and expensive. They even scolded me for attempting a DIY repair, which felt unfair considering their website advertised fixing complex motherboard issues.

#### A Fresh Start

Back home, I soldiered on, using an external TV as a makeshift monitor (not ideal for the eyes!). This prompted a software refresh. I installed macOS Sonoma using [OpenCore Legacy Patcher](https://github.com/dortania/OpenCore-Legacy-Patcher) and initially opted for Windows 11. However, the latest Nvidia drivers (version 425.31) wouldn't output to the external monitor for some reason. I settled for an older driver version that worked, but Windows 11 kept pushing the problematic update.

#### Linux Liberation

Losing faith with Windows, and having positive experiences with Ubuntu on other machines, I desided Linux was the answer. Ubuntu was okay, and Linux Mint felt a bit outdated. I finally landed on [EndeavourOS](https://endeavouros.com) with [KDE Plasma 6](https://kde.org/plasma-desktop) (think Arch Linux with a GUI installer). It's been a fantastic experience ever since.

#### Driver Dilemma

The driver saga continues, though. Installing proprietary drivers on EndeavourOS (kernel version 6.8.9) proved unsuccessful. Honestly, I'm hesitant to use official Nvidia drivers anymore. They're outdated and don't support Wayland support. So, I'm sticking with the open-source Nouveau drivers for now. Yes, the performance isn't ideal, but at least they're still actively maintained, and for my Kepler-based GPU, the upcoming Vulkan driver, NVK, might even outperform the old official Nvidia drivers.

Despite the hardware hiccups, this trusty MacBook Pro has served me well. With a fresh Linux install and a focus on open-source options, it's ready for a new chapter, even if the display drivers remain a work in progress.

### Gaming stuff on Linux (WIP)

- **Linux kernel 6.8.9 + Mesa 24.0.7**
- **Minecraft 1.20.4** (+ [Sodium](https://github.com/CaffeineMC/sodium-fabric)) = ~45-60FPS (kinda playerble)
- **Civilization V** = ~20-30FPS (Playable)
- **Cvilization: Beyond Earth** = ~20-30FPS (Worst than Civ5 but weirdly playable)
- **Portal 2** = ~40-60FPS (playble)
- **Phoenix Wright: Ace Attorney** = ~50-60FPS (Very playble)
- **Genshin Impact** = ~10-20FPS (Not playable and lots of artifacts)

Note: the FPS's are really just estimates from my memory, please take it with a grain of salt (for now).

As you might have read, I'm using the Nouveau drivers, as of Mesa 24.0.7 + Linux kernel 6.8.9, there's still no auto-reclocking support and OpenGL is still version 4.3, but luckily there's still much hope with potential NVK support, and since this is a Kepler-based GPU, manual reclocking is actually supported and that's what I've been doing whenever I'm playing a game.

So these are the FPS I'm getting with the highest clock speed manually set then using the latest Proton (or [Proton-GE](https://github.com/GloriousEggroll/proton-ge-custom)) and forcing it to use WineD3D (DirectX to OpenGL) instead of the more efficient DXVK (DirectX to Vulkan).

Another note: MacBooks have this weird thing where, if you use a third-party OS (Windows, Linux & etc), it will only enable the dGPU (my suspicion is because Apple used their own gmux technology for the GPU switching), but with OpenCore Legacy Patcher, we could actually spoof third-party OSes to allow access to both of the GPUs, but as of now I decided to have this option off for now, as I want to see the actual performance of the dGPU without it being affected by the more well supported iGPU.
