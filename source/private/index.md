---
title: 日志随记
date: 2017-06-28 13:35:02
---
## 2017-06-28

### 可见性API属性和事件：
> * document.hidden: Boolean值，表示当前页面可见还是不可见
> * document.visibilityState: 返回当前页面的可见状态。
    * hidden
    * visible
    * “prerender” 这个表示纳尼呢~~恩，我也不确定，字面意思是“预渲染”。莫非指的是啪啪啪一下子开了很多个选项卡，之前选项卡依然在加载渲染的状态？或者说是浏览器新打开时记住的上一次关闭选项卡的状态？求达人指明！
    * “preview” 预览。根据部分2011年底相关国外部分文章的说法，这种状态出现在，如window7系统下，鼠标放在底部（一般是）任务栏的图标上（预览）的时候。

实际应用价值很大，故做记录以便使用时候做参考。详见[张鑫旭大神空间](http://www.zhangxinxu.com/wordpress/2012/11/page-visibility-api-introduction-extend/)