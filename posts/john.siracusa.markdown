---
title: John Siracusa
summary: Programmer, writer (Ars Technica)
date: 2009-07-01
categories:
- developer
- mac
- writer
---

### Who are you, and what do you do?

I'm John Siracusa. I'm a programmer by day and a freelance [technology writer](http://arstechnica.com/author/john-siracusa/ "A list of John's articles on Ars Technica.") by night (and weekends).

### What hardware do you use?

My main machine is a 2x2.8 GHz [Mac Pro][mac-pro] (Early 2008) with 8 GB of RAM, dual optical drives, an NVIDIA GeForce 8800 GT video card, and 3.5 TB of disk space spread over four internal drives: two 1 TB Western Digital Caviar Blacks, a 1 TB Samsung Spinpoint F1, and the 500GB Western Digital Caviar Blue that came with the Mac.

It's connected to a 23-inch Apple [Cinema display][cinema-display] (the model right before the 24-inch LED display was introduced) and Creative Labs [GigaWorks T40 Premium 2.0][gigaworks-t40] speakers, plus a separate subwoofer left over from an old set of Labtec speakers. I use the Apple aluminum keyboard that came with the Mac Pro and a [Logitech MX300][mx-300] mouse. (I haven't used an Apple mouse since the one that came with my [Performa 6110CD][performa-6110cd].) I've also got a tiny i-rocks powered USB 2.0 hub.

