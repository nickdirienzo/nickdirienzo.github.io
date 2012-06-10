---
layout: post
title: "Use a Static Blogging System"
date: 2012-06-10 10:44
comments: true
categories: [Blogging, Octopress]
---
I know I said I would make the switch yesterday. And I know I said I would write up a post about my first week at Google. But, I had a busy Saturday with friends, so I just pushed it back a day. No big deal. 

I apologize about switching between three different blogging platforms within three days. I've been saying I am going to blog more this summer, since I have some interesting topics to talk about now. However, I could not have relied on my custom engine because there was a lack of metadata and features, and I didn't want to iterate on it more right now; Blogger didn't allow me to have fine grain control, so that was also out. I wanted a rock solid system, so I searched for one.
 
I hunted around, and came across this [Ask HN](http://news.ycombinator.com/item?id=3414277) question. The [top rated comment](http://news.ycombinator.com/item?id=3415061) said to move away from the notion of a blogging platform and switch to a static blogging system. He recommended [Octopress](http://octopress.org/), which this site is now powered by!

It was really easy to get up and running. The setup documentation was spot on, but the only annoyance I had was providing my `read/write url` for my repo. Turns out, it's just `git@github.com:username/username.github.com.git.` 

Once you have it all configured, you just run `rake generate` then `rake deploy`. Since this is a "blogging framework for hackers," you should also be on top of pushing to source. 

I'll summarize my week later today in a different post. Sorry to keep you waiting. :)
