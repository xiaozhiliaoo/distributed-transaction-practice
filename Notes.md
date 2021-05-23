这篇文章非常好，值得反复阅读：
https://www.alibabacloud.com/blog/an-in-depth-analysis-of-distributed-transaction-solutions_597232
https://zhuanlan.zhihu.com/p/183753774
https://blog.csdn.net/youanyyou/article/details/115222258
数据库本身支持吗？
分库分表，newsql， 事务：spanner
分布式事务实现方案
基于数据库资源层面
2PC 两阶段提交协议
3PC 三阶段提交协议
基于业务层面
TCC
数据源配置。
分布式事务的产生的原因：SOA，分库分表
mysql和oracle跨库
seata-server高可用部署，
seata console有吗？
分布式事务，DB层面事务，
数据源不在自己这里，
嵌套事务，能回滚吗？
表会无限增大吗？事务存储能放hbase吗？
seata 一个服务，里面多数据源，能回滚吗？
seata适合B端，C端如何呢？
seata竞品是什么？
tidb跨数据中心
B站搜索分布式事务。
spring事务新起线程，事务不生效吗？
https://www.bilibili.com/video/av328211129/
seata源码阅读挺好的。
支付宝  XTS, alibaba TXC(Taobao Transaction Constructor)
https://github.com/alibaba/fescar

TCC和DB

蚂蚁金服分布式事务实践解析:https://www.bilibili.com/video/av328211129/
分布式事务 Seata TCC 模式深度解析：https://www.bilibili.com/video/BV1pK411s7MS
分布式事务 Seata saga 状态机设计器使用教程：https://www.bilibili.com/video/BV15V411Z7f8

