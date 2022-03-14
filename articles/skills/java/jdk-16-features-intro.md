---
title: 'JDK 16特性简介'
tags:
    - JDK概述
categories:
    - [JDK概述]
---  
  
  
  
  
##  JDK 16新特性说明
  
  
JDK 16于2021年3月16日正式发布GA版
  
OpenJDK 官网对 JDK 16新特性说明的访问地址:
http://openjdk.java.net/projects/jdk/16/
  
  
##  JDK 16新特性概览
  
  
| JEP | Feature                                       | 说明 |
|-----|-----------------------------------------------|-------------|
| 338 | Vector API (Incubator)                        | 向量API的支持(处于孵化阶段) |
| 347 | Enable C++14 Language Features                | 开启C++14语言特性 |
| 357 | Migrate from Mercurial to Git                 | 版本管理系统从Mercurial迁移到Git |
| 369 | Migrate to GitHub                             | 代码库迁移到GitHub |
| 376 | ZGC: Concurrent Thread-Stack Processing       | 更新ZGC中并发线程栈处理技术 |
| 380 | Unix-Domain Socket Channels                   | 支持Unix-Domain Stocket Channels |
| 386 | Alpine Linux Port                             | 支持Alpine Linux Port |
| 387 | Elastic Metaspace                             | 弹性的元数据空间 |
| 388 | Windows/AArch64 Port                          | 支持Windows/AArch64 Port |
| 389 | Foreign Linker API (Incubator)                | 外部链接API(处于孵化阶段) |
| 390 | Warnings for Value-Based Classes              | 对基本类型封装类的告警 |
| 392 | Packaging Tool                                | 打包工具 |
| 393 | Foreign-Memory Access API (Third Incubator)   | 外部内存访问API(处于第三孵化阶段) |
| 394 | Pattern Matching for instanceof               | 对于instanceof关键字的模式匹配 |
| 395 | Records                                       | Record类支持 |
| 396 | Strongly Encapsulate JDK Internals by Default | 默认对JDK内部API进行强制封装 |
| 397 | Sealed Classes (Second Preview)               | 封装类的支持(处于第二预览阶段) |
  
  
从以上表格中可以看出对Java语言本身比较有意义的改进是JEP 338、JEP 394、JEP 395和JEP 397
其中JEP 394和JEP 395从JDK 14中开始引进，现在经过一年多的发展和应用，终于在JDK 16中完成落地
  
IntelliJ IDEA 从 2021.1.x 版本开始支持JDK 16，下面将使用该版本进行JDK 16新特性的体验测试
  
##  JDK 16新特性体验
  
  
JDK 16的下载从Oracle官网下载，下载地址是:
https://www.oracle.com/java/technologies/javase-jdk16-downloads.html
  
安装过程不必多说，下面看一下JDK 16的版本:
```bash
$ java -version
java version "16" 2021-03-16
Java(TM) SE Runtime Environment (build 16+36-2231)
Java HotSpot(TM) 64-Bit Server VM (build 16+36-2231, mixed mode, sharing)
```
  


<br/>
<center>
<img src="http://coderap.gitee.io/images/logo/public-wechat-qrcode-8.jpg"/>
</center>