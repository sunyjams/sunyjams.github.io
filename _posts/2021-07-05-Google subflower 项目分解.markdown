---
layout: post
title:  "Google sunflower 项目分解"
date:   2021-07-05 18:01:00 +0800
categories: Android 架构
---

## Google sunflower 项目分解

1.Spotless 代码格式化工具

Github 地址：https://github.com/diffplug/spotless

2.Hilt 依赖注入工具

Google 对其的介绍和使用：https://developer.android.com/training/dependency-injection/hilt-android?hl=zh-cn

它在Dagger的基础上构建而成，而Dagger是Square公司开源的编译时依赖注入框架。

Dagger地址：https://github.com/google/dagger

3.Room 持久性库，Sqlite 的抽象层

4.LiveData 可观察的数据存储器类

5.ViewModel 管理界面数据的生命周期

6.Navigation Android 官方导航组件，提供Fragment的导航，给fragment创建了一个backstack

7.Paging 方便在RecyclerView中分页加载数据

8.WorkManager 异步任务管理

9.Glide 图片加载框架

10.Gson Json解析

11.Retrofit RESTful 的 HTTP 网络请求框架

12.Coroutines 协程，多线程并发处理，自动管理线程