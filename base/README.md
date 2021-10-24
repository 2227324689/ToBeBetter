<img width="350" src="../README.assets/1566299350462.png">

[![license](https://img.shields.io/hexpm/l/plug.svg?style=flat-square)](https://github.com/2227324689/ToBeBetter/blob/master/LICENSE) [![origin](https://img.shields.io/badge/origin-%E5%92%95%E6%B3%A1%E5%AD%A6%E9%99%A2-yellowgreen.svg?style=flat-square)](https://www.gupaoedu.com) [![blog](https://img.shields.io/badge/blog-%E5%8D%9A%E5%AE%A2-orange.svg?style=flat-square)](https://istio.tech) [![author](https://img.shields.io/badge/author-Mic-blue.svg?style=flat-square)](#) [![Gpmall](https://img.shields.io/badge/linked-gpmall-red.svg?style=flat-square)](#) [![community](https://img.shields.io/badge/community-%E6%8A%80%E6%9C%AF%E7%A4%BE%E5%8C%BA-lightgrey.svg?style=flat-square)](https://gper.club)

# Java基础类面试题

JavaEE基础，是面试必问的领域，很多人不理解，这些基础性的东西，平时工作中几乎用不到，但是为什么面试的时候总爱问。一栋房子能起多高，是由下层的基础建设以及地基决定的。

同样工作3年，同样用ssm框架、同样用mysql数据库。在面试官眼里，如何区分你写的CRUD比别人更有价值？同样3年经验你要求20K，他只要15k，为什么要选择你而不选择一个比较划算的人？ 

作为面试官，技术的深度和自身对技术的见解是区分一个人能力强弱的因素之一。同时，平常使用得很少的技术你能有很深刻的理解，说明你对技术是热爱的，一个热爱技术的人至少不会写出太多的bug，而不会因为工作的996而抱有负面的情绪。

Java基础类的面试，我主要从以下几个方面进行整理和收集。

| ![1566383567493](../README.assets/1566383567493.png) | ![1566383600147](../README.assets/1566383600147.png) | ![1566383632180](../README.assets/1566383632180.png) | ![1566383677895](../README.assets/1566383677895.png) | ![1566383711068](../README.assets/1566383711068.png) |
| :--------------------------------------------------: | :--------------------------------------------------: | :--------------------------------------------------: | :--------------------------------------------------: | :--------------------------------------------------: |
|        [JavaSE基础面试题](#JavaSE基础面试题)         |      [Java并发编程面试题](#Java并发编程面试题)       |           [JVM常见面试题](#JVM常见面试题)            |            [网络IO面试题](#网络IO面试题)             |       [Java 8新特性面试题](#Java8新特性面试题)       |



# JavaSE基础面试题

[[0] new String("abc")创建了几个对象](JavaSE基础面试题/0.md)

[[1]两个对象值相同(x.equals(y) == true)，但是可能存在hash code不同吗?](JavaSE基础面试题/1.md)

[[2]重载（Overload）和重写（Override）的区别。重载的方法能否根据返回类型进行区分](JavaSE基础面试题/2.md)

[[3]new Integer(112)和Integer.valueOf(112)的区别](JavaSE基础面试题/3.md)

[[4]深克隆和浅克隆的实现方式](JavaSE基础面试题/4.md)

[[5]类加载机制的原理](JavaSE基础面试题/5.md)

[[6]受检异常和非受检异常](JavaSE基础面试题/6.md)

[[7]如何理解抽象和接口](JavaSE基础面试题/7.md)

[[8]用过final关键字吗？它有什么作用](JavaSE基础面试题/8.md)

[[9]private修饰的方法可以通过反射访问，那么private的意义是什么](JavaSE基础面试题/9.md)

[[10]一个java文件有3个类，编译后有几个class文件](JavaSE基础面试题/10.md)

[[11]写一个你认为最好的单例模式](JavaSE基础面试题/11.md)

[[12]String a = "ab"; String b = "a" + "b"; a == b 是否相等](JavaSE基础面试题/12.md)

[[13]int a = 1; 是原子性操作吗](JavaSE基础面试题/13.md)

[[14]了解注解吗？请阐述注解的原理](JavaSE基础面试题/14.md)

[[15]String和StringBuilder、StringBuffer的区别？](JavaSE基础面试题/15.md)

# Java并发编程面试题

[[0]synchronized底层实现原理](Java并发编程面试题/1.md)

[[1]volatile作用，指令重排相关](Java并发编程面试题/2.md)

[[2]写一个死锁](Java并发编程面试题/3.md)

[[3]ReadWriteLock读写之间互斥吗?](Java并发编程面试题/4.md)

[[4]ReentrantLock的实现原理](Java并发编程面试题/5.md)

[[5]什么是Java中的CAS操作,AtomicLong实现原理？](Java并发编程面试题/5.md)

[[6]什么是Java指令重排序？](Java并发编程面试题/6.md)

[[7]CountDownLatch 与线程的 Join 方法区别是什么？](Java并发编程面试题/7.md)

[[8]Semaphore 的内部实现是怎样的？](Java并发编程面试题/8.md)

[[9]ThreadLocalRandom 是如何利用 ThreadLocal 的原理来解决 Random 的局限性？](Java并发编程面试题/9.md)

[[10]Thread类的sleep()方法和对象的wait()方法都可以让线程暂停执行，它们有什么区别?](Java并发编程面试题/10.md)

[[11]什么是线程池，线程池的实现原理是什么?](Java并发编程面试题/11.md)

[[12]简述synchronized 和java.util.concurrent.locks.Lock的异同？](Java并发编程面试题/12.md)

# JVM常见面试题

[[0]JVM的内存划分及作用](JVM常见面试题/0.md)

[[1]垃圾回收算法有哪些](JVM常见面试题/1.md)

[[2]GC收集器有哪些？CMS收集器和G1收集器的特点?](JVM常见面试题/2.md)

[[3]一个对象什么时候会被GC](JVM常见面试题/3.md)

[[4]如何排查内存泄漏的问题](JVM常见面试题/4.md)



# 网络IO面试题

[[0] 什么是序列化和反序列化，Java如何实现序列化](网络IO面试题/0.md)

[[1]阻塞IO、非阻塞IO、多路复用的含义和区别](网络IO面试题/1.md)

[[2]Java提供了几种类型的流，以及你是如何理解IO的](网络IO面试题/2.md)

[[3]Poll与ePool的区别？](网络IO面试题/3.md)



# Java8新特性

[[0]什么是lambda表达式? 什么情况下可以使用lambda](Java8新特性/0.d)

[[1]什么是流](Java8新特性/1.md)

[[2]Optional是什么? 什么时候使用?](Java8新特性/2.md)

[[3]函数式接口是什么?如何声明一个函数式接口?](Java8新特性/3.md)

[[4]接口中的默认方法和抽象方法有什么区别?](4.md)



































