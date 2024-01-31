---
title: Tamas Kemenczy
summary: Game designer (Kentucky Route Zero), web developer (Pitchfork)
date: 2012-11-20
categories:
- artist
- designer
- game
- hacker
- linux
- mac
---

### Who are you, and what do you do?

I'm [Tamas Kemenczy](http://singlemaltmana.net/ "Tamas' website."), an artist, indie game designer and web developer based in Chicago. Right now I'm collaborating with [Jake Elliott](http://dai5ychain.net/ "Jake's website.") on [Kentucky Route Zero][kentucky-route-zero], a [Cardboard Computer](http://cardboardcomputer.com/ "Cardboard Computer's website.") game, as well as working as a developer for [Pitchfork](http://pitchfork.com/ "Pitchfork's website."), most recently working on the [Bat for Lashes](http://pitchfork.com/features/cover-story/reader/bat-for-lashes/ "A cover story on Bats for Lashes.") cover story. I also work on a homebrew [Arduino][] VGA synthesizer for [Arcanebolt](http://arcanebolt.net/ "Arcanebolt's website."), a video/noise project.

### What hardware do you use?

For my workhorse game dev setup, I sit on an old creaky farm chair in front of an Apple 27" [Cinema Display][cinema-display], driven by a 2010 11" [MacBook Air][macbook-air] with 2GB of RAM and a Nvidia Geforce 320M graphics card. I'm not in any rush to upgrade for the moment, and I don't mind the lower ceiling - I like to know that what I'm working on runs on somewhat more modest hardware. My tattered pair of [Sony MDR-7506][mdr-7506] headphones are a classic and they have good audio response.

I do testing on a few other laptops sitting around: A 2011 13" [MacBook Pro][macbook-pro], an older 2009 MacBook Pro, a [Lenovo Thinkpad T60p][thinkpad-t60p], Lenovo 13" Thinkpad Edge, and a [Lenovo IdeaPad V570][ideapad-v570].

On input devices: I use an old school optical 3-button/wheel mouse and an [Apple Wireless Keyboard][keyboard] with the caps lock remapped to control. While I depend on a multitouch trackpad/[Magic Mouse][magic-mouse] for day-to-day use, I find that it's just a bit too fuzzy and error-prone for the production tools I use. So the hard-wired buttons are an essential haptic.

For Arcanebolt, I use a Lenovo Thinkpad Edge running some bygone version of [Ubuntu][] for flashing the Arduino boards. During performances we use an old XT keyboard that talks to the board. We use an obsolete Magnavox CRT screen to display the Arduino-generated VGA images, and on occasion an old IBM CRT as well. Old naive monitors like that are much more responsive to weird and corrupt video signals!

### And what software?

