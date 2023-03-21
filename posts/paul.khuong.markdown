---
title: Paul Khuong
summary: Principal engineer (Backtrace)
date: 2020-05-08
categories:
- developer
---

### Who are you, and what do you do?

My name is Paul Khuong and I'm a principal engineer at [Backtrace.io][backtrace], and an occasional blogger at [pvk.ca](http://pvk.ca/ "Paul's website."). I work and blog from home, with my girlfriend and our daughter.

### What hardware do you use?

After keyboard-gate, I stopped using Macs. My main computers are now two Chromebooks: a 2018 [Pixelbook][pixelbook] for personal stuff, and a [Pixelbook Go][pixelbook-go] for work. I find [Crostini][] is more than sufficient to run [emacs][] (and [Steam][], even!), plus wifi always works (: For serious work, I plug the Chromebooks into a 38" Dell [UltraSharp][u3818dw], and type on a Kinesis [Advantage2][]; that's the price of middle age.

I also go through a lot of paper. I always have a couple Triplus Fineliner pens on me, and usually a plain Moleskine notebook: they're easy to replace, and I find the combination gives me just the right level of friction. I used to scan my doodles with a Doxie [Flip][flip], but I can never find the thing anymore, so I've been playing with various phone apps to rectify pictures (the current contender is MS [Office Lens][office-lens]).

Finally, I rely on two baremetal machines for my computational experiments. My go-to machine is still the 4-way [E5-4617][xeon-e5-4617] I built in 2013 for my PhD work. When I'd rather have a lot of slow cores, I turn to a desktop Xeon Phi. Its watercooling system is so quiet, I may just have to stick to watercooled towers in the future.

### And what software?

On Chromebooks, I use [Chrome][] and [G Suite][g-suite], a lot :) Otherwise, I live in graphical mode emacs ([Wayland][]) on Crostini. Over the years, my dot emacs has gotten simpler: I change the default font, enable some Solarized light theme, start emacsserver, load [ParEdit][], [SLIME][] (however [Quicklisp][] sets it up), and [Magit][]... and that's it! Depending on my needs and the lunar phase, I'll switch to Calc mode, [SBCL][] + SLIME, or [IPython][] for quick computations.

When navigating code at work, I find [Sourcetrail][] works well on our reasonably sized [C][] and [C++][c-plusplus] applications.

My blog is a clumsily hacked up version of [Octopress][] + Koenigspress, recently rebased on top of [Jekyll][] 4.x. I'm pretty sure it only works by accident, but also don't really have time to spend on maintenance, so I should probably freeze whatever mess I currently have in a container.

Chat has been [irssi][] and [SILC][] for more than 15 years, except that I have to use Slack's web client since they shut down the IRC gateway.

### What would be your dream setup?

When I close my eyes to visualise complex issues, I tend to move things between 5-6 zones in my field of view. I don't think it would be practical to replicate that workflow with multiple monitors. However, I hope that light VR headsets will eventually support a high enough resolution for text-oriented work; having the focus follow my eyes across independent virtual desktops certainly *sounds* like a good fit :)

I'm still looking for a good alternative to C and (inline) assembly... I'm told [Rust][] might be it, but I haven't found a good excuse to try it out; in the meantime, I just invest in more and more test- and compile- time tools.

Finally, I have yet to find a reference manager I can really operate. I'll usually remember useful tidbits of information as I work on a problem, but no useful search term to pinpoint a reference: I'm more likely to roughly remember where or when I read the relevant paragraph than anything else. One of my long term projects is an application that records everything I read or watch on my personal devices, and lets me query that list by approximate geolocation and time.

[advantage2]: https://kinesis-ergo.com/shop/advantage2/ "A fancy ergonomic keyboard."
[backtrace]: https://backtrace.io/product/ "A service for tracking crash logs and exceptions."
[c-plusplus]: https://en.wikipedia.org/wiki/C%2B%2B "A compiled programming language."
[c]: https://en.wikipedia.org/wiki/C_(programming_language) "A compiled programming language."
[chrome]: https://www.google.com/intl/en/chrome/browser/ "A WebKit-based browser, where each tab runs in its own thread."
[crostini]: https://chromium.googlesource.com/chromiumos/docs/+/master/containers_and_vms.md#Crostini "A VM environment for Chrome OS."
[emacs]: http://www.gnu.org/software/emacs/ "A free open-source text editor."
[flip]: https://www.getdoxie.com/product/flip/index.html "A mobile flatbed scanner."
[g-suite]: https://gsuite.google.com/ "A hosted solution for email, calendaring and more."
[ipython]: http://ipython.org/ "An interactive shell for Python."
[irssi]: https://irssi.org/ "A CLI irc client."
[jekyll]: https://jekyllrb.com/ "A static site generator."
[magit]: https://github.com/magit/magit "A git mode for Emacs."
[octopress]: http://octopress.org/ "A weblog framework for Jekyll."
[office-lens]: https://www.microsoft.com/en-us/p/office-lens/9wzdncrfj3t8?activetab=pivot:overviewtab "OCR software."
[paredit]: https://www.emacswiki.org/emacs/ParEdit "An emacs mode for working with Lisp and Scheme source code."
[pixelbook-go]: https://en.wikipedia.org/wiki/Google_Pixel#Pixelbook_Go "A 13.3 inch Chrome OS laptop."
[pixelbook]: https://store.google.com/us/product/google_pixelbook "A 12.3 inch Chromebook."
[quicklisp]: https://www.quicklisp.org/beta/ "A library manager for Common Lisp."
[rust]: https://www.rust-lang.org/en-US/ "A programming language."
[sbcl]: http://www.sbcl.org/ "A Common Lisp compiler."
[silc]: http://silcnet.org/client.html "Conferencing and messaging software."
[slime]: https://common-lisp.net/project/slime/ "An emacs mode for working with Common Lisp."
[sourcetrail]: https://www.sourcetrail.com/ "A source code explorer."
[steam]: https://store.steampowered.com/ "A digital game distribution service."
[u3818dw]: https://www.dell.com/en-us/work/shop/dell-ultrasharp-38-curved-monitor-u3818dw/apd/210-amrc "A 38 inch monitor."
[wayland]: https://wayland.freedesktop.org/ "A windowing library for Linux. "
[xeon-e5-4617]: https://ark.intel.com/content/www/us/en/ark/products/64608/intel-xeon-processor-e5-4617-15m-cache-2-90-ghz-7-20-gt-s-intel-qpi.html "A CPU."
