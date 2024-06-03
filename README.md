## EPIPHANY
EPIPHANY：顿悟，灵光一闪。

## 网站示例
[web.awww.asia](https://web.awww.asia/)

这是我的个人网站，我的生活倒影，有诗意地记录自己的生活。

![首页](https://file.awww.asia/static/assets/1NBBG9%40CY%5DP%258Z2HE%24C1%4049.png)

## 技术栈
前端技术：Vue2（博客系统），Vue3（IM 聊天室系统），Element UI（Vue2），Element-Plus UI（Vue3），Naive UI（Vue3）

后端技术：Java，SpringBoot，MySQL，Mybatis-Plus，t-io，qiniu-java-sdk，spring-boot-starter-mail

## 网站简介
这是一个 SpringBoot + Vue2 + Vue3 的产物，支持移动端自适应，配有完备的前台和后台管理功能。

网站分两个模块：
- 博客系统：具有文章，表白墙，图片墙，收藏夹，乐曲，视频播放，留言，友链，时间线，后台管理等功能。
- 聊天室系统：具有朋友圈（时间线），好友，群等功能。

本网站采用前后端分离进行实现，两个前端项目通过Nginx代理，后端使用Java。

部署网站需要安装Nginx、Java、MySQL，然后打包前后端项目并部署。

文件服务可以使用七牛云，也可以使用服务器。默认使用服务器。

Vue3（IM 聊天室系统）是非必须的。如果部署，则需要依赖博客，然后从博客的“联系我”进入，因为登录模块在博客。

## 网站示例（详细示例请见官方网站：[web.awww.asia](https://web.awww.asia/)）

### 博客

#### 文章速览、文章分类
![首页文章速览](https://file.awww.asia/static/assets/1NBBG9%40CY%5DP%258Z2HE%24C1%4049.png)

![分类页面](https://file.awww.asia/static/assets/M%24T%29D6%5BL%28XPQC3%7DH6T4B0Z7.png)

#### 文章详情页：文章、视频功能与留言
![文章详情页](https://file.awww.asia/static/assets/Z4%254DSCS7WE%25J9T5K_~E%29YO.png)

![文章视频功能](https://file.awww.asia/static/assets/OF%297Q%5BY%28%24KKAQCY%25DQMO%40C5.png)

![文章留言区域](https://file.awww.asia/static/assets/5%24A4KSMAF%28G11%7B~EWU%288CI3.png)

#### 恋爱笔记与旅拍
![恋爱笔记页面](https://file.awww.asia/static/assets/%5BL%60SI4C13TV_1%7BKOHN%244%40YG.png)
### 后台管理系统

#### 访问统计、基础设置与文件管理
![后台管理访问统计](https://file.awww.asia/static/assets/%E5%90%8E%E5%8F%B0%E7%AE%A1%E7%90%86%E8%AE%BF%E9%97%AE%E7%BB%9F%E8%AE%A1.png)

![后台管理网站基础设置](https://file.awww.asia/static/assets/%E5%90%8E%E5%8F%B0%E7%AE%A1%E7%90%86%E7%BD%91%E7%AB%99%E5%9F%BA%E7%A1%80%E8%AE%BE%E7%BD%AE.png)

![后台管理文件资源管理](https://file.awww.asia/static/assets/%E5%90%8E%E5%8F%B0%E7%AE%A1%E7%90%86%E6%96%87%E4%BB%B6%E8%B5%84%E6%BA%90%E7%AE%A1%E7%90%86.png)

#### 文章管理与新增文章
![后台管理文章管理](https://file.awww.asia/static/assets/%E5%90%8E%E5%8F%B0%E7%AE%A1%E7%90%86%E6%96%87%E7%AB%A0%E7%AE%A1%E7%90%86.png)

![后台管理新增文章](https://file.awww.asia/static/assets/%E5%90%8E%E5%8F%B0%E7%AE%A1%E7%90%86%E6%96%B0%E5%A2%9E%E6%96%87%E7%AB%A0.png)

