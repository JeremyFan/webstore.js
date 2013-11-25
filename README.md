webstore.js
===========

webstore.js提供兼容各浏览器的Web本地存储方法。

<p>原理：封装了localStorage和userData两种存储方式，提供了统一的接口。</p>

###兼容性###
容IE6+以及常见浏览器的最新版本（Chrome31/Firefox25/Safari5/Opera17）。
<p>对于支持localStorage的浏览器，优先使用localStorage存储。对于低版本的IE使用userData存储。</p>

###用法###
webstore.js目前提供两个方法，分别用于存/取数据
<p>存储数据：webstore.set(key, value);</p>
<p>读取数据：webstore.get(key);</p>
          

###展示###
<a href="http://jeremyfan.github.io/webstore.js">去看看</a>

