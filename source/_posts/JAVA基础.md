---
title: JAVA基础
author: UyoAhz
avatar: 'https://q1.qlogo.cn/g?b=qq&nk=2496091142&s=640'
authorLink: /
authorAbout: 集中精神，以气御剪
authorDesc: 一个好奇的人
comments: true
photos:
  - 'https://blog-img-1258635493.cos.ap-chengdu.myqcloud.com/blogImg/img/Javadata1.png'
  - 'https://blog-img-1258635493.cos.ap-chengdu.myqcloud.com/blogImg/img/Javadata1.png'
abbrlink: 33701
date: 2021-07-02 18:27:57
categories:
tags:
keywords:
description:
---

byte     1字节               
short    2字节               
int      4字节               
long     8字节               
char     2字节（C语言中是1字节）可以存储一个汉字
float    4字节               
double   8字节               
boolean  false/true(理论上占用1bit,1/8字节，实际处理按1byte处理)       
JAVA是采用Unicode编码。每一个字节占8位。你电脑系统应该是 32位系统，这样每个int就是 4个字节
其中一个字节由8个二进制位组成
![](https://blog-img-1258635493.cos.ap-chengdu.myqcloud.com/blogImg/img/javadata.png)
Java一共有8种基本数据类型（原始数据类型）：     
类型  存储要求 范围（包含） 默认值 包装类
整 int 4字节（32位） -231~ 231-1 0 Integer
数 short 2字节（16位） -215~215-1 0 Short
类 long 8字节（64位） -263~263-1 0 Long
型 byte 1字节（8位） -27~27-1 0 Byte
浮点 float 4字节（32位） -3.4e+38 ~ 3.4e+38 0.0f Float
类型 double 8字节（64位） -1.7e+308 ~ 1.7e+308 0 Double
字符 char 2字节（16位） u0000~uFFFF（‘’~‘？’） ‘0’ Character
   （0~216-1（65535））  
布尔 boolean 1/8字节（1位） true, false FALSE Boolean

## 关键字
访问控制 
private、public、protected、default 

类、方法、变量修饰符 
abstract（抽象类）、class、extends、final、implement、interface、native、new、static、stricfp、synchronized、transient、volatile 


程序控制 
break、continue、return、do、while、if、else、for、instanceof、 switch、case、default 

异常处理 
try、catch、throw、throws 

包相关 
import、package 

基本类型 
boolean、byte、char、double、float、int、long、short、null、true、false 

变量引用 
super、this、void 

保留字 
goto、const

## 类的加载顺序
1.首先，需要明白类的加载顺序。 
(1) 父类静态代码块(包括静态初始化块，静态属性，但不包括静态方法) 
(2) 子类静态代码块(包括静态初始化块，静态属性，但不包括静态方法)
(3) 父类非静态代码块(包括非静态初始化块，非静态属性)
(4) 父类构造函数
(5) 子类非静态代码块(包括非静态初始化块，非静态属性)
(6) 子类构造函数
其中：类中静态块按照声明顺序执行，并且(1)和(2)不需要调用new类实例的时候就执行了(意思就是在类加载到方法区的时候执行的)
