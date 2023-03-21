---
title: Lincoln Mullen
summary: Historian, teacher
date: 2014-12-11
categories:
- developer
- historian
- linux
- mac
- teacher
---

### Who are you, and what do you do?

My name is [Lincoln Mullen](http://lincolnmullen.com/ "Lincoln's website.") and I'm a historian at [George Mason University](http://historyarthistory.gmu.edu/ "A university in Fairfax, Virginia."). I teach and write about American religious history; at the moment I'm writing a history of people who converted between religions in the nineteenth-century United States. I'm also a digital historian at the [Roy Rosenzweig Center for History and New Media](http://chnm.gmu.edu/ "A history and new media center in Fairfax, Virginia"). I'm responsible for teaching a [graduate course on computer programming for historians](http://lincolnmullen.com/courses/clio3.2014/ "A basic computer programming course aimed at scholars."), for which I'm writing a book (still very much a rough draft) on [using R for digital history](http://dh-r.lincolnmullen.com/ "Lincoln's book on R development.").

### What hardware do you use?

I have a [15" MacBook Pro][macbook-pro] with an Intel i7 processor, an SSD, and 16 GB of RAM provided by my department. I also use a [ThinkPad T430][thinkpad-t430] which was my main machine during graduate school. There is an unremarkable Dell external monitor on my desk. I have an [iPhone 5C][iphone-5c] but I more and more dislike using a phone for anything.

I really like my [Timbuk2 Command Laptop messenger][command]; I wouldn't change a thing about it.

### And what software?

I used to play around with software much too often. Now I've settled down with a few organizing principles influenced by Mike Gancarz's [*Linux and the Unix Philosophy*](http://www.amazon.com/gp/product/1555582737/ "A book about the thinking behind Unix and Linux."): I use Unix-style tools and store my data in plain text or flat files. Everything that I write is formatted in [Markdown][] using the [Pandoc][] extensions. [John MacFarlane's](http://john.macfarlane.usesthis.com/ "John's interview.") Pandoc is peerless for converting between markup formats. I use some custom [LaTeX][] templates with Pandoc. I use [Vim][], often in the terminal but usually in [MacVim][], for all text editing. Every project - writing, coding, you name it - is kept under version control with [Git][] and almost always made available on [GitHub][]. Almost every project is built by [GNU Make][make]. All of that is run through the shell, usually [ZSH][]. My [dotfiles](https://github.com/lmullen/dotfiles/ "Lincoln's dotfiles on GitHub.") and [Vim files](https://github.com/lmullen/vimrc/ "Lincoln's vim config files on GitHub.") are available on GitHub.

I used to write in several different programming languages, but now I use [R][] if at all possible. It took me some getting used to R and functional programming, but R really is a beautiful language for data analysis. It is made even better by the "Hadleyverse" of packages written by [Hadley Wickham](http://hadley.wickham.usesthis.com "Hadley's interview."), such as [dplyr][], [tidyr][], and [ggplot2][]. I use [Yihui Xie's](http://yihui.xie.usesthis.com/ "Yihui's interview.") [knitr][] package to write and code together in [R Markdown][r-markdown]. [RStudio][] (in Vim mode) is my only exception to the rule about using Vim for everything; it is a very nicely done IDE for R. Even better, I can use the server version of RStudio on a much more powerful machine, or for teaching a workshop, and get the same interface. If I can't write it in R, then I use [Ruby][], which is also beautiful. [JavaScript][] is not beautiful, but Mike Bostock's [D3.js][] is; I use it for interactive data visualizations and [maps](http://lincolnmullen.com/projects/slavery/ "Lincoln's maps of the spread of slavery.").

For managing citations I use [Zotero][], an excellent open-source application and web service by my colleagues at RRCHNM. My notes are written in Markdown, stored in Git, and edited in Vim, but they are turned into a wiki by [Gitit][].

For most websites, like my personal site or my course syllabi, I use [Jekyll][]. Jekyll is a static site generator written in Ruby so I'm comfortable writing plugins for it; it uses Markdown (with a Pandoc plugin) so I can write in plain text and keep the site under version control. For any kind of web exhibit or other scholarly website I use Omeka (think WordPress for galleries, libraries, archives, museums, and scholars). [Omeka][] is also created by my colleagues at RRCHNM. If I assign students to write blog posts, then I use [WordPress][]. I've been really pleased with [Reclaim Hosting](https://reclaimhosting.com/ "A web hosting provider targeting educators."), which provides hosting to educators and students.

The ThinkPad runs [Ubuntu 14.04 LTS][ubuntu]. Whenever I spool up a cloud or local virtual machine, it runs Ubuntu. I often use [Vagrant][] with [VirtualBox][] to create development environments. [Homebrew][] is obligatory for installing development dependencies on a Mac.

I use a few Mac or web apps: [iTerm2][iterm2] as a terminal emulator; [OmniFocus][] for task management, which I could probably use better; [BackBlaze][] for online backups; [DropBox][] for file syncing; [Caffeine][] to keep my monitor from going to sleep while I'm teaching; [QGIS][] for GIS work if I really must; [Transmit][] for FTP and Amazon S3; [TextExpander][] for snippets; [Spectacle][] for window management; [Feedly][] for reading feeds.

My open-source or open-access licenses of choice are MIT for software and CC-BY for prose.

### What would be your dream setup?

I have plenty of computing power and can rent more cheaply. I don't even have much to complain about when it comes to battery power. I wish that there was a way to teach students digital methods without going through the grime of setting up a development environment.

I've never found an e-reader that I liked. I want a device with a large-enough screen approaching an 8.5" by 11" piece of paper that could read e-books and PDFs of journal articles, nineteenth-century books, and students papers with equal ease, preferably with an e-ink screen. Is that too much to ask?

And most of all, I'd like more and more academic work in history and the humanities to be released online (in pre-prints like [arXiv](http://arxiv.org/ "Cornell's open library of educational resources."), or in final versions) in open formats and hopefully under open-access licenses.

[backblaze]: https://www.backblaze.com/cloud-backup.html "Online backup."
[caffeine]: http://lightheadsw.com/caffeine/ "A Mac menubar application to keep your computer awake."
[command]: https://www.amazon.com/Timbuk2-Command-Laptop-TSA-Friendly-Messenger/dp/B0068DTASQ "A TSA-friendly bag for laptops."
[d3.js]: https://d3js.org/ "A Javascript framework for manipulating data."
[dplyr]: https://github.com/hadley/dplyr/ "An R library for working with data frames."
[dropbox]: https://www.dropbox.com/ "Online syncing and storage."
[feedly]: https://feedly.com/ "A feed reader."
[ggplot2]: http://web.archive.org/web/20180506153516/http://ggplot2.org:80/ "A plotting system for the R language."
[git]: https://git-scm.com/ "A version control system."
[github]: https://github.com/ "A Git code repository service."
[gitit]: http://gitit.net/ "A wiki system backed by Git, darcs or Mecurial."
[homebrew]: http://brew.sh "Command-line package manager for Mac OS X."
[iphone-5c]: https://en.wikipedia.org/wiki/IPhone_5C "An iOS smartphone."
[iterm2]: https://iterm2.com/ "An alternative terminal application for macOS."
[javascript]: https://en.wikipedia.org/wiki/JavaScript "An interpreted scripting language."
[jekyll]: https://jekyllrb.com/ "A static site generator."
[knitr]: https://github.com/yihui/knitr "A dynamic report generation tool for R."
[latex]: https://www.latex-project.org/ "Typesetting software."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[macvim]: https://github.com/macvim-dev/macvim "A Mac GUI port of vim."
[make]: http://www.gnu.org/software/make/manual/make.html "Software to prepare code for compilation."
[markdown]: https://daringfireball.net/projects/markdown/ "An email-like format for marking up text."
[omeka]: https://omeka.org/ "Web publishing software aimed at scholars and museums."
[omnifocus]: https://www.omnigroup.com/omnifocus/ "Task management software for the Mac."
[pandoc]: https://pandoc.org/ "A Markdown document converter."
[qgis]: https://qgis.org/en/site/ "An open-source GIS mapping tool."
[r-markdown]: https://support.rstudio.com/hc/en-us/articles/205368677-R-Markdown-Dynamic-Documents-for-R "A version of Markdown that supports R embedding."
[r]: http://www.r-project.org/ "Software for statistical computing and graphics."
[rstudio]: https://www.rstudio.com/ "An IDE for the R language."
[ruby]: https://www.ruby-lang.org/en/ "An interpreted scripting language."
[spectacle]: https://www.spectacleapp.com/ "A Mac tool for moving and resizing windows."
[textexpander]: https://smilesoftware.com/textexpander "A Mac app for adding custom abbreviations for often-used text."
[thinkpad-t430]: http://shop.lenovo.com/us/en/laptops/thinkpad/t-series/t430/ "A 14 inch PC laptop."
[tidyr]: https://github.com/hadley/tidyr/ "An R library for tidying data."
[transmit]: https://panic.com/transmit/ "An FTP/SFTP client for the Mac."
[ubuntu]: https://www.ubuntu.com/ "A Unix distribution."
[vagrant]: https://www.vagrantup.com/ "Software for building and installing virtual dev environments."
[vim]: https://www.vim.org/ "A command-line text editor."
[virtualbox]: https://www.virtualbox.org/ "Open-source virtualisation software."
[wordpress]: https://wordpress.com/ "Weblog publishing software."
[zotero]: https://www.zotero.org/ "A research tool."
[zsh]: https://www.zsh.org/ "An interactive shell and scripting language."
