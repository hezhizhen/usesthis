---
title: Colin Percival
summary: Developer, security officer (FreeBSD)
date: 2010-06-27
categories:
- bsd
- developer
---

### Who are you, and what do you do?

I'm [Colin Percival](http://www.daemonology.net/blog/ "Colin's weblog."). I'm a FreeBSD developer since 2004, the FreeBSD Security Officer since 2005, and since 2006 I've been working on the [Tarsnap][] online backup system (which launched in 2008).

### What hardware do you use?

I do all of my work from a [Dell XPS M1530][xps-m1530] laptop -- Core 2 Duo T9300 (2.5 GHz) CPU, 3 GB of RAM, 250 GB hard drive. I don't really like this laptop: It runs quite hot, and all of its air intake is on the bottom, so it tends to overheat if I place it on a bed or carpeted floor.

As for servers: Lots of them, and I'm not entirely sure what all the hardware is. I use 6 dedicated servers plus a few virtual machines for various FreeBSD Security Officer functions; my personal website is hosted on a virtual machine at rootbsd.net, as is the Tarsnap website; and the Tarsnap backup service currently runs off a single Amazon EC2 instance (plus S3 storage).

I use [an HTC Dream][g1] (aka G1) phone.

### And what software?

On my laptop, I run [FreeBSD][] 7.3 (I've been meaning to upgrade to 8.0 but haven't gotten around to it yet) and [KDE][] 3.5. I use [Konqueror][] as a web browser whenever possible, but have [Firefox][] 3.6 installed for websites where Konqueror doesn't work. I use [Thunderbird][] 2.0 for email -- yes, I still download all of my email to my laptop. I do all of my coding in [kwrite][], and use [nano][] when I need to edit files from a command line; I've never seen much sense in the [emacs][] vs. vi wars. I do backups via Tarsnap, of course.

On servers I mostly run FreeBSD 8.0, but a few systems are still on 7.x (simply because I haven't gotten around to upgrading them yet). I use [djbdns][] for DNS (both authoritative and caching); [qmail][] for email; [ezmlm][] for mailing lists; [Apache][httpd] for web serving (I would probably not pick Apache if I cared about performance, but I don't do anything which needs fantastic HTTP serving performance); [stunnel][] for SSL termination (for security reasons, I prefer to keep SSL termination separate from HTTP serving); and of course Tarsnap for backups.

The exception to the above is the [EC2][] instance which runs the Tarsnap service: Unfortunately this is running [Ubuntu][], since FreeBSD doesn't yet run in EC2. I'm hoping this will be remedied soon (and want to hear from anyone else who wants to run FreeBSD on EC2 -- see [my recent blog post](http://www.daemonology.net/blog/2010-04-05-FreeBSD-EC2.html "Colin's post on FreeBSD and EC2.")), since I much prefer FreeBSD.

I run the standard [Android][] code on my phone, with [Twidroid][twidroid-android] installed for accessing Twitter, and [ConnectBot][connectbot-android] for SSH.

### What would be your dream setup?

On the desktop, there are two options. The practical one is something like the M1530, except more solidly built (my previous laptop was a Dell Latitude D600, and I noticed a big difference in build quality), not as hot-running, and with an SSD instead of the spinning drive.

The more fantastical option is a lightweight system with just enough power to run X and connect wirelessly to a server. Something like an iPad, except with a built-in hardware keyboard and running FreeBSD. I'd like to have access to a reasonable amount of computing power, but there's really no reason why it needs to be *physically* sitting in my lap. A [Dell Latitude Z][latitude-z] might work; I'm not sure.

Either way, I don't need any fancy 3D graphics, but I do want a reasonably large display and a high resolution, since I enjoy being able to have several shells plus a couple windows with 50 rows x 80 columns of code visible at a time.

On the server side, aside from the lack of FreeBSD on EC2, I'm really quite satisfied. Generally speaking I prefer multiple small boxes rather than a single large box. I could use one or two powerful (4+ core, 4GB+ RAM) boxes to speed up some FreeBSD work, but it wouldn't make a huge difference.

[android]: https://developers.google.com/android/?csw=1 "A mobile phone platform."
[connectbot-android]: https://connectbot.org/ "A secure shell for Android devices."
[djbdns]: http://cr.yp.to/djbdns.html "DNS server software."
[ec2]: https://aws.amazon.com/ec2/ "A web service for virtualised processing."
[emacs]: http://www.gnu.org/software/emacs/ "An extensible, customizable, free/libre text editor — and more."
[ezmlm]: http://www.ezmlm.org/ "Mailing list management software."
[firefox]: https://www.mozilla.org/en-US/firefox/new/ "A cross-platform open-source web browser."
[freebsd]: https://www.freebsd.org/ "An open source operating system."
[g1]: https://en.wikipedia.org/wiki/HTC_Dream "An Android smartphone."
[httpd]: https://httpd.apache.org/ "Web server software."
[kde]: https://kde.org/ "A graphical environment for *nix operating systems."
[konqueror]: http://web.archive.org/web/20200909184352/https://kde.org/applications/internet/org.kde.konqueror "An open-source web browser."
[kwrite]: https://kate-editor.org/ "A simple text editor for KDE."
[latitude-z]: https://www.techtarget.com/technologyguide/ "A super thin PC laptop."
[nano]: https://www.nano-editor.org/ "A command-line text editor."
[qmail]: http://web.archive.org/web/20220803223549/http://qmail.org/top.html "An SMTP server."
[stunnel]: https://www.stunnel.org/index.html "A tool to make any TCP connection over SSL."
[tarsnap]: http://www.tarsnap.com/ "An online backup system, aimed at *nix-based computers."
[thunderbird]: http://web.archive.org/web/20070322094547/http://www.thunderbird.net:80/ "An open-source cross-platform mail client."
[twidroid-android]: https://www.bluestacks.com/blog.html "A Twitter client for Android devices."
[ubuntu]: https://ubuntu.com/ "A Unix distribution."
[xps-m1530]: https://en.wikipedia.org/wiki/Dell_XPS#XPS_M1530 "A PC laptop with a 15.4 inch screen."
