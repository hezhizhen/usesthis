---
title: Jesse Vincent
summary: Developer, CTO of Keyboardio
date: 2015-06-30
categories:
- developer
- hacker
- linux
- mac
- windows
credits:
  name: Julian Cash
---

### Who are you, and what do you do?

I'm Jesse Vincent, and I make stuff. I've spent most of my career writing software of one kind or another, though for the past two years, I've primarily been working on hardware.

I'm co-founder and CTO of [Keyboardio](http://www.keyboard.io/ "Jesse's keyboard startup."), a boutique keyboard startup. We're making a gorgeous hackable ergonomic keyboard, the Model 01. This all started off as a hobby. After my last startup cratered, I decided to take a year off to screw around. Somewhere in there, I discovered that making your own keyboard was kind of a thing and decided to give it a try. Not that I knew how to design circuit boards, solder, laser cut, 3D print or CNC mill things. Somewhere a couple months in, people in cafes started to ask where they could buy my keyboard. I blogged about it. A few days later, there were a thousand people on our waitlist. The rest, as they say, is history.

### What hardware do you use?

Right now, I'm typing this on my prototype Keyboardio Model 01 keyboard. It features a split layout that echos how your fingers actually move, mechanical keyswitches and a CNC-milled hardwood enclosure.

My primary computer these days is a late-2013 Core i5 [Retina MacBook Pro][macbook-pro] with 16 gigs of ram and 500 gigs of SSD. Primarily, it runs [OS X][macos], though for reasons I'll get into later, I've got [Boot Camp][boot-camp] set up with [Windows 8.1][windows-8] as well. The SD slot on the MacBook is cute little[ 64GB Transcend JetDrive Lite][jetdrive-lite] with an [Ubuntu 14.10][ubuntu] install.

When I'm working at a table or desk, the laptop is perched on a [Roost][] laptop stand. The Roost keeps my laptop screen at eye-height. It's laser-cut from carbon fiber and folds down to almost nothing. Combined with the keyboard in my lap, I've got a reasonably ergonomic setup that fits in my laptop bag and takes less than a minute to set up in a cafe.

The Model 01 has some basic mousing functionality, but whenever I'm doing something at all mouse-intensive, I'll switch over to the [Logitech Wireless Trackball][wireless-trackball-m570]. I've never found trackpads all that comfortable and the Trackman Marble series are the most reasonable trackballs I've used to date.

CAD software is still somewhat painful for me with a trackball. It turns out that when you're trying to work with 3D objects, having a 2D mouse...just isn't quite enough. Over the past few weeks, I've been trying to get used to a [3DConnexion SpaceNavigator for Notebooks][spacenavigator-notebook]. It lives in my gear bag, but doesn't seem to be coming out most days. I'm not sold on it yet.

At home, an [iMac][], [Cinema Display][cinema-display] and [Drobo][] live on a sit-stand desk from [GeekDesk][] that I mostly leave in the sitting position. More often than not, the iMac plays the role of a TV while I solder or do actual work on the MacBook.

My phone is an [iPhone 6][iphone-6] with a [Typo2 hard keyboard case][typo2] from Typo keyboards. It's not a great phone keyboard, but it does happen to be the best phone keyboard for a non-Blackberry one can get these days.

Lately, I seem to have given up on tablets in favor of the [Kindle Voyage][kindle-voyage]. There's something remarkably liberating about reading on a device I can't check my email on.

The iPhone definitely lasts longer than my Android phone did, but I still find myself traveling with a USB battery 'just in case'. I've run through a variety of USB batteries. So far, I've managed to wreck every single one I've used.

Now for the hardware hacker stuff. Readers should keep in mind that I'm a self-taught novice. I may use or recommend completely nutty things.

I have two versions of the hardware setup. The good setup is at home. The crazy TSA-safe travel setup fits in a little [AmazonBasics zipcase][amazonbasics-universal-travel-case]. I'll try to detail them separately.

At home, the soldering iron is a [Weller WES51][wes51]. It's nothing fancy, but hasn't done me wrong. That's paired with a [solder sucker][solder-sucker] and a cheap [brass wire sponge tip cleaner][brass-sponge-solder-tip-cleaner] and a big, heavy [Panavise][pv-201] for holding boards while working. The only screwdriver set I find I need is the [iFixIt 54 bit driver kit][54-bit-driver-kit]. I have a variety of pliers and wirecutters and a half-dozen sets of tweezers in various stages of destruction.

I use a fairly basic [multimeter][ex330]. I've recently advanced to the point where I can use it for something more advanced than just beeping when there's electrical conductivity between the two probes.

The setup at home is completed by drawers and drawers of electrical components and supplies.

