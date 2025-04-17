---
layout: post
title: Review of Skyloong GK87 QMK/VIA
date: 2024-11-03 16:30 +0200
categories: [Computers, Keyboards]
image: https://i.imgur.com/hZJf9N1.jpeg
tags: [computers, software, hardware, macbook, linux, gaming, review, keyboard]
---

So as background, I wasn't able to find any other review (except very undetailed reviews on Amazon) on this keyboard, so weirdly enough this might be the most detailed review of this keyboard.

> Note: This is an improved/re-written version of a review I've made on [Epomaker.de](https://epomaker.de/products/skyloong-gk87-qmk-via)

The main reason I ordered this keyboard is that I study programming and I really want a QMK/VIA compatible, work-focused keyboard, and this keyboard seems to fit all the points of my needs.

> Also, this is technically my first proper Mechanical Keyboard, I was given one 9 years ago, so yeah.

So, I pre-ordered this and chose Gateron Yellow key-switches, it took around 5-weeks to ship from China to Germany through YunExpress (China) and Hermes (Germany) (The long shipping is understandable as this is a pre-order).

## Chassis

After opening the box, I was quite impressed by the weight and feel of the chassis, the plastic felt so good that to be honest, I had mistaken it for aluminium, the keyboard is technically made of a thick plastic and a small aluminium top (area of the USB-C port).

The keyboard isn't gasket mounted though, there is basically no flex to it at all, but I wouldn't consider this a negative.

It has three level of height adjustment, I haven't developed a preference for any height yet, but the flexibility is great for people who might prefer a certain height. The keyboard feet are also unexpectedly strong, so they shouldn't break like most other keyboards do.

> There were also an okay amount of extras in the box, being USB-C cable, key cap puller, extra switches and key-caps. (wouldn't say they're special or anything)

## Keys

As I said, this is my first proper long-term experience with a mechanical keyboard, I had tried Cherry browns, blue and reds before, and usually I had ended up preferred **linear** switches.

I ordered this keyboard through Epomaker.de and they (only) offer three **linear** switches options.

- Gateron Yellows (Linear)
- Epomaker Wisteria (Linear)
- Epomaker Flamingo (I assume also Linear)

> Although I personally like linear switches, I honestly don't understand why Epomaker.de tends to only offer linear switches, I know a lot of tactile/clicky people struggle to buy a keyboard from Epomaker.de before.

### Gateron Yellows

