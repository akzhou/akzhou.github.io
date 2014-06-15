---
layout: post
title: 从Markdown开始
---

###想说点什么 

&emsp;&emsp;说实话，我并不善于文字表达。自从高中毕业以后，想想已经好久没提起过笔了，拿笔最多的时候就在刷信用卡签名之类的，至于大学都做了些什么，呵呵！为什么突然那么有兴致写点东西，主要是越来越觉得记忆力不如当年了,好记性还真不如烂笔头啊，于是想着把学到的知识记录下来，顺便也能分享给大家，希望有相同困惑的你能少走点我走过的弯路，互相学习共同进步。

&emsp;&emsp;选择Markdown的原因是刚好这东西之前我没接触过，发现它是那么的简单、方便，可以专注于写文章上面，而且可以在[github][]上面开个Github pages当blog使用，代码可以放到上面共享，在加上强大的版本管理，已经完全满足了我的需求了。

&emsp;&emsp;Markdown是什么？看名字就知道是记录东西的，其实就是一门标记语言，可以在写文章时做些符号标记就能达到很方便的排版美化的效果，后缀名一般是.md。

###编辑器安装
Windows 平台

*   [MarkdownPad](http://markdownpad.com/)
*   [MarkPad](http://code52.org/DownmarkerWPF/)

Linux 平台

*   [ReText](http://sourceforge.net/p/retext/home/ReText/)

Mac 平台

*   [Mou](http://mouapp.com/)

在线编辑器

*   [Markable.in](http://markable.in/)

Chrome插件

*   [MaDe](https://chrome.google.com/webstore/detail/made/oknndfeeopgpibecfjljjfanledpbkog)


#####RextText for Debian 安装步骤
	#debian
	ak@debian:~$ sudo apt-get install retext

#####RextText 3.1配置css需要修改ReText.conf，
下载[github.css](https://gist.github.com/2554919.git)。
为了方便管理，css文件放到用户目录的`.config/ReText\ project/`下
	
	ak@debian:~$ cd ~/.config/ReText\ project/
	ak@debian:~/.config/ReText project$ ls
	github.css  ReText.conf 

修改ReText.conf内容为：*/home/ak/*为用户目录     
		
	[General]
	useWebKit=true
	useReST=false
	defaultExt=md
	styleSheet=/home/ak/.config/ReText project/github.css
	autoSave=true
	restorePreviewState=true
	previewState=true


Windows,Mac平台都是很容易安装的，今天周末休息就折腾了一下Linux平台，由于手上是一台古老的IBM X40，1.5GHz CPU,1g内存，64G SSD硬盘,勉强可以跑个Debian，golang，lua还是可以的，这倒好，不qq不微博，可以安静学习，好了，先写这么多，洗澡睡觉调闹钟看世界杯！




[github]:github.com

