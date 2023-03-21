---
title: Timothy Wood
summary: CTO and co-founder (The Omni Group)
date: 2014-02-27
categories:
- developer
- mac
---

### Who are you, and what do you do?

I'm Tim Wood, one of the founders and the CTO of [The Omni Group](https://www.omnigroup.com/ "The Omni Group's website."). I work with developers on all our product teams as needed, and our frameworks for Mac and iOS. My most recent projects have been [OmniPresence][], our new document syncing system, [OmniOutliner 2 for iPad][omnioutliner-ios], and [OmniOutliner 4][omnioutliner].

### What hardware do you use?

My main work machine is a [15" Retina MacBook Pro][macbook-pro]. At the office, it is attached to a [27" Thunderbolt display][thunderbolt-display] on a VESA arm. Next to that, is a [Mac Pro][mac-pro] with a [30" Cinema Display][cinema-display], and a couple iPads for testing document synchronization. In our recent office move, we switched over to adjustable height desks, so I typically work standing in the morning and sit down after lunch. Also tucked away in my office is a [Mac Mini][mac-mini] with an attached [Drobo][], acting as a [CrashPlan][] server for itself, my laptop, Mac Pro and (importantly) my home machines. Finally, there is my 5.1 system, NHT speakers all around, and a Rega turntable. During the construction of our new space, extra sound insulation may have been added to my office...

At home, I use a Mac Pro and a 30" Cinema Display. It's slower than the laptop these days, but has a huge display and bulk storage for family videos and pictures. I have a new Mac Pro on order, but haven't decided when to get a 4K display yet.

My wife is a photographer and musician, so she generates a fair bit of data that needs backing up. This gets stored on a Mac mini with a Pegasus Thunderbolt RAID, and then cloned via [SuperDuper!][superduper] to 3TB drives in a [drive dock][voyager-s3], which I rotate back to the office. It also gets backed up to CrashPlan's server *and* to the previously mentioned CrashPlan server at the office. We have various other [Time Machine][time-machine] drives for each workstation.

### And what software?

The vast majority of my time is spent in [Xcode][] and [Terminal][] ([zsh][], but [fish][] looks like it merits a try). We have some internal applications for bug tracking and monitoring our continuous build system that I always have running, as well as most of our published applications.

I use [TextMate 2][textmate] for random scripting and viewing small diffs, with [Kaleidoscope][] for larger diffs. [1Password][] is indispensable for keeping track of long random secure passwords. [FastScripts][] gets daily use for kicking off repetitive tasks (like automatically archiving read messages in [Mail][]). [Alfred][] is my app launcher of choice. [BusyCal][] holds my calendar. Whenever I need to edit images, I go to [Acorn][]. And, while working on AppleScript support in our apps, [Script Debugger][script-debugger] is amazingly useful.

Finally, for open source package management, I'm currently using [homebrew][].

### What would be your dream setup?

Refreshing the Mac Pro is a nice step, but there is still a lot of room left for improvement. I'm a big fan having my laptop always with me, and always up to date. Cloud storage and sync is great for some sorts of documents, but doesn't really help for in-progress changes to source code. I could do some silly dance to commit to a personal branch each time I want move between machines, but that is enough pain that I don't bother most of the time.

Instead, I would love the ability to simply connect a 20Gbps Thunderbolt 2 cable between my laptop and Mac Pro and suddenly have it gain super powers. Apple's multi-core toolkit ([GCD](http://developer.apple.com/library/ios/#documentation/Performance/Reference/GCD_libdispatch_Ref/Reference/reference.html "The documentation for the Grand Central Dispatch system.")) could gain the ability to handle side-effect free tasks on the external CPUs with application provided services ([XPC](http://developer.apple.com/library/mac/#documentation/MacOSX/Conceptual/BPSystemStartup/Chapters/CreatingXPCServices.html "The documentation for the XPC services API.")) that get copied to and run on the box. Unplug your laptop and any in-flight operations just get restarted locally in the laptop. On the display side, the system could switch to queuing commands for rendering on the Mac Pro GPUs to its attached display while the laptop remains closed.

On the storage front, there are several things I'd love to see:

* Touch sensitive connectors for removable storage. Grab the connector and ejection is requested automatically, with visual and audible (or haptic!) feedback indicating you can safely disconnect. Even better, maybe we could have filesystems and software that supported anytime ejection!
  
* Consumer-grade bulk storage that protects against [silent corruption](http://storagemojo.com/2007/09/19/cerns-data-corruption-research/ "A post about CERN's data corruption research."). I might break down and get a rack-mount [FreeNAS][] box for [ZFS](http://en.wikipedia.org/wiki/ZFS "The Wikipedia entry for ZFS.") at home, but with the size of consumer storage it seems crazy that every OS doesn't have end-to-end checksum validation and self-healing. Cloud storage would solve some of this, but it is too expensive for many people with large data sets (read: lots of photos of kids).

* A filesystem with snapshots supporting diffing (ZFS or otherwise), copy-on-write, and predicated commits (like [Software Transactional Memory](http://en.wikipedia.org/wiki/Software_transactional_memory "The Wikipedia entry for software transactional memory.")). Hacks like [NSFileCoordinator](https://developer.apple.com/library/mac/#documentation/Foundation/Reference/NSFileCoordinator_class/Reference/Reference.html "The documentation for Cocoa's NSFileCoordinator class.") and [FSEvents](https://developer.apple.com/library/mac/#documentation/Darwin/Conceptual/FSEvents_ProgGuide/Introduction/Introduction.html "The documentation for FSEvents.") are full of edge cases and tradeoffs that make writing syncing and backup software (or really, any software that deals with files) harder than it should be.

[1password]: https://1password.com "Password management software for Mac OS X."
[acorn]: https://flyingmeat.com/acorn/ "An image editor for the Mac."
[alfred]: https://www.alfredapp.com/ "A launcher app for the Mac."
[busycal]: http://www.busymac.com/busycal/ "Advanced calendar software for Mac OS X."
[cinema-display]: https://en.wikipedia.org/wiki/Apple_Cinema_Display "An LCD display."
[crashplan]: https://www.crashplan.com/en-us/ "An online backup service."
[drobo]: http://en.wikipedia.org/wiki/Drobo#Overview "A hardware-based backup system."
[fastscripts]: https://red-sweater.com/fastscripts/ "System-wide access to Applescripts, for the Mac."
[fish]: http://fishshell.com/ "A command-line shell."
[freenas]: https://www.freenas.org/ "Network Attached Storage software."
[homebrew]: http://brew.sh "Command-line package manager for Mac OS X."
[kaleidoscope]: https://www.kaleidoscopeapp.com/ "A file and image diff app for the Mac."
[mac-mini]: https://www.apple.com/mac-mini/ "A small desktop computer."
[mac-pro]: https://www.apple.com/mac-pro/ "The Intel-based Mac tower computer."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[mail]: https://en.wikipedia.org/wiki/Mail_(application) "The default Mac OS X mail client."
[omnioutliner-ios]: https://itunes.apple.com/us/app/omnioutliner-2/id704610906 "A to-do/task management software app."
[omnioutliner]: https://www.omnigroup.com/omnioutliner/ "To-do/task management software for Mac OS X."
[omnipresence]: https://www.omnigroup.com/omnipresence/ "Cloud syncing software."
[script-debugger]: https://latenightsw.com/sd4/ "An AppleScript IDE for the Mac."
[superduper]: http://shirt-pocket.com/SuperDuper/SuperDuperDescription.html "An excellent Mac backup/cloning application."
[terminal]: https://en.wikipedia.org/wiki/Terminal_(OS_X) "A console application included with Mac OS X."
[textmate]: https://macromates.com/ "A text editor for the Mac."
[thunderbolt-display]: https://www.apple.com/displays/ "A Thunderbolt-powered monitor."
[time-machine]: https://en.wikipedia.org/wiki/Time_Machine_(Mac_OS) "Backup software for the masses, included with Mac OS X 10.5."
[voyager-s3]: https://www.amazon.com/NewerTech-Voyager-Revision-Docking-Solution/dp/B007TTQQIA "A hard drive docking system."
[xcode]: https://en.wikipedia.org/wiki/Xcode "An IDE for Mac developers."
[zsh]: https://www.zsh.org/ "An interactive shell and scripting language."
