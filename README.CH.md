![Atom](https://cloud.githubusercontent.com/assets/72919/2874231/3af1db48-d3dd-11e3-98dc-6066f8bc766f.png)

[![macOS Build Status](https://circleci.com/gh/atom/atom/tree/master.svg?style=shield)](https://circleci.com/gh/atom/atom) [![Linux Build Status](https://travis-ci.org/atom/atom.svg?branch=master)](https://travis-ci.org/atom/atom) [![Windows Build Status](https://ci.appveyor.com/api/projects/status/1tkktwh654w07eim?svg=true)](https://ci.appveyor.com/project/Atom/atom)
[![Dependency Status](https://david-dm.org/atom/atom.svg)](https://david-dm.org/atom/atom)
[![Join the Atom Community on Slack](https://atom-slack.herokuapp.com/badge.svg)](https://atom-slack.herokuapp.com)

Atom-21世纪的款编辑神器,使用[Electron](https://github.com/atom/electron)编写，也以我们喜爱的

请浏览[atom.io](https://atom.io)或者[Atom forum](https://discuss.atom.io)以获取更多详情。

在Twitter上關注[@AtomEditor](https://twitter.com/atomeditor)以獲取重要公告。

该项目采取[贡献者公约](CODE_OF_CONDUCT.md)行为为准则。在参与此项目时，你必须遵守此公约。
如有所发现，请向atom@github.com汇报。

## 文档

如果您想阅读有关在Atom中使用Atom或开发软件包的信息，可以免费在线获取[Atom Flight Manual](https://flight-manual.atom.io)。
您也可以在[atom / flight-manual.atom.io](https://github.com/atom/flight-manual.atom.io)中找到手册的来源。

用于开发包的[API参考](https://atom.io/docs/api)也记录在Atom.io上。

## 安装

### 需要
- [Git](https://git-scm.com)

### macOS

下载最新的[Atom发布]（https://github.com/atom/atom/releases/latest）。

Atom将自动更新当新版本。

### Windows

下载最新的[Atom安装程序]（https://github.com/atom/atom/releases/latest）。 `AtomSetup.exe`是32位。对于64位系统，请下载`AtomSetup-x64.exe`。

Atom将自动更新当新版本。

你也可以从[发布页面]下载`atom-windows.zip`（32位）或`atom-x64-windows.zip`（64位）(https://github.com/atom/atom/releases/latest)。
`.zip`版本不会自动更新。


使用[Chocolatey](https://chocolatey.org)?运行`cinst Atom`以安装最新版本的Atom。

### Linux

Atom仅适用于64位Linux系统。

按照飞行手册中的[Linux安装说明](https://flight-manual.atom.io/getting-started/sections/installing-atom/#platform-linux)
配置您的发行版的软件包管理器以安装和更新Atom 。您还可以找到有关如何在不使用软件包存储库的情况下安装Atom官方Linux软件包的说明，
但在以这种方式下安装Atom，Atom将无法获得自动更新。

### Archive extraction

存档可供不想以root身份安装`atom`的人使用。

此版本允许您并行安装多个Atom版本。它基于Ubuntu 64位构建，但应与其他Linux发行版兼容。

1.安装依赖(在Ubuntu)：`sudo apt install git gconf2 gconf-service libgtk2.0-0 libudev1 
libgcrypt20 libnotify4 libxtst6 libnss3 python gvfs-bin xdg-utils libcap2`
2.从[Atom发布页面](https://github.com/atom/atom/releases/latest)下载`atom-amd64.tar.gz`。
3.在要提取Atom文件夹的目录中运行`tar xf atom-amd64.tar.gz`。
4.使用新提取的目录中运行`atom`命令来启动Atom。

Linux版本目前不会自动更新，因此您需要
重复这些步骤以升级到将来的版本。

## 创建

* [Linux](https://flight-manual.atom.io/hacking-atom/sections/hacking-on-atom-core/#platform-linux)
* [macOS](https://flight-manual.atom.io/hacking-atom/sections/hacking-on-atom-core/#platform-mac)
* [Windows](https://flight-manual.atom.io/hacking-atom/sections/hacking-on-atom-core/#platform-windows)

## 讨论区
*在我们的[论坛](https://discuss.atom.io/)上讨论Atom。

*在Slack团队中讨论Atom  -  [加入说明](https://discuss.atom.io/t/join-us-on-slack/16638?source_topic_id=25406)

## License

[MIT](https://github.com/atom/atom/blob/master/LICENSE.md)

当使用Atom或其他GitHub徽标时，请务必遵循[GitHub徽标指南](https://github.com/logos)。
