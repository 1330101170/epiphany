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
![首页文章速览](poetize_picture/首页文章速览.png)

![分类页面](poetize_picture/分类页面.png)

#### 文章详情页：文章、视频功能与留言
![文章详情页](poetize_picture/文章详情页.png)

![文章视频功能](poetize_picture/文章视频功能.png)

![文章留言区域](poetize_picture/文章留言区域.png)

#### 恋爱笔记与旅拍
![恋爱笔记页面](poetize_picture/恋爱笔记页面.png)

![旅拍页面](poetize_picture/旅拍页面.png)

#### 百宝箱、弹幕墙与友人帐
![百宝箱](poetize_picture/百宝箱.png)

![弹幕墙](poetize_picture/弹幕墙.png)

![友人帐](poetize_picture/友人帐.png)

#### 聊天室与朋友圈
![聊天室](poetize_picture/聊天室.png)

![朋友圈](poetize_picture/朋友圈.png)

### 后台管理系统

#### 访问统计、基础设置与文件管理
![后台管理访问统计](poetize_picture/后台管理访问统计.png)

![后台管理网站基础设置](poetize_picture/后台管理网站基础设置.png)

![后台管理文件资源管理](poetize_picture/后台管理文件资源管理.png)

#### 文章管理与新增文章
![后台管理文章管理](poetize_picture/后台管理文章管理.png)

![后台管理新增文章](poetize_picture/后台管理新增文章.png)

## 使用功能
网站介绍与更新记录：[https://poetize.cn/article/20](https://poetize.cn/article/20)。

### 功能介绍
本网站以诗词为基底，通过随机诗句API，每次进入都会有一句诗映入眼帘。

详情请见：[POETIZE - 功能介绍](https://poetize.cn/article/89)。

### 文章系统
文章在后台使用MarkDown编写，通过解析生成不同的标签，达到自定义美化效果。

详情请见：[POETIZE - 文章系统](https://poetize.cn/article/88)。

### 用户系统
详情请见：[POETIZE - 用户系统](https://poetize.cn/article/87)。

### 随笔
详情请见：[POETIZE - 随笔（朋友圈、点点滴滴、微言）](https://poetize.cn/article/86)。

### 资源聚合
详情请见：[POETIZE - 资源聚合](https://poetize.cn/article/85)。

### 文件服务
详情请见：[POETIZE - 文件服务](https://poetize.cn/article/84)。

