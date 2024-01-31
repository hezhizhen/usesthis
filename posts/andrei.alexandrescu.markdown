---
title: Andrei Alexandrescu
summary: Research scientist (Facebook)
date: 2012-05-18
categories:
- linux
- mac
- researcher
- scientist
---

### Who are you, and what do you do?

I'm Andrei Alexandrescu (I know! no-win name) and work as a Research Scientist at Facebook. In my free time I work on the [D][] programming language. I've also written a couple of books. My website is [http://erdani.com](http://erdani.com/ "Andrei's website.").

### What hardware do you use?

My work machine is a 13-inch [MacBook Pro][macbook-pro] (8GB RAM, 256GB SSD) running [OS X Lion][macos]. While at my desk I connect it to a [30-inch Dell monitor][u3011]. When I started working for Facebook (I work from home) my manager asked me what monitor I have. I told him I already had a 26-inch Soyo that serves me well. He was like, 'A larger monitor means you're more productive. I'm FedEx-ing you one. Don't feel flattered, it's just good business.' Since then the Soyo does little else than collecting dust.

When at the desk I also connect a stock Apple [flat keyboard][keyboard]. I tried a few others, including Microsoft's Digital Media Pro 1031 wireless keyboard. The meta keys don't match the Mac all that well, so I gave up on that. Finally I use a [Logitech M510][m510] wireless mouse.

While on the road I plug a USB [Sierra Wireless 598][aircard-598] device from Sprint for 3G connectivity. It has a MicroSD memory in tow and is a great little device - it just works. Never had any trouble with it.

My "work away from work" machine is an 2007-vintage [Dell E1705][inspiron-e1705]. I recall I got the cheapest machine I could (read: Dell outlet) featuring a 17-inch display with 1920x1200 resolution. I didn't care for speed as by then I was already equating "computing" with "cluster", but I wanted good resolution so I can cram as much information on the screen as possible. I grew fond of that machine. I can't ask more from a laptop keyboard (which, unlike the MacBook's, has two Ctrl keys and doesn't have "cut wrists" on its feature list). It's been through a doctorate and a book, and has the scars to prove it. You know that [story](http://www.weirdasianews.com/2009/04/28/footprints-wood-prayer-story-buddhist-monk/ "A story of a wooden floor with footprints from a Buddhist monk's prayers.") with the footprints worn into a wooden floor by a Buddhist Monk? Well, that machine's Space key has a thumb's footprint in it.

Digression - Dell power bricks have a thing of their own, did you know? They tend to "fail without failing" because they have a third wire sending information about the brick's power rating to the laptop, and that wire is often the first to fail mechanically (it's the thinnest). So the brick is still able to deliver power, but the laptop refuses to accept it. An entire secondary market of Dell power sources under $10 and Dell batteries under $25 is flourishing on eBay. They aren't exactly built to last, but at this price they can be considered consumables. Besides, the sellers are actually happy to send you replacement bricks for free. How a business can sell you a power brick for $8.65 shipped free, employ a human being responding phone calls within two rings (with a lovely accent), send you a free replacement, and still make money, is one of those mysteries of global economy.

As a writer, I must know what my books look like on all devices people would care to read them on. We have an [iPad 2][ipad-2] around, and I just got the small [Kindle][]. I'm not using the iPad much, but my wife uses it for studying every day. I plan to take the Kindle with me whenever I'm traveling.

I also use a 10-inch EEE PC (fitted with an after-market battery that makes the thing look like it swallowed an elephant). I use the EEE to chkdsk my NAS drives since OSX tends to mess them up.

Your interview made me realize I still have an antediluvian [Compaq Presario SR1726NX][presario-sr1726nx] tower right under my desk. It's from the days when desktop computers were like fridges - you know, "every house needs one". I forgot about it so thoroughly, it's become furniture. Now I do recall my three-year old presses its power button now and then to see the blinkenlights. I'll take it to the garage.

For communication I use an [iPhone 4S][iphone-4s] (from work), which I often connect to [Sennheiser HD 280 Pro headphones][hd-280-pro] to listen to music. By the way, I haven't a fixed phone since a long time ago; instead, I use an old [Linksys PAP2T][pap2t] VoIP box connected to the Internet (which I guess makes it count it as hardware).

