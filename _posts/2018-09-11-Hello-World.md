---
layout: post
title: Hello World - Tools & Environment Setup
---

So you're interested in reversing video games, eh? It's a long process with a steep learning curve, yet challenging, fun, and rewarding. In this first post I will list all the tools and base knowledge you'll need to start your journey into the RE world.

<!--more-->

Disclosure: I am not a professional reverse engineer. 

![_config.yml]({{ site.baseurl }}/images/config.png)


## The Essentials

Since nearly every PC game is developed for Windows, that is the OS we will be using. Thankfully there are plenty of tools developed to make our lives much easier.

### Dynamic Analysis - Cheat Engine

[https://www.cheatengine.org](https://www.cheatengine.org)

It's likely you've heard of this before or used it for the memory scanning feature. Don't be fooled however, Cheat Engine is in my opinion the best tool available to us for dynamic analysis on Windows. It's been around for years and has many advanced features that will eventually come in handy once you learn how to utilize them effectively. Cheat Engine receives steady updates, plus it's even open source!

Your experience with CE may range from zero to advanced, depending on how much you've used it in the past.

### Static Analysis - Interactive Disassembler

[https://www.hex-rays.com/products/ida/index.shtml](https://www.hex-rays.com/products/ida/index.shtml)

While IDA Pro is not free (the price is quite expensive for individuals.) This is my choice for static analysis. There is however a free version of IDA but it is limited in features. I recommend it anyway since you won't be using most of them for some time anyway.

### Code Development - Visual Studio

[https://visualstudio.microsoft.com/](https://visualstudio.microsoft.com/)

My preferred IDE. Most applications I write are either C or C++. Visual Studio supports a few more which might come in handy depending on what exactly you're reversing or trying to write.

Hopefully you have at least a couple months of experience with a programming language. It doesn't really matter which as long as it can be used to develop executable apps. I will be using C++ throughout most of my posts.

## Miscellaneous

### dnSpy

[https://github.com/0xd4d/dnSpy](https://github.com/0xd4d/dnSpy)


### Final Thoughts

This is just my personal setup. Don't restrain yourself to anything you don't want/need. There are plenty of alternatives to everything listed above. Find what works best for you and get comfortable with it.

Next up are a couple quick tutorials on using these tools.
