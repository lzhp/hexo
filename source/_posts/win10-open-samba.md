---
title: win10 open samba
date: 2019-10-09 21:22:00
categories:
tags:
---

买了一个玩客云，需要使用 samba 协议访问，win10 默认不开放访问 samba，需要进行如下设置。

## 打开 win10 的 samba 协议

依次进入控制面板-程序-程序和功能，选择 samba 相关的两个协议，如下图所示。

{% asset_img win10samba.png %}

## 允许匿名访问策略

进入命令行，输入`gpedit.msc`，进入组策略编辑器。

如下图，选择：管理模板-网络-lan man 工作站，将“启用不安全来宾登录”设置为已启用。

{% asset_img smbpolicy.png %}

现在应该可以访问 samba 的文件了。
