## 1. A Reinforcement Learning Approach for Minimizing Job Completion Time in Clustered Federated Learning

[Link to PDF](./paper/A_Reinforcement_Learning_Approach_for_Minimizing_Job_Completion_Time_in_Clustered_Federated_Learning.pdf)

### 问题:

1. **不是独立同分布的数据在联邦学习模型训练时** 准确率大大降低且模型训练的训练时间大大变长.

2. **客服端所拥有的资源不同，导致计算能力和通信能力的异质性**。设备异构性决定了FL作业完成时间受到同步框架下最慢客户端的限制，这被称为离散效应。

### 方法:

1. 两阶段的聚类联邦学习模型
    * 聚类阶段： 捕捉设备的异构性（可能不同的机器规格不同）,建模一个最大的集群内方差最小化问题，解决集群里某些节点训练较慢就掉队的问题
    * 训练阶段： 同时考虑非独立同分布数据和集群内节点的掉队效应，建立任务完成时间最小化的模型，通过选择客户端和调整集群的迭代次数。

---

## xxx
