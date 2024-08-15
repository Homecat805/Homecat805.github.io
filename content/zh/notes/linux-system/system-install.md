+++
title = 'Linux 系统安装'
date = 2024-08-15T10:26:09+08:00
draft = false
weight = 1
[params]
  author = 'Homecat'
+++

Linux 操作系统的内核是开源的，不同单位和厂家在内核的基础上开发和发行了多种发行版，如 Ubuntu、openEuler 等。 安装方式大同小异，具体参看各个系统的文档。

## Ubuntu 桌面

Ubuntu 桌面系统是非常优秀的开源软件，提供了基本应用程序，如办公套件，浏览器，电子邮件和多媒体应用程序等，以及数千个游戏和应用程序。使用 USB 启动方式安装 Ubuntu 的方式如下：

### 选择和下载镜像

- [官网](https://cn.ubuntu.com/download/desktop) 及官网提供的[其它镜像下载点](https://launchpad.net/ubuntu/+cdmirrors)
- 根据硬件选择和下载安装文件
  - 确定安装版本：20.04 LTS 64位
  - 确定安装文件格式：iso
  - 下载 ubuntu-20.04-desktop-amd64.iso 文件到本地。

### 制作安装盘

- 选择 Rufus 作为 USB 制作器。Rufus 只能在 Windows 上运行，并且要求 Win7 及后续版本(32或64位)，因此制作过程要在 Windows 环境中进行。
- 从 Rufus 官网下载 rufus.exe 文件。
- 打开 rufus，在程序界面上依次选择下载的 iso 文件、启动模式等参数后，按开始即可。启动模式的选择很重要，和被安装电脑的启动模式有关系，BIOS 或者 UEFI，必须正确选择。
    
### 安装
        
- 将USB安装盘插入待安装的电脑。
- 打开电脑，进入 setup，选择从 USB 启动，进入 Ubuntu 安装程序，按部就班，即可完成。