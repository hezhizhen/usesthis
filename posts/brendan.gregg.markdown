---
title: Brendan Gregg
summary: Senior performance architect (Netflix)
date: 2014-07-15
categories:
- bsd
- developer
- linux
- mac
- windows
---

### Who are you, and what do you do?

I'm [Brendan Gregg](http://www.brendangregg.com "Brendan's website."), I'm a senior performance architect at [Netflix][], and do large scale computer performance design, analysis, and tuning. Performance tuning improves the customer experience and saves the company money, by doing more with fewer resources. I also write technical books, contribute to open source projects, and speak at technical conferences as a performance expert. This year I gave the keynote at [SCaLE](http://www.socallinuxexpo.org/ "The Southern California Linux Expo site."), the Southern California Linux Expo, on Linux and Solaris performance differences.

### What hardware do you use?

I'm currently using an Apple [MacBook Pro][macbook-pro] Retina 15 inch as my work computer, connected to a 27-inch Apple [Thunderbolt monitor][thunderbolt-display] when I'm at my desk. Apple products in the past have been very reliable, which is what I'm after. I use the DVORAK keyboard layout, for efficiency and performance. The keys are still labeled QWERTY, which I ignore.

I have a menagerie of very old computers for doing personal IT projects or hobbies. These used to be mostly desktop PCs and servers, but they took up too much room and power, and so they became mostly laptops. I'll eventually toss them out too, and they'll be mostly virtual [VirtualBox][] instances or AWS [EC2][] instances.

One of my favorite laptops is a pink Acer Aspire One, with a 9-inch display, a 1.60 GHz Intel Atom processor, running [Windows XP][windows-xp]. It's cute. I don't use Windows much, so I use that for a fun excursion to another planet. It has some performance tools on it I was writing in [PowerShell][windows-powershell].

My only other Windows laptop, a Compaq, is for [Microsoft Flight Simulator][microsoft-flight-simulator]. With that I use CH Products rudder pedals, the Saitek throttle quadrant, and [Logitech Extreme 3D Pro joystick][extreme-3d-pro-joystick]. When I have the time, I'd like to build custom instruments and controls, and I've been collecting bits and pieces of hardware for that work.

I have a couple of PCs I was using for doing bare-metal server work, although these days I'm doing most of my work on the cloud instead. All of my personal computers may, via VirtualBox and EC2, be consolidated to run from a single 13-inch [MacBook Air][macbook-air], which would be great. I'd like to own fewer things if possible.

I do own many retro consoles. These include [Atari 2600s][atari-2600], [C64s][commodore-64], [N64s][n64], and [PS2][] slimlines (in particular as backups, in case the CD-ROM drive dies). It's hard to emulate these, especially the C64 music chips (the SID6581 and MOS8580).

As for other hardware, I use a [Fujifilm X-A1][x-a1] for photographs, and wear a [Casio AL-180][al-180] for the time. The Casio is indestructible, and requires no batteries. I also take a lot of notes on paper, and write with different instruments. These days, often with a 0.5mm [Uni-ball Kuru Toga mechanical pencil][kuru-toga], which auto-rotates the lead to keep it sharp.

### And what software?

Operating systems I used today are [OS X][macos] for the Macbooks, and Linux and [FreeBSD][] for servers. I was doing a lot with [Solaris][], [OpenSolaris][], and [SmartOS][], but not anymore. 

On my Macbook I usually have [Activity Monitor][activity-monitor] running to keep an eye on CPU resources, and [Temperature Monitor][temperature-monitor] Lite to keep an eye on GPU utilization, inferred by its temperature. Temperature Monitor Lite stopped working for the recent versions of OS X, so I've been figuring out GPU utilization by touching above the 1 and 2 keys and feeling the temperature.

If I notice performance issues on OS X, apart from Activity Monitor, I'll use a variety of [DTrace][] tools to figure out what's going on. That's an advantage for me for using Macbooks -- OS X has DTrace, which lets me do immediate advanced debugging. I use DTrace tools including [iosnoop][] and [execsnoop][], which are tools I originally wrote, and are shipped with OS X by default.

I use a lot of somewhat standard software. For word processing, I do a lot of my writing in the [vim][] text editor. I wrote my last book in vim, for the drafts, before they become [OpenOffice][] and [Word][] documents, which I use as well. I was writing a lot of presentations in [Keynote][], but snap-to-grid issues for a very popular Linux performance tools diagram I drew have driven me crazy, so I'm trying [OmniGraffle][] instead. For image editing, I try to hack first in OS X [Preview][], for the convenience, before moving to [ImageMagick][] and [GIMP][]. GIMP for pixel pushing, ImageMagick for various transforms.

