---
title: Thorsten Ball
summary: Writer, software developer
date: 2018-12-25
categories:
- developer
- mac
- writer
---

### Who are you, and what do you do?

I'm [Thorsten Ball](https://thorstenball.com/ "Thorsten's website."). I'm a writer and software developer. I wrote [Writing An Interpreter In Go](https://interpreterbook.com/ "Thorsten's site for his interpreter book.") and its sequel [Writing A Compiler In Go](https://compilerbook.com/ "Thorsten's site for his compiler book.") and I work at [ioki Mobility](https://ioki.com/en/ "A mobility consulting company.").

### What hardware do you use?

My main machine is a 2016 13-inch [MacBook Pro][macbook-pro]. It has the Touch Bar, 16GB of memory, a 512GB SSD and four Thunderbolt 3 ports. It's fast, it's quiet and it has enough resources to let me write code and prose. I like it a lot.

And while I don't care about the Touch Bar, I also don't care about the removed Esc key - I map Caps Lock to Control and use `Ctrl-[` instead. The Touch ID, though, now that's useful. I don't think I could live without it anymore. 

As for the infamous keyboard that ships with this generation of MacBook Pros: typing on it feels great, but I had to have the whole top unit of the computer replaced because of a stuck key. That's more than just annoying and the keyboard's clickyness doesn't make up for it. 

The other downside of this MacBook Pro is that it serves as a daily reminder of the unfulfilled dream of USB-C: I still have use an external USB hub and multiple USB-to-USB-C adapters because the one hub that has the necessary ports doesn't exist yet. 

I also have a 13-inch MacBook Pro from 2015, with 16GB of memory and a 256GB SSD. My previous main machine. When I booted it up the first time, I thought it's the best computer I've ever used. I still do, but I rarely use it anymore. 

When in use, both machines are either plugged into a 27-inch Dell monitor, with an external keyboard and mouse, or they sit on my lap. With an external display, the laptop sits to its right; its screen practically unused, only serving as a drag'n'drop destination for temporary files. 

My keyboard at home is a [Topre Realforce 87U][realforce-87u], which I adore. Great feel, great sound and its look is understated and elegant. Before that I used a [KUL ES-87][es-87] with Cherry MX Blue switches. At work I use an [Apple Magic Keyboard][magic-keyboard], because I haven't found the courage to take the spare KUL ES-87 to the office. It's loud. 

After years of using an external [Magic Trackpad][magic-trackpad] my wrist told me in unmistakable terms that it's had enough and after a short flirt with vertical mice I settled my right hand on a [SteelSeries Rival 110][rival-110]. That was two years ago and it's been my main mouse ever since - at home and at work. I never thought I'd say this about a computer mouse, but it feels and _sounds_ good - that's one serious _click_. 

My desk at home is a height-adjustable [Steelcase Ology][ology]. I've always wanted to give standing desks a try and after using them at work for a few months I decided to get one. Main requirement: it had to be adjustable through the push of a button - otherwise I'd be too lazy to switch enough between sitting and standing. 

Now, when I'm sitting, I'm sitting on a [Steelcase Gesture][gesture]. It's my first really high-quality office chair and the reason why I'm now fully convinced that it really does pay off to invest in a good chair, just like everybody says it does. 

I'm not a big phone productivity nerd but I have to mention my [iPhone X][iphone-x]. This is probably the best computing device I've ever had. It's fantastic. It's fast as hell, the screen is incredible and the camera gets a "wait, what, you shot that with your phone?" every time I shove baby pictures into someone else's face. I couldn't ask for more. 

Another favorite device of mine is my NAS, a [Synology DS716+II][ds716-plus-ii] with a total capacity of 4TB. I bought it two years ago, when chances were already high that The Cloud, as it were, and mobile computing would win in their fight to eliminate "files", "hard drive" and "storage devices" from our collective vocabulary. I bought it because I'm fascinated by servers. Networked computers that run for months and years, without a keyboard, mouse or display and only tiny LEDs to give off a life signals - I've always wanted to have one at home. But, you know, one that actually does something useful, as opposed to the [OpenBSD][] server I kept in my teenage bedroom for which my parents had to pay the electricity bill - sorry! 

