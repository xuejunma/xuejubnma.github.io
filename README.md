# 网页制作介绍

## 注册github账号
输入网址https://github.com/ 注册一个账号，假设用户名是stamax360. ***注意：*** 用户名是唯一并且不可以修改，并且主页网址 https://用户名.github.io/ 。 

## Fork 并且修改名字

- 输入网址 https://github.com/xuejunma/xuejunma.github.io/ 并且点击 **Fork**. 这样xuejunma.github.io仓库就复制到您的仓库。
***注意：*** 只有Fork到自己的仓库下才能修改内容

- 点击 **seeting**  将 xuejunma.github.io 修改自己用户名，如 stamax360.github.io. 



##  打开 includes/header.html 将 xuejunma全部修改为自己的用户名，如stamax360

 <code>   
<li class="nav-link"><a href="{{ site.baseurl }}/" class="logo"><strong>主页</strong></a>
<li class="nav-link"><a href="https://stamax360.github.io/aboutme"><strong>简历</strong></a>
<li class="nav-link"><a href="https://xuejunma.github.io/research"><strong>科研</strong></a>
<li class="nav-link"><a href="https://xuejunma.github.io/teaching"><strong>教学</strong></a>
<li class="nav-link"><a href="https://xuejunma.github.io/yanxitang"><strong>言蹊堂</strong></a>
<li class="nav-link"><a href="https://xuejunma.github.io/englishversion"><strong>ENGLISHVERSION</strong></a>
<code>

## 菜单栏
主页、简历等菜单栏可以在 includes/header.html 修改

## 社交账号
网页下面的社交平台  includes/footer.html修改

## 全局配置
可以在config.yml设置标题等。

## 页面内容
* index.html 修改主页
* aboutme.html 修改简历
* research.html 修改科研等



