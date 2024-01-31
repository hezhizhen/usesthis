---
title: Jonathan Foote
summary: Recovering scientist
date: 2011-07-22
categories:
- artist
- hacker
- hardware
- linux
- scientist
- windows
---

### Who are you, and what do you do?

[My](http://rotormind.com/ "Jonathan's website.") usual story is that I'm a "recovering scientist." I took a leave of absence from a wonderful cushy research job and somehow have not made it back onto the hamster wheel. I do a mix of consulting, speculative projects, and [stupid art things](http://www.chassistherobot.com/ "The site for Chassis, the drink-serving robot.").

### What hardware do you use?

Sadly, nothing that exotic or interesting. A big Windows box with a quiet fan, and [Cygwin][] and [VirtualBox][] for [Ubuntu][]. Yes, I know, Windows sucks -- but a lot of engineering software does not play nicely elsewhere. 

I used to be THE Apple fanboy -- remember the Mac 128K and the 5-volume "Inside Macintosh"? But then I discovered Unix workstations, and little things like memory management (whoa-- crashed apps don't crash the system?) and gradually drifted away. I may drift back now that Macs are nicely unixy so please don't hate me.

I like trackballs -- mice leave my wide hands feeling cramped. The [Logitech Marble Mouse][marble-mouse] is a good one. Also my desk is messy and it takes up much less space.

A [Win7][windows-7] laptop to be compatible with clients (dual-boot with Ubuntu), a couple older laptops for redundancy and for taking to challenging locations, an [iPhone][]. 

I'm fond of embedded Linux for [robotics](http://wiki.orbswarm.com/index.php?title=Overview "Information on the SWARM art work/robots.") and [stand-alone art installations](http://rotormind.com/projects/portfolio/Carr/ "Information on an interactive LED lightwork by Jonathan."). Had a pretty good run with the [TS-7260][ts-7260], but am poking at a pile of alternatives, like the [BeagleBoard][] and [Chumby][]. Kernel hacking is not really my passion, so I'm pleased when something Just Works - so far the Chumby has been (mostly) delivering on that account: download [Python][], check, set up ad-hoc wireless, check, import [OSC][pyosc] and send commands from [TouchOSC][touchosc-ios] on your iPhone.

For microcontrollers, I'm solidly in the AVR camp, mostly because the open-source tools (avr-gcc, and avrdude) are great. I need another bloated IDE like I need soft memory errors. I don't do [Arduino][] because I know assembly and I'm a snob. I've been doing a lot of work with my own Atmega328 prototyping board I call the "[rotorboard](http://www.flickr.com/photos/headrotor/3534845287/ "A photo of the rotorboard.")." It is similar to an Arduino but with room for various drivers and an XBee wireless module. 

Hardware tools: A Weller [W51 soldering iron][wes51], a low-end [Tektronix 4-channel scope][tds2004b], a [Fluke 179 DMM][179]. An Aoyue hot-air station for SMD. I love [these strippers][se-94]. A cheapo power screwdriver, and because I'm getting to That Age, a magnifying visor.

### And what software?

Well, I've programmed everything from 1-bit microcontrollers to a Cray X-MP using everything from FORTRAN punch cards to [brainfuck][]. My tools have not changed much since grad school: [emacs][] for coding and print statements for debugging.

I depend on Unix tools -- [awk][], [grep][], [sed][], [bash][] -- for basic data munging. I've also been known to use the [C][] preprocessor to do silly things like generate printer art postscript files. I feel like I have the patience for perhaps one or two more bloated toolchain learning curves in my life: [Objective C][objective-c] may be one, VisualCsharp.net (or whatevertheheck it's called these days) is certainly not.

I am ideologically sympathetic to FOSS, so I am pleased to use [Inkscape][] and [Blender][] and [Octave][] rather than the considerably more pricey commercial equivalents. I'm also cheap so this is a double win. I use source control for backup. I run a [VisualSVN server][visualsvn-server] on my main Windows box (totally easy to set up!) and keep everything under source control (using [svn][subversion] under Linux and [TortoiseSVN][] under Windows). I update with a cron job from several machines so everything is redundant and in sync.

I use [EagleCAD][eagle] for board design. Autorouters pain my ninja-routing sensibilities so I don't use them (granted I don't think I've ever used a really good one). I try to stay away from gnarly analog and HF designs but when I can't there's LTspice for simulation.

Finally: [Python][] is just the bomb. I've been doing a lot of GUIs for [fun and profit](http://rotormind.com/projects/portfolio/rotorbryte/ "Jonathan's GUI projects.") and [wxFormBuilder][] plus [wxPython][] is just crazy nice. Check it out at [One Minute Python](http://www.oneminutepython.com/ "A guide for creating Python applications."). For embedded and bare-metal systems I'm still totally fine with C. Stuck with a crappy windows DLL and no source? Wrap it with Makepy.py and Robert is truly avuncular.

### What would be your dream setup?

Probably something like dual Apple [Cinema Displays][cinema-display], or even 42-inch plasma monitors. My own personal laser cutter. My presbyopia is getting worse while SMD chips are getting smaller and smaller, one of these days I'm going to get a pair of [these surgical telescopes][standard-field-telescopes]. Oh, even though my posture is decades away from being salvageable, a nice chair. Programmers like nice chairs.

[179]: https://www.fluke.com/en-us/product/electrical-testing/digital-multimeters/fluke-179 "A digital multimeter."
[arduino]: https://www.arduino.cc/ "Open-source prototyping hardware."
[awk]: https://en.wikipedia.org/wiki/AWK "Data formatting language/software."
[bash]: http://www.gnu.org/software/bash/ "A terminal shell."
[beagleboard]: http://web.archive.org/web/20230812104124/https://www.beagleboard.org/ "An open development hardware board."
[blender]: https://www.blender.org/ "A free, open-source 3D renderer."
[brainfuck]: https://en.wikipedia.org/wiki/Brainfuck "A minimalist programming language."
[c]: https://en.wikipedia.org/wiki/C_(programming_language) "A compiled programming language."
[chumby]: http://www.chumby.com/ "A little device that runs Flash applications."
[cinema-display]: https://en.wikipedia.org/wiki/Apple_Cinema_Display "An LCD display."
[cygwin]: http://www.cygwin.com/ "A Linux-like environment for Windows."
[eagle]: http://web.archive.org/web/20221006162604/https://www.cadsoft.io/ "Software for designing printed circuit boards."
[emacs]: http://www.gnu.org/software/emacs/ "An extensible, customizable, free/libre text editor — and more."
[grep]: http://www.gnu.org/software/grep/ "A command-line tool for pattern matching in files."
[inkscape]: https://inkscape.org/ "An open-source vector graphics program."
[iphone]: https://en.wikipedia.org/wiki/IPhone_(1st_generation) "A smartphone."
[marble-mouse]: https://support.logi.com/hc/en-us/articles/360025260314--Product-Gallery-Marble-Mouse "A trackball mouse."
[objective-c]: https://en.wikipedia.org/wiki/Objective-C "An object-oriented compiled language."
[octave]: https://octave.org/ "A language for numerical computations."
[pyosc]: https://github.com/ptone/pyosc "A Python implementation of Open Sound Control."
[python]: https://www.python.org/ "An interpreted scripting language."
[se-94]: http://web.archive.org/web/20230502111454/https://www.amazon.com/GB-SE-94-10-gauge-26-gauge-Automatic/dp/B00004WLL0 "Wire strippers/crimpers."
[sed]: http://www.gnu.org/software/sed/ "Text filtering software."
[standard-field-telescopes]: https://www.designsforvision.com/surghtml/SStdTel.htm "Magnifying telescopes used during surgery."
[subversion]: http://web.archive.org/web/20200706092702/http://subversion.tigris.org/ "A version control system."
[tds2004b]: https://www.testunlimited.com/productDetail.aspx?product_id=259 "An oscilloscope."
[tortoisesvn]: https://tortoisesvn.net/ "A Subversion client for Windows."
[touchosc-ios]: https://hexler.net/touchosc "An OSC and MIDI controller for iOS."
[ts-7260]: https://www.embeddedts.com/products/board-detail.php?product=TS-7260 "A single board embeddable computer."
[ubuntu]: https://ubuntu.com/ "A Unix distribution."
[virtualbox]: https://www.virtualbox.org/ "Open-source virtualisation software."
[visualsvn-server]: https://www.visualsvn.com/server/ "A Subversion server for Windows."
[wes51]: http://web.archive.org/web/20230315042353/https://www.amazon.com/Weller-WES51-Analog-Soldering-Station/dp/B000BRC2XU/ "A soldering station."
[windows-7]: https://en.wikipedia.org/wiki/Windows_7 "An operating system."
[wxformbuilder]: https://sourceforge.net/projects/wxformbuilder/ "A GUI for designing wxWidgets apps."
[wxpython]: https://www.wxpython.org/ "Python bindings for wxWidgets."