In other words: this NAS is quite literally the fulfillment of a childhood dream. It sits right next to the router, holds [Time Machine][time-machine] and photo backups, important documents and large media files. I can SSH into it from work through a VPN (which feels like magic) and, on top of that, the Synology software is fantastic. When I first got a grasp of how much custom software they write for DSM, the operating system than runs on the NAS, I couldn't believe it. 

Then I also have two Raspberry Pis. A [Raspberry Pi 1][raspberry-pi], which is taking a long nap in my desk drawer until I decide what I could use it for, and a [Raspberry Pi 2][raspberry-pi-2], which is hooked up to our TV and runs [OpenELEC][]. Next to it is an old [Apple TV][apple-tv], which we use to access streaming services without having to connect the TV itself to the internet. 

### And what software?

After 10 years of using [Linux][] as my main operating system, I was enlightened when I switched to [macOS][] around five years ago. Wifi works without compiling kernel modules; using an external screen means "plugging it in"; putting the computer to sleep and waking it up is not something I have to worry about; moving windows between an external display and the built-in Retina display works so well that I only thought about it when I found out that's apparently a problem with other OSes. Best of all, though: in five years I didn't had to edit the config file for an audio system once. 

I would love to switch back to Linux, because of its customizability and because I'm an admirer of free software and open source, but every time I give it a shot, I notice something that nobody ever mentioned in all the "Things have changed! Linux is now ready for the desktop!" discussions: the Linux touchpad drivers give touchpads a bad name, Bluetooth connections are flaky, you still have to edit _this one file_ and, well, yes, _this_ doesn't work, of course. 

All I really want from an OS is to get out of the way and a Unix shell. My two main applications, always running, are the browser, [Firefox][], and the terminal, [iTerm2][]. 

At any point in time, Firefox has at least two pinned tabs open: my private [Gmail][] account and my private [Fastmail][] account. In the past 10 years that I've used it, I've grown so attached to Gmail's keybindings that I don't want to switch to a client that doesn't have them. Fastmail, though, does and is also remarkably fast and its non-flat-UI is very pleasing to my eyes. 

In the terminal, everything happens in a [tmux][] session. It's my terminal session and window-manager. Every multi-day project I'm working on gets its own session and in the rare case that I have to reboot the computer, I persist and restore the sessions and their window layouts with [tmux-resurrect][].

