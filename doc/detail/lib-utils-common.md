[![LibCommonUtils](https://img.shields.io/badge/AndroidAppFactory-LibCommonUtils-brightgreen)](#!doc/detail/lib-utils-common.md)[ ![Download](https://api.bintray.com/packages/bihe0832/android/lib-utils-common/images/download.svg) ](https://bintray.com/bihe0832/android/lib-utils-common/_latestVersion)

## 组件简介

安全的类型转换、时间格式化、自增ID、随机数等

## 组件信息

- 仓库引用：

    仓库引用可以参考 [组件使用方式](http://android.bihe0832.com/#!start.md) 中添加依赖的部分

- 组件使用：

	   implementation 'com.bihe0832.android:lib-utils-common:+'

- 相关源码：

    [https://github.com/bihe0832/AndroidAppFactory/tree/master/LibCommonUtils](https://github.com/bihe0832/AndroidAppFactory/tree/master/LibCommonUtils)

## 组件功能

- ReflecterHelper

    - 基于状态机的 Java 反射工具类

- MathUtils    

    - 最大值、最小值、随机数、随机区间获取

- KVPair

    - 简单的 int-string 数据结构
    
- IdGenerator

    - 基于 AtomicInteger 的 ID 自增封装

- DateUtil

    - 各式时间转换，获取各种格式的时间，时间比较文字结果（几秒前，几分钟前）

- ConvertUtils

    - 各种安全的类型转换，如 string -> int
   
    - 数组、列表获取指定index的安全类型
