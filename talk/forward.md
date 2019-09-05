### 数据库篇
* 为什么选用关系型数据库？OLTP和OLAP的场景理念
* 常用的DDL，DML，DCL
* 为什么需要事务？
* 事务的特性ACID
* 事务的隔离级别
* 事务的传播行为
* Mysql InnoDB默认的隔离级别，什么场景会调整隔离界别，传播行为有什么作用
* 索引，然后去讨论到B+，B、B+、B*树的区别，然后说到mysql的性能瓶颈
* Mysql数据存储在硬盘是什么格式，插入和查询运作方式，事务是怎么运作的
* Mysql 5.7+的主从复制优化

### Java Core
* OOP
* Error，checkedException and unCheckedException
* 在模块设计中如何设计对应的异常，选用checkedException 还是 unCheckedException
* 泛型擦除， ? extends X, ? super X, 如何获取容器对象中的泛型 instanceOf
* 集合
* IO
* 超类Object的方法hashCode()和equals()
* 枚举和注解

### 多线程，反射，代理，函数式，多Module
* 多线程集合类
* 死锁，锁死
* 超类Object的方法wait()和sleep()
* Java8的多线程优化
* 线程池的参数，work flow
* CPU密集型和IO密集型
* Future
* Fork-Join
* interrupt InterruptedException 以及此异常的处理
* parallelStream()
---------
* 反射，反射的必须条件
* JDK动态代理 CGLib
* Lambda，Stream，Option
* 接口的演进
* Java9 ， 10 ， 11 ，12的feature

### JVM
* JDK7的内存划分
* JDK8的内存划分
* tomcat内存调优
* JMM
* Hotspot的一些特性
* 内存分配优化CMS
* 垃圾回收算法
* 垃圾收集器
* Full GC
* StackOverflowError  OutOfMemoryError
* JIT，client模式和server模式
* 静态分派和动态分派

### 设计模式
* 设计原则
* 设计模式，伪代码orUML

### 数据结构 & 算法
* 队列，数组，链表，哈希表，堆，树
* 排序算法
* 二分查找
-------
* 两个栈实现先进先出

### 手写代码(伪代码)
* JDBC
* 生产者消费者
* 设计模式
* 算法

### redis
* 数据类型
* 高可用数据分片存储
* 哨兵算法
* 跳表

### MQ
* topic机制
* partition
* route
* 如何保证数据不重复消费
* 如何保证数据消费感知
* MQ(无论哪种)在具体的硬盘消息是以什么格式存在的

### 分布式事务
* 没研究过

### 协议
* Http和Https
* TCP IP协议层 / OSI协议层
* 常见的协议

### 框架(其实不想总结这个的)
* Mybatis如何避免SQL注入
* Spring容器里的类在使用的时候，是单例，还是new，还是clone，还是别的？
