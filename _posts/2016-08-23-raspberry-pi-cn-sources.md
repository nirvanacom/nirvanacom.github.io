---
layout: post
title:  关于树莓派国内源
category: linux
tags: [raspberry pi]
---
<p>第一个源(/etc/apt/sources.list) 的设置没什么问题了，最后用了aliyun的源。如下</p>
<p><code>deb http://mirrors.aliyun.com/raspbian/raspbian/ jessie main contrib non-free rpi</code></p>
<p>第二个源(/etc/apt/sources.list.d/raspi.list) 实在是找不到正确的位置,没办法还是用的官方的源，虽然非常非常慢，但可以正常使用。如下</p>
<p><code>deb http://archive.raspberrypi.org/debian/ jessie main ui</code></p>
<p><code># Uncomment line below then 'apt-get update' to enable 'apt-get source'</code></p>
<p><code>#deb-src http://archive.raspberrypi.org/debian/ jessie main ui</code></p>
<p>网上也没找到解决方法，可能还是路径不对，得再研究一下。先做个标记！</p>
- - -
<p>换了个源就可以了</p>
<p>第一个源(/etc/apt/sources.list)</p>
<p><code>deb http://mirrors.ustc.edu.cn/raspbian/raspbian/ jessie main contrib non-free rpi</code></p>
<p>第二个源(/etc/apt/sources.list.d/raspi.list)</p>
<p><code>deb http://mirrors.ustc.edu.cn/archive.raspberrypi.org/debian/ jessie main ui</code></p>
<p>这样就没问题了，害我折腾了这么久！</p>
- - -

<p>{{ page.date | date_to_string }}</p>
