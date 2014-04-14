---
layout: page
title: 欢迎访问
tagline: 
---
{% include JB/setup %}

![logo](assets/logo48.jpg)
欢迎访问我的blog。
## 最近的文章
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
## 最近在读的书
<script type="text/javascript" src="http://www.douban.com/service/badge/1348213/?selection=latest&amp;picsize=small&amp;hideself=on&amp;show=dolist&amp;n=6&amp;hidelogo=on&amp;cat=book&amp;columns=6">
</script>
## 在这里找到我
[豆瓣](http://book.douban.com/people/1348213/) 

 