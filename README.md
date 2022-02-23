# C++学习路线
![](https://github.com/xiaoyoumax/Cpp-Study/blob/main/C%2B%2B%E6%8A%80%E6%9C%AF%E6%A0%88.jpg)
1. [常用语法学习](#1)
2. [进一步提高](#2)
3. [工程实践](#3)
4. [相关的必知必会知识](#4)
- <h4 id="1">常用语法学习：《深度探索C++对象模型》侯捷</h4>

  - 专注于C++面向对象程序设计的底层机制，包括结构式语意、临时性对象的生产、封装、继承、以及虚拟——虚拟函数和虚拟继承
  - *一旦你能够了解底层实现模型，你的程序代码将获得多么大的效率*
  - 一些C++11/17的书籍:
    - 《深入理解C++11：C++11新特性解析与应用》
    - 《深入应用C++11：代码优化与工程级应用》
    - 《C++17完全指南》
    - 《Cpp 17 in Detail》
- <h4 id="2">进一步提高：《提高C++性能的编程技术》</h4>

    - 学习常见惯用法和高性能编码实践
    - 强推!
- <h4 id="3">工程实践：《C++ API 设计》和《大规模C++程序设计》</h4>

  - 前者从细粒度地教你在实际开发中如何设计C++ API接口
  - 后者告诉你大型C++程序小到单个.h/cpp文件如何编写，大到大型C++项目如何组织的最佳实践。
  - 书中的技术可以实实在在用于一线开发。
- <h4 id="4">相关的必知必会知识</h4>

  - 汇编：建议一定要掌握
    - 《汇编（第三版）》王爽
    - 《老码识途 从机器码到框架的系统观逆向修炼之路》韩宏
  - 编译、链接与运行时体系知识
    - C++程序如何通过预处理、编译与链接等步骤最终变成可执行的二进制文件？
    - 操作系统如何识别一个文件为可执行文件？
    - 一个可执行文件包含什么内容？
    - 执行时如何加载到进程的地址空间？
    - 程序的每一个变量和数据位于进程地址空间什么位置？如何引用到？
  - 狭义的操作系统原理
    - 操作系统如何管理进程与线程？
    - 虚拟内存与物理内存之间的对应关系？
    - 何为内存映射文件？
    - 进程之间如何通信？
  - 这两者推荐：《程序员的自我修养》（ps：必看）、《Windows核心编程》
  - 多线程知识：
    - 使用VS调试器将你需要学习的多线程程序中断下来，在多线程面板，看看这个进程一共有多少个正在运行的线程，分析每个线程的作用，然后研究下这些线程在何时何地创建的，为什么需要创建新的线程？
    - 推荐：《C++服务器开发精髓》
  - 网络编程：Socket编程
    - 理解和掌握常用的基础socketAPI不仅可以最大化地去定制各种网络通信框架，更不用说使用市面上流行的网络通信库，最重要的是，他会是你排除各种网络疑难杂症坚实地技术保障。
    - 《TCP/IP网络编程》、《Linux高性能服务器编程》

