---
layout: post
title:  How to insert pictures
category: test
tags: [test]
---
<body>
<p>关于怎样插入图片，在这里先做个标记，因为我还没找到方法，但是jekyll上有个说明：</p>
<p>Including an image asset in a post:</p>
<p><q>... which is shown in the screenshot below:</q></p>
<p><q>![My helpful screenshot]({{ site.url }}/assets/15.2.jpg)</q></p>
<p>一会就按这个说明先试一下！</p>
<hr/>
<p>![15.2](https://raw.githubusercontent.com/nirvanacom/nirvanacom.github.io/master/assets/15.2.png)</p>
<p><img src='https://raw.githubusercontent.com/nirvanacom/nirvanacom.github.io/master/assets/15.2.png' /></p>
<hr/>
<p>终于成功了！jekyll上面说的完全不行，我是在assets目录里放进一张图片，然后在github里把图片打开，查看它的图片地址，复制图片地址，粘贴到图片引用代码中就行了！</p>
<p><code><img src='https://raw.githubusercontent.com/nirvanacom/nirvanacom.github.io/master/assets/15.2.png' /></code></p>
<p>对，就是这么简单，搞了一天多才弄明白！</p>

{{ page.date | date_to_string }}

<!-- 多说评论框 start -->
	<div class="ds-thread" data-thread-key="2016-07-03-how-to-insert-pictures.md" data-title="How to insert pictures" data-url="https://nirvanacom.github.io/test/2016-07/how-to-insert-pictures.html"></div>
<!-- 多说评论框 end -->
<!-- 多说公共JS代码 start (一个网页只需插入一次) -->
<script type="text/javascript">
var duoshuoQuery = {short_name:"nirvanacom"};
	(function() {
		var ds = document.createElement('script');
		ds.type = 'text/javascript';ds.async = true;
		ds.src = (document.location.protocol == 'https:' ? 'https:' : 'http:') + '//static.duoshuo.com/embed.js';
		ds.charset = 'UTF-8';
		(document.getElementsByTagName('head')[0] 
		 || document.getElementsByTagName('body')[0]).appendChild(ds);
	})();
	</script>
<!-- 多说公共JS代码 end -->

</body>
