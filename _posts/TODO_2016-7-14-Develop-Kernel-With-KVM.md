---
layout: post
title: Developing Linux Kernel using KVM
---

I am back to doing some kernel hacking so I am building my kernel as I write this post. 
Every time I try to build a kernel, I have to setup the whole environment again which 
requires a bunch of google searches and skimming a bunch of tutorial. I am writing this 
post to consolidate all of that so that the next time I pick this up, I don't have to search
everywhere. 

## Getting the source

From kenrel.org or from `apt-get` both work. 

{% highlight bash %}

map <F5> /<C-r><C-w> <CR> :vim /<C-r><C-w>/g % \| copen <CR>

{% endhighlight %}

Go over a word and press `F5` to open the quickfix window with the matches.
You can switch between the quickfix buffer and the main buffer by using
<Ctrl-w><w>. 





