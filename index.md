---
layout: page
title: 第一个清晨
tagline: by:小脑灰
---
{% include JB/setup %}

    
## Article


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## About me
  <p>技术爱好者.正在努力前进中</p>
  <p><span>足迹:</span><a href="http://weibo.com/xiaohui0717">weibo</a></p>
  <p><span>Q Q:</span>87999405</p>
  <p><span>E-mail:</span>answerbob#gmail.com</p>


