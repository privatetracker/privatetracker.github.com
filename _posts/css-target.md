---
layout: post
category : test
tagline: "this is tagline"
tags: [this, is, tag]
---

{% I don't know what is this %}


## 定义
[w3c](http://www.w3.org/wiki/CSS/Selectors/pseudo-classes/:target) 对于`:target`的定义是：
> The :target pseudo-class represents an element that is the target element of the referring URI.

语法：
> :target{ properties }

<!-- more -->

下面给出两个 target 伪类的简单应用。

## 给标题添加 target 伪类
在网页内创建[页内链接](http://www.w3.org/TR/html401/struct/links.html#h-12.1)时（比如创建目录），点击目录后页面会跳转至对应的条目；而如果再次滚动页面，对应条目可能与其他条目混淆。这种情况下，给点击的条目添加特殊的样式会使其更加醒目。
<iframe width="100%" height="400" src="http://jsfiddle.net/iwilliam/b9A5X/embedded/result,html,css" allowfullscreen="allowfullscreen" frameborder="0"></iframe>
点击目录，会跳转至对应章节，同时章节背景会变成黄色，且在左边出现一个右箭头，指示这就是点击目录所对应的章节。

## 纯 CSS 打造 Tab 效果
<iframe width="100%" height="500" src="http://jsfiddle.net/iwilliam/HBUnJ/embedded/result,html,css" allowfullscreen="allowfullscreen" frameborder="0"></iframe>
**在 HTML 中如果有几个元素空间位置相同，且`z-index`一样，则最后声明的元素覆盖在上。所以，将默认第一个 tab 放在最后声明。此外还要注意将各 tab 背景色设为不透明颜色，否则会出现重叠。最后，应将各 tab 的`z-index`值设为正整数。**