![Gateron Yellow switches](https://i.imgur.com/8lRfhrx.jpeg){: w="400" h="400"}

I have never tried out Epomaker switches before, so I was hesitant to choose them, so I chose the **Gateron Yellow** switches as they were the only ones I could find detailed reviews from.

And oh my god, these switches are nice, I from what I have read, these switches are considered budget switches, but these are literally 10 times better than any linear keyboards at MediaMarkt, they are well lubed and feel very smooth.

I found them quite sensitive to type on, which can turn people off, but honestly I don't really mind.

Overall, these are really nice.

> I confess I do really want to try experimenting, I really want to try out Gateron Baby Kangaroos switches (Tactile), Gateron Baby Raccoons (Linear), Glorious Pandas (Tactile) or Glorious Lynx (Linear).

### Stabilizers

Okay, these are basically the worst parts of the keyboard.

The two shift, enter and backspace keys feel really mushy and hard to type on, they aren't so terrible that I wouldn't recommend this keyboard, and they are probably easily fixable with some lubing, but still this is something Skyloong could have done better.

### Key-caps

Yes, I'm going to talk about the key-caps, for some reason before ordering, I thought I was going to hate these key-caps, but after trying these out, I think these key-caps are amazing.

![Pudding Key-caps](https://i.imgur.com/LBK8Uvs.jpeg){: w="400" h="400"}

Skyloong calls these **"Pudding"** key-caps, basically on the top of the key-caps are matt feeling plastic, while the bottom/rest of the switch is see-through smooth plastic helps the bright LED shine through brightly.

The Top/Letters don't shine through much light, but the LEDs are so bright that I don't think anyone would complain that they can't see the keys.

## Software and customization

### QMK

Since I daily-drive Linux and since most keyboard-manufacturers don't support Linux, QMK/VIA open-source firmware was kinda a must for me.

While I was researching how to use QMK, I checked out the official QMK configurator and was confused to not see this keyboard as an option, since I was GitHub savvy, I went through QMK's GitHub repository, I proceeded to find that Skyloong's [Pull-request for this keyboard](https://github.com/qmk/qmk_firmware/pull/22668) was opened and left stale by the QMK maintainers for ~8 months, the Skyloong contributor closed the PR-request and made a new [pull-request](https://github.com/qmk/qmk_firmware/pull/24460), but a QMK maintainer didn't do research and mistook another keyboard for this model and the PR has been left stale for around a month now.

> Let me be clear, I don't mean to say anything bad to the QMK maintainers, but I feel QMK having so few maintainers/code-approvers makes development really slow, there are currently 332 PR-request and I my opinion the maintainers seems to be overwhelmed.

I admit I haven't gone through the QMK route (since I couldn't get QMK configurator to work), it is definitely possible to program you're own key-maps and use the terminal and stuff, but nah I'm lazy.

The official manual from Skyloong recommends download the [JSON file](https://github.com/JZ-Skyloong/VIA_keyboards/blob/gk87_bl/v3/skyloong/gk87/bl/gk87_bl_ansi.json) from their GitHub Repository and sideload it into the VIA configurator, I found it okay to use (it doesn't always work to be honest), but it's probably the way to go as of right now.

> If I'm correct VIA is simply an extension of QMK to make QMK simpler, so if the [pull-request](https://github.com/qmk/qmk_firmware/pull/24460) I mentioned gets merged, there would no longer be the need to manually sideload the [JSON file](https://github.com/JZ-Skyloong/VIA_keyboards/blob/gk87_bl/v3/skyloong/gk87/bl/gk87_bl_ansi.json) into VIA.

### LED backlight

![Bright LED blacklights](https://i.imgur.com/bEumxor.jpeg){: w="400" h="400"}

Well this would be small section, since these LED backlights are a single colour being *"cyan-nish"* blue, they are really bright, but I believe there are no per-key LED control (which honestly I don't feel it's needed on this keyboard) and as I have written in the key-caps section, with the help of the shine-through key-caps and the really bright LEDs, you won't struggle to see the keys at all.

> Also, VIA (and I assume also QMK) can control the LED directly

### Knobs

![Knobs](https://i.imgur.com/Zqz603B.jpeg){: w="400" h="400"}

There are three knobs at the top-right, and they feel really great, they are the clicky type of rotary encoders and knobs are made of high-quality aluminium, there's a bit of wobble but overall there fine.

You can also press into the knobs, so there's even more customization there.

Per-default settings for the knobs are Volume, LED brightness and Zoom (From left to right).

## Summery

I feel this keyboard tends to be forgotten by most people, I haven't seen that many reviews of Skyloong keyboards (especially this one), so when I first tried this I was genuinely really surprised by how good it is.

Overall, this keyboard was a worth-full buy even at full-price, I haven't tried it from the gaming perspective but for typing and coding, I have found it to be very, very fun to type on, the only thing I don't like are the stabilizers, Skyloong should have lubed them better, but it isn't enough for me to not recommend this keyboard.

### Pros

- Nice heavy high-quality chassis made from plastic and partially aluminium
- Nice feeling key switches and key-caps
- Three customizable rotary knobs
- Dual spaces for flexibility
- Bright LED backlights
- Potential full QMK/VIA support (And if you're a coder then it's probably already fits your requirements)
- Nice height adjustment with strong feet
- USB-C

### Cons

- Terrible mushy, badly lubed stabilizers on the shift, enter and backspace keys.
- No per-key LED controls (subjective)
- QMK/VIA support is not fully implemented
- Only Linear options (on the Epomaker.de site)
- Not gasket-mounted (also subjective)

This keyboard is great, and I highly recommend for anyone who wants a keyboard focused on productivity and doesn't really care for all the gamery aspects when it comes to buying a good mechanical keyboard, 8/10.
