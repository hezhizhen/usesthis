---
title: Johan Nordberg
summary: Freelance developer (Wintersmith)
date: 2016-06-07
categories:
- designer
- developer
- linux
- mac
---

### Who are you, and what do you do?

I'm [Johan Nordberg](https://johan-nordberg.com/ "Johan's website."), a freelance software developer and creative with a somewhat nomadic lifestyle, alternating between Sweden (where I'm [from](https://en.wikipedia.org/wiki/Luleå "The Wikipedia entry for Luleå.")), Italy (where I have my [main base](https://en.wikipedia.org/wiki/Florence "The Wikipedia entry for Florence.")) and Japan.

When not working for a client, I like to experiment with new technologies and make [open-source](https://github.com/jnordberg "Johan's GitHub account.") tools and libraries.

### What hardware do you use?

My main computer is a [13" MacBook Air][macbook-air] and I have a [15" MacBook Pro][macbook-pro] that I use for graphics work. And I'm not sure if this counts as hardware, but I use [Amazon EC2][ec2] to offload my laptop for heavy workloads like 3D rendering and data processing.

Besides that, there isn't much else needed for my work. I have pile of iPhones and iPads for application testing, or that's what I tell myself when I want to get the latest model anyways :D

Oh, and my portable speaker, the "[iLoud][]". I love music and this speaker sounds great, plus the batteries last for a whole day!

### And what software?

I use lots and lots of software! What I use varies greatly with the type project I'm working on, but I'll try list the tools and libraries I keep coming back to.

[Sublime Text 3][sublime-text] is probably where I spend most of my time - it's where I do all my coding. Except for [iOS][] and [OS X][macos] apps, though, where [Xcode][] is the only sane option. My second-most used app must be [iTerm2][], which is a great replacement for OS X's [Terminal.app][terminal]. I especially love the "visor" feature that lets you have a system-wide hotkey to quickly toggle a terminal. And in that terminal, my shell is [zsh][] with [oh-my-zsh][].

I use the [Creative Suite][creative-suite] (mainly [Photoshop][], [Illustrator][] and [Lightroom][]) for design and mockups, and [Final Cut Pro][final-cut-pro] for video editing. And when things need to get automated I use [GraphicsMagick][] and [ffmpeg][] respectively.

For 3D modelling and rendering I use a combination of [Fusion 360][fusion-360], [Cinema 4D][cinema-4d] and [Maxwell Render][maxwell-render]. And when I need something sliced for 3D printing I use [Simplify3D][], which I found through countless hours of experimenting to produce the best results. [Slic3r][] is pretty good too, if you want a hackable alternative.

To organize my work I use [Timings][] to track where I spend my time, and [Slack][] to communicate with clients and collaborators. All code is managed with [git][] (with [GitX][] as front-end) and self-hosted on a server running [Gogs][], except for open-source stuff which lives on [GitHub][].

My favourite programming language is [CoffeeScript][], which basically is [JavaScript][] with a better syntax. I also use [Python][], [Go][], [Swift][swift.2] and occasionally a bit of [C][].

For web development my stack usually consists of [Wintersmith][], [Browserify][] (with [Coffeeify][]), [Browsernizr][] and [Stylus][] for the front-end. And [Node.js][] + [hapi][] for the back-end. Or just Go with the standard library if performance is key. I would also like to mention [d3.js][] - it's mostly used for data visualizations but has almost everything you could ever want for working with 2D graphics and the DOM; I've built entire web apps using nothing but d3.js.

On my servers -- which I host on [Scaleway][] and [Vultr][] -- I use [FreeBSD][] or [Debian][], and I usually put [nginx][] in front of whatever web app is running on them. And I use [rsub][] to remote edit files on them.

I manage backups with a self-hosted [Syncthing][] cloud that has servers in both hemispheres so I can get decent speeds wherever I'm located. I also use [Carbon Copy Cloner][carbon-copy-cloner] to make bootable full-disk backup images.

I use [Alfred][] as an easily accessible calculator, [1Password][] to manage my passwords, and I try to install everything through [Homebrew][] with [Cask][homebrew-cask].

That's about it, I think. I also use a lot of paper to get my thoughts organised before they go into the computer in some form.

### What would be your dream setup?

I'm super excited for VR! I have a [HTC Vive][vive] on preorder and I'm currently building a beast of a rig that will power it. I have this vision of a virtual workspace that I want to explore, and I plan to spend the next year following that, experimenting with UI concepts in VR.

So I guess my dream setup would be a device with a small screen you keep in your pocket, just like a smartphone, but with a pair of goggles you put on to enter your virtual office to get stuff done.

Or if all that fails... the new line of [MacBooks][macbook.2] looks nice! One of those and a $5k monthly allowance on Amazon EC2 would be pretty sweet :)

