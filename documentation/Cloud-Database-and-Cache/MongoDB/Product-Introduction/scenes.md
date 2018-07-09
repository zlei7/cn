# 应用场景

## 同城容灾
云数据库 MongoDB 实例支持跨可用区部署，以提供同城容灾。选择跨可用区部署时，实例的主从节点与隐藏节点分别部署在不同的可用区，当因不可抗力导致某一可用区整体不能服务时，可快速将服务切换到另一可用区。

![同城容灾场景](https://github.com/jdcloudcom/cn/blob/master/image/mongodb/mogno-001.png)


## 分服应用
依托云数据库 MongoDB 完善的备份机制和根据备份创建实例的能力，可快速将某一实例的数据同步到另一个数据库实例中，以满足游戏等分区类应用场景快速滚服和合服的需求。

![分服应用场景](https://github.com/jdcloudcom/cn/blob/master/image/mongodb/mongo-002.png)
