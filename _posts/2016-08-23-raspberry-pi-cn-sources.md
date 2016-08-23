---
layout: post
title:  关于树莓派国内源
category: linux
tags: [raspberry pi]
---
<p>第一个源(/etc/apt/sources.list) 的设置没什么问题了，最后用了aliyun的源。如下</p>
<p>deb http://mirrors.aliyun.com/raspbian/raspbian/ jessie main contrib non-free rpi</p>
<p>第二个源(/etc/apt/sources.list.d/raspi.list) 实在是找不到正确的位置,没办法还是用的官方的源，虽然非常非常慢，但可以正常使用。如下</p>
<p>deb http://archive.raspberrypi.org/debian/ jessie main ui</p>
<p># Uncomment line below then 'apt-get update' to enable 'apt-get source'</p>
<p>#deb-src http://archive.raspberrypi.org/debian/ jessie main ui</p>
<p>网上也没找到解决方法，可能还是路径不对，得再研究一下。先做个标记！</p>

{{ page.date | date_to_string }}
