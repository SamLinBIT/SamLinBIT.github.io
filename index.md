# 电脑空间清理

> C盘空间越来越小，导致电脑系统变卡了怎么办？
>
> 超极本的硬盘太小，莫名奇妙就满了，垃圾又不知道怎么清理怎么办？

以上这些磁盘空间不足的问题是我最经常被问到的问题，而这个问题某搜索引擎中的总是建议安装那些形形色色的「xx助手」「xx管家」，事实上安装了以后也没有能够很好地清理电脑，而且还会暗中做一些奇奇怪怪的事情。

磁盘上的垃圾文件主要有两大类：

1. 系统在日常工作中产生的文件，特点是非常细碎，且大部分人不懂得如何清理；
2. 自己下载了大型文件而忘记进行归档或删除，导致大量磁盘空间被占用而不自知。

本篇文章分别来讲讲如何清理这两种类型的垃圾文件，让你夕阳红硬盘重焕荣光。

![夕阳红](https://i.loli.net/2018/03/10/5aa3c1aa17d71.png)

## 系统垃圾清理 

清理系统垃圾经常被推荐的是CCleaner，但这款软件的对于某些win10的垃圾似乎有点不太能照顾到。本文推荐使用的是Dism++，这是一款由初雨团队打造的一款小巧，易用的系统优化软件，功能包括空间回收，系统优化，更新管理，系统备份等等。

我们只讲解空间清理的部分，进入软件的空间回收后，就能对系统中各类过期缓存，无用历史记录等项目进行扫描，可以对相应项目进行清理。可以说是一键操作，非常简单。

![Dism++](https://i.loli.net/2018/03/10/5aa3b4593f83b.jpg)

需要注意的是，系统还原点是一个占用很大空间的备份文件，在你确认现有系统没有问题时再去删除还原点。

[Dism++的官网地址](https://www.chuyu.me/zh-Hans/)

## 大型文件清理

磁盘清理完系统缓存文件后，磁盘依然还有大文件需要清理，可能是下载的电影随意乱放再也没找到，却占用了巨大空间，而我们又无法一个个文件来排查，此时就需要Space Sniffer这款软件来自动排查磁盘空间里分别都有哪些文件，并根据文件大小来显示文件块。

![Space Sniffer](https://i.loli.net/2018/03/10/5aa3bb9056e0d.jpg)

对文件块点击右键-属性就能查看文件所在位置，针对性地做清理。

值得注意的是，某些品牌会在电脑`C:\SWSETUP\Install`文件夹中留下电脑驱动，可以备份后将其删除，可以省下大量空间。

[Space Sniffer官网地址](http://www.uderzo.it/main_products/space_sniffer/)

## 结尾

对于第一部分的系统空间的清理并不需要经常做，因为系统需要一些缓存来加快加载速度，请强迫症同学们一定要管住手😂。而对于大型文件则需要在平时养成对文件进行归档的好习惯，避免大文件乱放而不自知。希望大家可以不用再为磁盘空间不知道怎么就占满而心力交瘁地重装系统啦~