[1password]: https://1password.com "Password management software for Mac OS X."
[alfred]: https://www.alfredapp.com/ "A launcher app for the Mac."
[browserify]: http://browserify.org/ "A Node.js dependency manager."
[browsernizr]: https://github.com/jnordberg/browsernizr "A Modernizer module for Browserify."
[c]: https://en.wikipedia.org/wiki/C_(programming_language) "A compiled programming language."
[carbon-copy-cloner]: https://bombich.com/ "Mac disk backup software."
[cinema-4d]: http://web.archive.org/web/20160602174133/http://www.maxon.net/en/products/cinema-4d-prime/who-should-use-it.html "3D rendering software."
[coffeeify]: https://github.com/jnordberg/coffeeify "A CoffeeScript module for Browserify."
[coffeescript]: https://coffeescript.org/ "A language that compiles into Javascript."
[creative-suite]: https://www.adobe.com/creativecloud.html "A collection of design tools."
[d3.js]: https://d3js.org/ "A Javascript framework for manipulating data."
[debian]: https://www.debian.org/ "A Linux distribution."
[ec2]: https://aws.amazon.com/ec2/ "A web service for virtualised processing."
[ffmpeg]: http://www.ffmpeg.org/ "Comprehensive audio/video software."
[final-cut-pro]: https://en.wikipedia.org/wiki/Final_Cut_Pro "A nonlinear video editor."
[freebsd]: https://www.freebsd.org/ "An open source operating system."
[fusion-360]: http://web.archive.org/web/20221224070522/https://www.autodesk.com/products/fusion-360/overview "Cloud-based CAD/CAM software."
[git]: https://git-scm.com/ "A version control system."
[github]: https://github.com/ "A Git code repository service."
[gitx]: http://gitx.frim.nl/ "A git GUI for Mac OS X."
[go]: https://golang.org/ "A compiled programming language."
[gogs]: http://web.archive.org/web/20221219133336/https://gogs.io/ "A self-hosted git service."
[graphicsmagick]: http://www.graphicsmagick.org/ "Image editing and converting software."
[hapi]: https://hapijs.com/ "A web framework."
[homebrew-cask]: https://github.com/caskroom/homebrew-cask "A command-line tool for installing Mac applications."
[homebrew]: http://brew.sh "Command-line package manager for Mac OS X."
[illustrator]: https://www.adobe.com/products/illustrator.html "A vector graphics editor."
[iloud]: https://www.ikmultimedia.com/products/iloud/ "A portable Bluetooth speaker."
[ios]: https://www.apple.com/ios/ios-10/ "A mobile operating system."
[iterm2]: https://iterm2.com/ "An alternative terminal application for macOS."
[javascript]: https://en.wikipedia.org/wiki/JavaScript "An interpreted scripting language."
[lightroom]: https://www.adobe.com/products/photoshop-lightroom.html "Photo management and editing software."
[macbook-air]: https://www.apple.com/macbook-air/ "A very thin laptop."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[macbook.2]: https://en.wikipedia.org/wiki/MacBook_(2015_version) "A very thin 12 inch laptop."
[macos]: https://en.wikipedia.org/wiki/MacOS "An operating system for Mac hardware."
[maxwell-render]: http://www.maxwellrender.com/products/maxwell-render-suite "3D rendering software."
[nginx]: http://nginx.org/ "A very fast web/mail server."
[node.js]: https://nodejs.org/en/ "A Javascript application platform."
[oh-my-zsh]: https://github.com/robbyrussell/oh-my-zsh "A framework of extensions and themes for the zsh shell."
[photoshop]: https://www.adobe.com/products/photoshop.html "A bitmap image editor."
[python]: https://www.python.org/ "An interpreted scripting language."
[rsub]: https://github.com/henrikpersson/rsub "Software for editing file remotely via Sublime Text."
[scaleway]: https://www.scaleway.com/ "An SSD-based web hosting service."
[simplify3d]: https://www.simplify3d.com/ "3D printing software."
[slack]: https://slack.com/ "A collaboration service."
[slic3r]: https://slic3r.org/ "3D printing software."
[stylus]: http://stylus-lang.com/ "A dynamic language for generating CSS."
[sublime-text]: http://www.sublimetext.com/ "A coder's text editor."
[swift.2]: https://swift.org/ "A compiled programming language."
[syncthing]: https://syncthing.net/ "Self-hosted file syncing software."
[terminal]: https://en.wikipedia.org/wiki/Terminal_(OS_X) "A console application included with Mac OS X."
[timings]: https://www.mediaatelier.com/Timings2/ "Time tracking software for the Mac."
[vive]: http://www.htcvr.com/ "A SteamVR headset."
[vultr]: https://www.vultr.com/ "An SSD-based web hosting service."
[wintersmith]: http://wintersmith.io/ "A static site generator."
[xcode]: https://en.wikipedia.org/wiki/Xcode "An IDE for Mac developers."
[zsh]: https://www.zsh.org/ "An interactive shell and scripting language."
