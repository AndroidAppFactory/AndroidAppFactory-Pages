[![LibOS](https://img.shields.io/badge/AndroidAppFactory-LibOS-brightgreen)](#!doc/detail/lib-android-os.md)[![Download](https://api.bintray.com/packages/bihe0832/android/lib-android-os/images/download.svg) ](https://bintray.com/bihe0832/android/lib-android-os/_latestVersion)

## 组件简介

对于系统级别的常用功能的封装，例如获取进程名，当前系统版本，展示隐藏软键盘等

## 组件信息

- 仓库引用：

    仓库引用可以参考 [组件使用方式](http://android.bihe0832.com/#!start.md) 中添加依赖的部分

- 组件使用：

	   implementation 'com.bihe0832.android:lib-android-os:+'

- 相关源码：

    [https://github.com/bihe0832/AndroidAppFactory/tree/master/LibOS](https://github.com/bihe0832/AndroidAppFactory/tree/master/LibOS)

## 组件功能

- OSUtils

  - 根据进程ID获取进程名

    - 当前系统版本，API 版本，是不是Android Q
        
- DisplayUtil

  - 隐藏软键盘、虚拟导航判断

    - 获取屏幕（完整、可用）宽高等分辨率信息、状态栏宽高
    
    - dp，sp，px 等各类数据单位之间转换
