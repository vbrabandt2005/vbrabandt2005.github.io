---
layout: post
title: My tech equipments & software for 2024
date: 2024-05-13 05:47 +0200
categories: [Computers]
tags: [computers, software, hardware, apple, macbook, macos, linux, gaming]
---

This post is a list of all computers & software I use on the daily, plus some written reasons of why I use them.

Note: this doesn't include Android apps as I'll probably write another post for them.

## My computers

### Main "desktop": MacBook Pro 15" i7 2013

- **Name:** [Apple MacBook Pro 15" 2013](https://everymac.com/systems/apple/macbook_pro/specs/macbook-pro-core-i7-2.3-15-dual-graphics-late-2013-retina-display-specs.html)
- **CPU:** [Intel Core i7-4850HQ (4 cores, 8 threads) @ 3.50 GHz](https://www.intel.com/content/www/us/en/products/sku/76086/intel-core-i74850hq-processor-6m-cache-up-to-3-50-ghz/specifications.html)
- **iGPU:** Intel Iris Pro Graphics 5200
- **dGPU:** NVIDIA GeForce GT 750M (2 GB VRAM)
- **Ram:** 16 GB DDR3L
- **Disks:** Apple (Samsung) SSD - 512 GB
- **OS:** macOS Sonoma + [OpenCore](https://github.com/dortania/OpenCore-Legacy-Patcher) & [Endeavour OS](https://endeavouros.com) + [KDE Plasma 6](https://kde.org/plasma-desktop)
- **In-depth info:** [here](https://vbrabandt2005.github.io/posts/long-story-of-my-fathers-macbook-pro)

### Laptop: MacBook Pro 13" i5 2013

- **Name:** [Apple MacBook Pro 13" 2013](https://everymac.com/systems/apple/macbook_pro/specs/macbook-pro-core-i5-2.4-13-late-2013-retina-display-specs.html)
- **CPU:** [Intel Core i5-4258U (2 cores, 4 threads) @ 2.90 GHz](https://www.intel.com/content/www/us/en/products/sku/75990/intel-core-i54258u-processor-3m-cache-up-to-2-90-ghz/specifications.html)
- **iGPU:** Intel Iris Graphics 5100
- **Ram:** 8 GB DDR3L
- **Disks:** WD Black SN770 1 TB
- **OS:** macOS Sonoma + [OpenCore](https://github.com/dortania/OpenCore-Legacy-Patcher) & [Ubuntu 24.04 LTS](https://ubuntu.com/desktop)
- **In-depth info:** [here](https://vbrabandt2005.github.io/posts/short-story-of-my-mothers-macbook-pro/)

As I inherit both of these MacBooks from my parents, it wasn't really my choice, I will write about the story and experiences with both of these (& other computers) later.

## My choice of Software

### Operating Systems

- **OS for Desktops:** [Ubuntu](https://ubuntu.com/desktop), [Kubuntu](https://kubuntu.org), [Endeavour OS](https://endeavouros.com) or [Arch Linux](https://archlinux.org)
- **OS for Laptops:** [Ubuntu](https://ubuntu.com/desktop), [Kubuntu](https://kubuntu.org) or [Endeavour OS](https://endeavouros.com)
- **OS for older computers:** [Ubuntu MATE](https://ubuntu-mate.org) & [Linux Mint](https://linuxmint.com)
- **OS for Productivity, Music editing:** macOS

After trying out Linux, I haven't found a reason to go back to daily driving Windows, since I play some Anti-cheat games, I might want to dual-boot, but still I just find Linux to be more exciting to use than Windows (and that's saying as an early Windows 11 user/defender).

I honestly don't really care much about which Linux Distros to use, as most distros I would use are all either Debian/Ubuntu-based or Arch-based, though I still tend to prefer the 2 main desktop environment [Gnome](https://www.gnome.org) & [KDE Plasma](https://kde.org/plasma-desktop) for daily drive use, which between the two I prefer? Honestly depends on what computer I'm installing it on (usually simple [Gnome](https://www.gnome.org) on Laptops & Customizable [KDE Plasma](https://kde.org/plasma-desktop) on Desktop).

Sadly as a musician, I have become accustomed to GarageBand/Logic and I haven't found a good alternative for it yet, because of this I still feel like I need macOS around, I genuinely thought of getting myself another Mac only because of this 🥲.

### Package Managers

- [UpdateMe](https://github.com/vbrabandt2005/General-Scripts/tree/main/UpdateMe), my personal all in one update script

> (it sucks code wise, but I mean it's just a shell script, and it works)

#### Debian/Ubuntu-based

- [Nala](https://gitlab.com/volian/nala), an apt frontend
- [Pacstall](https://pacstall.dev/), AUR for Debian/Ubuntu-based distros

##### AppImages

- [Gear Lever](https://github.com/mijorus/gearlever), a handy GUI for managing AppImages

##### Flatpak

- [Warehouse](https://github.com/flattool/warehouse), a versatile toolbox for Flatpak
- [Flatseal](https://github.com/tchx84/flatseal), a Flatpak permissions manager

### Terminal

- **Terminal emulator (Windows):** [Windows Terminal](https://github.com/microsoft/terminal)
- **Terminal emulator (macOS):** [iTerm2](https://iterm2.com)
- **Terminal emulator (Linux):** [GNOME Terminal](https://gitlab.gnome.org/GNOME/gnome-terminal), [Konsole](https://konsole.kde.org) & [Alacritty](https://github.com/alacritty/alacritty)
- **Shell:** Zsh + [Oh My Zsh](https://ohmyz.sh/)
- **Prompt:** [Starship](https://starship.rs/) + [Tokyo Night](https://starship.rs/presets/tokyo-night)

### Browsers

- **General use:** Google Chrome 🥲
- **Not-Chrome use:** [Floorp](https://github.com/Floorp-Projects/Floorp)

Yes, I'm sorry I've been using Google Chrome since I've got introduced to it, I just like the syncing between devices, but if I ever need to do something privacy focused then I use [Floorp](https://github.com/Floorp-Projects/Floorp), which is a Firefox fork with more features.

### Text Editors & Office suite

- **General text editing:** [Notepad++](https://notepad-plus-plus.org) (Windows), [Kate](https://kate-editor.org) (Plasma) & [Notepad-Next](https://github.com/dail8859/NotepadNext)
- **Coding:** [VSCode](https://code.visualstudio.com) & [Zed](https://zed.dev)
- **Office suite:** [LibreOffice](https://www.libreoffice.org) & Google Docs

I mean, who doesn't love the amazing Notepad++? After switching to Linux, I wanted a similar text editor and found [Notepad-Next](https://github.com/dail8859/NotepadNext), which worked well. But on KDE Plasma, I decided to try [Kate](https://kate-editor.org), developed by the KDE organization itself. It integrates beautifully with Plasma, and I absolutely love it, so much so, that I even installed it on my Ubuntu laptop, though the integration with Gnome isn't as seamless.

In terms of general coding, I've always been a simple man, and VSCode fits me mostly. It's Electron-based, true, but it's extendable and customizable to my needs. [Zed](https://zed.dev) recently received some hype as a Rust-based code editor with performance in mind. It's still not available on Linux (but it is on macOS) (for some reason, like why prioritize macOS of all the OSes first?). I tried it, and honestly, it deserves the hype. I really want to try it out properly when it matures more.

Back in Windows, Microsoft Office was still the prime office suite. However, Microsoft's requirement for a subscription to use it (if it were a one-time payment of 200 euros, I would actually prefer that) has made LibreOffice a good alternative for me. While it lacks the fancy features of MS-Office, LibreOffice is very capable. I also use Google Docs occasionally, especially when collaborating with others or working on devices without an office suite installed (plus, I kind of like Google Docs on Android).

### Multimedia

- **All in one:** [Kodi](https://kodi.tv)
- **Video players:** [VLC](https://www.videolan.org), [MPV](https://mpv.io) & [Celluloid](https://celluloid-player.github.io)
- **Music players:** [Foobar2000](https://www.foobar2000.org), [Strawberry](https://www.strawberrymusicplayer.org) & [Elisa](https://apps.kde.org/en-gb/elisa)
- **CD Ripping:** [dBpoweramp](https://www.dbpoweramp.com), [fre:ac](https://www.freac.org) & [Audex](https://apps.kde.org/en-gb/audex)
- **DVD & Blu-ray ripping:** [Handbrake](https://handbrake.fr) & [MakeMKV](https://www.makemkv.com)

I don't actually use Kodi all that often, but I always have it installed just because I like it so much.

VLC has always been the standard for media players for a long time, but I've been using MPV as my default video player for a while and honestly, I still don't really know the difference between the two.

I really wish Foobar2000 had a Linux version, in my opinion it's probably the best Music player on desktops, so I tried to find alternatives, the best alternative I found was [Strawberry](https://www.strawberrymusicplayer.org) which works well enough for me.

CD ripping might be an unusual topic, but I'm a big defender of physical media (mainly Music & Movies) and I have a big collection of CDs, back then I found dBpoweramp on Windows and oh my fricking god, it's so, so good, but sadly there's no Linux version, so I've been using fre:ac & Audex.

### Graphics

- **Drawing/painting software:** [Krita](https://krita.org)
- **Raster graphics editor:** [Gimp](https://www.gimp.org)
- **Vector graphics editor:** [Inkscape](https://inkscape.org)
- **Pixel Art:** [Asprite](https://www.aseprite.org/) (or [LibreSprite](https://libresprite.github.io/))

I can't write much about these as I wouldn't consider myself an expert in this aspect, but these 3 programs I have listed out I always have installed and trust in case I ever need them, special mention for Krita, it's so good I actually paid for it on Steam despite it being free.

### Digital audio workstation (DAW)

- [Audacity](https://www.audacityteam.org/) (or [Tenacity](https://tenacityaudio.org/))
- GarageBand
- Ableton

GarageBand is my current favourite DAW, it's simple and has enough features for anyone to finish their songs, I really want to buy Logic Pro. I do own a copy of Ableton lite, but last I used it I found it to be too convoluted, maybe I will try it out again later.

And I mean [Audacity](https://www.audacityteam.org/) (or [Tenacity](https://tenacityaudio.org/)) despite all their flaws are still a must-have as a basic DAW, both are open-source, with Tenacity being a fork of Audacity with telemetry and weird stuff removed.

My current try-out list are Logic & [Bitwig](https://www.bitwig.com).

### Video-editing

- **Video editors:** [Kdenlive](https://kdenlive.org/) & [Shotcut](https://shotcut.org)
- **Video capture:** [OBS](https://obsproject.com)

Again I don't do video editing on the daily, but whenever I need to then Kdenlive & Shotcut are my preferred video-editor, both are cross-platform & Open-source. I want to try out Final Cut Pro in the future though. For screen-capture then OBS is a must of course.

### Game Launchers

- **Best of all:** [Steam](https://store.steampowered.com/)
- **GOG & Epic launcher:** [Heroic Games Launcher](https://heroicgameslauncher.com)
- **Hidden Indie gems**: [Itch.io](https://Itch.io)
- **A better Minecraft launcher:** [Prism Launcher](https://prismlauncher.org)
- **Anime Games:** [An Anime Game Launcher](https://github.com/an-anime-team/an-anime-game-launcher) & [The Honkers Railway Launcher](https://github.com/an-anime-team/the-honkers-railway-launcher)
- **Misc:** [Lutris](https://lutris.net/)
- **Proton-GE management:** [ProtonUp-Qt](https://davidotek.github.io/protonup-qt/)

I mean who doesn't like Steam (OK, well Tim Sweeney at Epic), but seriously, there's a reason why Steam is so huge, firstly the launcher is legitimately good, they have fair prices, they have a good support team, and they support open-source.

Epic & their store sucks, I won't be talking more about it, GOG though is actually rather good (especially their launcher), though both stores doesn't have a Linux launcher, but [Heroic Games Launcher](https://heroicgameslauncher.com) has been quite great for me, it's simple and works really well. (Note: Lutris is also a good alternative)

Another cool store is Itch.io, it's mainly focused on Indie games, and they have a Linux launcher which is also fantastic.

I've been using Prism Launcher even before I switched to Linux. It has multiple features, such as the ability to manage mods, resource packs, and shaders. Yeah, it's quite good.

[An Anime Game Launcher](https://github.com/an-anime-team/an-anime-game-launcher) & [The Honkers Railway Launcher](https://github.com/an-anime-team/the-honkers-railway-launcher) provide a native Linux solution for launching games from a certain "anime games" company. Unlike the original launchers, these launchers offer additional features such as language voice pack management, FPS unlocking, FSR upscaling, and more.

(P.S. I'm really proud to have contributed the Thai translations for these two "anime games" launchers!)

Usually I always play with Proton(GE)/Wine enabled, as I found most Linux Native versions of games to be inferior to the Windows version (except for some indie games), some games have quite good native ports but most of the time I found its saves to be incompatible with Windows (like Civ5, Tomb Raider & VA-11 Hall-A for example), me like cross-platform OK, it would annoy me a lot if I try to play one of these games on Windows and find my game saves to be incompatible.

Overall, gaming on Linux has been shockingly & impressively good, I don't think out of all the games I'm currently playing I haven't seen any real big issues (except for DXVK not being support on my computers or some audio-crackling).

### Misc

- **Scanning program:** [NAPS2](https://www.naps2.com)
- **Third-party Discord client:** [Vesktop](https://github.com/Vencord/Vesktop) & [Armcord](https://github.com/ArmCord/ArmCord)
- **Torrenting:** [qBittorrent](https://www.qbittorrent.org)
- **Software sharing:** [Localsend](https://localsend.org) & [RQuickshare](https://github.com/Martichou/rquickshare)
- **System Info:** [CPU-X](https://github.com/TheTumultuousUnicornOfDarkness/CPU-X)

[NAPS2](https://www.naps2.com) is probably the best free & open-source document scanning software, not much to say really, it's cross-platform and quite cool.

I don't actually endorse you breaking the TOS of Discord, except on Linux because the Discord client on Linux kinda sometimes sucks and receive less priority than other versions (Honestly if Valve owned Discord, it would be so much better lol).

Sadly I was introduced to pirating quite young (by my father in fact), I don't do it any more, but I still use it when downloading Linux ISOs. Out of all the Torrent clients out there, [qBittorrent](https://www.qbittorrent.org) is closes to the original µTorrent client, but it's 100x better ethically and feature-wise.

This list might not be complete, but will be updated over months & years, but yeah if you actually read everything I don't know you're crazy lol.
