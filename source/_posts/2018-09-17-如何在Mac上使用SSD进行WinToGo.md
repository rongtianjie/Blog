---
title: 如何在Mac上使用SSD进行WinToGo
date: 2018-09-17 19:19:06
tags: Mac
categories: Tutorial
---

##### **优点：**
- 不占用本地磁盘空间，很适合低配版Mac用户。
- 保持了本机系统的完整纯洁不被污染。
- SDD 配合 USB 3.0 数据线传输流畅。
<!--more-->

##### **缺点：**
- 占用一个宝贵的 USB 接口。
- WTG 系统下是无法访问本机硬盘的，但是在 OS X 系统下可以读取 WTG 硬盘的内容，但不能写入。<br><small>安装软件例如 Mounty 之类的可以写入。</small>
- 不能设置每次开机自动从 WTG 系统启动，所以系统不能重启，不能休眠。

### 准备
- 一台 Mac
- 一个运行 Win10 企业版的 PC（Win8/8.1企业版亦可，运行在 PD 虚拟机里也行）
- 一个 SSD 及配套数据线
- 一个容量大于 2.8G 的U盘

### 开始
1. 在 OS X 系统里把驱动程序安装包下载复制到 U盘里。（方法：打开 Boot Camp 助理，点击菜单栏上的“操作”，再点击“下载 Windows 支持软件”，然后选择下载位置即可）
![下载驱动安装包](images/1.jpg)
2. 在 Windows 系统里下载并双击打开你要安装的 Windows 安装镜像。（可以在[MSDN](https://msdn.itellyou.cn/), 我告诉你里下载）
3. 在 Windows 系统里打开 Windows to go。
![打开 Windows to go](images/2.jpg)
4. 选择驱动器和要安装的镜像文件。
![选择文件](images/3.jpg)
5. 选择是否需要登录密码。
6. 确定后漫长的等待。
![安装系统](images/4.jpg)
7. 将 SSD 插入 Mac，开机并同时按住 Option/Alt 键，选择 EFI Boot。
8. 插入 U盘，打开 WindowsSupport\BootCamp\Setup.exe
9. 安装完驱动后大功告成。

