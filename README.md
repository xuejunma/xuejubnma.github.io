# Github搭建个人主页介绍

## 注册github账号
在https://github.com/ 注册一个账号，假设用户名是stamax360. ***注意：*** 用户名是唯一并且不可以修改，个人主页网址是https://用户名.github.io/ 。 

## Fork 并且修改名字

- 输入网址 https://github.com/xuejunma/xuejunma.github.io/ 并且点击 **Fork**. xuejunma.github.io仓库便拷贝到您的仓库中。
***注意：*** 只有Fork到自己的仓库下才能修改内容。 Fork需要一些时间。另外，修改内容不会立刻出现在个人主页上，时间由网速决定。

- 点击 **setting**  将 ***xuejunma***.github.io 修改为自己用户名，如 ***stamax360***.github.io. 



##  修改菜单栏 主页、简历、科研的链接

* 打开 includes/header.html并且点击 🖊   进入编辑，将全部***xuejunma***修改为自己的用户名，如 ***stamax360***，***注意*** 修改一定要点击🖊   进入编辑中，否则无法修改。
* 保存。 网页拉到最后，点击***Commit changes***保存。 ***注意***  若不保存，意味着没有修改。

```php 
<li class="nav-link"><a href="{{ site.baseurl }}/" class="logo"><strong>主页</strong></a>
<li class="nav-link"><a href="https://stamax360.github.io/aboutme"><strong>简历</strong></a>
<li class="nav-link"><a href="https://xuejunma.github.io/research"><strong>科研</strong></a>
<li class="nav-link"><a href="https://xuejunma.github.io/teaching"><strong>教学</strong></a>
<li class="nav-link"><a href="https://xuejunma.github.io/yanxitang"><strong>言蹊堂</strong></a>
<li class="nav-link"><a href="https://xuejunma.github.io/englishversion"><strong>ENGLISHVERSION</strong></a>
```

## 修改全局配置
打开config.yml，将 ***马学俊，邮箱*** 等信息修改为自己的信息。如将 ***马学俊*** 修改自己的名字，如一诺9257.

```php
# Site settings
# 站点名字，也就是html的title 会显示在浏览器标签上。
title: 一诺9257
#name: 马学俊
# 站点副标题，会显示在首页上，可以不填。
subtitle: 
email: yinuoyumi@163.com
```

## 修改页面内容
* index.html 修改 ***主页***
* aboutme.html 修改 ***简历***
* research.html 修改 ***科研***
* teaching.html 修改 ***教学***
* yanxitang.html 修改 ***言蹊堂***

### 以index.html为例说明。

* 将所有***马学俊***的信息全部修改为自己的信息。
* 图片修改，在仓库界面点击***profilepicturenew.jpg***直接删掉；再点击***Uploads files*** 上传一个命名为***profilepicturenew.jpg***图片。 ***注意*** 图片的名字一定是profilepicturenew.jpg，如果不是，将下面命令的图片名字修改为自己的图片名字。

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
网页下面的社交平台在includes/footer.html修改

* 修改***yinuoyumi@163.com***  
* 将全部***xuejunma***修改为自己用户名，如stamax360
* 将***苏州大学数学科学学院***修改为自己的单位，如东吴大学数学科学学院。
* 如果添加新的社交账号，任意复制一个，修改网址和名称即可。
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

##  增减菜单栏 主页、简历、科研等界面

### 删去， 直接删去即可
### 新建 *** 休闲*** 界面 
* 打开 includes/header.html，点击编辑，输入下面内容保存； 

```php 
<li class="nav-link"><a href="https://用户名.github.io/xiuxian.html"><strong>休闲</strong></a>

```

* 回到仓库主页面，点击***Create new file***，并且命名为xiuxian.html;
* 点击xiuxian.html，进入编辑页面，输入下面内容保存即可。

```php
---
layout: page
title:  " "
permalink: /xiuxian/
---
```

## html 命令
 大家可以直接在搜索引擎中收索***html常见命令***，会出现很多资料。
 
## 感谢
特别感谢[Pesoto](https://pesoto.github.io/)创建了模板。

目前网页基本完成。如果有任何问题麻烦邮箱联系我，谢谢！


