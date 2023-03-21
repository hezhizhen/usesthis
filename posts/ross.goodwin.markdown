---
title: Ross Goodwin
summary: Creative technologist, artist, hacker
date: 2016-08-04
categories:
- artist
- developer
- mac
- scientist
- technologist
---

### Who are you, and what do you do?

I'm Ross Goodwin, and I'm a creative technologist, artist, hacker, data scientist, and recent graduate of [NYU ITP](https://tisch.nyu.edu/itp "A graduate program at NYU."). I am passionate about developing new forms and interfaces for written language, enabled by technology, and machine intelligence in particular. I've written two (rather long) essays about my recent experiments with writing and machine learning, which can be found here: [I](https://medium.com/artists-and-machine-intelligence/adventures-in-narrated-reality-6516ff395ba3 "Ross' article about machine learning."), [II](https://medium.com/artists-and-machine-intelligence/adventures-in-narrated-reality-part-ii-dc585af054cb#.rrb6659s6"Ross' other article about machine learning.").

Most recently, I made a film with [Oscar Sharp](http://www.thereforefilms.com/oscar-sharp.html "Oscar's about page.") called [*Sunspring*](https://www.youtube.com/watch?v=LY7x2Ihqjmc "Ross and Oscar's YouTube video."). It is, so far as we know, the first film ever created from a computer generated screenplay. I generated the screenplay by training an [LSTM recurrent neural network](http://colah.github.io/posts/2015-08-Understanding-LSTMs/ "A post about Recurrent Neural Networks.") on hundreds of science fiction screenplays, until it could adequately recognize patterns of individual characters to write dialogue and action descriptions on its own.

### What hardware do you use?

I do the vast majority of my work on a [13" MacBook Pro][macbook-pro] (c. mid 2014). However, the cloud resources I leverage are another story entirely. At any given time, I'm running four to six [Amazon Web Services][aws] instances to manage web scraping jobs, [Twitter][] bots, web application projects, and other tasks and projects best suited for remote execution. 

My primary computational workhorse is the NYU High Performance Computing facility, where I have access to 32 [NVIDIA Tesla K80 GPUs][tesla-k80], each with 24GB of GPU memory, along with large numbers of CPU cores and significant RAM allotments. I can simply [SSH][] into the login node for this facility, and I have all these resources available from my laptop. 

For portable applications, I've done a lot of work with various [Raspberry Pi][raspberry-pi] and [Arduino][] models. More recently, I've been using the NVIDIA Jetson platform, which is like a Raspberry Pi with a GPU, for a variety of projects including generating the final screenplay for Sunspring as well as my Camera, Compass, Clock project.

Another piece of hardware I've been using is the [Datamax O'Neil microFlash 4te thermal printer][microflash-4te]. I currently own three of them, and they're great for providing a tactile dimension to projects that might otherwise live entirely on a computer screen. They print much wider (over 4") than other thermal printers I've used, and they have built-in batteries, which come in handy for portable applications. While these printers are fairly expensive when purchased new, the manufacturer has been making the same printer model for over 10 years, and used ones can be picked up for quite a bit less than retail on [eBay][].

### And what software?

[Python][] was my first language, and I remain a devoted Python programmer. To me, it's still the most elegant and poetic programming language I've found, and the functionality of the standard library is incredible. Beyond that, my favorite Natural Language Processing library is [Pattern][], and I'm in the process of learning [TensorFlow][] for machine learning.

In [JavaScript][], I'm a big fan of [p5.js][], which is developed by a lot of my friends from ITP, and was created by my former ITP professor [Lauren McCarthy](http://lauren-mccarthy.com/ "Lauren's website."). (In Introduction to Computational Media at ITP, I learned the [Java][] version of [Processing][] from [Daniel Shiffman](http://shiffman.net/ "Daniel's website."), and I've found the paradigms I learned in that version carry over pretty smoothly to the JavaScript version.)

For machine learning, I've been using [Torch][], which uses the [Lua][] programming language. Along with writing my own code, I've experimented extensively with [Andrej Karpathy](https://github.com/karpathy "Andrej's GitHub account.")'s incredible open source contributions, which include [NeuralTalk2][] and [char-rnn][]. More recently, I switched to [Justin Johnson](https://github.com/jcjohnson "Justin's GitHub account.")'s [torch-rnn][], which is 7x more memory efficient than char-rnn.

### What would be your dream setup?

In the world of photography, there's a common condition called [G.A.S. ("Gear Acquisition Syndrome")](http://petapixel.com/2015/11/25/10-practical-tips-for-fighting-g-a-s-gear-acquisition-syndrome/ "An article about Gear Acquisition Syndrome."), which is pretty well known. I think many people are also prone to the same "gear lust" with respect to new computers. In general, I try not to lust after new equipment, so long as what I'm currently using remains adequate for what I want to do. So far, that's been the case, so I suppose my "dream setup" is my current setup. 

That said, I'd absolutely love to own a personal machine learning rig with at least 4 K80 GPUs, running [Ubuntu][] Linux, and a nice large monitor for designing web interfaces (and staring at smoothly rendered high-def fractal patterns). Or maybe one of these new [NVIDIA deep learning appliances][dgx-1], which unfortunately cost about as much as a modest house in most places.

[arduino]: https://www.arduino.cc/ "Open-source prototyping hardware."
[aws]: https://aws.amazon.com/ "Amazon's web service platforms."
[char-rnn]: https://github.com/karpathy/char-rnn "A Recurrent Neural Network library for Torch."
[dgx-1]: https://www.nvidia.com/object/deep-learning-system.html "A deep learning appliance."
[ebay]: https://www.ebay.com/ "An auction service."
[java]: http://web.archive.org/web/20221226094350/https://www.java.com/en/ "A cross-platform compiled programming language."
[javascript]: https://en.wikipedia.org/wiki/JavaScript "An interpreted scripting language."
[lua]: http://www.lua.org/ "An interpreted scripting language."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[microflash-4te]: http://web.archive.org/web/20170716082621/https://www.datamax-oneil.com/do/com/en-us/home/printers-software/portable-printers/ultra-rugged-receipt-printers/microflash-4te "A receipt printer."
[neuraltalk2]: https://github.com/karpathy/neuraltalk2 "Image captioning code for Torch."
[p5.js]: https://p5js.org/ "A Javascript library based on Processing."
[pattern]: http://www.clips.ua.ac.be/pages/pattern "A web data mining module for Python."
[processing]: https://processing.org/ "A programming language/environment."
[python]: https://www.python.org/ "An interpreted scripting language."
[raspberry-pi]: https://en.wikipedia.org/wiki/Raspberry_Pi "A single-board hackable computer."
[ssh]: https://en.wikipedia.org/wiki/Secure_Shell "A command-line tool for secure remote connections."
[tensorflow]: https://www.tensorflow.org/ "An open source machine learning library."
[tesla-k80]: https://www.nvidia.com/object/tesla-k80.html "A GPU-based accelerator."
[torch-rnn]: https://github.com/jcjohnson/torch-rnn "A Recurrent Neural Network library for Torch."
[torch]: http://torch.ch/ "A Lua-based computing framework."
[twitter]: https://twitter.com/ "An online micro-blogging platform."
[ubuntu]: https://www.ubuntu.com/ "A Unix distribution."
