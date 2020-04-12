---
title: 安装Eclipse(STS)
date: 2019-08-22 21:08:55
categories:
tags:
  - 开发技术
---

每次重新安装 Eclipse（STS）都是非常痛苦，每次都有一些必须的安装内容，记录一下，备忘。

本次安装，基于 STS4.4.2 版，2019 年 8 月底。
JDK 已经安装好的情况下。

1. 到官方网站下载 zip 版本的 STS 文件，官方地址：
   STS：<https://spring.io/tools>
   Eclipse：<https://www.eclipse.org/downloads/>
2. 解压，先不着急启动
3. 安装 lombok 插件，直接双击 lombok.jar，选择已经解压的目录即可
4. 打开解压目录下的 SpringToolSuite4.ini 文件，去掉 lombok 的绝对路径，改为相对路径
   {% asset_img utf8.png %}
5. 修改默认为 utf-8 编码，在 SpringToolSuite4.ini 文件的最下面加入一行代码:-Dfile.encoding=UTF-8，如上图
6. 安装 google style 插件，从<https://github.com/google/google-java-format#eclipse>下载 google-java-format-eclipse-plugin_1.6.0.jar，放到"dropins"目录
7. 启动 Eclipse（STS）
8. 进入“Window > Preferences > Java > Code Style > Formatter > Formatter Implementation”，选择 google formatter，见下图
   {% asset_img formatter.png %}
9. 依次安装常用的插件：
   1. 反编译，Enhanced Class Decompiler
   2. 代码静态扫描，sonarlint
   3. 阿里规约扫描 <https://p3c.alibaba.com/plugin/eclipse/update>
   4. 可选，如果需要安装 Flowable，安装 flowable designer：<http://flowable.org/designer/update>
10. 为解决中英文字体大小不一致，依次“Window > Preferences > General > Appearance > Corlor and Fonts > Text Font”，调整字体大小为五号或者小五
    {% asset_img font.png %}
