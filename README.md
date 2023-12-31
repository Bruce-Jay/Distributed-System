# Distributed-System
2023年春分布式计算系统课程习题答案和编程题答案等

Question-Answer 课后习题答案，包含 1,2,3,4,5,10 章的习题，是本学期的教学内容

Other features coming soon~

## 关于教材

教材是徐辰老师，也就是本课的授课老师编著的《分布式计算系统》，高等教育出版社 2022 年版

<img src="Question-Answer/images/image-20230626201659032.png" alt="image-20230626201659032" style="zoom: 33%;" />

本书章节的组织结构，我认为是本书的最大特色：

1. 在**设计思想**方面主要回答以下问题: 该系统应对的应用场景如何? 为什么需要构造这个系统? 该系统所处理的数据模型是怎样的? 该系统采用何种计算模型? 如果系统支持迭代计算，则应采用何种迭代模型?

2. 在**体系架构**方面主要回答以下问题: 作为一个分布式系统，该系统包含哪些部件， 即由哪些进程或线程构成? 各个部件分别扮演怎样的角色? 系统中的各个部件以何种次序共同工作才能保障用户应用程序的顺利执行?

3. 在**工作原理**方面主要回答以下问题: 系统如何根据用户编写的应用程序生成相应的执行计划，以及是否可以进行优化? 面对数据密集型应用，系统如何减少数据I/O的代价 (此处I/O的代价表现为节点本地读写数据的磁盘I/O代价以及节点之间通过网络进行数据传输的代价，后者在分布式场景下显得尤为突出) ?

4. 在**容错机制**方面主要回答以下问题: 商用服务器集群中的节点发生故障是常见现象，系统如何保证在某些节点存在故障的情况下不影响用户应用程序的正常执行，即故障对用户透明? 早期的并行计算系统部署于高性能服务器甚至超级计算机中，通常无须考虑容错问题。容错机制是本书所讨论的分布式计算系统与早期分布式计算系统之间存在的显著差异。

5. 在**编程示例**方面主要回答以下问题: 使用系统的编程接口进行简单编程的一般步骤是怎样的? 编程过程是否存在通用的框架? 如何提高某些程序的性能? 使用不同系统实现同一个应用所编写的程序有何差异?
