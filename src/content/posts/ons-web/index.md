---
title: 在网站上也可以玩Galgame？
published: 2026-01-03
pinned: false
description: 用OnscripterYuri部署web版ONS游戏
tags:
  - Galgame
  - 游戏
  - 网站
category: 教程
draft: false
image: ./cover.png
---
## **注意：本教程只适用于部署使用Onscripter引擎的游戏。**

众所周知，Onscripter引擎的最初设计目的就是为了方便跨平台移植用NScripter编译的游戏，所以得益于它高度可移植的SDL库，ONS游戏移植相对比较简单。

这次用到的是这个叫 [OnscripterYuri](https://github.com/YuriSizuku/OnscripterYuri) 的项目，这个项目是基于 [ONScripter-Jh](https://github.com/jh10001/ONScripter-Jh) 开发的，在原本只支持安卓的基础上增加了对`Windows`, `Linux`, `Mac`, `Web`, `RetroArch` and `PSV`的支持。

项目地址：
::github{repo="YuriSizuku/OnscripterYuri"}
