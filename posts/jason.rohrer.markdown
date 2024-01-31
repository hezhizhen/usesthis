---
title: Jason Rohrer
summary: Game developer (Passage)
date: 2010-02-25
categories:
- developer
- game
- linux
- windows
---

### Who are you, and what do you do?

I'm [Jason Rohrer](http://hcsoftware.sf.net/jason-rohrer "Jason's site."), an independent video game designer. I've released 13 games over the past four years, and I did everything alone on all the games that I made (code, graphics, music, etc.). The most well-known game of the bunch is [Passage][]. I'm currently working on a game for the Nintendo DS that will be published by Majesco sometime in 2010.

### What hardware do you use?

My main computer these days is a broken [Dell Inspiron 4100][inspiron-4100] that my sister was going to throw away---I got it for free. It has a 950 MHz processor and 256 MiB of RAM. The hard drive is 18 GiB. It's broken in that the LCD screen's driver chip has a flaky connection, so it sometimes turns black screen areas bright red or has blue streaks around the edges of UI windows. My sister had tried adjusting the gamma correction to minimize this, but eventually gave up on it. She also found that the computer had gotten too slow to be usable. Opening a simple Word document could take minutes, she said. 

When I received the laptop, I found that the LCD problem could be corrected by "twisting" the top corners of the LCD screen. Twist it just right, and you can get a perfect image again. If the ambient temperature shifts, or you jostle the laptop in your luggage, the problem comes back, but a few seconds of LCD twisting almost always solves the problem. I'm pretty sure that it's a bad connection of some kind.

I also have a [PowerComputing 250 MHz][powertower-pro-250] PPC Mac Clone (remember those?) with 128 MiB of RAM that I use occasionally for backups and testing. In fact, Passage was developed on that computer.

When I started [iPhone][] development last year, I got a first-generation [Intel Mac Mini][mac-mini] on Craig's List for $250. It has a 1.5 GHz processor and 512 MiB of RAM and a 40 GiB hard drive. It's off, most of the time, though, unless I'm doing iPhone stuff.

When I want to do an official Mac build of a game, I turn on my wife's old first-generation [iMac][] (tray-loading), to ensure that the build will work on PPC machines too (I don't want to make an Intel-only build). It has a 233 MHz PPC processor and 128 MiB of RAM.

Like most programmers, I have some trouble with my wrists. I switch back and forth between a regular keyboard and [a DataHand][the-professional-ii] that I found used on eBay (they no longer manufacture them).

### And what software?

I mentioned before that the Dell laptop was too slow for my sister. [Windows XP][windows-xp] has a habit of doing this to people over the years---slowing down to the point where they feel like they need new computers! So I reformatted the drive, split it into two partitions, and reinstalled XP on one of the partitions. The machine was suddenly fast again! In fact, it is now faster than the [Vista-hobbled][windows-vista] Dell Laptop that my sister got to replace it.

On the other partition, I installed [Ubuntu][] 7.04 (aka Feisty Fawn), which is my main development OS, and what I boot into almost every day. I'm typing in Ubuntu right now, in fact. Actually, I'm running [Xubuntu][], which is just Ubuntu with a lighter-weight desktop environment. I found that regular Ubuntu was using way too much memory.

I code using [Emacs][], and I compile in the terminal using GNU [makefiles][make] and [GCC][]. For pixel graphics, I've fallen in love with [mtPaint][], but I also use [GIMP][] when I need layers and masks. For vector graphics, like making EPS files, I use [Skencil][]. When I need to typeset something, like a design document or an invoice, I use [LaTeX][]. Almost all of this software is available in the Ubuntu repository for easy installation via apt-get (just one line in the terminal and---bam---you have a new, working app perfectly installed).

For slide presentations, I use [Firefox][] in full-screen mode (I have coded a little HTML template that puts "back" and "next" links at the top of each HTML slide).

In terms of libraries, I use [SDL][] for graphics/sound/input and OpenGL if I need to draw polygon-based graphics.

On the cross-platform side, I compile my ports using the same makefiles and GCC. On [Mac OS X][macos], these things are built-in (as they should be), but on the Windows side, I use [MinGW][] and [MSys][]  to provide a sane, command-line build environment. SDL and OpenGL work on all these platforms, fortunately.

On Windows, I've also made some of my games (my small, 1-week "sketches") using [GameMaker][], which is absolutely amazing. A Mac port is in beta right now, which is great, because I don't like having my work trapped on a single platform.

### What would be your dream setup?

Dream setup? This is it!

[emacs]: http://www.gnu.org/software/emacs/ "An extensible, customizable, free/libre text editor — and more."
[firefox]: https://www.mozilla.org/en-US/firefox/new/ "A cross-platform open-source web browser."
[gamemaker]: https://gamemaker.io:443/gamemaker "A cross-platform game creation tool."
[gcc]: http://gcc.gnu.org/ "Code compiler frontends."
[gimp]: https://www.gimp.org/ "An open-source image editor."
[imac]: https://www.apple.com/imac-24/ "An all-in-one computer."
[inspiron-4100]: http://web.archive.org/web/20210921094200/https://www.zdnet.com/product/dell-inspiron-4100/ "An old PC laptop."
[iphone]: https://en.wikipedia.org/wiki/IPhone_(1st_generation) "A smartphone."
[latex]: https://www.latex-project.org/ "Typesetting software."
[mac-mini]: https://www.apple.com/mac-mini/ "A small desktop computer."
[macos]: https://en.wikipedia.org/wiki/MacOS "An operating system for Mac hardware."
[make]: http://www.gnu.org/software/make/manual/make.html "Software to prepare code for compilation."
[mingw]: http://web.archive.org/web/20221229043715/http://www.mingw.org/wiki/MinGW "A compiler system for Windows based on GCC."
[msys]: http://web.archive.org/web/20230522171508/http://www.mingw.org/wiki/msys "A Bash shell for Windows."
[mtpaint]: https://mtpaint.sourceforge.net/ "A painting program for *nix and Windows."
[passage]: https://hcsoftware.sourceforge.net/passage/ "A cross-platform game of discovery."
[powertower-pro-250]: http://web.archive.org/web/20230706194108/https://everymac.com/systems/powercc/powertower_pro/powertower_pro250.html "A PowerPC-based Mac clone."
[sdl]: http://www.libsdl.org/ "A cross-platform multimedia/gaming library."
[skencil]: http://www.skencil.org/ "A freeware vector drawing application for *nix."
[the-professional-ii]: http://www.atpm.com/7.05/datahand.shtml "An oldish USB-based input device."
[ubuntu]: https://ubuntu.com/ "A Unix distribution."
[windows-vista]: https://en.wikipedia.org/wiki/Windows_Vista "A desktop operating system."
[windows-xp]: https://en.wikipedia.org/wiki/Windows_XP "An operating system for x86 computers."
[xubuntu]: https://xubuntu.org/ "A lightweight version of the Ubuntu distribution."
