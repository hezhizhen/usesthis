---
title: David Lublin
summary: Developer, artist, co-founder (VIDVOX)
date: 2017-05-23
categories:
- artist
- developer
- mac
---

### Who are you, and what do you do?

My name is [David Lublin](http://www.davidlubl.in/ "David's website.") and since 2004 I have been half of a company called [VIDVOX](http://vidvox.net/ "David's software company.") that makes software for artists. I do a bit of everything, which includes coding, design, sales, support, marketing, tutorials and documentation, beta testing, blogging, tweeting, community building, managing freelancers and a bunch of other things.

We find that open standards are particularly important for creative communities and we maintain two open source projects that we are especially proud of. The first is the [Hap video codecs][hap], a set of movie formats that use GPU accelerated decompression for playback of extremely high resolution video on Mac, Windows and Linux machines. The second is [ISF](https://www.interactiveshaderformat.com/ "A shader format.") (Interactive Shader Format), an open specification for writing GLSL shaders that can be used as video generators and image filters across different host applications on desktop, mobile and web platforms. A bunch of our other useful low level code for working with specifications like MIDI, OSC and OpenGL is also [available on GitHub](https://github.com/mrRay/vvopensource "A collection of open source code from VIDVOX.").

I also sometimes make art!

[Mostly I am known for VJing](http://www.davidlubl.in/projects/#/visual-performances/ "David's video performances."), which is live video performed remixing, usually along with music. I've gotten to do a lot of fun shows over the years including a performance at Lincoln Center and a tour with Girl Talk back in 2011. For geek points, the one time I got to fill in for The Eclectic Method for a Doctor Who fan meet up at Comic Con was maybe my top moment personally so far.

Recently I have been making a number of Twitter bots, most noteworthy of which are [@TVCommentBot](https://twitter.com/TVCommentBot "David's TV comment Twitter bot.") (a bot that watches live broadcast TV and inserts its own closed captioning) and [@TVFaceBot](https://twitter.com/TVFaceBot "David's TV face Twitter bot.") (a bot that looks for faces on live broadcast TV and tweets them), and a few spin offs like [@StarTrekTVBot](https://twitter.com/StarTrekTVBot "David's Star Trek comment Twitter bot.") (because I've run out of Star Trek episodes to watch) and [@TVCrimeBot](https://twitter.com/TVCrimeBot "David's crime TV comment Twitter bot."). Related to this I am also now developing a website for bots to find love online called [bot.dating](http://bot.dating/ "David's bot website.").

Probably the project that I am most passionate about is [MIDIDogs.biz](http://mididogs.biz/ "David's website where dogs sing TV theme songs.") which is a website where I post videos of digitally synthesized barking dogs singing your favorite TV themes and pop songs along with puntastic titles like "Paw and Order" and "Fluffy The Vampire Spayer" and "Game of Bones" and "Doggie Howser" -- I take requests.

At the most recent [Stupid Hackathon](http://www.stupidhackathon.com/ "A hackathon for stupid ideas.") my project was the low tech "[Yell Hole](https://vimeo.com/206174341/ "David's Stupid Hackathon entry.")" which is basically a bucket with sound insulation that you can put on your head and yell into without disturbing your neighbors.

### What hardware do you use?

Currently my primary development machine is a 15" TouchBar [MacBook Pro][macbook-pro] with an [LG 4k display][ultrafine-4k]. I miss the physical escape key but otherwise very happy. I've used a similar setup of a MacBook Pro along with an external monitor for over a decade and this is the best version of it yet.

For work I have a lot of Macs for testing, we need pretty much every GPU and macOS combination readily available in case a user has a problem. Along these lines I have several high end audio interfaces (e.g. the MOTU 828 and [YellowTec PUC2][puc2] on my desk right now), video capture devices (Blackmagic [UltraStudio 4k][ultrastudio-4k] & [Mini][ultrastudio-mini] recorders, a few Logitech webcams, some old DV / Firewire gear in the closet..), MIDI controllers (lately enjoying the [Numark Orbit][orbit], [APC mini][apc-mini], [Korg NanoKontrol][nanokontrol] and a Serato DJ-style controller when doing my own shows but I probably have over a dozen others in storage), plus some DMX lighting gear (most used are [ENTTEC ArtNet boxes][ode] and a few older [Mega Pixel LED bars][mega-pixel-led] from American DJ) and other random things we support like WiiMotes. I also have a handful of cheap-ish external monitors that we sometimes use for testing multi-screen output configurations. We are always getting new stuff, usually when someone has a problem with something we don't have on hand already.

Right now @TVCommentBot and @TVFaceBot are running on a [2010 Mac mini][mac-mini] that is plugged into my living room TV so that I can watch the feed instead of regular TV. The system gets broadcast TV over the airwaves through a standard antenna and a cheap digital TV receiver which outputs HDMI that is captured with a BlackMagic Mini recorder. A MIDI controller is connected for adjusting some parameters of the software without having to access the keyboard and mouse which are difficult to reach.

I have an [iPhone 5s][iphone-5s] for all of the things you'd expect someone to have a smartphone for that gets used constantly and a [3rd generation iPad][ipad-3] which does not get much use. So far I haven't had a compelling reason to upgrade either to a newer model.

For headphones I've had the same pair of Sony [MDR-7506][]'s for about a decade. I also often use the [standard iPhone ear buds][earpods] outside of the house.

My desk is a [GeekDesk][] which I confess is usually used in sitting mode lately. I am thinking about installing some basic drawers for holding the small pieces of gear that end up cluttering the top area.

The best purchase I have made in the last few years is [a peg board with hooks for organizing my large cable collection](https://twitter.com/DavidLublin/status/762781479751585792 "David's peg board tweet.") that makes it possible to connect all these things together.

I have had the same [HP LaserJet 1320 printer][laserjet-1320] since 2004 and have tried out lots of different kinds of small notebooks over the years (currently making my way through a small graph paper book from Muji). I have a couple of typewriters that I've collected over the years, a newer [Olivetti MS 25 Plus][ms-25-plus] manual sometimes gets dusted off for use.

### And what software?

When VJing and otherwise making video art I typically use [VDMX][] which is software that we primarily work on at VIDVOX. Sometimes I'll connect it to other custom software using [Syphon][] or MIDI / OSC.

I write most of my code in [BBEdit][], [Xcode][] for compiling and [Tower][] as my [Git][] client. When needed I am ready to get down with [Terminal][].

Online I use [Chrome][] for web browsing, [Adium][] for chat and [Transmit][] for FTP. [Squarespace][] for blogging and [Vimeo][] for video hosting.

[TextEdit][] for writing words and [Keynote][] for making presentations. I often use [Stickies][] app on my Mac for keeping quick notes and snippets.

When creating new video filters typically I will use our free [ISF Editor][isf-editor], an in-house tool we released for writing and previewing GLSL shaders. Though not as often as in the past I also still make use [Quartz Composer][quartz-composer] from time to time.

For making video tutorials [ScreenFlow][] is my favorite. I will sometimes also use [iMovie][] or [QuickTime Player 7 Pro][quicktime-pro] as part of my video workflow. Lately I have been trying to use [Affinity Designer][affinity-designer] and [Photo][affinity-photo] for the basic image and vector design work that I need to do.

Some of my bots make use of open source machine learning techniques -- I got started with one called [DeepBelief][deepbeliefsdk] which is still what powers the object detection for @TVCommentBot, though nowadays there are lots of even better libraries like [TensorFlow][] available for this kind of stuff.

### What would be your dream setup?

A giant science fiction laboratory that includes a Holodeck from Star Trek that somehow fits inside my apartment in NYC and is also sound insulated because I love working from home but being able to walk across the street for a bagel / slice of pizza pretty much anytime of day is also a requirement.

A way to directly interface my brain thoughts with machines that doesn't involve installing a microchip in my head.

In the meantime I am thinking of getting a second desk or workbench to make it easier to divide work / art time and having a real life living human assistant would be amazing.

[adium]: https://en.wikipedia.org/wiki/Adium "A multi-protocol chat application for the Mac."
[affinity-designer]: https://en.wikipedia.org/wiki/Affinity_Designer "A vector graphics editor."
[affinity-photo]: https://affinity.serif.com/en-us/photo/ "Photo editing software."
[apc-mini]: http://web.archive.org/web/20170708085029/http://akaipro.com:80/product/apc-mini "A wireless Live controller."
[bbedit]: http://www.barebones.com/products/bbedit/ "A text editor for the Mac."
[chrome]: https://www.google.com/intl/en/chrome/browser/ "A WebKit-based browser, where each tab runs in its own thread."
[deepbeliefsdk]: https://github.com/jetpacapp/DeepBeliefSDK "An image recognition development framework."
[earpods]: https://en.wikipedia.org/wiki/Apple_earbuds "The white headphones included with iPhones."
[geekdesk]: https://www.geekdesk.com/ "An electronic, height-adjustable desk."
[git]: https://git-scm.com/ "A version control system."
[hap]: https://github.com/vidvox/hap "A video codec."
[imovie]: https://www.apple.com/imovie/ "A Mac OS X video editor, included in iLife."
[ipad-3]: https://www.apple.com/ipad/ "A tablet device with a retina display."
[iphone-5s]: https://en.wikipedia.org/wiki/IPhone_5S "A smartphone."
[isf-editor]: https://vdmx.vidvox.net/tutorials/using-the-isf-editor "An editor for ISF generators."
[keynote]: https://www.apple.com/keynote/ "Presentation software for the Mac."
[laserjet-1320]: http://h10025.www1.hp.com/ewfrf/wc/product?cc=us&lc=en&dlc=en&product=410623 "A laser printer."
[mac-mini]: https://www.apple.com/mac-mini/ "A small desktop computer."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[mdr-7506]: https://www.amazon.com/Sony-MDR7506-Professional-Diaphragm-Headphone/dp/B000AJIF4E "Studio-quality headphones."
[mega-pixel-led]: https://www.adj.com/mega-pixel-led "A bright LED light bar."
[ms-25-plus]: https://www.amazon.com/Olivetti-MS-25-Plus-Typewriter/dp/B00093IW12/ "A typewriter."
[nanokontrol]: https://www.amazon.com/Korg-nanoKONTROL-USB-Controller-Black/dp/B001J8LJWK "A USB MIDI controller."
[ode]: https://www.enttec.com/products/controls/dmx-over-ethernet/ode/ "A device for controlling lights over Ethernet."
[orbit]: https://www.numark.com/product/orbit "A wireless MIDI controller."
[puc2]: https://www.yellowtec.com/en/products-lp/puc.html "A USB-based audio converter."
[quartz-composer]: https://en.wikipedia.org/wiki/Quartz_Composer "A visual programming environment."
[quicktime-pro]: https://support.apple.com/kb/HT201175 "A commercial version of QuickTime."
[screenflow]: http://www.telestream.net/screenflow/overview.htm "A screencasting studio for the Mac."
[squarespace]: https://www.squarespace.com/ "A site hosting/creation service."
[stickies]: https://en.wikipedia.org/wiki/Stickies_(software) "Desktop note software for the Mac."
[syphon]: http://syphon.v002.info/ "Real-time video frame mixing."
[tensorflow]: https://www.tensorflow.org/ "An open source machine learning library."
[terminal]: https://en.wikipedia.org/wiki/Terminal_(OS_X) "A console application included with Mac OS X."
[textedit]: http://web.archive.org/web/20200525165141/https://support.apple.com/en-us/HT2523 "A text editor included with Mac OS X."
[tower]: https://www.git-tower.com/ "A Mac GUI for Git."
[transmit]: https://panic.com/transmit/ "An FTP/SFTP client for the Mac."
[ultrafine-4k]: https://www.apple.com/shop/product/HKMY2VC/A/lg-ultrafine-4k-display "A 21.5 inch 4K display."
[ultrastudio-4k]: https://www.blackmagicdesign.com/products/ultrastudio "A rack-mounted 4K video capture device."
[ultrastudio-mini]: https://www.blackmagicdesign.com/products/ultrastudio "A little video capture device."
[vdmx]: https://vidvox.net/ "Real-time video studio software for the Mac."
[vimeo]: https://vimeo.com/ "A video sharing service."
[xcode]: https://en.wikipedia.org/wiki/Xcode "An IDE for Mac developers."