Finally, a few weeks ago I got a [Dell XPS 17][xps-17] to replace my moribund Ubuntu machine. Not being in a hurry, I played with the pre-installed Windows 7 for a while, and... but wait, this gets into software! So let's make this the segue into your next question.

### And what software?

Yeah, so as I was saying, I played with [Windows 7][windows-7] for a while. I've been exclusively a Windows user and programmer for some ten years, but have not used it since 2005. I was curious how it feels to get back to my native village, you know, the nostalgia and memories of a former life. (It didn't go over so well. I noticed not much has changed, it was raining, there was mud everywhere, and I fell into some cow dung.) Two odd things about that installation out of the box (not sure whose fault it is): one, the default fonts looked like crap. Checked the resolution and used ClearType Tuner twice, no avail. Second, the multitouch trackpad handling is terrible, terrible. I'd put two fingers on it and move, it would do nothing. I lift the fingers, and exactly by that time some timeout expires and the multi-touch enters in action. And it's sticky! So then I need to explicitly cancel it by tapping again. You see, that's why people love Apple's multi-touch to the extent they accept the reversal of scrolling direction.

Anyhow, on a regular basis I use [OpenNX][] to connect remotely to big iron - a blade running [CentOS][] 5.2 - and run [emacs][] remotely for editing. For shell sessions I don't go through X; instead, I run [iTerm2][] and then connect to remote [screen][] sessions via [ssh][]. (The day I figured the connection between ssh and screen, a white dove landed on my shoulder.) Inside the screen sessions, I run [zsh][]. (The day I figured how cool zsh is, a hawk came and rid me of the white dove.) I also often need to run Juniper Network Connect, which helps me the same way sand helps the eye.

