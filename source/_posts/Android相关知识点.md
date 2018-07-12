---
title: Android相关知识点
date: 2018-07-12 16:14:04
type: "Android"
tags:
- Android
- 开发
---

# Android用户界面定义 #
两种方式:
XML布局文件中通过XML属性进行控制
Java程序代码中通过调用方法进行控制

#基类
Drawable是Android提供的一个抽象基类，代表可以绘制出来的某种东西，Drawable包含了大量子类。
ViewGroup继承View类，可以当成普通View使用,但是ViewGroup平常当做容器类使用。
