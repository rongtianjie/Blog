---
title: 在Mac上通过“启动转换”安装Windows
date: 2018-09-15 16:34:02
tags: 
	- Mac
	- 双系统
categories: Tutorial
---

“启动转换”可帮助您在 Mac 上安装 Microsoft Windows。安装后，请重新启动 Mac，以在 macOS 和 Windows 之间切换。
<!--more-->
![启动转换助理](images/1.jpg)

开始之前，确保您已备齐所有必需物品：
* 基于 Intel 的 Mac。
* 包含 64 位 Microsoft Windows 8 或更高版本（Home 或 Pro 版本）的 Microsoft Windows 安装介质或磁盘映像 (ISO)。
* 启动驱动器上至少有 55 GB 的可用磁盘空间。
* 16 GB 或更大容量的空白 USB 2 闪存驱动器。（较新型号的Mac并不需要闪存驱动器，详见文末“进一步了解”）

## 1.检查系统要求
某些版本的 Windows 要求具有特定处理器，并且需要比其他版本更多的硬盘驱动器空间和内存 (RAM)。检查您的 Windows 副本随附的文稿，以了解您需要什么。然后使用“[系统信息](https://support.apple.com/zh-cn/HT203001)”来了解您 Mac 的当前配置。
## 2.获取 Windows 磁盘映像
当您购买 Windows 时，它会以可下载的磁盘映像文件 (ISO) 或者安装光盘或 USB 闪存驱动器的形式提供。如果您的 Windows 副本以 DVD 形式提供，您可能需要为它[创建磁盘映像](https://support.apple.com/zh-cn/HT203909)才能与“启动转换”搭配使用。如果您的 Windows 版本以 USB 闪存驱动器形式提供，您可以从 [Microsoft](http://www.microsoft.com/zh-cn/software-download/windows10ISO) 或 [MSDN](https://msdn.itellyou.cn/) 下载 ISO。
## 3.打开“启动转换助理”
“启动转换助理”会引导您完成在 Mac 上安装 Windows 的整个过程。请从“应用程序”文件夹内的“实用工具”文件夹中打开这个应用。然后，按照屏幕上的说明操作，以对启动磁盘进行重新分区并下载 Windows 的相关软件驱动程序。如果您在安装期间收到提示，请连接一个空白的 USB 2 闪存驱动器。
## 4.对 Windows 分区进行格式化
完成该助理的操作后，Mac 会重新启动至 Windows 安装程序。如果系统询问您希望将 Windows 安装在什么位置，请选择 BOOTCAMP 分区，然后点按“格式化”。
<small>只有使用闪存驱动器或光盘驱动器安装 Windows 时，才需要进行这一步。在所有其他情况下，系统会选择正确的分区，并会自动为您进行格式化。</small>
## 5.安装 Windows 和 Windows 支持软件
请拔下在安装期间不需要使用的所有外部设备，如显示器和磁盘。然后按照屏幕上的提示来安装 Windows。安装完成后，您的 Mac 会在 Windows 中启动，并启动 Windows 支持软件安装器。如果屏幕没有自动显示“欢迎使用‘启动转换’安装器”，您可以[手动安装 Windows 支持软件](https://support.apple.com/zh-cn/HT208495)。
## 6.在 macOS 和 Windows 之间切换
安装 Windows 和 Windows 支持软件后，您可以使用 Windows 中的“启动转换”系统托盘项切换回 macOS。选择 macOS 宗卷，然后重新启动 Mac。要从 macOS 切换到 Windows，请[使用“启动磁盘”偏好设置面板](https://support.apple.com/zh-cn/HT202796)来选择“启动转换”宗卷，然后重新启动 Mac。您也可以在 Mac 重新启动后按住 Option 键，在 macOS 和 Windows 之间选择。

### 进一步了解
安装 OS X El Capitan 10.11 或更高版本后，以下机型使用内置驱动器来临时储存安装 Windows 所需的内容，因此您不需要使用 USB 闪存驱动器：
* MacBook Pro（2015 年及更新机型）
* MacBook Air（2015 年及更新机型）
* MacBook（2015 年及更新机型）
* iMac（2015 年及更新机型）
* iMac Pro
* Mac Pro（2013 年末）
有关在 Mac 上使用 Windows 的更多信息，请点按“启动转换助理”中的“打开‘启动转换’帮助”按钮。以下资源也包含有用信息：
* [从 Windows 安装介质为“启动转换”创建 ISO 映像](https://support.apple.com/zh-cn/HT203909)
* [通过“启动转换”在 Windows 中使用 Apple 键盘](https://support.apple.com/zh-cn/HT202676)

<small>此教程摘自Apple官网文章[HT201468](https://support.apple.com/zh-cn/HT201468)，更新于2018年6月26日</small>
