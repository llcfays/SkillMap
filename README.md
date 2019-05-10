一个自己学习计划的技能图谱，不完整的地方，会在学习的过程中不断完善。

希望未来能够顺利的完成它。

加油！！！

[我将会在我的博客同步](https://llcfays.github.io/)

---
# Dart
### Dart web
- [创建 web 项目](https://github.com/llcfays/Dart-web-simple/tree/master/quickstart)
### Flutter

# Java
### Java基础
- [Java Object类方法](https://llcfays.github.io/2019/04/09/Java/Java基础/JavaObject类方法/)
- String、StringBuffer、StringBuilder区别，StringBuffer 底部如何实现？String 可以被继承吗，为什么？
- String a=""和String a=new String("")的的关系和异同？String 的创建机制如何理解
- 为什么 Java 中的 String 是不可变的（Immutable）？字符串设计和实现考量？String不可变的好处？
- static关键字可以修饰什么？static使用的注意事项有哪些？static关键字的特点？使用static存在什么问题？
- static变量存储位置是哪里？静态变量的生命周期？静态变量何时销毁？静态引用的对象回收如何理解？
- 访问修饰符public,private,protected,以及不写（默认）时的区别？访问修饰符底层怎么实现访问权限管理？
- 静态变量和实例变量的区别？成员变量与局部变量的区别有那些？外部类和内部类有何区别，生命周期是怎样的？
- 如何实现对象克隆？克隆有哪些方式？深克隆和浅克隆有何区别？深克隆和浅克隆分别说的是什么意思？
- int和Integer的区别？装箱、拆箱什么含义？什么时候装箱/拆箱？装箱和拆箱是如何实现的？
- final，finally，finalize有什么不同？finally什么情况下不会被执行？java.lang 包下为什么要设置final？
- 为什么要用通配符？上界通配符和下界通配符注意要点？什么是无界通配符？如何理解泛型编译器类型检查？
- [HashMap原理，Hash冲突，并发集合，线程安全集合及实现原理](https://llcfays.github.io/2019/04/12/Java/Java基础/HashMap原理，Hash冲突，并发集合，线程安全集合及实现原理/)
- HashMap 和 HashTable 区别
- HashCode 作用，如何重载hashCode方法
- ArrayList与LinkList区别与联系
- GC机制
- Java反射机制，Java代理模式
- Java泛型
- 什么是泛型擦除，能否通过开发中实际案例说下？如何获取泛型的具体的类型【反射】？
- Synchronized原理
- Volatile实现原理
- 方法锁、对象锁、类锁的意义和区别
- 线程同步的方法：Synchronized、lock、reentrantLock分析
- Java锁的种类: 公平锁、乐观锁、互斥锁、分段锁、偏向锁、自旋锁等
- ThreadLocal的原理和用法
- ThreadPool的用法和示例
- wait()和sleep()的区别
- 如何验证int类型是否线程安全？那些类型是线程安全的？举一个线程安全的例子【AtomicInteger】？
- Java序列话中如果有些字段不想进行序列化怎么办？Java序列化机制底层实现原理是怎样的？
- 原始数据类型和引用类型局限性？为何要引用基本数据包装类？基本数据类型一定存储在栈中吗？
- new Integer(123) 与 Integer.valueOf(123)有何区别，请从底层实现分析两者区别？
- instanceof它的作用是什么？在使用过程中注意事项有哪些？它底层原理是如何实现的，说说你的理解？

### Java高级
- Java虚拟机，Java运行，Java GC机制（可达性分析法，引用计数法）
- Java对象的完整生命周期
- JVM内存模型
- 进程间通信，线程间通信
- JVM类加载机制
- Java引用类型
- 设计模式：除常用设计模式之外，特别的，反射机制，代理模式
- HTTP协议和HTTPS协议
- Socket协议，Socket实现长连接
- [UDP协议](https://llcfays.github.io/2019/04/18/Java/Java高级/UDP协议/)
- TCP和UDP协议
- HTTP协议中GET和POST的具体实现
- 序列化和反序列化
- 线程池的实现原理
- 数据库基础知识：多表查询、索引、数据库事务

# 数据结构与算法
- [时间复杂度与空间复杂度](https://llcfays.github.io/2019/05/09/数据结构与算法/算法的时间复杂度和空间复杂度/)
- [数组](https://llcfays.github.io/2019/05/10/数据结构与算法/数组/)
- 栈和队列
- 数组和链表，自定义一个动态数组
- Hash表，及Hash冲突的解决
- 二叉树
- B+ B-树
- 基础排序算法：重点  快排、归并排序、堆排序（大根堆、小根堆）
- 快排的优化
- 二分查找与变种二分查找
- 哈夫曼树、红黑树
- 字符串操作，字符串查找，KMP算法
- 图的BFS、DFS、prim、Dijkstra算法（高阶技能）
- 经典问题：海量数据的处理  （10亿个数中找出最大的10000个数 TOP K问题）
- 分治算法
- 动态规划
- 贪心算法
- 分支限界法


# 设计模式

# Android

### Android 基础
- [Android Application 生命周期](https://llcfays.github.io/2019/04/17/Android/Android基础/AndroidApplication的生命周期)
- [Android Activity生命周期](https://llcfays.github.io/2019/03/28/Interview/Activity)
- Android Service、IntentService，Service和组件间通信
- Activity的onNewIntent
- Fragment的懒加载实现，参数传递与保存
- ContentProvider实例详解
- BroadcastReceiver使用总结
- Android消息机制
- Binder机制，共享内存实现原理
- Android 事件分发机制
- Android 多线程的实现：Thread、HandlerThread、AsyncTask、IntentService、RxJava
- ActivityThread工作原理
- 嵌套滑动实现原理
- RecyclerView与ListView(缓存原理，区别联系，优缺点)
- View的绘制原理，自定义View，自定义ViewGroup
- View、SurfaceView 与 TextureView
- 主线程Looper.loop为什么不会造成死循环
- ViewPager的缓存实现
- requestLayout，invalidate，postInvalidate区别与联系
- AndroidP新特性
- Android两种虚拟机
- ADB常用命令
- Asset目录与res目录的区别
- Android SQLite的使用入门

### Android 高级
- Android 基础难点
    - AIDL
    - Binder
    - 多进程
    - View的绘制流程
    - 事件分发
    - 消息队列
- Android 架构层源码
    - Android包管理机制，核心PackageManagerService
    - Window管理，核心WindowManagerService
    - Android Activity启动和管理，核心ActivityManagerService
    - 根Activity工作流程
    - Context关联类
- 各种原理、经典第三方库源码
    - 自定义LayoutManager，RecyclerView中如何自定义LayoutManager
    - VLayout实现原理，即如何自定义LayoutManager
    - Glide加载原理，缓存方案，LRU算法
    - Retrofit的实现与原理
    - OKHttp3的使用，网络请求中的Intercept
    - EventBus实现原理
    - ButterKnife实现原理
    - RxJava实现原理
    - Dagger依赖注入
    - 热修复实现原理，解决方案
    - 组件化原理和解决方案
- Android进程通信以及多进程开发
- Android动画机制
- Android 绘图原理
- Android 页面恢复
- 混合开发
- Android WebView
- Gradle、自动化构建、持续集成相关

### Android 系统
- Android 编译过程
- APP 启动加载过程
- Android 虚拟机 Android APP 运行的沙箱原则

### Android 架构

### Android 优化
- Android 性能调优
    + 性能瓶颈点
    + 性能调试及定位
    - 性能调优点
        + 同步改异步
        - 缓存
            + 单例模式
            - 缓存
                + 图片缓存
                + 线程池
                + View 缓存
                + IO 缓存
                + 消息缓存
                + 通知栏缓存
            + 其他
- 内存优化
    + 图片内存优化
    + 主动回收 Java 对象
    - 关闭资源对象
        + 数据库的关闭
        + 流等的关闭
        + bitmap 对象回收
- 代码优化
    + 数据类型选择
    + 数据结构选择
    + 避免创建不必要的对象
    + 对常量使用 Statci Final 修饰符
    + 避免内部 Getters/Setters
    + 复杂算法尽量用 C 完成
    + 减少不必要的全局变量
    + 不要过多指望 GC
    + 了解 Java 四种引用方式
    + 代码重构
    + 算法优化
- UI 优化
    + 控件优化
    - 布局优化
        - 抽象布局标签
        - 去除不必要的嵌套和 View 节点
        - 减少不必要的 infaite
        - 布局用 Java 完成比 XML 快
        - 多用自适应属性
        - 使用 XML 定义图片
- 网络优化
- 数据库优化
- 服务端优化
- 其他优化

# 其他

### 服务器开发相关

### 前端开发相关

### 开发调试各种工具
-  调试工具
    - 网络调试
        + Charles
        + Wireshark
        + Fiddler
        + tcpdump
        + Paw/Postman

    - 内存分析
        + monitor
        + MAT

    - Android tools
        + adb
        + draw9patch
        + hierarchyviewer
        + uiautomatorviewer

- 版本管理
    - Git
        + Git命令
        + Github/GitLab
    -  SVN

- CodeReview
    - Gerrit
    - Github pull request

- Bug/任务管理
    - Redmine
    - JIRA
    - Bugzilla
    - Teambition
    - Tower
- 编译工具
    - Gradle

- 持续集成
    - Jenkins
    - Travis CI

- 应用分发
    - 蒲公英
    - fir.im