The Mac is connected through a [D-Link DGS-2205][dgs-2205] 5-Port Gigabit Ethernet switch to an 802.11n [AirPort Extreme][airport-extreme] base station. (It's not the new dual-band model, unfortunately.) The AirPort, in turn, is connected to my gloriously symmetrical 20/20 Mbps [FiOS][] Internet connection. (I don't use the router that Verizon supplied; the AirPort connects directly to the FiOS [ONT](http://en.wikipedia.org/wiki/Optical_Network_Terminal#ONT "Wikipedia entry on ONT.") in the basement with 100 feet of Cat-6 cable.) An Epson [Stylus CX7800][stylus-cx7800] is also connected to the AirPort via USB.

The family laptop (ostensibly my wife's machine) is a 2.4 GHz 15-inch [MacBook Pro][macbook-pro] (Mid 2007) with 4 GB of RAM, a matte screen, and the stock 160 GB hard drive. It's intermittently connected via a FireWire 400 cable to a Western Digital Caviar 250 GB hard drive inside a Macally [PHR-100AF][] external drive enclosure.

Finally, I've got a 1G [iPod touch][ipod-touch] (16 GB), a 2G iPod touch (32 GB), a 1G [iPod shuffle][ipod-shuffle] (1 GB), a 2G iPod shuffle (1 GB), and a 3G [iPod][] (20 GB). I've also got a [Newton MessagePad 120][messagepad-120] on my desk as a decoration.

This is just the hardware that gets used on a daily basis. In the attic, I've got every Mac I've ever owned, all the way back to my original Mac 128k, in their original boxes, plus many, many more second-hand Macs and NeXT machines that I've acquired over the years, mostly from the [M.I.T swapfest](http://www.mitflea.com/ "The MIT flea markets site.").

One final hardware note. All those hard drives feed my paranoid backup regime. On the Mac Pro, the three 1 TB drives give me 1 TB of actual storage. I boot from and use the first drive, which is continuously backed up to the second drive using [Time Machine][time-machine]. All other volumes are unmounted until needed. I make a bootable backup of the first drive onto the third drive using [SuperDuper!][superduper] every few weeks. I also do an encrypted network backup using [Backblaze][]. (About 400 GB uploaded so far. FiOS!) The fourth drive is chopped up into several partitions for Boot Camp, prerelease OS installs, etc.

The laptop backup is simpler: periodic Time Machine backup to the 250 GB external drive via FireWire.

### And what software?

I do all of my programming and writing in [BBEdit][], which I've been using since version 2.1 (despite a brief dalliance with emacs when I was in college).

My second-most-frequently-typed-in application is [Terminal][]. It has few frills, but it gets the basics right: I can copy and paste long lines of text without incident, it supports UTF-8, "unlimited" scrollback length, bitmapped 9pt Monaco, and it never crashes. Sounds boring, but just try a few terminal emulators on other platforms to see how badly it can be botched.

For email, I use [Entourage][] which I've always viewed as the spiritual successor to [Claris Emailer][emailer], my first email love. I use it instead of Apple Mail because of its superior Exchange support (for work), its integrated calendar, which I use instead of [iCal][], and a huge number of little features: mailing list manager, custom columns on a per-folder basis, quote-aware text re-wrapping, etc.

My primary web browser has been [Safari][] since it was introduced, mostly due to the minimalist user interface and speed of non-rendering tasks (e.g., how long it takes to create a new, empty browser window). The fact that Safari 4 now also renders web pages and runs [JavaScript][] lightning-fast is just icing on the cake for me. (I'm still sore about what they did to the reload button, however. I'm using the [Safari 4 Reload Fix][safari-4-reload-fix] hack for now.) [Firefox][] is my secondary browser, and my primary [JavaScript debugger][firebug]. I also have [Camino][], [OmniWeb][], [Opera][], and the latest Mac builds of [Chrome][] and [Chromium][] installed.

Despite having all those web browsers, I do [most of my web browsing](http://arstechnica.com/staff/fatbits/2005/09/1200.ars "John's Ars Technica article, 'The state of Mac web browsing'.") indirectly via RSS/Atom feeds inside [NetNewsWire][]. I use [Colloquy][] for IRC. For IM, I use [Adium][] with a custom Colloquy-look-alike message theme that I created when I came over from [Fire][] a few years ago. My Twitter client of choice is [Twitterrific][], on both the Mac and the iPod.

I've been reducing my system customizations in recent years, but there are a few that I can't live without. [WindowShade X][windowshade-x] is the most significant, as my sole remaining [APE][] module. So-called "haxies" [get a bad rap](http://arstechnica.com/staff/fatbits/2006/02/2918.ars "John's Arc Technica article, 'Paths in the grass'."), but I seriously don't know what I would do without WindowShade.

[Quicksilver][] is my next essential. I assign it to command-spacebar instead of Spotlight. (Quicksilver used that key-combination first, after all.) I use Quicksilver solely as an application/file launcher (okay, and clipboard history tracker), with the "Bezel" interface appearance. I've tried [LaunchBar][] and a few others, but I always come back to Quicksilver. I want my launcher to appear, react to my input, and disappear instantly. Quicksilver has always felt the snappiest to me. I also want the UI to be in the middle of the screen, not up in a corner or near the menu bar.

If I could avoid using the Dock entirely, I would. But there's still no other way to get notifications (bouncing icons) or see a icon badge updates. So in addition to the Dock, I run [DragThing][] with two docks: a "process dock" growing down from the upper right corner, a la Mac OS 9, and a "folder dock" in the lower right corner containing my most frequently accessed folders. (I find the way that the Leopard Dock handles folders so disagreeable that I no longer have any folders in my Dock.)

I still have [ASM][] installed, but I rarely use it directly these days. I keep it running mostly for its "Classic Window Mode" which brings all windows belonging to an application forward when you click on any one of them, but (and this is the important part) *shift*-click suppresses the behavior. It's the best of both worlds. DragThing has a similar feature, but for now I'm sticking with ASM for this.

I also have the excellent [iStat Menus][istat-menus] installed so I can see the freaking date next to the time in the menu bar.

[Dropbox][] is recent addition to my "essentials" list. It works the way iDisk always should have. [Yojimbo][] with [MobileMe][mobile-me] syncing is the other half of my machine-independent "Big Wad o' Stuff" system. Anything of interest that I encounter during the day but don't have time to look at gets dumped into either Dropbox or Yojimbo (or a MobileMe-synced NetNewsWire tab).

[MacFUSE][] with [sshfs][] has really helped take the pain out of mounting remote volumes in recent years.

I use [VMware Fusion][vmware-fusion] for work and play. It's an amazingly Mac-like application for a first-time Mac developer, and it's been rock-solid for me. I've also got Windows XP installed on a [Boot Camp][boot-camp] partition for gaming.

On my iPod, I mostly bounce between [Twitterrific][twitterrific-ios], [Safari][safari-ios], and (sadly) [Peggle][peggle-ios]. (It was on sale for $0.99. I was powerless.)

Oh yeah, and what you're reading now was written (mostly) using MacSpeech [Dictate][dragon-dictate-mac]. A few decades of typing has left me with some significant [RSI](http://en.wikipedia.org/wiki/Repetitive_strain_injury "Wikipedia entry on RSI."), and speech recognition, for all its flaws and limitations, goes a long way towards mitigating the damage.

### What would be your dream setup?

My dream setup could be described as "more of what I already have." Bigger/more displays, more RAM, more hard disk space, a faster video card, faster network connection, etc. In particular, I really wanted to buy a 30-inch display with my Mac Pro, but couldn't bring myself to pay so much money for the "old" model with the [CCFL](http://en.wikipedia.org/wiki/Cold_cathode "Wikipedia entry on CCFL.") backlight. (Of course, here we are a year later and there's still no 30-inch LED-backlit Apple display.) I'd also like a big, fast pool of fault-tolerant network-attached storage hidden somewhere in my basement.

On the software side, I have [so many complaints](http://arstechnica.com/staff/fatbits/2009/05/hypercritical.ars "John's complaints post.") about every application that I use, even (*especially*) the ones I love the most, it's hard to know where to begin. I guess I'd start with a version of NetNewsWire with much better syncing features. (Only MobileMe syncing will sync NetNewsWire browser tabs, and that feature is going away soon.) An arbitrary number of window splitters in BBEdit and Terminal would also be nice. That's just two off the top of my head, but I think I'd better stop there.

[adium]: https://en.wikipedia.org/wiki/Adium "A multi-protocol chat application for the Mac."
[airport-extreme]: https://en.wikipedia.org/wiki/AirPort_Extreme "A wireless access point."
[ape]: https://en.wikipedia.org/wiki/Application_Enhancer "A Mac OS X framework and system daemon for loading haxies."
[asm]: https://download.cnet.com/ASM/3000-2094_4-10058963.html "A menu-based application switcher for Mac OS X."
[backblaze]: https://www.backblaze.com/cloud-backup.html "Online backup."
[bbedit]: http://www.barebones.com/products/bbedit/ "A text editor for the Mac."
[boot-camp]: https://en.wikipedia.org/wiki/Boot_Camp_(software) "Software to allow Macs to run Windows natively."
[camino]: http://caminobrowser.org/ "An alternative Mac browser based on Gecko."
[chrome]: https://www.google.com/intl/en/chrome/browser/ "A WebKit-based browser, where each tab runs in its own thread."
[chromium]: http://www.chromium.org/ "Open-source builds of the Chrome web browser."
[cinema-display]: https://en.wikipedia.org/wiki/Apple_Cinema_Display "An LCD display."
[colloquy]: http://colloquy.info/ "An IRC client for the Mac."
[dgs-2205]: https://www.amazon.com/D-Link-DGS-2205-5-Port-Desktop-Switch/dp/B000FIVDIA "5-port Gigabit switch."
[dragon-dictate-mac]: https://en.wikipedia.org/wiki/DragonDictate "Speech-recognition software."
[dragthing]: https://dragthing.com/ "A popular dock application for the Mac."
[dropbox]: https://www.dropbox.com/ "Online syncing and storage."
[emailer]: https://en.wikipedia.org/wiki/Claris_Emailer "An email client for the Mac."
[entourage]: https://en.wikipedia.org/wiki/Microsoft_Entourage "A Mac email client included with Office."
[fios]: https://www.verizon.com/home/fios/ "Fibre optic Internet connection."
[fire]: https://en.wikipedia.org/wiki/Fire_(instant_messaging_client) "A multi-protocol chat client for the Mac."
[firebug]: https://getfirebug.com/ "A Firefox addon for web development."
[firefox]: https://www.mozilla.org/en-US/firefox/new/ "A cross-platform open-source web browser."
[gigaworks-t40]: https://www.amazon.com/Creative-Labs-GigaWorks-Multimedia-Technology/dp/B00113V748 "Compact computer speakers."
[ical]: https://en.wikipedia.org/wiki/Calendar_(Apple) "The calendar software included with macOS."
[ipod-shuffle]: https://www.apple.com/ipod-shuffle/ "A very small music player."
[ipod-touch]: https://www.apple.com/ipod-touch/ "It's like an iPhone, without the phone bit."
[ipod]: https://www.apple.com/ipod/ "A music player."
[istat-menus]: https://bjango.com/mac/istatmenus/ "A collection of Mac OS X menu items for monitoring your system."
[javascript]: https://en.wikipedia.org/wiki/JavaScript "An interpreted scripting language."
[launchbar]: https://www.obdev.at/products/launchbar/index.html "An application launcher and data manager for the Mac."
[mac-pro]: https://www.apple.com/mac-pro/ "The Intel-based Mac tower computer."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[macfuse]: https://code.google.com/archive/p/macfuse "A system for adding third-party file systems to Mac OS X."
[messagepad-120]: https://everymac.com/systems/apple/messagepad/stats/newton_mp_120.html "A much-loved PDA device."
[mobile-me]: https://en.wikipedia.org/wiki/MobileMe "An online 'cloud' service (mail, calendar, etc)."
[mx-300]: https://www.amazon.com/Logitech-930672-0403-300-Optical-Mouse/dp/B00006HMPJ "An optical mouse."
[netnewswire]: https://en.wikipedia.org/wiki/NetNewsWire "A popular feed reader for the Mac."
[omniweb]: https://en.wikipedia.org/wiki/OmniWeb "An alternative Mac browser based on WebKit."
[opera]: http://web.archive.org/web/20221227050003/https://www.opera.com/ "A cross-platform web browser."
[peggle-ios]: https://itunes.apple.com/app/peggle/id314303518 "A terribly addictive peg-popping game."
[performa-6110cd]: http://www.everymac.com/systems/apple/mac_performa/specs/mac_performa_6110cd.html "An old PPC-based Mac."
[phr-100af]: https://www.amazon.com/Macally-PHR-100AF-FireWire-External-Enclosure/dp/B0001UEHI0 "An external Firewire hard drive enclosure."
[quicksilver]: https://qsapp.com/ "A data manipulator and launcher for the Mac."
[safari-4-reload-fix]: http://earthlingsoft.net/ssp/tidbits/#safari4reloadfix "A hack to change the 'Add Bookmark' button into a 'Reload' button."
[safari-ios]: https://en.wikipedia.org/wiki/Safari_(web_browser)#iOS-specific_features "A web browser included with iOS."
[safari]: https://www.apple.com/safari/ "A fast web browser."
[sshfs]: https://code.google.com/archive/p/macfuse/wikis/MACFUSE_FS_SSHFS.wiki "An SSH file system for MacFUSE."
[stylus-cx7800]: http://www.epson.com/cgi-bin/Store/consumer/consDetail.jsp?BV_UseBVCookie=yes&oid=56291070&modeloid=58773&infoType=Overview "An all-in-one printer/copier/scanner."
[superduper]: http://shirt-pocket.com/SuperDuper/SuperDuperDescription.html "An excellent Mac backup/cloning application."
[terminal]: https://en.wikipedia.org/wiki/Terminal_(OS_X) "A console application included with Mac OS X."
[time-machine]: https://en.wikipedia.org/wiki/Time_Machine_(Mac_OS) "Backup software for the masses, included with Mac OS X 10.5."
[twitterrific-ios]: https://itunes.apple.com/WebObjects/MZStore.woa/wa/viewSoftware?id=284540316&mt=8 "A Twitter client."
[twitterrific]: https://twitterrific.com/mac "A Twitter client for the Mac."
[vmware-fusion]: http://web.archive.org/web/20221223060906/https://www.vmware.com/products/fusion.html "A PC emulator for the Mac."
[windowshade-x]: https://www.macupdate.com/app/mac/6485/windowshade-x "A Mac haxie to customise window minimising."
[yojimbo]: http://www.barebones.com/products/Yojimbo/ "Data 'bucket' software for the Mac."
