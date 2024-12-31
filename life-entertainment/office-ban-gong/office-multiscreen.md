## Spacedesk
[![website_official](https://gitbook07.oss-cn-hangzhou.aliyuncs.com/website_official.svg)](http://www.spacedesk.net/)

> Windows network display monitor software 

无线将你同一局域网内的各种设备拓展成为windows的第二屏幕。

## Xdisplay

一款由Splashtop公司开发的软件，它可以将您的iPad、Android平板电脑、Kindle或智能手机变成高性能的第二显示器。支持多种设备和操作系统，包括Windows、macOS、iOS和Android。

Xdisplay可以通过USB连接将您的设备或平板电脑连接到计算机，以实现第二显示器的功能。它支持多种分辨率，包括1080p和60fps。Xdisplay还支持多个显示器，可以扩展或镜像您的显示器。

https://www.splashtop.com/wiredxdisplay

Github: https://github.com/topics/display

## AirDroid

官网：https://www.airdroid.cn/

AirDroid作为一款远程控制软件，无需数据线，搭配AirDroid电脑客户端或电脑浏览器打开网页版，即可实现电脑对手机的在线管理。能够在主流操作系统Windows、Linux、Mac、Android、iOS间进行跨平台协同操作，支持在设备间无损传输各类文件、远程操控移动设备、接收回复手机消息、手机投屏，收听设备环境音等多种功能。

## Vysor
[![website_official](https://gitbook07.oss-cn-hangzhou.aliyuncs.com/website_official.svg)](https://www.vysor.io/) ![translation](https://gitbook07.oss-cn-hangzhou.aliyuncs.com/translation.svg)

> A window to your Phone

免root实现电脑控制手机 , 支持[`Windows` 、`macOS`、 `Linux`、`browser`]

## Scrcpy
[![website_official](https://gitbook07.oss-cn-hangzhou.aliyuncs.com/website_official.svg)](https://github.com/Genymobile/scrcpy  )![translation](https://gitbook07.oss-cn-hangzhou.aliyuncs.com/translation.svg)

可视为开源免费版的 Vysor 替代品，可以将安卓手机的画面投屏到电脑桌面显示上并进行操控，支持[`Windows` 、`macOS`、 `Linux`]，支持 USB、WiFi 两种方式连接，无需在手机安装任何应用，无需 root。

支持鼠标控制、电脑键盘输入、电脑剪切板复制粘贴(互通剪贴板)、拖放文件传输到手机、以及拖放 APK 文件进行安装。

Github: https://github.com/Genymobile/scrcpy
https://github.com/Genymobile/scrcpy/releases/tag/v1.18

**Scrcpy GUI增强版**

作者：酷安@晨钟酱，一个全平台（Windows、macOS、Linux）的开源工具，通过图形界面封装了Scrcpy的命令行参数，方便使用， github：https://github.com/Tomotoes/scrcpy-gui （停止维护2022）。

QtScrcpy: https://github.com/barry-ran/QtScrcpy

> Android real-time display control software

**AnLink国产增强版**

[![website_official](https://gitbook07.oss-cn-hangzhou.aliyuncs.com/website_official.svg)](https://cn.anlinksoft.com/ )

官网：https://anl.ink/

下载：https://cn.anlinksoft.com/download/

支持所有品牌的Android手机,WiFi和USB连接,多点触控,共享剪贴板等， 仅用于Windows。

**网页版**

在浏览器中控制手机

https://github.com/yume-chan/ya-webadb

https://app.tangoapp.dev/

## ReDroid

用现成的服务器的直接搭建云手机，参考：[基于ReDroid搭建云手机](https://www.jianshu.com/p/a6b5bedcc205) 23.1

## PiP-Tool

PiP tool is a software to use the Picture in Picture mode on Windows. This feature allows you to watch content (video for example) in thumbnail format on the screen while continuing to use any other software on Windows.

Github: https://github.com/LionelJouin/PiP-Tool (画中画，最近更新2019，疑似作者已弃坑)

## 串流软件

> Streaming (串流处理) 是指透过网际网路传输数位音讯或视讯。声音和影像资料会以资料流的方式传送给用户，因此使用「串流处理」这个名词。串流处理的主要优势是使用者不需等待下载完成就可以检视或收听所接收的媒体。

----

**MoonLight（SunLight）**: Moonlight是NVIDIA开源项目之一，可以方便的将PC电脑画面传输到各主流操作系统的客户端甚至谷歌浏览器上，交互支持键鼠/手柄/触摸屏/触控板/触控笔，就像用自己的电脑一样方便。 支持多种平台，包括安卓、iOS、Windows、Mac和Linux。

> 客户端CLIENT指观看画面的设备，主机指运行SUNSHINE的电脑, 三个端口打开命令如下：
>
> ```bash
> netsh advfirewall firewall add rule name="GameStream UDP" dir=in protocol=udp localport=5353,47998-48010 action=allow
> netsh advfirewall firewall add rule name="GameStream TCP" dir=in protocol=tcp localport=47984,47989,48010 action=allow
> ```

Moonlight官网地址：https://moonlight-stream.org/

Github地址：https://github.com/moonlight-stream 

**Steamlink**: 由V社 Steam出品的串流软件，可以将PC上的游戏串流到其他设备(ios，平板，电视等设备等)上。

**AMD Link**是AMD官方出品的串流软件，支持使用AMD显卡进行串流。

https://www.kast.gg/： Watch parties made easy.

**Parsec：**https://www.bilibili.com/video/BV1vF411j7bc (可能是世界上最好的远程控制软件——parsec) 
注意： Parsec属于商业软件，Parsec没公网ip寄一半

## 国内手机电脑生态

华为电脑管家（huawei/honor）

互传: https://es.vivo.com.cn/

 lenovo one lite

米卓同屏助手

将ipad投屏到windows上可用蓝莓投屏(buleberry Airplay)

Macast: DLNA投屏工具