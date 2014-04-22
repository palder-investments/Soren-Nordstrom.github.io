---
layout: post
title: Use wget to download the weekly CLR podcast
date: 2014-04-21 19:07
comments: true
external-url:
categories:
---

I hate web browsers.  They just keep getting bigger, and clunkier.  So, I try to do as much as possible from the command line, and getting my weekly techno fix from CLR.net is no exception.  I receive the RSS feed in my reader and get the number and name of this week's artist from there.  Then I cd into the directory where I keep those sorts of things.

``` bash
wget -c http://daten.clr.net/pod/CLRSRxxx_Artist_Name.mp3
```

The folks over at CLR are pretty good about sticking to their naming convention, so each week is just n+1 from last week's number and the title-cased artist name in the same URL.  

Easy-peasy, no fucking browser.

-sn