The travel setup gets me derisive looks from hardware hackers and impressed looks from software folks for the same bit of kit: A battery-powered Hakko soldering iron. (In general, battery-powered soldering irons are really bad at maintaining an accurate temperature. When pros go portable, they seem to go for TSA-antagonizing [butane-powered soldering irons][solderpro-50].) The iron's saving grace is that airport security screeners don't bat an eyelash at it. Paired with a solder sucker and some super-fine solder, I'm pretty well set up to effect electronics repairs on a park bench. (It turns out that hotels frown on soldering in your room. Don't ask.)

The multimeter is a $5 item I picked up at [GuangHua Digital Plaza](http://www.gh3c.com.tw/ "A six story electronics market in Taipei.") in Taipei. The travel tweezers live on my keychain along with the screwdriver and knife of last resort, a [Swiss+Tech Utili-Key][utili-key]. A [DSO Nano v3][dso-nano-v3] digital oscilloscope the size of a deck of cards has recently joined the kit. A few [Arduino Micros][arduino-micro] and a [USB voltage/amp meter][usb-mini-charger-doctor] come in handy more often than I'd care to admit.

Non-hardware-hacking things in the travel kit include spare MicroUSB cables, a fast-charging USB wall plug, a [PortaPow USB condom][fast-charge-data-block-usb-adaptor], a couple SD cards and a USB stick or two. The PortaPow does something pretty simple - it severs the data line on a USB connection. This makes it much harder for a malicious host to pwn your device when you plug it in to grab a few spare electrons. More practically, it tricks your device into charging much faster because it believes it's connected to a wall plug rather than a computer.

### And what software?

I've been living my life on the command-line for... a very long time. Many of my workflows are very... terminal-centric. I'm writing my responses to this interview in 'note', a shell script I've been using instead of [Evernote][] for a good few years:

    cd ~/Dropbox/notes && vi `date +%Y-%m-%d`-$1`

'note' has recently been supplemented by [Notational Velocity][notational-velocity], which syncs to [Simplenote][simplenote-ios] on my iPhone.

Rather than [imgur][] and a pastebot, I use another [tiny script](https://github.com/obra/bin/blob/master/tempfiler "Jesse's custom image-sharing script on GitHub.").

My personal todo list lives in a todo.txt file that I manage with [todo.sh][], aliased to 't'.

My [zsh][] prompt is one of those godawful full-color monstrosities courtesy of [oh-my-zsh][]. I jump between directories using '[z][]'.

A lot of my old-skool Internet life still lives in a [screen][] session on a server. I read personal mail in [mutt][], chat on IRC with [irssi][] and chat with MIT zephyr folks in [BarnOwl][]. I connect to the server with [Mosh][], which smooths out bad internet connections and gracefully reconnects when I change networks or put my MacBook to sleep.

Reading across my menubar:

- [Pomodoro][] keeps me on task, 25 minutes at a time.
- [Dropbox][] keeps personal and work documents syncced to the cloud.
- [Arq][] keeps my Mac backed up to [Amazon Glacier][glacier] and [S3][].
- [f.lux][] adjusts my screen's color temperature, so I can't blame my laptop for keeping me up at night.

I tend to flit between browsers. Ideologically, I prefer [Firefox][]. When I've run head-to-head tests, [Safari][] has extended my battery life so much that I had a hard time believing it. [Chrome][] is a battery and CPU hog, but I keep coming back to it, because the feature set is as close to perfect as I've found. [LastPass][] lets me keep my passwords in sync across all of them.

[Work email][gmail] and [calendar][google-calendar] are Googley. In general, I'm a big fan of [indieweb](http://indiewebcamp.com/ "An independent web group.") tech and self-hosting, but I'm a bigger fan of outsourcing things that aren't your core competency. Running a mail server isn't going to make us a better keyboard company.

Inside the company, we communicate using [Slack][] pretty much exclusively.

Corporate task tracking is in [Trello][], though our process is mostly built around a morning planning session where we build 'today lists' in a tiny little webapp I knocked together. Today lists are pomodoro-compatible todo lists that expire after 18 hours.

When I'm writing code these days, I'm mostly writing Arduino [C][] in [vim][] and flashing it onto the keyboards with [avrdude][], though I sometimes slack off and use the [Arduino IDE][arduino-ide].

After running through a half-dozen EDA (Electronic Design Automation) tools over the course of a year, I settled on [KiCAD][], an open-source electrical CAD tool that's gaining popularity amongst folks working on open hardware. It's not without its issues, but it's evolving very quickly and is far more CAD than I need. It runs on Linux, MacOS and Windows. If you're using KiCAD on a Mac, you REALLY want to be running a [nightly build](http://downloads.kicad-pcb.org/osx/ "Nightly Mac builds of KiCAD.").

For 'traditional' solid CAD, I've been using [Autodesk Fusion 360][fusion-360]. Fusion 360 is a hybrid-cloud CAD package. (In this case, that means it's built around Chromium and offloads storage, rendering and file format conversion to Autodesk's servers.) It can work offline, but it's really meant to be used while connected to the Internet. 360 runs on both Windows and MacOS, but runs much better on Windows. Initially, I tried using [VMWare Fusion][vmware-fusion] (no relation) to run Fusion 360 in Windows. CAD, like gaming, turns out to be one of those things that just runs too slowly inside a VM. When I'm doing any real CAD work, I reboot into a Windows 8.1 Boot Camp partition. I'm at the point where I can actually design the things I want in 360 and have the come out looking and feeling nice. Fusion 360 isn't a replacement for [Solidworks][] or [Autodesk Inventor][inventor], but I'm not a replacement for a real mechanical engineer. (Disclosure: Autodesk is sponsoring Keyboardio with free licenses and amazing engineering support.)

There are some things, like USB debugging, that Linux is just better at. As you might expect, that's not the sort of thing that works well in virtualization, either. To that end, I went out and bought the aforementioned JetDrive and installed a recent Ubuntu + [GNOME][] on it. I was blown away by how much it didn't suck. It even deals reasonably well with the Retina screen on the MacBook. I use [rEFIt][] to triple-boot between OS X, Windows and Linux. I still feel a little dirty booting to Windows in public.

### What would be your dream setup?

I'm still waiting for my heads-up virtual display. It's my hope that the recent interest in VR gaming will get me the lightweight infinite desktop I've always wanted.

More realistically, I've been looking longingly at the various efforts to run a reasonable Linux desktop on the [Surface Pro 3][surface-pro-3]. Windows 8.1 is fairly tolerable, but still not quite what I want. The hardware is pretty much exactly what I want. It's as powerful as a MacBook Pro in a package lighter than the new [MacBook][macbook.2]. And it gets rid of the legacy keyboard, so I can bring my own ;)

[54-bit-driver-kit]: https://www.ifixit.com/Store/Tools/Mako-Driver-Kit--64-Precision-Bits/IF145-299-4 "A set of precision screwdrivers."
[amazonbasics-universal-travel-case]: https://www.amazon.com/AmazonBasics-Universal-Travel-Electronics-Accessories/dp/B002VPE1QG "A travel case."
[arduino-ide]: https://www.arduino.cc/en/Main/Software "A development environment for Arduino hardware."
[arduino-micro]: https://store.arduino.cc/arduino-micro "A small microcontroller board."
[arq]: https://www.arqbackup.com/ "S3-based backup for the Mac."
[avrdude]: https://github.com/sigmike/avrdude "A utility for changing the ROM and EEPROM of AVR microcontrollers."
[barnowl]: https://barnowl.mit.edu/ "A multi-protocol command-line IM client."
[boot-camp]: https://en.wikipedia.org/wiki/Boot_Camp_(software) "Software to allow Macs to run Windows natively."
[brass-sponge-solder-tip-cleaner]: https://www.adafruit.com/products/1172 "A soldering iron cleaner."
[c]: https://en.wikipedia.org/wiki/C_(programming_language) "A compiled programming language."
[chrome]: https://www.google.com/intl/en/chrome/browser/ "A WebKit-based browser, where each tab runs in its own thread."
[cinema-display]: https://en.wikipedia.org/wiki/Apple_Cinema_Display "An LCD display."
[drobo]: http://en.wikipedia.org/wiki/Drobo#Overview "A hardware-based backup system."
[dropbox]: https://www.dropbox.com/ "Online syncing and storage."
[dso-nano-v3]: https://www.seeedstudio.com/wiki/DSO_Nano_v3 "A digital oscilloscope."
[evernote]: https://evernote.com/ "Online software for capturing notes."
[ex330]: https://www.adafruit.com/products/308 "A multimeter."
[f.lux]: https://justgetflux.com/ "A tool to make the colour of your screen adapt to the current time of day."
[fast-charge-data-block-usb-adaptor]: http://www.portablepowersupplies.co.uk/portapow-fast-charge-data-block-usb-adaptor/ "A USB charging and data blocking device."
[firefox]: https://www.mozilla.org/en-US/firefox/new/ "A cross-platform open-source web browser."
[fusion-360]: http://web.archive.org/web/20221224070522/https://www.autodesk.com/products/fusion-360/overview "Cloud-based CAD/CAM software."
[geekdesk]: https://www.geekdesk.com/ "An electronic, height-adjustable desk."
[glacier]: https://aws.amazon.com/glacier/ "A data archiving service."
[gmail]: https://mail.google.com/mail/ "Web-based email."
[gnome]: https://www.gnome.org/ "A desktop system for *nix operating systems."
[google-calendar]: https://en.wikipedia.org/wiki/Google_Calendar "A web-based calendar client."
[imac]: https://www.apple.com/imac/ "An all-in-one computer."
[imgur]: https://imgur.com/ "An image sharing service."
[inventor]: http://web.archive.org/web/20221224070540/https://www.autodesk.com/products/inventor/overview "3D CAD software for mechanical designers."
[iphone-6]: https://en.wikipedia.org/wiki/IPhone_6 "A smartphone."
[irssi]: https://irssi.org/ "A CLI irc client."
[jetdrive-lite]: https://us.transcend-info.com/apple/jetdrivelite/ "A flash storage SD card for the MacBook Air and MacBook Pro."
[kicad]: http://web.archive.org/web/20220324205847/https://kicad-pcb.org/ "Open-source CAD software."
[kindle-voyage]: https://www.amazon.com/High-Resolution-Display-Adaptive-PagePress-Sensors/dp/B00IOY8XWQ "A high-resolution ebook reader."
[lastpass]: https://lastpass.com/ "A password manager."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[macbook.2]: https://en.wikipedia.org/wiki/MacBook_(2015_version) "A very thin 12 inch laptop."
[macos]: https://en.wikipedia.org/wiki/MacOS "An operating system for Mac hardware."
[mosh]: https://mosh.org/ "A remote terminal shell system."
[mutt]: http://www.mutt.org/ "A command-line email client."
[notational-velocity]: http://notational.net/ "A clever note-taking app for the Mac."
[oh-my-zsh]: https://github.com/robbyrussell/oh-my-zsh "A framework of extensions and themes for the zsh shell."
[pomodoro]: http://web.archive.org/web/20181018013724/http://pomodoro.ugolandini.com:80/ "Mac software for better managing your time."
[pv-201]: https://www.adafruit.com/products/151 "A mini-vice."
[refit]: http://refit.sourceforge.net "A boot menu for Intel-based computers."
[roost]: https://www.therooststand.com/ "A foldable laptop stand."
[s3]: https://aws.amazon.com/s3/ "Cloud-based Internet storage magic."
[safari]: https://www.apple.com/safari/ "A fast web browser."
[screen]: http://www.gnu.org/software/screen/ "Think of it as tabs for your *nix terminal."
[simplenote-ios]: https://itunes.apple.com/us/app/simplenote/id289429962 "A note app with cloud syncing."
[slack]: https://slack.com/ "A collaboration service."
[solder-sucker]: https://www.adafruit.com/products/148 "A tool for removing solder."
[solderpro-50]: https://www.sparkfun.com/products/9450 "A butane-powered soldering iron."
[solidworks]: https://www.3ds.com/products-services/solidworks/ "Modelling/CAD software."
[spacenavigator-notebook]: https://www.3dconnexion.com/products/spacenavigator-for-notebooks.html "A 3D mouse."
[surface-pro-3]: https://en.wikipedia.org/wiki/Microsoft_Surface_Pro_3 "A 12 inch Windows 8.1 Pro tablet."
[todo.sh]: http://web.archive.org/web/20170623150912/http://ginatrapani.github.io:80/todo.txt-cli/ "A command-line interface for your todo.txt file."
[trello]: https://trello.com/ "A project management service."
[typo2]: https://www.amazon.com/Typo2-Keyboard-for-iPhone-6/dp/B00O49D29Y "An iPhone case with a built-in keyboard."
[ubuntu]: https://www.ubuntu.com/ "A Unix distribution."
[usb-mini-charger-doctor]: https://www.amazon.com/BESTOPE®-Charger-Doctor-Current-Voltage/dp/B00GC9I61I "A USB-powered voltage test tool."
[utili-key]: https://www.thinkgeek.com/product/6d98/ "A 6-in-1 tool that folds into the shape of a key."
[vim]: https://www.vim.org/ "A command-line text editor."
[vmware-fusion]: http://web.archive.org/web/20221223060906/https://www.vmware.com/products/fusion.html "A PC emulator for the Mac."
[wes51]: https://www.amazon.com/Weller-WES51-Analog-Soldering-Station/dp/B000BRC2XU "A soldering station."
[windows-8]: https://en.wikipedia.org/wiki/Windows_8 "An operating system for PC and tablet computers."
[wireless-trackball-m570]: https://www.logitech.com/en-us/product/wireless-trackball-m570 "A wireless trackball."
[z]: https://github.com/rupa/z "A command-line tool for quickly moving between directories."
[zsh]: https://www.zsh.org/ "An interactive shell and scripting language."
