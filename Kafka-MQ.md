## Overview
Kafka is an open-source distributed event streaming platform. For high-performance data pipelines, streaming analytics, data integration, and mission-critical applications.

## Roles
1. Producer: 消息的推送者
2. Consumer：消息的消费者
3. Broker： Kafka server
4. Topic: 一个topic中保存同一类消息
5. Partition： 每一个topic中可以有多个partition. 每个partition在存储层面是append log文件。
6. Offset：一个partition对应一个磁盘文件，而消息在文件中的位置称为offset(偏移量).

## Kafka Data Workflow
![image](https://github.com/FL-LearningGroup/SoftwareMiddleware/blob/main/kafka-dataworkflow.jpg)