My shell of choice is [zsh][] and has been for a few years. Back then, its completion system was far more advanced than Bash's, which is why I originally switched, but nowadays Bash has caught up and I can't give you any other reason for my attachment to zsh than this: my `.zshrc` is [395 lines long](https://github.com/mrnugget/dotfiles/blob/master/zshrc"Thorsten's .zshrc config file on GitHub.) and that's - roughly speaking - 395 lines more than I'm willing to port to Bash for equal features. 

Now, drumroll, fanfare, spotlight, take a deep breath, here comes the most important piece of software on my computer: my editor, [Vim][]. And, look, I'd really like to dedicate the next ten or twenty thousand words to Vim, but I fear that every non-Vim user would get cramps in their eyes from rolling them so far back in their head that instead I'll keep it short. 

After hesitating for years to customize my setup too much (because what if someone drops me in front of a vanilla setup and shouts "and now, show me what you've got!"?) I now freely and happily use a [bunch of plugins](https://github.com/mrnugget/vimconfig/blob/master/vimrc "Thorsten's .vimrc config file on GitHub."), mostly for language support and for running tests and linters. My `.vimrc` has grown whenever I noticed a little pain point I had and I now consider my setup pretty much complete. Especially after I switched to [Neovim][] for better performance and could run my tests in the built-in terminal emulator. 

I think Vim's modal editing, in combination with its language to manipulate text (e.g.: type `di"` to **d**elete the text **i**n in quotes), is by far the best approach to text editing. And not just when that text is code, no, I cherish Vim's features even when writing prose, because I read and edit text much more than I write it from top to bottom in an empty file. 

Vim also neatly fits into Unix philosophy, which dictates that a good tool does one thing and does it well and - this is the part people often forget - is easy to combine with other tools. I often pipe text into Vim or call other tools from inside it, to either format my text (type `:%!sort -rn` into your Vim to see what I mean) or to compile/test/run my code. 

Over the years, I've invested a lot of time in getting better at using Vim and I'd like to think that I'm pretty good at it by now (even though my dream of someone on the train tapping me on the shoulder and telling me "Hey, I saw how you use Vim. You're amazing. I'm going to name my child after you." is, as of now, still unfulfilled). But I've also seen and felt where the idea of the text editor as only a tiny part of a larger toolchain falls apart, where a myriad of composable tools would do well with just a tiny bit more coupling and integration. That lead me to dipping my toes into this endless well (some say: abyss) called [Emacs][]. It certainly has its charms to edit text inside this fully-programmable Lisp machine: you can hook into everything that happens in Emacs, you can redefine every key binding and function and you can extend the editor by simply writing and evaluating code. It's mighty and I might switch, but I feel like I need a sabbatical to get the most out of it. 

My note taking setup consists of Markdown files in a Dropbox folder as the storage engine and Vim and [fzf][] as the editing frontend. fzf a fantastic tool that I highly recommend to anyone using a command line. I use it to fuzzy search through the list of note files and can so easily edit an existing or create a new note. On my phone I use [1Writer][1writer-ios] to edit the Markdown files. 

My toolchain for writing books is a little bit more elaborate than _just_ Markdown files, but not by much. I wrote [a lengthy blog post](https://thorstenball.com/blog/2018/09/04/the-tools-i-use-to-write-books/ "Thorsten's post detailing what he uses when writing books.") on the topic that you can read if you want the details, but the short version is this: [pandoc][]. One of the best tools I've _ever_ used and I mean that. 

Outside of the terminal, these are the tools that I always install on a fresh macOS installation or currently use: [Todoist][] to keep track of small tasks and to hold my daily to-do list; [Arq][] to keep an encrypted backup of my computer on [Amazon S3][s3] (Time Machine is configured to back up to an encrypted external drive and the NAS); [1Password][] as my password manager; [iStat Menus][istat-menus] to quickly find our why the fans turned on; [SizeUp][] to center or maximize windows; [Karabiner][] for remapping external keyboards; [Fantastical 2][fantastical] as the calendar; [Annotate][] to take screenshots and draw on them; [Typora][] to take a quick look at Markdown files and to draw diagrams in them; [Monodraw][monodraw] to draw the diagrams for my books; [Postgres.app][] to run several versions of [PostgreSQL][] easily; [Postman][] to debug and document APIs.

Inside the terminal, my most cherished tools are, in no particular order: the Unix coreutils, [ripgrep][], [curl][], [git][], [jq][], [awk][], [sed][], [z][], [Homebrew][].

### What would be your dream setup?

My dream setup is not one, fully-formed idea, but rather a mixture of multiple wishes and inspirations. 

The first of these is full sync of applications and data between devices. Others call this "thin clients". Either way, what I want is to sit down at my computer and have access to the same files, tasks, notes, images, etc. that I just worked with on my phone. No local storage except for caching, everything's backed up and synced. When the computer dies I want to be able to get a new one, boot it up and - after an hour or so - see the same applications and data that I previously used. 

If you go all-in on an ecosystem (Apple, or Google, for example) you can get close to this ideal, but as soon as you put one foot outside - by switching out just your to-do app, for example - a lot of things start to break down: reminders don't work on your phone anymore, the calender is now missing due dates of tasks, and maybe the to-dos themselves don't sync between phone and computer. 

If every application had an API or offered direct access to its data, we could solve this. But, then again, opening up and generalizing for interoperability is oftentimes the opposite of the tight integration that made these applications work so well in the first place. Tough problem. 

The other idea is "programmability". I want to be able to hook into everything my computer and my phone do and run custom code or actions. I want to add buttons and shortcuts to apps and bridge them with my files and command line tools. I want to run custom code in web apps that connects them to my native applications. 

This wish for programmability is a result of my dance with Emacs. Because once you've used Emacs for a certain amount of time you start to wonder: why can't everything be like this? And the sad thing is that technically it _can_. 

You can already use things like [Automator][] on macOS, or Shortcuts on iOS. But that doesn't cover it. You also have to use [IFTTT][], because half of the things we do nowadays happen on the web. But the majority of these web applications don't have powerful APIs. And I know why they don't, because they're incredibly hard to build and don't generate immediate value for the business. 

But even leaving the web aside and just thinking in terms of your local machine, it's hard to reprogram everything, because not everything's integrated into automation tools or has an API. You could go really low and learn a myriad of languages, build systems and recompile everything you're using. But we all know that that's never going to happen. 

I don't have solution for this, nor do I know if it's even possible, but after using Emacs for some time I began to see why people move everything into it and manage their tasks, emails, notes and spreadsheets in it. 

The last idea in my dream setup is much more practical: we need to get rid of terminal emulators. It's 2018 and we're using software to emulate [hardware from the 70s][vt100] to run text-based command line utilities. Don't get me wrong, I want to keep the command line, but we should find something better than terminal emulators to run them in. Leaving aside the fact that terminal emulators still know about the concept of a baud rate, which they very much shouldn't since at least a decade, it just doesn't work: the performance when displaying text is still so bad that we're tweaking text editors and config file after config file just to get _text_ displayed faster. And if that doesn't work, we build [even faster emulators][alacritty]. 

Maybe we need to get rid of plain text, this holy relic of Unix, in order to make our command lines faster. But if that means that my editor won't stutter when I scroll through a 200 line file with syntax highlighting, then so be it, because that's certainly not part of my dream setup.

[1password]: https://1password.com "Password management software for Mac OS X."
[1writer-ios]: https://apps.apple.com/us/app/1writer/id680469088 "A text editor app."
[alacritty]: https://github.com/alacritty/alacritty "A fast terminal emulator."
[annotate]: http://web.archive.org/web/20201109034003/https://apps.apple.com/us/app/annotate-capture-and-share/id918207447 "Mac software for capturing and annotating screenshots."
[apple-tv]: https://en.wikipedia.org/wiki/Apple_TV "A device for viewing media on a TV."
[arq]: https://www.arqbackup.com/ "S3-based backup for the Mac."
[automator]: https://en.wikipedia.org/wiki/Automator_(software) "Software included with Mac OS X for creating script-based workflows."
[awk]: https://en.wikipedia.org/wiki/AWK "Data formatting language/software."
[curl]: https://curl.se/ "A command-line tool for transferring data from URLs."
[ds716-plus-ii]: https://global.download.synology.com/download/Document/Hardware/DataSheet/DiskStation/16-year/DS716+II/enu/Synology_DS716_PlusII_Data_Sheet_enu.pdf "A NAS device."
[emacs]: http://www.gnu.org/software/emacs/ "An extensible, customizable, free/libre text editor — and more."
[es-87]: http://web.archive.org/web/20190506063301/http://www.keyeduplabs.com/es-87.html "A mechanical keyboard."
[fantastical]: https://flexibits.com/fantastical "A calendaring app for the Mac."
[fastmail]: https://www.fastmail.com/ "An email hosting service."
[firefox]: https://www.mozilla.org/en-US/firefox/new/ "A cross-platform open-source web browser."
[fzf]: https://github.com/junegunn/fzf "A fuzzy finder for the command line."
[gesture]: http://web.archive.org/web/20190508113942/https://www.amazon.com/dp/B0141G9IHY/ "A desk chair."
[git]: https://git-scm.com/ "A version control system."
[gmail]: https://en.wikipedia.org/wiki/Gmail "Web-based email."
[homebrew]: https://brew.sh/ "Command-line package manager for Mac OS X."
[ifttt]: https://ifttt.com/ "A web service for applying rules to items, not unlike how you might filter your email."
[iphone-x]: https://en.wikipedia.org/wiki/IPhone_X "A 5.8 inch smartphone."
[istat-menus]: https://bjango.com/mac/istatmenus/ "A collection of Mac OS X menu items for monitoring your system."
[iterm2]: https://iterm2.com/ "An alternative terminal application for Mac OS X."
[jq]: https://stedolan.github.io/jq/ "A command line tool for manipulating JSON data."
[karabiner]: https://karabiner-elements.pqrs.org/ "Mac software for remapping the keys of your laptop."
[linux]: http://web.archive.org/web/20221224200715/https://linux.org/ "A free, open-source Unix-like operating system."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[macos]: https://en.wikipedia.org/wiki/MacOS "An operating system for Mac hardware."
[magic-keyboard]: https://en.wikipedia.org/wiki/Magic_Keyboard "A wireless keyboard."
[magic-trackpad]: https://en.wikipedia.org/wiki/Magic_Trackpad "A trackpad for desktop machines."
[monodraw]: https://monodraw.helftone.com/ "An ASCII art tool for macOS."
[neovim]: https://neovim.io/ "A refactored vim."
[ology]: https://www.steelcase.com/eu-en/products/desks/ology/ "An adjustable standing desk."
[openbsd]: http://www.openbsd.org/ "An open-source operating system emphasising security and cryptography."
[openelec]: https://en.wikipedia.org/wiki/OpenELEC "A media streaming OS for embeddable devices."
[pandoc]: https://pandoc.org/ "A Markdown document converter."
[postgres.app]: https://postgresapp.com/ "A bundled installation of Postgres for Mac OS X."
[postgresql]: https://www.postgresql.org/ "A relational database server."
[postman]: https://www.postman.com/ "A browser extension for testing APIs."
[raspberry-pi-2]: https://en.wikipedia.org/wiki/Raspberry_Pi "A single-board hackable computer."
[raspberry-pi]: https://en.wikipedia.org/wiki/Raspberry_Pi "A single-board hackable computer."
[realforce-87u]: https://www.elitekeyboards.com/products.php?pid=rf_se17t0&sub=topre_keyboards%2Crftenkeyless "A keyboard."
[ripgrep]: https://github.com/BurntSushi/ripgrep "A tool for searching directories via regular expressions."
[rival-110]: http://web.archive.org/web/20200313111916/https://steelseries.com/gaming-mice/rival-110 "A gaming mouse."
[s3]: https://aws.amazon.com/s3/ "Cloud-based Internet storage magic."
[sed]: http://www.gnu.org/software/sed/ "Text filtering software."
[sizeup]: https://www.irradiatedsoftware.com/sizeup/ "Mac software for arranging windows."
[time-machine]: https://en.wikipedia.org/wiki/Time_Machine_(Mac_OS) "Backup software for the masses, included with Mac OS X 10.5."
[tmux-resurrect]: https://github.com/tmux-plugins/tmux-resurrect "A tmux plugin for persisting sessions across restarts."
[tmux]: https://sourceforge.net/projects/tmux.mirror/ "A terminal multiplexer, similar to screen."
[todoist]: https://todoist.com/ "A to-do service."
[typora]: https://typora.io/ "A web-based Markdown editor."
[vim]: https://www.vim.org/ "A command-line text editor."
[vt100]: https://en.wikipedia.org/wiki/VT100 "A video terminal."
[z]: https://github.com/rupa/z "A command-line tool for quickly moving between directories."
[zsh]: https://www.zsh.org/ "An interactive shell and scripting language."
