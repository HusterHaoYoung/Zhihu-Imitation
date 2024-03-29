# 低知乎问答系统

Springboot+Mybatis开发，数据库使用Mysql+redis，异步框架处理消息推送。

***

**功能**

[1. 用户登录注册管理](#用户注册登录管理)

[2. 问题管理](#问题管理)

[3. 评论中心与站内信](#评论中心与站内信)

[4. Redis实现赞踩功能](#Redis实现赞踩功能)

[5. 异步设计](#异步设计)

[6. 关注功能和粉丝列表页实现](#关注功能和粉丝列表页实现)

[7. timeline新鲜事实现](#timeline新鲜事实现)

***

## 用户注册登录管理

**登陆界面：**

![img](https://github.com/HusterHaoYoung/Zhihu-Imitation/blob/master/src/main/resources/static/images/img/log.png)

**导航栏（登陆前）：**

![img](https://github.com/HusterHaoYoung/Zhihu-Imitation/blob/master/src/main/resources/static/images/img/navigator1.png)

**导航栏（登陆后）：**

![img](https://github.com/HusterHaoYoung/Zhihu-Imitation/blob/master/src/main/resources/static/images/img/navigator2.png)

**个人信息导航：**

![img](https://github.com/HusterHaoYoung/Zhihu-Imitation/blob/master/src/main/resources/static/images/img/navigator3.png)

## 问题管理

**问题发布：**

![img](https://github.com/HusterHaoYoung/Zhihu-Imitation/blob/master/src/main/resources/static/images/img/question.png)

**敏感词过滤（内容已被过滤）：**

![img](https://github.com/HusterHaoYoung/Zhihu-Imitation/blob/master/src/main/resources/static/images/img/sensitive.png)

**问题广场（首页显示）：**

![img](https://github.com/HusterHaoYoung/Zhihu-Imitation/blob/master/src/main/resources/static/images/img/page.png)

## 评论中心与站内信

**评论页面：**

![img](https://github.com/HusterHaoYoung/Zhihu-Imitation/blob/master/src/main/resources/static/images/img/comment.png)

**个人站内信：**

![img](https://github.com/HusterHaoYoung/Zhihu-Imitation/blob/master/src/main/resources/static/images/img/message.png)

**站内信详情：**

![img](https://github.com/HusterHaoYoung/Zhihu-Imitation/blob/master/src/main/resources/static/images/img/message1.png)

## Redis实现赞踩功能

**评论的赞踩：**

![img](https://github.com/HusterHaoYoung/Zhihu-Imitation/blob/master/src/main/resources/static/images/img/like.png)

## 异步设计

**异步设计原理：**

![img](https://github.com/HusterHaoYoung/Zhihu-Imitation/blob/master/src/main/resources/static/images/img/asynchronous.jpg)

## sns关注功能和粉丝列表页实现

**用户关注：**

![img](https://github.com/HusterHaoYoung/Zhihu-Imitation/blob/master/src/main/resources/static/images/img/profile.png)
**关注列表：**

![img](https://github.com/HusterHaoYoung/Zhihu-Imitation/blob/master/src/main/resources/static/images/img/follow.png)

**问题关注：**

![img](https://github.com/HusterHaoYoung/Zhihu-Imitation/blob/master/src/main/resources/static/images/img/followQuestion.png)

## timeline新鲜事实现

**新鲜事（目前只有关注、评论问题被列为新鲜事）：**

![img](https://github.com/HusterHaoYoung/Zhihu-Imitation/blob/master/src/main/resources/static/images/img/feed.png)
