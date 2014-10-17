---
layout: page
title: PT 风向标
tagline: 关注国内外PT站重要消息，提供各大PT站简介。
---
{% include JB/setup %}

# PT 风向标
> 微信号： private_tracker

## 主要功能：
- 分享国内外pt站开放注册、开放邀请、全站免费等重要信息；（这些信息会经过严格筛选，那些常年开放的日经站就不会拿来说了，而会选取最符合天朝人民切身利益的消息进行推送）
- 输入关键字，返回pt站介绍，比如输入CHD，然后就把彩虹岛的基本信息返回过来；当然关键字不仅限于PT站，也会加上一些重大事件、专业名词解释、pt届传奇用户等等……
- 于是问题就来了……


## 最近文章

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## 联系方式
admin@privatetracker.in  
微信公众号：  
![二维码](http://pic-share.qiniudn.com/pt.jpg)
