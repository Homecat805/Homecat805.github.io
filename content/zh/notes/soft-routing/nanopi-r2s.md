+++
title = '友善 NanoPi R2S 路由器的基础用法'
date = 2024-08-12T12:21:20+08:00
draft = false
weight = 1
[params]
  author = 'Homecat'
+++

友善 NanoPi R2S（以下简称R2S）是友善电子团队最新推出的一款实现满速率双千兆的、完全开源的开发板。通过刷机用作主路由或旁路由，可安装多种应用，以扩展使用功能。

<!--more-->

## 产品属性

- CPU: Rockchip RK3328, Quad-core Cortex-A53
- DDR4 RAM: 1GB
- Network：
  - 10/100/1000M以太网口 x 1
  - USB3.0转10/100/1000M以太网口 x 1
- USB2.0 Host: Type-A x1
- MicroSD Slot x 1
- MicroUSB: 供电和Slave功能
- Debug Serial Port: 3.3V TTL电平，3Pin 2.54mm间距排针
- PC Size: 55.6 x 52mm
- Power Supply: DC 5V/2A
- Temperature measuring range: 0℃ to 80℃
- OS/Software: U-boot，Ubuntu-Core，OpenWrt

官方参考文档：[NanoPi R2S](https://wiki.friendlyelec.com/wiki/index.php/NanoPi_R2S/zh#NanoPi_R2S.E8.B5.84.E6.BA.90.E7.89.B9.E6.80.A7)

## 刷机准备

- NanoPi R2S 开发板一快
- 64G TF 卡一张 以及 读卡器一个
- 下载固件
  - 官方固件： [百度网盘](https://download.friendlyelec.com/NanoPiR2S)，选择 rk3328-sd-friendlywrt-23.05-20240314.img.gz 并解压成 img 镜像文件。
  - 其它固件： [OpenWrt](https://openwrt.org/) 等
- 系统盘制作工具：[Rufus](https://rufus.ie)

## 刷机

- 将 TF 卡装入读卡器，插入装有 Windows 系统的电脑。
- 打开 Rufus 将固件写入到 TF 卡上。
- 取出 TF 卡，插入 NanoPi R2S，并接通电源。
- 用网线连接 NanoPi R2S 和电脑，访问 http://192.168.2.1 进行配置，也可以通过 ssh 访问并配置。