For browsers, I like to use [Opera][], [Firefox][], and [Chrome][], moving tabs between them to balance load. I usually have over one hundred tabs open in Firefox, which organizes what I'm working on and articles I need to read. Firefox handles the tab load well, except for when some begin to burn CPU, which are much harder to find in Firefox than Chrome and Opera which have task managers. For Firefox I can usually figure out the problem tabs using DTrace to dynamically instrument various functions.

I'm logged into IRC 24x7, using [irssi][] in a screen session, an approach I've been using for over ten years. I also use [Adium][] and [HipChat][], for talking over other protocols.

For one-off programs, I often find [awk][] quick and sufficient, then shell or [Perl][]/[Python][] as needed. For shell scripts, I like to use [ksh93][kornshell], but generally stick to ksh88 functionality. For complex data processing, I'll either write programs in awk/[C][]/Perl/Python, or use [R][] or [gnuplot][]. And for server software, C, [Java][], or [node.js][].

For performance tools, I use everything, which is part of my job. On Linux, that includes [top][], [vmstat][], [iostat][], [mpstat][], [sar][], [nicstat][], [strace][], [tcpdump][], and [perf_events][perf]. And plenty of unstable or in-development tools, including [ktap][], [SystemTap][], and [sysdig][]. I often need to write my own tools to answer the performance questions I have, and I've published a few hundred in the past, many for DTrace. 

I spent a lot of time in [Terminal][], with many tabs open. Many of these are ssh sessions to remote servers, where I'll often use [screen][] for managing sessions. Some are [CScope][] sessions to various code repositories I keep handy.

If I need to concentrate and shut out distractions, I'll put on headphones and listen to a few different audio sources. Usually [SIDPLAY][] playing HVSC, and a noisy keyboard program (I've alternated between versions I write myself, and 3rd party ones). It helps me concentrate. I used to include KSFO tower ATC a lot as well (playing at the same time). Over the bridge for two eight right...

### What would be your dream setup?

Probably something like a 15-inch MacBook Air with at least 1 TB of flash storage, and enough CPU to run several VirtualBox instances. It'd probably run OS X, but with various bug fixes so that it never panic'd. I'd also be able to use the thing without having to agree to lengthy Apple T&Cs.

For flight simulators, I'd like a computer with enough GPU horsepower to run [X-Plane][] 10 with insane levels of detail enabled, and without the GPU melting. I'd use this for a sit-in flight simulator, with authentic controls and instruments.

I'd also like to have a small data projector aimed at the ceiling above my bed, and then an easy keyboard device - maybe a split keyboard with DVORAK - so that I can catch up on email or reading as I fall asleep.

