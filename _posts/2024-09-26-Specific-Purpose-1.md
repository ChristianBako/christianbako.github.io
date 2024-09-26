---
layout: post
title: Specific Purpose Machine 1: Capslock is Actually Great
---

# Overview
Modern computers are designed as general purpose machines meant for everyone from engineers building spaceships to literal babies watching Youtube.

You're not everyone.

You should mold the computer to your mind.

I'm a big Vim guy. I got into it when I was a kid and now I can't stop using it because of the efficiency of Vim motions. 
It drastically lowers the friction between me and the computer.

My browser has Vim. Every code editor I've ever used has Vim. I'm writing this article in a Vim enabled markdown editor.

Vim turns a general purpose machine into a specific purpose one. One targeted at modifying text and taking input as fast as possible.

Your whole computer should be like Vim. Specific to you, with muscle memory to match.

# CapsLock

The first step along that path is to make CapsLock useful.

CapsLock is the coccyx of the keyboard, it's a vestige of [mechnical](https://en.wikipedia.org/wiki/Caps_Lock) typewriters.

If you're over the age of 17 you probably never used it on purpose. As far I can tell the only valid use for it is yelling at someone in all caps over the internet.

Secretly though CapsLock is actually the most useful button on your keyboard for one reason. CapsLock is a modifier key. 

It changes the behavior of other keys while it's pressed. Remap CapsLock and a new set of keyboard layer is unlocked.

You should make this useless button useful.

You paid for the whole keyboard after all! 

> Well, let's say you can shave 10 seconds off of the boot time. Multiply that by five million users and thats 50 million seconds, every single day. Over a year, that's probably dozens of lifetimes. So if you make it boot ten seconds faster, you've saved a dozen lives. That's really worth it, don't you think?

\- [Saving Lives](https://www.folklore.org/Saving_Lives.html)

Mac's exploding view is the worst way to find a given window if you're a power user. The ordering of windows changes every time you swtich apps so you can't create muscle memory.

The visual effort of finding that window interrupts your train of thought and takes seconds to find another window. Every second you spend seeking adds up over time.

Alt-Tab's stack based window finder is a bit better, but still is a linear search. (Outside of using it as "back" button to get to your prev window.)

I use a combo of CapsLock + Raycast to target specific apps on OSX instead of fumbling around in the dark for them.

# Tutorial
## Rebind CapsLock to ^

Go to Settings -> Keyboard -> Keyboard Shortcuts -> Modifier Keys in OSX and set CapsLock to be Control.

NOTE: If you have something like a Yubikey or other keyboard emulator Apple might not default to your actual keyboard. Doublecheck before you break your Yubikey and get very confused ;)
## Setup Shortcuts
Download [RayCast](https://www.raycast.com/). 

It's free and the easiest way to get the behavior we're looking for. There are some native ways of setting up shortcuts on OSX, but I couldn't get them to work.

Setup shortcuts using the remapped CapsLock key by going to RayCast command line -> Extensions and use the Hotkeys field for your desired apps.

I recommend using CapsLock mapped to Control and Command to establish a new key that is approximate to the <Leader> key in Vim. 
This combination of keys allows you to easily press CapsLock with your pinky and then command with your thumb.

Think of it as a keyboard namespace to put all your personal shortcuts under. 

Your right and left fingers are still on the home row, which leaves a huge amount of keyboard shortcuts to set.

My shortcuts are:
* Arc Browser - ^⌘,
* Intellij - ^⌘.
* Obsidian - ^⌘'
* Spotify - ^⌘:
* WezTerm - ^⌘/
* Claude Ask Question - ^⌘Space

You can replace these with whatever you most frequently use, and add context dependent apps like Teams/Slack/Outlook.

Happy Hacking

Chris
