# weixin446-springboot外卖系统小程序

## 前言

欢迎来到我们的weixin446-springboot外卖系统小程序项目。这是一个基于Java语言和Spring Boot框架的外卖系统，搭配微信小程序前端，为用户提供便捷的外卖订购体验。在此，我们将为您详细介绍本项目的相关内容。

## 内容介绍

本项目是一款功能完善的外卖系统，主要包括以下模块：用户模块、商家模块、订单模块、配送模块等。用户可以通过微信小程序查看附近的外卖商家，浏览商品信息，下单购买，并实时跟踪订单状态。商家则可通过后台管理系统进行商品管理、订单处理等操作。本系统致力于为用户提供一个方便、快捷、安全的外卖订购环境。

## 技术介绍

- 语言：Java
- 使用框架：Spring Boot、Spring MVC、MyBatis、微信小程序
- 前端技术：JS、Vue、CSS3、Uniapp
- 开发工具：IDEA/Eclipse、Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是一段关于查询外卖商家列表的核心代码：

```java
// 商家Service层方法
public List<Merchant> getMerchantListByUserId(Integer userId) {
    // 查询附近商家列表
    List<Merchant> merchantList = merchantMapper.getMerchantListByUserId(userId);
    return merchantList;
}

// 商家Mapper接口方法
public List<Merchant> getMerchantListByUserId(Integer userId);
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图
