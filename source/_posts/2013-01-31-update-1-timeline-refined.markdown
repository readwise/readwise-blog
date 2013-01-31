---
layout: post
title: "R/W Update#1: 更好的时间线"
date: 2013-01-31 14:41
comments: true
categories: ann
author: Sun Ning
author-url: http://sunng.info/
---

![I don't always test my code, but when I do I do it on production](http://i.imgur.com/wReNhae.jpg)

这周的工作，界面上能展示的不多。我们对时间线做了比较大的手术。

<!-- more -->

原先的时间线的工作机制，是以☐☐☐☐☐☐☐☐☐☐☐☐☐（此处省略200字）。这样的机制有两个明显的问题：

1. 看过和没有看过的文章常常交错在一起，让人迷惘
2. 一夜过后，时间线上出现很神奇的情况，文章的热度排列为「冷...热...冷...热...」

不仅是很多用户，我自己使用的过程中也感到很不方便。于是我们痛下决心，抄起键盘对时间线大刀阔斧一番。
一小时前上线的版本已经基本解决了上面提到的问题。如若问题依旧，请参考题图。

还有可以提一句，用户名旁边显示的数字是你的 **Karma**。目前 **Karma** 可以通过评论和评论被投票获得。

![karma screenshot](http://i.imgur.com/tqjVRN6.png)

还有什么比工程师写得产品博客更平淡的，而且他还要一边 test on production。

对对对，我们的工程师 [debugger87](https://github.com/debugger87/) 昨天回家结婚，顺便过年了，我们祝他新婚愉快。

