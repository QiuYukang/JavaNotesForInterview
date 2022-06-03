# JavaNotesForInterview

个人在面试准备过程中整理的笔记，包含常见的Java面试知识点、面试重点、面试技巧、面筋等，适合在准备过程中进行路线和内容的参考，赶时间的同学也可以直接看我的笔记复习。

主要包含以下内容（带 :star: 的是重点，必须看的）：

> <font color="red">建议使用Typora软件来阅读本文档，显示效果较好。</font>

- [0-面试记录和常见面试问题](0.个人面试记录.md)
- [1-Java基础:star: :star:](1.Java基础知识.md)
- [2-JVM:star: :star:](2.JVM相关笔记.md)
- [3-Java并发编程:star: :star:](3.Java并发编程相关笔记.md)
- [4-MySQL:star: :star:](4.MySQL相关笔记.md)
- [5-Redis](5.Redis相关笔记.md)
- [6-操作系统:star:](6.操作系统相关笔记.md)
- [7-计算机网络:star:](7.计算机网络相关笔记.md)
- [~~8-个人项目~~](8.项目相关笔记.md)
- [9-Web框架相关笔记](9.Web框架相关笔记.md)
- [10-数据结构和算法:star: :star:](10.数据结构和算法.md)
- [11-分布式系统设计](11.分布式系统设计相关笔记.md)

## Java面试准备流程

### Java语言

语言不是很重要，你学Java也可以投非Java的岗位，只要有一门熟悉的语言来面试就可以。

Java主要准备下面几点：

- **基础语法**：网上找个视频快速入门语法，Java集合源码学习参考这个开源项目[JCFInternals](https://github.com/CarpenterLee/JCFInternals)。<font color="red">非常不建议看《 Java核心卷I/II 》，太厚了真没人看得下去！</font>

- **JVM**：看书《深入理解Java虚拟机 第三版》前八章+最后两章

- **多线程并发**：《Java并发编程的艺术》全书

### 算法

<font color="red">新手不建议去看《算法导论》《算法 第三版》这种书，太厚了没几个人看得下去的</font>，直接看下基本的数据结构（数组、队列、堆、栈、二叉树、链表）然后开始刷题：

- [CS-Notes力扣题解](https://github.com/CyC2018/CS-Notes/blob/master/notes/Leetcode%20题解%20-%20目录.md)：按tag刷完接近200多道即可

-  《剑指offer》至少刷两遍、里面的题目必须非常熟练

- [CodeTop公司高频面试题](https://codetop.cc/home)：可以在面试前找对应公司和对应岗位的高频题目来做做

### 数据库

数据库的面试大多数都是问理论知识，很少让写SQL语句的。主要准备：

- MySQL：视频快速入门SQL基本增删改查语法、重点看书《MySQL技术内幕 InnoDB存储引擎》（3/4/7/8/9章略看）。
- Redis：[狂神说Redis视频](https://www.bilibili.com/video/BV1S54y1R7SB)快速入门Redis语法、《Redis设计与实现 第二版》全书看

### 计算机网络

主要掌握TCP/UDP/DNS/HTTP/网络安全（CSRF、SQL注入、XSS攻击）。

- 以前没学过：先看《 TCP/IP协议族》相关章节

- 以前学过：可以直接看我整理的笔记！！！

### 操作系统

主要掌握进程和线程、内存管理两大块的知识。

- 有时间的：看[清华陈俞老师的教学视频](https://www.bilibili.com/video/BV1uW411f72n)、《操作系统导论》全书、网上面筋
- 没时间的：直接看我整理的面筋也够了

### Web框架

spring/springmvc/springboot，看视频快速入门、会用，能写一个项目就可以，不是面试重点。没时间的话，如果有别的软件项目甚至可以不看Web框架。

### 其它加分点

- 设计模式：《HeadFirst设计模式》，常见设计模式（单例、工厂、代理、生产者消费者模式）需要掌握一下。
- 分布式、RPC框架、消息队列等知识
