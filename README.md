# News-Recommend-System
# 协同过滤在线新闻推荐网站系统

## 基于Java的协同过滤算法个性化在线新闻推荐系统

#### 介绍
新闻推荐系统，使用了基于用户的协同过滤推荐算法，根据评分数据计算推荐，同时还使用了新用户喜好标签进行混合推荐，及将两种推荐结果全部输出，解决了冷启动和数据稀疏性问题。同时采用基于统计的热点推荐和相关推荐等。采用爬虫收集新闻数据实时更新新闻数据和推荐结果。

Java+SSM(Spring+SpringMVC+Mybatis)+Mysql基于用户的协同过滤算法个性化新闻推荐系统，采用基于用户、项目、内容、聚类、混合的协同过滤推荐算法。

## 智能新闻推荐系统项目在线演示地址：
[前台演示地址（推荐用谷歌浏览器）：http://1.95.71.218:8090/WebNewsRecommendSystem/](http://1.95.71.218:8090/WebNewsRecommendSystem/)      
  
[后台演示地址（用谷歌浏览器）：http://1.95.71.218:8090/WebNewsRecommendSystem/admin/login](http://1.95.71.218:8090/WebNewsRecommendSystem/admin/login)    

[第二个新闻推荐前台演示地址：http://1.95.71.218:8081/NewsRecommendOnline/](http://1.95.71.218:8081/NewsRecommendOnline/)    

[第二个新闻推荐后台演示地址：http://1.95.71.218:8081/NewsRecommendOnline/admin/login](http://1.95.71.218:8081/NewsRecommendOnline/admin/login)     



 **源码获取：** [协同过滤算法个性化新闻推荐系统源码.zip](https://github.com/user-attachments/files/18202253/default.zip)


### 一、项目简介

**项目创新点**：
使用了基于用户的协同过滤推荐算法，根据评分数据计算推荐，同时还使用了新用户喜好标签进行混合推荐，及将两种推荐结果全部输出，解决了冷启动和数据稀疏性问题。同时采用基于统计的热点推荐和相关推荐等。

**冷启动**：一个新用户第一次登录，没有评分和收藏数据，那么没有办法进行个性化推荐；

**数据稀疏性**：会伴随项目的整个运行过程，比如：项目刚上线，新闻数据很多，但是用户及用户的评分、收藏数据较少，用户之间没有交集，那么有些用户就没有推荐结果


**1、开发工具和实现技术**
IDEA，jdk1.8，mysql5.5/mysql8，navicat数据库管理工具，tomcat7，SSM（spring+springmvc+mybatis）开发框架，jsp页面，javascript脚本，jquery脚本，bootstrap前端框架，layer弹窗组件，webuploader文件上传组件等。

**2、项目功能**

**前台用户包含**：注册、登录、注销、浏览新闻、搜索新闻、信息修改、密码修改、新闻评分、个人中心，新闻收藏、新闻评论、新闻浏览、用户喜好标签、热点推荐、个性化推荐新闻等功能；

**后台管理员包含**：数据统计、用户管理、新闻管理、新闻类型管理、评分管理、收藏管理、评论管理、用户喜好标签管理、浏览记录管理等。

**个性化推荐功能**：

**游客**：展示热点推荐（根据新闻被收藏数量降序推荐）

**登录用户**：同时进行 基于用户的协同过滤推荐算法进行推荐（根据评分数据）和 基于喜好标签的推荐（根据登录用户的喜好标签随机推荐）

### 系统功能展示

**1,前台用户系统**

**游客**：

![01首页](https://github.com/user-attachments/assets/cb153419-b2e7-47a1-9a81-fc5e7db10c03)

**登录用户**：

![01首页登录用户](https://github.com/user-attachments/assets/aef4ab51-4750-43a5-a919-2625ed17c823)
![02新闻详情](https://github.com/user-attachments/assets/a62339f9-3fa8-4cd8-8ecc-aac0775b1d5d)
![输入图片说明](03%E4%B8%AA%E4%BA%BA%E4%B8%AD%E5%BF%83.png)
![输入图片说明](04.png)
![输入图片说明](05.1.png)
![输入图片说明](05.png)
![输入图片说明](06.png)

**2，后台管理系统**
![输入图片说明](07.png)
![输入图片说明](08.png)
![输入图片说明](09.png)

**3，协同过滤推荐算法展示**
![输入图片说明](%E4%BB%A3%E7%A0%81.jpg)
![输入图片说明](10%E6%8E%A8%E8%8D%90%E5%B1%95%E7%A4%BA.png)
![输入图片说明](11%E7%AE%97%E6%B3%95.png)

 **源码获取：** [协同过滤算法个性化新闻推荐系统源码.zip](https://github.com/user-attachments/files/18202254/default.zip)