[Emacs][] is [home sweet home](https://github.com/tamask/emacs-conf "Tamas' Emacs configuration on Github.") and I use it across the board for development and pretty much anything text-related. Menlo is the monospace/programming font that I can't do without, it makes all the right changes to Bistream Vera Sans Mono. For general scripting I use [Python][] or [JavaScript][], and [Bash][] to tie it all together. I like the webkit flavor of browsers, [Safari][] or [Chrome][]. [OS X][macos] generally has bash/Emacs-style key bindings which is really helpful, and although I don't really spend too much time with the built-in OS apps and features (other than [Messages][ichat]), Spotlight, Quick Look and the suite of screenshot commands are wonderful. I jot down text snippets with [Gist][].

[Blender][] is my jam for computer graphics - fullscreened on that 27" display with the Elsyiun skin. I view Blender as the Emacs of its domain and the extensibility via the Python API is indispensable. For a tool that I spend so much time in, the UI hits the mark. I lug around a number of [Python scripts](https://gist.github.com/tamask "Tamas' Python scripts on Gist.") for my Blender/Unity workflow (mainly for working with obsolete vertex-based coloring and line art), and I've found myself tweaking the FBX exporter too. I also love the idea of using Blender as a headless, general purpose command-line renderer that uses Python for scripting. [Gimp/X11][gimp] does the job for image/texture editing and I fire up [Grapher][] occasionally to help visualize curves and filters for various shaders and procedural graphics.

Kentucky Route Zero is being developed in [Unity Pro][unity] and we're using [Mono][]/[C#][c-sharp] for game components. We've set up the Unity project for external revision control and use [GitHub][] for code storage and issue tracking, and I use a [Tumblr][] to document my thought process and keep track of inspiring media for the game's art direction. I often end up with with long email chains talking through various game mechanics and possibilities so I guess [Gmail][] could count towards a project management tool. I find HTML/JavaScript/CSS a great low-overhead prototyping environment to fallback on.

For my Arcanebolt-related work, I use a custom [Makefile][make], [avr-gcc][] and [avrdude][] to compile Arduino projects via Ubuntu. This way I can comfortably work in Emacs instead of the bundled Arduino IDE (creature of habit). [GNU screen][screen] comes in handy for reading back serial output from the board.

###What would be your dream setup?

The setup I have right now does the trick. I used to have back problems from hunching over a laptop screen for long periods of time - getting a nice external monitor really helped, so I'm still coasting on that! Come to think of it, I'd love a portable display that was bright enought to easily see outdoors. It would be wonderful on a rooftop deck, or a porch.

[arduino]: https://www.arduino.cc/ "Open-source prototyping hardware."
[avr-gcc]: https://github.com/epi/avr-gcc "A gcc-based toolset for AVR microcontrollers."
[avrdude]: https://github.com/sigmike/avrdude "A utility for changing the ROM and EEPROM of AVR microcontrollers."
[bash]: http://www.gnu.org/software/bash/ "A terminal shell."
[blender]: https://www.blender.org/ "A free, open-source 3D renderer."
[c-sharp]: https://en.wikipedia.org/wiki/C_Sharp_(programming_language) "A compiled programming language."
[chrome]: https://www.google.com/intl/en/chrome/ "A WebKit-based browser, where each tab runs in its own thread."
[cinema-display]: https://en.wikipedia.org/wiki/Apple_Cinema_Display "An LCD display."
[emacs]: http://www.gnu.org/software/emacs/ "An extensible, customizable, free/libre text editor — and more."
[gimp]: https://www.gimp.org/ "An open-source image editor."
[gist]: https://gist.github.com/starred "A version controlled code snippets service."
[github]: https://github.com/ "A Git code repository service."
[gmail]: https://en.wikipedia.org/wiki/Gmail "Web-based email."
[grapher]: https://en.wikipedia.org/wiki/Grapher "A 2D/3D graphing program included with Mac OS X."
[ichat]: https://en.wikipedia.org/wiki/IChat "An AIM/Jabber client included with Mac OS X."
[ideapad-v570]: http://web.archive.org/web/20150512151421/http://shop.lenovo.com:80/us/laptops/ideapad/v-series/v570 "A 15.6 inch PC laptop."
[javascript]: https://en.wikipedia.org/wiki/JavaScript "An interpreted scripting language."
[kentucky-route-zero]: http://kentuckyroutezero.com/ "An adventure game."
[keyboard]: https://www.apple.com/us/shop/goto/mac/accessories "The keyboard."
[macbook-air]: https://www.apple.com/macbook-air/ "A very thin laptop."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[macos]: https://en.wikipedia.org/wiki/MacOS "An operating system for Mac hardware."
[magic-mouse]: https://en.wikipedia.org/wiki/Magic_Mouse "A multi-touch mouse."
[make]: http://www.gnu.org/software/make/manual/make.html "Software to prepare code for compilation."
[mdr-7506]: http://web.archive.org/web/20230522193817/https://www.amazon.com/Sony-MDR7506-Professional-Diaphragm-Headphone/dp/B000AJIF4E "Studio-quality headphones."
[mono]: https://www.mono-project.com/Main_Page/ "A cross-platform .NET framework."
[python]: https://www.python.org/ "An interpreted scripting language."
[safari]: https://www.apple.com/safari/ "A fast web browser."
[screen]: http://www.gnu.org/software/screen/ "Think of it as tabs for your *nix terminal."
[thinkpad-t60p]: https://support.lenovo.com/us/en/docs/MIGR-62487 "A 15 inch PC laptop."
[tumblr]: https://www.tumblr.com/ "An online personal publishing platform."
[ubuntu]: https://ubuntu.com/ "A Unix distribution."
[unity]: https://unity.com/products "A cross-platform game development tool."
