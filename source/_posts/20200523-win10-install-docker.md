---
title: win10 install docker
date: 2020-05-23 21:05:18
categories:
tags:
---

Win10提供了对docker的支持，记录下Win10下如何安装docker环境。

1. 首先启用hyper-v，在“启用或关闭 Windows 功能”里，选择hyper-v功能，如下：

    {% asset_img install-hyper-v.png %}

    注：如果安装了vmware等功能，安装hyper-v会导致VMware无法使用，请做好评估后使用

2. 到 [docker 官网](https://hub.docker.com/editions/community/docker-ce-desktop-windows)下载docker安装文件，文件比较大，用迅雷等工具下载比较快，现在后根据提示安装即可。

3. 安装后需要重新启动Windows，Docker随开机启动，第一次运行时docker启动时间略长，根据需要，可能需要多次重启电脑。

4. 启动后，耐心等待docker启动成功，在系统的右下角，会出现一条小鲸鱼，如下图。

    {% asset_img docker-running.png %}

5. 进入命令行，执行`docker --version`命令，正确执行说明安装成功。

6. 运行`docker run hello-world`命令，出现如下图所示

     {% asset_img docker-hello-world.png %}
     