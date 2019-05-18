# 网页制作介绍

## 注册github账号
输入网址https://github.com/ 注册一个账号，假设用户名是stamax360. ***注意：*** 用户名是唯一并且不可以修改，并且主页网址 https://用户名.github.io/ 。 

## Fork 并且修改名字

- 输入网址 https://github.com/xuejunma/xuejunma.github.io/ 并且点击 **Fork**. 这样xuejunma.github.io仓库就复制到您的仓库。
***注意：*** 只有Fork到自己的仓库下才能修改内容

- 点击 **seeting**  将 xuejunma.github.io 修改自己用户名，如 stamax360.github.io. 



##  修改菜单栏 主页、简历、科研的链接
打开 includes/header.html并且点击 🖊   进入编辑，***将 ***xuejunma***全部修改为自己的用户名，如***stamax360***
* 新建 *** 休闲*** 菜单，那么复制***教学***，然后粘贴，修改相应内容

```php 
<li class="nav-link"><a href="{{ site.baseurl }}/" class="logo"><strong>主页</strong></a>
<li class="nav-link"><a href="https://stamax360.github.io/aboutme"><strong>简历</strong></a>
<li class="nav-link"><a href="https://xuejunma.github.io/research"><strong>科研</strong></a>
<li class="nav-link"><a href="https://xuejunma.github.io/teaching"><strong>教学</strong></a>
<li class="nav-link"><a href="https://xuejunma.github.io/yanxitang"><strong>言蹊堂</strong></a>
<li class="nav-link"><a href="https://xuejunma.github.io/englishversion"><strong>ENGLISHVERSION</strong></a>
```

## 修改全局配置
打开config.yml，将马学俊，邮箱等信息修改为自己的信息。如将***马学俊***修改自己的名字，如一诺9257.

```php
# Site settings
# 站点名字，也就是html的title 会显示在浏览器标签上。
title: 马学俊
#name: 马学俊
# 站点副标题，会显示在首页上，可以不填。
subtitle: 
email: yinuoyumi@163.com
```

## 页面内容
* index.html 修改***主页***
* aboutme.html 修改***简历***
* research.html 修改***科研***
* teaching.html 修改***教学***
* yanxitang.html 修改***言蹊堂***

### 以index.html为例说明。

* 将所有***马学俊***的信息全部修改为自己的信息。如果不知道 其中的命令含义，而可以html常见命令，会有很详细的介绍。
* 图片修改，可以直接在仓库点击***profilepicturenew.jpg***，然后直接删掉；在点击***Uploads files*** 上传一个命名为***profilepicturenew.jpg***图片。

```php   
---
layout: page
title: <font face="Kaiti"> 马学俊 </font>
---

<img src="profilepicturenew.jpg" alt="stmax pic" style="width:200px;height:220px;" title="stamax "; algin="middle">
<br>
副教授
<br>
统计系
<br>
数学科学学院 
<br>
苏州大学
<br>
邮箱: yinuoyumi@163.com

```


## 修改社交账号
网页下面的社交平台  includes/footer.html修改

* 修改***yinuoyumi@163.com***  
* 将全部***xuejunma***修改为自己用户名，如stamax360
* 将***苏州大学数学科学学院***修改自己的单位，如东吴大学数学科学学院。
* 如果添加新的社交账号，复制三个中的一个，修改网址和名称即可。
```php

<div class="site-navigation">
      <p><a href="mailto:yinuoyumi@163.com"><i class="fa fa-envelope"></i> E-mail</a></p>
</div>

<div class="site-contact">
      <p><a href="https://github.com/xuejunma/xuejunma.github.io/"><i class="fa fa-github"></i> GitHub</a></p>
</div>

<div class="site-signature">
      <p><a href="http://math.suda.edu.cn/"><i class="fa fa-linkedin-square"></i> 苏州大学数学科学学院</a></p>
</div>
```

##  删减菜单栏 主页、简历、科研等界面

### 新建 *** 休闲*** 界面 
* 打开 includes/header.html，点击编辑，输入下面内容保存； 

```php 
<li class="nav-link"><a href="https://xuejunma.github.io/xiuxian.html"><strong>休闲</strong></a>

```

* 回到仓库主页面，点击***Create new file***，并且命令为xiuxian.html;
* 点击xiuxian.html，进入编辑页面，输入下面内容。

```php
---
layout: page
title:  " "
permalink: /xiuxian/
---
```




