# 一 源码下载
官方提供的所有历史版本的下载地址 https://archive.apache.org/dist/hadoop/common/
在hadoop-1.0中，MapReduce由编程模型（map/reduce）、调度系统（JobTracker 和TaskTracker）和数据处理引擎（MapTask 和ReduceTask）等模块组成，而hadoop-2.0中新增YARN 完成来完成资源调度功能（原编程模型和数据处理引擎不变），自身仅包含非常简单的任务分配功能。本例采用hadoop-1.0.0。
步骤：
## 1 下载hadoop-1.0.0.tar.gz  这是包含源代码的发行版本，用IntelliJ-IDEA-2017打开；
## 2 下载JDK 1.6版本；
## 3 IntelliJ-IDEA-2017已经集成了ANT,在setting->Plugins->中输入Ant,勾选Ant Support即可
![image](https://github.com/Miraclelucy/funny-hadoop/blob/master/images/ch01_01.png)
## 4 导入下载好的hadoop-1.0.0项目,使用AntBuild构建项目的build.xml文件
![image](https://github.com/Miraclelucy/funny-hadoop/blob/master/images/ch01_02.png)

# 二 hadoop-1.0.0源码结构目录
![image](https://github.com/Miraclelucy/funny-hadoop/blob/master/images/ch01_03.png)

