# Java 学习/面试指南

<div align="center">  
<img src="http://my-blog-to-use.oss-cn-beijing.aliyuncs.com/18-11-16/49833984.jpg" width=""/>
</br>
</div>

## 目录

* [Java](#java)
  * [Java/J2EE 基础](#javaj2ee-基础)
  * [Java 集合框架](#java-集合框架)
  * [Java 多线程](#java-多线程)
  * [Java BIO,NIO,AIO](#java-bionioaio)
  * [Java 虚拟机 jvm](#java-虚拟机-jvm)
  * [设计模式](#设计模式)
* [数据结构与算法](#数据结构与算法)
  * [数据结构](#数据结构)
  * [算法](#算法)
* [计算机网络与数据通信](#计算机网络与数据通信)
  * [网络相关](#网络相关)
  * [数据通信\(RESTful,RPC,消息队列\)总结](#数据通信restfulrpc消息队列总结)
* [操作系统](#操作系统)
  * [Linux相关](#linux相关)
* [主流框架](#主流框架)
  * [Spring](#spring)
  * [ZooKeeper](#zookeeper)
* [数据存储](#数据存储)
  * [MySQL](#mysql)
  * [Redis](#redis)
* [架构](#架构)
* [面试必备\(Essential content for the interview\)](#面试必备essential-content-for-the-interview)
  * [备战面试\(Preparing for an interview\)](#备战面试preparing-for-an-interview)
  * [BATJ真实面经\(BATJ real interview experience\)](#batj真实面经batj-real-interview-experience)
  * [最常见的Java面试题总结\(Summary of the most common Java interview questions\)](#最常见的java面试题总结summary-of-the-most-common-java-interview-questions)
* [闲谈](#闲谈)
* [说明](#说明)

## 待办

* [ ] Java 8 新特性总结
* [ ] Java 多线程类别知识重构
* [x] BIO,NIO,AIO 总结 
* [ ] Netty 总结
* [ ] 数据结构总结重构
  
## Java

### Java/J2EE 基础

* [Java 基础知识回顾](https://github.com/Snailclimb/Java-Guide/blob/master/Java/Java基础知识.md)
* [J2EE 基础知识回顾](https://github.com/Snailclimb/Java-Guide/blob/master/Java/J2EE基础知识.md)
* [Java常见关键字总结：static、final、this、super](https://github.com/Snailclimb/Java-Guide/blob/master/Java/final、static、this、super.md) 

### Java 集合框架

* **常见问题总结：**
  * [这几道Java集合框架面试题几乎必问](https://github.com/Snailclimb/Java-Guide/blob/master/Java/这几道Java集合框架面试题几乎必问.md)
  * [Java 集合框架常见面试题总结](https://github.com/Snailclimb/Java-Guide/blob/master/Java/Java集合框架常见面试题总结.md)
* **源码分析：**
  * [ArrayList 源码学习](https://github.com/Snailclimb/Java-Guide/blob/master/Java/ArrayList.md) 
  * [【面试必备】透过源码角度一步一步带你分析 ArrayList 扩容机制](https://github.com/Snailclimb/JavaGuide/blob/master/Java/ArrayList-Grow.md)    
  * [LinkedList 源码学习](https://github.com/Snailclimb/Java-Guide/blob/master/Java/LinkedList.md)   
  * [HashMap(JDK1.8)源码学习](https://github.com/Snailclimb/Java-Guide/blob/master/Java/HashMap.md)  

### Java 多线程

* [并发编程面试必备：synchronized 关键字使用、底层原理、JDK1.6 之后的底层优化以及 和ReenTrantLock 的对比](https://github.com/Snailclimb/Java_Guide/blob/master/Java/synchronized.md)
* [并发编程面试必备：乐观锁与悲观锁](https://github.com/Snailclimb/Java-Guide/blob/master/EssentialContentForInterview/面试必备之乐观锁与悲观锁.md)
* [并发编程面试必备：JUC 中的 Atomic 原子类总结](https://github.com/Snailclimb/Java_Guide/blob/master/Java/Multithread/Atomic.md)
* [并发编程面试必备：AQS 原理以及 AQS 同步组件总结](https://github.com/Snailclimb/Java_Guide/blob/master/Java/Multithread/AQS.md)
* [BATJ都爱问的多线程面试题](https://github.com/Snailclimb/Java_Guide/blob/master/Java/Multithread/BATJ都爱问的多线程面试题.md)
* [并发容器总结](https://github.com/Snailclimb/Java_Guide/blob/master/Java/Multithread/并发容器总结.md)

### Java 虚拟机 jvm

* [可能是把Java内存区域讲的最清楚的一篇文章](https://github.com/Snailclimb/Java_Guide/blob/master/Java/可能是把Java内存区域讲的最清楚的一篇文章.md)
* [搞定JVM垃圾回收就是这么简单](https://github.com/Snailclimb/Java_Guide/blob/master/Java/搞定JVM垃圾回收就是这么简单.md)
* [《深入理解Java虚拟机》第2版学习笔记](https://github.com/Snailclimb/Java_Guide/blob/master/Java/Java虚拟机（jvm）.md)

### Java BIO,NIO,AIO

* [BIO,NIO,AIO 总结 ](https://github.com/Snailclimb/JavaGuide/blob/master/Java/BIO%2CNIO%2CAIO%20summary.md)
* [Java IO 与 NIO系列文章](https://github.com/Snailclimb/Java_Guide/blob/master/Java/Java%20IO与NIO.md)

### 设计模式

* [设计模式系列文章](https://github.com/Snailclimb/Java_Guide/blob/master/Java/设计模式.md)

## 数据结构与算法

### 数据结构

* [数据结构知识学习与面试](https://github.com/Snailclimb/Java_Guide/blob/master/数据结构与算法/数据结构.md)

### 算法

* [算法学习与面试](https://github.com/Snailclimb/Java_Guide/blob/master/数据结构与算法/算法.md)  
* [常见安全算法（MD5、SHA1、Base64等等）总结](https://github.com/Snailclimb/Java_Guide/blob/master/数据结构与算法/常见安全算法（MD5、SHA1、Base64等等）总结.md)
* [算法总结——几道常见的子符串算法题 ](https://github.com/Snailclimb/Java_Guide/blob/master/数据结构与算法/搞定BAT面试——几道常见的子符串算法题.md)
* [算法总结——几道常见的链表算法题 ](https://github.com/Snailclimb/Java_Guide/blob/master/数据结构与算法/Leetcode-LinkList1.md)   

## 计算机网络与数据通信

### 网络相关

* [计算机网络常见面试题](https://github.com/Snailclimb/Java_Guide/blob/master/计算机网络与数据通信/计算机网络.md)
* [计算机网络基础知识总结](https://github.com/Snailclimb/Java_Guide/blob/master/计算机网络与数据通信/干货：计算机网络知识总结.md)
* [HTTPS中的TLS](https://github.com/Snailclimb/Java_Guide/blob/master/计算机网络与数据通信/HTTPS中的TLS.md)

### 数据通信(RESTful,RPC,消息队列)总结

* [数据通信(RESTful、RPC、消息队列)相关知识点总结](https://github.com/Snailclimb/Java-Guide/blob/master/计算机网络与数据通信/数据通信(RESTful、RPC、消息队列).md)
* [Dubbo 总结：关于 Dubbo 的重要知识点](https://github.com/Snailclimb/Java-Guide/blob/master/计算机网络与数据通信/dubbo.md)
* [消息队列总结：新手也能看懂，消息队列其实很简单](https://github.com/Snailclimb/Java-Guide/blob/master/计算机网络与数据通信/message-queue.md)
* [一文搞懂 RabbitMQ 的重要概念以及安装](https://github.com/Snailclimb/Java-Guide/blob/master/计算机网络与数据通信/rabbitmq.md)

## 操作系统

### Linux相关

* [后端程序员必备的 Linux 基础知识](https://github.com/Snailclimb/Java-Guide/blob/master/操作系统/后端程序员必备的Linux基础知识.md)  
* [Shell 编程入门](https://github.com/Snailclimb/Java-Guide/blob/master/操作系统/Shell.md)  

## 主流框架

### Spring

* [Spring 学习与面试](https://github.com/Snailclimb/Java_Guide/blob/master/主流框架/Spring学习与面试.md)
* [Spring中bean的作用域与生命周期](https://github.com/Snailclimb/Java_Guide/blob/master/主流框架/SpringBean.md)
* [SpringMVC 工作原理详解](https://github.com/Snailclimb/JavaGuide/blob/master/主流框架/SpringMVC%20%E5%B7%A5%E4%BD%9C%E5%8E%9F%E7%90%86%E8%AF%A6%E8%A7%A3.md)

### ZooKeeper

* [可能是把 ZooKeeper 概念讲的最清楚的一篇文章](https://github.com/Snailclimb/Java_Guide/blob/master/主流框架/ZooKeeper.md)
* [ZooKeeper 数据模型和常见命令了解一下，速度收藏！](https://github.com/Snailclimb/Java_Guide/blob/master/主流框架/ZooKeeper数据模型和常见命令.md)
  
## 数据存储

### MySQL

* [MySQL 学习与面试](https://github.com/Snailclimb/Java_Guide/blob/master/数据存储/MySQL.md)
* [【思维导图-索引篇】搞定数据库索引就是这么简单](https://github.com/Snailclimb/Java_Guide/blob/master/数据存储/MySQL%20Index.md)

### Redis

* [Redis 总结](https://github.com/Snailclimb/Java_Guide/blob/master/数据存储/Redis/Redis.md)
* [Redlock分布式锁](https://github.com/Snailclimb/Java_Guide/blob/master/数据存储/Redis/Redlock分布式锁.md)
* [如何做可靠的分布式锁，Redlock真的可行么](https://github.com/Snailclimb/Java_Guide/blob/master/数据存储/Redis/如何做可靠的分布式锁，Redlock真的可行么.md)

## 架构

* [一文读懂分布式应该学什么](https://github.com/Snailclimb/Java_Guide/blob/master/架构/分布式.md)
* [8 张图读懂大型网站技术架构](https://github.com/Snailclimb/JavaGuide/blob/master/架构/8%20张图读懂大型网站技术架构.md)
* [【面试精选】关于大型网站系统架构你不得不懂的10个问题](https://github.com/Snailclimb/JavaGuide/blob/master/架构/【面试精选】关于大型网站系统架构你不得不懂的10个问题.md)

## 面试必备(Essential content for the interview)

### 备战面试(Preparing for an interview)

* [【备战面试1】程序员的简历就该这样写](https://github.com/Snailclimb/JavaGuide/blob/master/EssentialContentForInterview/PreparingForInterview/程序员的简历之道.md)
* [【备战面试2】初出茅庐的程序员该如何准备面试？](https://github.com/Snailclimb/Java-Guide/blob/master/EssentialContentForInterview/PreparingForInterview/interviewPrepare.md)
* [【备战面试3】7个大部分程序员在面试前很关心的问题](https://github.com/Snailclimb/JavaGuide/blob/master/EssentialContentForInterview/PreparingForInterview/JavaProgrammerNeedKnow.md)
* [【备战面试4】Java程序员必备书单](https://github.com/Snailclimb/Java-Guide/blob/master/EssentialContentForInterview/PreparingForInterview/books.md)
* [【备战面试5】Github上开源的Java面试/学习相关的仓库推荐](https://github.com/Snailclimb/Java-Guide/blob/master/EssentialContentForInterview/PreparingForInterview/JavaInterviewLibrary.md)
* [【备战面试6】如果面试官问你“你有什么问题问我吗？”时，你该如何回答](https://github.com/Snailclimb/Java-Guide/blob/master/EssentialContentForInterview/PreparingForInterview/如果面试官问你“你有什么问题问我吗？”时，你该如何回答.md)
* [【备战面试7】美团面试常见问题总结（附详解答案）](https://github.com/Snailclimb/Java-Guide/blob/master/EssentialContentForInterview/PreparingForInterview/美团面试常见问题总结.md)

### BATJ真实面经(BATJ real interview experience)

* [5面阿里,终获offer(2018年秋招)](https://github.com/Snailclimb/JavaGuide/blob/master/EssentialContentForInterview/BATJrealInterviewExperience/5面阿里,终获offer.md)

### 最常见的Java面试题总结(Summary of the most common Java interview questions)

* [第一周（2018-8-7）](https://github.com/Snailclimb/Java-Guide/blob/master/EssentialContentForInterview/MostCommonJavaInterviewQuestions/第一周（2018-8-7）.md) (为什么 Java 中只有值传递、==与equals、 hashCode与equals)
* [第二周（2018-8-13）](https://github.com/Snailclimb/Java-Guide/blob/master/EssentialContentForInterview/MostCommonJavaInterviewQuestions/第二周(2018-8-13).md)(String和StringBuffer、StringBuilder的区别是什么？String为什么是不可变的？、什么是反射机制？反射机制的应用场景有哪些？......)
* [第三周（2018-08-22）](https://github.com/Snailclimb/Java-Guide/blob/master/Java相关/这几道Java集合框架面试题几乎必问.md) （Arraylist 与 LinkedList 异同、ArrayList 与 Vector 区别、HashMap的底层实现、HashMap 和 Hashtable 的区别、HashMap 的长度为什么是2的幂次方、HashSet 和 HashMap 区别、ConcurrentHashMap 和 Hashtable 的区别、ConcurrentHashMap线程安全的具体实现方式/底层具体实现、集合框架底层数据结构总结）
* [第四周(2018-8-30).md](https://github.com/Snailclimb/Java-Guide/blob/master/EssentialContentForInterview/MostCommonJavaInterviewQuestions/第四周(2018-8-30).md) （主要内容是几道面试常问的多线程基础题。）

## 闲谈  

* [选择技术方向都要考虑哪些因素](https://github.com/Snailclimb/Java-Guide/blob/master/闲谈/选择技术方向都要考虑哪些因素.md) 
* [结束了我短暂的秋招，说点自己的感受](https://github.com/Snailclimb/JavaGuide/blob/master/闲谈/2018%20%E7%A7%8B%E6%8B%9B.md) 
* [【2018总结】即使平凡，也要热爱自己的生活](https://github.com/Snailclimb/JavaGuide/blob/master/闲谈/2018%20summary.md)
* [Java项目 Github Trending 月榜](https://github.com/Snailclimb/JavaGuide/blob/master/闲谈/JavaGithubTrending/JavaGithubTrending.md)

***

## 说明

### 介绍

*  **对于 Java 初学者来说：** 本文档倾向于给你提供一个比较详细的学习路径，让你对于Java整体的知识体系有一个初步认识。另外，本文的一些文章
也是你学习和复习 Java 知识不错的实践；
*  **对于非 Java 初学者来说：** 本文档更适合回顾知识，准备面试，搞清面试应该把重心放在那些问题上。要搞清楚这个道理：提前知道那些面试常见，不是为了背下来应付面试，而是为了让你可以更有针对的学习重点。

本文档 Markdown 格式参考：[Github Markdown格式](https://guides.github.com/features/mastering-markdown/)，表情素材来自：[EMOJI CHEAT SHEET](https://www.webpagefx.com/tools/emoji-cheat-sheet/)。
