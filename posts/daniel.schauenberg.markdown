---
title: Daniel Schauenberg
summary: Staff engineer (Etsy)
date: 2017-02-21
categories:
- developer
- mac
---

### Who are you, and what do you do?

Hi! I'm Daniel Schauenberg and currently I'm a Staff Engineer on [Etsy][]'s fleet management and provisioning team. I've previously worked on the DevTools team at Etsy and in former jobs I was an embedded systems engineer and a network/systems administrator at a chemical plant before that.

### What hardware do you use?

In terms of hardware I use an [11" MacBook Air][macbook-air] as my personal laptop, and have the same model for work in conjunction with a [27" Thunderbolt Display][thunderbolt-display], [Apple Wireless Keyboard][keyboard], and [Apple Trackpad][magic-trackpad]. It's honestly the best laptop I have ever owned, and I can't imagine ever going with a different size (although Apple's current laptop lineup suggests that I will have to at some point).

I have [Sennheiser HD 280 Pro headphones][hd-280-pro] at work and also burn through a pair of [Sennheiser CX 300‑II in-ear headphones][cx-300-ii] about once a year. But they are still the best ones I've found so far.

I recently acquired an [iPhone SE][iphone-se] after my trusty, almost 4 year old [iPhone 5][iphone-5] got too slow, and I have a 1st gen [iPad mini][ipad-mini] that I barely use. My phone is connected to a [Pebble Time][pebble-time] but I have most notifications disabled. I have a root server at Hetzner that hosts most of my stuff, an HP microserver at home for backups, and built my own homerouter on an [apu1d4][] board. And I *love* my [YubiKeys][yubikey] (I have a 4 for work and a [NEO][yubikey-neo] for personal stuff) which I mostly use for 2FA on my servers and home router (via [Duo Security][duo]) and for signing [git][] commits.

### And what software?

A lot of my work revolves around text files (code, journal, notes, ..) so the two pieces of software I probably interact with most are [vim][] and git. Most of the time I write [bash][], [Ruby][], [PHP][] or [Go][], and I use [Make][] religiously to automate as much as possible, sign git commits with GPG, read email in [mutt][] and generally live in a bunch of nested [tmux][] sessions in a fullscreen [iTerm2][] terminal. I use [Ledger][] for my accounting, which stays with the theme of being a bunch of text files, tracked in git, and automated with make.

For productivity and tracking what I have to do I rely a ton on [OmniFocus][], for which I have some scripts to pull in things from [JIRA][] at work, [GitHub][] issues (.com and our enterprise install), and email I need to reply to.

I listen to music in either [iTunes][] or [Amazon Music][amazon-cloud-player] (RIP [Rdio][]) depending on what I want to listen to. I use a version of [Skitch][] from 2012 that still supports WebDAV uploads so I can host my screenshots on [S3][] via [s3itch][] hosted on [Heroku][]. I also run my own [URL shortener][katana] on there. I use [macOS][] on the laptops and run [FreeBSD][] on all my servers. I try to run as much stuff as possible myself, so my personal infrastructure is made up of things like [ownCloud][] (for WebDAV, CalDAV, and CardDAV), [Sendmail][], [Dovecot][], [Nagios][], [Graphite][], [procmail][], and [Fetchmail][]. All my servers (including my home router) run ZFS and are managed by [Chef][].

On my iPhone I mostly use [Tweetbot][tweetbot-ios], [Instagram][instagram-ios], [Reeder][reeder-ios] (<3 RSS), [Calm][calm-ios], and a combination of [Working Copy][working-copy-ios] and [Editorial][editorial-ios] to clone git repos on my phone and take notes or write blog posts. I also use [Pocket][pocket-ios] a lot, to the point where I had ~2000 articles backlogged. So I wrote a tool I called [pocketcleaner][] which runs on one of my servers and trims down the list to the 20 newest entries every Sunday night.

### What would be your dream setup?

I basically have my dream set up in a lot of ways. It would be awesome if I didn't have to charge my MacBook Air so often, and I would love it if macOS had kept closer to its UNIX roots. But otherwise I'm really enjoying my setup.

[amazon-cloud-player]: https://www.amazon.com/b?ie=UTF8&node=2658409011 "A web-based music service."
[apu1d4]: https://pcengines.ch/apu1d4.htm "A computer system board."
[bash]: http://www.gnu.org/software/bash/ "A terminal shell."
[calm-ios]: https://itunes.apple.com/us/app/calm-meditate-sleep-relax/id571800810 "A meditation and relaxation app."
[chef]: https://www.chef.io/chef/ "Configuration management software."
[cx-300-ii]: https://www.amazon.com/Sennheiser-II-Precision-Enhanced-Earbuds/dp/B001EZYMF4 "In-ear headphones."
[dovecot]: https://dovecot.org/ "A secure IMAP server."
[duo]: https://duo.com/ "A two-factor authentication service."
[editorial-ios]: http://omz-software.com/editorial/ "A Markdown-powered text app."
[etsy]: https://www.etsy.com/ "A doily deployment system."
[fetchmail]: https://en.wikipedia.org/wiki/Fetchmail "A tool for retrieving email from a mail server."
[freebsd]: https://www.freebsd.org/ "An open source operating system."
[git]: https://git-scm.com/ "A version control system."
[github]: https://github.com/ "A Git code repository service."
[go]: https://golang.org/ "A compiled programming language."
[graphite]: https://github.com/graphite-project/graphite-web "A data metrics processor/viewer."
[hd-280-pro]: https://www.amazon.com/Sennheiser-HD-280-Pro-Headphones/dp/B000065BPB "Closed stereo headphones."
[heroku]: https://www.heroku.com/ "A service for running and deploying Ruby, Node.js, Clojure, Java, Python, and Scala apps."
[instagram-ios]: https://itunes.apple.com/us/app/instagram/id389801252 "A photo taking/sharing app."
[ipad-mini]: https://www.apple.com/ipad-mini/ "A 7.9 inch tablet device."
[iphone-5]: https://en.wikipedia.org/wiki/IPhone_5 "A smartphone."
[iphone-se]: https://en.wikipedia.org/wiki/IPhone_SE "A 4 inch smartphone."
[iterm2]: https://iterm2.com/ "An alternative terminal application for macOS."
[itunes]: https://www.apple.com/itunes/ "A jukebox application and online store."
[jira]: https://www.atlassian.com/software/jira "Issue/project tracking software."
[katana]: https://github.com/mrtazz/katana "A hosted URL shortener."
[keyboard]: https://www.apple.com/keyboard/ "The keyboard."
[ledger]: https://ledger-cli.org/ "A command-line accounting system."
[macbook-air]: https://www.apple.com/macbook-air/ "A very thin laptop."
[macos]: https://en.wikipedia.org/wiki/MacOS "An operating system for Mac hardware."
[magic-trackpad]: https://en.wikipedia.org/wiki/Magic_Trackpad "A trackpad for desktop machines."
[make]: http://www.gnu.org/software/make/manual/make.html "Software to prepare code for compilation."
[mutt]: http://www.mutt.org/ "A command-line email client."
[nagios]: https://www.nagios.org/ "Software for monitoring hardware/software infrastructure."
[omnifocus]: https://www.omnigroup.com/omnifocus/ "Task management software for the Mac."
[owncloud]: https://owncloud.org/ "Self-hosted syncing and sharing software."
[pebble-time]: https://en.wikipedia.org/wiki/Pebble_Time "A smartwatch."
[php]: https://php.net/ "An interpreted scripting language."
[pocket-ios]: https://getpocket.com/ios/ "An app for the read-it-later service."
[pocketcleaner]: https://github.com/mrtazz/pocketcleaner "A tool for managing your Pocket queue."
[procmail]: https://en.wikipedia.org/wiki/Procmail "A mail delivery agent."
[rdio]: http://web.archive.org/web/20151209115835/http://www.rdio.com:80/home/en-us/ "A music streaming service."
[reeder-ios]: https://reederapp.com/ios/ "A Google Reader client for iOS."
[ruby]: https://www.ruby-lang.org/en/ "An interpreted scripting language."
[s3]: https://aws.amazon.com/s3/ "Cloud-based Internet storage magic."
[s3itch]: https://github.com/roidrage/s3itch "S3 proxy software for Skitch's WebDAV sharing."
[sendmail]: https://en.wikipedia.org/wiki/Sendmail "Email routing software."
[skitch]: https://evernote.com/skitch/ "An always-on image editor for the Mac."
[thunderbolt-display]: https://www.apple.com/displays/ "A Thunderbolt-powered monitor."
[tmux]: https://sourceforge.net/projects/tmux/ "A terminal multiplexer, similar to screen."
[tweetbot-ios]: https://tapbots.com/tweetbot/ "A Twitter client for iOS."
[vim]: https://www.vim.org/ "A command-line text editor."
[working-copy-ios]: https://workingcopyapp.com/ "A Git client."
[yubikey-neo]: https://www.yubico.com/products/yubikey-hardware/yubikey-neo/ "A USB-based tool for generating one-time passwords."
[yubikey]: https://www.yubico.com/products/yubikey-hardware/yubikey/ "A USB-based tool for generating one-time passwords."
