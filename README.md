计算机组成原理



Resource:

- 计算机组成与系统结构第二版 清华大学出版社 杨若瑜等编著
- 深入理解计算机系统 第三版 Randal E.Bryant David R, O'Hallaron
- 15-213/18-213/15-513: Introduction to Computer Systems (ICS) 
  

Finished:


  ---
  - 第一章 计算机系统漫游
  - 第二章 信息的表示和处理
    - 信息存储及位级运算
    - 整数表示及运算
    - 浮点数 IEEE 754 单精度表示
  - 第三章 程序的机器级表示
    - Basic
    - Contro
    - Procedures
    - Data
    - Advanced topic
  - 第四章　存储器层次结构

    - 存储技术　　　　　［Ram,Disk,SSD,Locliaty(局部性)］
    - 存储器层次结构　
    - 高速缓存`cache` 　[直接相联．组相联．全相联．`cache`友好代码]
  - 第五章　链接`Linking`
    - 静态链接 目标文件 可重定位目标文件
    - 动态链接 重定位 共享库
  - 第六章 异常控制流 `Exception Control Flow`
    - 异常
      - 异常处理
      - 异常分类
    - 进程
      - 逻辑控制流 上下文切换
      - 私有地址空间 虚拟内存空间
    - 进程控制
      - 回收子进程 僵尸进程 `fork`和` execve`
    - 信号 `Sigal`
  - 第七章 虚拟内存
  - 第八章 动态分配
  - 第九章 系统级I/O 
    - Everything is File
    - 描述符表、文件表、v-node表
    - 标准I/O与系统级I/O
  - 第十章 UNIX网络编程
    - Tiny Server
  - 第十一章 并发编程
    - 并发类型
      - 基于进程的并发
      - 基于线程的并发
      - 基于I/O事务的并发
    - 并发的要求
      - 互斥
      - 同步
    - 调度共享资源
      - 生产者、消费者模型
      - 读、写模型（互斥）
      - 理发店模型
    - 并发带来的后果
      - 死锁、活锁
      - 竞争
      - 饥饿
      - 不安全线程
      - 可重入性
    - 信号量 `P V`操作

- LAB 
  - [x] CPP Lab (C Programming Lab: Assessing Your C Programming Skills)
  - [x] Data Lab
  - [x] Bomb Lab (4/6)
  - [x] Cache Lab (9/10)
  - [x] Shell Lab (10/10)
  - [x] Malloc Lab (10/10)
  - [x] Proxy Lab  (7/7)

