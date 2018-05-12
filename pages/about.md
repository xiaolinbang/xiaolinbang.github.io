---
layout: page
title: About
description: 小林帮
keywords: xiaolinbang, 小林帮
comments: true
menu: 关于
permalink: /about/
---

小林帮

Just Do It！

## 作者简介

  职业方向：linux软件开发工程师
  
  从业时间：2014~至今
  
  个人邮箱：xiaolinbang2017@126.com

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
