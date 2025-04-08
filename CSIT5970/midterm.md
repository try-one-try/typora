[toc]

## HDFS

- 什么是HDFS
  - HDFS 是 Google 文件系统（GFS）的开源实现
  - An open-source implementation of GFS
  - HDFS 是为存储非常大的文件而设计的文件系统，支持流式数据访问模式，运行在廉价通用硬件组成的集群上
  - A filesystem designed for storing very large files with streaming data access patterns, running on clusters of commodity hardware
- HDFS设计假设
  - 硬件：使用廉价通用硬件，故障是常态（如硬盘、电源、人为错误）
  - Hardware：Uses cheap commodity machines, where failures are normal (disk, power, human errors)
