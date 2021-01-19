[![LibThread](https://img.shields.io/badge/AndroidAppFactory-LibThread-brightgreen)](#!doc/detail/lib-thread.md)[ ![Download](https://api.bintray.com/packages/bihe0832/android/lib-thread/images/download.svg) ](https://bintray.com/bihe0832/android/lib-thread/_latestVersion)

## 组件简介

线程管理模块，提供了不同优先级（系统级别的优先级）的线程（HandlerThread）及一个初始有五个线程的线程池（动态增长）

## 组件信息

- 仓库引用：

    仓库引用可以参考 [组件使用方式](http://android.bihe0832.com/#!start.md) 中添加依赖的部分

- 组件使用：

	   implementation 'com.bihe0832.android:lib-thread:+'

- 相关源码：

    [https://github.com/bihe0832/AndroidAppFactory/tree/master/LibThread](https://github.com/bihe0832/AndroidAppFactory/tree/master/LibThread)

## 组件功能

- ThreadManager

    - 提供了快速在新线程、主线程立刻或者延时执行的方法

    - 提供了不同优先级的HadlerThread，对外暴露Looper
