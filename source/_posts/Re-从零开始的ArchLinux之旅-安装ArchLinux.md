---
title: Re:从零开始的ArchLinux之旅-介绍ArchLinux
date: 2023-01-28 20:55:08
top_img: https://img.mailset.top/archLogo.png
cover: https://img.mailset.top/ArchLinuxAvatar.png
tags:
  - Linux
  - ArchLinux
  - 技术
  - 教程
---

## 欢迎来到ArchLinux之旅！

### ArchLinux介绍

本教程将围绕着ArchLinux开教程，所以这里介绍一下ArchLinux。

~~为了能激起你的兴趣，建议看一下[萌娘百科-Arch_Linux娘](https://zh.moegirl.org.cn/Arch_Linux%E5%A8%98) (误)~~

本文章将围绕着[Arch_Linux-官方教程](https://wiki.archlinuxcn.org/wiki/Arch_Linux)来介绍，建议搭配官方文章食用

官方对ArchLinux结词和我认为是最合适的结词是：Keep It Simple, Stupid(保持简单，且一目了然)

还有社区常说的一句话：Try It And See™

### 排名

ArchLinux在DistroWatch里面的排名不算太靠前，你可以去为他投一票[为ArchLinux投票](https://distrowatch.com/table.php?distribution=arch)

但是ArchLinux常年人气还是很高的，你可以看看BiliBili上推ArchLinux的有多少[BiliBili-ArchLinux](https://search.bilibili.com/all?keyword=ArchLinux)

### 特性

ArchLinux有极高的自定义性，不但安装系统用什么文件系统，分区多么奇葩(指/usr一个，/home一个，/tmp一个，/mnt一个，/proc一个，/root一个，/opt一个，/sys一个，/run一个，/var一个，/home一个......)，你还可以干出一些奇葩的操作(魔改linux内核并安装~~里面开机输出一些奇葩东西并把内核丢给你的室友，让他社死~~，随便安装桌面管理器~~一个电脑10个de和wm~~)之类的都不在话下~~前提是你会弄~~

### 包管理

ArchLinux始终拥有最新的软件包仓库，也就是滚动更新，内核(指linux包)，在新内核发出的一段时间之后，在ArchLinux软件仓库就会更新新版本，~~这一点直接完爆openSUSE风滚草~~，在2012年到2013年间就用Systemd代替掉了System V init，在2012年7月弃用了基于菜单的*Arch 安装框架 (AIF)*，替换成了*Arch 安装脚本([arch-install-scripts](https://archlinux.org/packages/?name=arch-install-scripts))*，并且拥有很全面的[ArchWiki](https://wiki.archlinuxcn.org/)

顺带一提，ArchLinux从 *2001年早期* 就由 **加拿大程序员和吉他师Judd Vinet** 开始开发了，并在 *2002年3月11日* 正式发行了0.1版，后来在 *2007下半年* ， **Judd Vinet退出了Arch的开发** ，并把统治权交给了 **美国程序员Aaron Griffin(开源软件不分国籍，想急的先别急)** ，原文在[这里](https://bbs.archlinux.org/viewtopic.php?id=38024)，并到目前仍是Arch开发者。而在2020年初，Arch使用了心得流程来选择未来的领袖，记载在[这里](https://wiki.archlinux.org/title/DeveloperWiki:Project_Leader)。 **Aaron Griffin** 决定不再担任领导，而Arch通过选举方式，确认了 **Levente Polyak** 为新的领导，相关记录在[这里](https://archlinux.org/news/the-future-of-the-arch-linux-project-leader/)，这样一看，ArchLinux真是一个又新又旧的系统呢

ArchLinux是受到了Slackware、BSD、PLD Linux和CRUX的启发，但是那时候这些发行版缺少包管理工具，所以Arch的创始人 **Judd Vinet** 以同样的简介原则编写了包管理器pacman，这也能算得上是包管理器的鼻祖了吧

---

这个教程就先写到这里，想看更详细的介绍信息，欢迎到[ArchLinux介绍](https://wiki.archlinuxcn.org/wiki/Arch_Linux)来看，下期将会出关于如何安装ArchLinux的详细教程。

同时欢迎来到我的ArchLinux交流QQ群：437308086，恭候着大家哦！
