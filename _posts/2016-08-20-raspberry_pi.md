---
layout: post
title:  Raspberry Pi 3
category: linux
tags: [raspberry pi]
---
<p>chromium装上了，装的chromium-browser_48。需要下载的一共三个文件，分别是：</p>
<p><code>chromium-browser_48.0.2564.82-0ubuntu0.15.04.1.1193_armhf.deb</code></p>
<p><code>chromium-browser-l10n_48.0.2564.82-0ubuntu0.15.04.1.1193_all.deb</code></p>
<p><code>chromium-codecs-ffmpeg-extra_48.0.2564.82-0ubuntu0.15.04.1.1193_armhf.deb</code></p>
<p>安装的时候好像要先安装第三个，然后再装第一，二个，不然会提示找不到包。不过资源消耗还是很大，登录百度账号什么的，可以达到90％多。装完后还要装flash，不然不能播放视频。这个网上有，这里标记下文件名：</p>
<p><code>chromium-pepper-flash-12-12.0.0.77-1-armv7h.pkg.tar.xz</code></p>
<p>接下来是gnucash。这个开始的时候是装不上的，后来不知道怎么回事，install一下就可以了，依赖也都正常。不多说。</p>
<p>另外，源的问题还没解决，还是用的官方源，后面更新慢如牛。因为找了几个国内源，update都不成功，如下提示：</p>
<p><code>W: Failed to fetch http://mirrors.ustc.edu.cn/raspbian/raspbian/dists/jessie/InRelease  Unable to find expected entry 'conrtib/binary-armhf/Packages' in Release file (Wrong sources.list entry or malformed file)</code></p>
<p><code>E: Some index files failed to download. They have been ignored, or old ones used instead.</code></p>
<p>看电影现在用omxplayer，命令行直接执行就可以：omxplayer -o local /filesname</p>
<p>其它暂时没什么，就是下载，看电影，记帐，github，学习，够用了。开发什么的，我还是超白，以后再说。</p>



<p>{{ page.date | date_to_string }}</p>
