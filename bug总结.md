<h1>悟空中文项目-疑难点汇总</h1>

<h2>li::marker</h2>

`li::marker`可以对li前的小圆点进行格式定义（前提是`list-style`不为`none`）。

<h2>伪元素层级</h2>

一般情况下，默认伪元素`::after`的层级在`::before`之上（后在前之上），并且伪元素的层级高于父元素。

<h2>nonscript标签</h2>

`noscript`标签是一个相当古老的标签，其被引入的最初目的是帮助老旧浏览器的平滑升级更替，因为早期的浏览器并不能支持JavaScript。`noscript`标签在不支持JavaScript的浏览器中显示替代的内容。这个元素可以包含任何HTML元素。这个标签的用法也非常简单：

```xml
<noscript>
  <p>本页面需要浏览器支持（启用）JavaScript</p>
</noscript>
```

<h2>mediaQuery控件的介绍</h2>

https://zhuanlan.zhihu.com/p/121091697