For email I use [Thunderbird][] with the Nostalgy extension. For browsing I use mostly [Chrome][] in conjunction with the [goo.gl URL Shortener][goo.gl-url-shortener], [Reddit Enhancement Suite][reddit-enhancement-suite], and [Tampermonkey][]. My personal website uses [Concrete5][], but I'm unhappy with it, it's too damn slow (I'm rooting for the headline: "Concrete5 solves the game of chess using cycles from its customers").

I use [Google Docs][google-docs] for light documents and [LaTeX][] for all heavy editing, including books and slides. [Skype][] and [Colloquy][] are almost always running on my laptop.

Needless to say, using language processors are a large part of my work, so [GNU C++][gcc], [Apache Hive][hive], and the dmd D compiler deserve a mention. I use [git][] for source control, [phabricator][] and [meld][] for looking at diffs, and all of my open-source work takes place on [github][].

### What would be your dream setup?

First off, I want one of them sit-stand workstations. I heard that sitting at work is bad for you - as bad, someone said, as a cocaine habit. I figure if I start using a standing desk, a cocaine habit is up for grabs at no change in my health balance.

I've noticed that the 17 inch laptop is, for me, a good compromise between screen real estate and transportability, so a MacBook Pro 17 custom made with a Dell laptop keyboard, rounded unibody edges, year-long battery, and no heat would be perfect.

OS-wise, Unix is to me the one system that is best geared to allow programmers to do Work - yes, capitalized. OS X is an okay Unix with a beautiful GUI on top, which is remarkable; but then Linux is an awesome Unix with an okay GUI on top, so I'd probably put Linux on that Mac. That is technically possible and actually easy, but I fear that would break some iBushido honor code, which would make me quite unpopular with the Apple fans community.

Finally, since you're asking about _dream_ setup, I'd love to try [Microsoft Visual Studio][visual-studio] on Linux. I've been productive with that IDE for years; I've also been productive with the traditional Unix tools, just in a different way. I'd be curious to see what it's like to compare and contrast the two mindsets directly.

[aircard-598]: http://web.archive.org/web/20150312004622/http://www.amazon.com:80/Sierra-Wireless-USB-598-Modem/dp/B00363WPVU "A USB modem."
[centos]: https://www.centos.org/ "A Linux distribution."
[chrome]: https://www.google.com/intl/en/chrome/ "A WebKit-based browser, where each tab runs in its own thread."
[colloquy]: https://colloquy.app/ "An IRC client for the Mac."
[concrete5]: http://web.archive.org/web/20220609011913/https://www.concrete5.org/ "A content management system."
[d]: https://dlang.org/ "A programming language."
[emacs]: http://www.gnu.org/software/emacs/ "An extensible, customizable, free/libre text editor — and more."
[gcc]: http://gcc.gnu.org/ "Code compiler frontends."
[git]: https://git-scm.com/ "A version control system."
[github]: https://github.com/ "A Git code repository service."
[goo.gl-url-shortener]: http://web.archive.org/web/20161012100443/https://chrome.google.com/webstore/detail/googl-url-shortener/iblijlcdoidgdpfknkckljiocdbnlagk "A Chrome extension to shorten URLs with the goo.gl service."
[google-docs]: https://en.wikipedia.org/wiki/Google_Docs "A web-based office suite."
[hd-280-pro]: http://web.archive.org/web/20221206010356/https://www.amazon.com/Sennheiser-HD-280-Pro-Headphones/dp/B000065BPB/ "Closed stereo headphones."
[hive]: https://hive.apache.org/ "A tool for working with Hadoop systems."
[inspiron-e1705]: https://www.dell.com/en-us "A 17 inch PC laptop."
[ipad-2]: https://www.apple.com/ipad/ "A tablet device."
[iphone-4s]: https://en.wikipedia.org/wiki/IPhone_4S "A smartphone."
[iterm2]: https://iterm2.com/ "An alternative terminal application for Mac OS X."
[keyboard]: https://www.apple.com/us/shop/goto/mac/accessories "The keyboard."
[kindle]: http://web.archive.org/web/20230315012831/http://www.amazon.com/Kindle-Ereader-ebook-reader/dp/B007HCCNJU/ "A digital book reader."
[latex]: https://www.latex-project.org/ "Typesetting software."
[m510]: https://www.logitech.com/en-us/product/wireless-mouse-m510.html "A wireless mouse."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[macos]: https://en.wikipedia.org/wiki/MacOS "An operating system for Mac hardware."
[meld]: http://meldmerge.org/ "A visual diff/merge tool."
[opennx]: http://web.archive.org/web/20230706192437/http://opennx.net/ "A remote X window connection tool."
[pap2t]: https://www.cisco.com/c/en/us/obsolete/unified-communications/cisco-pap2t-internet-phone-adapter-with-2-voip-ports.html "A VoIP phone adapter."
[phabricator]: https://www.phacility.com/ "A suite of developer tools."
[presario-sr1726nx]: http://h10025.www1.hp.com/ewfrf/wc/document?docname=c00576009&lc=en&cc=us&product=1818328&dlc=en "A PC tower."
[reddit-enhancement-suite]: https://redditenhancementsuite.com/ "A browser extension to customise Reddit viewing."
[screen]: http://www.gnu.org/software/screen/ "Think of it as tabs for your *nix terminal."
[skype]: https://www.skype.com/en/ "Voice and video chat software."
[ssh]: https://en.wikipedia.org/wiki/Secure_Shell "A command-line tool for secure remote connections."
[tampermonkey]: https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo "A Chrome extension for managing userscripts."
[thunderbird]: http://web.archive.org/web/20070322094547/http://www.thunderbird.net:80/ "An open-source cross-platform mail client."
[u3011]: http://web.archive.org/web/20230507075658/https://www.amazon.com/Dell-UltraSharp-30-Inch-PremierColor-Monitor/dp/B00C2RPW8O/ "A 30 inch LCD screen."
[visual-studio]: http://web.archive.org/web/20180617165945/https://www.visualstudio.com/ "A Windows development environment."
[windows-7]: https://en.wikipedia.org/wiki/Windows_7 "An operating system."
[xps-17]: http://web.archive.org/web/20190506095815/https://www.dell.com/en-us/shop/cty/pdp/spd/xps-17 "A 17 inch PC laptop."
[zsh]: https://www.zsh.org/ "An interactive shell and scripting language."