[activity-monitor]: https://en.wikipedia.org/wiki/Activity_Monitor "A process monitor application included with Mac OS X."
[adium]: https://en.wikipedia.org/wiki/Adium "A multi-protocol chat application for the Mac."
[al-180]: http://www.digital-watch.com/DWL/1work/casio-al-180/ "A solar-powered wristwatch."
[atari-2600]: https://en.wikipedia.org/wiki/Atari_2600 "A gaming console."
[awk]: https://en.wikipedia.org/wiki/AWK "Data formatting language/software."
[c]: https://en.wikipedia.org/wiki/C_(programming_language) "A compiled programming language."
[chrome]: https://www.google.com/intl/en/chrome/browser/ "A WebKit-based browser, where each tab runs in its own thread."
[commodore-64]: https://en.wikipedia.org/wiki/Commodore_64 "An 8-bit computer."
[cscope]: http://cscope.sourceforge.net/ "A command-line tool for browsing source code."
[dtrace]: https://en.wikipedia.org/wiki/DTrace "Tracing software."
[ec2]: https://aws.amazon.com/ec2/ "A web service for virtualised processing."
[execsnoop]: http://www.brendangregg.com/DTrace/execsnoop "Command-line software for watching process execution."
[extreme-3d-pro-joystick]: https://gaming.logitech.com/en-us/product/extreme-3d-pro-joystick "A joystick."
[firefox]: https://www.mozilla.org/en-US/firefox/new/ "A cross-platform open-source web browser."
[freebsd]: https://www.freebsd.org/ "An open source operating system."
[gimp]: https://www.gimp.org/ "An open-source image editor."
[gnuplot]: http://www.gnuplot.info/ "A command-line graphing tool."
[hipchat]: http://web.archive.org/web/20170905004635/https://www.hipchat.com/ "A hosted IM and file service."
[imagemagick]: http://www.imagemagick.org/script/index.php "Image editing and converting software."
[iosnoop]: http://www.brendangregg.com/DTrace/iosnoop "Command-line software for monitoring disk I/O."
[iostat]: https://en.wikipedia.org/wiki/Iostat "A command-line tool for monitoring disk and network I/O."
[irssi]: https://irssi.org/ "A CLI irc client."
[java]: http://web.archive.org/web/20221226094350/https://www.java.com/en/ "A cross-platform compiled programming language."
[keynote]: https://www.apple.com/keynote/ "Presentation software for the Mac."
[kornshell]: http://www.kornshell.org "A command-line shell."
[ktap]: http://www.ktap.org/ "A command-line kernel tracing tool."
[kuru-toga]: https://www.amazon.com/Uni-Roulette-Rotation-Mechanical-Pencil/dp/B004OHNTVC "A mechanical pencil with a rotating lead system."
[macbook-air]: https://www.apple.com/macbook-air/ "A very thin laptop."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[macos]: https://en.wikipedia.org/wiki/MacOS "An operating system for Mac hardware."
[microsoft-flight-simulator]: https://en.wikipedia.org/wiki/Microsoft_Flight_Simulator "A flight simulator game."
[mpstat]: https://en.wikipedia.org/wiki/Mpstat "A command-line tool for showing statistics about running processes."
[n64]: https://en.wikipedia.org/wiki/Nintendo_64 "A 64-bit gaming console."
[netflix]: http://web.archive.org/web/20221226033709/https://www.netflix.com/ "A movie rental and streaming service."
[nicstat]: http://www.brendangregg.com/index.html#Software "A command-line network monitoring tool."
[node.js]: https://nodejs.org/en/ "A Javascript application platform."
[omnigraffle]: https://www.omnigroup.com/omnigraffle/ "Diagramming software for the Mac."
[openoffice]: http://www.openoffice.org/ "An open-source office suite."
[opensolaris]: https://www.oracle.com/technetwork/server-storage/solaris11/overview/index.html "A free operating system based on Solaris."
[opera]: http://web.archive.org/web/20221227050003/https://www.opera.com/ "A cross-platform web browser."
[perf]: https://en.wikipedia.org/wiki/Perf_(Linux) "A command-line kernel performance analyser."
[perl]: https://www.perl.org/ "An interpreted scripting language."
[preview]: https://en.wikipedia.org/wiki/Preview_(macOS) "An image viewer included of macOS."
[ps2]: https://en.wikipedia.org/wiki/PS_2 "A gaming console."
[python]: https://www.python.org/ "An interpreted scripting language."
[r]: http://www.r-project.org/ "Software for statistical computing and graphics."
[sar]: https://en.wikipedia.org/wiki/Sar_(Unix) "A command-line system monitor."
[screen]: http://www.gnu.org/software/screen/ "Think of it as tabs for your *nix terminal."
[sidplay]: http://www.sidmusic.org/sidplay/mac/ "A Commodore 64 music player for the Mac."
[smartos]: https://www.joyent.com/smartos "An operating system."
[solaris]: http://www.oracle.com/us/products/servers-storage/solaris/resources/index.html "An operating system."
[strace]: https://en.wikipedia.org/wiki/Strace "A command-line tool for monitoring system calls."
[sysdig]: http://web.archive.org/web/20200414123559/http://www.sysdig.org/ "A command-line profiling and monitoring tool."
[systemtap]: https://en.wikipedia.org/wiki/SystemTap "A command-line instrumenting tool."
[tcpdump]: http://www.tcpdump.org/ "A command-line tool for analysing packets."
[temperature-monitor]: http://www.bresink.com/osx/TemperatureMonitor.html "Mac software for reading the temperature sensors inside Apple computers."
[terminal]: https://en.wikipedia.org/wiki/Terminal_(OS_X) "A console application included with Mac OS X."
[thunderbolt-display]: https://www.apple.com/displays/ "A Thunderbolt-powered monitor."
[top]: https://en.wikipedia.org/wiki/Top_(software) "A command-line tool for listing running processes."
[vim]: https://www.vim.org/ "A command-line text editor."
[virtualbox]: https://www.virtualbox.org/ "Open-source virtualisation software."
[vmstat]: https://en.wikipedia.org/wiki/Vmstat "A command-line system monitoring tool."
[windows-powershell]: https://en.wikipedia.org/wiki/Windows_PowerShell "A shell and scripting language for Windows."
[windows-xp]: https://en.wikipedia.org/wiki/Windows_XP "An operating system for x86 computers."
[word]: https://products.office.com/en-us/word "A document editor."
[x-a1]: http://www.fujifilm.com/products/digital_cameras/x/fujifilm_x_a1/ "A 16.3 megapixel digital camera."
[x-plane]: https://en.wikipedia.org/wiki/X-Plane_(simulator) "Flight simulator software."
