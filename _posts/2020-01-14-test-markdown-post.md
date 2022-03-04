---
toc: true
layout: post
description: This is tedious
categories: [markdown]
comments: true
title: What it takes to set up an automated, freely hosted blog
---
# First post config

I'm not good at markdown, but wow this thing was a pain to get configured. Even created an issue just for the main issue I was running into, which baffled me at first but I stuck to my guns and read through the whole error stack to see what the root cause of the error was, rather than what it just stated. I suspect it is some dependency issue, and the author has not tested with the latest version of the minima theme. The problem is that the '''theme-remote''' flag always gets the latest version, but for some reason that doesn't mean the committer has tested it? I'm not sure at the moment, but I reverted to an older commit and it's working fine now.

To be continued