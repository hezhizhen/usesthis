---
title: Janelle Shane
summary: Research scientist, neural network trainer
date: 2017-09-07
categories:
- mac
- researcher
- scientist
---

### Who are you, and what do you do?

By day I'm a research scientist at a small R&D company. I do holographic and other kinds of liquid crystal laser beam steering.

In my spare time, I also train neural networks to generate entertaining nonsense. I run a blog at [lewisandquark.tumblr.com](http://lewisandquark.tumblr.com/ "Janelle's neural networks website.") where I've trained neural networks to generate paint colors, cookbook recipes, and even guinea pig names.

### What hardware do you use?

I'm using a [2010 MacBook Pro][macbook-pro], with big dents where I dropped it twice. The screen's once-round corner is now polygonal, and the case near the hard drive is now crumpled. The second impact disturbed the connections between the body and the screen, and produced weird teal stripes over everything. I tweaked the color balance until the stripes went away, and now the display looks normal except for everything that used to be black is now pulsating a deep demonic red. The battery life is approximately one hour, and maybe 15 minutes if I'm running a neural network. It's got a GPU, but it's too old to run [CUDA][], forcing me to do CPU-based computations instead. So I'm thinking of maybe getting a new laptop one of these years.

I now run bigger datasets on [AWS][] (Amazon Web Services), but still prefer to run the smaller lists of names on the MacBook Pro.

### And what software?

I do my work with recurrent neural networks, which are machine learning frameworks that can learn to imitate input datasets. Unlike traditional programming where a programmer figures out the rules and teaches them to the computer, with neural networks the programmer gives a dataset to the computer and tells it to figure out its own rules. The process is similar in many ways to how people learn - and the earliest neural networks were designed for studying the workings of biological brains.

The framework I started out on is a [char-rnn][] (character-based recurrent neural network) programmed in [Torch][] by Andrej Karpathy. I still use this a lot for the smaller datasets, because I like how simple it is to sample from old checkpoints, or to change the temperature during sampling, and it's lightweight enough to run on the 2010 Macbook Pro's CPU.

For bigger datasets, I like the [TensorFlow][]-based char-rnn that Chen Liang [has implemented][tensorflow-char-rnn]. It can take advantage of the AWS's GPU acceleration, and what really sets it apart from the other tensorflow char-rnn implementations is its flexibility in letting me go back and look at earlier points in the neural network's learning process.

I've also been experimenting with the visual neural network framework by Prof. Mark Riedl of Georgia Tech.

### What would be your dream setup?

One day, I'd like to have a MacBook Pro for everyday use and a cheap Linux machine with a decent GPU at home to run calculations. AWS is handy, but I always have to remember to shut down my session after my calculations are done. An iPad would be nice to use as a lab notebook, but it would make an even better travel computer if it could run regular programs like the [Surface Pro][surface-pro] can. Maybe one of these days.

[aws]: https://aws.amazon.com/ "Amazon's web service platforms."
[char-rnn]: https://github.com/karpathy/char-rnn "A Recurrent Neural Network library for Torch."
[cuda]: https://en.wikipedia.org/wiki/CUDA "A programming platform for GPUs."
[macbook-pro]: https://www.apple.com/macbook-pro/ "A laptop."
[surface-pro]: http://www.microsoft.com/surface/en-us/support/browse/surface-windows-8-pro "A tablet/laptop hybrid."
[tensorflow-char-rnn]: https://github.com/crazydonkey200/tensorflow-char-rnn "A Recurrent Neural Network library built on top of TensorFlow."
[tensorflow]: https://www.tensorflow.org/ "An open source machine learning library."
[torch]: http://torch.ch/ "A Lua-based computing framework."
