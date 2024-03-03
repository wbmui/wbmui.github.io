---
layout: post
title:  "Windows Polaris OS"
date:   2023-06-12 12:00:00
categories: Windows
author: WinBetaUser
image: http://i1.wp.com/wptavern.com/wp-content/uploads/2014/12/jekyll.png
---

关于 Windows Polaris OS 的介绍详见 [BetaWiki](http://betawiki.net/wiki/Windows_Polaris_OS)。
<!--more-->

Windows Polaris OS 是 Windows Core OS （简称 WCOS）的取消变体，它和 Windows Andromeda OS 一起取消后变成了 Windows 10X。它只泄露了一个版本，但是缺少大量 shell 文件，导致开机后黑屏。它是 ARM32 架构的，因此我们可以用 [GitHub @binarymaster 提供的为 Windows RT 兼容性进行修改的 QEMU](https://github.com/binarymaster/qemu/releases/tag/v6.2.0-winrt-v3) 进行模拟。

注：请不要把 Windows Core OS 与 Windows Core 混淆。Windows Core Build 16236 是泄露的 ARM32 架构系统，但是安装起来比较麻烦。
{:.info}

### 启动画面

![polaris-os-img0](\images\polaris-os-boot.png)

### 概念图片

![polaris-os-img0](\images\polaris-os-img0.png)

![polaris-os-img1](\images\polaris-os-img1.png)

### 下载

请前往[下载中心](/download)的“系统镜像”部分下载。

位置：用于移动设备的 Windows\Windows Polaris OS\\<对应文件>

