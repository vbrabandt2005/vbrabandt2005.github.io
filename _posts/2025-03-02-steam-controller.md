---
layout: post
title: Steam Controller revisit in 2025
date: 2025-03-02 03:20 +0200
categories: [Computers, Controllers]
image: https://i.imgur.com/M4grmvo.jpeg
tags: [computers, software, hardware, linux, gaming, review, controller]
---

So, weirdly for Christmas, I randomly thought to myself that I want a [Steam Controller](https://store.steampowered.com/app/353370/Steam_Controller/) 10 years after it's release, the two games that made me want a Steam Controller was Okami and Civilization 6 (will explain later). I managed to snag one up second-hand through an Ebay auction for 60 euros (which I think was a fair price at this condition), It came with the original box, dongle, papers and of course the controller itself.

## First Impressions

![Holding the Steam Controller](https://i.imgur.com/SfCusjt.jpeg)

First time holding it felt really nice, yes, it's not the usual controller style, but despite its large OG Xbox-style big design, I got used to it really quickly to be honest.	

> My advice to anyone in using the Steam controller is instead of using your middle fingers to grip the controller, place both your index and middle fingers on bumper buttons and triggers always, this way, your thumbs will be at the proper angle making it easier to use the buttons and the touchpads.

Personally, the glossy-style plastic feels rather cheap to the touch, In general it felt as if Valve had dumped so many technologies into this controller that to lower the cost, they had to use cheaper plastics, I mean it's not bad, and I don't think it will break anytime soon, all I'm saying is, it's no Xbox 360 Controller.

Using it for the first time felt like a charm, the Steam integration with the Steam Client was really great and for the most parts worked out of the box.

### Updating

During my research, I discovered Valve released an Update which enabled Bluetooth connectivity.

Although I compliment the good Steam Input API integration, since the new Steam Big Picture UI update, Valve had removed the ability to update the Steam Controller entirely.

So I had to find a way, Valve released [.bat files and instructions](https://help.steampowered.com/en/faqs/view/1796-5FC3-88B3-C85F) for updating the controller on Windows, but I happen to be one of those Linux users, so I'm stuck, I tried using Wine, but sadly, the constant reconnection and restarting of the controller during the update process made it frankly impossible to use the .bat files to update the controller through Wine on Linux easily.

In the end I had to "hack" my way through by making a Windows virtual machine and install a 2018 build of Steam (with the old Steam UI), forward my Steam Controller into the VM and update it that way.

It was painful and took me hours, but in the end I now have the entire capabilities of Steam Controller.

On a genuine note, I'm surprised and really sad to see Valve no longer really caring about updating their own controller through their own client, I'm not asking for Valve to continue making new updates for the controller, It's just they should have implemented the update function into the new Steam UI too, and even though they have provided .bat files for Windows users, if you're purely a Linux or MacOS user then you're in a very hard position.

> There has been constant leaks about new Valve hardware soon (including a possible **Steam Controller 2**), So Valve ([Our Lord and Savior Gaben](https://i.imgur.com/eXBFL.jpeg), please re-implement the update function, as you will probably have to use a similar system to the OG Steam Controller.

#### Bluetooth connectivity

I admit I don't really have much to say here, because honestly I haven't found a use for this situation yet, I have tried and got it working with the Steam Link App but that's just it.

> I don't really want to comment on latency because I'm just not that type of player, like yeah I know how bad latency feels like, but genuinely I don't know how fast latency feels like, I just get used to it lol, but yeah that's just me being a really casual gamer.

## Actually using the controller

When I told my friends that I had bought myself a Steam Controller, every single person replied with "Why the actual hell would you want a Controller with no D-Pad and no 2nd thumb-stick?", I know it's hard for the people to understand and honestly in fairness, I don't think Valve explained it well either, as in my opinion it's not really an attempt to replace a traditional controller, but rather an attempt to get **Keyboard and Mouse games** working on a controller.

The controller makes a lot of sense especially in the context of a Home-Theatre-PC situation where you have your PC connected to a TV for media or gaming, the Steam Controller mostly removes the need of awkwardly having a keyboard and mouse on your lap while sitting on a sofa. The touchpads are so good, they basically remove the needs of a mouse and Steam provides an on-screen keyboard which is convenient enough, plus not to mention the amazing Steam Big-Picture mode.

In a racing (e.g. Forza), platform (e.g. Mario) and third-person (e.g. Tomb Raider) games where the developers designed the game in mind with controller support, a traditional controller make sense, but then there are games like **Civilization**, **Cities: Skylines** or any game which usually requires keyboard and mouse, in these cases you can configure the controller to simulate key-presses and mouse movement and it's frankly amazing.

I can't say much concerning FPS shooters because I admit I don't really play those kinds of games enough, but I have heard/read mixed opinions concerning this, in my experience it's something you have to get used to, it's definitely more causal and not meant for any competitive shooting, but basically you have to utilize the touchpad and gyro-sensor to aim, I personally have gotten used to it, but it always depends on personal preference.

### Controller build quality

Although I had criticized the feel of the plastic, the electronics itself feels really great.

#### Touchpads

The Highlights of the controller really, they are fairly accurate, of course it's not stylus accurate, but it's enough for the usual mouse movements, and the haptic-feedback on this controller often makes it feel like you're using more of a trackball rather than a touchpad to be honest a lot of the times.

> The left touchpad which is intended to be the D-Pad feels honestly weird to use in traditional games where a normal D-Pad is expected, it's just not accurate sometimes, but maybe I just have to learn how to use it properly.

#### Triggers

![How to hold it](https://i.imgur.com/ngSA2vN.jpeg)

Yes, the Triggers are another highlights of this controller, these triggers are special because they are dual-stage controllers, you can do a soft pull of the trigger then do a full-pull on the trigger to achieve a click.

I haven't actually been in a situation where I had to use this, but honestly it's quite awesome to know you can configure aiming and firing on a single trigger (soft-pull to aim and then full-pull to fire).

> Though to be honest to you, in games where the dual-stage triggers aren't used (so like a traditional analog trigger), having the click in the end kinda feels weird sometimes, but nothing deal-breaking.

#### Bumpers

Bumpers are clicky, they're basic, I don't think there's much special to them to be honest, I think a criticism would be that they need a bit of force to click.

#### Back-triggers

![Back-Pic](https://i.imgur.com/bL0lmBw.jpeg)

If I assume correctly, I believe back-triggers back then weren't that common, so yes, it special for it's time, I'm honestly fine with them too, I haven't been in a situation where I have to use them, but as far my experience goes, I personally think they feel great and I think the fact they are part of the backplate/battery-cover is actually kind of smart design even though it's clear it was made because of cost-savings.

#### Thumb-stick and buttons

The Thumb-stick feels honestly quite high quality, I can't explain why, but compared to cheaper controllers, touching this Thumb-stick makes me feel it's going to last for quite sometime

> I wonder though, Hall-Effect thumb-stick mod :)

Buttons feels small, but not in a bad way, honestly they aren't small enough to make me complain, maybe it will be different if I were to have bigger fingers.

### Steam Input API
Of course it depends on the games, the Steam Controller is quite unique in that it entirely relies on the Steam Input API on the Steam Client, in simple-terms, the Steam Input API intercepts a controllers signal, allowing the configuration of a controller's signal and then feeding it into the game, this is a really underrated feature which allows non-Xbox/X-Input controllers (e.g. PlayStation Dual-shock & Nintendo Switch controllers) to work/be-configured on games which only support Xbox/X-Input controllers.

Some games/developers implement the Steam Input API directly into the game allowing direct modification of controller configuration and wide-ranging controller support, back then Game-devs used Steam Input API to easily implement controller support into their games, I do know some games which intentionally implemented the Steam Input API with the Steam Controller in mind, and this has since moved over to the Steam Deck as some developers wishes to fully support it.

![Steam Input config for Civ5](https://i.imgur.com/e2t7D1g.jpeg)

#### Examples of Steam Controller/Steam Input API games

I would put Steam Input API games into three levels.

##### Native-Official

Native-Official means the game developer implemented Steam Input API directly into the game enabling the full configuration of the controller and wide-ranging controller support, these games are probably more common than you think and has appeared on some unexpected games to be honest.

1. Sid Meier's Civilization VII - includes Steam Input API allowing controller use like it's console versions.
2. Marvel's Spider-Man (+ Miles Morales & 2) - Surprising considering these are Sony-Published games, but I'm assuming it's because of wanting Steam Deck support.
3. Okami HD - I believe was implemented with the Steam Controller in mind.
4. Most Valve games :)

##### Non-Native-Official

Non-Native-Official means games which didn't implement Steam Input API directly into the game but instead provide official preset configuration for the Steam Controller (and I assume these configs will work with Steam Deck too)

1. Sid Meier's Civilization 5 and 6 - Civ5 specifically was one of the game shown when Valve presented the Steam Controller, the configuration simply hooks buttons into key-presses and touchpads to mouse input, it's actually a rather unique experience.
2. Doom (2016)
3. Factorio
4. Hades

##### Unofficial

Unofficial in this case means straight up fan-made configurations for often games which might not even support controllers in general.

I only have one example of this and it's **Sid Meier's Pirates (2004)**, this game is one of those older games where a numpad is needed for navigation, my keyboard (Skyloong GK87) happens to not have a numpad, so I had to find a way, I admit I haven't bought the Steam Controller intending to play this game, but it so happens someone made a Steam Input preset for the controller and I have been playing with it ever since, admittedly it's not perfect, but it's quite awesome to be honest.

> **Note:** In games which already has official controller support, the Steam Controller will by-default configure itself to be a standard (Xbox-style) controller (The Touchpads emulates the usual D-Pad and camera thumb-stick). Just want to mention as sometimes default configuration isn't really the best.

### Conclusion

Admittedly not all Steam Games will support the Steam Controller, some you have to make your own configurations (especially less-popular indie games), but honestly that's what makes the Steam Controller so cool, it's basically a tinkerers controller, it's unique and way ahead of it's time, and it's understandable why today there's a big cult-following of this controller, I think why it didn't sell well was because it was trying to fix an issue not every person really had, not everyone back then had a Steam Machine (wink, wink), and since the majority of gamers usually have their gaming PCs on a desk, the number of HTPC users who felt the need for this kind of controller was probably small.

In fact, in all honestly I can't really even recommend this controller except to those with very specific use cases, yes, this controller was ahead of it's time, but it has its flaws, I think it's biggest flaw is it's biggest speciality and it's the touchpads, the common people just wasn't used to the idea and admittedly not every game adapt well to the control scheme which the Steam Controller is able to provide, to put it simply, a touchpad can't really replace a thumbstick.

The Steam Controller legacy is think is bigger than most people think, despite being called a "failure", it did surprise the market with something innovative, and sometimes we need something like that, no matter how necessary, and the fact that the Steam Deck's control scheme (which is of course can be considered something of a successor) is considered one of it's main buying of the Steam Deck, Valve has constantly been obsessed with perfecting there inventions and their progress shows.

There has been leaks and rumours of Valve potentially returning to the Steam Machine and if you want to make a home-console, you need to make a controller, there has been recent leaks which shows a model of a Steam Deck-like controller but without the screen, and it looks quite interesting, it basically fixes the issue with the OG Steam Controller, all the Thumbsticks are there, while keeping the innovative touchpads, it looks awesome and I will probably get it if the leaks are real.

Finally, should you get yourself a discontinued but very innovative controller from 10 years ago? The answer is ***not really***, except if you're a HTPC-user, is constantly playing games on a couch, and is tired of always having to rely on Keyboard and Mouse, or you just want one in your rarities collection.

It's not useless, but it's current-gen game support is small (if not, near none), and for most people I think in most cases an Xbox (or 8Bitdo) Controller + Steam Big-Picture mode is sufficient, I think what the Steam Controller was trying to achieve was admirable, but really if you really want a Steam Controller, I think most people should just wait and pray for a Steam Controller 2, the improvements made for the Steam Deck simply makes it way more usable overall.

#### TL;DR

You don't really need it unless you find a reason to get one and even at that, you should just get the rumoured future Steam Controller 2, Still a legendary controller though.

## Rating

7/10, Legendary controller, if utilized properly with Steam Input API or an official configuration from the game developer.

### Pros
- Innovative touchpads
- Innovative dual-stage triggers
- Tinkerers dream
- Nice Gyro-motion sensors
- Multiple configurations, whether official, fan-made or DIY-made
- Nice Haptic-feedback

### Cons
- Touchpads can't really replace real thumbstick and D-Pad
- Dual-Stage controllers can feel weird
- Without practice FPS-shooters can feel bad
- Micro-USB
- Updating is hard
- Not really supported anymore